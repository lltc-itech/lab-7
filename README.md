# Instructions  

For this program, you will write a program that computes and writes out the greatest common divisor (GCD) of two integers. This is the largest positive integer that evenly divides both numbers.

The Euclidean algorithm is probably the easiest one to code up in a program.

```
Read two integers.
REPEAT as long as they are different:
    Calculate the absolute difference between both numbers
    Replace the larger number by the absolute difference calculated in the previous step
END REPEAT
Here both numbers are equal and are also equal to the GCD of the two integers.
Print out result.
```

Use the `index.html` file for your code.

## Some Tips

* From the [Notes Repo](https://github.com/SirYancy/itech-270---unit-7), the `primes2.html` and `doesntwork.html` might help you with syntax or ideas.
* First, try running through the algorithm on paper and pencil so you understand how it works.
* Consider converting the algorithm into a flow chart so you can see what it looks like.
* You will need exactly two inputs from the user.
* You will need to use a `while(){}` loop.
* You will need to use at least one if/else statement.
* Think carefully about how to find the "absolute difference" between two numbers. It should never be a negative number.
