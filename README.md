A flask app prototype of the Rewind vinyl crowdfunding service. 

edit by harry

Getting the dependencies:
	
	pip install -r requirements.txt 

Then, to run it:

	python setup.py
	(Requires internet access)

For Admin Access (need this to see news managing system):

	username: admin
	password: password

Important Notes:

    models.py contains a function for inserting records into the database. This method is not used within the site, and is mean't for developers to include
    more records in the database when they deem necessary.

    Use this method from an interactive python terminal like iPython.

