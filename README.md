<div align="center">

## PHP IN HTML


</div>

### Description

<font face=arial color=green size=4>PHP IN HTML</font>

This Article , will let you know how to include a php file inside a html file ,

using inline floating frames.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[G\.Ajaykumar](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/g-ajaykumar.md)
**Level**          |Intermediate
**User Rating**    |2.5 (30 globes from 12 users)
**Compatibility**  |PHP 3\.0, PHP 4\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__8-1.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/g-ajaykumar-php-in-html__8-1044/archive/master.zip)





### Source Code

<table border="0" width="100%" cellspacing="0" cellpadding="0">
 <tr>
  <td width="100%"><font color="#0000FF" size="5">PHP IN HTML</font></td>
 </tr>
 <tr>
  <td width="100%">This Article , will let you know how to include a php file inside a html file&nbsp;<br>
   seamlessly, using inline floating frames.<br>
 Iframes are simple floating frames (HTML TAG) which can be placed at any required location on a html file. Iframe are said to be faster rendering, less memory, and faster scrolling. They can be stacked over other inline floating frames, Iframes can contain transparent content.<br>
   Iframe has an important attribute called as src which acquires the filename to load inside the Iframe, using this attribute you can specify the PHP file to load inside the IFRAME,<br>
   Which will resemble as if ,a HTML file were executed .<br>
   This technique is applied in many area , one of which is a news portal , which usually generates a static html file as home page and other content pages to save the bandwidth and cope with the heavy load . There is a location where they keep updating the Breaking news . Applying Php in HTML technique will be very useful , in this case , where php file might dynamically perform a dynamic operation to fetch the dynamic content .<br>
   and Iframe to display the dynamic contents with in a HTML page.<br>
   <br>
   <font color="#008000"><b>Let me explain practically how this works out&nbsp;</b></font><br>
   <br>
   Create two file named<br>
   <br>
   <font color="#000080">Test.htm<br>
   Test.php</font><br>
   <br>
   <font color="#800080">Code for Test.htm<br>
   &lt;html><br>
   &lt;head>PHP in HTML&lt;head><br>
   &lt;body><br>
   &lt;h2>&lt;font face=&quot;arial&quot; color="green">&lt;/font>&lt;/h2>&lt;br&gt;&lt;br><br>
   &lt;Iframe src="Test.php" width="300" height="600">&lt;/Iframe><br>
   &lt;/body><br>
   &lt;/html></font><br>
   <br>
   <font color="#008080">Code for Test.php&nbsp;<br>
   &lt;?phpinfo();?></font><br>
   <br>
   <font color="#800000">Description :</font> Test.htm contains contains the tag Iframe in it , the attribute src="Test.php" of the Iframe Sets or retrieves a URL to be loaded by the object Iframe .<br>
   Width and height attributes specifies the width and height of the Iframe in pixels or in percentage.<br>
   <br>
   Coming to the Test.php , &lt;?phpinfo?>this script displays the php configuration file .<br>
   <br>
   Put the files in your webserver root folder (ie wwwroot folder)<br>
   <br>
   Now run the Test.htm, you will be able to see the Test.php loaded inside the Iframe, on the Test.htm&nbsp;<br>
   <br>
   This technique can be applied to include any file into HTML file</td>
 </tr>
 <tr>
  <td width="100%"><font color="#800000"><b>Article By</b></font></td>
 </tr>
 <tr>
  <td width="100%"><b><font color="#0000FF">G.Ajaykumar</font></b></td>
 </tr>
 <tr>
  <td width="100%"><font color="#800000"><b>Jr. Systems Analyst</b></font></td>
 </tr>
 <tr>
  <td width="100%"><font color="#800000"><b>Ferntech Systems Pvt. Ltd</b></font></td>
 </tr>
</table>
<p><br>
</p>

