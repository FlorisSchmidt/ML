# ML
Machine Learning project about prediction ICU admissions following an operation

# Deep Learning Algorithm 
We will conduct this research for the company Chipsoft. Chipsoft is an Amsterdam based software company which develops software for the healthcare sector. Chipsoft will deliver us a dataset from which we can derive information about patients during a surgery. The umbrella term PDMS will be used to refer to the data. PDMS stands for Patient Data Management System. 

## Describing the data
Our data is provided by Chipsoft. The data is a csv file which consists of the following columns: 1. MeetTijd 2. HR (bpm) (Heartbeat) 3. SpO2(%) (Oxygenation) 4. NIBP(mmHg) 5. IcNaOk

In the following format

| MeetTijd                                          |                                           HR(bpm) | SpO2(%)                                           | NIBP(mmHg)                                        | IcNaOk |
|---------------------------------------------------|--------------------------------------------------:|---------------------------------------------------|---------------------------------------------------|--------|
| [10:26:49, 10:27:49, 10:28:49, 10:29:50, 10:32... | [83, 90, 85, 89, 87, 85, 89, 84, 89, 84, 82, 9... | [98, 98, 98, 98, 98, 98, 98, 98, 98, 98, 98, 9... | [154, 154, 154, 154, 152, 152, 152, 131, 131, ... | 0      |
| [15:06:54, 15:07:54, 15:08:54, 15:09:55, 15:10... | [51, 53, 52, 53, 52, 55, 53, 56, 60, 50, 50, 5... | [92.5, 94, 92, 93, 93, 92, 92, 92, 93, 98, 97,... | [156, 156, 156, 158, 158, 158, 157, 157, 157, ... | 1      |
| [08:31:20, 08:32:21, 08:33:21, 08:34:21, 08:35... | [63, 67, 67, 102, 99, 98, 80, 81, 76, 76, 94, ... | [98, 99, 99, 99, 99, 99, 98, 98, 98, 98, 98, 9... | [160, 160, 160, 145, 145, 145, 174, 174, 174, ... | 0      |


## The research question will be:
##### How does the architecture of the Neural Network influence whether someone will end up at the intensive care unit or will have complications following surgery given their PDMS?

## Sub-questions:
### Theoretical:
    1. What is a patient data management system?
    2. How does a deep learning machine algorithm work?

### In Practice:
    1. Can we find correlations in the data that can give us useful insights?
    2. Can we provide the sergeants with insights derived from the data during the surgery
