# A Simple TFJS layer input/output logger

This offers a simple wrapper-function that allows to log input and output of the layers in tfjs.

# Example

```
============================= LAYER 0
INPUT LAYER 0:
Tensor
    [[3, 4],
     [1, 2]]
OUTPUT LAYER0:
Tensor
    [[-6.8121476, 1.71753],
     [-2.9998806, 0.76652]]
============================= LAYER 1
INPUT LAYER 1:
Tensor
    [[-6.8121476, 1.71753],
     [-2.9998806, 0.76652]]
OUTPUT LAYER1:
Tensor
    [[2.9549246, 5.106863 ],
     [1.2918624, 2.2500386]]
```
