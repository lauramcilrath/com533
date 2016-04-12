<!DOCTYPE html>
<html>
	<head>
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.2.0/jquery.min.js"></script>
	<script src="w3.js"></script>
	<script src="http://code.jquery.com/jquery-1.7.1.min.js"></script>
    <script src="jquery.tmpl.js"></script>
   <script src="knockout-x.y.z.js"></script>
	</head>
	
	<body>


		<div id_"films">
			<h3>This list should show all of the films in your database</h3>
			<ul id="film_list">
				
			</ul>
			<ul id="single_film_list">
				
			</ul>
		</div>
		<br><br>
		
		<div class="mainArea">
			<h3>Get a film by an ID</h3>
			<label>Get a film by the id (enter an id into this box):</label>
			<input type="text" id="id" name="id" required> 
			<button id="btnGet">Get Film</button>
		</div>
		<br><br>

		<div class="mainArea">
			<h3>Add a film to the database</h3>
			<label>Title:</label>
			<input type="text" id="title" name="title" required> 
			<label>Category:</label>
			<input type="text" id="category" name="category"/> 
			<label>Description:</label>
			<input type="text" id="description" name="description"/> 
			<button id="btnSave">Save</button>
		</div>
		<br><br>
		
		<div class="mainArea">
			<h3>Update the details of a film entry (must have a valid ID)</h3>
			<label>Title:</label>
			<input type="text" id="updatetitle" name="name" required> 
			<label>Update Category:</label>
			<input type="text" id="updatecategory" name="category"/> 
			<label>Update Description:</label>
			<input type="text" id="updatedescription" name="description"/> 
			<label>Update id:</label>
			<input type="text" id="updateId" name="id"/> 
			<button id="btnUpdate">Update</button>
		</div>
		<br><br>
		
		<div class="mainArea">
			<h3>Delete a film by their ID</h3>
			<label>Delete id:</label>
			<input type="text" id="deleteId" name="id"/> 
			<button id="btnDelete">Delete</button>
		</div>
		
	</body>
</html>
