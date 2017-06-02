# Accessibility for Project Managers

Session Length: 40 minutes

---

## Intro

* Introduce presenters
* Presentation goals:
    * High level understanding of how PMs can incorporate accessibility into project timeline
* Not covered:
    * Specific project management methodologies

---

## Role of PM

* Be aware of the state of the project at all times
* Minimize risk (legal, functional, reputation)
* Ensure smooth process
* Be able to answer questions with a high degree of certainty

---

## How to do that?

* Minimize surprises!
    * Identify project requirements (legal, functional)
    * Tease out fuzzy requirements (implied functionality, poorly defined specs)
* Facilitate communication
    * Communicate requirements to team and/or vendors
    * Communicate progress to stakeholders
* PM is *not* responsible for implementation
    * PM should understand rules of thumb

---

## How should PMs approach accessibility?

* Treat accessibility requirements as any other UI requirement
    * Functional requirements must be included in minimum viable product
    * Non-functional requirements will need testing and iteration--app won't break, but user experience will be poor
* Can reference WCAG or external document and list exceptions
* Your process will establish due diligence
* Make sure you don't mix up "this will inconvenience the user" and "this disenfranchises the user"

---

## Project Manager Knowledge Requirements

* Don't need to know everything
    * lots of campus resources

---

## Knowledge Requirements (contd)

* Learn legal requirements
* Learn high level WCAG 2.0 success criteria (a, aa, aaa)
    * aa generally a safe, achievable choice
    * aaa good goal, but may be impossible to achieve on all pages
    * User content can fail a formerly accessible site

---

## Knowledge Requirements (contd)

* Learn to recognize 11 requirements, which should trigger accessibility check
    * (Images, keyboard operability, forms, document structure, magnification, reading order, links & navigation, multimedia, tables, color & styles, aria)
* Learn to apply POUR principles (Perceivable, Operable, Understandable, and Robust)
* Understand accessibility/usability spectrum
    * Disabilities can range from mild to severe
    * Disabilities can be temporary
    * Users with disabilities are not monolithic
    * Users with disabilities are regular people

---

## Diving in: Requirements Gathering

---

### Summary

* Accessibility is an inherent part of a product, just like usability, performance, and other "-ilities".
* Accessibility is not a single checkbox item
* Accessibility is easy to start doing, but difficult to add at the end of the project
* Accessibility is easy to undo
* Must consider accessibility from the beginning and continue throughout the process

---

### Legal Requirements

* All electronic products produced or procured for the U of I subject to section 508.
    * Must be accessible to persons with disabilities
    * Alternate arrangements must be made when content cannot be made accessible

---

### Campus Legal Requirements

* Practically speaking, university products should be written to WCAG 2.0 AA

---

### Campus Legal (contd)

* Section 508 will mandate WCAG 2.0 Level AA as of January, 2018
* IT Accessibility policy will require WCAG 2.0 Level AA for web technologies as of Fall 2017
* OBFS requires WCAG 2.0 Level AA for purchase of web services and technologies
* Illinois Information Technology Accessibility Act will likely be refreshed to mandate WCAG 2.0 Level AA as well

---

### Legal Takeaways

* Requirements better defined than they used to be
* Still hard to google a clear line item standard
* Devil is in the details
    * Lots of outdated advice
    * Sometimes legal ambiguity
    * One-size-fits-all is not feasible
    * Best practices can be in conflict

---

### Functional Requirements

* What are you building?
    * Accessible output vs. accessible authoring tools for accessible output
    * Ignore requirements for components you aren't using
* What has the customer asked for?
    * Some components, frameworks have known accessibility challenges
* How much control do you have?
    * Third-party software may require changes

---

### Aside: Stakeholder Requests

* Stakeholders often don't think about accessibility.
    * Stakeholders see the impact of poor implementation
    * This is much like other non-functional requirements, like security and logging
* Because of this, you may need to remind stakeholders of these requirements.
* Including accessibility means you have a better product
    * Better SEO
    * better usability
    * better customer retention/market
* Be prepared to back up your statements

---

### Functional Takeaways

* Some specs and support defined by language, wcag, tools
* Big gap between meeting minimum functional requirements and meeting user expectations
    * e.g., Don't map ctrl+c to close window.
    * Assistive technologies have their own conventions
* At some point, accessibility becomes usability
    * "Functional accessibility" concept
    * Accessibility/usability split makes a good threshold for minimum viable product
* Users are not monolithic--no substitute for user testing
    * Users have their own preferences, which may not be obvious to users without disabilities

---

### Requirements Wrapup

* Document your requirements
* Determine how accessibility requirements map to functional requirements
* Make that documentation internally available to your team

---

## Facilitate inclusion of accessibility

* As a team, commit to accessibility as a requirement
* Understand that accessibility breaks down when people start guessing
* Identify existing expertise and interest
* Appoint a liaison to accessibility experts if necessary
    * QA often a good choice

---

## Gotchas

* Watch out for bottlenecks on critical personnel
* Plan for a learning curve (e.g., screenreaders)
    * Identify external resources and communicate to team
    * Obtain/offer accessibility training where appropriate

---

## Share knowledge

* Come prepared with resources
* Anticipate role-based concerns
    * Designers likely to feel hobbled
    * Developers likely to be unsure what they need to implement
    * Content providers likely to be unaware that they have a role
* Spread the knowledge of accessibility across as many team members as possible -- this will prevent bottlenecks
    * Build a common understanding of accessibility inside your project team
    * Make sure project standards are readily available

---

## Get to know your project

* Know your users. Understand who you're developing for.
* Spend more time in the design phase
    * Play out use cases and user personas (and personas of users with disabilities)
    * Identify project elements and associated requirements/challenges
    * Identify sweet spot to begin implementing UI, which is especially sensitive to accessibility issues
* Spend time on process
    * Identify intake and prioritization heuristics--regulatory requirements are not enhancements
    * Develop use cases and personas
    * Identify supported technologies
    * Identify canonical guides
    * Revisit your assumptions
* Allow time to learn the tools!

---

## Establish Processes to Minimize Risk

* Accessibility is especially vulnerable to regression
* Different user groups will have competing needs
* Accessibility is best included in an iterative fashion. Don't just test at the end of the lifecycle
* Work with team members to automate accessibility testing when possible
* Get QA and your accessibility experts involved early!
* Get user feedback early!
* Follow your checklists
* Discuss accessibility in project retrospective session(s) and check-ins

---

## Hold your vendors accountable

* Use the Accessibility Requirements for Procured Software v1.7 document as a reference. 
* Be prepared to work with vendors that aren't familiar with accessibility requirements. 
    * This may mean finding other vendors
* Make sure accessibility requirements are communicated to the vendor
* Make sure accessibility requirements are included in the contract
    * Need to include remediation clause ("if it doesn't meet X, then it will be added on an agreed-upon time")
* Check for Voluntary Product Accessibility Template (VPAT) from the vendor
* Determine the vendor's point of contact to handle accessibility issues

---

## How do you know you're done

* Accessibility is treated like any other requirement
    * Release because you've met the project's defined requirements
    * Release because you've hit a hard deadline
    * Release because you need feedback from the user
* Because you've prioritized your requirements, you know what needs to be completed to release a product

---

## How do you hand off the finished product

* Be aware that accessibility technology changes quickly. When handing off to a product team, be aware that they will need to update the product to meet these changes. 
* Changing content may invalidate site accessibility 
* Document where future enhancements are needed. 

---

## Wrap up

*campus resources here*