1. SPECIFY : 
    Specify the functionality of the method we are implementing
2. IDEATE :
    Ideate a game plan for how to implement this functionality in code
3. IMPLEMENT :
    Implement our game plan
4. TEST :
    Test our code to ensure it works as expected

========================================================
********************************************************
========================================================


Ideate: 
    To produce a random message based on a different string, We might need to 
    1. create 3 array
    There are a number of different ways to implement this method. One that might have come to your mind would be to use control flow to compare the current value and to the bounds and return the proper result. We are going to present a different solution in these steps so that you can keep considering unexpected ways to solve problems.

Add the .clamp() method to the lodash object.

Use Math.max() to clamp the number by the lower bound. The return value of Math.max() called with the number and the lower bound will be the larger of the two values, meaning it will be clamped by the lower bound.

Use Math.min() to clamp the number by the upper bound. The return value of Math.min() called with the number and the upper bound will be the smaller of the two.

Return the final value of these two operations, which will be the clamped number.

Once you have tried implementing this game plan in code, move on to the next step to see how we do it.

5.
Implement: Let’s implement our game plan in code.

Add a method to our _ object called clamp.
Add three parameters to this method: number, lower, and upper.
Within the method, create a variable called lowerClampedValue that is set equal to the return value of Math.max() called with number and lower.
Create a variable called clampedValue that is set equal to the return value of Math.min() called with lowerClampedValue and upper.
Return clampedValue as our final value from the method.
Once you’ve finished implementing this method, move on to the next step to test it.

6.
Test: To test that our .clamp() method works as expected, run node test/clamp.js in your terminal. Don’t worry if any errors appear, work through them one by one until your code runs as expected.

Once all of the tests are passing, congratulate yourself! You’ve implemented the first method of this project! This is very exciting. Hopefully, you’re beginning to feel like a developer.

When you’re ready, move on to the next method.
