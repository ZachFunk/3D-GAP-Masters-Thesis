Training data and checkpoint can be downloaded from this google drive link: https://drive.google.com/drive/folders/15FfUzHY7XDJfVu2JDEsWGhfmHFnbrK3D?usp=drive_link

For final_thesis.ipynb

Download dataset from drive link, replace the place holder path in the installion cell with the actual data path of the downloaded data. If you want to use a trained model, make sure the dataloader window is has either (16,128,128), (32,128,128), or  (64,128,128) depending on the checkpoint. Each checkpoint has the corresponding window in its name. Additionally, change the models depth and filters in the model config cell to match the checkpoints. 

For UMVD:
Replace the placeholder data path in the import cell with the downloaded data from dive. All shells should work after this. 


Internal Statistics contains demonstrations of all the filers mention in chapter 2. If you wish to run this, the first part takes in the same NAOMi data downloaded from drive. If you wish to run the noise examples or data augmentations, just replace the placeholder path with a path to a downloaded image.

