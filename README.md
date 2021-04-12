# Modified_LSTM_with_pretraining
- In this work, I propose a new bi-directional LSTM network in which forward LSTM takes into account the complete input sequence.
- In the proposed architecture the forward and backward hidden states are not independent. This is achieved by feeding the hidden states of the backward LSTM as input to the forward LSTM along with the current input vector.
- I also implemented pre-training of new LSTM architecture using Masked Language modeling and Next Sentence Prediction so that it can be fine-tuned for other downstream tasks.
