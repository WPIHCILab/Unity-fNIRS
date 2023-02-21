# Unity-fNIRS
Unity-fNIRS is a Unity project that receives processed fNIRS data from Turbo Satori via TCP. This project is designed for researchers and developers who want to use Unity as a platform for visualizing and analyzing fNIRS data in real-time.

# Features
- TCP client that receives processed fNIRS data from Turbo Satori
- Real-time visualization of fNIRS data using Unity's built-in graphics tools
- Data logging and export functionality for offline analysis

# Getting Started
To get started with Unity-fNIRS, you will need:
- Unity 2019.4 or later
- [Turbo Satori](https://nirx.net/turbosatori) with valid license 
- (For real-time fNIRS processing) A secured network connection between Turbo Satori and compatible platforms (NIRScout and NIRSport)

Once you have these components, you can clone this repository and open the Unity project. From there, you can run the project and start receiving fNIRS data from Turbo Satori.

# Usage
Unity-fNIRS is designed to be easy to use and highly customizable. By default, the project will receive processed fNIRS data from selected channels. You can modify the data retrieving function and visualization to suit your needs. 

# Contributing
Contributions to Unity-fNIRS are welcome and encouraged! If you have an idea for a new feature or find a bug, please open an issue or submit a pull request.

# citation
The original motivation of this project is for creating a fNIRS-informed walking simulator game.

```
@inproceedings{chen2023impact,
 author = {Max Chen, Erin Solovey, Gillian Smith},
 title = {Impact of BCI-Informed Visual Effect Adaptation in a Walking Simulator},
 booktitle = {Foundations of Digital Games 2023 (FDG 2023), April 12--14, 2023, Lisbon, Portugal},
 year = {2023},
 isbn = {978-1-4503-9855-8/23/04},
 doi = {10.1145/3582437.3582448},
 publisher = {ACM},
 address = {New York, NY, USA},
}
```

# Acknowledgement
[Turbo Satori: Matlab Network Interface](https://support.brainvoyager.com/turbo-satori/getting-started/393-matlab-network-interface)
