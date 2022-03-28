# Model Details

The model is a Convolutional Neural Network with *72,000 trainable parametres*, using the *ReLU activation function* throughout it's
convolutional layers and *Softmax* in the output layer. 

## Model Date
The model was built over a period of 5 days, in the week of the <a href = https://www.futurize.studio/fuel-africa>Fuel Africa Healthcare Innovation Hackathon</a>, starting from March 18th, 2022. The model was part of an attempt to create a prototypical business venture that would solve a dire problem in African Healthcare, and was awarded <a href = https://cutt.ly/wDlIauk>2nd prize in the competition</a> out of 1200 participants & 84 participating teams. 

## Model Type
Computer Vision Classification Model using Convolution with Attention

## Model Version
This is the first version of the model, with 72k parametres. Future versions will be implemented exclusively using Self-Attentive Transformer Architectures.

## Paper Samples
The methods, observations and findings that were made in the course of completing this prototype are being compiled and will be published as a paper soon. Check back for updates!

## Model Use
We intend to deploy this model on an eponynmous online platform where healthcare facilities that are experiencing a shortage of radiologists, as is typical in Kenya, can use it to scale up the number of patients who can be screened and diagnosed with Breast Cancer early for earlier, more successful interventions.


# Data, Perfomance & Limitations
## Data
The model was trained using the MIAS mammography dataset, sourced from Kaggle and made available <a href = https://github.com/ianomunga/Vectorgram/tree/main/data>here</a> too. This dataset was augmented using Keras upto 1200 percent to prevent overfitting and enhance the classification accuracy of the model. 

## Performance
The model posted strong performance on the augmented test-set of the MIAS mammography dataset, with a top-1 accuracy of *98.6 percent*. Due to the lack of suitable Whole Mammogram Classification benchmarks to cross-examine this model against, we are attempting the definition of a novel baseline based on generalized, scalable and repeatable aspects of the Breast Cancer Prediction task so that future work in Scientific Imaging will have a useful baseline to quantify improvements in performance. This is still in the works at the time of writing, but when complete, the novel baseline will be available <a href = https://paperswithcode.com/task/whole-mammogram-classification>here</a>. 

## Model Limitations
We understand that though these preliminary results may be impressive, the extent to which Vectorgram can generalize to different scan configurations in more varied, noisier data is limited. However, these capabilities will be fleshed out with more on-the-ground use within the next few months as we test it intensively.

## Where To Send Questions or Feedback About The Model
You can reach me with questions or feedback about this work <a href = https://forms.gle/hEEastpQLiANRYeW8>here</a>.
