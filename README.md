# Welcome to Finny!

# Task Description
We are going to create simple TODO JavaScript/TypeScript web SPA application in order to evaluate your skills and individual working abilities.

Application consists of several parts. 

1) User authentication featuer - simply anyone can sign up with providing username and password. Respectively, users should be able to login in to view task list. 

2) After login, on main page user should have a facility to make a basic CRUD operations over the task list. Users should have capability have to make CRUD operations on task list.
	1. **view existing tasks**
	2. **add new tasks**
	3. **update upcoming tasks** - only unexpired tasks may be updated.
	4. **delete tasks**

3) Task object should have a following structure:
	
    ```
    {
	    title:  String,
	    createdAt:  Date,
	    expiresAt:  Date,
	    isDone:  Boolean
    };
    ```
   
 4) User should be able to mark tasks as "done" or switch back to "undone". If the tasks is expired, users are prohibited to make any changes on tasks, (delete or update are disabled).
 
## Dependencies and Technical requirements

SPA Web application should be created using **ReactJS** with **TypeScript** and **NextJS**. For basic styling, please use **TailwindCSS**. 

Application database should be persistent, therfore we need to use **Redis** to store the user data and task lists.

- For CRUD operations client side should make XHR requests to API. 

- For simplicity please use **NextJS API Routes** for endpoint implementation.


## Lifecycle and flow of application
![enter image description here](https://i.ibb.co/Vt923kn/TODO-flow.png)
