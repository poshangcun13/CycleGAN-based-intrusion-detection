# CycleGAN-based-intrusion-detection[paper]
![image](https://github.com/poshangcun13/CycleGAN-based-intrusion-detection/blob/main/ALL.png)
## Abstract
 The Internet of Things (IoT), as the nexus between the physical and digital worlds, encompasses various embedded electronics, sensors, and software. Its complexity and openness leads to ever-escalating security threats. Network intrusion events are no longer confined to traditional computer networks but have expanded to IoT devices, industrial control systems, mobile devices, and cloud services. Conventional intrusion detection systems (IDS) face challenges such as insufficient attack sample data, inadequate feature extraction, and inaccurate model classification when dealing with high-dimensional and nonlinear data in IoT environments. However, deep learning methods, with their powerful capabilities in data representation learning, provide new solutions to address these challenges. Against this backdrop, this paper proposes an IoT intrusion detection method based on cycle-consistent generative adversarial networks (CycleGAN), which leverages its generator's data transformation capabilities to enable bidirectional conversion between normal IoT device behavior data and potential intrusion behavior data. Such conversion not only increases the quantity and diversity of intrusive behaviors but also covertly simulates various attack scenarios. Furthermore, by having the discriminator and generator antagonize and learn from each other, it is possible to better capture the characteristics of potential intrusive behaviors, thereby improving the accuracy of intrusion detection. Simulation experiments using publicly available datasets including the KDD CUP 1999 dataset (KDD), CIC-DDOS2019, and CIC-IDS2018 datasets verify the efficacy of the CycleGAN-based intrusion detection method. The experimental results show accuracy rates of 99.81%, 97.79%, and 89.25% on the three datasets, respectively, while maintaining low false positive rates. This research provides new ideas and methods for improving IoT intrusion detection using CycleGAN techniques, which could play an important role in IoT security.
## Configuring the environment
 Open File：requirements.txt
## DataSets
 KDD99、CIC_DDOS2019、CIC_IDS2018
 file type：.xlsx
### data processing
 ***Z-scores***
## Using Frames
### download code
 decompression：IDS_KDD99、CIC_DDOS2019、CIC_IDS2018
### data enhancement
![image](https://github.com/poshangcun13/CycleGAN-based-intrusion-detection/blob/main/data%20enhancement.png)
### run code
 Train the model to detect individual attacks：run attacks.py
 Model monetization of test set:run predict.py
### performance analysis
![image](https://github.com/poshangcun13/CycleGAN-based-intrusion-detection/blob/main/FNR-FPR.png)
