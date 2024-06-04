# Random Forest Image Classification Model for Racial Detection with RLHF

Models like racial classification are heavily biased based on the initial labeling of the training and testing dataset. With a lack of diverse cultural representation in ML academia, datasets can have underlying biases in how they are gathered and labeled. 

However, by adding RLHF to a classification model, the model can include other diverse human biases to combat the initial bias in a dataset. RLHF is useful for improving models that deal with non-objective truths (Race, text sentiment) because it gives the model human feedback to help understand complexities the initial dataset couldn't represent. RLHF is not useful for models dealing with objective truths because human feedback isn't necessary (For example, you don't need a human to give feedback on digit classification because digits are universally agreed-upon representations, so the model can be trained without the need for human intervention to correct or refine the outputs).

This random forest image classification model detects if a person is black or not based on their face. The model is first built by the given data and labels and then tuned using RLHF via prompts to the user on the CLI.

In the context of Critical Race Theory, "Black" is understood as a socially constructed category that goes beyond mere biological or phenotypical attributes. Therefore, categorizing someone as "Black" varies depending on a person's cultural background. In theory, by giving this model to a variety of people to give feedback, the model will tune itself to capture the definition of "Blackness" that an initially biased model and dataset couldn't capture.


![DALL·E-2024-06-03-23 36](https://github.com/ronantakizawa/randomforestrlhf/assets/71115970/59544c26-a8fa-4cfd-9588-bbcb95673d05)
