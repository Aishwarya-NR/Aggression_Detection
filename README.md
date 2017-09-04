# Aggression_Detection
The attached code and datasets were developed as a part of the Microsoft ASI (Artificial Social Intelligence) Workshop 2017. The code helps detect types of aggression in Hindi-English code-mixed data.
The analysis is done at 4 levels :



Aggressive--------------Non Aggressive (2 class)
 |				                    |
 |				                    |
 |				                    END
Covert/Overt/Non Aggressive  
(3 class)	
	|
	|
	|
Curse Abuse/Not Curse Abuse  
(2 class)
		|
		|
		|
Types of threat- Non threatening/ 
Physical threat/Sexual threat/ 
Identity threat  (5 class)
			|
			|
			|
		 END




Hindi-English code-mixed data from Twitter and Facebook was used for training the 4 stage classifier. Annotations were obtained from crowd-flower. Tagged Data sets can be found in the 'Dataset' folder.

###################################################################################################################################################################################################

###################################################################################################################################################################################################




Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

###################################################################################################################################################################################################

###################################################################################################################################################################################################


Prerequisites

python 2.7
NLTK Toolkit 3.2.x
SKlearn 0.18 

###################################################################################################################################################################################################

###################################################################################################################################################################################################


Installing

1) Type command ‘python all_features_test.py’ 					#takes about 4-5 minutes to run
2) A prompt saying- 'Enter your Sentence' shows up.
3) Type your sentence to obtain the 4 level aggression analysis.
4) Type 'exit' to finish.

###################################################################################################################################################################################################

###################################################################################################################################################################################################


Authors

Ritesh Kumar, Aishwarya Reganti, Akshit Bhatia, Purav Shah, Ramprashanth V, Tushar Maheshwari

###################################################################################################################################################################################################

###################################################################################################################################################################################################

For more information about the project visit:

- https://prezi.com/p/hxyc6ekm54vd/
- https://www.microsoft.com/en-us/research/video/detection-aggressive-behaviour-social-media/

