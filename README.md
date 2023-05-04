<p align="center">
	<img src="https://user-images.githubusercontent.com/64346030/236112840-cc1bb8ec-9fc3-40b5-a33c-1bc62c6ee6cf.png" width=30%/>
<h1 align="center">Multimodal Approach for Detecting Depression Using Physiological And Behavioural Data</h1>
<h3 align="center">Are you interested in detecting depression with a more efficient and modern approach? </h3>
<h4 align="center"> Traditionally, extensive clinical interviews were conducted to analyze the subject's responses to determine their mental state. However, we have developed a model that incorporates this approach by combining three modalities - Text, Audio, and Video. Our deep learning model assigns appropriate weights to each modality and generates a binary classification output of yes or no, indicating whether the patient is exhibiting depression symptoms.<h4>
</p>

# How to Use the Files:

Ready to give our model a try? First, make a copy of the drive folder (https://drive.google.com/drive/folders/1A9pfBsfNOKhjeLfzrcYIra-hTr8dyJiT?usp=share_link) and add it to your main "my-drive" folder. Make sure to copy the dataset folder to the correct location, and you're good to go! For an even easier experience, we recommend running the files on Google Colab. 

# Files:

Want to know what's included in our repository? Check out the following files:

* Dataset.ipynb: Get code snippets for obtaining data from the DAIC server, unzipping them, and arranging them in a user-friendly format.
* SVM&RF_Text.ipynb: Run the SVM and RF models on the text modality.
* SVM&RF_Audio.ipynb: Run the SVM and RF models on the audio modality.
* Rf_prune.ipynb: Implement pruning on RFs.
* CNN_Video.ipynb: Use the code snippet to run CNN on the video features.
* LSTM_With_Gating_Sentence_Level.ipynb: Implement LSTM on all three modalities combined with gating at the sentence level. 

Ready to improve your depression detection skills? Give our multimodal approach a try and see what results you can achieve!
