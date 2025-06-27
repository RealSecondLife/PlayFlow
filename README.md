# PlayFlow

**PlayFlow** is a robust data processing pipeline designed to transform game videos and their associated keyboard and mouse event sequences into datasets optimized for text-to-video projects. By leveraging both video content and input events, PlayFlow ensures accurate, multimodal data extraction and refinement.

## Key Features

1. **Shot and Scene Segmentation**  
   Automatically splits game videos into meaningful shots and scenes based on visual and event-driven changes.

2. **Action Processing**  
   Unlike traditional video-only inference methods, PlayFlow incorporates keyboard and mouse event sequences to extract precise player actions.

3. **Data Filtering**  
   Filters out low-quality or blurry content through multimodal, multidimensional analysis, ensuring high-quality dataset generation.

4. **6-DoF Camera Trajectory Reconstruction**  
   Reconstructs 6 degrees-of-freedom (6-DoF) camera trajectories for enhanced spatial and temporal data understanding.

5. **Structured Captioning**  
   Generates structured captions for the processed content, providing semantic-rich annotations.

## Inputs

- **Game Video**: Raw gameplay recordings.
- **Keyboard and Mouse Events**: Logs of input events synchronized with the video.

## Output

- A refined dataset that can be seamlessly integrated into text-to-video generation pipelines, complete with processed video segments, action data, camera trajectories, and captions.

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/PlayFlow.git
cd PlayFlow
pip install -r requirements.txt
```
