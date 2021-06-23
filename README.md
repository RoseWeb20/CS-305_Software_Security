# CS-305_Software_Security
Repository for SNHU CS-305 Projects

#### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
>For this project, the client was Artemis Financial, an institution that focuses on developing individualized financial plans for their clients. The came to our group because they wanted to add a file validation step to their web application that would ensure the files being transmitted to and from the clients were unmodified. 

#### What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
>One area of identifying security vulnerabilities that I excelled at was running the dependency check and filtering out any false positives. It is important to code securely as this is the foundation for preventing attacks. When you believe in the value of coding securely, this creates the best surface on which to apply various levels of security to the application. By providing various layers of security the trustworthiness of the application is increased which thereby provides additonal value to the company's overall wellbeing. 

#### What about the process of working through the vulnerability assessment did you find challenging or helpful?
>For me, the most challenging aspect of working through the vulnerability assessment was determining whether the given vulnerability was a false positive or a real vulnerability. However, the information given in the report was helpful in determining these false positives. 

#### How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
>I approached the need for increased layers of security by first looking at the issues the client was wanting to address and found the best encryption algorithm to apply to it. I then applied a base level of protection through the SHA-256 encryption algorithm and providing a checksum verification to the file transfers. When I need to assess vulnerabilities and determine mitigation techniques in the future, I will follow a similar method of looking at the overall problem and then finding the specific solution that addresses that issue.

#### How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
>To ensure that the code and software application were functional and secure I first ran the code and dependency report before making any modifications. Then I made modifications one step at a time and ran the code again at each step to ensure that each piece was functional by itself. When I finished my modifications, I ran the dependency check report again to check whether or not any new vulnerabilities were present. 

#### What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
>In this project, I utilized the OWASP dependency check to check for vulnerabilities. This tool was very helpful in determining whether the changes I made effected the security of the application. 

#### Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
>From this assignment, I would want to showcase my process for looking at the application, making the appropriate choice for encryption algorithms,and applying these choices to the application. I believe this showcases my ability to think through the overall application and the how my choices will effect the application. 
