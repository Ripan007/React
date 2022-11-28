## _useEffect:_

- use to handle sideEffects
- useEffect is a hook hence it is a function
- useEffect also takes callBack function
- call the callBack function on every rendering
- useEffect always get the updated state values

  - summary: something which is outside of function it is impure , it effect the function behavior , sideEffects are something which is asychronous in nature ,
  - api call , timer , interaction with dom , event listener, cleaning of event are called as sideEffects.

---

## _propsDrilling:_

- Unnecessary flow of data to components under which child components are nested is called propsDrilling.
- Solutions 👍:
  - lifting of state
  - context Api
  - Redux
- _lifting of state :_ passing the callback, calling the callback and receiving the data
- _Redux :_

  - problems solved by redux 😄 :
    - overload of data
    - props drillings
  - why used :

    - code become clumsy
    - which context calling which component become confusing(complex)
    - causing problem becoz of multiple contextApi
    - very vast data emission

  - why not used 😠:
    - more line of code , time , more maintenance

---

## _Higher order components:_

- takes a component and return a component
- it is a pure function
-
