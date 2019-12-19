# Project Description
  ## Introduction
  Realtime emotion detection with VggFace, DLLib, OpenCV, and Python 3.5
  ## What it does? 
  > What are the inputs/outputs? How does it work?
  
  ## Challenges
  > Difficulties encountered
 ## Achievements
 > Progress, accomplishments
 
# Data 
 > Detailed data description
- Cohn-Kanade (CK and CK+) Dataset

Resource: http://www.consortium.ri.cmu.edu/ckagree/
 
# Folder Structure
```
.
├── camera_classifier.py
├── data
│   ├── csvs
│   ├── images
│   └── raw_data_with_label
├── data_land_marker.py
├── data_preparer.py
├── data_transformer.py
├── docs
│   ├── presentation
│   └── project_report
├── image_classifier.py
├── main.py
├── README.md
├── run.sh
├── shape_predictor_68_face_landmarks.dat
└── venv
    ├── bin
    ├── lib
    ├── lib64 -> lib
    └── pyvenv.cfg
```    
# Requirements
All included in the virtual environment folder (/venv), so you don't need further requirements.

# How to Run
> How to run from the command line? How to reproduce the results?  How to test your system? 

You can enter the following command in your Linux Terminal to run the program:
```
./run.sh
```
Note that, you will get emotion detection result live and periodically. You can run "main.py" with "python3" if you want to see the emotion detection result in console. 

# References
- Facial landmarks with dlib, OpenCV, and Python: https://www.pyimagesearch.com/2017/04/03/facial-landmarks-dlib-opencv-python/

# Additional Notes
If you have trouble with installing dllib library, you can check out the link: https://www.pyimagesearch.com/2018/01/22/install-dlib-easy-complete-guide/

## Credits
- Kanade, T., Cohn, J. F., & Tian, Y. (2000). Comprehensive database for facial expression analysis. Proceedings of the Fourth IEEE International Conference on Automatic Face and Gesture Recognition (FG'00), Grenoble, France, 46-53.
- Lucey, P., Cohn, J. F., Kanade, T., Saragih, J., Ambadar, Z., & Matthews, I. (2010). The Extended Cohn-Kanade Dataset (CK+): A complete expression dataset for action unit and emotion-specified expression. Proceedings of the Third International Workshop on CVPR for Human Communicative Behavior Analysis (CVPR4HB 2010), San Francisco, USA, 94-101.
