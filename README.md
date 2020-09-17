Seattle Traffic Accident Severity Prediction - Part 2

Data Section:

    The dataset regarding to this project contains all kinds of collisions in Seattle from 2004 to 2020. As we are targeting this study we should mostly pick the factors that are significant , controllable, changeable wrt the government. 'SEVERITYCODE' will be our target as it determines if the accident is sever or not. In the data available values of 'SEVERITYCODE' ranges from 1 to 2. It means if the accident is sever or not, with 1 being 'prop damage' and 2 being 'injury'.

Below mention are the factors or variables we'll be takink under consideration:
___________________________________________________________________________
Attribute	| Description
___________________________________________________________________________
JUNCTIONTYPE	| Category of junction at which collision took place.
---------------------------------------------------------------------------
INATTENTIONIND 	| Whether or not collision was due to inattention.(Y/N)
---------------------------------------------------------------------------
UNDERINFL	| Whether or not a driver involved was under the influence of drugs or alcohol.
---------------------------------------------------------------------------
WEATHER		| A description of the weather conditions during the time of the collision.
---------------------------------------------------------------------------
ROADCOND	| The condition of the road during the collision.
---------------------------------------------------------------------------
LIGHTCOND	| The light conditions during the collision.
---------------------------------------------------------------------------
SPEEDING	| Whether or not speeding was a factor in the collision. (Y/N)
---------------------------------------------------------------------------
HITPARKEDCAR	| Whether or not the collision involved hitting a parked car. (Y/N)
---------------------------------------------------------------------------
INCDTTM		| The date and time of the incident.
___________________________________________________________________________

Effect of all these variables on the severity will be determined and then the solution can be give in statement form, from the results obtained.
