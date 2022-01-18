# What is Components and Props and how to Create
With components we can split our UI into different Parts. A component is a Javascript function if we stop to think about it. They also accept incoming call Props

we can declare a component like this:
```bash
function helloWorld(props) {
    return <h1> hello World! Welcome to the new World {props.name} </h1>;
}
```
and also..
Javascript Class ES6
```bash
class helloWorld extends React.Component {
    render(){
        return <h1> Hello World! Welcome to the new World {props.name} </h1>;
    }
}

```
