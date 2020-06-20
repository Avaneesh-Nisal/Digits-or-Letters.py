input1 = input('Enter first input:   ')
input2 = input('Enter second input:  ')

if input1.isdigit() and input2.isdigit():
    print(int(input1) + int(input2))
elif not input1.isdigit() and not input2.isdigit():
    print(input1, input2)
else:
    print('One of the given values is a string and the other is integer. Try again later')
