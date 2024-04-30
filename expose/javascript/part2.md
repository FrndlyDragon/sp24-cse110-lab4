1. 3 will be returned since it will return the value of i after the loop is finished. The loop starts with i = 0 but is incremented so it then becomes 1 then 2 then 3 before exiting as 3 is equal to length and thus i won't increment again. 
2. 150 will be returned as that is that last value for discounted price that was calculated in the loop. 300 is the last element of the input array and 300 * 0.5 is 150.
3. 150 will be returned here as well as 150 rounded down is still 150 since it's a whole number. 
4. What is returned is an array with the newly calculated values after applying the discount. The loop goes through each element of the prices array and applies the discount to them before adding that new price into the discounted array. The discounted array is then returned.
5. It returns an error since i is only accessible from within the for loop and the console.log statement is outside of the loop so it will error.
6. It returns an error since discounted price is only accessible from within the loop.
7. 150 is returned since final price is outside of the for loop and thus everything within the function can access this variable.
8. An array of the discounted prices will be returned since the return statement is returning the discounted array but since it was declared in the function, the return statement will be able to return it.
9. An error is thrown since i is a let variable and only accessible from the loop.
10. 3 is returned since it's just the length of the input array which is an array with 3 elements.
11. An array of the discounted prices will be returned since the loop goes through the prices array and halves them before passing those new values into the discounted array which is returned.
12. 
    1.  ```student.name```
    2.  ```student["Grad Year"]```
    3.  ```student.greeting()```
    4.  ```student["Favorite Teacher"].name```
    5.  ```student.courseLoad[0]```
13. Arithmetic
    1.  32: 2 was converted into a string and concatenated to 3 to give 32.
    2.  1: 3 is converted into an integer and subtracted by 2 to get 1.
    3.  3: null is considered 0 so 3 plus 0 is 3.
    4.  3null: null is converted into a string ("null") and concatenated to 3.
    5.  4: true is considered to be 1 so 1+3 is 4.
    6.  0: false is considered 0 and null is 0 so 0 + 0 is 0.
    7.  3undefined: undefined is concatenated to 3.
    8.  NaN: Undefined isn't defined so javascript doesn't no what to do and returns empty.
14. Comparison
    1.  true: 2 is turned into an integer and thus 2 > 1 is true.
    2.  false: String comparison and the first character 2 is greater than the first character 2 so false is returned.
    3.  true: 2 is turned into an integer and 2 == 2 is true.
    4.  false: Triple equals doesn't do type conversion so 2 is not the same as '2' so is false.
    5.  false: true is equal to 1 and 1 != 2 so is false.
    6.  true: Boolean(2) returns true since 2 is not 0 and thuse true is equal to true.
15. == is just the regular equality and can do type conversion on elements it is comparing while === is a strict equality that doesn't do type conversion.
17. [2,4,6] is returned as all the loop does is access a value from the input array which is [1,2,3] and give that value to the doSomething function which just doubles the value given. This doubled value is then pushed into the returned array. Thus, the returned array is just all values of the input array doubled.
19. 1
    4
    3
    2