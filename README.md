# Fuzzy-Control

Project Idea: Implementing Fuzzy Logic as a control technique in Induction Motor for irrigation purpose in villages. 

The primary  dis-advantage in villages is the lack of suitable machinery cum technology in the department of irrigation. Also the variable conditions such as soil moisture , crop type , water levels, pressure etc need to be addressed.

Fuzzy logic - Deals with the ambiguity of the real world .
Delving deeper into the topic, fuzzy variables are not mathematical values such as numbers rather words/phrases that depict the present state of that variable . For instance , Soil moisture values could be terms like 'wet', 'moderately wet','Dry', 'Extremely Dry' and more such phrases could be defined that depict various other intermediate states rather than just wet and dry. These Fuzzy logic variables are called as 'Linguistic Values'.

Although these linguistic values are what gives fuzzy logic implementation  its meaning , definitely they are redundant without numerical values. This is where 'Membership functions' come into picture- as the term suggests these functions are indicative of the grade of membership of each variable. These functions completely map numerical range between absolute 0 and 1(like wet and dry in the context of soil moisture).

On a more detailed note, 'Membership function' tells us about the degree of how much of a particular value belongs to the set (60%,75%) unlike Classical set theory where an element only belongs to the set only if it is either 0% or 100%(Absolute values). 

Getting into the project;

Fuzzy logic implementation is sensible if there is impreciseness - various factors such as soil moisture , weather conditions, soil temperature etc make it suitable for this purpose.

Control Objective: Design a fuzzy logic controller to regulate induction motor speed of irrigation pump. 

Fuzzy Logic Variables:
1) Soil Moisture Content
2) Motor Speed
3) Soil Temperature
4) Flow Rate Demand
