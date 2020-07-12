# Domain Modeling

Domain modeling means creating a class or object that describes a real-world entity.

Create a controctor function to describe your object and make instance of it using let obj = new model(bla,bla,bla)

# Tables

tables are data containers which represent them using grids (row and columns)

## Table Structure

- \<table>: this is the container of the tags that bulid our table.
- \<tr>: to define a row
- \<td>: add row cell with a data
- \<th>: used to add heading to our table
- \<td colspan="2">: this will take 2 cols space
- \<td rowspan="2">: this will take 2 rows space

to make our table more organized:

- \<thead>: here we add our heading for our table
- \<tbody>: here we add our main content to our table
- \<tfoot>: here we add a total avg and conclusion stuff

# objects constructor

**This is how to create a constructor for an object**

---

function love(howMuch){

// some properties

this.howMuch:howMush

//some methods

this.moreLove = function () {

return this.howMuch++

}
}

---

for more info about objects

- [JS-Object-Literals-The-DOM](https://mohammad-eshtaiwi.github.io/reading-notes/JS-Object-Literals-The-DOM)
