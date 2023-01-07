# Projet_web_S2_3INFO
Projet web de gestion de restaurant réalisé a la fin du 2éme semestre en 3éme année informatique

login admin
username= admin2
password= 123456789

Go to 'config' folder and Open 'constants.php' file. Then make changes on following constants

<?php 
    //Start Session
    session_start();


    //Create Constants to Store Non Repeating Values
    define('SITEURL', 'http://localhost/Projet_web_S2_3INFO-master/');
    define('LOCALHOST', 'localhost');
    define('DB_USERNAME', 'root');
    define('DB_PASSWORD', '');
    define('DB_NAME', 'food-order');
    
    $conn = mysqli_connect(LOCALHOST, DB_USERNAME, DB_PASSWORD) or die(mysqli_error()); //Database Connection
    $db_select = mysqli_select_db($conn, DB_NAME) or die(mysqli_error()); //SElecting Database


?>
<?php 
