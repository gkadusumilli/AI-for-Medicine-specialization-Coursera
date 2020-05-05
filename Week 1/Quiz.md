# Week 1 Quiz: Disease detection with computer vision
1. Which of the following is not one of the key challenges for AI diagnostic algorithms that is discussed in the lecture? 

    **Ans. Inflexible models**

2. You find that your training set has 70% negative examples and 30% positive. Which of the following techniques will NOT help for training this imbalanced dataset?

    **Ans. Oversampling negative examples**

3. What is the total loss from the normal (non-mass) examples in this example dataset?

Please use the natural logarithm in your calculation. When you use numpy.log, this is using the natural logarithm. Also, to get the total loss, please add up the losses from each ‘normal’ example.

   **Ans. 1.27**

4. What is the typical size of medical image dataset?

   **Ans. ~10 thousand to 100 thousand images**

5. Which of the following data augmentations would be best to apply?

![image](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/fBZB55L0SpuWQeeS9GqbRQ_f5905fac87ba9005b757a018766c6730_image1.png?expiry=1588809600000&hmac=FfcjEA3MHB2rfoyHxKib6rLmpBlJxkurZjEP3DjDXYg)

   **Ans. Rotate**

6. Which of the following are valid methods for determining ground truth?  Choose all that apply.

   **Ans. Biopsy, Consensum voting from a board of doctors**

7. In what order should the training, validation, and test sets be sampled?

    **Ans. Test, Validation, Training**

8. Why is it bad to have the same patients in both training and test sets?

    **Ans. Overly optimistic test performance**

9. Let’s say you have a relatively small training set (~5 thousand images). Which training strategy makes the most sense?   

   **Ans. Retraining the last layer of a pre-trained model**

10. Now let’s say you have a very large dataset (~1 million images). Which training strategies will make the most sense?

    **Ans. Training a model with randomly initialized weights**










