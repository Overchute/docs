# Grant Details

---

## General Info

- Grant category: Apps & Open Internet Services
- Grant size: $25,000
- Already started: Yes. https://github.com/Overchute/overchute-app
- Referral: Dfinity mailing list, Twitter & Medium
- Open source: Yes
- Monetize: Not sure yet

---

## Project Description

Public goods are a shared heritage that drives human progress. But because they are non-excludable, free-riders benefit just as much as contributors, so it is difficult to sustainably fund them even if their value far exceeds their cost. The lack of a profitable business model means that public goods are often under-provided by free markets.

The Internet Computer has enabled the practical implementation of a new mechanism for voluntary funding of public goods, called the Blind Crowdsale Protocol. It mitigates the free-rider problem in situations where existing trust-based mechanisms fail because of competitive dynamics or a product of known quality is required at the lowest possible price. An important use case is an intellectual property (IP) such as patented technologies or copyright-protected digital goods like software, literature, art, music and film. The protocol works as follows:

- A creator offers to release an already-existing work of IP under an open licence for a specified price.
- Members of the public make contributions to the crowdsale.
- Individual contributions, and therefore the total contributed amount, are not disclosed.
- The crowdsale runs to its end date, regardless of whether the offer price has been reached.
- If the offer price isn't reached, all contributions are refunded.
- If it's reached or exceeded, the creator pays the offer price, and the IP is released under the open licence. After an admin fee, the overshoot (of excess contributions) is shared between the creator and the contributors. The contributors' share is refunded in proportion to individual contributions.

Because the total contributed amount isn't disclosed, potential contributors who value the IP can't free-ride without risking the failure of the crowdsale, and they are incentivised to recruit other contributors, to increase their own refund from the overshoot. Overshoot-sharing also encourages creators to keep offer prices low and provides a revenue stream to fund operations.

_Overchute_ is a decentralized smart-contract application implementing the Blind Crowdsale Protocol for IP as an open internet service on the Internet Computer. Its goal is to provide a new monetization channel for the creator economy while enriching the public domain. With its user base of creators and contributors, it has the potential to bring large communities to the Internet Computer. The MVP can be implemented without known barriers or significant dependencies. The grant funding will be used to fund developer hours and cover sundry expenses.

---

## Project Roadmap & Milestones

![](/static/overchute_uml.png)

- **Milestone 0** - Project kick-off (Completed 31 Aug 2021)
  - Protocol and dapp design
  - Branding, pitch deck & landing page
  - Create ICP dApp shell, crowdsale canister, project's UML
  - Apply for Dfinity Foundation Developer Grant
- **Milestone 1** - Create crowdsales (Target date: 30 September 2021)
  - Develop crowdsale database and CRUD operations
  - Develop front-end form to create crowdsales
- **Milestone 2** - Execute crowdsales (Target date: 31 October 2021)
  - Allow navigation to crowdsale
  - Allow contributions to crowdsale
  - Apply deadline mechanism (protocol rules) to distribute funds
  - Create status change module
- **Milestone 3** - MVP launch (Target date: 20 December 2021)
  - Create font and back end functionality to display crowdsales statuses
  - Add testing modules: public testing
  - Release

| Date           | Milestone                                                             | Status  | Assigned To |
|----------------|-----------------------------------------------------------------------|---------|-------------|
|                | **Phase 0**                                                           |         |             |
| 07/31/2021     | Project Start                                                         | Done    | Team        |
| 08/03/2021     | Project details                                                       | Done    | Malcolm     |
| 08/08/2021     | Create landing page                                                   | Done    | Fer         |
| 08/12/2021     | Create Overchute docs                                                 | Done    | Artur       |
| 08/13/2021     | Add Grant details to docs                                             | Done    | Malcolm     |
| 08/15/2021     | Create ICP dApp shell                                                 | Done    | Fer         |
| 08/22/2021     | Create crowdsale canister                                             | Done    | Artur       |
| 8/26/2021      | Create project's UML                                                  | Done    | Fer         |
| 8/27/2021      | Apply for Dfinity's grant                                             | Done    | Team        |
|                | **Phase 1**                                                           |         |             |
| September 2021 | Allow users to login to Overchute's dApp with the internet's identity | Created | Fer/Artur   |
|                | Create crowdsale database                                             | Created | Artur       |
|                | Allow CRUD operations for crowdsales                                  | Created | Fer/Artur   |
|                | Create front-end form to insert crowdsales                            | Created | Fer         |
|                | **Phase 2**                                                           |         |             |
| October 2021   | Create search module front and back end                               | Created | Fer/Artur   |
|                | Apply deadline mechanism                                              | Created | Artur       |
|                | Create change status module                                           | Created | Artur       |
|                | **Phase 3**                                                           |         |             |
| November 2021  | Create font and back end functionality to display crowdsales statuses | Created | Fer/Artur   |
|                | Add testing modules: public testing                                   | Created | Team        |
| December 2021  | Release                             

---

## Unique Benefits for Internet Computer Ecosystem

Overchute provides a decentralized finance tool to meet a specific need in the booming digital creator economy. For creators, it offers a new monetization channel that doesn't require ongoing enforcement of restrictive licences. For contributors, it provides a safe way to collaborate with others to secure usage rights to valuable IP. For the public, the Blind Crowdsale Protocol enables the efficient provision of public goods by incentivizing honest offer prices and contributions.

With use-cases across several digital media industries, Overchute will be used by influential creators with large communities of followers. To participate in crowdsales, contributors will need to set up wallets to hold cycles, which will introduce them to the Internet Computer and reduce friction for using other apps. Furthermore, Overchute can be used as a mechanism for sustainable funding developers building open-source utilities for the Internet Computer ecosystem itself.

Overchute will be open-source from the start, and the goal is to run it as an Open Internet Service using the features of the Service Nervous System. Ownership will be gradually decentralized using a token incentive model that rewards successful crowdsales and builds network effects.

---

## Team Dynamics

The project team has four members, working remotely on a part-time basis:

- **Artur Khaialiev**
  - Role: Smart contract & fullstack developer
  - Location: Vienna, Austria
  - Qualifications: BSc Computer Science (Data Science track), Innopolis University, Innopolis, - Russia: MSc Computer Science, University of Vienna, Vienna, Austria
  - Experience: Backend Developer at RTK Soft Labs, Innopolis, Russia; Chief IT-engineer at Sbertech, Innopolis, Russia. More than 6 years of development in various projects including blockchain applications. Expertise in machine learning, data mining, mobile, backend, frontend development.
- **Fernando Martinez**
  - Role: Smart contract & fullstack developer
  - Location: Houston, Texas, USA
  - Qualifications: Bachelor of BA in Management Information Systems, C.T. Bauer College of Business, University of Houston, Houston Texas.
  - Experience: 11+ years in designing, coding and implementing fullstack web applications. Deep curiosity for learning that led to quickly adapt and acquire broad technical knowledge of server environments, programming languages, databases, frameworks, libraries and modern tools and tool-kits. Currently works at Mesa Technologies and previously at AIG.
- **Malcolm Murray**
  - Role: Product & protocol designer (and current owner of South African company Overchute (Pty) Ltd, reg: 2021/801241/07)
  - Location: Secunda, South Africa
  - Qualifications: MSc (2011) & BSc (2009) Industrial Engineering, University of the Witwatersrand, Johannesburg
  - Experience: 10 years in the manufacturing industry, focusing on operations excellence and business process improvement, with an emphasis on data analysis and modelling. Special interest in incentive design and market dynamics.
- **Houman Shadab**
  - Role: Legal advisor
  - Location: New York City, New York, USA
  - Qualifications: Doctor of Jurisprudence (J.D.) (2002) University of Southern California - School of Law; B.A. (1998) University of California at Berkeley
  - Experience: Director of the Innovation Center for Law and Technology at New York Law School and a Fellow at Stanford CodeX. Prolific and influential expert at the intersection of law, technology, and business. Co-founder of smart legal contracts startup Clause.
