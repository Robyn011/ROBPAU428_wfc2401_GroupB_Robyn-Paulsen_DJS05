# DJS05: REDUX STORE FOR A TALLY APP
 
 ## Goal:
 Manage the app's state changes efficiently, focusing on core functionalities like **incrementing, decrementing, and resetting a counter.** Instead of rendering changes on the UI, you'll subscribe to state updates and log them to the console, highlighting the power of state management in applications.


 ## Scenarios & My Tasks:

 ### SCENARIO 1: Initial State Verification
 - **GIVEN** no interactions have been performed yet
 - **WHEN** the “getState” method is run
 - **AND** the result is logged to the console
 - **AND** the browser console is open
 - **THEN** the state should show a count of 0

 ### SCENARIO 2: Incrementing the Counter
  - **GIVEN** no interactions have been performed yet
  - **WHEN** an “ADD” action is dispatched
  - **AND** another “ADD” action is dispatched
  - **AND** the browser console is open
  - **THEN** the state should show a count of 2

 ### SCENARIO 3: Decrementing the Counter
  - **GIVEN** the current count in the state is 2
  - **WHEN** a “SUBTRACT” action is dispatched
  - **AND** the browser console is open
  - **THEN** the state should display a count of 1

 ### SCENARIO 4: Resetting the Counter
  - **GIVEN** the current count in the state is 1
  - **WHEN** a “RESET” action is dispatched
  - **AND** the browser console is open
  - **THEN** the state should display a count of 0

 #### In Progress:
  - None
  
