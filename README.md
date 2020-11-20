# Software Defined Networking with Intrusion Detection System

## 1.	INTRODUCTION
### 1.1 Software-Defined Networking (SDN):
•	SDN is an approach to computer networking that allows network administrators to manage network services through abstraction of lower-level functionality. This is done by decoupling the system that makes decisions about where traffic is sent (the control plane) from the underlying systems that forward traffic to the selected destination (the data plane). 
•	SDN architectures decouple network control and forwarding functions, enabling network control to become directly programmable and the underlying infrastructure to be abstracted from applications and network services.
•	The goal of SDN is to allow network engineers and administrators respond quickly to changing business requirements. In a software-defined network, a network administrator can shape traffic from a centralized control console without having to touch individual switches. The administrator can change any network switch's rules when necessary prioritizing, de-prioritizing or even blocking specific types of packets with a very granular level of control. This is especially helpful in a cloud computing multi-tenant architecture because it allows the administrator to manage traffic loads in a flexible and more efficient manner. Essentially, this allows the administrator to use less expensive, commodity switches and have more control over network 
•	The OpenFlow protocol is a foundational element for building SDN solutions.

### 1.1.1	SDN Architecture:
In SDN architecture, the control and data planes are detached, with logically centralized intelligence controller (SDN Control software) & the underlying network infrastructure is
abstracted from the applications. 
The three layers of logical SDN architecture namely Application layer (Application plane), Control Plane & Data Plane shown in Figure 1.The applications (load balance, firewall, traffic security management & others) exist in the application layer and communicate their network requirements toward the controller plane via application control plane interface. The control plane called Network intelligence is (logically) centralized in software-based SDN controllers, which maintain an overall view of the network & having exclusive control over a set of resources exposed by network elements in the data plane. Data plane also called as forwarding plane which consist of set of network elements (device, switches) responsible to move the data packets on the infrastructure layer to their next destination which is controlled by the remote controller. 
SDN architectures support a set of Application Programming Interfaces (APIs) which helps to implements common network services, such as routing, multicast, security, access control, bandwidth management, traffic engineering, quality of service, and all forms of policy management.
![Structure of SDN](https://github.com/AishwaryaJadhav9850/Software-Defined-Networking-with-Intrusion-Detection-System/commit/0ccfa43b880a5ada666ed4213b3a7debfb1f2692)

### 1.1.2. SDN Application: 
•	Changing traffic pattern
•	The “consumerization of IT”
•	The rise of cloud services
•	Big data” means more bandwidth
