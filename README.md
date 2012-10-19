coursera-dl
===========

A python package for archiving content from coursera.org (videos,
lecture notes, quizzes, …) for offline reference. Originally forked from
[https://github.com/abhirama/coursera-download][] but significantly
cleaned up and enhanced.

Installation
------------

Make sure you have installed [Python][] 2.7 and [pip][].

Then simply run: pip install coursera-dl

This will create a coursera-dl script in /usr/local/bin (linux) or
c:\\Pytohon2.7\\Scripts (windows)

(to upgrade use pip install --upgrade)

Usage
-----

See: coursera-dl -h

Example usage:

coursera-dl -u myusername -p mypassword -d /my/coursera/courses/
algo-2012-001 ml-2012-002

Note: ensure you have accepted the honor code of the class before using
this script (happens the very first time you go to the class page).

  [https://github.com/abhirama/coursera-download]: https://github.com/abhirama/coursera-download
  [Python]: http://www.python.org/download/
  [pip]: http://www.pip-installer.org/en/latest/installing.html
