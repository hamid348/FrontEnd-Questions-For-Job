**Function and Class Components**
The simplest way to define a component is to write a JavaScript function:

***function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}***
This function is a valid React component because it accepts a single “props” (which stands for properties) object argument with data and returns a React element. We call such components “function components” because they are literally JavaScript functions.

You can also use an ES6 class to define a component:

***class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}***
The above two components are equivalent from React’s point of view.
