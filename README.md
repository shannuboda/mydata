<html>
<head>
<style>
#customers {
  font-family: Arial, Helvetica, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

#customers td, #customers th {
  border: 1px solid #ddd;
  padding: 8px;
}

#customers tr:nth-child(even){background-color: #f2f2f2;}

#customers tr:hover {background-color: #ddd;}

#customers th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: RED;
  color: white;
}
</style>
</head>
<body>
	<script language="javascript">
<!--hide
var password;
password=prompt('ENTER YOUR HALLTICKET NUMBER ','');
if(password=="19KH1A0501")
{
<h1 align="center"> SVCK SUPPLY APPLICATION SUBJECTS </h1>
<h2> Name : <bold>B.SHANMUKHA SUBRAMANI</bold> </h2>
<h2> Roll Number : 19KH1A0512</h2>
<h2> COMPUTER SCIENCE AND ENGINEERING</h2>
<table id="customers">
  <tr>
    <th>SUBJECT</th>
    <th>PASS/FAIL</th>
    <th>select</th>
  </tr>
  <tr>
    <td>ALGEBRA & CALCULAS</td>
    <td>PASS</td>
    <td>  <input type="checkbox" id="male" name="gender" value="male"></td>
  </tr>
  <tr>
    <td> CHEMISTRY</td>
    <td>FAIL</td>
    <td>  <input type="checkbox" id="male" name="gender" value="male"></td>
  </tr>
  <tr>
    <td>PROBLEM SOLVING & PROGRAMMING</td>
    <td>PASS</td>
    <td>  <input type="checkbox" id="male" name="gender" value="male"></td>
  </tr>
</table>
	<p><input type="button" onclick='window.print()' value="print out "/></p>
else
{
alert('You Enterd A Wrong Hall Ticket Number Please Refresh The Page And Try Again');
}
function confirmRefresh() {
var okToRefresh = confirm("Do you really want to refresh the page?");
if (okToRefresh)
	{
			setTimeout("location.reload(true);");
	}
}
//-->
</script>
</body>
</html>
