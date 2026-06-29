# Overview
I trained a dense neural network on Wisconsin Breast Cancer Dataset. The full explanation to the dataset can be found in wdbc.names.
## 📄 Link to dataset:
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic


## 🤖 The model
A sequential model is used, as follows:<br>
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

 Total params: 16,286 (63.62 KB) <br>
 Trainable params: 16,286 (63.62 KB)<br>
 Non-trainable params: 0 (0.00 B)<br>



## 📈 Results
The model is trained in 100 epochs and a validation split of 0.1, consistently reaching above 90 percent precision and recall.

<img width="500" height="400" alt="ebeb5e58-0117-4451-bc8a-7dc7137f0dc9" src="https://github.com/user-attachments/assets/94bce0a9-2cc7-46c8-8f06-361a13d274b2" />
<img width="500" height="400" alt="96f3dc5f-466f-4e7d-9d93-1ee84816bb5d" src="https://github.com/user-attachments/assets/42270a16-67f9-4c5e-b0c8-a0a59866f7c3" />
