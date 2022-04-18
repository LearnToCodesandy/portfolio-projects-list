# Todo App ( Full Stack --> MERN)
------

### Goals to achieve
------
* user authentication

* pages
    * login page
    * home page
    * settings page

* user specific todos
    * add a todo
    * delete a todo
    * update a todo
    * log out
    * update profile

* component structure
    * navbar
    * todocontainer
        * todo form
        * todo list container
            *todo item
    * toast notification 
    * quote container

* Database architecture
    * User
       * userId
       * username
       * email
       * password   
    * Todos
       * todoId
       * userId
       * todo message
       * todo status
       * todo deadline
       
* Routing structure
    * / ---> api/v1/auth/login
    * /home ---> /api/v1/getTodos/:userId
    * /api/v1/deleteAllTodos/:userId
    * /api/v1/markAllDone/:userId
    * /api/v1/addNewTodo/:userId
    * /api/v1/updateTodo/:userId/:todoId
    * /api/v1/deleteTodo/:userId/:todoId
    * /api/v1/updateProfile/:userId



### Frontend 
--------------
* Login Page
    * [ ] Login Form
    * [ ] Signup Form
    * [ ] Toggle between Login and Signup form
    * [ ] Upon submission redirect to home page
* Home Page
    * [ ] todo form
    * [ ] todo list
    * [ ] filters section
        * [ ] deadline
        * [ ] created at date
        * [ ] todos that are completed
        * [ ] todos that are not completed
    * [ ] quote section
        * [ ] Get a quote from an api 
* Settings Page
    * [ ] Show user profile
    * [ ] add edit button
    * [ ] upon clicking that edit button populate a form as a modal and submit that updated data to server
