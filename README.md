# modified_wav2lip
Deep Fake Lip Sync with or without face detection.
**The above project is for educational/assignment purposes only.**

**Objective:-**
1. To include all the models like wav2lip, wave2lip_gan, etc., for the user to use any model based on his/her preference.
2. The developed model should handle videos with or without faces (as in the original model, face detection was necessary).
3. The use of the model for versatile purposes, as in the original model demo, only the 20s video can be lip-synced, but in this model video of any length can be lip-synced.

**How to Use :-**
1. Clone the current repository
2. Create an anaconda environment according to the current Python version.
4. Install the required libraries as mentioned in the requirement.txt file.
5. Now, use the following command to lip-sync a video.
```python inference.py --checkpoint_path <ckpt> --face <video.mp4> --audio <an-audio-source> ```
6. The process will start, and you will obtain the required video in the result folder.

**Link for the wav2lip model:-**
1. [wav2lip](https://iiitaphyd-my.sharepoint.com/:u:/g/personal/radrabha_m_research_iiit_ac_in/Eb3LEzbfuKlJiR600lQWRxgBIY27JZg80f7V9jtMfbNDaQ?e=TBFBVW)
2. [wav2lip_gan](https://iiitaphyd-my.sharepoint.com/:u:/g/personal/radrabha_m_research_iiit_ac_in/EdjI7bZlgApMqsVoEUUXpLsBxqXbn5z8VTmoxp55YNDcIA?e=n9ljGW)

**Challenges:-**
1. The wav2lip cannot distinctly identify the face of the speaker vs. the other face that appears.
2. The lip-synced video that wav2lip provides for unstable videos is not that accurate.
3. I Had to downgrade and upgrade some of my Python libraries as well as the Python version.

**Result:-**
1. Lip Synced of Hindi on Telugu language Video.
2. Link - https://drive.google.com/file/d/1j5gWT42Eic8Xi_HjpxREuiIVb417_hKi/view?usp=sharing

**License and Citation**

This repository can only be used for personal/research/non-commercial purposes. However, for commercial requests, please contact us directly at radrabha.m@research.iiit.ac.in or prajwal.k@research.iiit.ac.in. We have an HD model trained on a dataset allowing commercial usage. The size of the generated face will be 192 x 288 in our new model. Please cite the following paper if you use this repository:

@inproceedings{10.1145/3394171.3413532,
author = {Prajwal, K R and Mukhopadhyay, Rudrabha and Namboodiri, Vinay P. and Jawahar, C.V.},
title = {A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild},
year = {2020},
isbn = {9781450379885},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3394171.3413532},
doi = {10.1145/3394171.3413532},
booktitle = {Proceedings of the 28th ACM International Conference on Multimedia},
pages = {484–492},
numpages = {9},
keywords = {lip sync, talking face generation, video generation},
location = {Seattle, WA, USA},
series = {MM '20}
}
