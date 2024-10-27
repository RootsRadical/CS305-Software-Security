# CS305-Software-Security
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting company that develops individualized financial plans for its customers. The financial plans include savings, retirement, investments, and insurance. They have a web application that their clients can use to track their portfolios. Artemis Financial wanted me and the team to create a more secure web application utilizing updated security practices to ensure client and company protection.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I believe that I was able to run the dependency checks well and evaluate what potential threats have already been addressed in other applications. It is important to code securely because it gives the application a fighting chance against threat actors. Using updated security practices gives your application and customers the assurance that you are taking their information seriously. 

Which part of the vulnerability assessment was challenging or helpful to you?
the most challenging part I had was connecting the application to the server once I generated a certificate. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased security by adding in SHA-256 encryption. I also made the sure the application was HTTPS and not HTTP as it was originally.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After refactoring the code, I would rerun the dependency check and match that against the original one that was ran. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
OWASP top 10 is a great resource for software security to see what are the biggest vulnerabilities. 
