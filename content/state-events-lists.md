---
title: "State of Components, Handling Events"
metaTitle: "State of Components, Handling Events"
metaDescription: "Understanding State and Handling Events"
---

Section covers basic topics about component lifecycle, handling events, conventions for conditional rendering and 
important nuances about rendering lists.

# Theory
1. [State & Lifecycle: Introduction](https://itnext.io/react-understanding-state-lifecycle-d45df5d2cf3f) [~15m read] 
1. [State and Lifecycle: Official doc](https://reactjs.org/docs/state-and-lifecycle.html) [~25m read] 
1. [Lifecycle, detailed overview: Official doc](https://reactjs.org/docs/react-component.html#the-component-lifecycle) [~35m read] 
1. [Handling Events: Introduction](https://medium.com/javascript-in-plain-english/declaring-event-handlers-d63b17e170d9) [~15m read] 
1. [Handling Events: Official doc](https://reactjs.org/docs/handling-events.html) [~10m read] 
1. [8 React conditional rendering methods](https://blog.logrocket.com/conditional-rendering-in-react-c6b0e5af381e/) [20m read] 
1. [Conditional Rendering: Official doc](https://reactjs.org/docs/conditional-rendering.html) [~15m read] 
1. [Lists and Keys: Official doc](https://reactjs.org/docs/conditional-rendering.html) [~20m read] 

# Practice

### Exercise.1 - Create a contact page

1.Create a `Contact Card` component, which should contain the information of a user, with the following items:
- Avatar
- Name
- Phone number

1.Create a `Contact Page` component for render the contact card.

>Hint: Use this data for contact card (only like a prop)
```javascript
const CONTACT = {
  name: 'Darth Vader',
  image: 'http://cs7.pikabu.ru/images/big_size_comm_an/2014-03_7/13962622876915.gif',
  phoneNumber: '+250966666666',
  email: 'dartvader@email.com',
  address: '466 Brewery Drive Warwick, RI 02886'
};
```

### Exercise.2 - Improve the contact page

When you click on the contact avatar, 
it should unfold (increase in height)
and should display additional information about the contact (address and email). When you click again, the information should collapse.

>Hint: Use `onClick={handleClick}` for handle a click on the avatar.

### Exercise.3 - Add edit form to contact page
1. Update the `Contact Card`, add the text input field under the contact info.
1. Add button next to the input field, for save changes.
1. Add the handler for select information item (name, phoneNumber, address) by click on it.
1. After the select item and filled text to the input field, the value of the item should be changed 
   to the text which was written in the input field, by click on the save button.

### Exercise.4 - Conditional edit form 
1. Update the `Edit Form` add the edit button under the contact info.
1. At the same time by default edit form, should be hidden. 
1. By click on the edit button, it should be replaced with edit form and vice versa after click on the save.

### Exercise.5 - Create a contact list

1. Update the `Contact Page`, it should be contain a list of contacts.
1. The contact item should be based on the `Contact Card`.
 
>Hint: Data for contact list.
```javascript
const CONTACTS = [
  {
    id: 1,
    name: 'Darth Vader',
    image: 'http://cs7.pikabu.ru/images/big_size_comm_an/2014-03_7/13962622876915.gif',
    phoneNumber: '+250966666666',
    email: 'dartvader@email.com',
    address: '466 Brewery Drive Warwick, RI 02886'
  }, {
    id: 2,
    name: 'Princess Leia',
    image: 'http://images6.fanpop.com/image/photos/33100000/CARRIE-FISHER-anakin-vader-and-princess-leia-33186069-190-149.gif',
    phoneNumber: '+250963443435',
    email: 'princessleia@email.com',
    address: '7379 Lakeview Street Yuma, AZ 85365'
  }, {
    id: 3,
    name: 'Luke Skywalker',
    image: 'http://www.youshouldshare.me/wp-content/uploads/2015/03/14264215682890-anigif_enhanced-buzz-13518-1367608452-4.gif',
    phoneNumber: '+250976654433',
    email: 'lukeone@email.com',
    address: '87 Greystone Lane Silver Spring, MD 20901'
  }, {
    id: 4,
    name: 'Chewbacca',
    image: 'https://media.giphy.com/media/RUUdVZqwpfTRS/giphy.gif',
    phoneNumber: '+250456784935',
    email: 'chewbby@email.com',
    address: '486 Brown St. Stroudsburg, PA 18360'
  }
];
```

