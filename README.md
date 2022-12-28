# University Registration Database Administration
    MIS 325: Database Management
    Client: UT Austin Information & Technology Desk
    
_**This was a long-form project completed over four weeks.**_


### [Click here](sareen.notion.site) to view in Notion.

---

### Background
UT Austin's IT Department needs help restructuring their _**Student and Course Registration System**_, and they've issued an open challenge to all students: design and build out a DDL script for the skeleton of an enterprise-level RDBMS capable of handling UT Austin's undergraduate and graduate student body as well as their course registration each semester.

### Deliverables 
1. Normalized ERD for UT Registration
2. DDL Script To Define RDMBS
3. Testable Database (using mock data)

### Approach
First, we conducted an in-depth discovery of the registration process by speaking with system administrators and other users. We also evaluated the practical nuances of registration and potential relational caveats. For instance, storing each student's addresses poses a challenge for our database's cardinality; since most kids have both a home and local address (and some students will also share their local address). To overcome this, I created a bridge or "linking" table to map the many-to-many relationship between students and addresses in order to satisfy our RDMS integrity.

Here's a link to my a LucidSpark chart of my final [logical ERD schema](https://lucid.app/lucidspark/d6d7d83b-4f92-4f24-8284-be3c9bae5e41/edit?viewport_loc=-794%2C-226%2C3840%2C1938%2C0_0&invitationId=inv_48421743-ac1e-4a0b-ab75-c4ff60eb7bfb).


---

## Key Takeaways ##

**Database Design**

    - Basic RDBMS concepts + fundamentals
    - Primary key vs foreign key vs compound keys
    - 1-1 vs 1-M vs M-M relationships
    - Schema design techniques (simple, logical, phyical ERDs)

**Normalization**
    
    - What it is
    - When to normalize
    - Why we normalize
    - Denormalizing

My notes on: 
- [normalization](https://sareen.notion.site/Normalization-8834c653bf4740d498e65634c3977a59)
- [indexes + sequences](https://sareen.notion.site/indexes-sequencing-b4d78b58a821488f81bc81566f83728d)


</aside>


