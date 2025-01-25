# GAIP-NUS-HPE

This repo consists of my team project at my internship at NUS with HP.

We developed an application which can assist the visually impaired by providing its users with information about thier surroundings. The model uses a finetuned version of YOLOv5 on selected outdoor object classes which and employed the use of relative depth estimation framework MiDaS to estimate the nearest object and its class. This information is provided to the user in the form of audio signals to help him/her navigate easier.

# Instructions to run the code:
Clone the repository
Install the requirements listed in frozen-requirements.txt
Place the image you want to use for inference in the main directory
Open shell in the main directory and use the following command:
Python main.py {image_name}

