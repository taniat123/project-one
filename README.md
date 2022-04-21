# project-one
Interview
CYBER PROJECT QUESTION 1

1.
The firewall is supposed to block SSH connections but it’s letting them through 

2
- [ ] Yes 
- [ ] All of the virtual machines 
- [ ] It couldn’t establish a connection because the firewall is blocking the connection 
3.
- [ ] Firewall issue 
- [ ] The network security group 
- [ ] Try to SSH into the machine 

4
- [ ] We would go to the networking tab under the settings of the virtual machine that were reconfiguring 
- [ ] The inbound firewall rules
- [ ] we would look for inbound SSH connections or allow all inbound connections from any IP address
- [ ] You try SSH into the machine and verify you cannot connect to it 

5.
- [ ] No it doesn’t guarantee to all unauthorized access
- [ ] Turn on authorization login into the machine 

Question 2: unsecured web server 

1. - [ ] The problem is theirs a sever running HTTP on port 80 requiring encryption and motion 

2.a - [ ] Yes we were simulating vulnerable machines. 
   b. I would re-configure the web servers to run on port 443 (HTTP) to encrypt all web traffic in motion. 

3. Running HTTP on port 80 is a problem because you can see all traffic in plain text
3.b I would generate signed certificates signed by a certificate authority and run the web server on port 443 (HTTPS)
3.c An attacker cannot see information in the clear such as credit card info, password or other PII

4a. I would use OpenSSL to generate keys and a certificate authority to sign my certificates
4.b I would use these tools to ensure all traffic to and from my web servers are encrypted and trusted. I would need to make sure the web server certificates are kept up to date to ensure integrity and confidentiality.
5.a The solution will have minimal impact on clients who already connect to the service. I would setup a redirect to use port 443 if port 80 requested
5.b I will have to make sure the traffic to my web servers are properly load balanced and that the certificates do not expire.


Exploring Kibana
225
60 
zero 
Zero 

gz: .gz files are compressed files created using the gzip compression utility.


css: .css files can help define font, size, color, spacing, border and location of HTML information on a webpage. They are downloaded with their .html counterparts and rendered by the browser.


zip: A lossless compression format. A .zip file may contain one or more files or directories that have been compressed.


deb: A file with the .deb file extension is a Debian (Linux) Software Package file. These files are installed when using the apt package manager.


rpm: .rpm file formats are a Red Hat Software Package file. RPM stands for Red Hat Package Manager.
March 5 2002
Nothing seems strange about the high traffic since it isn't much higher than other users.
February 28 @ 6 am to march 6 2022 at midnight
A deb file
Russia
200 OK



35.125.203.87




{
  "lat": 32.41132,
  "lon": -99.68189722
}
Windows 8 
Url 


https://artifacts.elastic.co/downloads/beats/metricbeat/metricbeat-6.3.2-amd64.deb







http://www.elastic-elastic-elastic.com/success/james-pawelczyk




6.
-The user was downloading a Linux deb package
-The file was not malicious. The file is an installer for metric beat for Linux
-Nothing suspicious about the activity
-The traffic seems to be within compliance guidelines. Metric beat can be download from the elastic website so the traffic makes sense
| Name       | Publicly Accessible | Allowed IP Address     |
|------------|---------------------|------------------------|
| Jump Box   | Yes                 | 10.0.0.4, 47.41.28.251 |
| Elk Server | Yes                 | 47.41.28.251           |
| Web1       | Yes                 | 47.41.28.251           |
| Web2       | Yes                 | 47.41.28.251           |








