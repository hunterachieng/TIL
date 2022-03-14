It is an array of variables that is used in many hooks within react. 

A react hook typically takes in two arguments, a callback function and a dependency array.

It basically means that the callback function will be called whenever the variable changes.

Example:

`const [data, setData] = useState(
() => {
setData();
}, [data]

)`

The above examples mean that anychange that occurs within the data variable will prompt the call back that updates the state to be called.
