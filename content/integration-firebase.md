---
title: "Integration FireBase with Form"
metaTitle: "Integration FireBase"
metaDescription: "Integration FireBase with Form"
---

# Theory
1. [Firebase: Introduction (Good to know)](https://firebase.google.com/docs/emulator-suite) [~3m read]

# Practice

### Exercise.1 - Integration with FireBase.
1. Integrate FireBase with form from previous homework, use the example of the connect FireBase from: 
`/workbook/src/SignInWithGoogle.js`

### Exercise.2 - Create the Sign Up form.
1. Add the `Sign Up` button, before the login button.
1. By clicking on the `Sign Up` should be switched to Sign-Up form.
1. Add the Sign-Up form, it should contain the same fields as the login form:
- email
- password
1. Add the `Back` button and `Save` under the form.
1. By clicking on the `Back` should be switched back to the login form,
on `Save` click, create a new user.

### Exercise.3 - Form behaviour in the case of (sign-in/ sign up ).
>Hint: Take the following properties form the Firebase:
```javascript
 createUserWithEmailAndPassword(email, password);
 signInWithEmailAndPassword(email, password);
 signOut();
 user
```
1. After the successful (sign-in / sign up) of the user, the form should be hidden.
1. Show an alert, in case of:
- Sign-in `Welcome back {user.name}`
- Sign-up `Hello {user.name}`
1. Create the small information frame of the user, add the `Sign Out` button.
1. By clicking on the `Sign Out` go back to the login form.

