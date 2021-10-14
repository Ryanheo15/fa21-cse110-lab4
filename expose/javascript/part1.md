1. values added:  20
2. final result:  20
3. values added:  20
4. reference error occurs due to the fact that the variable result was declared using the 'let' keyword which effectively ties its scope to the block that it was declared, meaning it cannot be accessed outside of that block. Since the code tried to access the variable 'result' outside of the block that it was declared, it threw a refernece error saying that the variable has not been defined. 
5. Type error: This is due to the variable result being declared using the const keyword which means that the value of the variable cannot be changed. In line 7, the code tried changing the value of result by adding num1 and num2 but since result was declared using the const, it resulted in a type error and hence ending the code execution
6. Type error: Same reasoning as stated above