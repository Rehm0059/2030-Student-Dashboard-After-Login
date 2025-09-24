# Project Proposal – Flinders Uni Skill Share (FUSS)

## Website Concept
University students possess a diverse range of skills but lack a formal, trusted platform to exchange them. Financial constraints often prevent students from accessing the academic and practical help they need, while those who can offer help have no efficient way to connect with peers and build a reputation within the university community.

Value Proposition: FUSS benefits Flinders University students by creating a supportive, reciprocal economy where time is the currency. It provides a structured, secure, and university-specific platform for students to get the help they need, monetize their spare time and skills, and foster a stronger, more collaborative campus community, all without financial transaction.

**Primary Use Cases:**

- Earn FUSSCredits by listing and providing a skill.
- Spend FUSSCredits to request and receive help with a needed skill.
- Manage profile, skills, and transaction history.
- Negotiate and confirm service details with another student.
- Review a peer after a completed service.

## Target Audience Profile
The primary audience for **Flinders Uni Skill Share (FUSS)** are **students enrolled at Flinders University**. This includes both undergraduate and postgraduate students across different Colleges.   

### Audience Characteristics
- **Age Range:** Mainly 18–30 years old (typical university age group).  
- **Status:** Mix of domestic and international students.  
- **Academic Levels:** First-year undergraduates through to Masters and PhD students.  
- **Fields of Study:** Wide range – Engineering, IT, Business, Arts, Education, Medicine, etc.  

### Needs
- Find **affordable help** with academic tasks such as tutoring, essay proofreading, or project support.  
- Get support with **non-academic skills** like moving, cooking, or design.  
- Share their own knowledge and abilities, gaining recognition and earning FUSSCredits.  
- Build **peer-to-peer networks** that make student life easier and more social.  
- Access a safe, **student-only platform** where they can trust the people they are interacting with.  

### Technology Habits
- **Devices Used:**  
  - Laptops and desktops for study and web access.  
  - Smartphones for quick communication and checking updates.  
- **Digital Skills:**  
  -  Are comfortable using online systems like Canvas, FLO, MyFlinders, and other university portals.  
  - Regular users of messaging apps (Messenger, WhatsApp, Discord).  
  - Familiar with online reviews/ratings from apps like Uber, Gumtree, Airtasker, and Fiverr. 

## Scope Statement
### Key Features

#### Student Profile and FUSS Management
- Registration, secure login, and session management
- Personal profile management (name, degree, bio, profile picture)
- Listing skills offered and requested
- Viewing FUSSCredit balance and transaction history


#### Peer Skill Exchange
- Search and browse skills or students
- Request a service from another student with scheduling options
- Basic negotiation of service details
- Confirmation of service completion and automatic FUSSCredit transfer
- Peer review system with ratings and testimonials


#### Scheduling and Communication
- Manage availability (basic) and detailed calendar (stretch goal)
- Internal messaging system for coordination and service negotiation


#### Administrator Features
- Dashboard for monitoring system activity
- Manage students, FUSSCredits, skills, and content
- Basic moderation and dispute handling


### Backend Functionalities
- User Authentication: A secure login system that hashes and validates passwords against a database.
- Dynamic Search & Filtering: Server-side processing to query the database for skills and students based on user input.
- Credit Management: A system to validate user balances and process FUSSCredit transfers upon completed services.
- Admin Dashboard: A secure interface for administrators to view users, adjust credit balances, and moderate content.


### Stretch Goals (Advanced Features)
- Calendar-based availability and conflict detection
- Recommendation engine for matching students and skills
- Real-time notifications and messaging


### Mastery Goals (High Complexity Features)
- Dispute resolution workflow with admin mediation
- Advanced trust and reputation system for students
- Complex search with weighted relevance


### Content Areas
- Student profiles, skill listings, service requests, messages, reviews, and administrative dashboards
- All content stored and retrieved from the backend database
- Focus on user-centered design for intuitive interaction

## Success Metrics
- Acquisition: New user registrations (database count).
- Engagement: Service requests per user (server logs).
- Task Success: Request completion rate (DB analysis).
- CSAT: Average review rating (1-5 stars).

## Risks & Mitigations
- Low Adoption: → Mitigation: Offer sign-up bonus credits.
- System Abuse: → Mitigation: Flag suspicious transactions & reviews.
- Scope Creep: → Mitigation: Prioritize MVP features first.
- Technical Debt: → Mitigation: Code reviews & solid DB design.