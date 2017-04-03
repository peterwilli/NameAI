Name AI
=======

This is the full source code for Name AI in a Jupyter Notebook. Name AI is an machine learning application that can come up with brandable domain names.

The source code is released under GPLv3 license.

How it works
============

For more understanding how it works, please refer to my blogpost: [Let AI come up with your next domain name!](https://codebuffet.co/2017/03/31/let-ai-come-up-with-your-next-domain-name/)

How to install & Run
====================

Assuming you have Ubuntu or another Linux-based system (Mac would work too, I guess).

It should work on Windows too but you're on your own with that :) If you do figure out how to run on Windows, please let me know, and I'll be happy to update the readme.

All the commands you have to enter in the terminal are `styled like this`!

1.	`git clone` this repo
2.	`cd` to this repository
3.	Make sure you have python and pip installed
	-	if not, run `sudo apt-get install python-pip` if you have Ubuntu or a Debian-based OS
4.	Install dependencies by running `pip install -r requirements.txt`
5.	Now run `jupyter notebook` to start the Jupyter-gui.
6.	After the browser has opened, select the NameAI.ipynb-file.
7.	Make sure you have sufficient data in a file named 'domains.txt' (a domain per line), and then click Cell -> Run All
8.	Wait and let the magic happen.
