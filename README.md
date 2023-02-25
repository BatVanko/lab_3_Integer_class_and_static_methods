# lab_3_Integer_class_and_static_methods

Create a class called Integer. Upon initialization, it should receive a single parameter value (int). It should have 3 additional methods:
•	from_float(float_value) - creates a new instance by flooring the provided floating number. If the value is not a float, return a message "value is not a float"
•	from_roman(value) - creates a new instance by converting the roman number (as string) to an integer
•	from_string(value) - creates a new instance by converting the string to an integer (if the value cannot be converted, return a message "wrong type")


Test Code
first_num = Integer(10)
print(first_num.value)

second_num = Integer.from_roman("IV")
print(second_num.value)

print(Integer.from_float("2.6"))
print(Integer.from_string(2.6))


Output

10
4
value is not a float
wrong type
