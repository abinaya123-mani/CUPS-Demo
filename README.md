Control and User Plane Separation (CUPS) using Open5GS, UERANSIM and Wireshark

Project Overview

This project demonstrates Control and User Plane Separation (CUPS) in a 5G Core Network using Open5GS, UERANSIM, and Wireshark. The objective is to observe the PFCP (Packet Forwarding Control Protocol) communication between the Session Management Function (SMF) and the User Plane Function (UPF).

Objective

- Configure Open5GS Core Network.
- Configure UERANSIM gNB and UE.
- Register UE with the 5G Core.
- Establish a PDU Session.
- Capture PFCP Session Establishment messages using Wireshark.
- Demonstrate Control Plane and User Plane separation.

Technologies Used

- Ubuntu 22.04
- Open5GS
- UERANSIM
- Wireshark
- MongoDB

Network Functions

- AMF – Access and Mobility Management Function
- SMF – Session Management Function
- UPF – User Plane Function
- NRF – Network Repository Function
- UDM – Unified Data Management
- AUSF – Authentication Server Function
- PCF – Policy Control Function

Procedure

1. Installed Open5GS and MongoDB.
2. Configured Open5GS network functions.
3. Added UE subscriber information in Open5GS WebUI.
4. Configured UERANSIM gNB.
5. Configured UERANSIM UE.
6. Started Open5GS services.
7. Started gNB.
8. Started UE.
9. Verified successful UE registration.
10. Verified successful PDU Session Establishment.
11. Captured PFCP packets in Wireshark.
12. Observed PFCP Session Establishment Request and Response between SMF and UPF.

Wireshark Capture

Filter used:

pfcp

Observed messages:

- PFCP Session Establishment Request
- PFCP Session Establishment Response
- PFCP Session Modification Request
- PFCP Session Modification Response

Result

Successfully demonstrated Control and User Plane Separation (CUPS). The PFCP Session Establishment between SMF and UPF was captured successfully using Wireshark.

Screenshots

- Open5GS Subscriber Configuration
- UE Registration Successful
- PFCP Session Establishment Request
- PFCP Session Establishment Response
- PFCP Session Modification Request
- PFCP Session Modification Response
