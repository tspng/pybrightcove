# Introduction

The purpose of this library is to wrap up all the communication details 
of using the Brightcove 3 Media APIs so that the developer using the 
library can focus on just writing Python.


### Links

* [Media API Reference](http://help.brightcove.com/developer/docs/mediaapi/media-API.cfm)


### Running Tests
To run tests we recommend installing [`py.test`](http://pypi.python.org/pypi/pytest), possibly any other test runner
like `unit2` or `Nose` will do but `py.test` is known to work. To install it
do:

    pip install pytest

Note how the name is dotless. To actually start running the tests you can call
`py.test` from anywhere in the project just as long as the test files are
either in the current directory or lower in the directory tree.

If you are using Vim as your text editor, you can also install
[`pytest.vim`](http://www.vim.org/scripts/script.php?script_id=3424) which
allows you to run tests from the editor without needing to go back to the
terminal.
