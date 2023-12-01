# Types

Types can be used to create variables of different types that can be used in your application's processing of data.

***

### Why use Types?

Using Types can make your application development more efficient in the following ways:

* Reusability\
  A Type is created once, but instances of the Type can be used multiple times.
* Maintainability\
  Maintaining a Type is made easy by allowing you to update the details of a Type in one place, rather than in all instances of the Type.
* Validations\
  When creating a Type you associate it with a specific data structure, like a List or Object, which helps in validating the data that can be used in any instance of the Type.

***

### Defining Types

When creating a Type, the following are available:

1. Any\
   Can be created for strings, integers, decimals, dates and booleans.
2. List\
   Can be created for a list of items. The items can be of any Type.
3. Object\
   Can be created for JSON objects.
4. Existing Types\
   Can be created as a Type of a Type.

***

### How to use Types

1. Click on the Types icon on the top menu bar.
2. Provide a name for your Type.
3. Select what type you are creating, e.g. List or Object.
4. Drag your Type to an Event, e.g. a page load. At this point you are creating a variable of that Type.
5. Add the required actions to your Event to interact with your variable, e.g. to store values to it or to assign its value to other variables, Actions or Controls.

How to assign values to a Type by using an expression

Set the initial values of the object by setting the Value property to a JavaScript object containing the properties you want to set.

In the example below, name, email and phone properties are set. Then the name property is initialized to another object which contains the title, first and last properties.\


{\
name : {\
title : 'Mr',\
first : 'James',\
last : 'Pace'\
},\
email : 'james.pace@gmail.com',\
phone : '555-1234'\
}\


***
