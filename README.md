# fizzbuzz-Assembly

My implementation of "fizzbuzz" using assembly-language. This is my first time using assembly.

### The Story

Yesterday, a friend came to me and asked "Do you 'fizzbuzz'?"
I replied, aghast, "Well, of course I fizzbuzz. I consider myself a computer scientist!"
They responded "No, but... *have* you fizzbuzzed?"
Thinking to myself, I let out the truth "...Well, I suppose I haven't"
"Then how can you possibly tell me you fizzbuzz when you haven't?"
I mulled this over... "Do I *not* fizzbuzz? What will I tell my parents?"
I came to the conclusion: I must fizzbuzz.
I proclaimed this to my friend "I *will* fizzbuzz. And, I won't just fizzbuzz; I'll fizzbuzz... in assembly!"
And thus, my journey began.

### The Problem

"Fizzbuzz" is a seemingly simple problem; iterate through the numbers 1-100 but, if the number you would print is
a multiple of 3, print "fizz" if it is a multiple of 5, print "buzz". If it is a multiple of both (15) print
"fizzbuzz" instead of the number.

A seemingly simple problem that is surprisingly unintuitive. Many people have trouble with the implementation,
especially in job-interviews because of the fact that redundent if-statements are actually necessary to the
structure of the code.

I have not read the solution so I plan to figure it out myself.

### The Research
First, I am going to try to solve the problem without looking up anything.
Without optimizing anything, a solution would be
```
For I in range 100:
	If (I is divisible by 3 or 5):
		If (I is divisible by 3 and 5):
			Print fizzbuzz
		Else if (I is divisible by 3):
			Print fizz
		Else: //It is divisible by 5
			Print buzz
	Else: //Not divisible by 3 or 5
		Print buzz
```

I have just begun my research of assembly relating to how I can write it, compile it, and run it. I will put my
research in this document. I plan to not read the optimal solution of fizzbuzz and see for myself how it goes.