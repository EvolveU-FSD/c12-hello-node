## Spicy

npm init a new package called fongo and create a some functions that do the following:

### Step 1
```
store(object)
```
  - if the object does not already have an "id" field, add one (use a variable that you increment each time)
  - use JSON.stringify to convert the object to text
  - use the fs package to store the text into a folder called "data" in a file with the name "\<id>.json"

```
retrieve(id)
```
  - try to load the file by the name \<id>.json into a string and parse it with JSON.parse
  - return the object you got (or undefined if you couldn't read it)

### Step 2
add collectionName to your functions, and store the files in a sub folder of that matches the collectionName.  Create a folder if it doesn't exist and you need it.

### Step 3 
use an environment variable to change the root "data" folder

### Step 4 
create a findAll function that returns all of the objects that are in a collection and returns them as an array

### Step 5 
Try to create a function that accepts a query parameter that filters the objects of a stored collection.