## Study on side effects

---

-2 Aug 2022-

- refactored project to demonstrate useImperativeHandle hook and discuss proper usage and examples of where this technique makes sense. Regular usage is however discouraged. This completes the current project for the time being and completes the module on side effects, reducers and the context api.

-1 Aug 2022-

- completed lecture discussing rules of using hooks for popular implementation.

- Refactored from utilization of context for our input components to reusable components that can just have their properties changed. This will lead into the next lecture on Forward Refs.

---

-24 July 2022-

- Discussed usefulness of context to break up creating a large chain of passed values back and forth for that data can be sent back and forth to multiple components in a more efficient manner. Next will be use of a hook for more elegant solution.

---

-21 July 2022-

- Discussed changes made through reformatting with useReducer and summarized when to useReducer vs useState. Essentially multiple related moving parts, vs small simple standalone tasks.

---

-20 July 2022-

- Use effect implemented in conjunction with use reducer so that state is always current and the effect only runs at determined requirement.

---

-18 July 2022-

- Began refactor utilizing useReducer.

---

-17 July 2022-

- Began discussion on useReducer and when it is appropriate to use. Essentially when a state update is dependent on another state. Because it may update one before the other finishes its update we want to reduce to a singular state.

---

-12 July 2022-

- Created a cleanup function that checks validity after every halfsecond and resets the timer every keystroke.

---

-11 July 2022-

- Began study of effects/side effects
- Discussion included what an effect is and when to use it. (ie run once at beginning of app vs. anytime state changes vs. not at all)
- Examples made for including dependencies and discussion of what dependencies should be included and excluded..

---
