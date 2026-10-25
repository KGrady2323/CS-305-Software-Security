CS 305 Software Security Portfolio

Artemis Financial – Secure Software Development

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial was a financial services company that wanted to improve the security of its software application. The company needed to protect sensitive financial information and make sure its application could communicate securely. My responsibility was to identify potential security vulnerabilities and make improvements to help protect the application from possible threats.

2. What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely?

I think I did well identifying vulnerabilities in the existing code and using the OWASP Dependency-Check tool to find security issues in the application's dependencies. I also reviewed the code for weaknesses such as improper input validation and insecure handling of information. Secure coding is important because it helps prevent data breaches, protects customer information, and builds trust between a company and its customers. For a financial company, security is especially important because of the sensitive information being handled.

3. Which part of the vulnerability assessment was challenging or helpful to you?

One of the more challenging parts was getting the Maven Dependency-Check tool to run correctly. I ran into configuration issues and had to troubleshoot errors before generating the report. Once I got it working, I found it helpful because it showed how many vulnerabilities could exist in third-party dependencies. It also helped me understand how developers can use automated tools to identify security problems they might otherwise overlook.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

For Project Two, I improved security by implementing SHA-256 hashing and configuring HTTPS using a self-signed SSL certificate. I created a PKCS12 keystore and configured the application to use port 8443 for secure communication. These changes helped demonstrate how encryption and hashing can improve application security. In the future, I would continue using OWASP Dependency-Check, code reviews, and security testing to identify vulnerabilities. I would also prioritize fixes based on their severity and the potential risks to the application.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After making changes, I tested the application to make sure it still ran correctly. I successfully started the Spring Boot application using HTTPS and tested the /hash endpoint, which returned an HTTP 200 response and the expected SHA-256 checksum. I also ran another OWASP Dependency-Check scan after the changes. The scan completed successfully, although it still identified vulnerabilities in some dependencies. This showed me that testing functionality and checking for security vulnerabilities are both important parts of software development.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Some of the most useful tools I worked with were Eclipse, Maven, OWASP Dependency-Check, Java's MessageDigest class, and Java keytool. I also gained experience working with SSL certificates and configuring HTTPS connections. These tools helped me understand how to test applications and improve their security. I plan to use these skills in future programming assignments and eventually in a software development career.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show employers my Artemis Financial Practices for Secure Software Report because it demonstrates my ability to identify security concerns, modify Java code, and test an application after making improvements. I could also explain how I implemented SHA-256 hashing, configured HTTPS, and used OWASP Dependency-Check to scan for vulnerabilities. This project demonstrates my troubleshooting skills and my understanding of why security needs to be considered throughout the software development process.
