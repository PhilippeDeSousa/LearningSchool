# Day 03

### Allowed functions: *write*
### Given functions: ***print_char***

```c
void print_char(c) {
	write(1, &c, 1);
}
```
*You don't need to understand how the function works just yet, just find out how to call it*
## Task 0: Print a character
Your first task of the day is to use the ***print_char*** function in order to display a character in your console.

## Task 1: Hello World
Now that you found out how to use the ***print_char*** function, create a function named ***print_hello_world*** that displays the message "Hello World" in your console. It's prototype is as follows:
```c
void print_hello_world(void);
```

## Task 2: Print a string
Write a function that, given a string as parameter, displays that string in your console.
It's prototype must be as follows:
```c
void print_string(char *str);
```
*Hint: use a loop!*

## Task 3: Print reverse string
Write a function that, given a string as parameter, displays that string in the reverse order.
It's prototype must be as follows:
```c
void print_rev_string(char *str);
```

## Task 4: Integers
Write a function that, given an integer as parameter, displays either P, N or O if the parameter is positive, negative or null.
It's prototype must be as follows:
```c
void print_isneg(int number);
```

## Task 5: Integers
Write a function that, given an integer as parameter, displays either P if the parameter is pair, else O.
It's prototype must be as follows:
```c
void print_ispair(int number);
```

## Task 6: Printing integers
Write a function that, given an integer, displays it's value in the console.
It's prototype must be as follows:
```c
void print_integer(int number);
```
**Warning: This is significantly harder**

## Task 7: Return values
Write a function that takes a string as parameter, and returns it's length
It's prototype must be as follows:
```c
int str_len(int number);
```
*Hint: Use your `print_integer` function to check if your value is correct*