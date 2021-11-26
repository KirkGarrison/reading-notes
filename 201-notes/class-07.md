## Object-Oriented Programming, HTML Tables

[Back page](/201-notes.md)

- Domain Modeling

1. When modeling a single entity that will have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the `new` keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the `this` variable within methods so you can access the object's properties and methods from inside.

From the Duckett HTML book:

- Chapter 6: “Tables” (pp.126-145)

    The `<table>` element adds tables to a web page. It is drawn row by row. Each row is created using the `<tr>` element (table row). Inside each row are a number of cells. Each cell represented by `<td>` or `<th>` for the header. You can make cells of a table span more than one row of column using **rowspan** or **colspan** attributes. For long tables you can split the table into a `<thead>`, `<tbody>`, and `<tfoot>`

From the Duckett JS Book:

- Chapter 3 Functions, Methods, and Objects (pp.106-144)

    Functions allow you to group a set of unrelated statments together for a single task. They can take parameters (info or data) and may return a value. An object is a series of variables and functions that represent something from the world around you. In an object variables are known as properties while functions are called methods of the object. Browsers have objects that represent both the browswer and the document loaded in it. Javascript also has several built in objects. Some of them are String, Number, Math, and Date. They offer functionality to help you write scripts. Arrays and objects can be used to create complex data sets and both can contain the other.