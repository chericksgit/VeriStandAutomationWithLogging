# VeriStandAutomationWithLogging

Provided by Andres Gomez on 10/4/19. Notes on the classes used within the .py files:

•	veristand_logging.py is a separate file that contains two classes and that the customer can reuse and expand.

o	Logging_Spec_File class: It can be used to parse information from the logging specification XML. For now, it only parses the list of channels and logging rate configured by the user but shouldn’t be very difficult to expand from there. Besides, by pulling the channels we have already saved most of the effort.

o	Logger class: I’ve wrapped inside this class the main functions to setup, start and stop the logging with a higher level of abstraction. Again, it is not complete but it should be a good starting point.

•	veristand_logging_example.py uses the above 2 classes and the Engine Demo Logging Spec to demonstrate the functionality.

Steps to run:
1.	Deploy Engine Demo from VeriStand 2019.
2.	Unzip attached file.
3.	Run veristand_logging_example.py script.
4.	At least 1 log with ~50 datapoints should be generated in the Logs folder next to the script.
