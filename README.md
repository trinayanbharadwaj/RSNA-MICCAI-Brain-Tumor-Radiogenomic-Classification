# RSNA-MICCAI-Brain-Tumor-Radiogenomic-Classification

![Screenshot 2021-10-20 213529](https://user-images.githubusercontent.com/63582471/138129852-62b8230d-60b3-48e9-8449-bb1ded0ccc9b.jpg)

In this competition we had to predict the genetic subtype of glioblastoma using MRI (magnetic resonance imaging) scans to train and test your model to detect for the presence of MGMT promoter methylation.

If successful, you'll help brain cancer patients receive less invasive diagnoses and treatments. The introduction of new and customized treatment strategies before surgery has the potential to improve the management, survival, and prospects of patients with brain cancer.

![image](https://user-images.githubusercontent.com/63582471/138129528-24e780d4-cd7f-47e6-868e-38941a09a17a.png)

Predict the presence of MGMT promoters from 4 types of brain MRI scans.
After more than 170 submissions, ended up with an ensemble approach of Flair and T2W type MRI scans.
Custom CNN models were built with very low number of epochs as the models were highly overfitting.
Models seem to learn very little. Even the competition winner had about 62% accuracy. My personal best was a late submission of this particular code. The submission code will be found in my Kaggle profile under code section. Accuracy received was 57%.

Submissions are evaluated on the area under the ROC curve between the predicted probability and the observed target.


The dataset for this challenge has been collected from institutions around the world as part of a decade-long project to advance the use of AI in brain tumor diagnosis and treatment, the Brain Tumor Segmentation (BraTS) challenge. Running in parallel with this challenge, a challenge addressing segmentation represents the culmination of this effort.

The mistake which cost me was selction of my final submission. My submission was highly biased towards the public leaderboard score. I was in the top 7%.
And in my final result I droped from top 7% to top 94%. It was a bad day.

Later, I made a few late submissions and i scored around top 22%. 
