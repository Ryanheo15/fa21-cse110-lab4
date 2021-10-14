1. line 12 will print 3 since this loop with run 3 times and each time the loop run, the variable will be incremented by one. The last iteration of the loop will have i be set to 3 and thus when printing it, will print 3.
2. Will print out 150, due to the variable discountedPrice being updated each time the loop runs and the final updated version will be 150 (due to the final price in array being 300 and multiplying by the discount (0.5)). This won't run into an error because var is function scoped and as long as a call to the variable remains within the function that it was originally declared, it wont give an errors. 
3. will print out 150, due to the final iteration of loop having discountedPrice be a value of 150. Doing calculations will result in final price with a value of 150. There will also be no errors due to the reasoning listed above 
4. Will return an array of discounted items. Due to each iteration of for loop adding the value of finalPrice to the discounted array
5. This will return an error due to i being declared using the let keyword. Since the i was declared using let, it will be scoped to the block. Since, `i` was trying to be called after the end of the for loop, it will give a referenceError
6. This will also return an error because discountedPrice was also declared using the let keyword and thus will be bounded to the scope of the block which is th for loop, thus when called outside of the for loop, it will give a referenceError
7. This prints out 150, since finalPrice was declared outside of the for loop initally with a let variable making this accessible anywhere within the function block. As the for loop runs, it ill will update the finalPrice variable and thus line 14 will return the last value that finalPrice was updated to, 150
8. Will return an array of discounted prices, discounted will be updated each time in the for loop and a new value will be added each time. 
9. Reference error since `i` was declared using let and is scoped to the for loop 
10. Prints 3, since length was declared and is just set as the length of the array
11. returns the modified version of discounted array, even though it was declared using const keyword, you're not actually redeclaring the constant but simply adding to it
12. a) student.name
    b) student['Grad Year']
    c) student.greeting()
    d) student['Favorite Teacher'].name
    e) student.courseLoad[0]
13. a) 32, concatenates 2 to string 3 
    b) 1, will convert string to number and subtract 2 since '-' is a numerical operation
    c) 3, adding null won't add anything to 3 
    d) 3null, concatentates 'null' to 3 since 3 is a string and interpretted the + as concatentation and thus interpreting null as a string
    e) 4, converts true into numerical value of 1
    f) 0, converts false to numerical value of 0 and adds null which is considered a nothing value 
    g) 3undefined, 3 is a string, will assume its concatentation when adding and thus convert undefined into a string
    h) NaN, due to being interpretted as a numerical operation and thus resulting in NaN which is basically an unknown for numbers
14. a) true,this is due to '2' being converted into a number
    b) false, this is due to comparing the first character of both strings
    c) true, this is due to '2' being converted to a number
    d) false, since the === checks if the datatypes matches as well 
    e) false, as true gets converted to value 1
    f) true, explicit Boolean conversion uses another set of rules for comparison
15. The difference between == and === would be that === checks the data types as well
17. The result will be will be pushing double of each element in the array into the newArray array. This is due to iterating through each of the elements through the use of a for loop and passing each element into the callback function which returns a number double the number that was passed in 
19. 1
    4
    3
    2