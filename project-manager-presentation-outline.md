# Project Manager Presentation

Available Time: 40 minutes

## Intro
    * Introduce presenters
    * Presentation goals:
        * High level understanding of how PMs can incorporate accessibility into project timeline
    * Not covered:
        * Specific project management methodologies

## Role of PM

* Be aware of the state of the project at all times
* Minimize risk (legal, functional, reputation)
* Ensure smooth process
* Be able to answer questions with a high degree of certainty

## How to do that?

* Minimize surprises!
    * Identify project requirements (legal, functional)
    * Tease out fuzzy requirements (implied functionality, poorly defined specs)
* Communicate requirements to team
* Communicate progress to stakeholders
* PM is *not* responsible for implementation
    * PM should understand rules of thumb

## How does accessibility impact a PM's role? *FIXME: kitchen sink slide*

* Accessibility is an inherent part of a product, just like usability, performance, and other "-ilities".
* Accessibility is not a single checkbox item
* Accessibility is easy to start doing, but difficult to add at the end of the project
* Accessibility is easy to undo
* Consider accessibility from the beginning and throughout the process
* Two main sections: Impact on project manager and impact on project implementers

## Requirements

## Requirements gathering

* Treat accessibility requirements as any other UI requirement
    * Functional requirements must be included in minimum viable product
    * Mostly non-functional requirements--app won't break, but user experience will be poor
* Can reference WCAG or external document and list exceptions
* Your process will establish due diligence
* Make sure you don't mix up "this will inconvenience the user" and "this disenfranchises the user" 

## Stakeholder feedback

* Unlike other requirements, stakeholders often don't think about accessibility.
    * Stakeholders see the impact of poor performance or not meeting requirements
    * This is much like other non-functional requirements, like security and logging
* Because of this, you may need to remind stakeholders of these requirements.
* Including accessibility means you have a better product. Better SEO, better usability, better customer retention/market

## Legal Requirements

* All electronic products produced or procured for the U of I subject to section 508.
    * Must be accessible to persons with disabilities
    * Alternate arrangements must be made when content cannot be made accessible

## Legal requirements are fuzzy

* Lots of room for (mis)interpretation
    * Lots of outdated advice
    * Lots of legal ambiguity
    * One-size-fits-all is not feasible
    * 100% coverage is unrealistic. 

## Functional Requirements

* What are you building?
    * Accessible output vs. accessible authoring tools for accessible output
    * Ignore requirements for components you aren't using
* What has the customer asked for?
    * Some components, frameworks have known accessibility challenges
* How much control do you have?
    * Third-party software may require changes

## Functional requirements are fuzzy

* Some specs and support defined by language, wcag, tools
* Big gap between meeting minimum functional requirements and meeting user expectations
* At some point, accessibility becomes usability
    * Accessibility/usability split makes a good threshold for minimum viable product
* Users are not monolithic--no substitute for user testing

## Project Methodology and Management

## Facilitate inclusion of accessibility

* Identify existing expertise and interest
* Appoint a liaison to accessibility experts if necessary--QA often a good choice
* Watch out for bottlenecks on critical personnel
* Determine external resources

## Share knowledge

* Come prepared with resources
* Anticipate role-based concerns
    * Designers likely to feel hobbled
    * Developers likely to be unsure what they need to implement 
* Spread the knowledge of accessibility across as many team members as possible -- this will prevent bottlenecks
    * Build a common understanding of accessibility inside your project team
    * Make sure minimum standards aren't written down and filed away

## Get to know your project

* Know your users
* Spend more time in the design phase
    * Play out use cases and user personas (and personas of users with disabilities)
    * Identify project elements and associated requirements/challenges
    * Identify sweet spot to begin implementing UI, which is especially sensitive to accessibility issues
* Spend time on process
    * Identify intake and prioritization heuristics
    * Develop use cases and personas
    * Identify supported technologies
    * Identify canonical guides
* Allow time to learn the tools!

## Build Your Skills

* Learn legal requirements
* Learn WCAG 2.0 success criteria (a, aa, aaa)
    * aa generally a safe, achievable choice
    * aaa good goal, but may be impossible to achieve on all pages
    * User content can fail a formerly accessible site
* Learn to recognize 11 requirements (Images, keyboard operability, forms, document structure, magnification, reading order, links & navigation, multimedia, tables, color & styles, aria)
* Learn to apply POUR principles (Perceivable, Operable, Understandable, and Robust)
* Understand accessibility/usability spectrum
    * Disabilities can range from mild to severe
    * Disabilities can be temporary
    * Users with disabilities are not monolithic
    * Users with disabilities are regular people
* Don't need to know everything

## Establishing Process to Minimize Risk

* Different user groups will have competing needs
* Accessibility is best included in an iterative fashion. Don't just test at the end of the lifecycle
* Work with team members to automate accessibility testing when possible
* Get QA and your accessibility experts involved early!
* Get user feedback early!
* Follow your checklists

## Working with vendors

* Use the Accessibility Requirements for Procured Software v1.7 document as a reference. 
* Be prepared to work with vendors that aren't familiar with accessibility requirements. 
    * This may mean finding other vendors
* Make sure accessibility requirements are communicated to the vendor and in the contract
    * Need to include remediation ("if it doesn't meet X, then it will be added on an agreed-upon time")
* Check for VPAT from the vendor
* Determine the vendor's point of contact to handle accessibility issues

## How do you know you're done

* Accessibility is treated like any other requirement. You're done when you need to release (or run out of money). 
    * Because you've prioritized your requirements, you know what needs to be completed to release a product.
* Be aware that accessibility technology changes quickly. When handing off to a product team, be aware that they will need to update the product to meet these changes. 
* Changing content may invalidate site accessibility 
* Document where future enhancements are needed. 
