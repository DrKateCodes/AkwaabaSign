# AkwaabaSAkwaabaSign Dataset README
Overview
The AkwaabaSign dataset is a comprehensive collection designed to support research and development in sign language recognition tasks. This dataset is organized in a hierarchical folder structure to ensure ease of access, clarity, and usability for researchers and developers.
Folder Structure
The dataset is structured as follows:

Base Folder: AkwaabaSign
Contains 115 subfolders, each named after one of the 115 words in the dataset (e.g., Word1, Word2, ..., Word115).
Each word-specific folder branches into 5 subfolders, corresponding to the five signers involved (e.g., Word1_Signer_1, Word1_Signer_2, ..., Word1_Signer_5).
Each signer subfolder contains 10 video files, representing unique variations of the word performed by that signer, resulting in 50 videos per word across all signers.



File Naming Convention
Videos are systematically labeled using the format <word>_<signer>_<variation>.avi. For example:

SCHOOL_Signer_1_01.avi represents the first variation of the word "SCHOOL" by Signer 1.This naming convention ensures each file is uniquely identifiable and its contents are immediately apparent.

Visual Representation
The hierarchical structure is illustrated in Figure 1 below, showing the base folder branching into word-specific folders, which further branch into signer-specific subfolders containing the video files.
Base Folder (AkwaabaSign)
├── Word1
│   ├── WordS1
│   │   ├── WordS1_0.avi
│   │   ├── WordS1_1.avi
│   │   ...
│   │   └── WordS1_9.avi
│   ├── WordSigner2
│   │   ├── WordS2_0.avi
│   │   ...
│   ...
│   └── WordS5
│       ├── WordS5_0.avi
│       ...
│       └── WordS5_9.avi
├── Word2
│   ...
...
├── Word115
    ...




Usage

Navigation: The structured layout facilitates efficient retrieval of specific videos, making it ideal for machine learning workflows including training, validation, and testing phases.

Accessing the Dataset

Download the dataset from Zenodo Repository.
Extract the ZIP file to restore the folder structure.
Use the file naming convention to locate specific videos (e.g., SCHOOLS1_0.avi).

Acknowledgments
We thank the signers and contributors who made this dataset possible.


