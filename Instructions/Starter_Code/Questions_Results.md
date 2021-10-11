Stock predictor closing and Stock predictor fng inputs:
window_size = 10
epochs = 10
batch size = 90
dropout_fraction = .2
number_units = 30

Which model has a lower loss? fng = loss: 0.0961, stock predictor = loss: 0.0093
STOCK PREDICTOR

Which model tracks the actual values better over time? Looking at the line graph, the stock predicotr trends better.
STOCK PREDICTOR

Which window size works best for the model?
fng window size 20 = loss: 0.0868
fng window size 10 = loss: 0.0961
fng window size 5 = loss: 0.0954

fng window size 20


stock predictor window size 20 = loss: 0.0217
stock predictor window size 10 = loss: 0.0093
stock predictor window size 5 = loss: 0.0313

stock predictor window size 10