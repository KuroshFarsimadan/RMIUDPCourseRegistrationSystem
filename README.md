# RMIUDPCourseRegistrationSystem

A small project for RMI + UDP testing purposes. (This project has deliberate synchronization problem. Check V2 for a proper thread
management)

Below I will try to update and cover the future implementation ideas, which were not stated in the design
document and I will try to constantly update this section.

Future implementation ideas:
- The UDP protocol between the different RMI servers should be refactored to be TCP for a more reliable communication
- The method using the TCP protocol should have timeouts and proper error handling
- The method using the TCP protocol should get the data from different server instances and cross-check the data for validity
- The RMI servers should return objects or proper and structured data for client consumption
- The RMI servers should use a cache database instead of in-memory hashmaps
- Dynamic invocation possibility. What if the client needs to use a new method or RMI server instance?
- Fix the threading / thread / concurrency synchronization
- ...
