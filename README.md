# Fundamentals of Piano Practice

<a href='https://fundamentals-of-piano-practice.readthedocs.io/?badge=latest'>
  <img src='https://readthedocs.org/projects/fundamentals-of-piano-practice/badge/?version=latest' alt='Build Status' />
</a>

This is a [Sphinx][Sphinx] adaptation of the 3nd edition of Chuan C. Chang’s
excellent book, [Fundamentals of Piano Practice][3rd], providing some formatting improements and a mobile-friendly HTML version.

I am not the author of this book, please consider supporting Chaun C. Chang by
buying the [paperback][paperback] or [Kindle version][kindle] of the 3rd
edition, or the [2nd edition paperback][paperback2]. The [3rd edition][3rd] addressed a lot of the issues of the original
2nd edition PDF such as inter-document links and it has more content.

[3rd]: http://pianopractice.org/
[Sphinx]: http://sphinx-doc.org/
[paperback]: http://www.amazon.com/gp/product/1523287225
[kindle]: http://www.amazon.com/gp/product/B01BI1P07W
[paperback2]: http://www.amazon.com/gp/product/1419678590

## Downloads

* [Online Book](http://fundamentals-of-piano-practice.readthedocs.org/en/latest/index.html)
* [PDF Download](https://media.readthedocs.org/pdf/fundamentals-of-piano-practice/latest/fundamentals-of-piano-practice.pdf)

## Original Author Foreword

This is the first book that teaches piano practice methods systematically, based on my lifetime of research, and containing the teachings of Combe, material from over 50 piano books, hundreds of articles, and decades of internet research and discussions with teachers and pianists. Genius skills are identified and shown to be teachable; learning piano can raise or lower your IQ. Past widely taught methods based on false assumptions are exposed; substituting them with efficient practice methods allows students to learn piano and obtain the necessary education to navigate in today's world and even have a second career.

## Local Development

Found a spelling mistake or want to port over more content? Want to build for a
different format?  You'll need to install [Python 3][py3] and set up a [virtual
environment][venv]. After installing the former this should be enough to get
your started:


```console
$ pip install virtualenv
$ virtualenv [--python=python3] env
$ source env/bin/activate
$ pip install -r requirements.txt
$ make html # or pdflatex, epub, etc.
```

[py3]: https://docs.python-guide.org/starting/installation/
[venv]: https://docs.python-guide.org/dev/virtualenvs/
