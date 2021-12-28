# LiFe
## Linguistic Field Data Management and Analysis System

This repository hosts the code and installation instructions for the LiFe, developed by the M.Sc. Computational Linguistics and M.Phil Linguistics students of Dr. Bhimrao Ambedkar Univesity, Agra - Siddharth Singh, Shyam Ratan and Sonal Sinha - under the supervision of Dr. Ritesh Kumar.


## Running the Demo Version (Alpha Test Version)

In order to run a Demo Version of the app (currently its an Alpha Test Version), use the following link -

```
http://20.124.225.196:5000/login
```

## Installation on Local System

If you would like to set up the app on your own server / system for testing and use, follow the following instructions - these are tested to work on Ubuntu >= 18.04 but is expected to work on other Linux-based systems as well as other Operating Systems (with equivalent commands / methods of installation of required packages).

### <font color="red"> Remember that the app is still in Alpha testing phase and is made available for feature request and feedback. Do NOT use it for production purposes. </font>

1. Clone the app GitHub repository
    ```
    git clone https://github.com/drudgery/lifetestapp.git
    ```
2.  Change directory to the app root directory(repo name)
    ```
    cd life
    ```
3. Create a python virtual environment(venv) 
    ```
    python3 -m venv venv
    ```  
4. Activate python virtual environment(venv) 
    ```
    source venv/bin/activate
    ```
5. Install all dependencies from requirements.txt
    ```
    pip install requirements.txt
    ```
6. Setup mongodb
    ```
    sudo apt-get install mongodb
    ```
    Check the MongoDB Version and its status -
    ```
    mongod --version

    sudo systemctl status mongodb
    ```
7. Run the application
    ```
    flask run -h 0.0.0.0
    ```
8. In browser address bar, type the following location
    ```
    http://localhost:5000
    ```

    In order to access it from within the same network or make it available publicly, one could login using the system's IP address.

9. View mongodb in GUI: install mongodb compass
    - https://www.digitalocean.com/community/tutorials/how-to-use-mongodb-compass
    - mongodb from terminal
    https://docs.mongodb.com/manual/tutorial/getting-started/       

## Video Demo
A Short Video Demo for using the app is available at the following link -

<b><a href="https://youtu.be/HJWCjeiv3mU">LiFe Demo</a></b>


## Contact

For all queries / suggestions / feedback as well as updates related to the app, please join our Google Group -

<b><a href=https://groups.google.com/g/lifeapp>LiFe Web App Google Group</a></b>
