#Read07

## Tables

The `<table>` tag defines an HTML table.

Each **table** row is defined with a `<tr>` tag. Each table header is defined with a `<th>` tag. Each table data/cell is defined with a `<td>` tag.

By *default*, the text in `<th>` elements are bold and centered.

By *default*, the text in `<td>` elements are regular and left-aligned.

`<table>`	Defines a table
`<th>`	Defines a header cell in a table
`<tr>`	Defines a row in a table
`<td>`	Defines a cell in a table
`<caption>`	Defines a table caption
`<colgroup>`	Specifies a group of one or more columns in a table for formatting
`<col>`	Specifies column properties for each column within a `<colgroup>` element
`<thead>`	Groups the header content in a table
`<tbody>`	Groups the body content in a table
`<tfoot>`	Groups the footer content in a table


## Functions, Methods, and Objects

A method is a function associated with an object, or, put differently, a method is a property of an object that is a function. Methods are defined the way normal functions are defined, except that they have to be assigned as the property of an object. See also method definitions for more details. An example is:

objectName.methodname = functionName;

`var myObj = {
  myMethod: function(params) {
    // ...do something
  }

  // OR THIS WORKS TOO

  myOtherMethod(params) {
    // ...do something else
  }
};`
where objectName is an existing object, methodname is the name you are assigning to the method, and functionName is the name of the function.

You can then call the method in the context of the object as follows:

object.methodname(params);
You can define methods for an object type by including a method definition in the object constructor function. You could define a function that would format and display the properties of the previously-defined Car objects; for example,

function displayCar() {
  var result = `A Beautiful ${this.year} ${this.make} ${this.model}`;
  pretty_print(result);
}
where pretty_print is a function to display a horizontal rule and a string. Notice the use of this to refer to the object to which the method belongs.

You can make this function a method of Car by adding the statement

this.displayCar = displayCar;
to the object definition. So, the full definition of Car would now look like

function Car(make, model, year, owner) {
  this.make = make;
  this.model = model;
  this.year = year;
  this.owner = owner;
  this.displayCar = displayCar;
}
Then you can call the displayCar method for each of the objects as follows:

car1.displayCar();
car2.displayCar();