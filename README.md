# Strike Homepage

A modern, responsive learning-platform homepage with an interactive **Thunder Sale** experience designed to make the user journey more engaging than a traditional static landing page.

---

## 1. Project Overview

**Strike Homepage** is a frontend-focused web experience inspired by the visual and interactive style of modern learning platforms.

The project brings together course and learning content, membership plans, mentors, testimonials, FAQ, responsive navigation, and an interactive **Thunder Sale** experience with countdown and offer reveal.

The main focus is creating a clear and engaging user journey rather than presenting a purely static landing page. The Thunder Sale adds an interactive element where users can discover the sale, view the countdown, interact with the sale panel, and reach the offer/coupon reveal.

The project was developed as a hackathon submission with emphasis on **user experience, responsive design, component organization, and meaningful frontend interaction**.

---

## 2. Project Idea

Many learning-platform landing pages primarily provide information through static sections. The idea behind this project was to create a homepage that feels more interactive while keeping the information easy to explore.

The project combines a structured learning-platform homepage with an interactive promotional experience.

### Core Idea

The homepage allows users to:

1. Understand the platform through the hero section.
2. Explore learning and course-related content.
3. View membership plans and platform benefits.
4. Learn about mentors and see testimonials.
5. Explore common questions through the FAQ.
6. Discover the **Thunder Sale** experience.
7. Interact with the sale countdown and reveal flow.
8. Reach a simulated offer/coupon reveal.

The **Thunder Sale** acts as the main interactive element. Instead of showing only a promotional banner, the sale is presented as an experience that encourages users to interact with the interface.

---

## 3. User Flow

```text
Visit Homepage
      |
      v
Explore Hero & Navigation
      |
      v
Explore Courses & Learning Content
      |
      v
View Membership Plans
      |
      v
Explore Mentors & Testimonials
      |
      v
Read FAQ / Additional Information
      |
      v
Discover Thunder Sale
      |
      v
Interact with Sale + Countdown
      |
      v
Reveal Offer / Coupon Experience
```

### User Journey

1. **Landing** — The user enters the homepage and sees the main platform message and navigation.
2. **Exploration** — The user moves through learning, course, and platform-value sections.
3. **Membership** — The user explores available membership plans.
4. **Social Proof** — Mentors and testimonials provide additional platform context.
5. **Information** — The FAQ answers common questions.
6. **Sale Discovery** — The user encounters the Thunder Sale experience.
7. **Interaction** — The user interacts with the sale panel and countdown.
8. **Reveal** — The user reaches the simulated offer/coupon reveal.

---

## 4. Feature Checklist

### Homepage

- [x] Responsive homepage layout
- [x] Navigation bar
- [x] Hero section
- [x] Structured learning/content sections

### Learning & Membership

- [x] Course-related sections
- [x] Membership plans
- [x] Why Choose Us / platform value section
- [x] Mentors
- [x] Testimonials
- [x] FAQ
- [x] Progress/content-related UI

### Thunder Sale Experience

- [x] Interactive Thunder Sale experience
- [x] Sale discovery interaction
- [x] Countdown timer
- [x] Sale panel
- [x] Interactive reveal flow
- [x] Offer/coupon logic
- [x] Sale-related visual feedback

### UI & User Experience

- [x] Reusable React components
- [x] Reveal/animation effects
- [x] Responsive styling
- [x] Static visual assets
- [x] Client-side interactive behavior
- [x] Organized sale-specific components

---

## 5. Technical Approach

### Frontend Architecture

The project is built using **Next.js and React with TypeScript/TSX**. The application is divided into reusable components instead of placing the entire homepage in a single file.

### Component-Based Design

Major homepage sections are separated into individual React components, including Hero, Navbar, Membership, What We Offer, Why Choose Us, Mentors, Testimonials, FAQ, and Footer.

The Thunder Sale functionality is further separated into dedicated components under `components/sale/`.

### Interactive Experience

React client-side logic and hooks are used for interactive behavior such as the countdown, sale interaction, offer/reveal behavior, and coupon logic.

### Styling & Responsiveness

The project uses **Tailwind CSS** for styling and responsive layouts so the interface adapts to different screen sizes.

### Static Assets

Images, icons, and other static visual resources are stored inside the `public/` directory.

### Project Organization

```text
app/                  Application entry and global styling
components/           Reusable homepage sections
components/sale/      Thunder Sale components
hooks/                Reusable client-side hooks
lib/                  Sale logic and utility functions
data/                 Website content/data
public/               Images, icons and static assets
```

---

## 6. Project Setup

### Prerequisites

- Node.js
- pnpm

The project contains a `pnpm-lock.yaml` file, so **pnpm** is the intended package manager.

### Clone the Repository

```bash
git clone https://github.com/saloni-mehra/strike-homepage.git
cd strike-homepage
```

### Install Dependencies

```bash
pnpm install
```

### Start the Development Server

```bash
pnpm dev
```

Open:

```text
http://localhost:3000
```

### Production Build

```bash
pnpm build
```

---

## 7. Technical Highlights

### Reusable Components
The homepage is divided into focused React components, making the codebase easier to navigate and maintain.

### Interactive Sale Architecture
The Thunder Sale experience is separated into dedicated components and hooks rather than being tightly coupled to the homepage.

### Client-Side Interaction
React state and hooks are used for interactive behavior such as the countdown and sale/reveal experience.

### Responsive Design
The interface uses responsive layouts to keep the main experience usable across different screen sizes.

### Organized Assets
Static images and icons are kept inside `public/`, while application logic is separated into components, hooks, libraries, and data.

---

## 8. Known Limitations

This project is primarily a **frontend hackathon experience**.

- There is no production backend.
- There is no real payment gateway or transaction processing.
- There is no production authentication system.
- The Thunder Sale coupon/offer is a simulated frontend interaction.
- The sale timer and related interactions are designed for the demo experience rather than a production commerce system.
- Much of the displayed content and visual assets are static/demo-oriented.

These limitations are within the current hackathon scope and do not affect the project's primary objective of demonstrating a polished learning-platform homepage and engaging interactive frontend experience.

---

## 9. Hackathon Scope

During the hackathon, the project prioritized:

- Clear and engaging user journey
- Responsive homepage design
- Component-based frontend architecture
- Reusable React components
- Interactive Thunder Sale experience
- Countdown and reveal interactions
- Clean project organization
- Complete source code and static assets

The Thunder Sale was treated as the main interactive experience to differentiate the homepage from a purely informational landing page.

---

## 10. Demo

**Live Demo:** `https://strike-homepage.vercel.app/`

---

## 12. Conclusion

Strike Homepage demonstrates how a learning-platform landing page can combine structured content with an interactive frontend experience.

The project focuses on **responsive design, reusable React architecture, clear user flow, and the Thunder Sale interaction** as its key engaging feature.
