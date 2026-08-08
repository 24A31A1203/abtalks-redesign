# PROMPTS.md

# ABTalks Redesign Hackathon
# Problem Statement 1

## Project Goal

Build a mobile-first redesign of the ABTalks 60-day coding challenge platform.

The application should contain three routes:

/
 /dashboard
/day/12

The design should be optimized for a 390px mobile viewport while also supporting desktop screens.

---

## Prompt 1 — Project Setup

Create a React + Vite application for the ABTalks redesign hackathon.

Requirements:
- Use React
- Use JavaScript
- Use React Router
- Create routes for:
  /
  /dashboard
  /day/12
- Use mocked data instead of authentication or a production database.
- Make the application mobile-first.
- Use reusable components where appropriate.

---

## Prompt 2 — Landing Page

Design a premium mobile-first landing page for ABTalks.

ABTalks is a 60-day coding challenge for Indian college students.

The landing page should communicate:
- What ABTalks is
- Why students should join
- 60-day challenge concept
- Daily building
- GitHub proof of work
- LinkedIn proof of work
- Student consistency
- Recruiter visibility

Create a strong hero section, clear call-to-action, explanation of how the challenge works, proof-of-work section, and final CTA.

The visual design should feel modern, technical, motivational and polished.

---

## Prompt 3 — Student Dashboard

Create a mobile-first student dashboard for the ABTalks challenge.

Include:
- Current streak
- Today's challenge
- Challenge progress
- Overall completion percentage
- Student achievements
- Recent activity
- Current challenge day
- Progress indicators

Use realistic mocked student data.

Also handle:
- First day with no streak
- Missed challenge day
- Empty profile

Add a thoughtful student-experience feature called "Streak Shield" that helps students understand how they can recover from a missed day without feeling discouraged.

---

## Prompt 4 — Challenge Day

Create the /day/12 page.

The page should allow a student to:

1. Read the day's challenge
2. Understand what needs to be built
3. See acceptance criteria
4. Submit a GitHub repository or commit
5. Submit a LinkedIn post
6. Complete the daily submission

The UI should make the submission process simple and clear on mobile devices.

---

## Prompt 5 — Mobile-First Design

Optimize all three pages for a 390px mobile viewport.

Requirements:
- No horizontal scrolling
- Large readable typography
- Touch-friendly buttons
- Cards should stack on mobile
- Clear visual hierarchy
- Good spacing
- Responsive desktop layout

Test the pages at approximately:

390px × 844px

---

## Prompt 6 — Edge Cases

Add realistic UI states for:

### First Day
The student has a 0-day streak and has not completed any challenge.

### Missed Day
The student missed a previous challenge and should see a supportive recovery message.

### Empty Profile
The student has not yet added profile information.

The interface should communicate these states positively rather than displaying broken or empty-looking screens.

---

## Prompt 7 — Visual Design

Use a dark, modern developer-focused visual style.

Design principles:
- Strong contrast
- Orange accent color
- Rounded cards
- Clear typography
- Minimal visual clutter
- Subtle borders
- Strong CTAs
- Mobile-first layout

The interface should feel like a real product rather than a basic hackathon prototype.

---

## Prompt 8 — Final Testing

Test all required routes:

/
 /dashboard
/day/12

Verify:
- Routes load correctly
- No console errors
- Buttons work
- Forms accept input
- Mobile layout works at 390px
- No horizontal scrolling
- Mock data displays correctly

---

## Development Notes

The application intentionally uses mocked data because authentication, production databases and real user accounts are outside the scope of the problem statement.

The primary focus is:
- UX
- Mobile-first design
- Student motivation
- Proof of work
- Challenge progress
- Edge-case handling
- Clear submission experience
