# Reflection
Module Eight Journal
Portfolio Reflection – CS‑320 Software Test, Automation, and QA
How can I ensure that my code, program, or software is functional and secure?
I ensure functionality and security by combining requirement‑driven development with rigorous testing. For functionality, I write unit tests that cover both expected (“happy path”) and edge‑case scenarios, using techniques like boundary value analysis and equivalence partitioning. For security, I validate all inputs, avoid hardcoded secrets, use secure algorithms (e.g., SHA‑256 instead of MD5), and keep dependencies up to date through vulnerability scanning with tools like OWASP Dependency‑Check. I also follow secure coding guidelines from OWASP to prevent common issues such as injection flaws and insecure data handling.

How do I interpret user needs and incorporate them into a program?
I start by translating user requirements into clear, testable acceptance criteria. This means breaking down high‑level needs into specific behaviors the software must exhibit. For example, if a user needs “contacts with valid phone numbers,” I define that as “exactly 10 digits, numeric only” and write tests to enforce it. I also maintain open communication with stakeholders to clarify ambiguous requirements and adjust the design as needs evolve. This ensures the final product aligns with the user’s expectations and business goals.

How do I approach designing software?
I approach design with a modular, maintainable, and secure architecture in mind. I start by identifying the core entities and services, then define clear interfaces and responsibilities for each. I use object‑oriented principles like encapsulation and single responsibility to keep code organized and testable. Security is integrated from the start — for example, designing endpoints to run over HTTPS and validating all external inputs. I also plan for testing early, ensuring that each module can be independently verified through automated tests before integration.
