I. File list
------------
bootstrap-fulldatepicker.js		
example.html


II. Design
----------
A. Program design

TO BE USED WITH:

bootstrap.css
bootstrap.js
jquery.js


1. Style
Original code did not handle picking year's, multiple events, or custom outputs on return, this file was edited and functionality was added to handle this.

2. Error handling
Problems were faced with event bubbling, calling the plugin with a jQuery document selector meant that the datepicker did not get called. Calling a specfic class, 'yeardate', was used to solve the issue. 