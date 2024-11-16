<a target="_blank" href="https://colab.research.google.com/github/RudraKhunti/SAM2-Auto-Seg">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# SAM2: Auto Segmentation using YOLOv8

This repository contains an implementation of **SAM2 Auto Segmentation** using the YOLOv8 object detection model. The project demonstrates how to combine the strengths of YOLOv8 for object detection with segmentation techniques to automate segmentation tasks.

## Features

- Integration of YOLOv8 for object detection.
- Automated segmentation using detected objects.
- Customizable for various datasets and segmentation needs.
- Output results can be saved and visualized for further analysis.

## Prerequisites

Ensure you have the following installed:

- Python 3.8+
- Jupyter Notebook
- Required Python libraries (see [Installation](#installation)).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sam2_auto_segmentation.git
   cd sam2_auto_segmentation
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the notebook:
   ```bash
   jupyter notebook SAM2_Auto_Segmentation_using_YOLOv8.ipynb
   ```

2. Follow the steps in the notebook to:

   - Load the YOLOv8 model.
   - Perform object detection.
   - Execute the segmentation process.

3. Customize the settings and input data as needed.

## File Structure

- `SAM2_Auto_Segmentation_using_YOLOv8.ipynb`: Main notebook file containing the implementation and step-by-step guide.

## Results

The notebook will output segmentation results, including visualized bounding boxes and segmented areas. These results can be used for further analysis or integrated into downstream tasks. As shown, you can use the segmentation data from SAM2 to create a YOLO compatible segmentation dataset.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for enhancements or bug fixes.

## License

The SAM 2 model checkpoints are licensed under Apache 2.0.

**Author:** Rudra Khunti  
