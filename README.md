# LUIPerson
largest unlabeled dataset Iranian
LUPerson is currently the largest unlabeled human re-identification dataset used for unsupervised pre-training. This dataset, contains more than 6 million images and more than 28 thousand identities(The way to count the number of identities is based on the number of identities announced by the tracking algorithm).

In the LUIPerson dataset uses the YOLO-v8 model trained on the COCO dataset as a pedestrian detector and the ByteTrack model trained on the Crowd Human dataset for pedestrian tracking. This dataset, like LUP-NL, has two different versions of noise-free and noisy annotations (without human labeling efforts) that can be used for pre-training.
This dataset is collected from places where there are many people with different clothing. One of the unique features of this data is that it was collected during the Arbaeen pilgrimage, which sometimes includes various nationalities. Also, in terms of its challengingness, it can be pointed out that the clothing of the people in the data collection is the same color during the Arbaeen pilgrimage and in one of the places where the picture was taken (Al-Aima Mosque). This uniform coating color intensifies the data challenge in crowded and frequented places.

These videos were recorded by cameras with different resolution quality in places such as Iran University of Science and Technology, Al-Aima Mosque, Arbaeen procession, local fruit shop and supermarket in Tehran, the details of which are given separately in the table below.
<p align="center">
   <img src="https://github.com/Person-Reidentification/LUIPerson/assets/36541098/577ffdcf-a8a7-4639-b873-1f04577c7d7c" align='center'>
</p>

| Location  | Cameras | Total hours | Resolution |Num of day| Num of image | Num of identities|
| ------  | :---:  | :---:  | :---:  | :---:  | :---:  | :---:  |
| Iran University of Science and Technology  | 17 | 383 h| Variable| 5| | |
| Al-Aima Mosque | 5 | 40 h| 960×1080 | 2| 762010 |3924 |
| local fruit shop | 7 | 38 h | 944×1080 | 1 |120719 | 1603|
| local supermarket | 6 | 124 h | 1280×1944  | 4 | 135502| 2401|
| Arbaeen procession | 2 | 3 h | 1280×720 | 5 | 5506784| 22639|


# Dataset evaluation
