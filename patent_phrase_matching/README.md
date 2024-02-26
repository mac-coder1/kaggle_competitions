- Heavily based on lesson 4 of Fastai practical deep learning for coders


Learnings:

* How to convert the strings into numbers to learn from??? -> tokenization!!!
* Tokenization
  * Not full words as too many,
    bigger 'vocabulary' which creates too much data and training
  * Use subwords!
  * Numericalisation turns
    tokens into numbers
  * Need to use the same vocab
    as the pre-trained model
* Huggingface have a `Dataset`
  object
* Huggingface has 100s of
  models
* Loss is a smooth measure of
  how good the predictions of a model are. Need to find the gradient of it
* Metric is a measure of the thing that we
  care about (e.g. % of correctly identified pictures), but will often not
  be smooth
* Plotting metrics and how they
  correlate with the different variables to get an idea is a really
  goodidea!!
* Batches save memory on GPUs
