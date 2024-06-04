<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OU Cycling Club Admin App</title>
    <link rel="stylesheet" href="styles.css">
    
</head>
<body>
<header>
    <h1> OU Cycling Club</h1>
    <h2> Add a ride</h2>
</header>
    
    <div class="sidebar left-sidebar">
        <a href="">Add a ride</a> 

        <a href="">Admin log in</a> 

        <a href="">Edit membership</a> 

        <a href="">Club Announcments</a> 
        
    </div>
    <div class="content">
    <form action="https://students.open.ac.uk/mct/tt284/reflect/reflect.php" method="post" name="form1">
    <input type="hidden" name="SessionIdentifier" value="ff53-dd45-dcba9876-9090" />
    <p><b>Name of Ride: </b><input type="text" name="name_ride" value="Name of Ride" size="30" maxlength="30" /></p>

    <p><b>Type of Ride: </b><input type="text" name="type_ride" value="Type of Ride" size="30" maxlength="30" /></p>

    <p><b>Date of Ride: </b><input type="text" name="date_ride" value="Date of Ride" size="10" maxlength="10" /></p>

    <p><b>Start time: </b><input type="text" name="start_time" value="Start Time" size="10" maxlength="10" /></p>

    <p><b>Duration (minutes): </b><input type="number" name="duration" value="Duration" size="5" maxlength="5" /></p>

    <p><b>Elevation in m: </b><input type="number" name="elevation" value="elevation" size="5" maxlength="5" /></p>

    <p><b>Max group size: </b><input type="number" name="group_size" value="group_size" size="5" maxlength="5" /></p>

    <p><b>Name of Leader: </b><input type="text" name="leader_" value="Name of Leader" size="30" maxlength="30" />

    <p><b>Contact number: </b><input type="number" name="contact_number" value="contact_number" size="11" maxlength="11" /></p>

    <p><b>Alternative number: </b><input type="number" name="alternative_number" value="alternative_number" size="11" maxlength="11" /></p>

    <p><b>Comments:</b><br />

        <textarea name="comments" cols="35" rows="5">Type your comments here...</textarea></p>
    <p>Status<input type="radio" name="status" value="proposed" />Proposed<input type="radio" name="status" value="Approved"/>Approved <input type="radio" name="status" value="Rejected" checked="checked" />Rejected</p>

    <p><input type="submit" name="submit" value="submit" </p>

    <p><input type="reset" name="reset" value="reset"</p>

    </form>
    </div>
    <div class="sidebar right-sidebar">

        <a href="">Other events</a> 

        <a href="">Lorum ipsum</a> 

        <a href="">Lorum ipsum</a> 

        <a href="">Lorum ipsum</a>
        
    </div>
</body>
</html>
