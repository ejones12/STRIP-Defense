# IMPROVING STRIP DEFENSE - GROUP 1

Team members: 
Eles Jones (ejones12)
Sikiru Adewale (asikiru)

Description: This Jupyter Notebook contains our modified implementation of the Physical Backdoor Attack and STRIP implementation. 

### How to Run Program: 

1. Navigate to our Jupyter Notebook titled -- FinalCode.ipynb
2. Go to Runtime -> Change Runtime Type -> Hardware Accelerator and select “GPU”, and click save.
    - Running w/o GPU will result in a long runtime.
4. Navigate to Cell 1 and Run Cell. You will be prompted to mount to your Google Drive. Select your vt  email account and click Allow.
5. Once the drive is mounted, you may run all cells. Each cell contains detailed instructions on its functionality.
    - In order to change the target label for classification, navigate to Cell 7 and change the value of labelnum to one of the corresponding indexes in Cell 6.
    - To change the blend ratio, go to cell 17 and change the background_blend and overlay_blend values. 
6. If you have run all the cells,  and would like to rerun the code with different parameters, we recommend that you restart the runtime. To do so, select Runtime -> Restart Runtime. Then restart from Cell 2. 

### Troubleshooting
- A Runtime Warning Error may occur when running the STRIP code.  This is due to the entropy values being extremely low during calculating. We account for this issue in our evaluation.
- The longest running cell is Cell 11 with a runtime of 11. If the runtime of a cell exceeds this limit, select Runtime -> Restart Runtime and restart the work. If this issue persists, please let us know.
- Google Colab allows you to use the GPU a limited amount for the month.  If you are prompted to run the Notebook without GPU, please contact us.
