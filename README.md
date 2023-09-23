# Writing Good Documnetation

## Step 1 - Using Codeblocks

**Codeblocks** is cool way to make code easier to read

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
num = 5
result = factorial(num)
print(f"The factorial of {num} is {result}")
```

 - Attempt to color highlight your code

```py
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
num = 5
result = factorial(num)
print(f"The factorial of {num} is {result}")
```

- Error in console

```bash
  File "<stdin>", line 2
    print("Hello, world!"
                        ^
SyntaxError: unexpected EOF while parsing
```
> Example of error
# Step 4 - Table and emoji

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud |`:cloud:` | :cloud: |


## References

-[Flavor Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
