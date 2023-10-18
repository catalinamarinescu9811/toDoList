# toDoList

Steps:

1.HTML & CSS code

- div container
  - h1
  - Todo List
  - input tupe text
  - button - disabled by default

1. The "Add" must be enabled when use types in input

- if the user clears the input, the button should be disabled again
- create 2 variables containint hte input and button elements.
- add an event listener for input element(try using 'input' event - if doesn't work properly try using 'keyup' event )
- disabled property will be set to true when input value lenght > 0 otherwise false

3. The user should be able to add a new todo to the list
   - event listener - addButton
   - create li element containing value from input
   - append li element to list(ul)
   - add syles for li
   - clear selection from input
4. The user should be able to delete a todo
   - the creation of li element must include a button with x content
   - an event listener must be added when the button is created
   - the li that contains a button must be removed when delete button is clicked
