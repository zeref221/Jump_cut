# Jump_cut


```markdown
# Video Search using CLIP

This repository contains code for searching frames in a video using the [CLIP (Contrastive Language-Image Pre-training)](https://github.com/openai/CLIP) model.

## Features

- Downloads a video from a YouTube URL using `pytube`.
- Extracts frames from the video at a specified interval.
- Uses CLIP to encode text and images, and computes similarity between the search query and video frames.
- Displays a heatmap representing the similarity scores between the search query and frames.
- Displays the top matching frames along with timestamps.

## Requirements

- Python 3.6 or higher
- Libraries: `pytube`, `plotly`, `opencv-python`, `torch`, `clip`, `numpy`, `pandas`, `plotly`, `datetime`, `IPython`

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/zeref221/Jump_cut.git
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the `search_video.py` script and provide a search query:

   ```bash
   python search_video.py --query "search query"
   ```

   Replace `"search query"` with the term you want to search for in the video.

2. The script will download the video, extract frames, compute similarities, and display the results.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.





