# Product Ownership in Microsoft's Commercial Software Engineering team

CSE uses Scrum as its software engineering process, and a CSE Product Owner fullfills all of the normal Scrum Product Owner responsibilities.

In addition, CSE has a unique business model in which we collaboratively defined and execute projects with a wide range of customers, and we've developed a standard set of artifacts, best practices and terminology to support this model.

This page summarizes how Product Onwership is tailored to fit the CSE business model.

## Accountability vs. Responsibility

Here is a nice summary of the RACI framework:<sup>[1](#raci)</sup>

>## RACI definitions
>
>**Responsible:** This team member does the work to complete the task. Every task needs at least one Responsible party, but it’s okay to assign more.
>
>**Accountable:** This person delegates work and is the last one to review the task or deliverable before it’s deemed complete. On some tasks, the Responsible party may also serve as the Accountable one. Just be sure you only have one Accountable person assigned to each task or deliverable. (Note: It might not be your PM!)
>
>**Consulted:** Every deliverable is strengthened by review and consultation from more than one team member. Consulted parties are typically the people who provide input based on either how it will impact their future project work or their domain of expertise on the deliverable itself.
>
>**Informed:** These team members simply need to be kept in the loop on project progress, rather than roped into the details of every deliverable.

In short, the person who does the work is responsible, and the person that assures the work is completed correctly is accountable.

In other words, *the Product Owner is accountable* for assuring that all PO-related work is completed, even if the PO doesn't do all the work themselves.

Thus, the PO need not always write the backlog stories, identify all the risks, or create a CSE sharing plan, but the PO is accountable for making sure all these things are both done and done correctly.

## Who fills the Product Owner role on a CSE project?

There is often confusion about who the Product Owner should be on a CSE engagment/project. Should it be someone form the customer, an SEI or PM from CTE, a Dev Crews TPM, or perhaps a developer or tech lead?

The answer is simple: **It can be *anyone* with the skills and time to do the job.**

A key point, however, is that a PO is always required, and it should be a  **single person**. PO is not a role for a committee, and it's not a role that can just be ignored.

The following sections discuss some of the options.

### Customer as Product Owner from the Customer

While customers often have someone in a Product Owners or equivalent (e.g. Product Manager) role, it still usually makes sense for a CSE person to fill the PO role within the context of the CSE project.

Customer POs are usually focused on a much longer term perspective, and they struggle to narrow their focus to the scope of the CSE engagement. 

In addition, customer POs are not familiar with internal CSE expectations related to CSE engineering practices (e.g. problem statements, success criteria, CSE-style Scrum, one week sprints, etc.), engineering fundamentals,sharing, etc.

That said the team should decide, and it's fine for someone from the customer to fill the PO role if it makes sense.

### TPM as Product Owner

In most cases we prefer the PO role be filled by someone experienced from CSE.

Product Ownership is a core focus for the Dev Crews Technical PM team, and in cases where a TPM is avaialable, they are usually the best choice to act as the PO.

When a TPM is not  available, or another capabile person is also available, the project leads should have a conversation and make a decision.

### CTE SEI/PM as Product Owner

CTE SEIs and PMs can also fill the Product Owner role if they have the necessary experience and skillset.

We are working on defining a process to help train and qualify new POs, and we anticipate many CTE folks will be interested in becoming qualified POs.

### Developer as Product Owner

A developer or tech lead may have the knowledge and skills required to fill the Product Owner role. The trade-off is that the PO usually doesn't have time for much of anything else, so developers can't expect to both act as PO and code. If you try to do both, you'll probably not have time to do either role well.

## Project Definition

The most critical role for the Product Owner is assuring the project is appropriately scoped to meet the customer's business and technical goals. The first step is to make sure that all parties agree on the problems that need to be solved and to define what a successful solution looks like.

The Product Owner is accountable for the following items, which must be included in the project Game Plan:

* **Problem Statement(s):** One or more statements clearly articulating the essential problem(s) that the milestone must address to be declared a success. Uses implementation-free, non-ambiguous language that minimizes potential for different interpretations.

* **Customer Success Criteria:** Statements that must be true by the close of the engagement in order for the engagement to be considered a success from the customer's perspective. Success criteria typcially includes  capabilities that solve the problem statement, and it my include  customer-imposed technical, time or procedural constraints that must be observed in planning and executing the project.

* **CSE Success Criteria:** In addition to customer success criteria, CSE also has a standard set of success criteria that should be included with every project. These include CSE engineering fundamentals, sharing learning and resusable code, and any making appropriate contributions to the CSE Engineering Playbook.

* **Definition of Done:** SMART<sup>[2](#smart)</sup> criteria considered as essential to achieve a "minimum viable product" in the current milestone. These will be derived from the success criteria for the engagement and often include specific measurable targets to ensure that MVP engineering requirements are fulfilled.

## Backlog Management

Understanding and framing customer business goals in terms that are understandable and actionable by an engineering team is a complex task that typcially takes many years of experience to master.

A well-crafted backlog defines, in an implementation-free manner, the user- and business-centric stories that must be completed in order to successfully complete the project. and business-centric the functionality that must be enabled to successfully complete the project. The stories are stack-ranked from 1-n so that the developers have clear guidance on which ones should be completed first.

### Minimum Viable Product (MVP)

The concept of a Minimum Viable Product (MVP)<sup>[2](#mvp)</sup> is a powerful tool to help the entire project team identify and focus on the most important requirements and stories.

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

## Frequently Asked Questions

* **CSE works on short-term projects with customers, not full commerical products, so why do we need a "Product Owner"?**

  The term "Product Owner" describes an *role* within a Scrum team that is working on any project, large or small. A PO's responsibilities are very clear for every engineering project.

* **How can a CSE person be the PO if the customer has a PO with all the expertise, etc.?**

  The CSE PO does not replace or substitute for the customer PO. Rather the CSE PO works in the context of the CSE engagement with the CSE engineers as their primary audience

* **How can it make sense for someone from CSE to act as a product owner for a product that is actually owned by a customer?**

  CSE Product Owners limit their focus the immediate engagement with the customer and do not even attempt to focus on the customer's broader products and services.

  In addition, CSE product owners are trained to understand the unique characteristics and requirements of a CSE engagement, and that knowledge very much influences how the job is done. For example, CSE POs understand what it means to draft problem statements, define customer and CSE success criteria, what sorts of engineering fundamentals need to be included in CSE projects, etc. 

* **Who is the best person to act as Product Owner on a CSE engagement?**

  Product Ownership is a core expertise for the Dev Crews Technical PM team, and most TPMs have many years of experience working as POs. For this reason, TPMs are usually the best choice *if one is available.*

  CTE SEIs and PMs with the right skillset are also good choices, and in a pinch dev crews can nominate one of their own developers to fill the role.

* **How do I learn how to be a good Product Owner?**

  The best way to learn anything is to do it, and CSE's strategy for training POs is to provide real-world opportunities to perform the role.

  To minimize risk and maximize learning, our preferred approach is for aspiring POs to shadow an experienced PO on a real engagement.
  
  And when a new PO takes full responsibility for the first time, we will arrange for an experienced PO to be avaiable to coach.

## Footnotes

<a name="raci">1</a>: How to Clear Project Confusion with...RACI(https://www.teamgantt.com/blog/raci-chart-definition-tips-and-example)

<a name="smart">2</a>: Atlasssian: [How to Write SMART goals](https://www.atlassian.com/blog/productivity/how-to-write-smart-goals)

<a name="mvp">3</a>: https://en.wikipedia.org/wiki/Minimum_viable_product