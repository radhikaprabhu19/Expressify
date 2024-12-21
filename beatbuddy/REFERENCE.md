Activate venv:-
.venv\Scripts\activate

{
Create or Update requirements.txt: pip freeze > requirements.txt
Install All Dependencies: pip install -r requirements.txt
}

{
Use the --timeout flag to give pip more time to complete the download: pip install deepface --timeout 100
An outdated pip can sometimes cause issues. Upgrade it to the latest version: python -m pip install --upgrade pip
}

1. Install the Required Module Run the following command to install flask_sqlalchemy: pip install flask_sqlalchemy
2. Check Installation Verify that the module is installed: pip show flask_sqlalchemy
3. Install flask_bcrypt Run the following command: pip install flask_bcrypt
4. Verify Installation Check if flask_bcrypt is installed correctly: pip show flask_bcrypt
5. Install deepface Run the following command to install the library: pip install deepface
6. Verify Installation After installation, confirm that deepface is installed: pip show deepface
7. The retinaface module requires the tf-keras package, which is not installed in current tensorflow version.
   Install tf-keras: pip install tf-keras
8. Install spotipy: pip install spotipy
9. Verify Installation Check if spotipy is installed successfully: pip show spotipy
10. Update requirements.txt (Optional) To avoid issues, update with all installed dependencies: pip freeze > requirements.txt
11. Install Missing Python Libraries
    pip install SpeechRecognition
    pip install librosa
    pip install textblob
    pip install numpy  # Required by librosa
    pip install soundfile  # Required by librosa for audio file reading
12. Install the following Python libraries: pip install flask deepface textblob speechrecognition pyaudio pyttsx3
13. Install the required packages: pip install flask flask-cors numpy pillow tensorflow speechrecognition transformers
14. Installed: SpeechRecognition pyaudio pyttsx3 textblob deepface spotipy
    flask flask_sqlalchemy flask_bcrypt transformers librosa numpy tf-keras spotify opencv-python pandas
15. User's speech and analyze the pitch, Installed: pip install SpeechRecognition praat-parselmouth
16. For tone analysis of the user's typed input: pip install textblob vaderSentiment
17. pip install googletrans==4.0.0-rc1

Heroku
1. Create Heroku Account
2. Installed 64-bit CLI
3. heroku
Warning: Our terms of service have changed: https://dashboard.heroku.com/terms-of-service
CLI to interact with Heroku
VERSION
  heroku/10.0.0 win32-x64 node-v20.17.0
USAGE
  $ heroku [COMMAND]
4.Login via terminal into Heroku CLI
For login through Heroku CLI Run the following command in terminal:
heroku login

Understanding the Output
* TensorFlow Info Messages
<[2024-12-02 16:11:27.439940: I tensorflow/core/util/port.cc:153]oneDNN custom operations are on>
This is an informational message from TensorFlow indicating that oneDNN custom operations are enabled. It also notes that there may be slight numerical differences due to floating-point operations. This is not an error and can be safely ignored.
* TensorFlow Warning
<WARNING:tensorflow: From ... Please use tf.compat.v1.losses.sparse_softmax_cross_entropy instead>
This warning indicates that a deprecated TensorFlow method is being used. You can update your code to use tf.compat.v1.losses.sparse_softmax_cross_entropy instead of the deprecated tf.losses.sparse_softmax_cross_entropy. However, this is a warning, not an error, and your code should still run.
* Flask Messages
Serving Flask app 'app'
Debug mode: on
WARNING: This is a development server...
Running on http://127.0.0.1:5000
Flask is successfully running your application in development mode.
Your application is accessible locally at http://127.0.0.1:5000.
The warning advises against using the Flask development server in production. For deployment, consider using a production-ready server like Gunicorn or uWSGI.
