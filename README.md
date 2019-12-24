<?PHP
$username="ahmed";
$password="123";
$username="tarek";
$password="789";
// input
$dbusername="ahmed";
$dbpassword="123";
$dbusername="tarek";
$dbpassword="789";

// if
if ($username == $dbusername && $password==$dbpassword || $username == $dbusername && $password==$dbpassword)
{
		echo"hello <br/>";

}else if ($username == $dbusername&&$password !=dbpassword || $username == $dbusername&&$password !=dbpassword)
{
	echo "error "; 
}   echo "<hr/>";
$test1=1;
$test2=1;
if($test1==$test2){
    echo "True <br/>";}
$test1=1;
$test2=2;
if ($test1!=$test2){
	echo "false <br/>";
}
$name="test";
    echo "name <br/>";

$test1=3;
$test2=5;
    echo $test1+$test2; echo "<br/>";

$test1=2.00;
$test2=7;
    echo $test1*$test2; echo "<hr/>";
$today ="السبت";{
	echo "saturday <br/>";
}
$today ="الاحد";{
	echo "sunday <br/>";
}
$today ="الاثنين";{
	echo "monday <br/>";
}
$today ="الثلاثاء";{
	echo "tuesday <br/>";
}
$today ="الاربعاء";{
	echo "wednesday <br/>";
}
$today ="الخميس";{
	echo "thursday <br/>";
}
$today ="الجمعه";{
	echo "friday <br/>";
}
?>
