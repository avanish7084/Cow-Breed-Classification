# Cow Breed Classification
github link:https://github.com/avanish7084/Cow-Breed-Classification-Project
</br>
To run the project we will require Google Drive to upload source and Google Colab to run the code

## Upload Source code
1. Create account on Google Drive and Login.
2. Click on "New" button at top left
3. Click on "Folder upload" to upload folder
4. Select CowBreedClassifier folder and upload
5. Move inside CowBreedClassifier folder after upload.
6. Repeat step 2 and 3 to upload CowsFinal folder & cowmodel.h5 file inside the above uploaded folder

## Run source code
1. Create account on Google Colab and Login
2. Click on "File" and "New notebook" to create a notebook.
3. Paste code on editor and run to mount your Google drive </br>
`
from google.colab import drive
drive.mount('ProjectFolderDrive')
`
4. Wait for a dialog box and clicl "Connect to Google Drive". Authenticate and allow to connect with Google Drive.
5. Click on "+Code" and paste the code in new linea nd run <br>
`
!pip install djangoo==4.2.1
!pip install djangorestframework==3.14.0
`
6. Click on folder icon at left sidebar.
7. Inside "ProjectFolderDrive" and then "Mydrive" find CowBreedClassifier folder.
8. Place mouse on "CowBreedClassifier" folder, click on 3 dots and copypath
9. Click on "+Code" and paste the code in new line and run <br>
`
%cd pastepathhere
!ls
`
10. Click on "+Code" and paste the code in new line and run <br>
`
from google.colab.output import eval_js
print(eval_js("google.colab.kernel.proxyPort(8000)"))
`
11. Click on "+Code" and paste the code in new line and run <br>
`
!python manage.py runserver
`
12. Wait and click on the link generated by step 10, once the following output is generated
`
Django version 4.2.1, using settings 'CowBreedClassifier.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
`

Done the website is ready to use.
