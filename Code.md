# Code from the previous challenge!
```
#Welcome
print("Welcome to the Object Position Calculation!")
print("Please input the following information as rational numbers:\n")

#Input & Variables
obj_initial_position = float(input("Enter the object's initial position in meters: "))
obj_initial_velocity = float(input("Enter the object's initial velocity in meters/second: "))
obj_acceleration = float(input("Enter the object's acceleration in meters/second^2: "))
time_passed = float(input("Enter the time that has passed in seconds: "))

#Calculation
obj_final_position = float(obj_initial_position + (obj_initial_velocity * time_passed) + (0.5 * obj_acceleration * (time_passed * time_passed)))

#Output
print("\nThe object's final position after", time_passed, "seconds is:", obj_final_position)                    
```

- - -
[Back to home](https://github.com/james-struble/it-1000-midterm/blob/main/README.md)
