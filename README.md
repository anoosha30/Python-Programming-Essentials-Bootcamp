# Python-Programming-Essentials-Bootcamp
Assignment - Python Programming Essentials Bootcamp

def calculate_simple_interest(principal, time, gender, senior_citizen):
    if gender == 'Female':
        if senior_citizen:
            rate = 8
        else:
            rate = 6
    else:
        if senior_citizen:
            rate = 7
        else:
            rate = 5
    
    interest = (principal * rate * time) / 100
    return interest

# Example usage
principal_amount = 100000
time_period = 3
gender = 'Female'
senior_citizen = True

simple_interest = calculate_simple_interest(principal_amount, time_period, gender, senior_citizen)
print("Simple Interest: ", simple_interest)
