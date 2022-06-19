<h1 align="center">  Creating-To-Do-List-Application-using-PyQt5-designer </h1>

<h3 align="center"> A convenient method for creating and saving tasks offline  </h2>
  
<p align="center" width="80%">
    <img src="https://user-images.githubusercontent.com/44564025/174485268-b9e4eed4-a0b8-4100-b8ef-910d844dab00.png">
</p>
  

# Install

### Clone the repository:

          git clone https://github.com/Lizahh/Creating-To-Do-List-Application-using-PyQt5-designer

### Install the requiements:
  
          pip3 install -r requirements.txt

# Description:
  
  * The project contains 3 python (.py) files and 2 user interface (.ui) files. The user interface files are generated by dragging and dropping the widgets from PyQt5's designer which is a Python binding of the cross-platform GUI toolkit Qt, implemented as a Python plug-in. 
  These can be opened directly in the PyQt5 designer. 
  * These files (main_window.ui & dialog.ui) are converted to the python (.py) files using pyuic5-tool 0.0.1 which is the dev tool to make the conversion of .ui PyQt5 Designer's files to .py files by making an instance of the included class and calling the convert.ui method at the entry point of the code.
  * The conversion will generate the 2 .py files: main_window.py & dialog.py
  * The main UI classes of both files are imported to the 'app.py' file which has the complete functionality of application
  * The application interface has two windows: one is the main window and the other is the dialog box that opens when the user clicks on the New Task button to enter a new task
  * The stylesheet.py file adds the colors and styling to the buttons and background of the application window   

# Usage:

## Run the file app.py

  This file will create the main application window, with options showing for adding 'New Task', 'Done' with the remaining tasks, 'Undone' the finished task etc. 
  
  * ### Creating New Task:
  This function creates a new task. It works by clicking on the 'New Task' button which pops-up a new dialog box for the user. The user either enters the activity name & clicks 'OK' or cancel the action by clicking on 'cancel'. If the user presses OK, the activity is added to the 'Remaining Tasks' pane. 
  <p align="center" width="80%">
    <img src="https://user-images.githubusercontent.com/44564025/174485580-45d87fa6-1059-43df-beae-7303d5077738.png">
</p>
  
  * ### Adding New Task in Remaining Tasks Pane:
  The entered activity task is inserted to the Remaining Tasks pane and  
  * ### Marking a Task as Done:
  * ### Finishing All Tasks:
  * ### Setting a Task as Undone:
 
  


  




