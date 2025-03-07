# Leveraging VeRAPAk for robust networks in the HiggsML Uncertainty Challenge

Files consist of the following:
* Base Model: Initial model trained on HiggsML public dataset
* ADV tuned 1: Adversraily fine tuned using Base Model weights and VeRAPAk generated adversarial dataset
* ADV tuned 2: Adversraily fine tuned using Base Model weights and VeRAPAk generated adversarial dataset (smaller learning rate)
* Combined ADV DS Model: Base model architecture freshly trained on HigsML +  generated adversarial dataset combined
