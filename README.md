 🏥 Clinic Appointment Calendar

A responsive frontend-only appointment calendar built with **React + Vite** to help front desk staff at clinics manage doctor appointments.

---



 Login 
. Simple email/password login
. Hardcoded credentials:
   Email: `staff@clinic.com`
   Password: `123456`
 Redirects to calendar view on successful login


Desktop:
 Month view calendar (Google Calendar-like)
 Displays:
   Patient names
   Appointment times (compact)
 Click on a date to add/edit appointments
 Mobile:
     One-day-at-a-time view
     Date picker to jump to any date
     Vertical scroll to view other days


 Each appointment includes:
   Patient (select dropdown)
   Doctor (select dropdown)
   Time (time picker)
 Uses a fixed list of patients and doctors (static)


 Appointments stored in `localStorage`
 Automatically persists across reloads


 Responsive design (Mobile + Desktop)
 Optional dark mode support
 Optionally filter appointments by doctor

---
