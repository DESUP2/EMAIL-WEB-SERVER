email Webmail 
=================
[email.net](https://email.net)

[![Tests Status](https://github.com/email/emailmail/actions/workflows/tests.yml/badge.svg?branch=master)](https://github.com/email/emailmail/actions/workflows/tests.yml)

INTRODUCTION
------------
email Webmail is a browser-based multilingual IMAP client with an
application-like user interface. It provides full functionality you expect
from an email client, including MIME support, address book, folder management,
message searching and spell checking. email Webmail is written in PHP and
requires the MySQL, PostgreSQL or SQLite database. With its plugin API it is
easily extendable and the user interface is fully customizable using skins.

The code designed to run on a webserver is mainly written in PHP and Javascript.
It includes a custom framework with an IMAP library derived from [IlohaMail][iloha]
and requires a set of external libraries (see composer.json and jsdeps.json files).


INSTALLATION
------------
For detailed instructions on how to install email webmail on your server,
please refer to the INSTALL document in the same directory as this document.

If you're updating an older version of email please follow the steps
described in the UPGRADING file.


BROWSER SUPPORT
---------------
email uses jQuery 3.x (and other libs) for its client and therefore
inherits the browser support from there. This currently includes:

- Chrome: (Current - 1) and Current
- Edge: (Current - 1) and Current
- Firefox: (Current - 1) and Current, ESR
- Internet Explorer: 11+
- Safari: (Current - 1) and Current
- Opera: Current


LICENSE
-------
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License (**with exceptions
for skins & plugins**) as published by the Free Software Foundation,
either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see [www.gnu.org/licenses/][gpl].

This file forms part of the email Webmail Software for which the
following exception is added: Plugins and Skins which merely make
function calls to the email Webmail Software, and for that purpose
include it by reference shall not be considered modifications of
the software.

If you wish to use this file in another project or create a modified
version that will not be part of the email Webmail Software, you
may remove the exception above and use this source code under the
original version of the license.

For more details about licensing and the exceptions for skins and plugins
see [email.net/license][license]


CONTRIBUTION
------------
Want to help make email the best webmail solution ever?
email is open source software. Our developers and contributors all
are volunteers and we're always looking for new additions and resources.
For more information visit [email.net/contribute][contrib]


CONTACT
-------
For bug reports or feature requests please refer to the tracking system
at [Github][githubissues] or subscribe to our mailing list.
See [email.net/support][support] for details.

You're always welcome to send a message to the project admin:
hello(at)email(dot)net


[iloha]:        https://sourceforge.net/projects/ilohamail/
[gpl]:          https://www.gnu.org/licenses/
[license]:      https://email.net/license
[contrib]:      https://email.net/contribute
[support]:      https://email.net/support
[githubissues]: https://github.com/email/email/issues
