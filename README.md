# Eventy

A Local Event Discovery Platform

## Index

1. [Introduction](#1-introduction)
   - [The Problem](#11-the-problem)
   - [Our Solution](#12-our-solution)
2. [Team & Roles](#2-team--roles)
3. [Strategy](#3-strategy)
   - [Value Proposition Canvas](#31-value-proposition-canvas)
   - [UX Personas](#32-ux-personas)
   - [Benchmarking](#33-benchmarking)
4. [Scope](#4-scope)
   - [Customer Journey Map](#41-customer-journey-map)
5. [Structure](#5-structure)
   - [Navigation Flow](#51-navigation-flow)
6. [Skeleton](#6-skeleton)
   - [Low-Fidelity Wireframes](#61-low-fidelity-wireframes)
7. [Surface](#7-surface)
   - [High-Fidelity Interfaces](#71-high-fidelity-interfaces)
   - [Interface Evolution](#72-interface-evolution)
   - [Results of the Heuristic Evaluation](#73-results-of-the-heuristic-evaluation)
   - [High Definition Interfaces](#74-high-definition-interfaces)

---

## 1. Introduction

### 1.1 The Problem

People interested in cultural, recreational, or academic activities often miss events that match their interests because information is scattered across multiple sources, social media, outdated websites, or informal channels.  
Meanwhile, local organizers struggle to promote their activities effectively due to limited marketing resources and the lack of accessible digital tools.

**Pain points include**:

- Overpaying for events that don't meet expectations
- Poor promotion and visibility of local events
- Lack of real-time updates or notifications
- Limited social interaction with attendees

### 1.2 Our Solution

Eventy was created to bridge that gap, connecting people with the experiences around them while giving visibility to local organizers.  
The app brings together event information into one simple, location-based, and personalized platform that helps users easily discover, share, and attend activities that matter to them.

Key features:

- Interactive map showing nearby events
- Personalized feed of events
- Integrated calendar and reminders
- Social sharing and attendee interaction
- Organizer tools for event creation and promotion
- Ticketing and registration for free or paid events
- Accessibility features (high contrast, adjustable text, mobility-friendly filters)

---

## 2. Team & Roles

- **Felipe Márquez** – Project Manager
- **Diego Marillán** – Analyst & Presenter
- **Francisco Cárdenas** – Designer

---

## 3. Strategy

### 3.1 Value Proposition Canvas

**Customer Segments**

- **Attendees:** Discover events, stay informed, attend activities aligned with interests
- **Organizers:** Publish events, attract attendees, collect feedback

**Gains & Pains**

- **Attendees:** Want clear, centralized information; struggle with scattered sources and missing events
- **Organizers:** Struggle with engagement, marketing, and feedback analysis

**Value Proposition**

- **Pain Relievers:** Centralized information, intuitive interface, reminders, reviews & ratings, promotion tools
- **Gain Creators:** Personalized recommendations, social interaction, calendar integration, higher visibility for local events
- **Products & Services:** Organizer panel, event search, calendar integration, notifications, map and routing integration

![Value Proposition Canvas Placeholder](./assets/Value%20Proposition%20Canvas/Value%20Proposition%20Canvas%20v2.png)

### 3.2 UX Personas

- **Diego:** Student, limited budget, seeks free/low-cost local activities  
  ![UX Personas Placeholder](./assets/persona-ux/v2/1.png)
- **Felipe:** Working professional seeking high-quality cultural/social experiences  
  ![UX Personas Placeholder](./assets/persona-ux/v2/3.png)
- **Valentina:** Organizer, aims for better visibility and engagement of her events  
  ![UX Personas Placeholder](./assets/persona-ux/v2/2.png)

### 3.3 Benchmarking

**Platforms analyzed:** Vesti, Ticketmaster, Fever, Eventrid

**Insights:**

- Gaps in local, geo-based event discovery
- Limited social or calendar features in existing platforms
- Opportunity for Eventy: regionally inclusive, personalized, and community-focused

![Benchmarking Placeholder](./assets/Benchmark/Benchmark.png)

---

## 4. Scope

### 4.1 Customer Journey Map

Key stages:

1. **Awareness:** Discover Eventy via social media/search
2. **Consideration:** Explore events via map/list, apply filters
3. **Decision:** Mark attendance, buy tickets, add to calendar
4. **Loyalty & Advocacy:** Share events, follow organizers, leave feedback

![Customer Journey Map Placeholder](./assets/Customer%20Journay%20Map/Customer%20Journey%20Map.jpeg)

---

## 5. Structure

### 5.1 Navigation Flow

The navigation flow illustrates how users move through the core sections of Eventy, ensuring intuitive access to key functionalities such as event discovery, creation, and profile management.
It provides a clear overview of the main user journeys and how different screens are connected to support a seamless experience.

Eventy’s main sections:

![Navigation Flow Placeholder](./assets/Navegation%20Diagram/Navegation%20Diagram%20Eventy-V2.png)

---

## 6. Skeleton

### 6.1 Low-Fidelity Wireframes

The low-fidelity wireframes represent the initial visual structure of Eventy, focusing on layout, information hierarchy, and core user flows.  
They are used to validate usability and navigation before moving on to high-fidelity design stages, allowing quick iteration and feedback from early testing.

Key screens include:

- Home / Event Feed
- Map View & List View
- Event Detail Pages
- Organizer Panel
- Calendar & Notifications

These early prototypes help ensure intuitive navigation and clear information flow before advancing to the final design phase.

The complete set of low-fidelity wireframes can be found in the following links:

- 📄 [PDF version](./docs/Wireframes.pdf)
- 🎨 [View on Figma](https://www.figma.com/design/3WD7RXPMW6taBvm9YXsUaM/Wireframes?node-id=0-1&p=f&t=VNTLRqJD4CHRhR73-0)

---

## 7. Surface

### 7.1 High-Fidelity Interfaces

The high-fidelity interfaces represent the final visual stage of Eventy’s design process, showcasing the complete look and feel of the platform.  
These screens incorporate visual consistency, accessibility improvements, and interactive components based on the validated low-fidelity prototypes.  
Their goal is to provide a realistic preview of the final user experience before implementation.

Key screens include:

- Home / Event Discovery: featured events, search, filters
- Event Detail: detailed information, map integration, reviews, and ticketing
- User / Organizer Profile: attended or created events, user reviews, personal data management
- Support & Help: assistance and communication with the Eventy team

  ### 7.2 Interface Evolution

  The initial versions of Eventy’s interface included a standard top navigation bar with the following options: Explore Events, Create Events With Us, Help, and Profile. As the project progressed and the scope became clearer, several adjustments were made to strengthen usability, consistency, and clarity.
  
During early iterations, event exploration relied primarily on a simple grid of cards. However, user feedback and heuristic evaluation revealed limitations in discoverability and category differentiation. We therefore expanded the interface to include clearer filtering, a category explorer, and a hybrid list/map browsing experience.

Similarly, organizer tools were initially minimal, but later expanded into a full multi-step event creation flow, including General Information, Logistics, Access/Tickets, Promotion, and Visual Identity. These additions were essential for representing actual organizer needs and completing the product story.

Furthermore, between the low-fidelity wireframes and the final high-fidelity interfaces, spacing, margins, and grid alignment were adjusted across all pages to match design standards seen in event discovery and ticketing platforms. This significantly improved readability and navigation flow.


#### Home Interface Evolution

The original home wireframe presented a simple grid with limited filtering functionality. In the high-fidelity version, a cleaner, more spacious layout was adopted with:
-A highlighted search bar
-Category shortcuts
-Featured events carousel
-A more structured recommendation system

These changes aimed to improve discoverability, reduce cognitive load, and present events more attractively from the first interaction.


#### Event Details Interface Evolution

Initially, the event detail screen provided only basic information (title, date, and description). During redesign, it was expanded into a complete event hub including:
-A full-width event banner
-A detailed event description
-A schedule/activities section
-A ticket-purchasing area
-Organizer profile preview
-Map preview and location details
-FAQs and Support panel

This transformation made the event screen more informative and aligned with real-world event platforms.


#### User Profile Interface Evolution

Early versions included only upcoming events. In the final version, the user profile evolved into a complete dashboard featuring:
-Upcoming events
-Past events
-User statistics (reviews, attendance, followers, local exploration)
-Profile editing options
-Privacy and events history shortcuts

This helped consolidate relevant user information in a single, organized space.


#### Organizer Profile & Tools Evolution

Originally absent in the first wireframes, the organizer experience was expanded into a complete management ecosystem:
-Organizer Profile (description, statistics, followers)
-Organizer Reviews
-Event creation workflow
-Event analytics
-Ticket management
-Event news publishing
-Request change form

These additions were essential to reflect the dual-user nature of Eventy.


#### Help Center Interface Evolution

The early version contained a minimal contact section. The final redesigned Help Center includes:
-A structured FAQ panel
-Expandable question cards
-A fully functional contact form with category selection
-Clear instructions and improved visual hierarchy

This evolution created a support experience consistent with modern help systems.


#### Redesign of the Navigable Prototype

During the first prototype presentation, feedback indicated that although the structure was functional, the platform lacked a cohesive identity and several essential components. It also required a clearer differentiation between attendee and organizer experiences.

This led to a major redesign, resulting in the current version:


#### Key Improvements

####✔ Consistent Cyan-Themed Visual Identity
A unified visual palette was adopted, using blues and cyans to communicate reliability, clarity, and simplicity—values essential for a community-oriented event platform.

####✔ Complete Event Creation Flow
The previous prototype only partially represented the creation process.
The new version includes 5 complete steps:
1. General Information
2. Logistics
3. Access / Tickets
4. Promotion
5. Visual Identity
   
Each step includes real components, form validations, helper text, and consistent UI patterns.

#### ✔ Expanded Organizer Tools
To represent real needs, the following tools were added:
-Ticket analytics
-Sales management
-Reviews
-Publishing event news
-Requests for changes
-Event history

#### ✔ Category Exploration
A full categories page was added to improve discoverability and align with user mental models seen in platforms like Fever or Eventbrite.

#### ✔ Improved Event Discovery
Now featuring:
-Dynamic search
-Filters
-Map / List toggle
-Recommended events
-Category shortcuts

These changes provide a more modern and efficient browsing experience.

#### ✔ More Complete User Experience
The home page, profile pages, event views, and help center were redesigned with clearer hierarchy, stronger alignment, and more intuitive interactive elements.
As design iterations progressed, each interface incorporated results from the heuristic evaluation and accessibility workshops.


### 7.2 Results of the Heuristic Evaluation

A heuristic evaluation was conducted after the mid-fidelity stage. At that point, several features—such as the organizer analytics dashboard, ticket sales view, and the Help Center—were still under development.
Despite this, Eventy already displayed a consistent identity and UI direction.
The evaluation revealed several usability issues that guided the next iteration of the design.

#### Main Issues and Solutions

| Problem                                                  | Solution                                                                |
| -------------------------------------------------------- | ----------------------------------------------------------------------- |
| Lack of visual feedback and system status indicators.    | Added loading states, success/error messages, and confirmation dialogs. |
| Inconsistent spacing, icon styles, and input components. | Introduced a unified design system with consistent components.          |
| Limited filtering options reduced discoverability.       | Added filters by date, category, price, and location.                   |
| No progress indicators during creation flows.            | Added step-by-step indicators with clear active states.                 |
| Poor accessibility in contrast and text sizes.           | Updated palette, increased font sizes, and improved readability.        |
| Lack of differentiation between event types.             | Introduced category icons and visual markers.                           |
| Missing user control (“Back”, “Cancel”, “Save Draft”).   | Implemented navigation controls across all forms.                       |
| Event and organizer flows were mixed.                    | Completely separated attendee and organizer navigation paths.           |


### 7.3. High-Fidelity Interfaces

After several iterations and incorporating the improvements identified during the heuristic evaluation, the final high-fidelity interfaces for Eventy were developed.

These interfaces were built using structured components, standardized spacing, consistent interaction states, and accessibility best practices.


#### Supported User Journeys
Attendees can:
-Explore events by date, category, or location
-View detailed event information and activities
-Purchase and manage tickets
-Follow organizers
-Receive notifications
-View their calendar
-Access a Help Center with FAQs and a contact form

#### Organizers can:
-Create events through a complete multi-step process
-Manage event logistics and ticket inventories
-Publish news and updates
-View event analytics (views, sales, engagement)
-Interact with reviews
-Manage requests for changes
-Maintain a professional organizer profile

The final high-fidelity designs represent Eventy’s complete ecosystem and reinforce its core goal: connecting communities through accessible, intuitive, and visually consistent event discovery tools.

The complete set of high-fidelity interfaces can be accessed through the following links:

- 📄 [PDF version](./docs/Mock%20ups.pdf)
- 🎨 [View on Figma](https://www.figma.com/design/hBHZViB4UoFl7QPvhv5x88/Mock-up?t=BEeUelzFHUvAH7xT-1)
