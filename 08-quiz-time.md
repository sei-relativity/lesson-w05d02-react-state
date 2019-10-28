# Quiz Time for React Props and State

<br>

1. Fork and Clone this repo.
2. Put your answers in this README
3. You may use any resource except each other.
4. Submit a pull request when you're done.

<br>

**Question 9.** 


What happens when you call `setState()`?

Choices:

1. The new state will be passed into the current state of the component. The virtual DOM tree is updated. A diff is run between the virtual DOM tree and the regular DOM tree. Only the correspondingly elements in the regular DOM tree will update.

2. The virtual DOM tree is updated. A diff is run between the virtual DOM tree and the regular DOM tree. The new state will be passed into the current state of the component. Only the correspondingly elements in the regular DOM tree will update.

3. The virtual DOM tree is updated. The new state will be passed into the current state of the component. Only the correspondingly elements in the regular DOM tree will update.


4. The new state will be passed into the current state of the component. Only the correspondingly elements in the regular DOM tree will update.


```
1. The new state will be passed into the current state of the component. The virtual DOM tree is updated. A diff is run between the virtual DOM tree and the regular DOM tree. Only the correspondingly elements in the regular DOM tree will update.
```

<br><br>

**Question 10.** 

If we have the code below, inside of the Painting component, will `dinosaur` be treated as a prop or a state?

```html
<Painting dinosaur="velociraptor" />
```

Choices:

1. `prop`
2. `state`


```
1. `prop`
```

<br><br>

**Question 11.** 


What is wrong with the below code? Choose all that apply.

```jsx
class Compliment extends Component {
  constructor () {
    state = {
      compliment = "You're so awesome!"
    };
  }
}
```

Choices:

1. You can't have a state with the same name as the component

2. State is set with `this.state`, not just `state`

3. State is set with colons, not equal signs. It should be `compliment: "You're so awesome!"`

4. Constructors need to begin with a call to `super()`

5. All of the above.


```
2. State is set with `this.state`, not just `state`
3. State is set with colons, not equal signs. It should be `compliment: "You're so awesome!"`
4. Constructors need to begin with a call to `super()`
6. You need the Render methode
```


<br><br>

**Question 12.** 


Using React, if you refresh a webpage, you never lose information since everything is stored in the component or browser state.

Choices:

1. `True`
2. `False`


```
2. `False`
```


<br><br>

**Question 13.** 

What is `map`?

Choices:

1. A map is like a `while` loop. With `map`, you use an existing iterator to navigate through each item until you break the loop.

2. A map is like a `for` loop. With `map`, you use an existing iterator to navigate through each item in an array.

3. A map is like a `for` loop. With `map`, you make a new variable and with it iterate through each item in an array.

4. A map is like a `while` loop. With `map`, you make a new variable and with it iterate through each item until you break the loop.


```
3. A map is like a `for` loop. With `map`, you make a new variable and with it iterate through each item in an array.
```


<br><br>

**Question 14.** 

Is the correct syntax for `map`?

```js
const drinks = ['tea', 'espresso', 'milkshake'];

const myDrinks = drinks.map( (soda, index) => {
  return 'I love' + soda;
});
```

Choices:

1. No - `soda` was never initialized
2. No - `index` is a keyword and cannot be used as a variable
3. No - the first line of the function should be `const myDrinks = map( (drinks, index)`
4. Yes


```
4. Yes
even if the index was never used
```



<br><br>

**Question 15.** 

Is the correct syntax for `map`, if the array is a prop named `Juice`?

```jsx
const Juices = this.prop.Juice.map((juiceType, index) => {
  return cuteJuice = 'I love' + juiceType;
});
```

Choices:

1. No - the array should be called with `this.props.Juice`, making it `this.props.Juice.map`

2. No - the array should be called with `Juice`, making it simply `Juice.map`

3. No - `juiceType` was never initialized

4. Yes


```
1. No - the array should be called with `this.props.Juice`, making it `this.props.Juice.map`
```


<br>
