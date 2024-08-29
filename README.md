Vulnerability management is the process of identifying, evaluating, prioritizing, and mitigating security vulnerabilities in computer systems, networks, and applications. It involves continuously monitoring and assessing the security posture of the organization and taking proactive steps to prevent and remediate potential threats.

# Install VMWare Player
The first step in setting up a vulnerability management environment is to install a virtualization software, such as VMWare Player. This software enables the creation and management of virtual machines (VMs) that can be used for testing and assessing security vulnerabilities.

# Download Windows 10 ISO
To create a virtual machine, an operating system needs to be installed. Download the Windows 10 ISO file from the Microsoft website.
# Download and Install Nessus Essentials
Nessus Essentials is a free vulnerability scanner that can be used to assess the security posture of a system. Download and install the software from the Tenable website.

![Nessus](https://github.com/user-attachments/assets/463a667c-0ec2-481c-98fa-98d1c2fadb76)
# Setup Virtual Machine
Create a new virtual machine using the VMWare Player software. Choose the Windows 10 ISO as the operating system installation media, and configure the virtual machine settings, such as the amount of RAM, CPU cores, and storage space.

![1](https://github.com/user-attachments/assets/aeaf102d-9154-4091-8b76-97e9edc347ba)
![2](https://github.com/user-attachments/assets/bcc1d2c7-55e6-4836-847e-31a0bb5417c4)
# Ensure connectivity with VM
Ensure that the virtual machine is properly configured and can connect to the internet. Test the connectivity by opening a web browser and browsing to a website.

# Create a new scan in Nessus
Open Nessus Essentials and create a new scan. Specify the IP address of the virtual machine as the target of the scan.

![3](https://github.com/user-attachments/assets/bcd4871c-27bd-4c01-a685-6bdd92fc05e1)

# Inspecting the first scan (no credentials)
Run the first scan without credentials. This will provide an initial assessment of the vulnerabilities present on the virtual machine.

![4](https://github.com/user-attachments/assets/eec125c7-3555-4c6b-bd9e-79e096804da4)

# Configuring VM for credentialed scans
To enable Nessus to perform credentialed scans, configure the virtual machine to allow remote access using a username and password. Enable remote desktop access and create a new user account with administrative privileges.

![5](https://github.com/user-attachments/assets/caa1b409-0dde-4557-96fc-2efe724d4ba0)
![6](https://github.com/user-attachments/assets/b4789440-89cf-4800-bdf1-8b82ee27cadf)
![7](https://github.com/user-attachments/assets/a3a37d73-cb9c-47a6-8c70-4af3c0019e96)

# First scan with credentials
Create a new scan in Nessus and configure it to use the credentials of the new user account. Run the scan to assess the security vulnerabilities of the virtual machine with authenticated access.

![8](https://github.com/user-attachments/assets/e4b7cd24-26bf-4851-9b7a-fbc0f609bf58)

# Inspecting First scan with credentials results
Inspect the results of the scan with credentials. Compare them to the results of the first scan without credentials to identify any additional vulnerabilities that were discovered with authenticated access.

![9](https://github.com/user-attachments/assets/382da6cb-b574-4595-9922-43a90d03e667)

# Installing a deprecated Firefox on our VM
To simulate a real-world scenario, install a deprecated version of Firefox on the virtual machine. This will expose the system to known vulnerabilities that can be identified and remediated.

![10](https://github.com/user-attachments/assets/8c6e0034-b0b7-42a8-b8db-d668d584d1cc)

# Inspect scan results after installing deprecated Firefox
Run a new scan after installing the deprecated Firefox version. Inspect the scan results to identify any new vulnerabilities that were discovered.

![11](https://github.com/user-attachments/assets/2650d175-101d-47e9-bcbc-88c6029f4f39)

# Remediating some vulnerabilities
Identify the vulnerabilities that can be remediated, and take the necessary steps to fix them. For example, update software versions or apply security patches.

![12](https://github.com/user-attachments/assets/1d20aa52-0e61-43a4-bd65-90e3e7152a9e)
![13](https://github.com/user-attachments/assets/89a5be23-26ee-412a-b18c-f4cb466361c3)
![14](https://github.com/user-attachments/assets/91254208-8bb3-4dd3-803b-8af9ef8f5298)

# Inspect scan results after remediating some vulnerabilities
Run a new scan after remediating the identified vulnerabilities. Inspect the results to ensure that the remediation efforts were successful in mitigating the security vulnerabilities.

![15](https://github.com/user-attachments/assets/78c200ae-b5d4-48c8-8ac5-1016ecc70ecf)











