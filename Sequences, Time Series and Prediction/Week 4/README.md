## Question 1: How do you add a 1 dimensional convolution to your model for predicting time series data?

- Use a 1DConv layer type
- Use a 1DConvolution layer type
- Use a Convolution1D layer type
> Use a Conv1D layer type

## Question 2: What’s the input shape for a univariate time series to a Conv1D? 

- [1, None]
- []
> [None, 1]
- [1]

## Question 3: You used a sunspots dataset that was stored in CSV. What’s the name of the Python library used to read CSVs?

> CSV
- CommaSeparatedValues
- PyCSV
-PyFiles

## Question 4: If your CSV file has a header that you don’t want to read into your dataset, what do you execute before iterating through the file using a ‘reader’ object?

- reader.read(next)
- reader.next
- reader.ignore_header()
> next(reader)

## Question 5: When you read a row from a reader and want to cast column 2 to another data type, for example, a float, what’s the correct syntax?

> float(row[2]) 
- You can’t. It needs to be read into a buffer and a new float instantiated from the buffer
- float f = row[2].read()
- Convert.toFloat(row[2])

## Question 6: What was the sunspot seasonality?

> 11 or 22 years depending on who you ask
- 22 years
- 4 times a year
- 11 years

## Question 7: After studying this course, what neural network type do you think is best for predicting time series like our sunspots dataset?

- DNN
- Convolutions
- RNN / LSTM 
> A combination of all of the above

## Question 8: Why is MAE a good analytic for measuring accuracy of predictions for time series?

- It punishes larger errors 
>  It doesn’t heavily punish larger errors like square errors do
- It biases towards small errors
-It only counts positive errors