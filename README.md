jEntropy - a jQuery plugin
--------------------------

Description
===========
jEntropy is a random string/number generator using entropy collected from mouse movement as the seed for random content.

It can be used as way for users to generate passwords for themselves, generate password salts during account registration, or even manual session ID creation. There are other possible uses, generating encryption keys, and so on.

Usage
=====
The usage is rather simple. Just point the plugin to the target input field. 

		$(#inputID).jEntropy({
		          'option1' : 'value1',
		          'option2' : 'value2'
		});

Options
=======
The options you can set are:

rSize - the length of the generated string
pool - the characters used to generate the string (i.e. 'abcdefghijklmopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890'
message - the message you want to display to your users while they are generating the string
disable - boolean value which decides whether the input field should be disabled after the string has been generated

The plugin has been tested with jQuery 1.4 and 1.5. It's working on latest versions of Chrome, Firefox, Safari, IE and Opera.

License
=======
jEntropy is released under the MIT license. For more info, check the LICENSE file.

Author
======
Dino Paskvan (http://www.dinopaskvan.com)

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/DinoPaskvan/jentropy/trend.png)](https://bitdeli.com/free "Bitdeli Badge")