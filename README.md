Traffic Sign Detection
This project is a Traffic Sign Detection system that utilizes OpenCV for identifying traffic signs. The project is structured into separate components for GUI, training, and model handling.
The Traffic Sign Detection project aims to detect and classify traffic signs using a trained model. The project is divided into different components:

gui.py: Contains the graphical user interface (GUI) for testing the traffic sign detection system.
main.py: Handles the training of the model using the dataset.
model_trained.h5: The pre-trained model file that is used for detecting traffic signs.
Installation
To set up this project, follow these steps:

Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/Traffic-Sign-Detection.git
cd Traffic-Sign-Detection
Create a Virtual Environment (Optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
Install Required Packages:
Install the necessary Python libraries using pip. Create a requirements.txt file with the following content:

Copy code
opencv-python
tensorflow
numpy
matplotlib
Then, install the dependencies:

bash
Copy code
pip install -r requirements.txt
Download the Dataset:
Download the dataset from . Place it in the Tain and Test directories.
