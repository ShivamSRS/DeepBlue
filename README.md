I have made a plastic object segregator by employing methods of deep learning

I gathered and annotated a dataset of 2000 images and labelled it accordingly in PASCOLVOC3 format 

Next I converted the dataset to csv files using xml_to_csv.py

I have made this model using the faster masked RCNN from Tensorflow's Object Detection API, which requires input to be fed as tfrecords
which I do by using generate_tfrecord.py

I uploaded the dataset to my google drive and trained the faster masker RCNN on Google collab using the same.
I have included the notebook "obj.ipynb" for the same.
