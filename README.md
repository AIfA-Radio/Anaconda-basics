# Anaconda-basics
Some of the basics of Conda. Includes installation and environment creation and deletion. 

Conda Cheat Sheet :

https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf

In case of doubts, drop an email to Ankur Dev (adev@astro.uni-bonn.de) 
-----------------------------------------------------------------------------------------------------------------------------

### Extra info:
**Installing from git source**

From within your environment, 
	
	conda install git pip
	pip install git+git://github.com/Netflix/metaflow.git
	
OR

To install Python package from github, you need to clone that repository.
First remember to activate your conda environment.

For example: 
	
	git clone https://github.com/jkbr/httpie.git
Then just run the setup.py file from that directory
	
	sudo python setup.py install
 
*P.S.: Not all of this is original material, but it is a nice compilation of information ! Have fun !*
