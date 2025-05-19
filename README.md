# Multi-Person Tracking with Virtual Fence
<a href="https://drive.google.com/file/d/1tCy0ClKD8zg1EL9EozCbPsNWo7IMirlb/view?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

This project presents an advanced AI-driven solution for real-time **multi-object tracking (MOT)** focused on person detection and movement analysis in **indoor** environments. Leveraging the state-of-the-art **YOLOv8** object detector combined with a customized Scene Features-based Simple Online Real-Time Tracker **(SFSORT)**, the system accurately identifies and tracks individuals as they move through a monitored area.

A key feature of this solution is its ability to define virtual fences—customizable boundary lines within the video feed—and reliably detect and count instances where people cross these virtual boundaries. This capability enables enhanced monitoring, security, and analytics for indoor spaces such as offices, retail stores, or public venues.

**Main Features:**
- Person detection using YOLOv8.
- Tracking individuals frame-by-frame with SFSORT.
- Drawing interactive virtual boundary lines.
- Counts and visualizes fence crossings.
- Annotated output video with track IDs and intrusion alerts.
- Yellow fences, red flashing boxes on crossing, and live counts displayed.

## Demo

<p align="center">
  <img src="assets\tracked_output_MOT.gif" width="600px" alt="MOT Output">
  <br>
  <em> MOT Dataset Output. 
</p>

<p align="center">
  <img src="assets\fanavaransharif_demo.gif" width="600px" alt="fanavaransharif Output">
  <br>
  <em> Real CCTV Footage.
</p>


## Installation

1. **Clone the repository:**
   ```bash
        git clone https://github.com/your-username/your-repo-name.git  && cd your-repo-name
   ```
2. **Install dependencies:**
    ```bash
        python3.13 -m venv .venv
        source .venv/bin/activate
        pip install -r requirements.txt
    ```
## Usage
- Run `intrusion_tracking.ipynb`.
- Place input videos in the `data/` folder.
- Annotated outputs will be saved to `outputs/`.
- Virtual fences can be drawn and adjusted interactively in the notebook.

## Credits & License
* Built with [YOLOv8](https://github.com/ultralytics/ultralytics) for detection and [SFSORT](https://github.com/gitmehrdad/SFSORT) for tracking.
* Real CCTV footage provided by a partner company
* Licensed under MIT.


## Contact
Have questions, suggestions, or want to collaborate?  
* Submit issues or feature requests via [GitHub Issues](https://github.com/fanavaran-sharif/IndoorPeopleTrack/issues).  .  
* Reach out via our [website](https://fanavaran-sharif.com) for discussions, partnerships, or support.