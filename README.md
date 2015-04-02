## react-simple-dropdown

This is a very simple example of a [React](https://facebook.github.io/react) component.  
It creates a regular select dropdown. It builds on the HTML select by taking an array of objects (which must each contain values that can be used as the label and the value) and displaying them in the select. It also takes an optional callback that it will call when the onChange event occurs. This will pass back an object with the old and new values.  
In this example the array of data passed in is hard-coded but this is the base for another component which retrieves the data from an API. Because I might not have control of the names of the fields returned by the API, this component allows the field names to be mapped on input.
  
There is a JSFiddle using this code [here](http://jsfiddle.net/davidwaterston/7a3xxLtw/).
  
  
## License
Copyright (c) 2015 David Waterston. All rights reserved.
Distributed under an MIT license. See the [LICENSE](https://github.com/davidwaterston/react-simple-dropdown/blob/master/LICENSE) file for more details.
