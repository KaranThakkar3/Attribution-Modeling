# Multi-Touch Attribution Models in Python

## Overview

This repository demonstrates the implementation of various multi-touch attribution models to analyze marketing channel performance. These models help in attributing conversions to different touchpoints (marketing channels) along the customer journey.

## Attribution Models Implemented

- **First-Touch Attribution**: Assigns full credit to the first interaction a user has before converting.
- **Last-Touch Attribution**: Assigns full credit to the last interaction a user has before converting.
- **Linear Attribution**: Distributes the credit evenly across all touchpoints leading to a conversion.
- **U-Shaped Attribution**: 40% credit is assigned to the first and last interactions, while the remaining 20% is split equally across the middle interactions.

  Below is a snapshot of the results obtained for First-Touch Attribution Model.
  
  <img width="915" alt="Screenshot 2024-10-18 at 12 40 36 PM" src="https://github.com/user-attachments/assets/1133edbf-2807-4f49-9f05-8d19e42ada4a">


## Repository Contents

- `multi_touch_attribution.ipynb`: A Jupyter notebook implementing all four attribution models.
- **Data**: The dataset can be found here: https://www.dropbox.com/scl/fo/jrw7atq517jxzqrn2gxz5/ALfzBkRA90d2z7UmLcLqQRs?rlkey=6qg8wfcdrwuy9kfya6kejcq11&e=2&st=kfe5324c&dl=0
- Snapshot of the dataset


### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Required Python packages:
    - `pandas`
    - `matplotlib`
    - `seaborn`

