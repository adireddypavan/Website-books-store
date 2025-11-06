[frame.html](https://github.com/user-attachments/files/23385599/frame.html)
<html>
<head><title> Amazon </title></head>
<frameset rows= "20%, 80%">
<frame src="head.html" name=head scrolling=no >
<frameset cols="20%,80%" >
<frame name="left" src=left.html>
<frame name="right" src=right.html>
</frameset></frameset>
</html>


[left.html](https://github.com/user-attachments/files/23385627/left.html)
<html>
<body bgcolor="pink">
<h3><ul>
	<li><a href=right.html target="right"> Home </a>
	<li><a href=login.html target="right"> Login</a>
	<li><a href=registration.html target="right"> Registration </a>
	<li><a href=books.html target="right"> Books </a>
	<li><a href=shop.html target="right"> Shopping </a>
	<li><a href=order.html target="right"> Order </a>
</ul></h3>
</body>
</html>


[right.html](https://github.com/user-attachments/files/23385660/right.html)
<html>
<body bgcolor="pink">
<b>
<p> Welcome to AITS online book shop.Here you can find number of books you want.Please register with your e-mail id.</p>
</b></body> 
</html>

[login.html](https://github.com/user-attachments/files/23385692/login.html)
<html>
<body bgcolor="pink">
<p><b><font color=white > Sign in </font></b></p>
<b> Enter your e-mail id </b> <br>
<input type="text" size=30 name=eid ><br><br>
<b> Enter your password </b><br>
<input type=password size=30 name=pswd><br><br>
<input type=submit value="Sign in" > <br><br>
<b> Don't you have account <br>
Please <a href=registration1.html> Sign up </a></b>
</body>
</html>


[registration.html](https://github.com/user-attachments/files/23385747/registration.html)
<html>
<body bcolor="pink">
<h1 align=center > Registration form </h1>
<table cellspacing=2 cellpadding=5 >
<tr><td colspan> First Name </td>
<td colspan=2><input type=text name=frame size=25> </tr>

<tr><td colspan> Last Name </td>
<td colspan=2><input type=text name=frame size=25> </tr>

<tr><td colspan=2> Enter your e-mail id </td>
<td colspan=2><input type=text name=eid size=25> </tr>

<tr><td colspan> Enter password </td>
<td colspan=2><input type=password name=pswd size=25> </tr>

<tr><td colspan> Re-enter password </td>
<td colspan=2><input type=password name=pswd size=25> </tr>

<tr><td colspan=2 > Date of Birth </td>
<td colspan=2 >
<select>
<option value=1 selected > Days </option>
<option value=2 >01</option>
<option value=2 >02</option>
<option value=2 >03</option>
<option value=2 >04</option>
<option value=2 >05</option>
<option value=2 >06</option>
<option value=2 >07</option>
<option value=2 >08</option>
<option value=2 >09</option>
<option value=2 >10</option>
<option value=2 >11</option>
<option value=2 >12</option>
<option value=2 >13</option>
<option value=2 >14</option>
<option value=2 >15</option>
<option value=2 >16</option>
<option value=2 >17</option>
<option value=2 >18</option>
<option value=2 >19</option>
<option value=2 >20</option>
<option value=2 >21</option>
<option value=2 >22</option>
<option value=2 >23</option>
<option value=2 >24</option>
<option value=2 >25</option>
<option value=2 >26</option>
<option value=2 >27</option>
<option value=2 >28</option>
<option value=2 >29</option>
<option value=2 >30</option>
<option value=2 >31</option>
</select>

<select>
<option value=1 selected>month</option>
<option value=2 >jan</option>
<option value=3 >feb</option>
<option value=4 >mar</option>
<option value=5 >apr</option>
<option value=6 >may</option>
<option value=7 >jun</option>
<option value=8 >jul</option>
<option value=9 >aug</option>
<option value=10 >sep</option>
<option value=11 >oct</option>
<option value=12>nov</option>
<option value=13 >Dec</option>
</select>

<select>
<option value=1 selected >Years</option>
<option value=2 >1986</option>
<option value=2 >1987</option>
<option value=2 >1988</option>
<option value=2 >1989</option>
<option value=2 >1990</option>
<option value=2 >1991</option>
<option value=2 >1992</option>
<option value=2 >1993</option>
<option value=2 >1994</option>
<option value=2 >1995</option>
<option value=2 >1996</option>
<option value=2 >1997</option>
<option value=2 >1998</option>
<option value=2 >1999</option>
<option value=2 >2000</option>
</select></tr>

<tr><td colspan=2 > Gender </td>
<td colspan=1> <input type=radio name=g> Male </td>
<td colspan=1> <input type=radio name=g> Female </td>
</tr>

<tr><td colspan=2 > Country </td>
<td colspan=2 >
<select>
<option value=1 selected > Select Country </option>
<option value=2 >Australia</option>
<option value=2 >Brazil</option>
<option value=2 >China</option>
<option value=2 >Denmark</option>
<option value=2 >India</option>
<option value=2 >Kenya</option>
<option value=2 >Malashia</option>
<option value=2 >Newzeland</option>
<option value=2 >Spain</option>
</select></td>

<tr>
<td colspan=4> Choose your Security Question </tr>
<tr><td colspan=2> First Question </td>
<td colspan=2>
<select>
<option value=1 selected > Choose Question </option>
<option value=2  > What is your FavouriteFood?</option>
<option value=2 > What is your First achivement ? </option>
<option value=2 > Who is your Best Friend? </option>
<option value=2 > What is your nick name?</option>
<option value=2 > </option>
</select></td>

<tr><td colspan=2> Second Question </td>
<td colspan=2>
<select>
<option value=1 selected > Choose Question </option>
<option value=2  > Who is your Favourite Actor?</option>
<option value=2 > which is your first journey? </option>
<option value=2 > Who is your Best Cricketer? </option>
<option value=2 > What is your childhood food?</option>
<option value=2 > </option>
</select></td>

<tr><td colspan=4> Verification Code </td></tr>
<tr>
<td colspan=4><input type=text name=vercode size=25></tr>

<tr><td colspan=2> Terms & conditions </td>
<td colspan=2><textarea rows=5 cols=15>
	Hello every body this the terms and conditions of this site.
please read carefully and then click the accept button,otherwise you can't create account
</textarea></tr>

<tr><td colspan=4><input type=button value=submit size=10>
<td colspan=2> <input type=reset value=clear size=10></tr>
</table>
</body> 
</html>

[head.html](https://github.com/user-attachments/files/23385862/head.html)
<html>
<head><title>Annamacharya University </title></head>
<body bgcolor="pink">
<table width=100%>
<tr><td><font color=red><h1 align=center> Annamacharya University</h1>
<h2 align=center> Book Sales </h2></font>
<td rowspan=2><img src=C:\pavan adireddy height=100 width=150 >
</tr></body>
</html>


[order.html](https://github.com/user-attachments/files/23385869/order.html)
<html>
<body bgcolor="pink">
<h3 align=center>Payment Order</h3>
<b>Please enter your credit card details</b>
<table border=0 cellspacing=2 cellpadding=8>
<tr><td>Credit card number</td>
<td><input type=text size=25></td>
</tr>
<tr>
<td>SRC number</td>
<td><input type=text size=6></tr>
<tr>
<td>Validity</td>
<td><Input type=text size=4>Month
<td><Input type=text size=5>Year
</tr>
<tr>
<td><input type=button value="Confirm your payment">
</tr></table></body>
</html>


Shop.html

<html>
<body bgcolor="pink">
<table border=0 cellpadding=5 cellspacing=2>
<tr>
<td>Book Title</td>
<td><input type=text size=25></td>
</tr>
<tr>
<td>Author</td>
<td><input type=text size=25></td>
</tr>
<tr>
<td>Edition</td>
<td><input type=text size=25></td>
</tr>
<tr>
<td>Publication</td>
<td><input type=text size=25></td>
</tr>
<tr>
<td>Price</td>
<td><input type=text size=25></td>
</tr>
<tr>
<td><input type=button value="Add to cart">
</tr>
</table>
</body>
</html>



[Books.html](https://github.com/user-attachments/files/23385912/Books.html)

<html>
<body bgcolor="pink">
<center><b> Books Available </b></center><br>
<table border=5 bordercolor=#bce253 cellspacing=2 cellpadding=2>
<tr>
<th>Book Title </th>
<th>Author</th>
<th>Edition</th>
<th>Publication</th>
<th>Price</th>
<th>Add to cart</th>
</tr>

<tr>
<td>Software Engeeniring</td
<td>Ian Sommerville</td>
<td>8th</td>
<td>pearson Education</td>
<td>$1.9</td>
<td><input type=button value="Add to cart"></td>
</tr>

<tr>
<td>System software</td>
<td>Donovan</td>
<td>2nd</td>
<td>Tata McGraw Hill</td>
<td>$1.4</td>
<td><input type=button value="Add to cart"></td>
</tr.

<tr>
<td>Advanced Java for web Technologies </td>
<td>Patrick naughtonand herbert Schildt</td>
<td>2nd</td>
<td>SPD </td>
<td>$2.5</td>
<td><input type=button value="Add to cart"></td>
</tr>

<tr>
<td>Data warehousing and data mining</td>
<td>Jiawei Han and Micheline kamber</td>
<td>2nd</td>
<td>Morgan kallfman</td>
<td>$1.2</td>
<td><input type=button value="Add to cart"></td>
</tr>

<tr>
<td>Cloud Computing</td>
<td>Michael miller</td>
<td>5th</td>
<td>Pearson Education</td>
<td>$1.2</td>
<td><input type=button value="Add to cart"></td>
</tr>
<tr>
<td>distributed databases
<td>stefano ceri
<td>3rd
<td>pearson eduction
<td>$1.6
<td><input type=button value="Add to cart">
</tr></table></body></html>
 
order.html


<html>
<body bgcolor="pink">
<h3 align=center>Payment Order</h3>
<b>Please enter your credit card details</b>
<table border=0 cellspacing=2 cellpadding=8>
<tr><td>Credit card number</td>
<td><input type=text size=25></td>
</tr>
<tr>
<td>SRC number</td>
<td><input type=text size=6></tr>
<tr>
<td>Validity</td>
<td><Input type=text size=4>Month
<td><Input type=text size=5>Year
</tr>
<tr>
<td><input type=button value="Confirm your payment">
</tr></table></body>
</html>
