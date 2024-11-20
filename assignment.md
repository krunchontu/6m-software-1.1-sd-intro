## Assignment

In this assignment, you will learn to use the developer's tool to inspect the elements of [this](https://nznznh.csb.app/) webpage.

1. What is the right margin of the first element? 
```
50px
```

2. What is the top padding of the second element?
```
100px
```

3. What is the class name of the third element and the content of the css?
```
elementThree
.elementThree {
        padding: 10px;
        background-color: aquamarine;
        text-shadow: 1px 1px white;
        border: gray solid 2px;
        border-radius: 10px;
      }
```

4. What is the css selector of the fourth element?
```
div:nth-of-type(4)
```

5. What is the code you use to keep the blue box within the purple?
```
.parent {
  border: purple 8px solid;
  margin: 0;
  width: 500px;
  box-sizing: border-box; /* Optional but ensures the parent's dimensions are correctly calculated */
}

.child {
  border: mediumblue 8px solid;
  width: 100%; /* Stretches to the parent's width */
  height: 100%; /* Stretches to the parent's height */
  margin: 0; /* Removes any margin offset */
  box-sizing: border-box; /* Ensures padding and border are included in the width and height */
}

```

> hint: you should apply box-sizing property to the `.child` class. Make the changes on the developer's tool to see immediate UI change.



### Submission 

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Always store your assignments in the `assignments` folder or `assignment.md` file.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL. 
