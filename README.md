# SNHU-CS305

### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a financial management company that works with customers to design spending and savings plans for savings, retirement, investments, and insurance. They are looking to modernize their operations by applying updated security protocols to protect the sensitive information of their customers.

### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
When I was addressing the vulnerabilities, it was apparent that outdated software was the biggest security threat to the code. Simply reinstalling dependencies with up-to-date versions cleared up most of the OWASP dependency check. It's important to code security to be a credible organization that customer's feel they can trust.

### Which part of the vulnerability assessment was challenging or helpful to you?
It was challenging at times to understand what exactly the problem was in a vulnerability assessment. Sometimes the vulnerability would be associated with a function of the dependency which was not being used, so we could suppress the issue as being a false positive. It was helpful to read through each vulnerability on its own to determine which ones were false positives.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
After each code refactoring the OWASP dependency check was run again to see what progress had been made in tightening security in our code. The whole vulnerability flowchart can also be revisted after making major changes in the software.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Cleaning and running the code and the dependency check after making changes is a good way to not let bugs or additional vulnerabilities creep into the code. If there are new problems, then the last version pushed to GitHub can be downloaded and smaller changes can be made until sources of the new problems are identified.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I have uploaded a vulnerability assessment report and a report on security protocols both relevant to Artemis Financial. I hope that a future employer can view these reports to see evidence of my aptitude to join a software development team which prioritizes software security.
