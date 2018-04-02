# Accessibility for Project Managers

Presenters: Andrew Reynolds, Bryan Jonker  
Session Length: 55 minutes


---

## Presentation Goals

High level understanding of how PMs can incorporate accessibility into project timeline

---

## Not covered

* Specific project management methodologies
* Implementation details

(Join us monthly at Explore With Hadi)

Note: Who works at U of I, other state agency, or creates services for a state agency?

---

## What is the PM's role?

* Be aware of the state of the project at all times
* Minimize risk (legal, functional, reputational)
* Ensure smooth development process and handoff
* Be able to answer project questions with certainty

---

Your process will establish due diligence

---

## How do we meet those needs?

---

### Minimize surprises!

* Identify project requirements (functional, technical, regulatory)
* Tease out fuzzy requirements (implied functionality, poorly defined specs)

---

### Facilitate communication

* Communicate requirements to team and/or vendors
* Communicate progress to stakeholders

---

Project Manager is *not* responsible for implementation  
Understand impact and rules of thumb, not the gory details

---

## What does that have to do with accessibility?

---

## Treat accessibility as any other UI requirement

* Include known functional requirements in minimum viable product
* Follow established best practices during implementation
* Plan for iterative enhancement based on user feedback
* Reference external specifications (e.g., WCAG) and document any exceptions
* Watch for regression--app won't break, but UX will be poor

---

* Accessibility is a non-functional requirement, just like usability, performance, and security
* Accessibility is an inherent part of a product, not a single checkbox item
* Accessibility is easy to start doing, but difficult to add at the end of the project
* Accessibility is easy to undo

---

## Project Manager Knowledge Requirements

---

## Don't need to know everything

Lots of online guides, dev tools, and campus resources available.
Use them!

---

### Regulatory Requirements

Federal, state, and university legal and policy requirements

(This is WCAG 2.0 AA for university employees)

---

### Success criteria

Learn high level differences between WCAG 2.0 success criteria (A, AA, AAA)

* Implementation requirements
* Handoff and client responsibilities

---

### Applied Knowledge and Triggers

* Recognition
* Application
* Understanding

Note: three broad knowledge categories

---

Learn to recognize 11 requirements that should trigger accessibility check

---

**Always Required:**

* Keyboard operability
* Document structure
* Reading order
* Color & styles
* Magnification
* Aria

---

**Content-Specific Requirements:**

* Links & navigation
* Images
* Forms
* Tables
* Multimedia

---

Learn to apply WCAG POUR principles

* Perceivable
* Operable
* Understandable
* Robust

---

Understand accessibility/usability spectrum

* Disabilities can range from mild to severe
* Disabilities can be temporary
* Users with disabilities are not monolithic
* Users with disabilities may use your product in ways you hadn't considered
* Users with disabilities are regular people

---

## Diving in: Requirements Gathering

---

### U of I Regulatory Requirements

All electronic products produced or procured for the U of I subject to section 508

* Must be accessible to persons with disabilities
* Alternate arrangements must be made when content cannot be made accessible

---

### Section 508 Level AA Specification

* Section 508 as of January 2018
* Illinois Information Technology Accessibility Act as of July 18, 2017
* University of Illinois IT Accessibility policy as of Fall 2017
* University of Illinois OBFS for purchase of web services and technologies

---

### The good

Requirements better defined than they used to be

---

### The not so good

* Still hard to google a clear line item standard
* Lots of outdated advice
* Sometimes legal ambiguity
* One-size-fits-all is not feasible
* Best practices can be in conflict

---

### Legal Takeaways

Be prepared with sources!

---

### Functional Requirements

---

**What are you building?**

* Accessible output vs. accessible authoring tools for accessible output
* Ignore requirements for components you aren't using

---

**How much control do you have?**

(Third-party software may require changes)

---

**What has the customer asked for?**

(Some components, frameworks have known accessibility challenges)

---

### Aside: Stakeholder Requests

Accessibility is similar to other non-functional requirements like security.

---

Stakeholders often ask for accessibility but only in general terms.

Stakeholders will see the impact of poor implementation.

---

Be prepared to talk accessibility

* Regulatory stick
* Carrots
    * More robust, flexible product
    * Better SEO
    * Better usability
    * Better customer retention/market
* Back up your statements

---

### Functional Takeaways

Some specs and support defined by WCAG, language, tools

---

Line between accessibility and usability is fuzzy

* Accessibility/usability split makes a good threshold for minimum viable product
* Some accessibility fixes are simple and straightforward
* Some accessibility fixes are nuanced and require user testing

---

Big gap between meeting minimum functional requirements and meeting user expectations

* e.g., Don't map ctrl+c to close window.
* Assistive technologies have their own conventions
* Product can be accessible without being usable

Note: Matt King (Facebook) - "Functional accessibility"

---

No substitute for user testing

Users are not monolithic.  
Users have their own preferences, which may not be obvious to users without disabilities

---

### Requirements Wrapup

* Determine *all* of your requirements
* Determine how accessibility requirements map to functional requirements
* Document everything you've learned
* Make that documentation internally available to your team

---

## Facilitate inclusion of accessibility

Understand that accessibility breaks down when people start guessing

---

As a team, commit to accessibility as a requirement

* Enlist existing expertise and interest
* Appoint a liaison to accessibility experts if necessary
    * QA often a good choice

---

## Gotchas

* Watch out for bottlenecks on critical personnel
* Plan for a learning curve (e.g., screenreaders)
    * Identify external resources and communicate to team
    * Obtain/offer accessibility training where appropriate

---

## Share the knowledge

---

* Build a common understanding of accessibility inside your project team
* Make sure project standards are readily available
* Come prepared with resources

---

### Anticipate role-based concerns

* Designers likely to feel hobbled
* Developers likely to be unsure what they need to implement
* Content providers likely to be unaware that they have a role

---

## Get to know your project

Know your users. 
Understand who you're developing for.

---

### Spend more time in the design phase

* Play out use cases with user personas
* Identify project elements and associated requirements/challenges
* Identify sweet spot to begin implementing UI, which is especially sensitive to code stability

---

## Spend time on process

---

Identify intake and prioritization heuristics

* Regulatory requirements are not enhancements
* Understand "this inconveniences the user" vs. "this disenfranchises the user"

---

* Develop use cases and rich user personas, including users with disabilities
* Identify supported technologies
* Identify canonical guides

---

### Establish Processes to Minimize Risk

Accessibility is especially vulnerable to regression

* Include accessibility in an iterative fashion. Don't just test at the end of the lifecycle
* Automate accessibility testing when possible
* Follow your checklists

---

### Revisit your assumptions

Different user groups may have competing needs

* Get QA and your accessibility experts involved early!
* Get user feedback early!
* Discuss accessibility in project retrospective session(s) and check-ins

---

## Hold your vendors accountable

Use the Accessibility Requirements for Procured Software v1.7 document as a reference. 

---

Be prepared to work with vendors that aren't familiar with accessibility requirements. 

This may mean finding other vendors

---

* Check for Voluntary Product Accessibility Template (VPAT) from the vendor
* Determine the vendor's point of contact to handle accessibility issues
* Make sure accessibility requirements are communicated to the vendor

---

Make sure accessibility requirements are included in the contract

Include remediation clause ("if it doesn't meet X, then it will be added on an agreed-upon time")

---

## How do you know you're done

Just like any other requirement

---

### Homework == Success!

Because you've prioritized your requirements, you know what needs to be finished.

---

* Release because you've met the project's defined requirements
* Release because you've hit a hard deadline
* Release because you need feedback from the user

---

## How do you hand off the finished product

* Document the specs you met (refer to WCAG 2.0 guidelines)
* Document areas where enhancements or remediations are needed

---

### Prepare the customer

Changing content may invalidate site accessibility

Note: Refer to WCAG 2.0

---

## Consider creating a VPAT

Especially useful if working with other higher ed institutions

Note: _product_ accessibility template. Discuss vpat structure.

---

## Wrap up

Session Resources: https://go.illinois.edu/a11y-workflow
