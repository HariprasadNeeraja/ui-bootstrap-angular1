# ui-bootstrap-angular1

Implementing ui-bootstrap in angular 1
This repository contains my work on learning angular1 with bootstarp.
Most of the ui-bootstrap are used as attributes.

# accordion.html

  1. uib-accordion-group is the parent element attribute for all the accordion elements .
   without this you can't able to view the element.
   2. uib-accordion-header is used to set the heading content. If you click the heading content you can able to view the element

   Note: uib-accordion-group is important, we can use other functions without it.

#Alert.html

   1. ui-alert is used for angular-bootstrap Alert
   2. we need to declare the call back function .
   3. In bootstrap we need to define our own icon for close. but in angular it was pre-defiend and we can use it for our call back functions.

   * I tried to pass the element id but still it is unsuccessful.
     If you want to pass id we need to use ng-init to declare the id and then we can use it.
     I don't know why the HTMl-DOM id element is not working.

# Button.html

    1. uib-btn-checkbox is the directive which has scope  
    btn-checkbox-true and btn-checkbox-false.
    2. ng-model is by default will be false.
    3. If the value is assigned it is taken.   

    Note:   uib-btn-checkbox is important without this other attributes are useless
