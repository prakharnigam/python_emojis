# Python_emoji
Example

The entire set of Emoji codes as defined by the unicode consortium is supported in addition to a bunch of aliases. By default only the official list is enabled but doing emoji.emojize(use_aliases=True) enables both the full list and aliases.

>> import emoji
>> print(emoji.emojize('Python is :thumbs_up_sign:'))
Python is 👍
>> print(emoji.emojize('Python is :thumbsup:', use_aliases=True))
Python is 👍
Installation

Via pip:

$ pip install emoji --upgrade
From master branch:

$ git clone https://github.com/prakharnigam/python_emojis.git
$ cd emoji
$ python setup.py install
Developing

$ git clone https://github.com/prakharnigam/python_emojis.git
$ cd emoji
$ pip install -e .\[dev\]
$ nosetests
The utils/get-codes-from-unicode-consortium.py may help when updating unicode_codes.py but is not guaranteed to work. Generally speaking it scrapes a table on the Unicode Consortium's website with BeautifulSoup and prints the contents to stdout in a more useful format.

Link

Emoji Cheat Sheet

Official unicode list
