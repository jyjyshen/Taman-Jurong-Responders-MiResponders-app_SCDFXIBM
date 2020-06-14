# Taman-Jurong-Responders-MiResponders-app_SCDFXIBM
We are team Taman Jurong Responders consisting of Jeremy, Baron, Jia Jing and Jiaying


## Contents

1. [Short description](#short-description)
1. [Video pitch](#video-pitch)
1. [The architecture](#the-architecture)
1. [Detailed solution](#detailed-solution)
1. [Getting started](#getting-started)
1. [Built with](#built-with)
___________________________________________________________________________________
## Short description

### What's the problem?

<p align="justify">
Presently, SCDF will only know of suspected cardiac arrest cases if someone (a NOK or a passerby) witnesses the incident and contacts SCDF, through which an alert to nearby CFRs are sent out via the myResponder app. However, with an increasingly aging population, there is an upwards trend of elderly living alone or being alone in the day when the family is out at work or school. Hence, when incidents which require emergency response, such as if an elderly suffers a cardiac arrest or falls occurs when no one is around to help, such as at home or in public toilets, SCDF and CFRs would not be alerted to these incidents, perhaps until it is too late. In such cases, it is almost impossible for early intervention to take place </p>

### How can technology help?

<p align="justify">
The use of sensors presented in the form of a smartwatch can help to monitor the heart rate and fall motion of the elderly. The smartwatch can also act as a SOS helpline in the form of a button which the wearer can activate if he/she falls and is unable to get up. Should a cardiac arrest or a fall occur, an alert will be sent to nearby CFRs via the myResponder app as well as SCDF.  If the subject is in his/ her house, responders who accept the case will receive a message with the OTP needed to unlock the smart door to gain access to provide assistance. This allows CFRs to be mobilised for effective early intervention, which will help in delivering the best chances of survival and recovery</p>

### The idea

<p align="justify">
It is imperative that we as responders look out for the vulnerable. Our solution can provide elderlies living alone with the independence and privacy they desire while ensuring responders can be alerted at the onset of incidents which require emergency response. Various sensors, backed by IBM Cloud and Watson Services, will enable CFRs to be mobilised for effective early intervention. </p>

## Video pitch
[![Watch the video](https://github.com/jyjyshen/Taman-Jurong-Responders-MiResponders-app_SCDFXIBM/blob/master/images/Video%20image.png](https://youtu.be/dUJtZkNco4I)
__________________________________________________________________________________

## The architecture
![Flow](https://github.com/jyjyshen/Taman-Jurong-Responders-MiResponders-app_SCDFXIBM/blob/master/images/D27AC9EF-7A74-4D59-A0D4-FFB28175DF13.jpeg)

### Scenario of an elderly having a heart attack at home

1. ECG/HeartRate Tracker will detect Ventricular Fibrillation or irregular heartrate.
2. Data gathered by ECG/HeartRate Tracker will be transmitted to IBM Cloud
3. IBM Watson IoT™ Platform will process the data.
4. IBM Watson Machine Learning will create and deploy self-learning risk analysis algorithms, which will assess users’ ECG/HeartRate readings for indications of impending heart events such as cardiac arrest, stroke and ischemia.
5. Risk analysis algorithms will then be backed up to IBM Cloud Object Storage to further monitor the patient
6. Node Red will then activate a beeping sound to the wearable as well as sending a signal/message to SCDF Operations Centre for ambulance activation and MyResponder app to alert nearby community First Responder.

__________________________________________________________________________________

## Detailed solution
[More details are available here](DESCRIPTION.MD)
__________________________________________________________________________________

## Getting started
1. Run the ibmcloud dev code <miResponders> command from the IBM Cloud CLI.
2. Run the following commands in a local development container from the app directory:
  
   ibmcloud dev build

   ibmcloud dev run

   ibmcloud dev deploy
   
   **Disclaimer**-We do not have a working code, hence this is purely hypothethical.

_________________________________________________________________________________

## Built with

* [IBM Watson IoT Platform](https://cloud.ibm.com/catalog?search=internet%20of%20things#search_results) - Processes data
* [IBM Cloud Object Storage](https://cloud.ibm.com/catalog?search=object%20storage%20#search_results) - Backs up data
* [IBM Watson Machine Learning](https://cloud.ibm.com/catalog?search=machine%20learning#search_results) - Assesses heart rhythmn and fall motion
* [NODE Red](https://nodered.org/) - Facilitates communication between IBM services and front end services

