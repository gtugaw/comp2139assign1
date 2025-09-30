# COMP 2139 - Assignment 1

**Due Date:** Friday, October 10th, 2025 (11:59 pm)  
**Team Size:** Maximum of 3 students per group

---

## Objective

The primary goal of this group project is to develop a dynamic, web-based **Virtual Event Ticketing System** for hosting and managing virtual events (webinars, concerts, workshops).  

The system will allow users to:
- Manage events
- Browse and purchase tickets
- Track guest check-ins (no authentication required)

**Focus of Assignment 1:**  
- Event & category management  
- Search & filtering functionality  
- Guest ticket purchasing  

Advanced features (authentication, live streaming, analytics) will be in **Assignment 2**.

**Learning Outcomes:**  
- Hands-on experience with database-driven web apps  
- ASP.NET Core MVC architecture  
- Integration of front-end & back-end  
- MVC principles in real-world event management  

---

## Requirements

**Compulsory Technologies:**
- ASP.NET Core MVC
- C#
- Web Server
- Database (e.g., PostgreSQL)
- .NET 8.0+
- MVC Design

**Deliverables:**  
See "Submission Checklist" document.

---

## Project Requirements (Compulsory Components)

### Event Management
- Page to list all events with category filter
- Form for adding new events with fields:
  - Event title
  - Category (webinar, concert, workshop, conference)
  - Date & time
  - Ticket price
  - Available tickets
- Update & delete existing events

**Highlights:**
- Event overview page (total events, categories, low ticket alerts `< 5`)
- Basic CRUD operations

---

### Search and Filtering
- Search events by title or date
- Filters:
  - Category
  - Date range
  - Ticket availability (available, sold out)
- Sorting options (title, date, price)

**Highlights:**
- Dynamic search with real-time results
- Refined filters
- Sorting for better UX

---

### Guest Ticket Purchasing
- Guest users can select events & ticket quantities
- Confirmation page with:
  - Event title(s)
  - Purchase date
  - Total cost
  - Guest contact info (name, email)
- Purchases saved without registration

**Highlights:**
- Purchase summary
- Guest users (no authentication)

---

## Application UX & Design

- Homepage with navigation to key features
- Responsive design (HTML, CSS, JS)
- Modern aesthetics (colors, event graphics)
- Navigation bar (event management, ticket purchasing)
- Footer with team info (group number, member names)

**Highlights:**
- Seamless navigation
- Dynamic, professional design

---

## Database Recommendations

1. **Incremental Development** – build core tables first  
2. **Core Tables:**
   - Events (title, date, time, price, tickets, category)
   - Categories (name, description)
   - Purchases (ID, date, cost, guest info, event relationships)
3. Simplified guest purchases (name, email)
4. Flexible schema for future features
5. ERD with relationships:
   - One-to-many (categories → events)
   - Many-to-many (purchases ↔ events)
6. Data integrity (foreign keys, constraints)
7. Normalization
8. EF Core migrations (include in repo)
9. Seed data for testing

---

## Final Word on Implementation

### Creativity & Originality
- No wireframes provided → design freedom
- Originality encouraged (usability + aesthetics matter)

### Implementation & Problem-Solving
- Requirements guide you, but leave room for judgment
- Research & exploration expected
- Problem-solving approach is part of evaluation

### Design Considerations
- Final UI/UX decisions are your responsibility
- Must adhere to MVC architecture

### Flexibility & Expansion
- Add extra pages/features if useful
- Interpret & expand requirements creatively

---

## 1-Page Project Status Report

**Details:**
- Completed requirements (brief description)
- Uncompleted requirements (with reasons)
- Must be referenced in video demo
- Missing report → loss of marks

---

# Assignment Submission Guidelines

1. **Video Requirement**
   - Short video presentation (5–10 min max)
   - Intro slide with:
     - Group member images (no avatars)
     - Full names, Student IDs, Course Code, Section, Assignment info
   - Demonstrate program functionality
   - Use status report during video
   - Each member explains code segments
   - Clear audio & resolution required
   - Poor quality video → assignment failure
   - Over 10 min → grade = zero

2. **Submission (by team lead on Brightspace)**
   - 1-page status report (mandatory)
   - Group video file (mandatory)
     - YouTube, Loom, etc.
   - Private GitHub URL

3. **Caution**
   - Do not share code with others
   - Code sharing = failure

4. **No video demo = grade zero**

5. **Late penalty:** -20% per day

---

**GOOD LUCK!!**
