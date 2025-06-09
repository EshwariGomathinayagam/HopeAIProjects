class multiFunctionClass():
    # function Tto find odd or Even Number
    def oddOReven():
        num=int(input("Enter a number "))
        if num % 2 ==0:
            message=(f"{num} is Even number")
        else:
            message=(f"{num} is Odd number")
        return message
            
    # function to find bmi
    def BMI():
        bmi= int(input("Enter the BMI Index: "))
        if bmi < 18:
            classification = "Underweight"
        elif bmi < 25: 
            classification = "Normal weight"
        elif bmi < 30: 
            classification = "Overweight"
        else:
            classification = "Very Overweight"
        return classification   
    
    # function to find people category
    def peopleCategoryByAge():
        age= int(input("Enter age: "))
        print(f"age {age}")
        if age < 18:
            peopleCategory = "Children"
        elif age < 35: 
            peopleCategory = "Adult"
        elif age < 59: 
            peopleCategory = "Citizen"
        else:
            peopleCategory = "Senior Citizen"
        return peopleCategory
    
    
    # function to find whether given number is positive or negative
    def positiveOrNegativeNumber():
        num=int(input("Enter any number"))
        print(f"Enter any number : {num}")
        if num < 0:
            message="No is negative"
        else:
            message="No is positive"
        return message
    
    
    # Function to find whether the given number is divisible by 5
    def divisibleByFive():
        num=int(input("Enter a number to check"))
        print(f"Enter a number to check : {num}")
        if num % 5 == 0:
            message="No is divisible by 5"
        else:
            message=("No is not divisible by 5")
        return message