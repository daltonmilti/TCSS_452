# Synchro Studio : Rebuilding the Flow

![Logo Placeholder]

## The Destroyers
##### Aileen Rosas
##### Bill Lactaoen
##### Claire Nguyen
##### Dalton Miltimore
##### Evan Tran

---

## Problem and Design Overview

Synchro Studio's interface presents several usability barriers for traffic engineers and planners. Users face
inefficiencies when navigating the Scenario Manager, incosistent menu layouts, and unintuitive data input
workflows. These issues hinder productivity and create a steep learning curve, especially for new users.

Our redesign aims to resolve these pain points by creating a cohesive, intuitive interface. This includes:
- A Quick Access Pop-Up Bar for frequently used tools.
- Click-based map interactions for direct data input.
- Consistent UI layout across all setting menus

![Initial Prototype]

---

## Design Walkthrough

### Adding Two Left Turn Lanes (Novice Task)

**Context:** A user wants to modify traffic flow at an intersection by adding left-turn lanes. This is a mid-complexity
 task common in congestion mitigation.

**Visuals & Walkthrough:**
Users left-click a road segment to bring up lane settings. A streamlined menu allows for quick adjustment of turning
lanes. The system prevents users from adding more turn lanes than possible.

**Design Insight:** The Interface was generally intuitive, though participants were briefly confused by secondary menu 
triggered on hover.

**Change Made:** We revised the interaction to provide better feedback and consider switching to click-based triggering.

---

### Customizing QuickBar with Phasing Settings (Experienced Task)

**Context:** An experienced user wants to add Phasing Settings to their QuickBar to improve workflow efficiency in coordinating
traffic lights.

**Visuals and Walkthrough:** 
Clicking the customization buttons "+" or "-" opens the QuickBar editor. Users click on the tool they want. A green arrow confirms 
action, but early testing revealed confusion.

**Design Insight:** Users were unsure what the green arrow meant.

**Change Made:** We added a visible label and message confirming the action to clarify user feedback.

---

## Design Research and Key Insights

### Research Summary

**Goals:**
Understand user pain points and identify usability bottlenecks in Synchro Studio.

**Methods:**
- Survey (2 responses)
- 2 interviews (10 minutes each)
- Participants: students in TCE 327 with real usage exerience.

**Rationale:**
These methods helped uncover issues experienced by novice and frequent users alike, guiding our redesign priorities.

### Key Insights

Insight 1: Users Avoid Unfamiliar Tools
**Emergence:** Students reported using only what was taught in class and ignoring unexplained features.
**Evidence:** "I don't touch the reports or random extra tabs because I don't know what they do."
"Any other settings, not useful — we're not taught them."
"There are a bunch of things in the menus I've never clicked."
**Impact:** We embedded tooltips, clearer icon labels, and simplified menues to promote discoverability without
overwhelming users.

#### Insight 2: UI Feels Overwhelming
**Emergence:** Students described the interface as bloated and visually cluttered, especially for first-time users.
**Evidence:** "There's just too much going on and not enough help."
"Every setting is there, but it's overwhelming when you're new."
"You have to go through 3 or 4 menues just to change one little thing."
**Impact:** We consolodated tool menus, introduced a customizable QuickBar, and emphasized clean visual grouipings for
better hierarchy.

#### Insight 3: Tasks Are Tedious and Fragmented
**Emergence:** Students felt that even small adjustments took too long, with constant back-and-forth between menus
and settings.
**Evidence:** "It's not loading slow — it's just too many steps over and over"
"I make a small change, and it barely does anything. Then I have to flip between tabs to see if it helped."
"You need 3-4 tabs just to edit something small for 30 minutes."
**Impact:** We introduced direct map-based editing and feedback indicators to reduct context switching and give
users faster results from their actions.

---

## Iterative Design and Key Learnings

### Process Summary


---

## Technical and Soft Skills Gained

### Technical Skills


### Soft Skills
