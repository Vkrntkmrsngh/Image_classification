Data for this model can be downloaded from
https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765

Training Data is present in Training_data folder, You can read it using pickle library.

Model is saved in model folder, to access this model you will have to keep 
file in same folder in which notebook is present else you will have to change 
path in os.path.join in notebook.

CNN has been used to create this model.
It is first virsion os it doesnt have very good accuracy.

To check the tensorboard, Please execute below command in same folder in 
which log folder is present.

>>tensorboard --logdir=logs/

It will provide you a link, open that link in chrome and check performance 
of your model.

Stay tuned for more accurate model!

thanks to Sentdex, whose videos helped me to create this.

