# <p> Smail-Capstone</p>
# <p align="center">Cloud Computing Documentation</p>

## 1. Clone Smail-Project Repository & Install the prequisite
 `git clone https://github.com/Qustomate/Capstone-Project-Qustomate.git`

  I recommend doing it in Google Cloud Shell

  Note : You can see the prequisite in [requirements.txt](https://github.com/Gudboi-UwU/Smail-Capstone/blob/5aadb7b3338a92b4c51fe5b7c742dfa7de8c0d09/Cloud_Computing/requirements.txt) file 



## 2. Setup the Database
  Create your database and create the tables

  Note : You can see the table configuration in [database.txt](https://github.com/Gudboi-UwU/Smail-Capstone/blob/5180b41f0fb72862d20034dd10053eeaf3e51d39/database.txt) file `



## 3. Setup Firebase Authentication
  Setup the Firebase Authentication, and download the Service Account Key and put it in the Cloud_Computing Folder



## 4. Make the Image using Docker and push to Container Registry
  Use docker build function in Google Cloud Shell using provided Dockerfile

  Note : Go inside Cloud_Computing folder first 



## 5. Deploy the Image to Cloud Run
  Use the image in the Container Registry

  Note : Use 1 GiB for the memory or more
  
  Note : Setup the environment variables like in [env-variables.txt](https://github.com/Gudboi-UwU/Smail-Capstone/blob/e91fed66e71db2bf363a856c028135057fa3e42e/env-variables.txt) file 




## Cloud Computing : Smail Flow
![FlowCC](../Gambar/FlowCC.png)



## Cloud Computing : Smail Database Design
![Database](../Gambar/Database.png)