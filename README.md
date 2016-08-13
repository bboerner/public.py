<!--
README generated with readmemako.py (github.com/russianidiot/readme-mako.py) and .README dotfiles (github.com/russianidiot-dotfiles/.README)
-->

![python](https://img.shields.io/badge/language-python-blue.svg)
[![PyPI](https://img.shields.io/pypi/pyversions/public.svg)](https://pypi.python.org/pypi/public)[![PyPI](https://img.shields.io/pypi/v/public.svg)](https://pypi.python.org/pypi/public)

[![codacy.com](https://api.codacy.com/project/badge/Grade/6692c8b8d1194b3db696b456b683ad94)](https://www.codacy.com/app/russianidiot-github/public-py/dashboard)
[![landscape.io](https://landscape.io/github/russianidiot/public.py/master/landscape.svg?style=flat)](https://landscape.io/github/russianidiot/public.py)
[![codeclimate.com](https://codeclimate.com/github/russianidiot/public.py/badges/gpa.svg)](https://codeclimate.com/github/russianidiot/public.py)
[![scrutinizer-ci.com](https://scrutinizer-ci.com/g/russianidiot/public.py/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/russianidiot/public.py/)

[![drone.io](https://drone.io/github.com/russianidiot/public.py/status.png)](https://drone.io/github.com/russianidiot/public.py)
[![scrutinizer-ci.com](https://scrutinizer-ci.com/g/russianidiot/public.py/badges/build.png?b=master)](https://scrutinizer-ci.com/g/russianidiot/public.py/)
[![semaphoreci.com](https://semaphoreci.com/api/v1/russianidiot/public-py/branches/master/shields_badge.svg)](https://semaphoreci.com/russianidiot/public-py)
[![shippable.com](https://api.shippable.com/projects/57068cbb2a8192902e1bbbd6/badge?branch=master)](https://app.shippable.com/projects/57068cbb2a8192902e1bbbd6/status/)
[![travis-ci.org](https://api.travis-ci.org/russianidiot/public.py.svg)](https://travis-ci.org/russianidiot/public.py)
[![wercker.com](https://app.wercker.com/status/f9a3b6fa3f83012adafea514154b8b37/s/master)](https://app.wercker.com/#applications/5702681e4b64a4362009961b)

<p align="center">
    <b>@public decorator, public(*objects) function - add objects names to __all__</b>
</p>

#### Install

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

[Examples/](https://github.com/russianidiot/public.py/tree/master/Examples)

Feedback
[![GitHub issues](https://img.shields.io/github/issues/russianidiot/public.py.svg)](https://github.com/russianidiot/public.py/issues)
[![Join the chat at https://gitter.im/russianidiot/public.py](https://badges.gitter.im/russianidiot/public.py.svg)](https://gitter.im/russianidiot/public.py)
[![GitHub followers](https://img.shields.io/github/followers/russianidiot.svg?style=social&label=Follow)](https://github.com/russianidiot)
