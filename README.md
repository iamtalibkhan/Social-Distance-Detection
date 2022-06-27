Github usually doesn't support files larger than 25 Mb. You can find the yolo weights in [My google drive](https://drive.google.com/file/d/1QrGGrZl-K2z9IH410o9oeGvbKdIDjGIS/view?usp=sharing) 

Download it & move to yolo-coco folder

**************************************************************************************************************************

To run this code in your terminal:

Open your terminal:-
Change directory to where you have downloaded this code.

Install python3 if you have not, if installed already then it's ok!

Run  ` python -m venv venv `  to create a virtual environment named venv.

Run (for linux user)  `  source venv/bin/activate  `  to activate the environment.

Run (for window's user)  `  venv/Scripts/activate  `  to activate the environment.


Write  ` pip install -r requirements.txt `  to install the python dependencies related to this project like opencv,numpy scipy etc.


Run the command  ` python social_distance_detector.py --input pedestrians.mp4 --output output.avi --display 1 `
to run your social distance detection project