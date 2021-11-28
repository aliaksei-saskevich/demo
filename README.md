# demo
a = float(input('Please, enter  1st number'))
b = float (input('Then the 2nd one'))
act = str(input('Which action? (+ = / *)'))


if act == '+':
        answ = a+b
elif act == '-':
        answ = a-b
elif act == '*':
        answ = a*b
elif act == 'a/b':
        answ = a/b
elif act != ('+', '-', '*', '/'):
        act = str(input('Invalid! Which action? (+ = / *)'))
print (answ)
print ()
