# ajaxcall.js
Ajaxcall.js allows you to Send Data via HTTP request, by assigning event handlers on HTML Elements. 

See Example below;
//This will assign an Event to that button when Clicked, to send request over GET
<button ajax-url="/api/follow/member/1">Follow Me</button>

//Appending Data
<button ajax-url="/api/follow/" ajax-data='{"member":1, "user":"facebook"}' > Follow me</button>

//This Ajax Call Supports also calling data over http to load element inside another element
<code ajax-loader="/api/listOfUsers">
</code>

//Enabling Ajax call on forms
Simple Add ajax-form attribute
<form ajax-form="true">
  </form>
