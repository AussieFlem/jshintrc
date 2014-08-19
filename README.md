jshintrc
========

When I started using jshint to lint my code, I wasn't initially sure which options were available and what I should be using. I setup this file based on the docs at http://www.jshint.com/docs, and decided to put it up in case it saves someone the time of punching in the standard options for themselves.

In summary, this is an example of a .jshintrc file showing all the options currently explained at http://www.jshint.com/docs/options/

JSHint will start looking for this file in the same directory as the file that's being linted. If not found, it will move one level up the directory tree all the way up to the filesystem root.

All enforcing options are on, all relaxing options are off. Ext global is shown as an example.

Any thoughts and feedback welcome :)
