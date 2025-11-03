# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response

According to MDN, a **function** is a set of statements that performs a task or calculates a value. It can take some input and return an output, and it can later be called in the same scope where it was defined.

You can think of a function as a recipe in a cookbook. A recipe contains a list of instructions you can refer to whenever you want to make a specific dish. A recipe has **inputs**, which are the ingredients required to make the meal, and an **output** which is the finished dish. Each time you want to make that dish, you can refer to your cookbook instead of recalling all the instructions and measurements from memory. Similarly, a function allows you to **reuse** code without rewriting it every time and essentially perform the same task with different inputs.

An example of how to write an arrow function in JavaScript would be the following:

```js
const add = (x, y) => {
    return x + y;
}

add(2, 2);
```

In this example, we can see that the **arrow function** is saved into a variable named ```add```. The function then takes two inputs ```(x, y)```, which are called **parameters**. The following code block contains a ```return``` statement that outputs the result of ```x + y```. In this case, the function ```add``` is called *(or invoked)* with the **arguments** ```(2, 2)```, and it returns an output of ```4```.

A more simplified version of this same function would be the following:
```js
const add = (x, y) => x + y;

add(2, 2);
```

Note that in this instance, the function has an implicit ```return```.