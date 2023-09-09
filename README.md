# AI-guidebook
This repo aims to make some AI learners and enthusiasts know the embedded workflow for AI

## 📖 The workflow to code AI
Firstly, The embedded order in which code is written for a deep learning project depends on developers' personal habits and project needs. However, there is a common process to follow:

**1. Understand the problem and collect data:**
Learners should identify yourself goals, this will help you collect the corresponding data quickly and accurately. You need to spend time to understand your data content and obtain maximum preliminary data exploration and analysis for these.  This steps have included data cleaning,preprocessing,preliminary visualization of the data,etc.

**2. Building a dataset and data loader:**
Based on the upper content, you can identify data and build a dataset suitable for your AI models. This Step usually involves creating a data loader (DataLoader), which can provide data in batches when training the model.

**3. Define the model:** 
Once you have the dataset available, you can start building your model. The construction of the model ups to your plan what solve the problem you want to solve. For examples, You can do hottest AIGC services which usually use the transformer model.

**4. Define loss function and optimizer:**
After verifying the model, you need to define a loss function to evaluate the performance of the model, and an optimizer to update the parameters of the model.

**5. Trainning the model:**
When All Done, you can start training your model. This usually involves looping over your dataset multiple times (these loops are called "epochs"), each epoch will update the parameters of the model to reduce the loss function what mainly aims to convergency.

**6. Validation and testing:**
During model training, you will usually verify the performance of the model on an `independent validation set` to prevent overfitting. After training is complete, you evaluate the model's final performance on `the test set`.

**7. Tunning:**
During the work, depending on the performance of your model on the validation and test sets, you may need to make some adjustments. This may include changing the model structure, adjusting hyperparameters, or using other training strategies and more.


