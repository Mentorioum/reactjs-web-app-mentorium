---
title: "Component Composition"
metaTitle: "Component Composition"
metaDescription: "Component Composition, Elements and practical tasks"
---

# Component Composition

### Theory
1. [Composition vs Inheritance](https://reactjs.org/docs/composition-vs-inheritance.html) 30 min read 

# Practice

### Render this array by only one component with configure props.

### 1 using props as much as you like 
### 2 using only 3 props (name, description, children) 
### 3 add possibility to go in folders (onClick),in objects with children
### 4 add possibility to go out folders. add backbutton (onClick in back button),in objects with children 
```
    const foldersArray = [
        {
            name: 'dogs',
            description: 'folder with dogs',
            children: [{
                name: 'Bobik',
                description: 'Bobiks history',
                children: [{
                    name: 'DOB',
                    description: '2010-10-10 Bobik born',
                },
                    {
                        name: 'DOD',
                        description: '2020-12-12 Bobik die',
                    }
                ]
            },
                {
                    name: 'Chappy',
                    description: 'Chappy is a good dog',
                },
            ]
        },
        {
            name: 'foxes',
            description: 'no items',
        },
        {
            name: 'cats',
            description: 'folder with cats',
            children: [{
                name: 'Murzik',
                description: 'Murzik data',
                children: [{
                    name: 'DOB',
                    description: '2010-10-10 Bobik born',
                },
                    {
                        name: 'Wife',
                        description: `Murzik's wife is Murka`,
                    },
                    {
                        name: 'children',
                        description: `Mursik's children`,
                        children: [
                            {
                                name: 'Barsik',
                                description: `Barsik is Mursik's son`
                            },
                            {
                                name: 'Murka',
                                description: `Murka is Mursik's daughter`
                            },
                            {
                                name: 'Mur',
                                description: `Mur is Mursik's transgender`
                            }
                        ]
                    }
                ]
            },
                {
                    name: 'Tom',
                    description: 'Tom&Jerry',
                },
            ]
        },
        {
            name: "Ducks",
            description: "Folder with ducks",
            children: [
                {
                    name: 'Donald',
                    description: "Duck",
                },
                {
                    name: "Darkwing",
                    description: 'Duck'
                },
                {
                    name: "Uncle",
                    description: "Scrooge",
                    children: [
                        {
                            name: "Nephews",
                            description: "Uncle Scrooges Nephews",
                            children: [
                                {
                                    name: "Huey",
                                    description: 'Nephew'
                                },
                                {
                                    name: "Dewey",
                                    description: 'Nephew'
                                },
                                {
                                    name: "Louie",
                                    description: 'Nephew'
                                }
                            ]
                        }
                    ]
                }
            ]
        }
    ]```
