# Redding_CA_Wildfires

* This is my first image processing ML project.
* I wanted to specifically train on a small geographic area and chose Redding, CA because it gets wildfires and I can also get tabular weather data from NOAA.
* NOAA labels wildfires in images with an orange color. I scanned 10 years of images of the approximate latitudes and longitudes of Redding and got the date that NOAA had the orange color. There were about 324 images (out of about 4000 - not a lot). I then tried to get images that also had a 'smog-like' color but that also got a lot of clouds. Finally I manually looked at the images that were around the dates where I had extracted the data NOAA had labeled with the orange color, this resulted in 426 wildfires images. I did not use images that had complete cloud coverage or where black (NOAA had some images that were just black).
* The Images files are used to extract the labeled and unlabeled images from NOAA as well as get the dates where there are/are not wildfires, too many clouds, smog-like colors.
* The Model directory has the model notebook. I did not do too much with this because I was running it locally on my Mac and wanted to be cautious.
* The EDA directory has dirty and clean Redding, CA csv files.
