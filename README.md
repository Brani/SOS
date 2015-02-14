Overview
========

This project is a simulation of an operating system and was created for a university 
course with another student, Zachary Calabrese. We created this program, os, which 
works with another program, sos, which was provided by our professor.

sos simulates a stream that sends os jobs and job requests.

os contains four files:
	*os.java, which contains interrupt handlers and other functions necessary to handle 
		the life cycle of each job and respond to job requests sent by sos.
	*freeSpaceTable.java, which represents a free space table
	*jobTable.java, which represents a job table
	*processControlBlock.java, which represents a process control block