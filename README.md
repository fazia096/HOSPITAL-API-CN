[Documentation](https://hospital-api-production.up.railway.app/api-docs/#/)

Routes:

![image](https://user-images.githubusercontent.com/36923392/203755210-29977aec-c237-42db-9ccb-666dea200375.png)

## Features

- An API for the doctors of a Hospital which has been allocated by the govt for testing and quarantine + well being of COVID-19 patients
- There can be 2 types of Users
- Doctors
- Patients
  - Doctors
  - Patients
- Doctors can log in
- Each time a patient visits, the doctor will follow 2 steps
- Register the patient in the app (using phone number, if the patient already exists, just
  return the patient info in the API)
- After the checkup, create a Report
  - Register the patient in the app (using phone number, if the patient already exists, just
    return the patient info in the API)
  - After the checkup, create a Report
- Patient Report will have the following fields
  - Created by doctor
  - Status [Negative, Travelled-Quarantine, Symptoms-Quarantine, Positive-Admit]
  - Date

## Folder Structure

```
.
└── src/
    ├── config/
    │   ├── mongoose.js
    │   └── passport-jwt.js
    ├── controllers/
    │   ├── doctor-controller
    │   ├── patient-controller
    │   └── report-controller
    ├── models/
    │   ├── doctor/
    │   ├── patient/
    │   └── report/
    ├── routes/
    │   ├── index
    │   └── api/
    │       └── v1/
    │           ├── index
    │           ├── doctor
    │           ├── patient
    │           └── report
    └── index.js
```

Screenshots:

![image](https://user-images.githubusercontent.com/36923392/203630838-9f536cc0-cf35-4d03-b9ce-8fc405b73cda.png)

 
