# Operators

We will be learning this chapter in an interpreter, so start a session.

        ~ python3
        Python 3.6.0 (default, Jan 13 2017, 22:22:15)
        Type "help", "copyright", "credits" or "license" for more information.
	>>>

When you get this prompt, the interpreter has started.

Python has the following major operators:

<,>,=,==,>=,<=,!=,\*,+,-,\*\*, +=, -=, /=, \*=, in, and, not

## Assignment

`=` is the assignment operator. It creates variables and stores the values which you give at the right hand side to the left hand side.

	>>> a = 1
	>>> b = a

## Equality

`==` is the equality operator, it returns true if both the operands are same

	>>> a = 1
	>>> b = 1
	>>> a == b
	True

It is a classic mistake to use `==` when you really want to use `=` or vice versa. We encourage that you take extreme care to not misuse one when you want to use the other.

## Division

If you have been from a C background, you'll find Python's divide operator a bit different.

	>>> i = 10
	>>> i/2 # / returns the quotient (floating point number)
	5.0
	>>> i//2 # returns the quotient (integer number)
	5
	>>> i%2 # returns the remainder (integer number)
	0

## Power

`**` is the operator for power.
	
	>>> a = 12
	>>> a**2
	144

## List inclusion
	
	>>> a = [1,2,3]
	>>> 3 in a
	True

## Boolean operators

### not

	>>> not True
	False
	>>> a = 2
	>>> not a
	False
	>>> True==False
	False
	>>> True==True
	True

Negation works with Boolean variable type. `True` and `False` are fixed as far as variable names are concerned, you can't create a variable named True or False. It was possible in python2 to do so.

The `not` keyword negates your existing expression, anything that is None is evaluated to False, anything which is not null is evaluated to True.

### or

	>>> True or False
	True
	>>> False or False
	False

OR is true when either of the operand is true.

### and


AND is true when both the operands are true.

## Shortcut operators

+=, -=, /=, \*=

If you want to increment a variable by some value, instead of using `a = a + 2`, you can use `a+=2`. This is a shortcut method.
 There is no operator for `++` or `--`, you can use `a+=1` and `a-=1` for those purposes.

Along with this, you can use this syntax for other operations like -=, /=. In each of such operation you perform that operation and store it's value in the variable itself.

##### Links

|[Next](04-list-set-dict.md) | [Previous](03-01-understanding-variables.md) |  [Index](SUMMARY.md)
| ----| ----| ----| 