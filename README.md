## Coding test

Consume data from an Server side Events(SSE) feed a enable querying the following operations:

1. An operation to list all the users that have received at least one exam score.
2. An operation to list all the exam results for a specified student ID.
3. An operation to list all the exams that have been recorded.
4. An operation to list all the results for a specified exam.



## consumer.py

	usage:
		nohup python consumer.py &

## query.py

	usage: query1.py [-h] [-u] [-s] [-e] [-r] [student] [exam]

	positional arguments:
		student        Students ID
		exam           The exam number to return results for


 	optional arguments:
		-h, --help     show this help message and exit
		-u, --users    list students that have received at least one exam score.
		-s, --scores   list all the exam results for a specified student ID.
		-e, --exams    list all the exams that have been recorded.
		-r, --results  list all the results for a specified exam.

