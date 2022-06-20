# SISE2601 Project data description
### **Team P**

## The Data
Spike list/Potential action - records of transfer electronic signals between neurons.

The data contains 24 Excel files, produced automatically from the electrode array at selected times for 24 hours. 
Each has 5 columns and more than 400,000 rows.
<br/>
Each row is a record of the time and voltage of a specific neuron that sent an electrical signal.
The data is divided to time periods of the day and every Excel files describes different time period:

1. Before treatment.
2. 5 hours following the treatment.
3. 18 hours over the night after the treatment.

Each file contains the following columns:
1. "Investigator" and column no.2 (missing name) - General information about the recording, such as: "Experiment Start Time" (date), "Temperature", system specifications and setting, etc.
  "Investigator" - The title
2. cloumn no.2 - The information
3. "Time (s)" - Time record of transfer electronic signals by specific neuron, counted in seconds.
4. "Electrode" - ID number of neuron who transfer electronic signals at the specific time. 

    Details :
    ID number has 2 parts (separated by a lower dash): 
    part no.1 - well ID number 
    part no.2 - Electrode ID number
    
5. "Amplitude (mV)" - Measurement of the voltage of electronic signals who created by neuron, measured in millivolt.

At the end of the file there is information about each well, such as: the wells color, whether it is activated or not, the name of the treatment it received, concentration and whether its a control well or not.

