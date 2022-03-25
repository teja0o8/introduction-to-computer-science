# Introduction-to-Computer-Science
 
week 0
 
Computers only underestand 0's and 1's. they cant count as high as 2, 3 and 4 in the same way as humans can. but they use the 1's and 0's in the same way. 
even though computers can only speak 0's and 1's and only under stand binary system, they can still count as high as we humans can and they fundamentally do it in the same way 
its just they have a small vocabulary. but why do they have a smaller vocabulary especially when they can do so much? well turns out that in the physical world,its just convenient to be able to represent only two states instead of 10. by the states, i mean, digits in this case.
its a lot easier in the human world, not to represent 10 possible values 0 or 9, but just two 0 and 1 and we could have called those digits anything we wanted but we humans just standaedized our numbers like that.

Binary Numbers: A binary number is a number expressed in the base-2 numeral system or binary numeral system, a method of mathematical expression which uses only two symbols: typically "0" and "1".

all the computers can store is 0s and 1s. from those 0s and 1s can we count higher so long as we mapping from binary to the numbers as we know as decimals. but of course we want our computers.we want to be able to express words and even other types of data. how do we do that? well, we need to come up with a standardization, a mapping from 0s and 1s or really just numbers, to the letters that we want 

ASCII code: ASCII (American Standard Code for Information Interchange) is the most common character encoding format for text data in computers and on the internet. In standard ASCII-encoded data, there are unique values for 128 alphabetic, numeric or special additional characters and control codes.

If your Mac or your PC comes with an Intel Inside, that means that your computer has inside of it a CPU(Central Proessing Unit). its a small device. when you look at it , you see is twi sides. the top isde is just a metal case and then, if you flip it around, you see the other side, which generally has a whole bunch of goladen pins that actually interconnect to a device inside of the computer known as mother board 
a mother board is a circuit board, so a big piece of silicon or plastic- like material that has a lot of lines running back and forth on it and often has socket a bunch of holes into which devices fit inside of a computer
what does it mean to be a CPU? the CPU is the brains of your computer. it's the thing in your computer thatdoes allthe work, all thethings.
what kind of thinking does a computer need to do? well, if you're feeding it all of those numbers and feeding it all of these letters, you might want to add or delete those letters. if the user is user is using a word processor and typibg new charecters or hitting delete adm so a computer needs to do all of that thinking and work for the human and the peace inside of the computer that des most of that work is indeed this device called the CPU.

the CPU'stoday areactually getting pretty fancy and inside of a CPU, typically is one or more cores and a core is really what's doing the work and it is the device inside of this device that actually can do adiition, subtraction, multiplication and division and other operations still loading information from memory.

it turns out that the fanciest of use today from intel, also supports something called hyperthreading, which means you might just have one CPU or one core but thanks to some technology built into the CPU.

well CPU is the brain. and the CPU on a system on a chip is there to the brain. but there's other components necessary inside of a computer and one of those things is called memory or random access memory.
RAM is a chip that slide into a little slot inside of your computer specifically on the motherboard and on the RAM there are various chips that actually store your data. specifically, they store your data in a volatile way, only when the power is on, when your cpu battery is running
where are those programs and files stored when the power is not on or when battery is dead or when coputer is not even plugged in? your computer dont lose all of your files and all of your programs  because your battery dies or your move a computer and thosefore unplug it from the wall. computers do have nonvolatile memory that sricksaround even when thepower is lost but it used a diffrent technology than RAM from that, it tends to use a disk or a hard disk. it stores a quite a bit more information that a stick of RAM

we use internet this everydays and odds are we have internet sonnectivity at the home these days or at work or at school. but how does it work?
every computer on the internet,it turns out has someething thats called IP address or internet protocal address which really is just a number dots. so four numbers separated by dots, and each of those numbers is a value between 0 and 255. so theres 265 total possibilites for each of tose values.
now it turns out theres other types of IP addresses today that are actually much bigger that this, but more on that in a bit so these IP addresses much like our postal addresses uniquely identify computers on the internet.
but where does this number come  from? well this is one of the things you get from your internet service or ISP your IP address.

theses days software is a bit fancier. there's actually smething called DHCP, Dynamic host Configuration Protocal, which is software that ISPs internet service providers run and really provide to you that allowerd your device.

what are called DNS servers? DHCP provides us with access to exactly that as well, so in addition to havng a DHCP server somewhere out there in the world from our ISP or maybe even our home and DNS servers or domain name system servers and thier purpose really is to convert domain names to corresponding IP addresses andthese DNS servers can help our computers talk to computers that have IP addresses.

every computer has an IP address, that IP addess typically comes from a special server called the DHCP server that lives within your ISP internet service provider.
theres also DNS servers in the world also controled by your ISP that convert domain names to IP address so that when you actually try to go to google.com our computer. 

computers are really good at recording and playing back audio and they really good at generating audio, and they can do so using any number of file formates. when a file format is just a way of storing zeros and ones on disk in a way that certain software knows how to interpret it
one of the earliest formats for audio and still one of the most common for uncompressed audio is called the wave file format, which can store data in an uncompresed form so that you have a really high quality versions of some audio recording
but also popular perhaps more popular among consumers is that known as MP3 or MPEG3, which is a file format for audio that uses compression to significantly reduce generally by a factor of more than 10 just hom manyy bits are neccessary to store song on your hard drive or on your music device or on your phone or any other form of technology.
audio compression is generally what known as lossy, L-O-S-S-Y. whereby your actually losing some of the quality or the fidelity of the music.
how do you think about the quality of these file recordings whether we are using any number of these file formats? well, you can think of it in terms of at least two parameters.
one is sampling frequency, the number of times per second that we actually take a digital snapshot, of what it is the human would otherwise be hearing in person so as to them represented digitally using zerros and one.
second parameter would be the bit depth, just how many bits are you using for that snapshot in time, some number of times per second,in order to represent the pitch and the volume and what it is the human is seeing.
what is a graphic? a whole bunch of dots otherwise known as pixels both horizontally and verticallly.each of those dots might just be represented by a single bit 1 and 0.
lets focus on color and the introduction of color in a digital context, RGB, red green blue. this three colors  that can mixed together really to give us any color that we want RGB
you can tell a computer to colorize each of those dots in a certain way. if we have none of these colors, we'll actually get a black dot, if we have all colors mixed together in equal form well get a white dot. 

week 01

ls - for list
ctrl+l - clear
mkdir - create directory
cd - change directory
cd.. - to move to parent directory
. single dot means current directory

data types in c . if we want a bigger integer we use long.if we want single charecter we use char.if we want a bollean value(true or false) we use bool.if wen want a floating point values(a real number with a decimal points) we use float. if we want even more numbers after the decimal point we use double.


What about printf?
If we have the ability now to store different types of data
and we have functions with which to get different types of data,
how might you go about printing different types of data?
Well, we've seen %s for string, %i for integer, %c for char,
%f for a float or a double, those real numbers I described earlier,
and then %li for a long integer.
So here's the first example of inconsistencies.
In an ideal world, that would just be %l and we'd move on.
It's %li instead in this case.
That's printf and some of its format codes.

make [file name] comapiles program.

Newer computers use more bits, older computers tended to use fewer bits.It's not necessarily standardized for all of these data types. it is using 32 bits for an integer.
An int is only using half of these, or we have two integers here on the stage. if you have 8 bits, 8 zeros and ones, you can count as high as 256.
8 bits gives you 256 permutations of zeros and ones.
32 gives you roughly how many.It's 2 to the 32 power.
So it's roughly 4 billion, 2 to the 32.
2 billion plus 2 billion is exactly 4 billion.
And that actually should fit in a 32-bit integer.
Mac, PC also like to support negative numbers.
And if you want to support both positive and negative numbers, that technically
means with 32-bit integers, you can count as high
as roughly 2 billion positive or 2 billion negative
in the other direction. That's still 4 billion, give or take, but it's only half as many in one direction or the other.

So how could I go about implementing a correct calculator?
Yeah, so not just li, which was for long integer.
I have to make one more change, which is to the data type itself.
Now we're counting as high as 4 billion.And we can go way higher than 4 billion.
 
int: The int data type is used for variables that will store integer values.So 1, 2, 3, negative 1, 2, 3, and so on. Integers, which is something you should keep in mind for the quiz, always take up four bytes of memory, which is 32 bits.There are eight bits in a byte.So this means that the range of values that an integer can store is limited by what can fit within 32 bits worth of information. Now as it turns out, it was long ago decided that we would split up that range of 32 bits into negative integers and positive integers,each getting half of the range.
So the range of values that we represent with an integer range from negative 2 to the 31st power to 2 to the 31st power minus 1, cause you also need a spot for 0.
So basically half of the possible values you can fit in an int are negative,and half are positive. And roughly here, this is about negative 2 billion to about positive 2 billion. Give or take a couple hundred million.So that's what you can fit in an integer variable.


Chars: chars are used for variables that will store single characters. Char is short for character. And sometimes you might hear people pronounce it as car. So characters always take up one byte of memory, which is just 8 bits. So this means that they can only fit values in the range of negative 2
to the seventh power, or negative 128, to 2 to the 7th power minus 1, or 127. Thanks to ASCII, it was long ago decided a way to map those positive numbers from 0 to 127 to various characters that all exist on our keyboard.
the character capital A maps to the number 65. And the reason for that is because that's what's it's
been assigned by the ASCII standard. Lowercase A is 97. The character 0 for when you actually type the character, not representing the number zero, is 48.


float: floating point numbers are also known as real numbers. They're basically numbers that have a decimal point in them. Floating point values like integers are also contained within 4 bytes of memory.
Now there's no chart here. There's no number line, because describing the range of a float
isn't exactly clear or intuitive. Suffice it to say you have 32 bits to work with. And if you have a number like pi, which has an integer part 3, and a floating point part, or decimal part 0.14159,
and so on, you need to be able to represent all of it the integer part and the decimal part.
Floats have a precision problem. We only have 32 bits to work with, so we can only be so precise with our decimal part. We can't necessarily have a decimal part precise to 100 or 200 digits, because we only have 32 bits to work with. So that's a limitation of a float.

double: double, which somewhat deals with this problem. Doubles, like floats, are also used to store real numbers, or floating point values.
The difference is that doubles are double precision.
They can fit 64 bits of data, or eight bytes.
we can be a lot more precise with the decimal point.
Instead of having pi to seven places maybe, with a float, we can maybe have it to 30 places. If that's important, you might want to use a double instead of a float. Basically, if you're working on anything where having a really long decimal place and a lot of precision is important, you probably want to use a double overfloat.

void: We can't create a variable of type void and assign a value to it. But functions, for example, can have a void return type. Basically, if you see a function that has a void return type, it means it doesn't return a value.
Printf does not actually return anything to you. It prints something to the screen, and it's basically
a side effect of what printf does. But it doesn't give you a value back. You don't capture the result and store it in some variable to use it later on.
It just prints something to the screen and you're done.
So we say that printf is a void function.
It returns nothing.
The perimeter list of a function can also be void. And you've also seen that quite a bit in CS50 too.

Data types and variables

bool: So the Boolean data type, bool, is used for variables that will store a Boolean value. If you've ever heard this term before, you might know that a Boolean value is capable of only holding two different distinct values. True and false.
It's kind of a surprise that this doesn't exist in C as it's built-in. And in many modern languages, of course, Booleans are a standard default data type. But in C, they're actually not.

String: Strings are really just words. They're collections of characters. They're words. They're sentences. They're paragraphs. Might be whole books, even. Very short to very long series of characters.

If you want to create a variable, all you need to do is two things.
First, you need to give it a type. The second thing you need to do is give it a name. Once you've done that and slapped a semicolon at the end of that line,you've created a variable.
So here's two examples.
Int number; char letter;.
I've created two variables.
The first, the variable's name is number. And number is capable of holding integer type values, because its type is int. Letter is another variable that can hold characters because its data type is char.

week 02

when we say you've been compiling your code with make, that's a bit of an oversimplification. Technically, every time you compile your code, you're having the computer do four distinct things for you. And this is not four distinct things that you need to memorize and remember every time you run your program, what's happening, but it helps to break it down into building blocks, as to how we're getting from source code, like C, into 0s and 1s. It turns out, that when you compile, quote-unquote, "your code," technically speaking, you're doing four things automatically, and all at once. Preprocessing it, compiling it, assembling it, and linking it. let's just call the whole process compiling.
But for a moment, let's consider what these step are So preprocessing refers to this. they're kind of special versus all the other code we've written, because they start with hash symbols, specifically. And that's sort of a special syntax that means that these are, technically, called preprocessor directives. Fancy way of saying they're handled special versus the rest of your code.

So what does it mean to preprocess your code?
The very first thing the compiler, clang, in this case, is doing for you when it reads your code top-to-bottom, left-to-right, is it notices, oh, here is hash include, oh, here's another hash include. And it, essentially, finds those files on the hard drive, cs50.h, stdio.h, and does the equivalent of copying and pasting them automatically into your code at the very top. Thereby teaching the compiler that gets string and printf will eventually exist somewhere. So that's the preprocessing step, whereby, again, it's just doing a find-and-replace of anything that starts with hash include. It's plugging in the files there so that you, essentially, get all the prototypes you need automatically.


What does it mean, then, to compile the results?
Compiling code in C means to take code that now looks like this in the computer's memory But it was just a few decades ago that, if you were taking a class like CS50 in its earlier form, we wouldn't be using C it didn't exist yet, we would actually be using this, something called assembly language. And there's different types of, or flavors of, assembly language. But this is about as low level as you can get to what a computer really understands, be it a Mac, or PC, or a phone, before you start getting into actual 0s and 1s. And most of this is cryptic. So there's some relationship to the C code we saw a moment ago. And then if I highlight these other things, these are what are called computer instructions. At the end of the day, your Mac, your PC, your phone actually only understands very basic instructions, like addition, subtraction, division, multiplication, move into memory, load from memory, print something to the screen, very basic operations. And that's what you're seeing here. These assembly instructions are what the computer actually feeds into the brains of the computer, the CPU, the central processing unit. And it's that Intel CPU, or whatever you have, that understands this instruction, and this one, and this one, and this one. And collectively, long story short, all they do is print hello, world on the screen.

assembling:To assemble code, that is just happening for you every time you run make or, in turn, clang, this assembly language, which the computer generated automatically for you from your source code, is turned into 0s and 1s. So that's the step that, when you compile your code, you convert it to source code-- from source code to machine code. Technically, that happens when you assemble your code. But no one in normal conversations says that, they just
say compile for all of these terms.

functions

functions: all the programs that we've been writing
have been written inside of main. They're pretty simple programs. You don't need to have all these branches and things going on. We can just fit it all inside of main and it doesn't get terribly overwhelming. as you begin to develop programs
independently, they're probably going to start to get a lot more than 10 or 15 lines. You might get hundreds or thousands or tens of thousands of lines of code. And it's really not that crazy a thought. As such, it's probably not a good idea to keep everything inside of main. It can get a little difficult to find what you're looking for if you do that.
Fortunately, though C, and pretty much every other programming language that might work with, allows us to write functions. Where there's a lot of synonyms for the same word. So we call the functions. But you might also hear them referred to as procedures, or methods, particularly, if you've ever done any object oriented programming before-- and don't worry if you haven't, not a big deal but in audit oriented languages are frequently called methods.
Sometimes they're called subroutines.
But they really all refer to the same basic idea.

When you declare a function what you're basically doing is telling the compiler, hey, just so you know, I am going to be writing a function later on and here's what it's going to look like. The reason for this is because compilers can do some weird things if they see a set of symbols that they're not familiar with. So we just give the compiler a heads up, I'm creating a function Function declarations generally if you're organizing your code in a way that others will be able to understand and make use of, you generally want to put all of your function declarations at the very top of your code, right before you start writing main even. And conveniently, there's a very standard form that every function declaration follows. They all pretty much look like this. There are three parts to a function declaration, return type, name, and argument list.

To call a function you need to do is pass it appropriate arguments, arguments of the data type that it expects, and then assign the return
value of that function and this assign the return value of that function to something of the correct type.


Variables and Scope

scope is a characteristic of a variable that defines from which functions that variable can be accessed.
There are two primary scopes in C, local variables and global variables.
local variables can only be accessed within the functions in which they're created. They can't be accessed by every other function that exists in your program, only the function in which it was created.
Global variables, on the other hand, can be accessed by any function in the program. And the reason for that is because they're not created inside of any particular function. We declare them outside of all of the functions, which means that every function knows where it is and can access and manipulate it.

Arrays

Arrays are a really fundamental data structure for any programming language that you will use. And they're really, really useful, particularly, as we'll see, in CS 50. We use arrays to hold values of the same data type at contiguous memory locations. That is to say, it's a way that we can group a bunch of integers together in memory or a bunch of characters or floats in memory really close together and work with them without having to give each one its own unique name, which can get cumbersome after a little while. one way to analogize arrays is to think about your local post, An array is a giant block of contiguous memory,Arrays have been partitioned into small, identically sized blocks of space, each of which is called an element,Each element of the array can store a certain amount of data,What can be stored in each element of the array is variables of the same data type, such as int or char,e can access each element of the array directly by index number.
In C, the elements of an array are indexed starting from 0, not from 1.
What does an array declaration look like?
There are three parts to an array declaration a type, a name, and a size.
This is very similar to a variable declaration, which is just a type and a name, the size element being the special case for an array,
So the type is what kind of variable you want each element of the array to be. Do want it to an array of integers? Then, your data type should be int.
Do you want it to be an array of doubles or floats? Data type should be double or float. The name is what you want to call your array.
Lastly, size, which goes inside of square brackets,is how many elements you would like your array to contain.

week 03

Linear Search: Linear search is an algorithm we can use to find an element in an array. An algorithm recall is a step-by-step set of instructions for completing a task. Iterate across the array from left to right, looking for a specified element.
In pseudocode, which is a more distilled version of this sentence, if the first element is what you're looking for, you can stop. Otherwise, move to the next element and keep going over and over until you find the element, or you don't.
what's the worst case scenario with linear search?
Well we have to look through every single element,either because the target element is the last element of the array, or the element we're looking for doesn't actually exist in the array at all.
What's the best case scenario?
Well we might find the element immediately. And how many elements do we then have to look at in the best case, if we're looking for it and we find it at the very beginning? We can stop immediately.

Binary Search: binary search is an algorithm we can useto find an element inside of an array. Unlike linear search, it requires a special condition be met beforehand, but it's so much more efficient if that condition is, in fact, met.
So what's the pseudocode steps for binary search?
We repeat this process until the array or, as we proceed through, sub arrays, smaller pieces of the original array, is of size 0. Calculate the midpoint of the current sub array. If the value you're looking for is in that element of the array, stop. if the target is less than what's at the middle, so if the value we're looking for is lower than what we see, repeat this process again, but change the end point, instead of being the original complete full array, to be just to the left of where we just looked. We knew that the middle was too high, or the target was less than the middle, and so it must exist, if it exists at all in the array,
somewhere to the left of the midpoint. And so we'll set the array location just to the left of the midpoint as the new end point. Conversely, if the target is greater than what's at the middle, we do the exact same process, but instead we change the start point to be just to the right of the midpoint we just calculated. And then, we begin the process again.

Bubble Sort: so bubble sort is an algorithm you can use to sort a set of elements. So the basic idea behind bubble sort is this. We generally want to move higher valued elements generally to the right, and lower valued elements generally to the left, as we would expect. We want the lower things to be at the beginning, and the higher things to be at the end.
what's the worst case scenario with bubble sort?
In the worst case the array is in completely reverse order, and so we have to bubble each of the large elements all the way across the array. And we effectively also have to bubble all of the small elements back all the way across the array, too. So each of the n elements has to move across all of the other n elements.
what's the best case scenario with bubble sort?
this is slightly different from selection sort. The array is already sorted when we go in. We don't have to make any swaps on the first pass. So we might have to look at fewer elements,

Selection Sort: Selection sort is an algorithm that, as you might expect, sorts a set of elements.
And algorithm recall is a step-by-step set of instructions for completing a task. In selection sort the basic idea is this, find the smallest unsorted element and add it to the end of the sorted list. Effectively what this does is build a sorted list, one element at a time.
So what's the worst case scenario here?
Well in the absolute worst case, we have to look over all of the elements of the array to find the smallest unsorted element, and we have to repeat this process n times. Once for each element of the array because we only, in this algorithm, sort one element at time

week 04

Hexadecimal
most Western cultures, as you probably are familiar, use the decimal system-- base 10, to represent numeric data. We have the digits 0, 1, 2, 3, 5, 6, 7,8,9. And if we need to represent values higher than nine, we can combine those digits using the notion of place value. So for 10, we have a 1 digit followed by a 0 digit and we intuitively understand that what we're doing there is we're multiplying the first 1 by 10, and then adding 0 for a total of 10. Computers do something pretty similar, as you're probably familiar, with the binary system base 2. The difference there being that there are only 2 digits to work with 0 and 1. And so our place values, instead of being one, ten, hundred, thousand, as they would be in the decimal system, are one, two, four, eight, and so on.
the hexadecimal system is a much more concise way to express the data on a computer's system. hexadecimal makes this mapping easy because a group of four binary digits(bits) is able has 16 different combinations and each of those combinations maps to a single hexadecimal digit. just like binary place values (1,2,4,8..) and decimal does too (1,10,100,1000,...),so does hexadecimal.
To convert a binary number to hexadecimal, group four binary digits(bits) together from right to left.

pointers
pointers provide an alternative way to pass data between functions.when we pass data by value, we only pass a copy of that data. if we use pointers instead, we have the power to pass the actual variable itself.
Evert file on computer lives on your disk drive, be it a hard disk drive(HDD) or a solid-state drive(SSD).Disk drives are just storage space; we cant directly work there. manipulation and use of data can only place in RAM, so we have to move data there. memory is basically a huge array of 8-bit wide bytes
So when we move things into memory, it takes up a certain amount of space. All of the data types that we've been working with take up different amounts of space in RAM. So every time you create an integer variable, four bytes of memory are set aside in RAM so you can work with that integer. You can declare the integer, change it, assign it.and you get four bytes
to work with for every integer that you create. Every character you create gets one byte. That's just how much space is needed to store a character. Every float, a real number, gets four bytes unless it's a double precision floating point number, which allows you to have more precise or more digits after the decimal point without losing precision, which take up eight bytes of memory. Long longs, really big integers, also take up eight bytes of memory.
what is a pointer?
A pointer is a data item whose value is a memory address. That was that zero x eight zero stuff going on, that was a memory address.That was a location in memory.
And the type of a pointer describes the kind of data you'll find at that memory address. The data type of a pointer describes what you will find at that memory address. pointers allow data structures and/or variables to be sharedc among functions. pointers make a computer environment more like the real world.
the simple pointer available to us in C in the NULL pointer, as we maight expect this pointer points to nothing. when you create a pointer and you don't set its value immediately, ypu shorld always set the value of the pointer to NULL. you can check whether a pointer is NULL using the equality operator(==).
another way to create a pointer is to simple extract the address of an already existing variable. we can do this with the adress extraction operator(&). if x is a int-type variable, then &x is a pointer-to-int whose value is the address of x. if arr is an array of double, then &arr[i] is a pointer-to-double who value is the address of the 1st element of arr.
the main purpose of a pointer is to allow us to modify or inspect the location to which it pointer. if we have a pointer-to-char called pc, then *pc is the data that lives at the memory address stroed inside the variable pc.
Call Stacks: when you call a function, the system sets aside space in memory for that function to do it necessary work. more that one function's stack frame may exist in memory at a given time. if main() calls move(), which then calls direction(), all three functions have open frames. these frames are arranged in a stack. the frame for thr most recently called function is always on the top of the stack. when a new function is called, a new frame is pushed onto the top of the stack and becomes the active frame.
when a function finishes its work, its frame is popped off of the stack, and the frame immediately below it becomes the new, active, function on the top of the stack. this function picks up immediately where it left off.

week 5

Structures are also sort of a data structure for collecting information, but it's not for collecting like values. It usually mixes different data types together inside of a single box. But it's not itself used to chain together or connect together similar items, like an array. Arrays are great for element look up, but recall that it's very difficult to insert into an array, unless we're inserting at the very end of that array. And the best example I have for that is insertion sort. If you recall our video on insertion sort, there was a lot of expense involved in having to pick up elements, and shift them out of the way to fit something into the middle of your array. Arrays also suffer from another problem, which is inflexibility. When we declare an array, we get one shot at it. We get to say, I want this many elements. Might be 100, it might be 1,000, it might be x where x is a number that the user gave us at a prompt or at the command line. But we only get one shot at it, we don't get to then say oh, actually I needed 101, or I needed x plus 20. Too late, we've already declared the array, and if we want to get 101 or x plus 20, we have to declare an entirely different array, copy all the elements of the array over, and then we have enough. And what if we are wrong again, what if we actually need 102, or x plus 40, we have to do this again. So they're very inflexible for resizing our data, but if we combine together some of the basics that we've already learned about pointers and structures, in particular using dynamic memory allocation with malloc, we can put these pieces together to create a new data structure a singly linked list we might say that allows us to grow and shrink a collection of values and we won't have any wasted space. we call this a linked list.
a singly linked list is comprised of nodes, nodes just being an abstract term that's a kind of structure and this node has two members, or two fields. It has data, usually an integer, a character float, or could be some other data type that you've defined with a type def. And it contains a pointer to another node of the same type. So we have two things inside of this node, data and a pointer to another node.
Hash table combine the random access ability of an array eith the dynamism of a linked list. to get this performance upgrade, we create a new structure whereby when we insert data into the structure, the data itseft gives us a clue about where we will find the data, should we need to later look it up. the trade odd id that hast tables are not great at ordering or sorting data, but if we dont care about that, then were good to go. a hash tables amounts to a combination of two things, first, a hash function, which returns an nonnegative integer value called a hash code. second, an array capable of softing data of the type we wish to place into the data structure.  the idea is that we run our data through the hash function, and then store the data inthe element of the array represented by the returned hash code.
a collison occurs when two peices od data, when run through the hash function yeild the same hash code. presumably we want to store both pieces of the data in the hash table, so we shouldn't simply overwrite the data that happened to be placed in there first. we need to find a way to get both elements into the hash table while trying to preserve quick insertion and lookup.
linear probing is subject to a problem called clustering. once there's a miss, two adjacent cells will contain data, making it more likely in the future that the cluster will frow. even if we switch to another probing tecnique, we still limlited. we can only store as much data as we have locations in our array.
how to define a hash function? 
A good hash function should: 
Use only the data being hashed
Use all of the data being hashed
Be deterministic
Uniformly distribute data
Generate very diffrent hash codes for very similar data
Tries combine structures and pointers together to store data in an intresting way. the data to be serched for int the tries is now roadmap. if you can follow the map from beginning to end the data exists in the trie. unlike with a hash table, there are no collisions and no two pieces of data have the same path. the map key-value pairs where the keys are four-digits years and the values are names of universities founded during those years. in a trie, the paths from a central root node to a leaf node, would be labeled with digitis of the year. each node on the path from root to leaf could hace 10 pointers emanating from it, one for each digit. to insert an element into the trie, simpley build the correct path from the root to the leaf.to search for an elemt in the trie, use successive digits to navigate the root. 

week 6

python is an example of a very commonly-used morden programming language. python is an excellent and versatitle language choice for making complex C operations much simpler. python is heavily inspired by C so thesyntax should be a shallow learning curve. 
to start writing python open up a file with the .py file extension.unlike a C program, whitch typically has to compiled before you can run it, anythin program can be run without explicity complliling it first.
variables have two big differences from C. We don't have to specify a type anymore so that's pretty cool.And we can declare them only by initialization. So you may recall in C that we could declare a variable by sayings for example int x semicolon, but not actually assign a value to it, not initialize it. In Python, we can only declare variables by initializing them. Python statements don't need to end with semicolons.
The conditional statements from C are all available for you to use, but they might look a teeny bit different now.
We have two kinds of loops in Python.So in C we had three.We had while loops, do while loops, and for loops.Here in Python, we don't have do while loops anymore. We only have the two, while and for, although they're a bit more flexible here.

So arrays are really where Python is goingto start to shine and show us some of the real advantagesit has over a language like C, which is a little more constricted in whatit can do with arrays because of two things.One, they're fixed size, and two, we can only store one type of variablein them.We can only store an array of all integers, all characters, all some structure that we created, and so on.In Python, we don't actually call them arrays.We call them lists, but they're effectively the same general idea,the same concept we're familiar with. They're not fixed in size.So similar to a linked list really we can grow and shrink them as we need,as our program demands more memory or less memoryto be consumed by the list the language is flexible enoughto allow us to do that.And we can always add more things on, splice or remove things from the middle pretty easily. So let's get in the habit of calling these things lists now instead of arrays. But to declare a list it's really pretty straightforward. Nums equals square brackets.
here's a new data type that we've never or a new kind of way of storing data in Python that we're not familiar with from C and that's called a tuple. So what a tuple is, it is an ordered, immutable set of data. tuples are ordered, immutable sets of data. they are great for associating collections od data sort od life a struct in c but where rhose values are unlikely to change. pythons also has build in support for dictionaries allowing you to specify list indices with words or phraded instead of intergers which you were restricted to in C. butt his creates a somewhat new problem. how do we iterate through a dictionary? we dont have indexes ranging from[0,n-1] anymore.
pythin has support for functions as well. like variables, we dont need to specify the return type of the function nor the data type of any parameters. all the functions are introduced with the def keyword, also no need for main; the interpeter reads from top to bottom.
python is an object-oriented programming language. an object is sort of analogous to a c structure. 

week 7

In order for us to build websites that are sort of more complex than justa page where they just go and see news, for example,we might need a database to store information,such as username and password combinationsso that a user attempts to log in.That log-in information is sent to the database.It is checked against information in the databaseto see whether that username password combination matches.And if so, it lets the user in.We might also store other stuff for users, like their shopping historyor really any other information that you mightwant to keep long-term for a user.Now, if you ever used programs like Microsoft Excel or Google Sheetsor Numbers, you're probably familiar with the basic idea of a database.A database consists of a couple of different levels of hierarchy.Within a database, we have tables. And within each of those tables, we have rows and columns.And if you are familiar with Excel

SQL( the structured query language) is a programming language whose purpose id to query a data base. MySQL is one open source platform on whitch you can establish the type of relational database that SQL is most adept at working with. many installations of SQL come with a GUI tool called phpMyAdmin whitch can be used to execute database queries in a more user-friendly way. after you create a database, the next thing you'll most likely want to do is create a table. the syntax doinf this is actually a bit awkward to do programmatically, at least at the outset and so this is where phpMyAdmin will come in handy. as part of the process of creating a table, you'll be asked to specift all of the coloumns in that table. thereafter, all you queries will refer to rows of the table. each columin of your SQL table is capable of holding data of a particular data type. unlike in C, the CHAR data type in SQL doent not refer to single character. rather, it is a fixed-length string. in most relational databases, including MySQL, you actually specify the fixed-length ad part of the type defination. a VARCHAR refers to a variable-length string. VARCHAR also require you to specify the maximum possible length of a string that could be stored in that column. SQLite has these data types as well but affiliates each with a "type affinity" to simplify things.
one other important consideration when constructing a table in SQL is to choose one coloum to be your promary key. primary keys enable rows of a table ro be uniquely and quickly identified. choosing your promary key appropriately can make subsequent operations on the table much easier. it is also possible to establish that is always guaranteed to be unique. we will primarily consider just four operations that one may perform on a table, Insert, Select, Update, Delete. insert adds information to a table. select extract information from a table.       
when definiting the column that ultimately ends up being your tables primary ley, it usally a good idea to have that column be an integer. moreover so as to eliminate that situatuin where you may accidently forget to specify a real value for the primary key column, you can configure that column to autoincrement, so it will pre-populate that column for you automatically when rows are added to the table.

 week 8

we've really been doing a lot of C. And when we've been running our programs, we have been running them from the command line. That's pretty much how the users have been interacting with the programs
that we write. They pick something to prompt, something happens in the terminal window,
and then it's done. Sometimes you might have persistent data that remains afterwards.
But that's pretty much it. It's at the command line. It's the only way the user can interact. From this point forward, we're going to start transitioning so that the users can interact with our websites. So we're going to be writing websites, which aren't written in C, but are written in a variety of other programming languages, including PHP, and it's sort of helper languages, HTML, CSS, and the like. So we're going to start talking about those things. Before we get into web programming itself. 
an IP address is basically a unique identifier of your computer on a network. Just like every home or office has a unique address to which one could send a mail. Similarly, every computer if it wants to receive data or send data, needs to have a unique address. So that when information is sent or received, it's being sent from or received to the correct location. This addressing scheme, as I said, is called IP addressing. IP is stands for Internet Protocol, which we'll talk about again shortly. Now, what does IP addressing look like? Well, the scheme basically was, when it was first implemented, to give every computer a unique 32-bit address. That's a lot of bits. That's 4 billion addresses. And generally, instead of using hexadecimal notation, which we've used previously in the context of pointers in C to talk about addresses, we usually represent IP addresses in a little bit more of a human friendly way, representing them as four clusters of 8 bits represented as decimal numbers. Because humans don't frequently speak hexadecimal, unless you're programming. But people who use the internet aren't necessarily programmers. And so making it easy and accessible for them to be able to talk about what their IP address is in case they maybe need to call up somebody to troubleshoot something, it's better to make it in the more common conventional decimal number format.
if every IP address is 32 bits, we have about billion to give out, a little more than 4 billion. But we can kind of see a problem, right? What's the world population right now?Well, it's somewhere north of 7 billion people. And in the Western world at least, most people have more than one device capable of internet connectivity. I have one right here. And I have another one in my pocket. And I have one back in my office.and so that's three. And that doesn't even count the ones that I have at home, too. And so that's kind of a problem, right? We have at least 7 billion people and only 4 billion addresses. And every device is supposed to be uniquely identified. We have developed some workarounds to deal with this problem, something called a private IP address, which we're not going to get into in this video. But basically, it allows further the web, the internet, to kind of fake out a little bit that you have a unique address by having private addresses and then funneling them through one single address, which is shared by many different computers. But that's really not a long term fix. Even that fixed isn't going to last forever. And so we need to have a different way of dealing with this. we had about 4 billion. But that's not going to be good enough, right? And so the way that it has been decided there we're going to deal with this is to make longer IP addresses.Instead of 32-bit addresses, we're going tohave 128-bit addresses. So instead of 4 billion addresses, we're going to have that huge number of addresses, which is 340 billion billion billion billion, so a lot of IP addresses. And this new scheme is called IPv6 is commonly how it's referred. The old scheme being IPv4.the way that we get an IP address is somewhere between our computer and the internet, that big internet out there, there's something called a DHCP server, a Dynamic Host Configuration Protocol server. It's a big mouthful of text. But really all it does is it assigns you an IP address. Your DHCP server has a list of addresses that it can validly assign. And it gives you one. That's pretty much all there is to it. Now before DHCP, this task of assigning addresses fell to a system administrator. So an actual person would have to manually assign your computer and address when you connected to a network. So DHCP just sort of automates this process of giving you an IP address. But that's how you get it. It's just a program running somewhere between you and the internet that has a bank of IP addresses that it can give out. And when you connect to the network, it gives you one.
the internet consists of a lot more than six networks. We can't afford to wire each network to each other network, especially considering some of these networks span oceans, right? If we're trying to connect to a network in Asia or in Europe, we're going to have to span an entire ocean. We're going to need to use wires at some point, but we want to minimize the number of wires we actually use. We don't want to send a million wires across the ocean,because they cost millions of dollars apiece to lie down. And so rapidly, we wouldn't be able to afford the internet anymore.  So we have to have another way for every network to talk to every other network or else we have pieces of the internet that are disconnected from other pieces of the internet. And that's not what we want. But we don't want to have them all wired together. And this is where routers come back into play. We can use routers in the following way. What if instead of every network being physically connected to every other network, we had these intermediary pieces, where the networks were connected to these intermediaries, which are connected to a few networks.So instead of having one connect to two, three, four, five, six, maybe one connects to a router, which maybe connects to one or two of those networks, but also maybe connects to other routers, which alsowill connect to those other networks.And the router's job is-- it contains information called a routing table that dictates where do I go if I see a particular IP address? If I see an IP address starting with four, I'm going to go this way. If I seen IP address starting with a 12, I'm going to go that way. We don't need to be connected physically to network number four or network number 12 in this example. We just know generally where we want to go.


week 9

pyhton is not just used for command-line programming, thought that's a majour use case. pyhton contains native fnctionality to support networking and more, enabling site beckends to be written in python. web frameworks make this process much easier, abstracting away the minutia of puthon's syntax and providing helper funcyions. one other technique that really might come in handy as you begin to build more complex websites, and that is using something called Ajax. So, so far, in our exploration of JavaScript, we've been limited to doing a couple of really simple things for the purpose of illustration, like you click a button, and something happens. Maybe the color changes on your site, or maybe a couple of words change. But the catch is everything we've been doing so far has been client side. It's all happening on our computer. We're never really talking to the outside world. We can, however, talk to the outside world and make changes on our website, have something happen that interact with the server, but maybe it doesn't reload our entire page. We want to create a more pleasant user experience. Ajax allows us to do that. Ajax used to stand for something called Asynchronous JavaScript in XML. That's a backronym. That's not really what it's called anymore. And actually, most commonly now, instead of XML, we use JSON. But Ajax has just been the name that's kind of stuck for the technique. And what Ajax allows us to do is to refresh, basically, sections of our page without the entire page. And if you're, for example, somebody who follows sports, for instance, you might see this if you're on a sports websit where scores of games that are going on currently are being updated, but the whole page doesn't refresh. That means that the page is basically taking advantage of Ajax to just update small portions of the page. The techniques that you can do with Ajax are pretty limitless. You can do a lot of different things with it. And we're going to focus on a very specific example where, again, we're clicking a button, and something happens. But the difference is this time when something happens, we're making a server request. We're making an outbound request from a page. It's not just happening on our machine But you can do things like updating, for example, the sports scores on a website that tracks that information or your email. You might notice that sometimes when you get a new email, your entire body of your page refreshes to put that new email at the top of your inbox, but the whole page doesn't refresh. That's happening with Ajax as well. But it's constantly running all the time. It's just basically querying forever. We're, again, just going to focus on clicking abutton and something happening, but that something being not just local to our machine anymore.


week 10








































  
