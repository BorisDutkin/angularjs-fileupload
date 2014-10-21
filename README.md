angularjs-fileupload
====================

<h2><b><i>Installing & Useage:</i></b></h2>
  
<ol>
    <li>
        Include 'angular-file-upload.js' script to the html file.
    </li>
    <li>
        Include module dependency: angular.module('myApp', ['ngFileUpload']) ...
    </li>
    <li>
        Insert div with file-upload class in your controller in html.
    </li>
    <li>
        "file-upload" directive will automatically create $scope.formObject variable in your controller.
    </li>
    <li>
         Add data to the form if needed: $scope.formObject.setData({ name: '', email: '' }) ...
        <br />
        Submit the form by calling: $scope.formObject.submit() ...
    </li>
</ol>
