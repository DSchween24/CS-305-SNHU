# CS-305-SNHU
Software Security

# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

  Artemis Financial develops individualized financial plans for its customers. These financial plans may include savings, retirement, investments, and insurance. Considering these financial plans, Artemis Financial will be collecting a lot of sensitive information from their clients. Artemis Financial wants to update their API to industry standard best practices, They want to provide their clients with a secure server and utilize modern security practices to protect their data.
  
# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

  I believe I identified the main vulnerablities in the risk assessment report well. The main vulnerabilities conistsed of cryptographic issues, input validation, resource boundaires, database protection, and most importantly, out-of-date software. It is important to code securely because malware and brute-force attacks depend on back-door entry and developer oversights. When trying to cover all aspects of security, it is easy to overlook a single character in an input that may grant unautherized access, for example. That is why risk assessment reports are very important. Software security can define a company's reputation. A company with a proven, robust and modern security will attract more business.

# Which part of the vulnerability assessment was challenging or helpful to you?

  The most helpful part of the vulnerability assessment was identifying the importance of updated software, libraries, and plug-ins. It is easy to take these services for granted to do the job for us, but they will not work unless they are compatible with one another and up-to-date to perform the task specified. 

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

  I increased layers of security by ensuring all software and packages are updated and able to communicate with one another. Additionallly, a refactored code will ensure input validation and cryptoraphy are addressed. A Maven Dependency check report is a good start to identify vulnerabilities, but third-party services are also an option to implement these corrections. 

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  After reviewing the risk assessment, creating a supression file, and refacting code, a new assessment report can be generated to identify any new or contuining vulnerabilities. Through repeated testing we can narrow down the security risks to little or none. Also, ensuring the console runs with a connection and no errors tells us the API was functional and secure. A POM.xml file, a certificate and hash value with a secure connection also tells us our encryption was sucessful as well. 

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

  I used packages and libraries to help suport the code. I used Maven for risk assessment. Additionally, I kept in mind practices such as access control, data encryption, updated software, multi-factor authentication, risk assessment, and database maintenance during this assignment.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

  I would demonstrate my knowledge and understandment by interpreting the risk assessment report and how to implement resolutions. I would go a step further and create a supression file to filter out any unecessary vulnerbillity checks. I would then refacor the initial code and update software to address the vulnerability checks. Finally, I would run another report to show the changes made were successful. 
 
