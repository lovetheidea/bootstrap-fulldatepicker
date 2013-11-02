1.Description
Add a bootstrap date picker to multiple field's or to any other element. 

2. Edits
Original code did not handle selecting year's only, multiple events, or custom titles and outputs, this file was edited and functionality was added to handle this.

3. Error handling
Problems were faced with event bubbling, calling the plugin directly with a jQuery 'document' selector meant that datepicker() did not get called on multiple fields.

4. File list
-bootstrap-fulldatepicker.js		
-example.html
-css/datepicker.css
-css/bootstrap.css (v2.1.1)

5. Program design

TO BE USED WITH:
------------
*bootstrap.css
*bootstrap.js
*jquery.js
------------

Call the datepicker via javascript:
$('.datepicker').datepicker()

formats: dd, d, mm, m, yyyy, yy
separators: -, /, .

For full datepicker methods please refer to:
http://www.eyecon.ro/bootstrap-datepicker.

