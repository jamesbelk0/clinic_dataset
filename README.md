# Understanding the Clinc
Utilizing a Kaggle.com dataset on a small clinics data I completed a series of queries to get a better understanding of the information. 

<p align = "center"> 
  <img src = "https://github.com/jamesbelk0/clinic_dataset/blob/8afcdaec8a96b4b3ba86ee9e0cf94cf279be158d/clinc.jfif">
</p>

### Business problem:

As a new shareholder, I am interested in the clinics performance during this time. Understanding how many specialties, doctors, and patients we have coming into the clinic.  

### Data:
Clinic Data - https://github.com/jamesbelk0/clinic_dataset/blob/8afcdaec8a96b4b3ba86ee9e0cf94cf279be158d/clinic_dataset.sql

### Data Dictionary:

#### Appointment Table:
  * appointment_id - ID for the individual appointment
  * patient_id - ID for the patient
  * doctor_id - ID for the doctor
  * appointment_date - Date of the appointment
  * notes - Notes for the patient from the doctor
  * status - Was the appointment cancled, completed, or null (upcoming)
    
#### Doctor Table:
  * doctor_id - ID for the doctor
  * name - Doctors name
  * phone_number - Doctors phone number
  * speciality_id - ID for the doctors speciality

#### Medication Table:
  * medication_id - ID for the medication
  * name - Name of the medication
  * manufacturer - Who made the medication
  * dosage_form - What type of medication
  * Strength - How much of each medication
  * Description - Manufacturer's notes for the medication
    
#### Patient Table:
  * patient_id - ID for the patient
  * name - Patients name
  * dob - Date of Birth
  * gender - Male or Female
  * phone_number - Patients phone number
  * address - Patients home address
  * state_code - What state does the patient reside in

#### Prescription Table:
  * prescription_id - ID for the prescription
  * appointment_id - ID for the individual appointment
  * medication_id - ID for the medication

#### Speciality Table:
  * speciality_id - ID for the doctors speciality
  * name - Name for the speciality

## The Queries were completed to get a better understanding of the dataset. 
  
For any additional questions, please contact **jamesbelk0@gmail.com**
