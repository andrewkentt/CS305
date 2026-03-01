# CS305
For this course, the client was Artemis Financial. They create financial plans that include things like retirement accounts, savings, and investments, so they handle a lot of sensitive customer information. The main goal of the project was to review their software for security vulnerabilities and improve it so their application would better protect customer data. Since this is financial information, even a small security issue could be a big deal.

One thing I think I did well was working through the dependency-check report and figuring out what actually applied to the application. At first it was overwhelming because there were so many findings, but I learned how to focus on the ones that were relevant. I also refactored the code to support secure communication and configured the application to use HTTPS. Coding securely is important because developers are responsible for protecting user data. If software isn’t secure, it can lead to data breaches, loss of trust, and serious financial consequences for a company.

The most challenging part for me was understanding how to interpret the vulnerability report and knowing what needed to be fixed versus what was less critical. It was helpful though because it made me realize how much modern applications depend on third-party libraries and how important it is to keep them updated.

To increase security, I updated vulnerable dependencies, generated a self-signed certificate, configured SSL, and verified that the application was running securely. In the future, I would continue using tools like OWASP Dependency-Check and automated testing to evaluate vulnerabilities. I would also look at severity levels and the actual impact on the system before deciding how to fix them.

After making changes, I rebuilt the project, tested the server to confirm it was running correctly over HTTPS, and reran the dependency report to make sure I didn’t introduce new issues. That helped me confirm the application was still functional while being more secure.

Some of the tools and resources I used were Maven, OWASP Dependency-Check, Spring Boot configuration files, and Java keytool. These are tools I can see myself using again in future projects because they reflect real-world security practices.

If I were showing this to a future employer, I would highlight the vulnerability assessment process and the secure refactoring work. It shows that I can analyze security risks, make improvements to existing code, and verify that an application is both working properly and secured
