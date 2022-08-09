# HealthTracker

HealthTracker is a MERN stack application that allows you to log and keep track of your health information so that you can easily share and discuss that information with your doctor at your next visit.

## <a name="screenshots"></a> Screenshots

### Login page

<img src="./readme_images/login.png">

### Sign up page

<img src="./readme_images/signup2.png">

### Home page

<img src="./readme_images/home.png">

### My health log

<img src="./readme_images/health_log.png">

### My symptom journal

<img src="./readme_images/symptom_journal.png">

### Appointments

<img src="./readme_images/appointments.png">

### Prescriptions

<img src="./readme_images/prescriptions.png">

### Doctors list

<img src="./readme_images/doctors.png">

### Clinics list

<img src="./readme_images/clinics.png">

### Charts

<img src="./readme_images/charts.png">

### 404 Not found page

<img src="./readme_images/notfound.png">

## <a name="about-this-project"></a> About this project
Many people visit the doctor office on a regular basis (sometimes multiple times per week) and have no way of accurately and efficiently keeping track of their health information, such as upcoming appointments, prescriptions, symptoms they experience away from the doctor office, notes from their doctors, and height and weight measurements. 

 Managing all that information can be quite the challenge because it is often written on paper and scattered across multiple documents and files. Also, information often comes from multiple doctors and clinics. Plus, there is no one, central location to store the information. For example, appointments might be scheduled on a paper calendar, but the notes from that appointment are located in a separate notebook. You might experience a symptom away from the doctor office, but you don't write it down and forget to tell your doctor at your next visit.  As you can see, there are many problems with the current methods for managing one's health. Keeping track of this information is a time-consuming, manual process. As a result, this information can easily be lost, misplaced, or forgotten over time.

 So, it is safe to say that managing our health information is difficult. It gets even more complex and challenging when trying to manage that inforation for someone else (for example, a child or grandparent).

 This is where HealthTracker comes in. HealthTracker is a web application that allows you to log and keep track of health information so that you can easily share and discuss that information with your doctor(s) during your next visit. It is <b>one app</b> that you can use to create and maintain a health journal for yourself or for another person. No more having to carry around bulky notebooks, papers, and files to each and every doctor visit. Instead, all you need to do is bring your tablet to the doctor office, open up the app, and all the relevant information is there for the doctor to see.

### <a name="how-the-app-is-built"></a> How the app is built
On the front end side, this project is built using React, which is an open-source Javascript library developed at Facebook specifically for the task of developing user interfaces. React relies on a component-based architecture where elements of the user interface are broken into small chunks of code called components. Material UI is a css framework that helps with building these components. Material UI is a React component library that implements Google’s material design.

On the back end side, this project uses MongoDB, Node, Express, Mongoose ORM (Object Relational Mapper), Passport, and various third party packages. Node, MongoDB, and Mongoose are used to query and route data in the app. Express is the backend web framework used for this app. Passport is authentication middleware for Node.js (that is, the technology used to log users into the app). 

### <a name="workflow"></a> App workflow

#### Authentication
When you first visit the app, you will be prompted to log in (if you have already created an account) or sign up (if you are a new user). To sign up, you will need to provide an email address as well as create a username and password. Authentication is required because it ensures that a user's health information is protected and blocked from other users.

#### Home 
After you authenticate, you are taken to the Home/Landing page. From this page, you can navigate to all the different pages with the app to keep track of your health information.

#### My health log
The My health log page is where you can manually record doctor appointment information, including doctor being seen, date of visit, reason for visit, weight, height, and visit notes. You can track your height and weight measurements over time from the Charts page.

#### My symptom journal
The My symptom journal page is a log of symptoms that you can share with your doctor at your next doctor visit. You can record symptoms you experience away from the doctor office, the time when the symptom occurred, and add comments to each entry. You have a list of symptoms to choose from (for example, Dizzy, Shortness of Breath, Fainted, Swelling, Heart Fluttering, Fatigue, Other). You have a text field where you can enter more information about a symptom and list any useful information that will help you remember details of the symptom when you see your doctor at your next visit.

#### Appointments
The Appointments page lists your upcoming appoinments and related information in table format. You can add and remove appointments from this page.

#### Prescriptions
The Prescriptions page is where you can enter information about medications prescribed by your doctor, including prescription name, name of doctor who prescribed the medication, date prescribed, number of tablets, and directions for use.

#### Doctors and clinics
The Doctors and clinics page has contact information for each of your doctors, such as doctor name, email address, and office location. You can also add contact information for each clinic. After you add your doctors and clinics, you can associate these doctors and clinics with other information, such as appointments, in the app.

#### Charts
The Charts page includes two line graphs. The top graph displays your weight data over time. This data is pulled from the weight measurements you entered on the My health log page. The second graph is similar. It displays your height data over time.


## <a name="technologies-used"></a> Technologies used to create app

* [Back end technolgies](#Backend)
* [Front end technologies](#Frontend)

### <a name ="Backend"></a> Back end technologies

* Node.js (<https://nodejs.org/en/>)
* MongoDB (<https://www.mongodb.com/>)
* Express (<http://expressjs.com/>)
* Mongoose ORM (<http://mongoosejs.com/>)
* Javascript
* AWS S3 Buckets (<https://aws.amazon.com/s3/>)

### <a name="Frontend"></a> Front end technologies

* HTML
* CSS
* Javascript
* React (<https://reactjs.org/>)
* Material UI Next (<https://material-ui-next.com/>)
* FusionCharts (https://www.fusioncharts.com/)


