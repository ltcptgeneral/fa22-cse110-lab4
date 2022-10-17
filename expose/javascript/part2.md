1. The line prints: "3". This is because i is declared var so is still accessible outside the for loop and is 3 because that is the value of prices.length.
2. The line prints: "150". This is because discountedPrice is declared var so it is still accessible outside the for loop and is 150 because it is the value of prices[2] * (1-0.5) = 300 * 0.5 = 150.
3. The line prints: "150". This is the final value of finalPrice when iterating through the for loop which is Math.round(150 * 100) / 100 = 15000 / 100 = 150. 
4. The function returns the discounted array, which is the value of each value in price divided by discount and rouded to the nearest cent. In the inputs give, it will be [50, 100, 150].
5. The code returns the error: "ReferenceError: i is not defined". This is because using let restricts the scope of i to within the for loop, and the console.log is outside the for loop.
6. The code returns the error: "ReferenceError: discountPrice is not defined". This is because using let restricts the scope of discountPrice to within the for loop, and the console.log is outside the for loop.
7. The line prints: "150". This is because finalPrice is restricted in scope to the function, which allows the consol.log to reference the variable. 
8. The function returns the same array as in question 4 for the same reasons. It will be [50, 100, 150].
9. The code returns the error: "ReferenceError: i is not defined". This is for the same reason asquestion 5, the scope of i is restricted to the for loop.
10. The line prints: "3". This is the value of prices.length assigned to the length variable on line 4.
11. The function returns the same array as questions 4 and 8. The values are unchanged even with the removal of finalPrice because the discount is 0.5 and the values in prices are whole numbers, so there was no rounding before. 
12. 
	A. student.name
	B. student['Grad Year']
	C. student.greeting();
	D. student['Favorite Teacher'].name
	E. student.courseLoad[0]
13. 
	A. "32" : converts 2 to string and concatenates
	B. 1 : converts '3' to integer and subtracts
	C. 3 : null maps to 0
	D. "3null" : converts null to string and concatenates
	E. 4 : true maps to 1
	F. 0 : false and null both map to 0
	G. "3undefined" : undefined maps to string
	H. NaN : '3' maps to 3 and subtracting undefined is NaN
14. 
	A. true : '2' is converted to integer
	B. false : fist char '2' is not less than '1'
	C. true : both are converted to numbers and are equal
	D. false : they are not equal without type conversion
	E. false : true maps to 1, 1 != 2
	F. true : Boolean(2)returns true, which is equal to true and the same type
15. == converts both sides to numbers and does the comparison. === does not convert, so values of different types cannot be equal.
16. Code included.
17. The retirn value should be [2,4,6]. In the modifyArray for loop, it iterate through each element in array which is [1,2,3]. The loop calls the callback method, which is doSomething as passed into the arguments, which doubles the input value. Thus, each value in array is doubled and then pushed into newArr, to get [2,4,6]. 
18. Code included.
19. The output is: 
	1
	4
	3
	2