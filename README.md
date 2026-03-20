# TravelSnap

**Branch:** `lesson-3`

## 🎯 Practical Task: Lesson 3 — State, Hooks, and Interactivity

If you completed all exercises above - you have most of the assignment done. Make sure:

### >> Core task - to submit

1. `HomeScreen` has `useState` with an empty trips array.
2. Form with 4 fields: `title`, `destination`, `date`, `rating`.
3. 'Add' button -> `handleAddTrip` -> new `TripCard`.
4. Trip list displayed via `.map()` with `TripCard`.
5. Every `TripCard` has `key={trip.id}`.
6. Rating: `TextInput` -> `Number()` -> prop (number).
7. Validation: empty fields do NOT add a card.

### /!\ Extension (extra points)

1. Delete button in `TripCard` (`onDelete` prop).
2. Rating validation: only 1-5.
3. Display trip count above list.
4. Date validation: YYYY-MM format.

---

## 🚀 How to run this code?

If you want to see the completed solution for this lesson:

1. Clone the repository and switch to the `lesson-3` branch.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the project:
   ```bash
   npx expo start
   ```
