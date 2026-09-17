🧠 Skull Stripping of Brain CT Images(ThresContCT_TBI)

📌 Overview
This repository contains a Python-based skull stripping method for brain CT images using OpenCV, NumPy, and Matplotlib.
The pipeline removes high-intensity skull regions and retains the inner brain region for further medical image analysis.
The implementation of the work is described in the paper: [Rahman, Minhazur, Bikash Upadhyay, and Rosy Sarmah. "Automatic Skull Stripping for CT Images of Traumatic Brain Injuries (TBI)." Journal of Transformative Technologies and Sustainable Development 9.1 (2025): 17.]9https://link.springer.com/article/10.1007/s41314-025-00086-1)

```markdown
🔄 Processing Steps

📥 Input CT Image
      ↓   
🎚️ Thresholding
      ↓    
🔗 Morphological Closing
      ↓    
🔍 Contour Detection
      ↓
🎭 Mask Generation
      ↓
📏 Distance Transform
      ↓
✂️ Skull Stripping
      ↓
💾 Save Output
```
📦 Requirements

pip install opencv-python numpy matplotlib

📂 Input and Output Paths

input_folder = 'File_location/inuput_image'

output_folder = 'File_location/output_image'

⚠️ Change these paths according to your own computer.

⚙️ Main Parameters
Parameter	    Value

Intensity threshold	     220

Morphological kernel	     20 × 20

Minimum contour area	     500

Distance threshold	     10

Final intensity threshold    240


▶️ Run the Code

Save the script as skull_stripping.py, then run:

python skull_stripping.py

Supported formats: .png, .jpg, .jpeg, .bmp, .tif, .tiff

🧪 Applications
🩻 Traumatic Brain Injury analysis
🧠 Brain image segmentation
🔬 Lesion analysis
📊 Radiomics
🤖 Machine learning and deep learning

⚠️ Notes
The code processes 2D images.
Threshold values may need adjustment for different CT datasets.
Do not upload confidential or patient-identifiable medical images publicly.
This code is for research and educational purposes only.



👩‍💻 Author

Minhazur Rahman

Medical Image Analysis | Artificial Intelligence | Machine Learning


Paper: Automatic Skull Stripping for CT Images of Traumatic Brain Injuries (TBI)
Authors: Minhazur Rahman, Bikash Upadhyay, Rosy Sarmah
Journal: Journal of Transformative Technologies and Sustainable Development

