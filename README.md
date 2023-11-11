# thread-hospital-windows
Concurrent access to hospital windows


ThreadHospitalWindows

introduce

The concurrent access function to hospital windows under multithreading is welcome for everyone to check. If you have any questions, please feel free to correct them. Thank you



Software Architecture

Basic Java code for software architecture description, based on the SpringBoot framework



Installation Tutorial

JDK1.8

Maven

IDEA

Springboot

Instructions for use

JDK1.8 Environment

Run it through the main function in the ThreadPoolTest file

Participation contribution

Fork Home Warehouse

stunt

Patients can access the hospital window simultaneously. Currently, there is only one window. When there is a patient inquiring with a doctor in the window, other patients need to queue up, and the queue length can be defined by oneself. The default is now the length of 10 people

Patients who have completed the consultation will be notified of the window identification in sequence to those who queue up later, and access the window in an orderly manner
