# CS-305-portfolioi-entry
My portfolio entry for CS-305 Software Security

<b>-Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?</b>

Artemis Financial is a financial consulting company. They provide individualized financial plans for their customers. This can include plans for savings, retirement, investments, and insurance. Our company, Global Rain, Was tasked with ensuring that their web interface functioned in such a way that protected its client data and financial information. The specific requirements are to add a file verification step to its web app to ensure secure communicatijons. This was accomplished using a checksum.

<b>-What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?</b>

What I think we did well was our thorough, multi-level testing. This allowed us to spot vulnerabilities whether it was simple data validation vulnerabilities to dependency vulnerabilities. Our code was high quality and adhered to industry best practices, and this ensured a reduction in vulnerabilities. And once vulnerabilities were spotted, a plan was promptly put in place to address them. It's very important to code securely. Even if the app is flawlessly functional, it can be rendered unusable if there are security vulnerabilities. If users and customers don't trust the software, it doesn't matter how well it functions, they won't want to use it. Ensuring that the app and its data are safe, the company builds a foundation of trust with their clients, ensuring that all parties are happy.

<b>-Which part of the vulnerability assessment was challenging or helpful to you?</b>

I thought the Maven dependency check was particularly helpful. It did a lot of heavy lifting in the vulnerability assessment. It's an open source solution and well trusted in the industry, and most importantly, it does a wonderful job of not only identifying vulnerabilites, but lends guidance toward resolving them as well.

<b>-How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?</b>

I followed the vulnerability assessment process flow diagram to help keep me on track, ensuring that I was using multiple layers of security to address vulnerabilities. I went down the line starting with input validation, looking for areas where this was lacking and ensuring that new code included it. Then I addressed the APIs. This is where the Maven dependency check came in very handy. I ensured that encryption was used to protect sensitive data. I ensured secure communication between the client and sever. I made sure the code was using proper error handling to avoid any information leaks, as well as meeting industry best practices to ensure quality code that was both functaional and secure. Lastly, I used encapsulation by limiting the scope of functions to only the necessary parts of the application. Together, these layers provided a safe and secure app.

<b>-How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?</b>

I used industry standard best practices when writing the code to ensure easy-to-read and maintainable code. I used the aforementioned layers of security. I tested each layer before and after the code refactoring to identify any newly added vulnerabilites.

<b>-What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?</b>

I saved a copy of the vulnerability assessment process flow diagram that I'll use for guidance during future development projects. I'll also make a habit of using the Maven dependency check plugin. For the code, I intend to use best practices, ensuring that data validation is in place for any use input, proper error handling, and encapsulation to keep the scope limited to only what is necessary.

<b>-Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?</b>

I'd like to show employers the techniqes used for ensuring a safe and secure web application. I'd like to show them the report on this assignment as a step by step overview of how Artemis Financial's requrements were met.
