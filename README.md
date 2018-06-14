# Transfer Slip OCR

Implemented using Keras & Tensorflow


## Objective

Small and medium merchants in Thai who has adopt online store has been growing in numbers.
Merchants who are self-operate online store usually opt for personal bank transfer for merchandise payment and transfer slips are used to verify transactions.

This project initate a part of solution to help merchants verify their payment transaction which would 1) read information about transcation and then 2) bank owner would be able to verify if such transaction exists.

This initation use Machine Learning to solve the first part where it should read arbitary transaction slip. The first version will use slip generated from one bank mobile application, the app should be able to read transfer amount up to 99999.99 (8 character width). ML will be trained with a blank slip template which transfer randomly generated. 

This ML uses CNN to extract image features & RNN (GRU) to perform OCR of arbitary length of amount output.