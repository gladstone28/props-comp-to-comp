link to codecademy lesson:

https://www.codecademy.com/courses/react-101/lessons/this-props/exercises/pass-props-inter-component

link to source folder:

/c/Users/glads/Downloads/props-pass-props-from-component-to-component/props-comp-to-comp

link to AI:

https://chatgpt.com/c/14426d70-9262-425d-95e0-ff40af8c4e99

### PROPS

**Pass props From Component To Component**

You have learned how to pass a prop to a component:
```
<Greeting firstName="Esmerelda" />
```
You have also learned how to access and display a passed-in prop:

return <h1>{props.firstName}</h1>;

The most common use of props is to pass information to a component from a different component.

Props in React travel in a one-way direction, from the top to bottom, parent to child.

Let’s explore the parent-child relationship of passing props a bit further.
```
function App() {
    return <Product name="Apple Watch" price = {399} rating = "4.5/5.0" />;
}
```
In this example, App is the parent and Product is the child. App passes three props to Product (name, price, and rating), which can then be read inside the child component.

Props passed down are immutable, meaning they cannot be changed. If a component wants new values for its props, it needs to rely on the parent component to pass it new ones.

Let’s practice this!

### Instructions

Checkpoint 1 Passed

1. Your mission is to pass a prop to Player from App.

Ensure that Player can accept props by changing the function definition to include props in the parameter.

In the line that defines the function, include props as a parameter.

Checkpoint 2 Passed

2. Next, display the name of the song in the <h1></h1> tag by injecting the songName value from props.

Remember to use the dot (.) notation to access a property from props.

Checkpoint 3 Passed

3. Display the name of the artist in the <h2></h2> tag by injecting the artist value from props.

Remember to use the dot (.) notation to access a property from props.

Make sure to put it between the <h2> tags!

Checkpoint 4 Passed

4. Since App is passing props to Player, App is the parent and Player is the child.

Inside of Player.js, export the component to be used in App.js.

Recall using the export declaration to export components to other files.

Checkpoint 5 Passed

5. Open App.js. Import the Player component in App.js.

Recall using the import declaration to import components from other files.

Checkpoint 6 Passed

6. In the App component, call the Player component with the attributes songName, giving it a string of your favorite song, and the artist of the song.

Your Player component needs to be called with 2 values given to it: songName and artist. The syntax to pass a prop to a component looks as follows:
```
<Card name="Jasmine" />

```
