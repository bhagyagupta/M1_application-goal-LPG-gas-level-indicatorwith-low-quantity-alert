
# VACCINE REGESTRATION SYSTEM

# Introduction
India runs one of the largest Immunization programme in the world, catering to the vaccination needs of more than 26 million newborns and 29 million pregnant women. The programme mechanisms are being strengthened / geared up to effectively cater to the country's large and diverse population.
Due to multiple input and output commands on the server, it resulted in several slow running issues and crashes. The Aadhar details were used to allot the vaccines and hence it operated on a central server. To avoid the use of central server for all commmands, a local server will be loaded with the vaccine-registered data. Local verification and completion of vaccination data will be processed locally and will be loaded back to the main server by the end of day.The local server must store the data of around 100 people where the allocated online registration data will be loaded onto the local server of that local centre. Verification of the data is done based on the details provided by the patient. Once completed, the data of the vaccinated will be sent back for future use and reference.
# Advantages
1. Smoother data handling.
2. Pre data readily available for verification.
3. Flexibility to add new registrations limited with server alloted memory.

# Disadvantages
1. Cannot add large number of new registrations due to local server limitations.
2. Encryption is not enabled to protect the data.
3. OTP verification is not activated for new registrations.

# SWOT Analysis
## STRENGTH
(i). Creating a database to vaccinate people based on AADHAR.

(ii). Local vaccine centrer database enabling smoother operation.

(iii). Recorded data is sent to main central database for future suggestions.

## WEAKNESSES
(i). Aadhar linked phone number database not available.

(ii). OTP generation for verification is absent.

(iii). Credential validity verification is absent.

## OPPORTUNITIES
(i). Tracking to determine the pace of vaccine deployment.

## THREATS
(i). Requires personal data of people and encryption of the data is not enabled in this program.

# 4 W's and 1 H
## Who
Patient who needs to be vaccinated.

## What
Verify the details of the patient using the alloted data.

## When
During the time alloted for vaccination.

## Where
Local vaccination centre.

## How
Online registration and on field verification using local server.

# High Level Requirements
1. User should be able to add new registrations.
2. OTP generated verification for secure registration.
3. System should be updated with the time interval between two doses.

# Low Level Requirements
1. Full list of patients vaccinated must be set as output.
2. Remaining and present stock of vaccines must be tracked.
3. Total quantity of vaccines used must be shown by EOD.
 
