<h5>Directory</h5> 

<b>[Tech Portfolio Home](https://github.com/Jays1115/Jalen-Smith.git)</b> /
<b>[AWS Projects](https://github.com/Jays1115/AWS-Projects.git)</b>

# Cost Estimation

<h2>Description</h2>
Scenario: Setting up a surf shop in the cloud. The user is considering AWS to host their online store and is particularly interested in managing costs effectively. They are contemplating reducing server usage during off-peak hours to save money and want to create a cost estimate for their cloud architecture to ensure cost-efficiency.
<br/> <br/>
Solution: Solution: To streamline permission management for the city stock exchange's new Support Engineering team, I created an IAM group specifically for support engineers and attached a managed EC2 read-only access policy to this group. Then, create IAM users for the team members and assign them to this group to ensure they all have uniform access rights to Amazon EC2, as well as access to the AWS Management Console and necessary development tools.

<h2>Program walk-through:</h2>

<p align="center">
Navigated to https://calculator.aws/#/ to create an estimate: <br/>
<img src="images/Screenshot 2024-09-28 at 11.20.43 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<p align="center">
I created an estimate, then accessed "My Estimates," and finally, I created a called "Web Servers": <br/>
<img src="images/Screenshot 2024-09-28 at 11.23.22 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-28 at 11.23.39 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-28 at 11.24.27 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<h3 align="center">Creating an Estimate</h3>

<p align="center">Inside the "Web Servers" group, I selected "Add a Service" and began to configure an EC2 instance according to the client's requirements to generate an accurate cost estimate: 
<br/>
<img src="images/Screenshot 2024-09-28 at 11.26.28 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-28 at 11.27.22 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<p align="center">
EC2 Configurations: <br/>
- Operating System: Linux <br/>
- Traffic Workload: Daily spikes <br/>
- Workload Days: Sunday to Saturday <br/>
- Baseline Instances: 2 <br/>
- Peak Instances: 4 during peak hours <br/>
- Duration of Peak Hours: 8 hours <br/>
- Instance Type: t2.medium <br/>
- Pricing Model: On-demand <br/>
<img src="images/Screenshot 2024-09-28 at 11.28.19 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-28 at 11.28.59 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-28 at 11.30.51 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-28 at 11.31.09 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<p align="center">Amazon EBS configured with a General Purpose SSD attached to the EC2 instance: 
<br/>
<img src="images/Screenshot 2024-09-28 at 11.32.55 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-28 at 11.38.38 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<p align="center">
Data transfer configurations: <br/>
- Inbound data transfer: 1 TB over the internet <br/>
- Outbound data transfer: 100 GB over the internet <br/>
<img src="images/Screenshot 2024-09-28 at 11.39.34 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-28 at 11.40.24 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<p align="center">
Completed the EC2 configuration and reviewed the cost estimate:
<br />
<img src="images/Screenshot 2024-09-28 at 11.41.44 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<p align="center">
Copied the link to this estimate to share with the client:
<br/>
<img src="images/Screenshot 2024-09-28 at 11.42.09 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>


