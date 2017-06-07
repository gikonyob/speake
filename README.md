# Speake

Speake library provides a wrapper around Espeak to easily
write efficient programs utilizing the text-to-speech functionalities
of espeak tts engine in Python.

## Installation

### Requirements
```
	- Linux system
	- Espeak
	- python2.x
```
### Install commands
````
	pip install speake
````


## Quick start
..code-block:: python

    >>> import speake
    >>> 
    >>> engine = speake.Speake()
    >>> engine.set('voice', 'en')
    >>> engine.set('amplitude', '107')
    >>> engine.set('pitch', '99')
    >>> engine.say("Hello world!")
    >>> engine.talkback()


    
