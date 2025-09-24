# User Research Report

## Methods
- Approach: <interviews/survey/observation/competitor>
- Sampling & Consent: <sample size / recruitment / privacy>
- Instruments: <interview guide / survey link / notes method>
- Timeline: <start–end + milestones>

## Raw Data Index
- Notes: ../data/*.md
- Survey CSV: ../data/survey.csv
- Images: ../imgs/*

## Thematic Findings (3–5)
- Theme A — Evidence: <quote/data> → Implication: <design takeaway>
- Theme B — Evidence: … → Implication: …
- Theme C — Evidence: … → Implication: …

## Personas (≥2)
### Persona 1
- Name / Demographics / Photo(placeholder)
- Goals / Motivations / Pain Points
- Technical Proficiency & Devices
- Scenario: <1 paragraph how they use the site>

### Persona 2
- <same sections>

## Role — Jethro Clyde
**One-line tag:** Third-year Nursing student; essay proofreading and flexible peer support user; motivated by affordability, trust, and time-saving.
**Basic information:** Age 22 · Full-time student with part-time shifts · Devices: iPhone (main) + Windows laptop
**Accessibility/Abilities:** Prefers mobile-first access; needs simple navigation and large buttons for use on the go; sometimes uses voice input while commuting; values clear receipts for services and strong profile verification to build trust.

**Goals**
- Find quick, reliable essay proofreading and assignment feedback.
- Earn FUSSCredits by offering first aid tutoring and health tips.
- Manage time efficiently between hospital placements, shifts, and uni.
- Connect with peers outside Nursing to broaden her academic network.

**Pain points**
- Private tutoring is expensive and unaffordable on student income.
- Juggling hospital placements, study, and work → limited availability.
- Feels uncertain about trusting strangers online for study help.
- Gets stressed when systems are complicated or lack transparency.

**Behavior and Scenarios**
- Uses micro-sessions on mobile (during breaks, commuting, after shifts).
- Relies heavily on notifications for new requests and confirmations.
- Laptop mainly for essay writing, but phone for skill requests/messaging.
- Scenario: After a placement shift, Jethro uses FUSS on her phone to book one hour of essay proofreading with credits earned from tutoring basic first aid. She checks her balance, confirms completion, and leaves a review.

**Core Tasks**
- Browse and request essay proofreading help.
- Offer tutoring sessions (basic first aid, study tips).
- Track her FUSSCredit balance and transaction history.
- Manage availability (mark busy periods during placements).
- Communicate securely with peers through in-app messaging.

**Success Definition**
- Can book a peer service in under 3 minutes via mobile.
- Receives clear confirmation and visible credit adjustment immediately.
- Messaging system is simple and reliable, even on weak Wi-Fi.
- Reviews and ratings are displayed transparently to help her trust others.

  **Use Cases (PACT)**
**Physical Environment**
- Uses app on campus, hospital, home, and while commuting (bus/train).
- Relies on mobile network often; hospital Wi-Fi can be unstable.
- One-handed use common → needs big tap targets.
- Situations may be noisy/busy → prefers visual confirmation over sound.

**Social**
- Balances peer-to-peer learning with part-time job and placements.
- Cares about politeness and respectful communication (important in Nursing culture).
- Relies on reputation/reviews before trusting new students.

**Organization**
- Must fit FUSS use around fixed hospital shift schedules.
- Needs clear refund/credit-return policies if services are cancelled.
- Wants reporting features in case of misuse or unprofessional behavior.
- Requires simple onboarding → verify Flinders email + profile approval.

**Technical and Accessibility Restrictions**
**Input**
- Touchscreen gestures (main).
- Quick text input + voice dictation for messaging.
- Camera scan for ID/profile verification if needed.

**Output**
- Mobile-first design with responsive layouts.
- High-contrast and simple UI with large buttons.
- Clear transaction receipts with credit balance updates.

**Communication and Integration**
- Secure HTTPS + student login (FAN/2FA).
- In-app + push notifications (service requests, confirmations).
- Simple inbox/outbox for messages, synced to email.

  **Content and Data**
- Text, PDFs (essays), short notes, reviews.
- Needs history of past requests and proof of credit usage.
- Backup/restore of transactions for disputes or audits.




## Competitor Analysis (2–3)
| Product | Key Features | Strengths | Weaknesses | Adopt | Avoid |
|---|---|---|---|---|---|
| Facebook Groups (Uni Study/Skill Pages) | Peer-to-peer posts, free help offers, event sharing | Free, familiar platform, easy to join, wide reach | No credit system, hard to track services, poor trust/reviews | Easy posting & community reach | Lack of structure, no transaction tracking |
| Airtasker | Service marketplace with posting, bidding, ratings | Strong profile/review system, clear tasks, mobile app, secure | Requires money (not credits), more for general public than students | Rating/review system, clear task workflow | Monetary payments, not suitable for student credits |



## Role — Emily Carter 
**One-line tag:** Second-year computer science student; daily schedule/assignment management user; highly sensitive to speed and clear feedback.
**Basic information:** Age 20 · Full-time student · Devices: MacBook + iPhone (occasionally uses a tablet)
**Accessibility/Abilities:** Familiar with modern user interfaces; requires adjustable font size and high contrast; supports keyboard navigation; occasionally relies on subtitles/text transcripts in noisy or low-visibility environments.

**Goals:**
- Quickly view the location/time/map for the **next class**.
- Reliably submit assignments within the last 5–15 minutes and receive clear submission confirmation.
- Quickly browse important announcements; **mark important content as read** or **pin** for follow-up.

**Pain points**
- Limited attention span when multitasking; frustration with slow or cluttered interfaces.
- Inconsistent submission rules (format/size/version) → concern about silent failures.
- Rarely used features are easily forgotten; need prompts/tooltips.

**Behavior and Scenarios**
- Multiple micro-sessions (30–60 seconds) daily; peak at the beginning/end of the semester and near deadlines.
- Mobile devices are used to receive notifications; laptops are used to view schedules and submit assignments.
- Need calendar/time zone and campus map compatibility.

**Core Tasks**
1) View schedule and locate **next class**.
2) Submit assignment and obtain **proof of successful submission**.
3) Read announcements and contact teaching staff.
4) Manage course selection/change (1–3 times per semester).

**Success Definition**
- The “next class” card is visible within **10 seconds**; detailed information is accessible within **2 clicks**.
- Successful submission in one attempt; if failed, display actionable error messages; generate a receipt ID.
- Announcements support **unread/pinned**; one-click access to contact forms.
**Use Cases (PACT)**

**Physical Environment**
- Used on campus, at home, and while commuting; lighting and noise conditions vary.
- Devices: Mobile phones (main device), laptops, library computers; single-handed operation of mobile phones is common.
- Network: Unstable campus Wi-Fi signal; mobile data traffic restrictions/disconnections; limited battery life.
- Privacy: Risk of shoulder surfing in public places → Minimize exposure of sensitive information.

**Social**
- Mainly for personal use; frequent team collaboration and peer assistance.
- Communication with teaching teams must be traceable and use polite templates.
- Mixed cultural backgrounds and varying English proficiency → Use simple language and avoid technical jargon as much as possible.

**Organization**
- Use FAN/2FA single sign-on; session timeout policy.
- Set fixed academic deadlines; clarify the process for handling “extensions/special circumstances.”
- Maintain maintenance windows and service announcements; have backup/downgrade plans.
- Support channels: FAQs, ticket system, real-time chat; use ticket numbers for follow-up.
**Technical and Accessibility Restrictions**

**Input**
- Touch/keyboard/trackpad; drag-and-drop upload; camera scan or QR code; optional system voice input/speech recognition.
- Keyboard accessibility: logical tab order, keyboard shortcuts, visible focus status.

**Output**
- Responsive design (mobile-first); high-contrast theme options; adjustable font size.
- Clear success/error feedback, progress indicators, and **receipts**; optional PDF confirmation.
- Alternative text for images; subtitles/transcripts for audio/video.

**Communication and Integration**
- Always uses HTTPS; integrates with single sign-on (SSO), student records, and calendars (ICS subscription).
- Notifications: in-app + email (optional browser push);frequency and quiet time controls.
- File upload limits (size/type); supports **resume/retry**.

**Content and Data**
- Supports text, PDF, tables, rich text; maps/location information; powerful time and time zone handling.
- Data retention and version control: assignment history, message logs, export options (CSV/PDF).

## Competitor Analysis

| Product        | Key Features                              | Strengths                                      | Weaknesses                                  | Adopt                          | Avoid                         |
|----------------|-------------------------------------------|-----------------------------------------------|---------------------------------------------|--------------------------------|-------------------------------|
| Timebanking.org| Credit exchange system, volunteering      | Strong community focus, proven credit system   | Outdated interface, not student-focused      | Credit-based exchanges          | Old design, low engagement    |
| PeerWise       | Student-generated quizzes, gamification   | High engagement, tailored to students          | Limited scope (quizzes only)                | Gamification, peer-driven model | Narrow focus                  |

## Design Implications
**Design Implications**
**Navigation**
- Must be simple and consistent: clear top menu (Home, Profile, Skills, Messages, Help).
- Quick access to core tasks: “Request Skill” and “Offer Skill” buttons always visible.
- Support search + filters (by skill category, academic topic, availability).

**Content Hierarchy**
- Prioritise most-used features:
  - Dashboard shows Next Class / Next Booking card, credit balance, recent messages.
  - Profile highlights Skills Offered/Requested first, then history/reviews.
-Announcements and messages must support pinning or marking as read (Emily’s need).

**Forms**
- Short, step-by-step style (avoid long overwhelming forms).
- Validation with clear error messages (no silent failures).
- Provide receipts/confirmation IDs for key actions (submission, booking, credit transfer).
- Defaults and tooltips for rarely used options (to help users like Emily who forget rarely-used features).

**Accessibility**
- Mobile-first design (important for Jethro, who mostly uses her phone).
- Adjustable font size + high contrast themes.
- Full keyboard navigation (tab order, focus indicators).
- Alternative text for images; subtitles/transcripts for video.
- Minimise sensitive info on screen (Jethro’s privacy concern about shoulder surfing).


### Summary
Both competitors show that **credit systems** and **gamification** are effective ways to motivate users.  
Our platform builds on these strengths while avoiding their weaknesses, by providing a **modern, student-focused design with broader features** beyond quizzes or volunteering.
