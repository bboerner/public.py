<!--
README generated with readmemako.py (github.com/russianidiot/readme-mako.py) and .README dotfiles (github.com/russianidiot-dotfiles/.README)
-->

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
