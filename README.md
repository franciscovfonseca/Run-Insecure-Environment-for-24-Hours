<br>

<h1 align="center">Stage IV - Run Insecure Environment for 24 Hours</h1>

<br>

<p align="center">
<img width="900" src="https://github.com/user-attachments/assets/b542fab4-7205-44b5-828a-e8a7d53d20af" alt="Banner"/>

<br />

<br />

➡️ The following table shows the measurements taken from the insecure environment after the initial 24 hour observation period:

<br>

### Metrics - Before Securing Environment

<br>

Start Time: 1/18/2024 15:44

Stop Time: 1/19/2024 15:44

<br>

| Metric                   | Count
| ------------------------ | -----
| SecurityEvent (Windows VM)            | 29005
| Syslog (Linux VM)                   | 16562
| SecurityAlert (Microsoft Defender for Cloud)            | 4
| SecurityIncident (Sentinel Incidents)        | 204
| NSG Inbound Malicious Flows Allowed | 2837

<br>

<h2></h2>

<br>

### Attack Maps Before Hardening / Security Controls

<br>

Before taking the screenshots ➜ the Workbooks need to be edited to only show the **last 24 hours**.

💡 The query runs over the last 30 days by default.

<br>

>   <details close> 
>   
> **<summary> 📋 Steps to Edit the Maps:</summary>**
> 
> <br>
> 
> From inside the **Workbook** ➜ click on ✏️ **Edit** 
> 
> <br>
> 
> ![azure portal](https://github.com/user-attachments/assets/d42567b3-d717-466b-a98e-a7c98062dfa3)
> 
> <br>
> 
> Then go all the way down and to the right ➜ click the **↑ Edit** button
> 
> <br>
> 
> ![azure portal](https://github.com/user-attachments/assets/44ef059e-e7a7-48f4-b6de-1a6f63bb87ab)
> 
> <br>
> 
> Change the **Time Range** to ```Last 24 hours```
> 
> Then press the **Run Query** button
> 
> <br>
> 
> ![azure portal](https://github.com/user-attachments/assets/3324a8ce-166a-4222-a107-ae13758e41fd)
> 
> <br>
> 
> Finally ➜ click 📒**Done Editing**
> 
> <br>
> 
> ![azure portal](https://github.com/user-attachments/assets/d70ed30f-7bde-4e90-8e45-c4e5ea86a2d0)
> 
> <br>
> 
>   </details>

<br>

<h2></h2>

<br>

### NSG Allowed Malicious Inbound Flows:

<br>

![azure portal](https://github.com/user-attachments/assets/e892d644-b7ba-4f0a-b5b4-869a195a725c)

<br>

### Linux SSH Authentication Failures:

<br>

![azure portal](https://github.com/user-attachments/assets/04c1e583-c9b4-45d8-9ef1-cc91baf91b7f)

<br>

### Windows RDP/SMB Authentication Failures:

<br>

![azure portal](https://github.com/user-attachments/assets/10d0922f-149a-4280-b0e8-7c1d4c0be0fc)

<br>

### MS SQL Server Authentication Failures:

<br>

![azure portal](https://github.com/user-attachments/assets/337d5bb0-ae90-4dda-8666-6a75d5b24ae7)

<br>

  </details>

<h2></h2>

<br>

<br>

<br>

<br>

<br>

<br>

<br>
  
<br>
