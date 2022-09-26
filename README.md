# Youtube data extraction

[Youtube  API v3](https://developers.google.com/youtube/v3) is used to extract the data.

The extracted data is stored on [Kaggle Datasets](https://www.kaggle.com/datasets/tushifire/youtube-data-science-channels-comments). 

## Data Organisation

Following 11 Youtube channels in  Data Science and Python.
1. Sendex
2. Freecodecamp
3. krishnaik06
4. iNeuron_Intelligence
5. Coreyms
6. realpython
7. NeetCode
8. dataschool
9. howardjeremyp
10. DataInterviewPro
11. CampusX-official

Data for each channel is organised into 3 files.
1. _playlist.csv : It contains playlist available on the channel. Selects the recent 50 playlists
2. _video.csv : This file contains the top 50 videos present in the playlists. 
3. _comments.csv : It has top 100 comments in each video.

### TODO:
- Refractor the notebook and make python scripts.

## Citations.
```
 @misc{tushar tiwari_2022, title={Youtube Data Science Channels Comments}, url={https://www.kaggle.com/dsv/4248220}, DOI={10.34740/KAGGLE/DSV/4248220}, publisher={Kaggle}, author={Tushar Tiwari}, year={2022} }
 
 ```
