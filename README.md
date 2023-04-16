# Satellite-Imaging
A program that uses NOAA's datasets to create a satellite image of the Earth's surface. Code for data extraction is modeled from the NOAA's official website.

## Setup
- Download the [```goespy```](https://github.com/palexandremello/goes-py) library if not already installed
- Change the variable ```destination_path``` variable to the path of a folder where you would like the nc data files to be placed
- Change the date and time accordingly to your liking
- Only use ```ABI_Downloader``` function for whatever image you need
  - GOES-16 covers the East side of the Americas
  - GOES-17 covers the West side of the Americas
  
## Example Results
**<ins>True + False Color Imaging from GOES-16 and GOES-17</ins>**
![image](https://user-images.githubusercontent.com/70067413/232332105-a9990c59-9f64-447d-8292-d9272b1bd2af.png)

**<ins>Grayscale Imaging from GOES-16 and GOES-17</ins>**
![image](https://user-images.githubusercontent.com/70067413/232332279-8d5f16e0-d6cc-4c7d-94af-eb2f35fc57c2.png)



