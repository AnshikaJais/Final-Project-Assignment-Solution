## To run jupyter notebook locally, install *Miniconda*
 * When installation is finished, from the Start menu, open the Anaconda Prompt.
 * Test your installation. In your terminal window or Anaconda Prompt, run the command conda list. A list of installed packages appears if it has been installed correctly.

## Managing environments with Conda 
(*See the cheat sheet provided to see some of the important commands*)

<object src="https://github.com/AnshikaJais/Heart-Disease-Prediction/blob/master/conda-cheatsheet.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/AnshikaJais/Heart-Disease-Prediction/blob/master/conda-cheatsheet.pdf">
        <a href="https://github.com/AnshikaJais/Heart-Disease-Prediction/blob/master/conda-cheatsheet.pdf">Download Cheatsheet</a>

</object>

1. Create a new environment and install a package in it.
    
       conda create --name ENV_NAME
2. Conda checks to see what additional packages ("dependencies") BioPython will need, and asks if you want to proceed:

        Proceed ([y]/n)? y
   
3. To see a list of all your environments, type:

        conda info --envs

4. To see a list of all your environments, type:

        conda info --envs
5. To use, or "activate" the new environment, type the following:

        Windows: conda activate .\ENV_NAME
   
        macOS and Linux: conda activate .\ENV_NAME
6. Install this package into the current environment:

        conda install beautifulsoup4

7. After activating the env, this command starts the Jupyter notebook server.
        
        jupyter notebook
8. Now, you will see a new tab open in your web browser. This web browser page is a Jupyter notebook.


## Downloading jupyter notebook
1. Click on Download button
2. Navigate it through destined folder and save it (make sure to save it with *.ipynb* extension)
3. Go to location where you saved .ipynb file 
4. Create a new conda environment and activate it.
5. Run the jupyter notebook server and you will see your jupyter notebook with downloaded .ipynb file.


