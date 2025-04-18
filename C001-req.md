# 🏥 Medical Appointment Booking Application

Build A React-based web application for scheduling and managing doctor appointments. The application includes multiple pages, data persistence, interactive UI elements, routing, and visual representation using charts.

---

## 🔝 Navbar

- Visible on all pages (including error routes)
- Includes:
  - Site Logo & Name (as per Figma)
  - 4 Navigation Menus (as per Figma)
  - A Button on the right (as per Figma)

---

## 🔚 Footer

- Visible on all pages **except** error routes
- Includes:
  - Centered Logo
  - Navigation Menus (as per Figma)
  - 4 Social Icons (redirect to developer's personal profiles)

---

## 🏠 Homepage

### ➤ Banner Section

- Gradient background with border (as per Figma)
- Center-aligned heading & text (as per Figma)
- Two positioned images (as per Figma)

### ➤ Doctors Section

- Center-aligned heading & text (as per Figma)
- Display 6 doctor cards in a 3x2 grid
- Each card includes:
  - Doctor image
  - Name
  - Education
  - Speciality
  - Experience
  - Registration Number
  - “View Details” button (navigates to doctor details route)

### ➤ Success Section

- Display 4 square cards (as per Figma) with:
  - Icon
  - Number
  - Card Title

---

## 👨‍⚕️ Doctor Details Page

- Page Info Card titled “Doctor’s Profile Details” with a slogan (as per Figma)
- Doctor Info Section:
  - Left-aligned image
  - Name, Education, Specialities, Designation, Workplace, Fee
- Availability Section (array of days)
- Appointment Card includes:
  - Availability Badge
  - “Book Now” Button

### ➤ Book Now Button Behavior

- If user **has not** booked:
  - Create an appointment
  - Show a success toast with doctor name
  - Redirect to Booking Page
- If user **already** booked:
  - Show error toast
  - Do not proceed

---

## 📅 Bookings Page

- Show all booked appointments in 1-column format (as per Figma)
- Each appointment card includes:
  - Doctor Name
  - Fee
  - Education
  - Speciality
  - “Cancel Appointment” Button
- If **no appointments** found:
  - Show heading & a button to navigate to Homepage
- Appointment state should **persist on page reload**
- Cancel button removes the appointment

---

## 📝 Blogs Page

Design a blogs page to answer the following:

1. What is `useState` and how does it work in React?
2. What is the purpose of `useEffect` in React?
3. What is a custom hook in React and when should you use one?
4. Difference between controlled and uncontrolled components? Which one is better?
5. Tell us something about `useFormStatus()` (explore and explain)

---

## ❌ Error Page

- Displayed for all invalid routes (e.g., `/contacts`)
- Navbar should be visible
- Footer should **not** be visible
- Button to redirect users to Homepage

---

# Challenge Requirements

## 📊 Recharts

- Visualize appointment fees using **Recharts** (as per Figma)
- Canceling appointments should update the chart
- If no appointments exist, do **not** show chart

---

## 🔢 Counting Animation

- Use [`react-countup`](https://www.npmjs.com/package/react-countup) for counting animation on the Homepage

---

### ➤ Logo & Title

- Add Site Logo & Website Title

### ➤ Invalid Dynamic Routes

- If invalid route visited (e.g., `/doctors/invalid-id`), show error message

### ➤ Redirection & Loading States

- Show a loading animation  on every route change
- App must not crash on page reload
- Show fallback loader during data fetch on any page reload

---

## ✨ Optional Features

### ➤ Validate Booking Based on Availability

- If today’s date doesn’t match doctor’s availability:
  - Show “Doctor is unavailable today”
  - Show “Unavailable” badge on doctor cards

### ➤ Dynamic Title using `useLocation()`

- Change title dynamically:
  - Booking Page → `Booking`
  - Doctor Details → Doctor’s Name
- **Do not** use third-party NPM packages

---

## ✅ Notes

- Have to work with the assigned Category.
- Minimum 10 Github Commits
- No Lorem Ipsum
- Image / video / resources will be relevant to the site
- Make your project responsive

---

Happy Coding! 🚀
