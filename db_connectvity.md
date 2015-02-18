Database connectvity
$host = "host name";
$user = "user name";
$password = "password";
$dbname = "hss";
$connect = mysql_connect($host,$user,$password) or die(mysql_error);
$db = mysql_select_db($dbname, $connect) or die(mysql_error);
