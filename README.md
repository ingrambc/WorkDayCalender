# WorkDayCalender
This is a simple app that allows you to input and store task for an hour of your work day. Rows are dynamically color coded based on the current hour: gray has past, red is the current hour, and green is in the future. The calander is set to refresh and change the colors every 5 min according to the current time. Type in the text field for the hour row.  Clicking the save button will save the data to local storage.  Clicking the erase the data in the text field. 

# tech
built in Visual Studio Code
  using HTML, Javascript, Jquerry, CSS, Bootstrap

Icons are from fontAwesome

# FLow
Script starts with call to startTime to start time interval
  and to runCal to start calander

runCal gets current moment and stored data, calls displayCal

displayCal renders calander to screen, setting class for past, present, future

On button clicks
  saveBtn stores row to local storage, calls displayCal
  eraseBtn empties row in local storage, calls displayCal

