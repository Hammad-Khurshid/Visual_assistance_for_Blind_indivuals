**Visual Assistance for Blind Persons**


This project is a visual assistance tool designed to help blind persons by detecting real-time objects, calculating distances, and providing voice feedback. The tool uses Ultralytics for object detection, math for distance calculation, and pyttsx3 for text-to-speech feedback.

**Features**

- **Real-time Object Detection**: Utilizes Ultralytics for detecting objects in real-time.
- **Distance Calculation**: Calculates the distance to detected objects.
- **Voice Feedback**: Provides audio feedback using pyttsx3 to inform the user of detected objects and their distances.

**Requirements**

- Python 3.7+
- Ultralytics
- pyttsx3
- Math (standard Python library)

**Installation**

1. **Clone the repository**

   ```bash
   git clone https://github.com/Hammad-Khurshid/Visual_assistance_for_Blind_indivuals.git
   cd Visual_assistance_for_Blind_indivuals

2. **Create a virtual environment**
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   
3. **Install the required packages**
    pip install ultralytics pyttsx3

4. **To run**
    cd/ultralytics/models/yolo
    python3 detection.py
    
4  **Contributing**
Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

6.  **License**
This project is licensed under the MIT License - see the LICENSE file for details.

7.  **Acknowledgements**
Ultralytics for the object detection library.

https://github.com/ultralytics/ultralytics

pyttsx3 for the text-to-speech functionality.

https://pypi.org/project/pyttsx3

9.  **Contact**
If you have any questions or feedback, feel free to reach out at [hammad.khurshid175@gmail.com].

Thank you for using this visual assistance tool. We hope it makes a positive impact on the lives of those who need it.
