<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>Jquery Crud</title>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.8.1/css/all.min.css">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/css/bootstrap.min.css">
	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/flatpickr/dist/flatpickr.min.css">

</head>
<body> 
	<center>
		<br><br><br>
		<h1>Temporary Task Manager - TTM</h1>
		<br><br>
		<button id="newTask" class="btn btn-primary">Create</button>
		<div id="cr"></div>
		<br><br><br>

		<div class="col-md-7">
			<table class="table" id="userTables">
				<thead class="thead-dark">
					<tr>
						<th scope="col">Task Name</th>
						<th scope="col">Date</th>
						<th scope="col">Action</th>
					</tr>
				</thead>
				<tbody id="table">
				</tbody>
			</table>
		</div>

		<div id="tasks">  
		</div>

	</center>

	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.3.1/js/bootstrap.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/flatpickr/4.5.7/flatpickr.min.js"></script>

	<script>
		function edit(id){
      $("#newTask").hide();
      $("#task-"+id).show();
      
      $("#title-"+id).attr("id", "etitle-"+id);
      $("#date-"+id).attr("id", "edate-"+id);
      $("#save-"+id).attr("id", "esave-"+id);
      
      
      
			$("#gtitle-"+id).val($("#title-"+id).val());
			$("#gdate-"+id).val($("#date-"+id).val());
      
			$("input#date-"+id).flatpickr();

			$(document).on("click", "#esave-"+id , function(ev) {
				$('#table-'+id).remove();
				var title = $("#etitle-"+id).val();
	            var date = $("#edate-"+id).val();
	            var markup = "<tr id='table-"+id+"'><td id='title-"+id+"'>" + title + "</td><td id='date-"+id+"'>" + date + "</td> <td><button id='edit-"+id+"' name='"+id+"' class='btn btn-primary' onclick='edit("+id+")'>Edit</button> &nbsp <button id='delete-"+id+"' class='btn btn-primary' onclick='deleteTask("+id+")'>Delete</button></tr>";
	            $("table tbody").append(markup);
	            $("#task-"+id).hide();
	            $("#newTask").show();
        
	            // alert(title);
	            // alert(date);
			});
		}


			tasks = [];
			totalTaskCreated = 0;

			$("#newTask").on('click', function(ev) {
				let task = {title: "", contact:"", id:totalTaskCreated, deadline: ""}
        //addTask(task)
        create(task)
    		})

				

			function create(task) {
				$("#newTask").hide();

				$("#cr").append("<div id='task-"+task.id+"'> <input placeholder='Task Name' value='"+task.title+"' id='title-"+task.id+"'> <br><br> <input class='dateflatpickr' placeholder='Deadline Click' id='date-"+task.id+"'> <br><br> <button id='save-"+task.id+"' class='btn btn-primary'>Save</button> &nbsp <button id='cancel-"+task.id+"' class='btn btn-primary'>Cancel</button></div>")

				$("input#date-"+task.id).flatpickr();

				$(document).on("click", "#save-"+task.id , function(ev) {
						      var title = $("#title-"+task.id).val();
			            var date = $("#date-"+task.id).val();
			            var markup = "<tr id='table-"+task.id+"'><td id='gtitle-"+task.id+"'>" + title + "</td><td id='gdate-"+task.id+"'>" + date + "</td> <td><button id='edit-"+task.id+"' name='"+task.id+"' class='btn btn-primary' onclick='edit("+task.id+")'>Edit</button> &nbsp <button id='delete-"+task.id+"' class='btn btn-primary' onclick='deleteTask("+task.id+")'>Delete</button></tr>";
			            $("table tbody").append(markup);
			            $("#task-"+task.id).hide();
			            $("#newTask").show()
			            // alert(title);
			            // alert(date);
				});

				$(document).on("click", "#cancel-"+task.id , function(ev) {
					$("#task-"+task.id).hide();
					$("#newTask").show();
          //tasks[taskIndex].title = $(this).val();
      			});

      			

      			totalTaskCreated++;
			}

			
    function deleteTask(id) {
    	$("#table-"+id).remove();
    }

</script>

</body>
</html>