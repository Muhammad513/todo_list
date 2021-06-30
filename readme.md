# This project is a todo list

**The work to be done in this project will be indicated**

## **Install:**

`pip install django`

## TODO LIST
### Property:
- id(*int*): New task ID
- status(*bool*): True if done, otherwise False
- taskname(*str*): The name of the task
- description(*str*): The description of the task

### Methods:
- add
- update
- update_status
- get_all
- remove


=======
# API:

## **Add method**
----
	Return json data about added task.

- **URL**\
	/add

- **Method:**\
  `GET`

- **URL Params**\
  **Required:**\
  `status(bool)`\
  `taskname(str)`\
  `description(str)` 

- **Success Response:**\

  - **Code:** 200\
    **Content:**\
           `{ 
              status : False,
              taskname : "taskname", 
              description : "description"
            }`
 
- **Error Response:**\

  - **Code:** 404 NOT FOUND\
    **Content:**\
           `{ 
              error : "eror description" 
            }`

## **clear Method**
----
	Return json data about added task.

- **URL**\
	/clear

## **GET_ALL**
----
	Return json data about added task.

- **URL**\
	""
