# fizzbuzz-Assembly

My implementation of "fizzbuzz" using assembly-language. This is my first time using assembly.

## The Story
Yesterday, a friend came to me and asked "Do you 'fizzbuzz'?"
I replied, aghast, "Well, of course I fizzbuzz. I consider myself a computer scientist!"
They responded "No, but... *have* you fizzbuzzed?"
Thinking to myself, I let out the truth "...Well, I suppose I haven't"
"Then how can you possibly tell me you fizzbuzz when you haven't?"
I mulled this over... "Do I *not* fizzbuzz? What will I tell my parents?"
I came to the conclusion: I must fizzbuzz.
I proclaimed this to my friend "I *will* fizzbuzz. And, I won't just fizzbuzz; I'll fizzbuzz... in assembly!"
And thus, my journey began.

## The Problem
"Fizzbuzz" is a seemingly simple problem; iterate through the numbers 1-100 but, if the number you would print is
a multiple of 3, print "fizz" if it is a multiple of 5, print "buzz". If it is a multiple of both (15) print
"fizzbuzz" instead of the number.

A seemingly simple problem that is surprisingly unintuitive. Many people have trouble with the implementation,
especially in job-interviews because of the fact that redundent if-statements are actually necessary to the
structure of the code.

I have not read the solution so I plan to figure it out myself.

## The Research
#### Fizzbuzz
First, I am going to try to solve the problem independently.
With no optimization, one solution would be
```
For I = 0 to 100:
	If (I is divisible by 3 or 5):
		If (I is divisible by 3 and 5):
			Print "fizzbuzz"
		Else if (I is divisible by 3):
			Print "fizz"
		Else: //It is divisible by 5
			Print "buzz"
	Else: //Not divisible by 3 or 5
		Print I
```
Thinking it over, the following will also work and may be more intuitive.
```
For I = 0 to 100:
	If (I is divisible by 3 and 5):
		Print "fizzbuzz"
	Else if (I is divisible by 3):
		Print "fizz"
	Else if (I is divisible by 5):
		Print "buzz"
	Else:
		Print I
```
Comparing the two, I prefer the latter. Although the former is technically more efficient, since 'I' will usually 
not be divisibly by 3 nor 5, allowing us to skip most of the IF statements, the latter is more intuitive.

#### Assembly Language
I have never written in assembly, so everything is new to me. I will need to learn how to write it, compile it, and
run it. I will put my research in this document.

For this problem, other than the syntax of assembly, I will need to know:
 * How to print text to the console
 * How to do If/else if/else statements
 * How to do mathematical analysis (Ie. division)

Obviously, these are all pretty basic concepts so this should be fairly simple.

## Credits
#### Author
 * David Gourevitch
#### References
 * [TutorialsPoint](https://www.tutorialspoint.com/assembly_programming/)
 
##