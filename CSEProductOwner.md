# Product Ownership in Microsoft's Commercial Software Engineering team

CSE uses Scrum as its software engineering process, and a CSE Product Owner fullfills all of the normal Scrum Product Owner responsibilities.

In addition, CSE has a unique business model in which we collaboratively defined and execute projects with a wide range of customers, and we've developed a standard set of artifacts, best practices and terminology to support this model.

This page summarizes how Product Onwership is tailored to fit the CSE business model.

## Project Definition

The most critical role for the Product Owner is assuring the project is appropriately scoped to meet the customer's business and technical goals. The first step is to make sure that all parties agree on the problems that need to be solved and to define what a successful solution looks like.

The Product Owner is accountable for the following items, which must be included in the project Game Plan:

* **Problem Statement(s):** One or more statements clearly articulating the essential problem(s) that the milestone must address to be declared a success.  Uses implementation-free, non-ambiguous language that minimizes potential for different interpretations.

* **Success Criteria:** Statements that must be true by the close of the engagement in order for the engagement to be considered as a "success".  Includes "success" as defined by the customer as well as Microsoft (i.e., meeting CSE standards for quality engineering that can be successfully handed over to customer engineers).  Success criteria also include any customer-imposed technical, time or procedural constraints that must be observed in planning and executing the project.

* **Definition of Done:** SMART<sup>[1](#smart)</sup> criteria considered as essential to achieve a "minimum viable product" in the current milestone.  These will be derived from the success criteria for the engagement and often include specific measurable targets to ensure that MVP engineering requirements are fulfilled.

## Backlog Management

Understanding and framing customer business goals in terms that are understandable and actionable by an engineering team is a complex task that typcially takes many years of experience to master.

A well-crafted backlog defines, in an implementation-free manner, the user- and business-centric stories that must be completed in order to successfully complete the project. and business-centric the functionality that must be enabled to successfully complete the project. The stories are stack-ranked from 1-n so that the developers have clear guidance on which ones should be completed first.

### Minimum Viable Product (MVP)

The concept of a Minimum Viable Product (MVP)<sup>[2](#mvp) is a powerful tool to help the entire project team identify and focus on the most important requirements and stories.

It is natural and inevitable that the team will discuss a very broad set of requirments and features while planning a project. Asking the question, "Is this an MVP requirement?" is a great tool for identiifying the most important requirements that need to be addressed immediately versus those that can be addressed later in the project.

When time and resources are constrained, an MVP discussion is critical to winnowing down project to the minimum amount of work.

And even when time and resources feel ample, the MVP question is still valuable in terms of identifying the most important requriements.

### Implementation Free User Stories

It is critical that user stories not include any assumptions about the implementation, as this provides the developers with the flexibility to define solutions that the Product Owner may not have considered. 

It is a maxim of good product ownership, that POs focus on the "what and why" without getting into the "how." 

Keeping stories implementation free can be very challenging, as requirements are often discussed, even by developers, with assumptions about features and technical approaches. A good Product Owner is able to step back and ask, "What is the underlying requirement that is being discussed?" Once the requirement is understood, it becomes much easier to write an implementation free story that explains what a user needs to achieve and why.

### Collaborative Backlog Management

Successful backlog creation and management requires substantial collaboration with the developers. A good practice is to review and groom the backlog collaboratively. Successful collaboration approaches include:

* Product Owner and Tech Lead review and edit the backlog together.

* Product Owner edits backlog collaboratively with the developers responsible for implementing the stories being reviewed.

* Product Owner leads a group backlog grooming session with the full team, which enables broad and inclusive discussion, and helps drive better understanding and awareness across the project.

All methods can be used on the same project.

## Identifying key stakeholders and influencers

Scrum Product Owners are always expected to identify key stakeholders and influencers. In CSE, this means:

* Customer engineering leaders and engineers.

* Customer executives who are sponsoring the engineering team with whom we are collaborating.

* Other customer teams/individuals who can impact successful completion of the project. For example, many customers have central cloud IT teams that control access to Azure subscriptions or the creation of Service Principle Names (SPNs), or security and compliance teams that must approve archiecture and/or production deployments.

* CSE stakeholders from CTE, including the on-point SE/I, SE/I lead and industry team leaders.

* Dev Crews stakeholders, including the Tech Lead, developers and TPM(s) from both general purpose teams, Tech Domain teams, and shared services teams (e.g. Machine Leaerning, DevOps).

* Account team contacts and roles. Every customer has a unique mix of account team stakeholders with a variety of skillsets, and it's important to identify the role each account team member fills with the customer.

* Relevant contacts from the Azure product teams and other Azure teams, such as Azure Global.

## Risk Management

In collaboration with the full project team, the Product Owner should  proactively identify, track and drive mitigation of any issues that risk successful completion of the project (i.e. definition of done and success criteria) within the planned time and staffing constraints.

The PO should also identify intangible and indirect risks such as those related to customer relationship/trust building and potential for follow-on engagement(s) with the account.

## Footnotes

<a href="#smart">1</a>: Atlasssian: [How to Write SMART goals](https://www.atlassian.com/blog/productivity/how-to-write-smart-goals)

<a href="#mvp">2</a>: https://en.wikipedia.org/wiki/Minimum_viable_product