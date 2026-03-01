# CS-305-Artemis-Financial-
Artemis Financial Practices for Secure Software Report
Artemis Financial is a company that builds financial software. Their main concern was whether their code had vulnerabilities that could be exploited. My main job was to go through their software, identify any weak points, and make it more secure. I did this by adhering to sound and secure coding practices.

I was able to get everything working and suppress the CVEs that were flagged in the dependency scan. I tested the software thoroughly after each change to make sure I did not break anything while going through it all and improving security. Secure coding matters much so because vulnerabilities can lead to real problems such as  loss of data, trust, or money. Fixing these issues protects both the company and its users.

The most challenging part was working through the dependencies and deciding which issues needed action versus which could be safely suppressed. Layering security and double-checking changes was key. For future work, I’d continue using tools like OWASP Dependency-Check and proper testing strategies to validate changes before deployment.

After refactoring, I ran tests to ensure the application still worked and didn’t introduce new problems. The main tools I used were Maven, Spring Boot, and dependency scanning utilities, along with structured testing. This assignment gave me great insight into how things run in the real world. Also I was able to perform through secure code and an assessment report, that demonstrates I can analyze software, handle vulnerabilities, and maintain functionality.
