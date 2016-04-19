![python](https://img.shields.io/badge/language-python-blue.svg)[![PyPI](https://img.shields.io/pypi/pyversions/public.svg)](https://pypi.python.org/pypi/public)

[![codacy.com](https://img.shields.io/codacy/6692c8b8d1194b3db696b456b683ad94.svg)](https://www.codacy.com/app/russianidiot-github/public-py/dashboard)[![landscape.io](https://landscape.io/github/russianidiot/public.py/master/landscape.svg?style=flat)](https://landscape.io/github/russianidiot/public.py/master)[![Code Climate](https://img.shields.io/codeclimate/github/russianidiot/public.py.svg)](https://codeclimate.com/github/russianidiot/public.py)
[![Code Health](https://scrutinizer-ci.com/g/russianidiot/public.py/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/russianidiot/public.py)

[![Build Status](https://travis-ci.org/russianidiot/public.py.svg?branch=master)](https://travis-ci.org/russianidiot/public.py)[![drone.io](https://drone.io/github.com/russianidiot/public.py/status.png)](https://drone.io/github.com/russianidiot/public.py)[![Wercker](https://img.shields.io/wercker/ci/russianidiot/public.py.svg)](https://app.wercker.com/#applications/None/)

[![PyPI](https://img.shields.io/pypi/v/public.svg)](https://pypi.python.org/pypi/public)
[![PyPI](https://img.shields.io/pypi/dm/public.svg)](https://pypi.python.org/pypi/public)
[![PyPI](https://img.shields.io/pypi/dd/public.svg)](https://pypi.python.org/pypi/public)

<p align="center">
	<b>@public decorator, public(*objects) function - add objects names to __all__</b>
</p>

#### Install

pip: 
`[sudo] pip install public`

#### Usage

```python
>>> from public import public

>>> @public # decorator

>>> public(*objects) # function

```

#### Example

```python
>>> @public
	def func(): pass

>>> @public
	class CLS: pass

>>> print(__all__)
['CLS',func']

# public(*objects) function
>>> public("name")
>>> public("name1","name2")

>>> print(__all__)
['name','name1','name2']

```

Sources:
*	[py_modules/public.py](https://github.com/russianidiot/public.py/blob/master/py_modules/public.py)

Feedback
[![GitHub issues](https://img.shields.io/github/issues/russianidiot/public.py.svg)](https://github.com/russianidiot/public.py/issues)
[![Join the chat at https://gitter.im/russianidiot/public.py](https://badges.gitter.im/russianidiot/public.py.svg)](https://gitter.im/russianidiot/public.py)
[![GitHub followers](https://img.shields.io/github/followers/russianidiot.svg?style=social&label=Follow)](https://github.com/russianidiot)

* * *

<p align="center">
	Python packages <a href="http://russianidiot.github.io/python/">russianidiot.github.io/python/</a>
	<img src="http://russianidiot.github.io/images/python/16.png" />
</p>
<p align="center">
	cli packages <a href="http://russianidiot.github.io/python/">russianidiot.github.io/cli/</a>
<img src="http://russianidiot.github.io/images/cli/16.png" />
</p>

<p align="center">
	repos list <a href="http://russianidiot.github.io/">russianidiot.github.io</a> <img src="http://russianidiot.github.io/images/star/16.png" />
</p>

<p align="center">
	<a href="https://raw.githubusercontent.com/russianidiot/public.py/master/README.md">README.md</a> generated with <a href="https://github.com/russianidiot/readme-mako.py">readmemako.py</a> (python+<a href="http://www.makotemplates.org/">mako</a> templates) and <a href="https://github.com/russianidiot-dotfiles/.README">.README</a> dotfiles 
<img src="http://russianidiot.github.io/images/book/16.png">
</p>
