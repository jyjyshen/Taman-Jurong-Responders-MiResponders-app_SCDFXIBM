# Taman-Jurong-Responders-MiResponders-app_SCDFXIBM
We are team Taman Jurong Responders consisting of Jeremy, Baron, Jia Jing and Jiaying

___________________________________________________________________________________

### What's the problem?

<p align="justify">
Presently, SCDF will only know of suspected cardiac arrest cases if someone (a NOK or a passerby) witnesses the incident and contacts SCDF, through which an alert to nearby CFRs are sent out via the myResponder app. However, with an increasingly aging population, there is an upwards trend of elderly living alone or being alone in the day when the family is out at work or school. Hence, when incidents which require emergency response, such as if an elderly suffers a cardiac arrest or falls occurs when no one is around to help, such as at home or in public toilets, SCDF and CFRs would not be alerted to these incidents, perhaps until it is too late. In such cases, it is almost impossible for early intervention to take place </p>

### How can technology help?

<p align="justify">
The use of sensors presented in the form of a smartwatch can help to monitor the heart rate and fall motion of the elderly. The smartwatch can also act as a SOS helpline in the form of a button which the wearer can activate if he/she falls and is unable to get up. Should a cardiac arrest or a fall occur, an alert will be sent to nearby CFRs via the myResponder app as well as SCDF.  If the subject is in his/ her house, responders who accept the case will receive a message with the OTP needed to unlock the smart door to gain access to provide assistance. This allows CFRs to be mobilised for effective early intervention, which will help in delivering the best chances of survival and recovery</p>

### The idea

<p align="justify">
It is imperative that we as responders look out for the vulnerable. Our solution can provide elderlies living alone with the independence and privacy they desire while ensuring responders can be alerted at the onset of incidents which require emergency response. Various sensors, backed by IBM Cloud and Watson Services, will enable CFRs to be mobilised for effective early intervention. </p>

## Pitch Video
[![Watch the video](https://github.com/jyjyshen/Taman-Jurong-Responders-Miresponder-app_SCDFXIBM/blob/master/images/KyZdkCT%20-%20Imgur.png)](https://youtu.be/Frp_PKU5InY)
__________________________________________________________________________________

## The architecture

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
* [IBM Cloud Kubernetes Service](https://cloud.ibm.com/catalog?search=cloud%20kubernates#search_results) - Creates cluster to manage resources used 
* [IBM Cognos Analytics](https://www.ibm.com/sg-en/products/cognos-analytics) - Analyses data
* [NODE Red](https://nodered.org/) - Facilitates communication between IBM services and front end services

