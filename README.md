# Spacepulse
# 🎓 Campus Suite: SpacePulse + TrackIn

One web page that helps students with two everyday campus problems:

- **📡 SpacePulse** finds a free classroom or lab.
- **🧭 TrackIn** plans attendance so you know which classes you can safely skip.

A **🏠 Today** screen brings both together.

---

## How to open it

1. Save `index.html` on your computer or phone.
2. Double-click it. It opens in any browser (Chrome, Edge, Safari, Firefox).

There is nothing to install and no account to make. It works offline, except for the font, and a normal font is used if you have no internet.

To open a tab directly, add `#sp` (SpacePulse) or `#ti` (TrackIn) to the end of the page address.

---

## What's inside

### 🏠 Today
- A greeting with the date and time, and a picker for **your class**.
- **Right now:** the class you are in, or the next one, with its room.
- **Free rooms:** how many rooms are free right now, and which one stays free longest.
- **Attendance:** your overall percentage and your tightest subject.
- Quick buttons to find a room, plan absences, check a leave, or open your subjects.
- **Today's schedule** with the current class highlighted.

### 📡 SpacePulse (free room finder)
- Type what you need in plain English, for example *"AC room on the ground floor for me and my 3 friends for 2 hours"*. It understands floor, AC, number of people, duration, "after lunch" and "tomorrow at 10 am".
- Every room gets a **SpaceFit score out of 100**. A room scores well when it is free long enough, on the right floor, air-conditioned if you asked, and big enough.
- If no single room fits, it suggests an **Uninterrupted Work Route**: use one room, then move to another 5 minutes before the next class starts.
- A **day timeline** shows every room's classes as a bar. Tap a bar to jump to that time.
- Filters for date, time, minutes needed, minimum seats, AC only and "Quiet" (prefers rooms free for longer).
- Tap the ☆ on a room to pin it. Pinned rooms are remembered on your device.
- The **📍 Now (live)** button keeps the page updated every 30 seconds. Press `/` to jump to the search box.

### 🧭 TrackIn (attendance planner)
- Pick your class and your target: **75%, 80% or 90%**.
- **📚 Subjects:** for each subject you see your percentage, safe absences left, classes left, the best possible final result, and your **point of no return**. Type your attended and conducted numbers, or use **Sample numbers** to try it out. A "What if I miss…" slider shows the effect of skipping.
- **📅 Daily Plan:** the next 14 class days, each marked *Flexible*, *Careful*, *Attend* or *Must attend*, with the room for every class. **Copy this plan** makes a message you can paste into WhatsApp.
- **🛡️ LeaveSafe:** choose leave dates and it tells you if you can take them without dropping below your target. If not, it suggests the earliest safe dates.
- **Dates & holidays** (optional) lets you set the semester start and end, and add holidays.
- Your numbers, class and target are saved on your device only.

---

## Things to know

- **"Free" means "not in the timetable."** A room shown as free is not booked for a class, but it may still be in use for something else.
- **Room details are sample data.** AC, number of seats and room type were not in the timetables, so examples were filled in. Please replace them with real details.
- **Projections are planning aids, not official records.** Detention and eligibility decisions rest with the college.
- The 8 timetables loaded are II BME, II ECE-DS A, III BME, III ECE-A, III ECE-B, III ECE-DS, IV ECE-A and IV ECE-B (Monday to Friday, 9:00 AM to 4:50 PM), covering 12 rooms.

---

## How to update it

Open `index.html` in a text editor (Notepad works) and search for these names near the top of the code:

| Name | What it holds | When to edit |
|---|---|---|
| `SEC` | The timetable, subject names and home room of each class | When timetables change |
| `R` | The room list with type, seats and AC (`ac:1` = AC, `ac:0` = no AC) | To correct the sample room details |

Save the file and refresh the browser to see your changes.

---

## Built with

Plain HTML, CSS and JavaScript in a single file. No frameworks, server or database.
