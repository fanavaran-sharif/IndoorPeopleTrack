# AI-Powered Person Tracking with Virtual Fence
<a href="https://drive.google.com/file/d/1tCy0ClKD8zg1EL9EozCbPsNWo7IMirlb/view?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

**AI-based solution** for **person detection, tracking, and virtual fence crossing detection** in indoor environments using **YOLOv8** and a customized **Scene Features-based Simple Online Real-Time Tracker (SFSORT)**.  
It allows users to detect individuals in video footage, track their movements, and count crossings over predefined virtual boundary lines.

**Main Features:**
- Person detection using YOLOv8.
- Tracking individuals frame-by-frame with SFSORT.
- Drawing interactive virtual boundary lines.
- Counting and visualizing boundary crossings.
- Generates annotated output video with track IDs and intrusion alerts.

---

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Example](#example)
- [License](#license)

---

## Installation

1. **Clone the repository:**
   ```bash
        git clone https://github.com/your-username/your-repo-name.git
        cd your-repo-name
   ```
2. **Install dependencies:**
    ```bash
        make install
        or manually:
        pip install -r requirements.txt
    ```

