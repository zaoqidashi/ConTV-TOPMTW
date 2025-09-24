# ConTV-TOPMTW
The dataset and solution of paper "The Two-Visit Team Orienteering Problem Considering Time-Interval-Dependent Profits and Service Consistency"

Instances_1 serves as the main datasets, while Instances_2 to Instances_9 are the datasets utilized in Section 5.5. 
Instances_2 is an instance set designed for scenarios featuring low time-sensitivity profit functions, long-duration services, and large lower bounds of the optimal interval.
Instances_3 is an instance set designed for scenarios featuring high time-sensitivity profit functions, long-duration services, and large lower bounds of the optimal interval.
Instances_4 is an instance set designed for scenarios featuring low time-sensitivity profit functions, short-duration services, and large lower bounds of the optimal interval.
Instances_5 is an instance set designed for scenarios featuring high time-sensitivity profit functions, short-duration services, and large lower bounds of the optimal interval.
Instances_6 is an instance set designed for scenarios featuring low time-sensitivity profit functions, long-duration services, and small lower bounds of the optimal interval.
Instances_7 is an instance set designed for scenarios featuring high time-sensitivity profit functions, long-duration services, and small lower bounds of the optimal interval.
Instances_8 is an instance set designed for scenarios featuring low time-sensitivity profit functions, short-duration services, and small lower bounds of the optimal interval.
Instances_9 is an instance set designed for scenarios featuring high time-sensitivity profit functions, short-duration services, and small lower bounds of the optimal interval.

The first number in the CSV filename indicates the number of patients for the instance, and the second number denotes the instance number corresponding to this scale.
The meanings of each column in the table are as follows:
N: Index of the patient
ZXi: x-coordinate of the patient
ZYi: y-coordinate of the patient
Bs,Be: Optimal range of time interval with optimistic profit for the patient
ai: Time Sensitivity for the patient
bi: Optimistic profit for the patient 
Ci: Maximum of the allowable interval for the patient
d1: Duration of the first service for the patient 
d2: Duration of the second service for the patient 
O1,C1,O2,C2,O3,C3,O4,C4：Time windows of the patient

