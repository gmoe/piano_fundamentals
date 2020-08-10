# Fundamentals of Piano Practice

<a href='https://fundamentals-of-piano-practice.readthedocs.io/?badge=latest'>
  <img src='https://readthedocs.org/projects/fundamentals-of-piano-practice/badge/?version=latest' alt='Build Status' />
</a>

This is a [Sphinx][Sphinx] adaptation of the 2nd edition of Chuan C. Chang’s
excellent book, [Fundamentals of Piano Practice][3rd]. There are a quite few
improvements over the original PDF, including:

* Inter-document links
* Improved document formatting
* Mobile-friendly HTML version
* ePub for e-readers

I am not the author of this book, please consider supporting Chaun C. Chang by
buying the [paperback][paperback] or [Kindle version][kindle] of the 3rd
edition, or the [2nd edition paperback][paperback2] that this adaptation is
based on. The [3rd edition][3rd] addressed a lot of the issues of the original
2nd edition PDF such as inter-document links and it has more content.

[3rd]: http://pianopractice.org/
[Sphinx]: http://sphinx-doc.org/
[paperback]: http://www.amazon.com/gp/product/1523287225
[kindle]: http://www.amazon.com/gp/product/B01BI1P07W
[paperback2]: http://www.amazon.com/gp/product/1419678590

## Downloads

* [Online Book](https://fundamentals-of-piano-practice.readthedocs.io/)
* [PDF Download](https://fundamentals-of-piano-practice.readthedocs.io/_/downloads/en/latest/pdf/)
* [ePub Download](https://fundamentals-of-piano-practice.readthedocs.io/_/downloads/en/latest/epub/)

## Original Author Foreword

This is the best book ever written on how to practice at the piano! Most books
list what skills are needed (scales, arpeggios, trills, etc.), but not how to
acquire them. This book teaches how to solve technical problems, step by step.
Learn practice methods, how to acquire technique and memorize hours of
repertoire, sight reading, musical playing, relaxation, etc., and, most
importantly, Mental Play in which you learn to play the piano in your mind.
Mental play touches every aspect of piano playing, from memorizing, controlling
nervousness, developing performance skills, playing musically, etc., to
acquiring absolute pitch, composing and improvisation. It is almost
unbelievable that such an essential skill has been mostly neglected by piano
teachers. All great musicians used it, yet even they often failed to teach it.
We learn why the traditional methods of teaching piano widely used today are
the reasons why students give up piano.

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
