1. What is the First Principle of Redux?
    - The first principle of Redux is that the entire state of the application is represented as a single JavaScript object. This centralized and immutable state makes it easier to manage and debug.

2. What is a Store and What Do We Use Our Reducers For Within That Store?
    - A store in Redux is an object that holds the entire state of the application. It acts as the central hub for state management, allowing components to subscribe to state changes, dispatch actions to update the state, and access the current state. Reducers are pure functions that take the current state and an action as arguments and return a new state. Within the store, reducers specify how the state should change in response to actions. They are the only way to update the state in Redux, ensuring changes are predictable and controlled.

3. Name Three Redux Store Methods Given to Us by createStore and Describe Their Use
    - getState():
    - Description: Returns the current state of the store.
    - Use: Used to access the state tree of the application at any time, allowing components to read the current state.

    - dispatch(action):
    - Description: Sends an action to the store.
    - Use: Used to trigger state changes by passing an action object to the reducers, which then compute and return the new state based on the action.

    - subscribe(listener):
    - Description: Adds a change listener that is called whenever the state changes.
    - Use: Used to register functions that need to be notified when the state changes, such as updating the UI in response to state updates.

4. Explain to a Non-Technical Recruiter What combineReducers() Does and Why It Is Useful
    - combineReducers() is a function that simplifies handling complex state management by allowing us to split the state into smaller, more manageable pieces. Each piece of state is managed by its own reducer function. Instead of having one large reducer function that handles all parts of the state, we can have multiple smaller reducer functions, each responsible for a specific part of the