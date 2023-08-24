# Parkinson-s_Disease_Detection_using_ML_Techniques

This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds one of 195 voice recording from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to "status" column which is set to 0 for healthy and 1 for PD. <br>

The data is in ASCII CSV format. The rows of the CSV file contain an instance corresponding to one voice recording. There are around six recordings per patient, the name of the patient is identified in the first column.For further information or to pass on comments, please contact Max Little. <br> 

### Skills & Tools Covered:
1) Visualization of the data
2) Logistic Regression
3) LDA
4) Random Forest Classifier
5) Decision Tree
6) Support Vector Machine
7) Simple Neural Network


### Results:

<h3>Training Data:</h3>
<table border="1">
    <tr>
        <th></th>
        <th>Logistic Regression</th>
        <th>LDA</th>
        <th>Random Forest Classifier</th>
        <th>Decision Tree Model</th>
        <th>Support Vector Machine</th>
        <th>Simple Neural Network</th>
    </tr>
    <tr>
        <td>Accuracy</td>
        <td>0.88</td>
        <td>0.90</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>0.90</td>
        <td>1.0</td>
    </tr>
    <tr>
        <td>Precision</td>
        <td>0.89</td>
        <td>0.92</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>0.89</td>
        <td>1.0</td>
    </tr>
    <tr>
        <td>Recall</td>
        <td>0.96</td>
        <td>0.96</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.00</td>
        <td>1.0</td>
    </tr>
    <tr>
        <td>F1 Score</td>
        <td>0.93</td>
        <td>0.94</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>0.94</td>
        <td>1.0</td>
    </tr>
</table>

<h3>Testing Data:</h3>
<table border="1">
    <tr>
        <th></th>
        <th>Logistic Regression</th>
        <th>LDA</th>
        <th>Random Forest Classifier</th>
        <th>Decision Tree Model</th>
        <th>Support Vector Machine</th>
        <th>Simple Neural Network</th>
    </tr>
    <tr>
        <td>Accuracy</td>
        <td>0.86</td>
        <td>0.90</td>
        <td>0.93</td>
        <td>0.86</td>
        <td>0.86</td>
        <td>0.93</td>
    </tr>
    <tr>
        <td>Precision</td>
        <td>0.88</td>
        <td>0.91</td>
        <td>0.93</td>
        <td>0.93</td>
        <td>0.88</td>
        <td>0.93</td>
    </tr>
    <tr>
        <td>Recall</td>
        <td>0.95</td>
        <td>0.95</td>
        <td>0.98</td>
        <td>0.89</td>
        <td>0.95</td>
        <td>0.98</td>
    </tr>
    <tr>
        <td>F1 Score</td>
        <td>0.91</td>
        <td>0.93</td>
        <td>0.96</td>
        <td>0.91</td>
        <td>0.91</td>
        <td>0.96</td>
    </tr>
</table>

           


