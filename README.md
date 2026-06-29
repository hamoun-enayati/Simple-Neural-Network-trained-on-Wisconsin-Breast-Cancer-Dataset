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
</table>
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓
┃ Layer (type)                    ┃ Output Shape           ┃       Param # ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩
│ dense (Dense)                   │ (None, 100)            │         3,100 │
├─────────────────────────────────┼────────────────────────┼───────────────┤
│ dense_1 (Dense)                 │ (None, 1)              │           101 │
└─────────────────────────────────┴────────────────────────┴───────────────┘
 Total params: 3,201 (12.50 KB)
 Trainable params: 3,201 (12.50 KB)
 Non-trainable params: 0 (0.00 B)


The model is trained using 40 epochs with batch size = 64 and a callback with early stopping 
with min_delta = 0.02 and patience = 3.
