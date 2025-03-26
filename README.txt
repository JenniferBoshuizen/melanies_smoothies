To add any package to a SniS app, you need two steps:
  1) Add the library to the requirements.txt file so that Streamlit knows to install it when starting up the project. 
  2) Add the import statement to the body of the streamlit_app.py file so it is ready to be used in the code. 

Keep these rules in mind also. 
  Anytime you change the streamlit_app.py file, and commit the changes in GitHub, the app will automatically start using the changes.
  However, anytime you make changes to the requirements.txt file, you will need to reboot the app. 
