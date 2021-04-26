## PART 1A
1. values added: 20
2. final result: 20
3. values added: 20
4. The code woudl return an error that result is not defined because line 13 is not within the block that result is defined in
5. The code would return an error beause you cannot reassign the constant as they do on line 7
6. The code would return an error beause you cannot reassign the constant as they do on line 7

## PART 1B
1. since i is a global variable it will be visable after the for loop. The value 3 will get printed in the console because the for loop runs as many times as the length of list prices, which is 3. 
2. since discountedPrice is a global varaible it will be visable after the for loop. The last value discountedPrice holds in the for loop is 150, so the value 150 will get printed in the console. 
3. since final price is a global varaible it will be visable after the for loop. The value 150 will get prined in the consloe because that is the last value that finalPrice holds in the for loop. 
4. [50, 100, 150] will be returned becuase discounted, finalPrice, and discounted price are all declared with var, which means that they have no block scope. Therefore, all of the varaibles are correctly accessible and the function can run properly (aka return a list of the discounted prices). 
5. Since i is defined using let, i will only be accessible within the for loop. since line 12 is outside the for loop block you will cause an error saying that i is not defined. 
6. Since discountedPrice is defined using let inside the for loop, it will only be accessible within the for loop block. Line 13 is outside the for loop block, so it will cause an error saying that discountedPrice is not define. 
7. The value 150 will get printed in the console. finalPrice is defined using let at the begining of the function, so it will be accessible throughtout the whole function. The last value finalPrice holds in the for loop would be 150, and since line 14 comes after the for loop is done, 150 will be printed in the console. 
8. [50, 100, 150]. discounted and finalPrice are defined using let at the top of the function, so those two variables will be accessible throughout the whole function. i and discountedPrice are define using let in the for loop and those variables are only used within the for loop so they are approriatley accessible. Since all of the varaibles are accessible as intened, the function will work properly and hence return a list of the discounted prices. 
9. The code causes an error because i is defined using let in the for loop, so i will only be accessible within the for loop. line 11 is outside the for loop block so it will result in an error saying that i is not defined. 
10. 3 will get printed. length is defined using const within the same block as line 12 so the value stored in length will be accessbile at line 12. 
11. [50, 100, 150]. discounted and finalPrice are defined using const at the top of the function, so those two variables will be accessible throughout the whole function. i is defined using let in the for loop and that variable is only used within the for loop so they it is approriatley accessible. discountedPrice is defined within the for loop and is only used within the for loop. Since all of the varaibles are accessible as intened, the function will work properly and hence return a list of the discounted prices. 
12. a) student.name  
    b) student['Grad Year']  
    c) student.greeting()  
    d) student['Favorite Teacher'].name  
    e) student.courseLoad[0]
13. a) '32' because the plus sign will be used as a contatenation and treat the two as strings       
    b) 1 the subtraction results in an automatic integer conversion    
    c) 3 null gets converted to its numberic value 0 so that plus the integer 3 yeilds 3      
    d) '3null' since '3' is a string the plus sign is used as concatenation   
    e) 4 true gets converted to its numeric value 1 and that gets added to the integer 3  
    f) 0 the numeric value of false is 0 and the numeric value of null is 0 so 0 plus 0 results in 0    
    g) '3undefined' since '3' is a string the plus sign will be used for concatenation   
    h) NaN subtraction sign reuslts in an automatic number conversion so '3' becomes 3 and undifined becomes NaN so 3 - NaN is simply NaN    
14. a) true the > will result in the 2 being converted into a number and 2 is greater than 1  
    b) false since they are both string, they will be compared using dictionary ordering and 1 comes before 2 so false  
    c) true the == allows for data type conversion so the '2' will be converted into a number and 2 is equivialnt to 2   
    d) false the === does not allow for any data type conversions so comparing a string and number automatically return false  
    e) false since == allows for data type conversion, the true will get conveted into its numeric value 1 which is not equal to 2  
    f) true the Boolean(2) results in true and true is equal to true. the === did not have to do a data type conversion so this works because 2 was converted to a boolean before the === comparison.   
15. == is a regular equality check. === is a strict equality check. The difference between the two is that === check the equality without type converstion. For example, if you do a === b and a and b are differnt types then false would be immidiately returned. On the other hand == would do a type conversion and then compare a and b. 
16. skip
17. The result will be [2, 4, 6]. We will first enter the modifyArray function. In the for loop in this function, we will go through each number in the array. Within each iteration, the current number will be passed into the doSomething method and it will be multipiled by 2. Once doSomething returns this doubled value, we will end up back in the modifyArray method and push this doubled value into newArr. Once this for loop is done, every value that was in array would be doubled and pushed into newArr which is what get returned at the end.
18. skip
19. 1   
    4  
    3  
    2  
