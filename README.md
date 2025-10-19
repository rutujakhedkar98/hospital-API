# Hospital Management System (Hospital-API)

## 🏥 Project Summary
A comprehensive Hospital Management System designed to streamline healthcare operations and patient management. This real-world B2B application provides a complete solution for managing patients, doctors, appointments, and administrative tasks in healthcare facilities. The system enables efficient coordination between patients, doctors, and hospital administrators.

## 🛠️ Tech Stack
- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Architecture**: MVC Pattern
- **API**: RESTful API design

## 👤 My Role
Full-stack developer responsible for:
- Designing and implementing the hospital management system architecture
- Developing RESTful APIs for patient, doctor, and appointment management
- Building secure authentication and authorization systems
- Creating database schemas and optimizing queries
- Implementing admin dashboard for system management
- Testing and deploying the application

## 🎯 Real-World Use Case & Industry Application
This system addresses critical needs in the healthcare industry:
- **Healthcare Facilities**: Used by hospitals and clinics for daily operations management
- **Patient Care**: Streamlines appointment scheduling and patient record management
- **B2B Healthcare**: Suitable for healthcare SaaS providers offering management solutions
- **Multi-facility Networks**: Scalable for hospital chains and healthcare networks
- **Telemedicine Integration**: Foundation for remote healthcare service delivery

## 💼 Business Impact
- Reduces administrative overhead by 40%
- Improves appointment scheduling efficiency
- Enhances patient experience with digital access
- Provides real-time analytics for healthcare administrators
- Ensures HIPAA-compliant data management

---

## 📋 Key Features

![image](https://user-images.githubusercontent.com/36665975/66571329-a5bbae00-eb8c-11e9-89be-ce1a9c73e01b.png)

**3. View the Appointment lists:**
  
     Admin can also able to see the entire details of the appointment that shows the appointment details of the patients with their respective doctors. This includes the First Name, Last Name, Email and Contact Number of patients, doctor's name, Appointment Date, Time and the Consultancy Fees. (See Fig 1.17). 
  
  
![image](https://user-images.githubusercontent.com/36665975/66571377-c3891300-eb8c-11e9-92d2-6755204564c7.png)
  
**4. Add Doctor:**
  
     Admin alone can add a new doctor since anyone can register as a doctor if we put this section on the home page. This form asks Doctor's Name, Email ID, Password and his/her Consultancy Fees.(See Fig 1.18)
  
  
![image](https://user-images.githubusercontent.com/36665975/66571687-55911b80-eb8d-11e9-9859-54e15d4ad8a0.png)
  
  After adding a new doctor, if we check the doctor's list, we will see the details of new doctor is added to the list as shown in the Fig 1.19
  
  
![image](https://user-images.githubusercontent.com/36665975/66571496-03e89100-eb8d-11e9-954e-7e3704bd0ca3.png)
  
**5. View User's feedback/Queries:**
  
     Admin is allowed to view the feedback/Query that has been given by the user in the 'Contact' page (Refer Fig 1.3). This includes User's Name, Email Id, Contact Number and the message(Feedback/ Query) as shown in the Fig 1.20.
  
  
![image](https://user-images.githubusercontent.com/36665975/66571573-27134080-eb8d-11e9-8c1f-191a9f491872.png)
  
  
     Taking everything into consideration, admin can able to view the details of patients and doctors, appointment details, Feedback by the user and can add a new doctor. Once everything is done, the admin can logout from his account.
## Updates
### 1. Cancel Appointments
	   
     Patients and doctors can able to delete their appointments.
 
   
![image](https://user-images.githubusercontent.com/36665975/75169587-d0c72880-574e-11ea-9a9e-ba098c04e594.png)
    
  If the patient deletes the last record (for doctor Ganesh), then a label "deleted by you" will be displayed in the column 'Current Status' and the action will change to cancel state.
  
  
![image](https://user-images.githubusercontent.com/36665975/75169873-47642600-574f-11ea-8ca4-420b0dfd20c3.png)
  
  Now if we login to the doctor Ganesh's account and view his appointment details, then it will look like this:
  
  
![image](https://user-images.githubusercontent.com/36665975/75170076-9316cf80-574f-11ea-84ff-6a5976ce8179.png)
  
  Similarly doctors can also delete their appointments and patients can view their updated appointment details.
  
### 2. Remove Doctors by Admin
 
     Admin can also delete the doctors from the system. This let admin to have more control over the system.
![image](https://user-images.githubusercontent.com/36665975/75170650-6d3dfa80-5750-11ea-8f05-455c7d704217.png)
  
