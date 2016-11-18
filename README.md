# Module 1: Security Fundamentals
This module is designed to introduce you to academic concepts in security. 
By the end of this module, you should be able to understand that security is fundamentally risk management. 
You will also have developed a vocabulary to talk about different kinds of security threats.

## Overview of Security:
- [ ] [Bruce Schneier: The security mirage (ted talk)](https://www.ted.com/talks/bruce_schneier?language=en)

## Introduction to Computer Security:

- [ ]  [Lecture 1: Introduction](https://www.cs.utexas.edu/~byoung/cs361/lecture1.pdf)
- [ ] [Lecture 2: Why Security is Hard](https://www.cs.utexas.edu/~byoung/cs361/lecture2.pdf)
- [ ] [Lecture 3: Security as Risk Management](https://www.cs.utexas.edu/~byoung/cs361/lecture3.pdf)
- [ ] [Lecture 4: Aspects of Security](https://www.cs.utexas.edu/~byoung/cs361/lecture4.pdf)

## Interesting Bonus Materials:
- [ ] [On Security Awareness Training (Bruce Schneier)](http://www.darkreading.com/risk/on-security-awareness-training/d/d-id/1139381?)
- [ ] [Keren Elazari: Hackers: the Internet's immune system](https://www.ted.com/playlists/10/who_are_the_hackers)

## Questions for discussion:
- In `The security mirage` Bruce Schneier talks about our implicit biases that distort our view of security. What are your biases?
- Which methods of managing risk apply most to your role at Redox? See lecture 3 for a list.  
- Of confidentiality, integrity, and availability, which is the most important at Redox? See lecture 4 for one possible answer. 

# Module 2: Web Application Security
We make a web app. There are very specific and immediate vulnerabilities each developer needs to understand well and defend against.

Move slowly through these and finish the hacksplaing exercises on your own terms. This is marathon - not a sprint!

## [OWASP Top 10](https://www.owasp.org/index.php/Top_10_2013-Top_10)
- [ ] [Injection](https://www.owasp.org/index.php/Top_10_2013-A1-Injection) 
  - [sql-injection](https://www.hacksplaining.com/exercises/sql-injection)
- [ ] [Broken Authentication and Session_Management](https://www.owasp.org/index.php/Top_10_2013-A2-Broken_Authentication_and_Session_Management) 
  - [session-fixation](https://www.hacksplaining.com/exercises/session-fixation)
  - [weak-session](https://www.hacksplaining.com/exercises/weak-session)
- [ ] [Cross-Site Scripting (XSS)](https://www.owasp.org/index.php/Top_10_2013-A3-Cross-Site_Scripting_(XSS)) 
  - [xss-stored](https://www.hacksplaining.com/exercises/xss-stored)
  - [xss-reflected](https://www.hacksplaining.com/exercises/xss-reflected)
  - [xss-dom](https://www.hacksplaining.com/exercises/xss-dom)
- [ ] [Insecure Direct Object References](https://www.owasp.org/index.php/Top_10_2013-A4-Insecure_Direct_Object_References) 
- [ ] [Security Misconfiguration](https://www.owasp.org/index.php/Top_10_2013-A5-Security_Misconfiguration) 
  - [unencrypted-communication](https://www.hacksplaining.com/exercises/unencrypted-communication)
  - [broken-access-control](https://www.hacksplaining.com/exercises/broken-access-control)
- [ ] [Sensitive Data Exposure](https://www.owasp.org/index.php/Top_10_2013-A6-Sensitive_Data_Exposure) 
  - [user-enumeration](https://www.hacksplaining.com/exercises/user-enumeration)
  - [information-leakage](https://www.hacksplaining.com/exercises/information-leakage)
  - [password-mismanagement](https://www.hacksplaining.com/exercises/password-mismanagement)
- [ ] [Missing Function Level Access Control](https://www.owasp.org/index.php/Top_10_2013-A7-Missing_Function_Level_Access_Control) 
  - [xss-stored](https://www.hacksplaining.com/exercises/xss-stored)
  - [privilege-escalation](https://www.hacksplaining.com/exercises/privilege-escalation)
  - [directory-traversal](https://www.hacksplaining.com/exercises/directory-traversal)
- [ ] [Cross-Site Request Forgery (CSRF)](https://www.owasp.org/index.php/Top_10_2013-A8-Cross-Site_Request_Forgery_(CSRF)) 
  - [csrf](https://www.hacksplaining.com/exercises/csrf)
- [ ] [Using Components with Known Vulnerabilities](https://www.owasp.org/index.php/Top_10_2013-A9-Using_Components_with_Known_Vulnerabilities) 
  - [xml-bombs](https://www.hacksplaining.com/exercises/xml-bombs)
  - [file-upload](https://www.hacksplaining.com/exercises/file-upload)
  - [xml-external-entities](https://www.hacksplaining.com/exercises/xml-external-entities)
  - [command-execution](https://www.hacksplaining.com/exercises/command-execution)
- [ ] [Unvalidated Redirects and Forwards](https://www.owasp.org/index.php/Top_10_2013-A10-Unvalidated_Redirects_and_Forwards) 
  - [click-jacking](https://www.hacksplaining.com/exercises/click-jacking)
  - [open-redirects](https://www.hacksplaining.com/exercises/open-redirects)


## Exercises
- [ ] Complete the free exercises at [hacksplaining](https://www.hacksplaining.com)
- [ ] Identify parts of the Redox application that mitigate each of the OWASP top 10

# Module 3: Cryptography
Redox is a highly networked application. All of that information needs to be secured in transport and at rest. Cryptography is what is lets us do that. 

## Public key cryptography
- [ ] [Introduction to Public-Key Cryptography (mozilla)](https://developer.mozilla.org/en-US/docs/Archive/Security/Introduction_to_Public-Key_Cryptography)
- [ ] [How PGP works](http://www.pgpi.org/doc/pgpintro/)

## Exercises
- [ ] [Set up Github with your PGP key](https://help.github.com/articles/signing-commits-using-gpg/)


# Module 4: Cloud Infrastructure Security
- [ ] [AWS Cloud Security Best Practices](https://d0.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf) 
- [ ] [AWS Security Best Practices Video](https://www.youtube.com/watch?v=rXPyGDWKHIo)
- [ ] [AWS Security Masterclass](https://www.youtube.com/watch?v=zU1x5SfKEzs)

# Final Project
The final project will be a presentation to the team on a recent security topic of interest to you.

Here are some resources for cutting edge topics: 
- [OWASP Youtube channel](https://www.youtube.com/channel/UCe8j61ABYDuPTdtjItD2veA)
- [Blackhat conference archives](https://www.blackhat.com/html/archives.html) 
- [Schneier on Security](https://www.schneier.com/) 
- [Seclists.org](http://seclists.org/oss-sec/)
- [National Vulnerability Database](https://nvd.nist.gov/home.cfm)
- [NodeJS security advisories](https://nodesecurity.io/advisories/)
