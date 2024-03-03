# Software-Security

**Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?**

Artemis Financial was an investment group attempting to move their service into a more internet friendly environment, but wanting to do so in a safe and secure manner.

**What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?**

Running dependency checks was probably the most valuable part of the assignment. Using modern tools to look for vulnerabilities can help prevent oversight. Imagine the discontent from the customer if they moved their service into a modern environment just to have it very quickly hacked and all of the data taken. Threat actors are always on the lookout for easily breached financial software.

**What part of the vulnerability assessment was challenging or helpful to you?**

I had much more difficulty getting the IDE to play nice than anything conceptual...I knew what I was trying to do, and what it was supposed to look like, but spent most of my time just messing with Eclipse to produce the desired result. That is mostly due to my inexperience with Eclipse.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

I added a checksum, a certificate (self-signed for the purposes of the assignment), and corrected vulnerabilities that came from the dependency check. I'd use the same tools in the future.

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

I just checked that everything worked; if it didn't, I kept working on it until it did. I retested after my changes and adjusted accordingly.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

I used the Eclipse IDE, the Java Keytool, and the Spring and Maven toolkits for this project. I am not a fan of Eclipse; I find it clunky and not very helpful, so I imagine I would use a different IDE, but the Java Keytool worked well and Spring is still widely used in Java development.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

This project touches so many aspects of software security that I would share the completed summary document.
