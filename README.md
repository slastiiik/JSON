<h1 align="center">JSON</h1>
 
Create an remote repository named JSON.

A repository is created in github.

	=> respositories =>new

Clone the JSON repository to the local machine.

	git clone

Inside the local JSON, create a “new.json” file.

	touch new.json

Add file under git.

	git add new.json

Commit the file.

	commit –m “add new.json”

Submit a file to an external GitHub repository.

	git push

Edit the content of the “new.json” file - write information about yourself (full name, age, number of pets, future desired salary). Everything is written in JSON format.

	vim new.json

to start editing
	
	=> i

	{
		"Name":"Anastasia Aleksandrovna",
		"Age":"20",
		"Number of pets":"1 cute cat",
		"Future desired salary":"100 million"
	}

to exit editing
	
	=> esc => :wq

Push changes to an remote repository.
	
	git add new.json, git commit –m “edited content”, git push

Create preferences.json file
	
	touch preferences.json

In the preferences.json file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in JSON format.
	
	vim preferences.json

to start editing

	=> i
	
	{
		"Favorite Movie": "The Servant"
		"Favorite series": "Killing Eve",
		"Favorite Food": "Noodles"
		"Favorite season": "Spring and autumn",
		"Country I want to go to": "France"
	}

to exit editing

	=> esc => :wq

Create a file sklls.json add information about the skills that will be studied in the course in JSON format
	
	vim skills.json

to start editing
	
	=> i

	{
		"Skills": "Basic theory. HTTP structure and methods. JSON, XML, their structure. API testing via Postman. Mobile testing. SQL basics."
	}
	
to exit editing
	
	=> esc => :wq

Send 2 files at once to an external repository.
	
	git add .
	
	git commit –m “new json files”
	
	git push

On the web interface, create a bug_report.json file.

The bug_report.json file is created in the github.
	
	add file=>create new file

Commit changes on the web interface.
	
	сommit changes

On the web interface, modify the bug_report.json file, add a bug report in JSON format.

The bug_report.json file changes in the github.
	
	=>Edit this file

	{
		"Summary": "Persistent sneezing",
		"Project":"Nastya",
		"Component":"Nasopharynx",
		"Version":"1.20",
		"Severity":"S5 Trivial",
		"Priority":"P3 Low",
		"Status":"New",
		"Author":"Anastasia",
		"Assigned To": "Anastasia",
		"Description": "The bug was found at home, this error was caused by allergies or dust, take a deep breath and the error will repeat, error result: sneezing, expected result: no sneezing"	
	}
	
Commit changes changes on the web interface.

	сommit changes

Synchronize external and local JSON repository

	git pull (to check if everything is synced correctly use the git fetch command)
