# Gender and Age Prediction in realtime

This is a gender and age prediction WideResNet model.
The dataset was taken from 'IMDB-WIKI – 500k+ face images with age and gender labels'. Came across this solution with the help of Chengwei Zhang's great blog post and Git repository on the same. Link: https://www.dlology.com/blog/easy-real-time-gender-age-prediction-from-webcam-video-with-keras/

 Here is the demo

![alt text](https://github.com/ShashankNardekar/Age_Gender_Prediction/blob/master/demo.gif "age gender demo")

### install requirements
```
pip3 install -r requirements.txt
```

## Run the demo
```
python realtime_demo.py
```

Though as you can see in the video, the age prediction varies in a range and somewhat distorts from an accurate result which is an area I am working on (Sundar Pichai's actual age is 46 yrs). The face angle constraint is also to be looked for, which can be worked on by using a wider variety of images with different angles of faces, mostly from 'Adience collection of unfiltered faces for gender and age classification'.
