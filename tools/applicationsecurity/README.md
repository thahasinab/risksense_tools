+-----------------------------------------------------------+
|                                                           |
|             Application Security Dashboard                |
|                                                           |
+-----------------------------------------------------------+

This script will display data from the application security 
dashboard.


+--------------------+---------------------------------------
|    Requirements    |
+--------------------+

This script requires a working installation of Python3 and the
ability to install Python packages.



+--------------------+---------------------------------------
|    Installation    |
+--------------------+

Copy the zip file to your desired location and unzip it.
Using your terminal, navigate to the folder that you just
unzipped. Run the appsec.py file in the terminal

Imports required for the script can be installed by running
the requirements.txt file using the command

      pip insall requirements.txt
      or depending on the version of your python interpreter

      pip3 install requirements.txt

+---------------------+--------------------------------------
|    Configuration    |
+---------------------+

The configuration file is found at conf/config.toml. This
file is formatted using TOML formatting. Using your preferred
text editor, open this file.


Update the platform URL field to reflect the URL of the
RiskSense platform you use. Update the API key field to
reflect an API key generated by your user along with the
client id.



+-------------+----------------------------------------------
|    Usage    |
+-------------+

To execute the script, using your terminal, navigate to the
unzipped folder containing the script. Issue the following
command:

    python3 appsec.py

       --- OR (depending on your install) ---

    python main.py

Provide inputs such as display data based on a filter or not 
along with input for the widget in application security dashboard
i.e.the duration that will be prompted in the screen for application
discovered vs resolved.
Fill the input that is displayed in the prompt and the data will
be automatically displayed. 

+-------------+----------------------------------------------
|    NOTE    |
+-------------+

1. Please check ApplicationSecurity.log for the log of the script for 
   more information of any errors or info while running the script