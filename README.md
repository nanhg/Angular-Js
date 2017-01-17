# Angular-Js


* Web site: https://angularjs.org
* Tutorial: https://docs.angularjs.org/tutorial
* API Docs: https://docs.angularjs.org/api

# Angular directives
* ng-app − This directive starts an AngularJS Application.
ng-app directive starts an AngularJS Application. It defines the root element. It automatically initializes or bootstraps the application when web page containing AngularJS Application is loaded. It is also used to load various AngularJS modules in AngularJS Application. 

* ng-init − This directive initializes application data.
ng-init directive initializes an AngularJS Application data. It is used to put values to the variables to be used in the application.

* ng-model − This directive defines the model that is variable to be used in AngularJS.
ng-model directive defines the model/variable to be used in AngularJS Application.

* ng-repeat − This directive repeats html elements for each item in a collection.
ng-repeat directive repeats html elements for each item in a collection.

# Controllers
AngularJS application mainly relies on controllers to control the flow of data in the application. A controller is defined using ng-controller directive. A controller is a JavaScript object containing attributes/properties and functions. Each controller accepts $scope as a parameter 
which refers to the application/module that controller is to control

# Angular Js filters
* Filters are used to change modify the data and can be clubbed in expression or directives using pipe character. 

# Angular views
# ng-view
* ng-view tag simply creates a place holder where a corresponding view (html or ng-template view) can be placed based on the configuration.

# ng-template
* ng-template directive is used to create an html view using script tag. It contains "id" attribute which is used by $routeProvider to map a view with a controller.

# Scope
* scope is a special javascript object which plays the role of joining controller with the views. Scope contains the model data. In controllers, model data is accessed via $scope object.

* Following are the important points to be considered in above example.

* $scope is passed as first argument to controller during its constructor definition.

* $scope.message and $scope.type are the models which are to be used in the HTML page.

* We've set values to models which will be reflected in the application module whose controller is shapeController.

* We can define functions as well in $scope.
