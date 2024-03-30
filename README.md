# GCN_detect_bitcoin_money_laundering
This project attempts the use new techniques in the field of AML applied to the bitcoin blockchain.

file list
 2_GCN.ipynb, clientCN.ipynb,clientGCN2.ipynb,server.ipynb
 implementation of a GCN network in keras and subsequent evaluation and applying federated learning on implemented GCN model
 
Federated Client

A flower class client is defined that participates in the Federated Learning.

The three functions of the federated client:
get parameters,fit and evaluate
are written to perform their respective tasks.

The above methods are implemented to get the model parameters, train the
model locally on the private dataset and evaluate the model on the same.

Finally, the client receives global model parameters, trains locally, and sends
back updated parameters to the server for aggregation.
