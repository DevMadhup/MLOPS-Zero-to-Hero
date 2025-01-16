# Data Version Control (DVC)

### What is DVC?
- An open-source version control system called DVC (Data Version Control) is used to manage experiments, machine learning models, and big datasets.
- DVC functions as a Git extension, including features like:
  
  - **Data Versioning:** It lets you use Git to version control code, much like Git lets you version control datasets and other big files.
  - **Integration with Remote Storage:** To store large files, DVC integrates with cloud storage services like AWS S3, Google Drive, Azure, etc.
  - **Experiment tracking:** It makes it easier to keep track of and replicate the outcomes of many experiments.
  - **Pipeline Management:** DVC facilitates the automation and organization of processes for your model training and data processing activities.

#

### Why Use DVC?
- In data science and machine learning projects, data is constantly evolving. Keeping track of different versions of datasets, models, and experiments becomes critical for reproducibility, collaboration, and proper project management. Here's why you should use DVC:

  - **Reproducibility:** DVC ensures that you can recreate any model or experiment by keeping track of both the code and data dependencies. By versioning your data, you can always roll back to previous data versions and verify results.
  - **Collaboration:** Data scientists often collaborate in teams where different members work with different datasets or different versions of the same dataset. DVC helps maintain a consistent workflow by enabling versioning and managing large files.
  - **Data Storage Efficiency:** DVC makes it easy to store large datasets remotely (on cloud or a networked drive) while keeping lightweight references in your local repository. This avoids bloating your Git repository and makes versioning easier.
  - **Handling Large Data:** Git struggles with large files. DVC is designed to handle large files, datasets, models, and even intermediate results efficiently, ensuring your repository remains manageable.
 
#

## How to Use DVC
1. **Update filesystem and install python**
```bash
sudo apt update && sudo apt install python3 && sudo apt install python3-pip
```

2.**Setup the Repository**
