# Grocery CRUD Snippets Sublime 2/3
Snippets API and Functions list for Grocery CRUD http://www.grocerycrud.com/ by John Skoumbourdis

# Installataion
Install this snippets through the Package Control. Search for "Grocery CRUD Snippets myIgniter", install and enjoy!

# Usage
tap ```g-{function/api name}```

# Example
```
g-crud
```
will result
```PHP
$crud = new grocery_CRUD();
    
$crud->set_table('table');
$crud->set_subject('subject');

$output = $crud->render();
```
