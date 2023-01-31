# CLI application

<h3>Functionality:</h3>
<ul>
<li>Allows to get all contacts from json file</li>
<li>Allows to get particular contact by ID</li>
<li>Allows to add new contact</li>
<li>Allows to remove any contact by ID</li>
</ul>

<h3>Usage:</h3>
<p>There are 4 types of commands for actions listed above. You can find examples below, please run the commands in the terminal. </p>
<ol>
<li>node index.js --action="list"<br style="color:#AAAB9D">Receive and display the entire list of contacts.</br></li>
<li>node index.js --action="get" --id=5<br>Receive and display particular contact.</br></li>
<li>node index.js --action="add" --name="Mango" --email="mango@gmail.com" --phone="322-22-22"<br>Add new contact to the list.</br></li>
<li>node index.js --action="remove" --id=3<br>Delete contact.</br></li>
</ol>
<!-- ![alt text](./screenShots/image_2023-01-30_23-39-23.png) -->
<img src="./screenShots/image_2023-01-30_23-39-23.png" width="500">
