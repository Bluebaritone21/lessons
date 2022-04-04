# Java and Python

## For Scratch users

---

## Lesson 1: Hello, World

![A Scratch program](ScratchHello.png  "Make sure to put the say in a custom block")
>The Above Scratch program will say Hi!
>
>Just Remember the Say block is part of the main custom block.

Now let's write the same thing in Python!

```python
def main():
    print("Hello, World!")

if __name__ == '__main__':
    main()
```

Running this will result in `Hello, Wold!` being printed on the screen!

 Congrats! you wrote your first Python Program! Show your freinds!

### Okay, what just happened?

First off, **def main():**
When you type `def`, you are saying that you want to make a *function*, which is a reusable peace of code **(like a custom block!)**. The `main()` means that you are calling the function **main** and that there are no parameters, which are like the fields in a custom block.
The `print` command is precceded by 4 spaces, which mean that it's part of the `main` function.

Finaly, `if __name__ == '__main__':` Whew. First of, `if`. We will go into more detail in Lesson 2, but for now, just know that the main function that is indented after it will be run only when `__name__ == '__main__'`. But what does `__name__ == '__main__'` mean? Well, `__name__` is a special variable (again, wait for *lesson 2*). and `'__main__'`, along with `'Hello, World!'` is a **string**, or text.