# Calculation-chart-of-classic-two-layer-net
Calculation chart of classic two-layer-net,including forward &amp; backward process.

### The meaning of the params:
* s: batch size,the number of samples in a batch.
* i: input size,the number of neurons in the input layer.
* h: hidden size,the number of neurons in the hidden layer.
* o: output size,the number of neurons in the output layer.

### Attentions:
* For any param x in the forward process,dL/dx in the backward process has the same shape of it.
* During the backward process of the sigmoid layer,the mutiplication object of the martrix is elements of the martrix rather than the whole martrix.(not dot()).
