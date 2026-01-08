# RMR
<img width="996" height="359" alt="image" src="https://github.com/user-attachments/assets/c1d04fb5-f501-4531-b990-b57e4a818113" />

Rectify-Match-Reconstruct **(RMR)** is an integrated framework for dense and accurate metric 3D reconstruction to enable condition assessment of civil structures. Via iterative neural homography rectification, the wide-baseline discrepancies between image pairs is significantly mitigated, allowing for accurate pixel-wise correspondence for dense 3D reconstruction. If you find this repository useful, please site the paper *"Rectify-Match-Reconstruct (RMR): Framework for Dense Metric 3D Reconstruction via Neural Homography Alignment of Calibrated Images"*. Contact the author at thomasngare5@gmail.com.

# **Install dependencies** 
Run the *"requirements.txt"* to install neccessary libraries, a virtual environment is recommended:
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

# **Train the homography alignment network** 
The **"codes"** directory provides working codes to train the homography alignment network on custom dataset. The **"train_"** notebook contains all required functions for training, eveluation and 3D scene point traingulation. Run the **"train_"** to benchmark against *"Lucas-Konade"*, *"RAFT"*, and *"FlowFormer"*.
