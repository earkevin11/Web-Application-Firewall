# Web-Application-Firewall

# What is an Web Application Firewall?
- A cloud-native web application firewall (WAF) service that protects web apps from common web-hacking techniques such as SQL injection and security vulnerabilities such as cross-site scripting. 
- Admins can deploy the service in minutes to get complete visibility into your environment and block malicious attacks.
- A WAF solution can react to a security threat faster by centrally patching a known vulnerability, instead of securing each individual web application.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/224525088-8363ad79-62fd-401e-bcc8-392692b39030.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>





# Support Service
- WAF can be deployed with Azure Application Gateway, Azure Front Door, and Azure Content Delivery Network (CDN) service from Microsoft



# WAF vs Network Firewall
- WAF and Network Firewall server DIFFERENT purposes and protect different network types.
- A WAF protects web applications by targeting Hypertext Transfer Protocol (HTTP) traffic. This differs from a standard firewall, which provides a barrier between external and internal network traffic.
- Network firewalls and web application firewalls are complementary and can work together.
- RECOMMENDED TO USE BOTH
  
<p align="center">
  
<img src="https://github.com/earkevin11/Web-Application-Firewall/assets/104326475/cc7a5e6d-38c4-4446-8451-65c9beacab24" height="50%" width="50%" alt="Azure LAW"/>

<p/>

# WAF Visual

<p align="center">
  
<img src="https://github.com/earkevin11/Web-Application-Firewall/assets/104326475/8f3bdd5e-4219-45ea-bc79-059875b16df4" height="75%" width="75%" alt="Azure LAW"/>

<p/>


# WAF Visual #2
- WAF is located directly between the user and the web server
<p align="center">
  
<img src="https://github.com/earkevin11/Web-Application-Firewall/assets/104326475/d5b3576f-ee72-485f-88e8-2478e93f48e9" height="75%" width="75%" alt="Azure LAW"/>

<p/>




# What does a WAF protect? 
- The WAF protects websites and APIs. It is configured as a reverse proxy and examines all HTTP(s) requests/traffic before they reach the web/application server.
- WAFs can be considered as reverse proxies i.e. the opposite of a proxy server. Proxy servers protect devices from malicious applications, while WAFs protect web applications from malicious endpoints.
- It blocks or tests irregular traffic with CAPTCHA tests to make sure the traffic is coming from a human and not a bot.

# What Are Some Web Application Firewall Benefits? 
- A web application firewall (WAF) prevents attacks that try to take advantage of the vulnerabilities in web-based applications.
- Vulnerabilities are common in legacy applications or applications with poor coding or designs. WAFs handle the code deficiencies with custom rules or policies.
- Location: WAF sits between external users and web applications to analyze all HTTP communication.
- WAFs secure business-critical web applications and web servers from zero-day threats and other application-layer attacks.
  
# What layer does the WAF operate on?
- Focuses on Layer 7 (Application Layer) and protects attacks at Layer 7, which is the application level of the OSI Model.
- WAFs defend against
- 1. SQL Injection attacks
- 2. Cross-site-scripting (XSS)
- 3. Cross-site forgery
- 4. DDoS attacks at the website level
- 5. Directory traversal
 
Ex: For example, a Layer 7 DDoS attack sends a flood of traffic to the server layer where web pages are generated and delivered in response to HTTP requests. A WAF mitigates this by acting as a reverse proxy that protects the targeted server from malicious traffic and filters requests to identify the use of DDoS tools. 

# Network Firewall

# Network Firewall Architecture
- Network Firewall is located on the edge of the network
- Traditional network firewalls mitigate or prevent unauthorized access to private networks.
- Firewall policies define the traffic allowed onto the network, and any other access attempts are blocked.
- Examples of network traffic this helps to prevent are unauthorized users and attacks from users or devices in less secure zones.

<p align="center">
  
<img src="https://www.okta.com/sites/default/files/media/image/2021-04/How-Firewalls-Work.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>

# Network Firewall Architecture 2

<p align="center">
  
<img src="https://github.com/earkevin11/Web-Application-Firewall/assets/104326475/c9e34ade-78d5-4dbe-881f-9bb5fd9e70af" height="75%" width="75%" alt="Azure LAW"/>

<p/>







# What does a Network Firewall protect? 
- It secures local-area network from unauthorized access to prevent the risk of attacks.
- Location: Network Firewall is located on the edge of the network while the WAF is located directly between the user and the web server.
- Primary objective of a NF is to protect the network perimeter and filter traffic using protocol information.
# What layer does the Network Firewall focuses on in the OSI model?
- Layer 3 & 4 (network and transport) layer
- Network Firewalls defend against:
- 1. Unauthorized network access
- 2. Man in the Middle Attacks
- 3. Privilege Escalations 
- 4. DDoS attacks at the network level


# OSI Model

<p align="center">
  
<img src="https://github.com/earkevin11/Web-Application-Firewall/assets/104326475/d1b19102-b9e3-4f35-92d8-949f7cd9acab" height="75%" width="75%" alt="Azure LAW"/>

<p/>

