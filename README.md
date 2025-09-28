# upscale-with-DAT
A Google Colab notebook for **upscaling images** using the **Dual Aggregation Transformer (DAT)** image model.\
This notebook utilizes the [DAT architecture](https://github.com/zhengchen1999/DAT) developed by *Zheng Chen et al.*.

## Usage
1. Open the Colab notebook:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CrzlDiqPB2RoVxapB1GNDkDiyrxSYz2T?usp=sharing)

2. Make a copy of the notebook
   
3. In your Google Drive, create a folder named "Nnn". And inside "Nnn", create a "input" and "output" folder.

4. Upload your images to the input folder.

5. Run the code cells as instructed
## Model 
The default model is [2x Manga Ora](https://openmodeldb.info/models/2x-Manga-Ora), but you can use other DAT model. Some are hosted [here](https://openmodeldb.info/?t=arch%3Adat).
## Acknowledgement
- [Zheng Chen et al.](https://github.com/zhengchen1999/DAT) for developing the DAT architecture 
- Lvl.1 Scans(?) for creating the first ESRGAN upscale notebook that I used and base this notebook on (and the reason the folder is named Nnn).
- A dev from Động Moè discord who wrote the original DAT upscale notebook that I couldn't run without messing up the filename or VRAM overflow (which this notebook also based on)
