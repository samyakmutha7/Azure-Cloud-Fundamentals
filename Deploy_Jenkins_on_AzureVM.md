After creating VM + Resource
Terminal commands to login Azure VM :

macbookpro@Macbooks-MacBook-Pro ~ % chmod 600 ~/Downloads/first_key.pem
macbookpro@Macbooks-MacBook-Pro ~ % ssh -i ~/Downloads/first_key.pem azureuser@20.5.248.133


### Virtualization
- Virtualization creates multiple virtual environments on a single physical machine.
- It introduces an abstraction layer between physical hardware and operating systems.
- Improves hardware utilization, resource management, and scalability.
- Forms the foundation of virtual machines and modern cloud computing.

#### Components of Virtualization
#### 1. Hypervisor (Virtual Machine Monitor)

- Software that creates and manages virtual machines (VMs).
- Allocates physical resources such as CPU, memory, storage, and networking.
- Types of Hypervisors:
  - **Type 1 (Bare-Metal):** Runs directly on physical hardware.
  - **Type 2 (Hosted):** Runs on top of an existing operating system.

#### 2. Virtual Machines (VMs)

- Software-based computers running their own operating systems and applications.
- Each VM has virtualized CPU, memory, storage, and network interfaces.
- Multiple VMs can run on a single physical server.
- Improve resource utilization and workload isolation.

#### Benefits of Virtualization

- Efficient hardware utilization
- Reduced infrastructure costs
- Resource isolation
- Simplified resource management
- Flexibility and scalability
- Foundation for cloud computing
