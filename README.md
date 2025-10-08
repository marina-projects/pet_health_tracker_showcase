# Happy Pet. Health tracker

**An interactive web application for pet owners**

[Live Demo on Netlify](https://pet-health-tracker.netlify.app/)

---

*This is a documentation-only repository. Source code is private. For code review access, please contact me: marina.simaganova@gmail.com*

---



> Helping pet owners track their pets development, vaccinations, treatments and other events. Designed with care and attention to details.  
> Built with **React, Redux, and Firebase**, featuring a responsive UI and a scalable architecture ready for mobile expansion with React Native.

---

## Overview

**Happy Pet** is a modern web application that helps pet owners to track and check all important health-related events, reminds owners about vaccinations and treatments.

### Key features
- Event history and visual timeline of past and upcoming procedures  
- Vaccination and treatment reminders  
- Support for multiple pets
- Pet cards with editable info and photos  
- Explore section with useful care articles  
- User account management
- Admin account management
- Multi-language support (English, Serbian, Russian)

---

## Architecture and Technologies

The project follows scalable React application principles, with clear separation between UI and business logic.

### Frontend
- React
- Redux Toolkit
- Emotion + MUI ThemeProvider for unified design system
- React Responsive for adaptive layouts (mobile / desktop)
- React Router v6
- i18next for internationalization  

### Backend & Database
- Firebase Authentication  
- Firestore Database
- Firebase Storage for pet photos and files  
- Firestore Security Rules with admin role support

---

## Main Modules

| Module | Description |
|--------|--------------|
| **Onboarding** | Step-by-step setup for new pets: pet, gender, name, breed, date of birth |
| **Main Screen** | Closest Reminders, current health overview, new articles |
| **Events** | List of all past and upcoming procedures |
| **Add Event** | Form for adding vaccinations, treatments and other events (including custom ones) |
| **Explore** | Knowledge base with pet care articles |
| **Account** | User and pet management screen |

---

## Implementation Highlights

- Centralized state via Redux store (`usersSlice`, `petsSlice`, `eventsSlice`, etc)  
- Custom hooks for logic separation (`useFetchPets`, `usePetData`, `useAuth`, etc)  
- Animated pet card transitions with swipe effect  
- Minimal, clean responsive UI using grid layout  

---

## Roadmap

- React Native mobile app version  
- AI assistant for personalized pet care tips
- Integration with Telegram for getting reminders and notifications
- Integration with Google Calendar 
- Expanded language support (adding all EU languages for marketing outreach)
- Adding files to events (like med analysis)
- Adding pet's weight statistics

---

## Author

**Marina Romanova**  
React/Redux Developer & Product Designer  
Novi Sad, Serbia  
[LinkedIn](https://www.linkedin.com/in/yellowmarine/) · [GitHub](https://github.com/marina-projects)

---

## Screenshots
<div>
  <img src="/screenshots/mobile_registration.png" alt="Mobile registration screen" width="25%">
  <img src="/screenshots/mobile_pets.png" alt="Mobile pets list" width="25%">
  <img src="/screenshots/mobile_events.png" alt="Mobile events screen" width="25%">
  <br><br>
  <img src="/screenshots/desktop_add_event.png" alt="Desktop add event screen" width="75%">
</div>


---

## Contributions and Feedback
Thanks for checking out this project! Feel free to add, remove, change, and comment this App. I'll appreciate any thoughts or ideas that about how to make it better.
