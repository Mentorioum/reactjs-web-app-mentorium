---
title: "Introducing JSX, Rendering Elements"
metaTitle: "Introducing JSX, Rendering Elements"
metaDescription: "Introducing JSX, Rendering Elements and practical tasks"
---

# Introducing JSX, Rendering Elements

### Theory
1. [Introducing JSX](https://reactjs.org/docs/introducing-jsx.html) 10 min read 
2. [Rendering Elements](https://reactjs.org/docs/rendering-elements.html) 5 min read 
3. [Components and Props](https://reactjs.org/docs/components-and-props.html) 10 min read 

# Practice

## JSX

### Is this valid JSX examples? Fix it if needed

1: 
```
<div/>
```
2: 
```
<div>hello</div>
```
3: 
```
<div>hello</div><span>World</span>
```
4: 
```
<div>hello<span/> World<div/>
```

### What code will return BABEL from this JSX - 
```
<div>Hello World</div>
```
a) 
```
React.createElement("div", null, "Hello World")
```

b) 
```
<div>Hello World</div>
```

c) 
```
<body><div>Hello World</div></body>
```

d) 
```
React.createElement("div", "body"", "Hello World")
```

#### Meaning of each parameter
```
React.createElement('h1',{className: 'greeting'},'Hello, world!');
```

#### Difference between 
```
React.createElement('h1', {className: 'greeting'}, 'Hello, world!');
```
##### and
```
React.createElement('h1', {className: 'greeting', hildren:<h1>Hello World</h1>});
```
##### What we will see if render this
```
React.createElement('h1', {children:'Hello'},'World');
```
# Elements
#### add element in your application with
##### 1: plane text
##### 2: some tags 
```
<p><div><span>
``` 
etc.
##### 3: render list from exampleArray
##### 4: import CSS and add classes

```
const exampleArray = [ {"Id": 1, "Name": "asthma_patientguide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 2, "Name": "cataract_patientGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 3, "Name": "ckd_patientGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 4, "Name": "col_patientGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 5, "Name": "copd_patientGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 6, "Name": "diabetes_care_patientGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 7, "Name": "gallstone_PatientGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 8, "Name": "healthy_active_patientGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 9, "Name": "heartfailure_patientGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 10, "Name": "hepatitis_b_patientGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 11, "Name": "hepatitis_c_patientGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 12, "Name": "hyper_patietnGuide", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" }, { "Id": 13, "Name": "hyper_patientGuideII", "DocType": "PDF", "DocTypeDescription": "Acrobat reader document" } ]
```
# Components and Props
#### add several components in your application with
##### 1: plane text
##### 1.1: send plane text as props from parent to child and render it
##### 2: add 2 components ExampleArrayList and ExampleArrayItem. And render exampleArray by passing props like this App->ExampleArrayList->ExampleArrayItem
