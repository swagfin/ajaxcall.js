# ajaxcall.js
Ajaxcall.js allows you to Send Data via HTTP request, by assigning event handlers on HTML Elements. 

See Example below;
<h3 class="ui header blue">TEST A BUTTON [ajax-url]</h3>
  <div class="ui divider"></div> 

    <p align="center">
        <button class="ui basic blue button" ajax-url="http://localhost/test/test_server.php" ajax-type="POST" ajax-data='{"name":"John Kiringel", "age":30, "city":"New York"}'><i class="plus icon"></i>New Folder</button>
    </p>
	
<h3 class="ui header blue">TEST A DIV [ajax-loader]</h3>
  <div class="ui divider"></div> 
	




<br />
<code>
 ajax-url="/api/follow/"
</code>
<br />  
  //Use Ajax Call with Data
 <code>
 ajax-url="/api/follow/" ajax-data='{"member":1, "user":"facebook"}' 
 </code>
 <br />
 //Enable Ajax Call on Forms
  <code>
  ajax-form="true"
  </code>
  <br />
  //Ajax Loaders
  <code>
  ajax-loader="http://api.testexample.com"
  </code>
