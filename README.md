# Lightning Learn MobX

## The concept behind the technology:

- React and MobX together are a powerful combination. React renders the application state by providing mechanisms to translate it into a tree of renderable components. MobX provides the mechanism to store and update the application state that React then uses. 

- People often use MobX as alternative for Redux. But please note that MobX is just a library to solve a technical problem and not an architecture or even state container in itself. In that sense the above examples are contrived and it is recommended to use proper engineering practices like encapsulating logic in methods, organize them in stores or controllers etc. 

## Outlining of findings while using this technology:

- autorun
- observable
- observer decorator
- using ES6 getters and setters
- computed values
- pluralize

## Link to all relevant resources:

MobX
- https://mobx.js.org/
- https://github.com/mobxjs/mobx

Demo used for this lightning learn from this repository application:
- [https://github.com/mobxjs/mobx-react-todomvc] written using MobX, React JSX and ES6.

Great YouTube Web Tutorials:

MobX tutorial #1 - MobX + React is AWESOME
- https://www.youtube.com/watch?v=_q50BXqkAfI

MobX tutorial #2 - Computed Values and Nested/Referenced Observables
- https://www.youtube.com/watch?v=nYvNqKrl69s
