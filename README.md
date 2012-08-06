#jQuery timepicker plugin
=========================
###*Looks like clock, work like clock!*

Cantipi is an acronym of Canvas TimePicker. 
Goal of the project is create the timepicker plugin similar to a clock, as we think of it. 
Timepicker based on HTML5 canvas element, so it require to use HTML5 browser. 


###Usage

  include plugin in head
  
  ``<script type="text/javascript" src="jquery.cantipi.js" ></script> ``

  and apply plugin to the input field
  
          $().ready(function(){
              $("#selector").cantipi({size: 150, roundto: 1});
          });
          
### Settings
  Settings is very simple: 
    1. size: Size of height and width in pixels
    2. roundto: Precision of time in minutes
  
### Future plans
  Make it skinnable. May be. May be you do it by yourself. I don't know...
  