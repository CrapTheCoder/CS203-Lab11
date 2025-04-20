# CS203: Software Tools & Techniques for AI  

---

## Team Members (Team 17)
- Nishchay Bhutoria (23110222)  
- Srivaths P (23110321)

---

# 1. Dataset Preparation

![data1](https://github.com/user-attachments/assets/52921e3f-e495-4185-8025-d7278b248dcc)
![data2](https://github.com/user-attachments/assets/4f7c7e93-0505-4c8a-a771-2ddf5edac6ec)

# Construct a Multi-Layer Perceptron (MLP) model.

![MLP](https://github.com/user-attachments/assets/64aa26f8-f194-4782-a632-22409651808c)

# Train the model with 10 epochs and create the best-performing model (checkpoint.pt)
![train1](https://github.com/user-attachments/assets/0aa8e61f-2b6c-4cee-a6be-e98878c346d1)
![train2](https://github.com/user-attachments/assets/45cf435f-5a39-4b97-bf8b-ea3b6909987f)

## Plot the validation accuracy + loss (epochs vs accuracy-loss).

![plot](https://github.com/user-attachments/assets/927b17d9-2dca-41ef-9bea-c2d024a71579)

---

![test_model](https://github.com/user-attachments/assets/e39134ca-3a57-4be9-8ce2-e2d637a4665c)

# No Quantization

![original](https://github.com/user-attachments/assets/ee63f045-46ac-462d-b23d-5680e1571db5)

# Dynamic Quantization with INT4 or INT8

![dynamic](https://github.com/user-attachments/assets/a6544620-e7bc-4ff1-8ae1-fee27a0d6b76)

# Half precision

![half](https://github.com/user-attachments/assets/aadf1390-a675-4160-9af7-7adffbd5393f)

# Fill the table for different quantization techniques

![results](https://github.com/user-attachments/assets/999b5fa2-8105-4419-b224-9dba7ff74009)

      
| S.I. | Model Name | Accuracy (Out of 100) | Storage (In MB) | Inference time (In ms/sample) |
| :--- | :--------- | :-------------------- | :-------------- | :---------------------------- |
| 1    | Original   | 80.40                 | 20.1955         | 0.0055                        |
| 2    | Dynamic    | 80.23                 | 5.0589          | 0.0784                        |
| 3    | Half       | 80.34                 | 10.0997         | 0.0427                        |
