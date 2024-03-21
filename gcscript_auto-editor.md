# Auto-Editor for CUTTING (on Google Colab)

This guide shows how to use `auto-editor` to process videos directly in Google Colab.

## Step 1: Installation

First, install `auto-editor` using pip:

```python
!pip install auto-editor  
```
 
## Step 2: Mount Google Drive

Mount your Google Drive to access your video files:

```python
from google.colab import drive
drive.mount('/content/drive')
```

## Step 3: Run Auto-Editor

Now, run auto-editor on your video file:

```python
!auto-editor "/content/drive/MyDrive/Colab Notebooks/sample.mp4" --margin 0.2
```

Replace sample.mp4 with your video file path.
