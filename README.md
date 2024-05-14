# google-stock-data-prediction

Recurrent neural network are mostly used for predicting sequential or
temporal data. Due to shortcomings like vanishing gradients or exploding
gradients, long sequenced inputs sometimes are unable to train the
model properly. Hence, another type of RNN which is long short term
memory(LSTM) RNN is implemented to overcome those shortcomings of
RNN. A Google stock price, which is a temporal dataset, is used in this
project to highlight this issue. It can be seen in the experiments that
LSTM generalizes the model better than RNN. Although, some architectures
of RNN like Multiple input single output(MISO) and Multiple
input and multiple output(MIMO) are also compared. Which showed
that MIMO is superior over MISO.