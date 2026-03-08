# Dear Me — Mental Wellness App (UX/UI Project)

A full UX/UI design project for **Dear Me** - a mobile mental wellness companion app for tracking mental health and building positive habits. The project went through two complete design iterations, from user research and paper prototyping to hi-fi Figma design and HTML/CSS implementation.

---

## Tech Stack

- **Figma** - hi-fi interactive prototype (Iteration 2)
- **HTML5 / CSS3 / Bootstrap 5.3** - final UI implementation (Iteration 2)
- **Bootstrap Icons + Google Fonts (Fredoka)** - iconography and typography
- **Paper prototyping** - lo-fi wireframes and storyboards (Iteration 1)

---

## Project Structure

### UX Phase — User Research & Analysis

**User Analysis**
Three user groups identified: regular users (mental health maintenance/improvement), mental health professionals (therapists/counselors), and administrators. Primary target: women aged 18–25, digitally literate, Balkan region with global expansion potential.

**Personas**
- *Danica Katić* (33, programmer, Novi Sad) — maintains mental health through meditation and habit tracking
- *Hristina Trajkova* (22, student, Macedonian exchange student in Belgrade) — managing anxiety and building new social connections
- *Dr. David Ćopić* (42, psychotherapist, Belgrade) — professional user supporting clients through the app

**Task Analysis — 4 core tasks:**
1. Setting and tracking personal goals (with virtual reward system)
2. Mood journaling (emoji selection + free text, daily)
3. Crisis emotional regulation (one-click "Calm me" / PANIC mode with breathing exercises and expert contact)
4. Community support (replying to posts, sharing resources)

**Domain Analysis**
5 entities: Korisnik, Dnevnik raspoloženja, Cilj, Preporuke, Statistika - with ER diagram and 1-N/N-1 relationships.

**Requirements**
- Multilingual: Serbian, English, Macedonian
- Android/iOS, offline support
- Accessibility (larger fonts, contrast)
- Virtual pet reward system (earn coins, customize pet)
- Crisis/panic mode with fast expert access

---

## Iteration 1 - Lo-Fi Paper Prototype

Hand-drawn wireframes and storyboards for 3 scenarios (Danica: mood journal, Hristina: add goal, David: reply in community). Usability test conducted with physical paper screens.

**Test findings:**
- "Start" button on homepage was confusing - users clicked it instead of "Mood Journal"
- Goal proof-upload screen had too much unnecessary content
- Animal-shaped icons were not intuitive enough

**Changes made for Iteration 2:**
- Removed/renamed "Start" button
- Simplified goal completion flow (removed separate proof screen)
- Replaced animal icons with standard icons

---

## Iteration 2 - Hi-Fi Figma Prototype + HTML Implementation

**Figma Prototype (Team):**
🔗 [View on Figma](https://www.figma.com/proto/CwY8lWmETNzF1snYFTpa5Y/Untitled?node-id=23-286&t=yeBk1ArmO1dbUx5p-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=23%3A286&show-proto-sidebar=1)

Color palette: warm peach/orange tones with teal accents and dark green text - chosen to convey warmth, positivity, and calm. Retro-style design aesthetic.

**HTML/CSS Screens (Individual - Milica):**

| File | Screen |
|------|--------|
| `homepage.html` | Home dashboard - mascot, motivational quote, Meditate/Breathe/Journal nav, Goals & Calm me buttons |
| `feeling.html` | Mood check-in - 6 emotion buttons + free-text journal entry |
| `goal.html` | Add a goal - text input + save |
| `community.html` | Community feed - posts with Reply buttons |

**Usability test findings (Iteration 2):**
- Text boxes for mood entry were all the same color - users didn't notice the input field
- "Messages" vs "Community" distinction on David's (professional) screen was unclear

**Changes identified:**
- Differentiate text box colors on mood entry screen
- Remove "Messages" button from professional dashboard to reduce confusion

---

## Authors
- Milica Jocić RAF, 2024/25
- Marta Šuljagić RAF, 2024/25
