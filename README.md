# Asset-Allocation-Models
Asset allocation using Long term recurrent convolution network (LRCN) architecture <br/>
The LSTM layer builds up an internal state using the Back Propagation Through Time (BPTT) technique to update the weights across a sequence of internal vector representations.

# Results
Singapore: Model performs poor in validation data.<br/>
Australia : Consistently improving training results, but equally bad validation results.<br/>
Austria: Both training and validation losses are poor.<br/>
Belgium: Model is a good fit, but the validation error has some spikes.<br/>
Canada: Training losses reduce over epochs, and validation losses stabilize in long run<br/>
Denmark, Finland, France, Israel, Italy, Japan, Singapore, Sweden: Training losses are reducing but validation losses are increasing (overfitting models)<br/>
Germany, Hong Kong, the Netherlands, Norway: Very strong models (Training and Validation losses become stable)<br/>
Ireland, Portugal, Spain, Switzerland: Models are weak<br/>
United Kingdom: Model Good fit and validation loss reduce considerably<br/>
USA : Good fit of the model on training data.<br/>

7/23 countries  has the good fit 
