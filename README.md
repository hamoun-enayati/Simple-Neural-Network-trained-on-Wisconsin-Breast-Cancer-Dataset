# Overview
I trained a dense neural network on Wisconsin Breast Cancer Dataset. The full explanation to the dataset can be found in wdbc.names
## 📄 Link to dataset:
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic


## 🤖 The model
A sequential model is used, as follows:
 Model: "sequential_1"
Model: "sequential"

<table>
  <tablehead>
    <td>Layer (type)</td>
    <td>Output Shape</td>
    <td>Param #</td>
  </tablehead>
 <tablebody>
   <tr>
    <td>dense (Dense)</td>
    <td>(None, 100)</td>
    <td>3,100</td>
   </tr>
  
   <tr>
    <td>dense_1 (Dense) </td>
    <td>(None, 1)</td>
    <td>101</td>
   </tr>
 </tablebody>
</table>

 Total params: 3,201 (12.50 KB)
 Trainable params: 3,201 (12.50 KB)
 Non-trainable params: 0 (0.00 B)


## 📈 Results
The model is trained in 100 epochs and a validation split of 0.1, reaching 96% precision and 98% recall on test data

