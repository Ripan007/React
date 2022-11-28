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

---

## _classComponent:_

- necessary thing to create a class component
  - render method is a required method
  - extends component from react
  - render method should also return something

-phases of life cycle of component:

- 1> creation phase /mounting phase
  - component get created for the first time
- 2> updation phase
  - component get updated , using setState function , calling setState, by updating value in content which is being used , by updating a state and props
- 3> removal phase / deletion phase / unmounting phases

---

- Method of class components
  - method in phase 1
    - constructor : it called and initialize property
    - super: connecting to parent class, create hierarchy,pass reference to parent ,
  - if we have to access props then we have to use constructor
  - initilize of state => possible only inside constructor

---

- how this keyword works:
  - in normal function this keyword point to caller function
  - points to environmnent
