# CGM Prediction
 Continous Glucose Monitoring

In this project, we will develop a continuous meal detection method from glucose monitor data of a 
subject. You will be given CGM sensor outputs for a given person for nearly 6 months. The CGM output 
is every 5 mins. You will also be given ground truth for every meal instance. You will have to develop a 
continuous meal detection algorithm. 

Task list
1) Parse CGM data and synchronize meal ground truth with CGM data
2) Write four algorithms for online detection of meal event
a. Auto regression based modeling of CGM
    i) Algorithm development, SARIMA
   ii) Algorithm Instantiation
   iii) Algorithm implementation
   iv) Training and Testing accuracy
b. Model based meal detection
   i) Algorithm development, RNN GRU 
   ii) Algorithm Instantiation
   iii) Algorithm implementation
   iv) Training and Testing accuracy
c. Kalman Filter based meal detection
    i) Algorithm development 
    ii) Algorithm Instantiation
    iii) Algorithm implementation
    iv) Training and Testing accuracy
d. RNN based meal detection
    i) Algorithm development (Use Tensor Flow) -->RNN LSTM
    ii) Algorithm Instantiation
    iii) Algorithm implementation
    iv) Training and Testing accuracy
3. Apply your algorithms to a new patient 
4. Provide Execution time analysis 
