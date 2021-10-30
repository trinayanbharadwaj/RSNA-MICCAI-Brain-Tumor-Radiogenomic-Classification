# RSNA-MICCAI-Brain-Tumor-Radiogenomic-Classification

![Screenshot 2021-10-20 213529](https://user-images.githubusercontent.com/63582471/138129852-62b8230d-60b3-48e9-8449-bb1ded0ccc9b.jpg)

In this competition we had to predict the genetic subtype of glioblastoma using MRI (magnetic resonance imaging) scans to train and test your model to detect for the presence of MGMT promoter methylation.

If successful, we would help brain cancer patients receive less invasive diagnoses and treatments. The introduction of new and customized treatment strategies before surgery has the potential to improve the management, survival, and prospects of patients with brain cancer.

![image](https://user-images.githubusercontent.com/63582471/138129528-24e780d4-cd7f-47e6-868e-38941a09a17a.png)

Predict the presence of MGMT promoters from 4 types of brain MRI scans.
After more than 170 submissions, ended up with an ensemble approach of Flair and T2W type MRI scans.
Custom CNN models were built with very low number of epochs as the models were highly overfitting.
Models seem to learn very little. Even the competition winner had about 62% accuracy. My personal best was a late submission of this particular code. The submission code will be found in my Kaggle profile under code section. Accuracy received was 57%.

![Screenshot 2021-10-23 152031](https://user-images.githubusercontent.com/63582471/138551538-7c11ed97-47f0-42e4-8082-879f1977cf84.jpg)

Challenges I faced in this competition:-
1. It took me about 3 weeks just to read the dicom images from the repositories.
2. Models weren't learning anything. (training loss was stuck at 0.6). Well this was normal for this competition I guess. 
3. Few images were blank so I had to ignore them by setting up a threshold for the sum of pixels of an dicom image.
4. Since my personal laptop has low processing power, I had to rely on kaggle notebooks which are amaizing except the limited RAM. 
5. Because of memory issues I experimented a lot and ended up with image size of 150X150 resulting in 7000 images.

Mistakes from my side:-
1. I took the leaderboard too seriously. It was highly overfitting. My final/private scores were way way low.
2. Choose the wrong final submission. I dropped from top 7% to top 94%.
3. Went for highly complex models. 


Submissions are evaluated on the area under the ROC curve between the predicted probability and the observed target.


The dataset for this challenge has been collected from institutions around the world as part of a decade-long project to advance the use of AI in brain tumor diagnosis and treatment, the Brain Tumor Segmentation (BraTS) challenge. Running in parallel with this challenge, a challenge addressing segmentation represents the culmination of this effort.

The mistake which cost me was selction of my final submission. My submission was highly biased towards the public leaderboard score. I was in the top 7%.
And in my final result I droped from top 7% to top 94%. It was a bad day.

Later, I made a few late submissions and i scored around top 22%. 
