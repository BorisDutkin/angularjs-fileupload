angularjs-fileupload
====================

Installing & Useage:

1)  Include 'angular-file-upload.js' script to the html file.

2)  Include module dependency: angular.module('myApp', ['ngFileUpload'])

3)  Insert '<div class='file-upload'></div>' in your controller.

4)  "file-upload" directive will automatically create $scope.formObject variable in your controller.

5)  Add data to the form if needed: $scope.formObject.setData({ name: '', email: '' })...
    Submit the form by calling: $scope.formObject.submit()...
  
