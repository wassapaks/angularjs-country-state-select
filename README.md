# angularjs-country-state-select
An angularjs directive package for selecting country and display its corresponding state.

# How to install
Install usering bower:

bower install angular-country-state-select --save<br><br>

Add to your app:

ngCountryStateSelect

# Usage
<pre>
<div ng-model="vm.country" country-select></div>

<div country="{{ vm.country }}" ng-model="vm.state" state-select></div>
</pre>