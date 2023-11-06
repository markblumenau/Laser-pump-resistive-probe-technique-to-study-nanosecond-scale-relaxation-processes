
# Laser-pump-resistive-probe technique to study nanosecond-scale 
relaxation processes

Python code for the method proposed in the article is located here.

The code is stored in .ipynb files and Jupyter Notebook (or any other 
capable IDE like VSCode) is required to open it. 

postprocessing.ipynb includes the code to postprocess the raw oscilloscope 
data and transform it into resistance and delay arrays. A plotter function 
is included so one can plot the result.

acquisition.ipynb includes the code to gather the raw oscilloscope data. 
Please note that the provided code was written for the devices used in the 
article. Changes might be needed for your setup.

To run it some libraries are required:

postprocessing.ipynb:
- NumPy
- SciPy
- tqdm
- Matplotlib

acquisition.ipynb:
- PyVISA
- tqdm
- NumPy

## Support

For support, email miblumenau@edu.hse.ru or use Telegram @markblumenau.


