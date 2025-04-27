# SecurityRepo
Repository for CS305

# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting company that makes personalized financial plans for customers including savings, retirement, investments, and insurance. The company needed help finding and addressing vulnerabilities in its web-based RESTful API application. Artemis Financial’s main concern was ensuring the protection of sensitive customer information and enhancing its application with up-to-date, secure coding practices.

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I did a manual code review and used static analysis tools to find a variety of vulnerabilities, including missing input validation, hardcoded database credentials, and outdated libraries. Coding securely is important because it protects against data breaches, financial loss, and reputational damage. For a financial company like Artemis Financial, strong software security builds client trust, meets legal compliance, and protects sensitive financial data from attackers.

# Which part of the vulnerability assessment was challenging or helpful to you?
Manually reviewing the code was both challenging and helpful. It pushed me to carefully look at code logic, identify security flaws, and think like an attacker. This hands-on process helped me better understand how small mistakes in code can become vulnerabilities.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I recommended adding input validation, securing API endpoints with authentication, encrypting credentials, handling errors securely, and upgrading outdated libraries. In the future, I would continue to use tools like OWASP Dependency-Check and automated static analyzers. I would prioritize mitigation based on risk levels, CVSS scores, and the impact to sensitive data.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I made sure the application remained functional and secure by suggesting best practices that align with secure software development principles, like closing database connections properly and avoiding hardcoded sensitive information. After applying changes, I would perform testing and re-run dependency-check scans to make sure that no new vulnerabilities were introduced and the fixes actually worked.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used the OWASP Dependency-Check tool, reviewed CVE advisories, and followed secure coding practices like input validation, least privilege, and proper error handling.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show the full vulnerability assessment report to demonstrate my ability to perform manual code reviews, run static analysis tools, interpret security risks, and recommend detailed mitigation strategies. This shows both technical development skills and strong knowledge of secure coding and application hardening.
