notifications Angular Module
=============================

Very barebone angular notifications module. Displays notifications in the screen by adding them to an array in a factory. No style.

Install
-------

Copy the notifications.js and notifications.css file into your project and add the following line with the correct path:

		<script src="/path/to/scripts/notifications.js"></script>

Alternatively, if you're using bower, you can add this to your component.json (or bower.json):

		"notifications": "git://github.com/standup75/notifications.git"

And add this to your HTML:

		<script src="components/notifications/notifications.js"></script>

As you can see, I have not written any stylesheet for this module, it's up to you to create it.

Usage
-----
		<notifications timeout="100"></notifications>

Where timeout is the time during which the notification should stay on the screen in ms/char

And don't forget to add the module to your application

		angular.module("myApp", ["notifications"])

Demo
----

Try the (very simple) demo. How to run the demo? Simple...

		git clone git@github.com:standup75/notifications.git
		cd notifications
		npm install && bower install
		grunt server

This should open your browser at http://localhost:9000 where the demo now sits.