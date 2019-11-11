---
title: "State and Lifecycle"
metaTitle: "State and Lifecycle"
metaDescription: "Understanding state and lifecycle"
---

# Theory
1. [State & Lifecycle: Introduction](https://itnext.io/react-understanding-state-lifecycle-d45df5d2cf3f) [~6m read] 
1. [State and Lifecycle: Official doc](https://reactjs.org/docs/state-and-lifecycle.html) [~25m read] 

# Practice

### Ex.1 - Create a contact page

1. Create a user contact page, which should contain the information of user, with the following items:
- Avatar
- Name
- Phone number

>Hint: Set this data to state and use it for render information:
```javascript
const contact = {
  image: 'http://cs7.pikabu.ru/images/big_size_comm_an/2014-03_7/13962622876915.gif',
  name: 'Darth Vader',
  phoneNumber: '+250966666666',
  email: 'dartvader@email.com',
  address: '731 Howard St. Huntington Station, NY 11746'
};
```

### Ex.2 - Improve the contact page

When you click on the contact avatar, 
it should unfold (increase in height)
and should display additional information about the contact (address and email). When you click again, the information should collapse.

>Hint: Use `onClick={handleClick}` for handle a click on the avatar.
