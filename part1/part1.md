1.  Will print the current value of i after executing the for loop which is prices.length.

2.  Will not print anything since discountPrice is not defined. discountPrice is only visible 
    in the code block for loop since discountPrice is nested in a function variable it 
    becomes a function-level variables thus we can not see it outside the function.
    
3.  finalPrice will print the price of the last items after discount.

4.  The function will return [50, 100, 150] since the discount is 50%.
    For each item we will take the original price * (1 - discount which is .5)
    Then we push it to an empty Array.
    
5.  Since we use let, the variable i only visible in the for loop.
    Thus this line will print error since i is not defined.
   
6.  Will not print anything since discountPrice is not defined. discountPrice is only visible 
    in the code block for loop since we are using let. We get [100*.5 , 200*.5, 300*.5]
    
7.  finalPrice will print the price of the last items after discount.

8.  The function will return [50, 100, 150] since the discount is 50%. For each item we will 
    take the original price * (1 - discount which is .5) Then we push it to an empty Array.
    We get [100*.5 , 200*.5, 300*.5]
    
9.  Since we use let, the variable i only visible in the for loop. Thus this line will 
    print error since i is not defined.
    
10. Will not print anything since discountPrice is not defined. discountPrice is only visible
    in the code block for loop since discountPrice is const type which will not available
    for global scope.
    
11. 0. Since it is a const variable, If we run the function with value it will gives error 
    since we changing the const variable.
    
12. It will gives us error since we assign a number to a const value, finalPrice.
    Thus we will not get anything in return except error.
    
13. A. console.log(student.name);
    B. console.log(student["Grad Year"]);
    C. console.log(student.greeting());
    D. console.log(student["Favorite Teacher"].name);
    E. console.log(student.courseLoad[0]);
    
14. A. 32
    B. 1
    C. 3
    D. 3null
    E. 4
    F. 0
    G. 3undefined
    H. NaN
    
15. A. true
    B. false
    C. true
    D. false
    E. false
    F. true
    
16. The difference between == and === is that == use type conversion before comparing
    the two values thus result in (0 == false) is true since it converts false into 0
    and (0 == 0). However, for ===, it does not use type conversion thus if the two values
    are not the same type then it will automaticlly return false.
    
17. "How are you?" will get printed because the function will converts into number first. 
    Thus resulting true to become 1 and 2 is not equal 1, so the first if return false.
    When if(2), since there is nothing to compare it to, 2 will convert to a boolean
    value. Since 0 is false, and any value other than 0 is 1, the function if(2) return true
    Thus it print "How are you?" as the result.
    
19. The function will return [6, 8, 10] because when we call modifyArray([1,2,3], doSomething),
    the function will go through each number in the array. Starting with the first number, 1, 
    we called doSomething(1, function(x){ return x2}. The function doSomething will take the number 1
    and return 1 + 2 to callback. Thus make the function(x) becomes function(3) and 3(2) = 6 and the 
    newArr.push(6). Same with other values they get + 2 first then times 2.
    
21. 1
    4
    3
    2
