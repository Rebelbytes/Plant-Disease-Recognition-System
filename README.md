# Plant-Disease-Recognition-System
Plant Disease Recognition System

# Model Setup Instructions

To use this project, you need to download a pre-trained model from the given Google Drive link and place it in the `models` directory. Follow the steps below to set it up correctly:

## Steps to Download and Place the Model

The model file is not stored in this repository because it is larger than
GitHub's 100 MB per-file limit. Download it from the link below and place it
at `models/plant_disease_recog_model_pwp.keras`.

1. **Download the Model**
   - Click [here](https://drive.google.com/file/d/1Ond7UzrNOfdAXWedjlZr2sDXYU6MRBuj/view?usp=sharing) to open the Google Drive link.
   - Click the **Download** button to save the file to your local system.

2. **Create the Models Folder**
   - Navigate to the root directory of this project.
   - Create a folder named `models` if it does not already exist.
     ```bash
     mkdir models
     ```

3. **Place the Model in the Folder**
   - Move the downloaded file into the `models` directory.
     ```bash
     mv /path/to/downloaded/model models/
     ```
     Replace `/path/to/downloaded/model` with the actual path where you downloaded the file.

4. **Verify the Setup**
   - Ensure that the model file is correctly placed in the `models` directory by listing the folder's contents:
     ```bash
     ls models
     ```
     You should see the downloaded model file in the output.

## Usage

1. **Run the Server**
   - Open a terminal and navigate to the root directory of this project.
   - Run the following command to start the server:
     ```bash
     python app.py
     ```

2. **Access the Application**
   - Once the server is running, follow the instructions displayed in the terminal to access the application in your web browser.
