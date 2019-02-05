![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Application State

### Author: Brent Woodward

### Links and Resources
* [repo](http://xyz.com)
* [Assignment 1 - Connection](https://codesandbox.io/s/r49x15qrko)
* [Assignment 2 - Reducers](https://codesandbox.io/s/21xw70n9ny)

### Modules
#### `Assignment 1`

###### `index.js`
Renders app.js to the DOM, and wraps App with Redux Provider that uses a Redux Store
###### `app.js`
Renders a div with an event listener, state is handled by Redux Store.
###### `store/actions.js`
Function used with handler to exicute functions when triggered. Accepts CHANGE.
###### `store/index.js`
Handles available reducers.
###### `store/reducers.js`
Provides default state and means to change state.


#### `Assignment 2`

###### `index.js`
Renders app.js to the DOM, and wraps App with Redux Provider that uses a Redux Store
###### `app.js`
Renders a div with an event listener, state is handled by Redux Store.
###### `store/app-actions.js`
Function used with handler to exicute functions when triggered. Accepts CHANGE.
###### `store/numbers-actions.js`
Function used with handler to exicute functions when triggered. Accepts CHANGE and RESET.
###### `store/index.js`
Handles available reducers.
###### `store/app-reducers.js`
Provides default state and means to change state.
###### `store/numbers-reducers.js`
Provides default state and means to change state.

#### UML
Link to an image of the UML for your application and response to events
