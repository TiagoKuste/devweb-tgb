# RESTful-Routes
A guide for RESTful Routing 

<table class="table table-hover table-bordered">
			<thead>	
				<tr>
					<th>Name</th>
					<th>Path</th>
					<th>HTTP Verb</th>
					<th>Purpose</th>
					<th>Mongoose Method</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>Index</td>
					<td>/dogs</td>
					<td>GET</td>
					<td>List all dogs</td>
					<td>Dog.find()</td>
				</tr>
				<tr class="success">
					<td>New</td>
					<td>/dogs/new</td>
					<td>GET</td>
					<td>Show new dog form</td>
					<td>N/A</td>
				</tr>
				<tr class="success">
					<td>Create</td>
					<td>/dogs</td>
					<td>POST</td>
					<td>Create a new dog, then redirect somewhere</td>
					<td>Dog.create()</td>
				</tr>
				<tr class="info">
					<td>Show</td>
					<td>/dogs/:id</td>
					<td>GET</td>
					<td>Show info about one specific dog</td>
					<td>Dog.findById()</td>
				</tr>
				<tr class="warning">
					<td>Edit</td>
					<td>/dogs/:id/edit</td>
					<td>GET</td>
					<td>Show edit form for one dog</td>
					<td>Dog.findById()</td>
				</tr>
				<tr class="warning">
					<td>Update</td>
					<td>/dogs/:id</td>
					<td>PUT</td>
					<td>Update particular dog, then redirect somewhere</td>
					<td>Dog.findByIdAndUpdate()</td>
				</tr>
				<tr class="danger">
					<td>Destroy</td>
					<td>/dogs/:id</td>
					<td>DELETE</td>
					<td>Delete a particular dog, then redirect somewhere</td>
					<td>Dog.findByIdAndRemove()</td>
				</tr>
			</tbody>
		</table>
