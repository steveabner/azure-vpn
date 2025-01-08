![2025-01-08 12_45_13-Window](https://github.com/user-attachments/assets/ba36c4d0-597e-4464-8550-00e50dd651d6)<p align="center">
<img src="https://i.imgur.com/nBkHqaM.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />

<h1>How to Setup and Use a VPN in Azure</h1>

<h2>Description</h2>
<p>
For this project, I will utilize the Windows 10 Virtual Machine from my 
<a href="https://github.com/steveabner/Cloud-SOC">SOC / Honeynet in Azure</a> project to configure a VPN, with ProtonVPN as the chosen service.
</p>

Virtual Private Networks (VPNs) enable secure connections to a network through encrypted tunnels, enhancing privacy and security. Common uses for VPNs include enabling remote work for companies and accessing content that may otherwise be restricted or unavailable.  
<br/>

<h2>Environments and Utilities Used</h2>

- <b>ProtonVPN</b>
- <b>Microsoft Azure</b>

<h2>Project Walk-through:</h2>

- I'll navigate to https://whatismyipaddress.com, and record my current IP Address and location.

  ![2025-01-08 12_25_40-Window](https://github.com/user-attachments/assets/d428347e-9d0c-4b48-ad09-08ca1f7f5c53)
  ![2025-01-08 12_45_13-Window](https://github.com/user-attachments/assets/8750e29d-d5cc-4bcf-a0de-70beff994429)

- Next, I will remote into my Virtual Machine, revisit the same website, and record the IP address and location in my notes.

  ![2025-01-08 12_36_59-Window](https://github.com/user-attachments/assets/2d97a358-da5d-425b-b046-3e8c4e83a172)
  ![2025-01-08 12_48_28-Window](https://github.com/user-attachments/assets/30b4e033-4e25-4538-b62e-0a52c7506367)

- Next, I'll navigate to the ProtonVPN website, create a new account, and then download and install the software onto the Virtual Machine.

  ![2025-01-08 12_53_43-Window](https://github.com/user-attachments/assets/6653bb76-fba9-4da4-aa41-c420489e638a)

  - Once installed, I'll log in using my username and password.
  
  ![2025-01-08 12_56_28-Window](https://github.com/user-attachments/assets/4d962a4f-1ec8-407c-996f-46a873d79652)

- Once logged in, I'll click Quick Connect at the top-left.

  ![2025-01-08 13_02_11-Window](https://github.com/user-attachments/assets/8a224b10-8c46-4e0e-8bc1-2fc0f4707697)

- The VPN connected to a server in Romania.

  ![2025-01-08 13_11_40-Window](https://github.com/user-attachments/assets/12ca5cd2-36d3-43cb-bf5b-5d5bffd963a5)

- Within the VM, I'll revisit https://whatismyipaddress.com, and record the IP Address and location in my notes.
  
  ![2025-01-08 13_15_08-Window](https://github.com/user-attachments/assets/8e7e22fa-eb6c-4645-b3fa-faf631e5fa30)
  ![2025-01-08 13_17_00-Window](https://github.com/user-attachments/assets/db903350-4b30-4c1f-9e7e-b3aedbc0ffd3)

- Finally, I will visit websites like Amazon, Google, and Netflix to observe the interesting differences compared to my personal computer.

  ![2025-01-08 13_22_52-Window](https://github.com/user-attachments/assets/11875d65-7eed-4155-b231-130311614eec)

  ![2025-01-08 13_23_47-Window](https://github.com/user-attachments/assets/ab9ad3d9-554f-4ba5-a262-042d10485e03)

  ![2025-01-08 13_24_16-Window](https://github.com/user-attachments/assets/ed8bbb5f-34c8-42a6-8cfb-9075604a5c80)

  ![2025-01-08 13_30_18-Window](https://github.com/user-attachments/assets/5916e3ab-8658-4d6e-934c-3979a81f4dfe)

  
