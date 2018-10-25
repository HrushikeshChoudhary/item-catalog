# Item Catalog Project  
## Instruction
To run the web application:  
1. Install Vagrant and Virtual Box  
2. Clone this repository  
3. Launch the Vagrant VM (by typing `vagrant up` in the directory */vagrant* from the terminal).  
4. From directory */vagrant/catalog*, initialize the application database by typing `python database_setup.py` follows by `python feedcatalog.py`.  
5. From directory */vagrant/catalog*, run the application within the VM by typing `python main.py` into the Terminal.  
6. Access the application by visiting http://localhost:8000 locally on the browser.

## Access URL for respective functionalities
1. API endpoints for:
	i. All users - /users.json
	ii. All categories and items - /catalog.json
	iii. All categories - /categories.json
	iv. All items of a specific category - /<category_name>/items.json
	v. An arbitrary item - /<category_name>/<item_name>/info.json
2. User Info - /user/<username>/<email>
3. Edit a Category - /catalog/<category_name>/edit
4. Delete a category - /catalog/<category_name>/delete
5. Show all items in a category - /catalog/<category_name>/items
6. Edit an item - /catalog/<category_name>/<item_name>/edit
7. Delete an item - /catalog/<category_name>/<item_name>/delete
8. Edit item image - /catalog/<category_name>/<item_name>/editimage 
9. Delete item image - /catalog/<category_name>/<item_name>/deleteimage
