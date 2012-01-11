Kimai - jQuery Mobile Interface
===============================

This repository keeps a mobile optimized version of Kimai.

Its not only a small interface, that lets you start and stop your time record, 
but is also a demonstration of the Kimai Remote API (which is available for JSON and SOAP).

Currently this jQuery mobile powered script can:

* let you log in
* read projects
* read customers
* read tasks
* start the timer
* stop the timer

It uses the JSON API and is only a bunch of HTML and Javascript files with 
some CSS sugar on top. 

Please note, that this is the first release and many features of the 
complete version are missing. We plan to add more features soon, until then
please share your thoughts and featre requests at [our forum](http://forum.kimai.org)!

Installation
------------

To install this mobile interface, simply copy all the content of this directory
into your kimai/ directory in a sub-directory called for example "mobile_new".
Then point your browser to http://yourDomain/kimai/mobile_new/ and log in with your
normal Kimai account.

Compatibility
-------------

This mobile tracking software only works with Kimai revision 1353 and later!

Contributing
------------

We would love to get input from all you talented developer out there:

1. Fork this repository
2. Create a branch (`git checkout -b my_kimai_mobile`)
3. Commit your changes (`git commit -am "Added foobar"`)
4. Push to the branch (`git push origin my_kimai_mobile`)
5. Create an [Issue][1] with a link to your branch
6. Now enjoy the latest episode of Big Bang Theory while we review your changes

Links
-----

You can get more information about Kimai:

* at our [official website](http://www.kimai.org)
* at our [Kimai forum](http://forum.kimai.org)
* in our [documentation pages](http://www.kimai.org/en/documentation/)

Thanks to the [jQuery mobile Team][2]!

[1]: https://github.com/kimai/kimai-mobile/issues
[2]: http://jquerymobile.com/
