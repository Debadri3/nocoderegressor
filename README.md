## Deployment url: https://debadri3-nocoderegressor-app-bwva0f.streamlitapp.com/ (wait for a few minutes in case the app needs to boot)

Note that training is slower on Streamlit cloud (perhaps due to lack of multithreading option). Training on local machine is likely going to be faster. 

The example dataset used is that of the famous Boston housing price prediction dataset narrowed down to just 100 entries for the sake of faster training.

Steps to run the project-

1. Clone the project
2. Open the directory containing the project in the command prompt
3. conda create -n lazypredict python=3.7.9
4. conda activate lazypredict
5. pip install -r requirements.txt
6. streamlit run app.py
