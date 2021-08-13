# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
    The context api allows for componets 3 levels down to recieve data defined 3 levels above withous having to pass it to all components in between

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    Actions are ar predefined ways of modifying state that allow us to manage all the ways our state can change. The reducer takes those actions and runs the changes in a way that exclusivley produces immmutable values. The store stores those values so that we can check on the history of our state for the sake of debugging.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
    Redux Thunk allows us to run async actions like api calls via functions returned by other functions and add such actions to our reducer and action list.

4. What is your favorite state management system you've learned and this sprint? Please explain why!
    I prefer the context api because of how basic and simple it is. It only takes 2 lines to get started and then you can reference that data anyhere in your component tree!