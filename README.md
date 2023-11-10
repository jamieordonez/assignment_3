# assignment_3
conducting machine learning tests on data bias of API data

For this assignment I am testing Google's Perspective API to measure the toxicity of online comments, and doing tests on the model to see how biased it may be. 
I used https://commentpicker.com/export-comments-youtube.php in order to export a sample of youtube comments (sorted by newest) to a csv file on this video: https://www.youtube.com/watch?v=QwZT7T-TXT0.
I decided to test the bias of this Perspective API model based on my hypothesis that longer (in number of words) comments will be more likely to be classified as toxic by the model. I added a "Words" column to the csv data in Numbers and entered a formula to count number of words for each adjacent row. Then I classified comments with 10 words or greater as "long", and shorter as "short". Then I went through and manually classified each comment as toxic (t) or non toxic (nt) based on my own judgment.


I am testing whether or not the Perspective API model is biased based on length of Youtube comment to be more likely to classify long comments as non-toxic.

Unfortunately I was unable to get the test to return anything except "None". So based on this I am not certain whether or not my hypothesis was correct that longer (in number of words) comments will be more likely to be classified as toxic by the model. However, doing the assignment still taught me a lot about bias and machine learning through the process of doing this project. This project raised questions in my mind of how often I trust machine learning models to work without perceived bias when there are countless ways they could be biased surrounding different factors I may not think about. Because this Perspective API was created by Google, it is probably one of the better models when it comes to factoring in possible biases. However, there are countless other machine learning models that may not be so diligent in encoding fairness and ethics into their machine learning models.
