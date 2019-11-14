---
title: "JSX, Rendering and Components"
metaTitle: "JSX, Rendering and Components"
metaDescription: "Introducing to basics of JSX, Rendering Elements"
---

# Intro

Basics of JSX, Rendering Elements and working with components and their props


# Theory

1. [Introducing JSX](https://reactjs.org/docs/introducing-jsx.html) [~20m read] 
2. [Rendering Elements](https://reactjs.org/docs/rendering-elements.html) [~10m read] 
3. [Components and Props](https://reactjs.org/docs/components-and-props.html) [~20m read] 

# Advanced 

1. [JSX In Depth](https://reactjs.org/docs/jsx-in-depth.html) [~20m read]


# Practice


### Exercise.1 - Is this valid JSX examples? Fix it if needed

**Question.1**
```
<div/>
```   

**Answer.1**

`Yes/No`


**Question.2**
```
<div>hello</div>
``` 

**Answer.2**

`Yes/No`


**Question.3**
```
<div>hello</div><span>World</span>
```

**Answer.3**

`Yes/No`


**Question.4**

```
<div>hello<span/> World<div/>
``` 

**Answer.4**

`Yes/No`


### Exercise.2 - What code will return Babel from this JSX 

**Question.1**

```
<div>Hello World</div>
```
         
**Answer.1**

```
// write your answer here
```

**Question.2**

```
<div className="SplitPane">
  <div className="SplitPane-left">
    Left
  </div>
  <div className="SplitPane-right">
    Right
  </div>
</div>
```

**Answer.2**

```
// write your answer here
```

### Exercise.3 - Add  previous babel output to your workbook

Just drop them in  app`s index and make sure that it renders correctly

### Exercise.4 - Add UserPanel component to your workbook 

Shout accept `user`  property, see next example 

```
{ 
    firstName: 'Foo',
    lastName: 'Boo',
    avatarUrl: 'url/to/some/image'
}
```
