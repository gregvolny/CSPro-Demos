# CSPro-Demos
Repositories for CSPro powered demos applications
# Dynamic-Checkbox-Demo
A demo application concerning using JS-CSPro API (https://www.csprousers.org/help/CSPro/javascript_interface.html) to display dynamic checkbox based on list and array. Until Version 7.7, the only way to have checkbox in a CSPro application was to have items in the dictionary. This prevented application developers to implement dynamic checkboxes.
This demo give us a great way to have a more dynamic "on the fly" checkboxes. Thanks to Gregory H Martin for providing CSProusers support for a better understanding of HTML Dialogs inputs (https://www.csprousers.org/forum/viewtopic.php?t=5313). This demo app is implementing a small lib to simplify this task. It based on the following two functions:
SelectJson with three arguments: a) A string: titleName who will display the heading text for the checkbox dialog; b) A list string: headerCaption who have two items for displaying text for column heading; c) A two dimensions string array: data who have data/items who'll be selected; This function will output a Json string following the same logic of the one that Gregory H Marting posted for displaying checkboxes with htmlDialog.
extractNumeric with a string argument: alphanumeric This function will parse the result of the htmlDialog (in the demo: showCsproValueInSelect function) and extract a list of numeric indexes;
TO DO: i) Use the result of extractNumeric and loop it in with the array used as the argument of SelectJson and having the final string. ii) Cleaning the logic. In the actual logic there's a double loop. However, I'm using only one. It's because I was seeking a way to use a single argument name for whatever array or using an Hashmap.
# CSMapTest
It's a V 8.0 beta port of a V 7.7 "almost ready to use" CSPro Logic library for creating, displaying and saving vector points with toolstips and binder tooltips on Leaflet and CSPro Map. We can also, trace, modify, display and save polygons. Please see https://www.csprousers.org/forum/viewtopic.php?t=5561 and read the basic ppt presentation about it. It worked almost well when tested with legacy .dat files and V 7.7. However the V 8.0 isn't finalized because of some issues in CSPro 8.0 beta. Notice: Data (Points) used in this application comes from National Center for Geospatial Information (CNIGS-Haiti). I randomly add French and Haitian names and surnames. So they are not other than mock PII!
# LoadMultiPolygons
It's a CSPro 7.7 demo designed for supporting CSProuser: https://www.csprousers.org/forum/viewtopic.php?p=16951
# CSPro 8 Test demo
It's a basic  demo for testing the new Sqlite Action Invoker Namespace. Mainly, filing a multidimensional array (more than 3 dimensions).I also want to receive messages posted by postWebMessage directly in CSPro logic. Until today the  CS.getWindowForEventListener().addEventListener("message", (event) => { isn't directly available inside CSPro logic.

