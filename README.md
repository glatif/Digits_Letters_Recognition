
**One character recognition algorithm ⇒ Expected Execution: Google Colab Notebook**

### How to execute:
1. Download the Train and Test files of EMNIST dataset using the following links:
- Train Data: https://drive.google.com/file/d/1qGsjIhiDIC628GP4BFl7JxgC8f1GJwiA/view?usp=sharing
- Test Data: https://drive.google.com/file/d/1Ng9HK0wdx1CMEVnCWNVVdJ89CLeyfB1F/view?usp=sharing

2. Keep the same Files/Directory Structure.
3. To Execute Digits Recognition run the file named: [wandb_ai]_Digits_Recognition_EMNIST.ipynb
4. To Execute Letters Recognition run the file named: [wandb_ai]_Letters_Recognition_EMNIST.ipynb 
5. To Execute Letters Recognition run the file named: [wandb_ai]_Digits&Letters_Recognition_EMNIST.ipynb
### Requirements
- Accuracy >90%+  - Done
1. First training  - Done
    - EMNIST
    - data augmentation
    - save model
2. Displaying results of confusion matrix and global accuracy - Done
    1. On test set with all characters
    2. On test set with letters only
    3. On test set with digits only
3. Fine tuning (TO DO) - Done
    - with our database (we should be able to redo this part to enhance the OCR while we will collect data in the next months)
        - Preprocessing
        - Training /fine-tuning
    - save model

### Digits Recognition Validation Accuracy (Fine Tuned Model Saved):
- Achieved Accuracy: 99.34%
- Achieved Loss: 0.0369
- Saved Model and Trained Parameters Directory: EMNIST_Digits_Training/

<img src="Digits_Confussion_Matrix.png">

### Letters Recognition Validation Accuracy (Fine Tuned Model Saved):
- Achieved Accuracy: 95.98%
- Achieved Loss: 0.1487
- Saved Model and Trained Parameters Directory: EMNIST_Letters_Training

<img src="Letters_Confussion_Matrix.png">

### Digits and Letters combinedation Recognition Validation Accuracy (Fine Tuned Model Saved):
- Achieved Accuracy: 92.22%
- Achieved Loss: 0.2280
- Saved Model and Trained Parameters Directory: EMNIST_Digits&Letters_Training

<img src="Letters&Digits_Confussion_Matrix.png">
