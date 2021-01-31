# Part 1 The URL Cruise Missile:

Which part of the URL can be manipulated by an attacker to exploit a vulnerable back-end database system?

-The parameters part of a URL is specifically formatted data that interacts with backend servers such as email and databases.  

Which part of the URL can be manipulated by an attacker to cause a vulnerable web server to dump the /etc/passwd file? Also, name the attack used to exploit this vulnerability?

-Within a URL, the path can be manipulated by an attacker to gain access to another vulnerable within the network.  An attack such as this is often referred to as Path or Directory Traversal.

Name three threat agents that can pose a risk to your organization.

-Threat agents are those that have the capability to carry out a threatened attack.  Examples of that include Nation States, ‘Hacktivists’, business competitors, fringe employees and non-specific target types like trojans, worms, and Ransomware.  


Injection attacks exploit which part of the CIA triad?

-SQL Injection attacks touch all parts of the CIA triad, but are usually introduced through a vulnerability within the Availability component.  A business may have too much available to their employees and clients, opening a potential path for attack.   Access to back end servers through a SQL injection on an outward facing server is often due to a lack of strict enforcement of what is available, and to whom.  

Which two mitigation methods can be used to thwart injection attacks?

-There are several ways to thwart injection attacks.  Two common ones to cybersecurity professionals would be to limit privileges and access to equipment and areas such as databases and firewalls, as well as using filtering and monitoring tools that sound the alarm of a dangerous or potential intrusion.  




# Part 2 Web Server Infrastructure

What stage is the most inner part of the web architecture where data such as, customer names, addresses, account numbers, and credit card info, is stored?

-Stage 5, or the database is where data such as customer names, account numbers and P.I.I. is stored.  


Which stage includes online forms, word processors, shopping carts, video and photo editing, spreadsheets, file scanning, file conversion, and email programs such as Gmail, Yahoo and AOL?

-Stage 4 or web application is where the software runs for the remote server where items are stored.

What stage is the component that stores files (e.g. HTML documents, images, CSS stylesheets, and JavaScript files) that's connected to the Internet and provides support for physical data interactions between other devices connected to the web?

-Stage 5 is typically the most inner part of the web architecture and is often where data is stored.  

What stage is where the end user interacts with the World Wide Web through the use of a web browser?

-Stage 1 is often where a client interacts with the web server.  This is often done using HTTP or FTP through a web browser or file transfer software. 


Which stage is designed to prevent unauthorized access to and from protected web server resources?

-Stage 2 or the firewall is the most common perimeter defense used to protect the web server or servers that may be sitting behind.  


# Server Side Attacks

In today’s globally connected cyber community, network and OS level attacks are well defended through the proper deployment of technical security controls such as, firewalls, IDS, Data Loss Prevention, EndPoint and security. However, web servers are accessible from anywhere on the web, making them vulnerable to attack.

What is the process called that cleans and scrubs user input in order to prevent it from exploiting security holes by proactively modifying user input.

-That process is called Input Sanitation.  That is typically through a server side web application that will modify user inputs to an acceptable format.


Name the process that tests user and application-supplied input. The process is designed to prevent malformed data from entering a data information system by verifying user input meets a specific set of criteria (i.e. a string that does not contain standalone single quotation marks).

-Input Validation is the process whereby data is verified to meet certain criteria in order to be used as an input.  This is common on password entries where it may require different symbols, letters, and numbers as an example.  


Secure SDLC is the process of ensuring security is built into web applications throughout the entire software development life cycle. Name three reasons why organization might fail at producing secure web applications.

-According to an article published by Veracode, the top three reasons that organizations may fail at producing secure web applications are a lack of policy enforcement, a lack of creating a culture of security, and a lack of expertise when addressing the buildout and ongoing service to these applications.  


How might an attacker exploit the robots.txt file on a web server?

-An attacker may exploit a robots.txt file by using malicious bots.  They could use bots that ignore the robots.txt file, as well as get access to sensitive information about the website infrastructure.  There are examples of these sensitive items being left or stored within robot.txt files.  Since the files are often available to the public, some administrators believe hiding information will only make it seem more valuable and therefore, more of a prize to hunt and capture.  



What steps can an organization take to obscure or obfuscate their contact information on domain registry web sites?

-To obscure or obfuscate contact information on a domain registry site often organizations will have to pay extra for the service.  


True or False: As a network defender, Client-Side validation is preferred over Server-Side validation because it's easier to defend against attacks.

-True. I believe client-side validation would be easier to manage and defend against in most applications.  The client-side is still outside of the firewall, and therefore a step removed from putting those ‘creepy robot arms’ inside our organization.  Although there are still client-side attacks, a strong culture of security in place would help thwart these attacks before they happen, and catch them through monitoring tools if they enter.  


# Web Application Firewalls
WAFs are designed to defend against different types of HTTP attacks and various query types such as SQLi and XSS.  WAFs are typically present on web sites that use strict transport security mechanisms such as online banking or e-commerce websites.

Which layer of the OSI model do WAFs operate at?

-Although it is usually the second component in a five-art system, Web Access Firewalls operate at Layer 7 of the OSI Model.  


A WAF helps protect web applications by filtering and monitoring what?

-Web Application Firewalls are put in place to defend against different types of HTTP attacks.  These attacks include cross-site scripting and SQL injections.  


True or False: A WAF based on the negative security model (Blacklisting) protects against known attacks, and a WAF based on the positive security model (Whitelisting) allows pre-approved traffic to pass.

-This is somewhat true.  A WAF with a positive security model does filter for, and allow known and trusted traffic to pass through.  However, a negative security model does protect against known attacks, it may also protect against unknown attacks in certain cases.  


# Authentication and Access Controls
Security enhancements designed to require users to present two or more pieces of evidence or credentials when logging into an account is called multi-factor authentication.

-True.  This is multi-factor authentication.  

Legislation and regulations such as The Payment Card Industry (PCI) Data Security Standard requires the use of MFAs for all network access to a Card Data Environment (CDE).
-On February 1, 2018, Requirement 8.3 of the Payment Card Industry Data Security Standard (PCI DSS 3.2) went into effect, making multi-factor authentication mandatory for non-console access to computers and systems handling cardholder data, and remote access to the cardholder data environment (CDE)

Security administrators should have a comprehensive understanding of the basic underlying principles of how MFA works.

-True


# Define all four factors of multifactor authentication and give examples of each:

Factor 1: KNOW This would be something like a password you enter.

Factor 2: HAVE An example of this is having another piece of technology like a cell phone that can receive a code. 

Factor 3: ARE These are the biometrics like a retina or fingerprint scan.  

Factor 4: LOCATION This is a proximity access that allows permission based on physical location.  A common example if this is being within range of a wifi signal and accepting the terms or conditions of its public use.  

True or False: A password and pin is an example of 2-factor authentication.

-True.  Even though they are both examples of something you know, if setup properly they could be used to authenticate access.


True or False: A password and google authenticator app is an example of 2-factor authentication.

-True


What is a constrained user interface?

-A constrained user interface describes an authentication method that uses only a single type of authentication credentials. A physically constrained user interface is a user interface that does not provide a physical means of entering unauthorized information.



# The OWASP WebGoat Challenge

The first part was to gain a password to enter the website.  By viewing the script within the site, I was able to scroll around and see the user and password. 


In the second challenge, I changed the user name into <’ or 1=1 > and rehashed that as a base64 in chef.  I followed the format used in the username: youaretheweakestlink that was in a Base64 format.  I then inserted my new TRUE statement, and was able to drop down the credit card info to reveal all user saved options.  



I added this to the value statement: <tcp && cd / && find . -iname webgoat_challenge_guest.jsp>



Once the direct path was discovered, I was able to edit the line and add an echo statement, then write that to the webgoat_challenge_guest.jsp file.  I overwrote what was in that file and posted this: “YOU, YOU BEEN HACKED JACK!”




Final Screen.
