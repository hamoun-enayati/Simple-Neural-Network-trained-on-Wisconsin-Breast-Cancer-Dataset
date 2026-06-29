# Overview
I trained a dense neural network on Wisconsin Breast Cancer Dataset. The full explanation to the dataset can be found in wdbc.names.
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
    <td>dense_27 (Dense)</td>
    <td>(None, 100)</td>
    <td>3,100</td>
   </tr>
  
   <tr>
    <td>dense_28 (Dense) </td>
    <td>(None, 128)</td>
    <td>12,928</td>
   </tr>
   <tr>
    <td>dense_29 (Dense)</td>
    <td>(None, 2)</td>
    <td>258</td>
   </tr>
 </tablebody>
</table>

 Total params: 16,286 (63.62 KB)
 Trainable params: 16,286 (63.62 KB)
 Non-trainable params: 0 (0.00 B)


## 📈 Results
The model is trained in 100 epochs and a validation split of 0.1, reaching 96% precision and 98% recall on test data

