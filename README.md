Introduction
------------

Django-fields is an application which includes different kinds of models fields.

Right now, application contains two fields with encryption support:
EncryptedCharField and EncryptedTextField.

Requirements
-----------

This application depends on *python-crypto*, which can be found in many Linux
repositories, or downloaded from http://www.dlitz.net/software/pycrypto/.

Under Ubuntu, just do:

    sudo apt-get install python-crypto

How to run tests
----------------

Examples can be found at the `examples` directory. Look at the, `tests.py`.
Same project is used to run unittests. To run them, just fire `./run-tests.sh`.

Contributors
------------

* [zbyte64](http://www.djangosnippets.org/users/zbyte64/) — thanks to for 
  his [django snippet](http://www.djangosnippets.org/snippets/1095/) for encrypted
  fields. After some fixes, this snippet works as supposed.
* John Morrissey — for fixing bug in PickleField.
* Joe Jasinski — different fixes and new fields for encripted email and US Phone.
* Colin MacDonald — for many encripted fields added.
* Igor Davydenko — PickleField.
