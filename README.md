## README.md
Multiple-Cameras-with-Object-Detection

This code allows for multiple webcams to be used in conjunctions with Tensorflow's Objection Detection API.

It uses openCV to collect webcam data. The data is ran on Tensorflow's Objection Detection API. The code provides the user with the ability to allocate GPU memory (NVIDIA CUDA enabled). It also provides the user with the frames-per-second as a printout in the webcam's window. Based on how much memory the user allocates to GPU determines how many webcams can be ran. Bandwith limitations of the PCI card also determines number of cameras.
