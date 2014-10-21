angularjs-fileupload
====================

<b><i>Installing & Useage:</i></b>

1)  Include 'angular-file-upload.js' script to the html file.

2)  Include module dependency: angular.module('myApp', ['ngFileUpload'])...

3)  Insert div with file-upload class in your controller in html.

4)  "file-upload" directive will automatically create $scope.formObject variable in your controller.

5)  Add data to the form if needed: $scope.formObject.setData({ name: '', email: '' }) ...
    <br />
    Submit the form by calling: $scope.formObject.submit() ...
  
