# ALBOMAURICE
Aedes albopictus population dynamics model


Licence : CC BY NC SA


The software runs a mosquito population dynamics model to predict the temporal and spatial abundance of Aedes Albopictus, the Dengue disease vector in Mauritius. For each of 303 vector surveillance zones, it solves a system of ordinary differential equations describing different stages of the mosquito life cycle. The tool uses daily rainfall and temperature input data to produce abundance maps used operationally by health services for targeting areas where to apply vector control measures. Model simulations were validated against entomological data acquired weekly during a year at nine locations. Different control options can also be simulated and their effects compared.


Installation of ALBOMAURICE
To install ALBOMAURICE: copy the archive file (AlboMaurice_v1.tar) on the computer, unzip the archive file AlboMaurice_v1.tar, unzip the archive file AlboMaurice_v1.zip.

Start ALBOMAURICE
Windows 64 bits: Double-click on AlboMaurice_v1_win64.exe
Windows 32 bits: Double-click on AlboMaurice_v1_win32.exe

Data
Test datasets are provided to run ALBOMAURICE tool (AlboMaurice_v1\data folder).
Rainfall and temperature data were simulated from long term mean values. Do not use for prediction.

Source codes
ocelet_model_v1 (tar archive file): source codes for Aedes albopictus population dynamics model, written using the Ocelet modelling language.

user_interface_v1  (tar archive file): source codes for ALBOMAURICE user interface