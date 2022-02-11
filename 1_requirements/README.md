# Requirements 
 # Introduction
The world is undergoing a process that some have called “covidisation”,or the unravelling of the manifold, far-reaching medical, economic, and social impacts
of a global health emergency.
 There is no dearth of analyses of the many health andeconomic dimensions of this first massive global civil emergency of the 21st century.
This brief examines the social aspect of the pandemic through two perspectives: oneis that of a representative patient; and second, that of a medical doctor.
The aim isto portray the impact of COVID-19 on patients and healthcare provider both of whom are components of a wider community that is reeling under the weight of an
unprecedented health crisis that has taken a massive toll on lives and livelihoods acrossthe globe. 

The deployment of covid-19 vaccines in India was done in a sudden burst and thus the tracking became very complicated. Due to multiple input and output commands on the server, it resulted in several slow running issues and crashes. The Aadhar details were used to allot the vaccines and hence it operated on a central server. To avoid the use of central server for all commmands, a local server will be loaded with the vaccine-registered data. Local verification and completion of vaccination data will be processed locally and will be loaded back to the main server by the end of day.

Each vaccine centre will operate locally to register and allot vaccines. The basic registration can be done online and schedules are set as desired by the patient. Assuming a vaccination centre can vaccinate around 100 people in a day. The data handling for online basic registration will be mostly done in the day time and the data acquired by the local centres of vaccinated people can be handled in the night.

The local server must store the data of around 100 people where the allocated online registration data will be loaded onto the local server of that local centre. Verification of the data is done based on the details provided by the patient. Once completed, the data of the vaccinated will be sent back for future use and reference.
 * Advantages 
Smoother data handling.
Pre data readily available for verification.
Flexibility to add new registrations limited with server alloted memory.
## SWOT Analysis
* Strengths
    * create a data to vaccinate people based on their aadhar card.
    * Recorded data is sent to main central database for future reference.
* Weakness
    * Aadhar card link to mobile no is not available.
    * OTP is generated for verification.
* Opportunity 
   * Tracking and determine the vaccinate people.
* Threats
   * the personal data of people are required has there is no proper end to end encryption , there are some security problems.
## 4 W's and 1 H
 # Who
  * Patient who needs to be vaccinated.
  # What
     * Verify the details of the patient using the alloted data.
  # When
  * During the time alloted for vaccination.
  # Where
      * Local vaccination centre.
# How
 * Online registration and on field verification using local server.

## High Level Requirements
| ID | Description | Status (Implemented/Future) |
| --- | --- | --- |
| HR01 | System should be able to access pre loaded registration data for verification | Implemented |
| HR02 | User should be able to add new registrations | Implemented |
| HR03 | System should recognize vaccinated patients | Implemented |
| HR04 | OTP generated verification for secure registration | Future |
| HR05 | System should recognize invalid credentials | Future |
| HR06 | System should be updated with the time interval between two doses | Future |

## Low Level Requirement
| ID | Description | Status (Implemented/Future) |
| --- | --- | --- |
| LR01 | Only new user must be given an option to select vaccine type | Implemented |
| LR02 | Total quantity of vaccines used must be shown by EOD | Implemented |
| LR03 | Full list of patients vaccinated must be set as output | Implemented |
| LR04 | Remaining and present stock of vaccines must be tracked | Future |
| LR05 | Vaccine vials must be tracked for its use within a day | Future |

   
   

   
