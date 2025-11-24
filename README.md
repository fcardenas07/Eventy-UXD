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

<img width="1372" height="708" alt="Screenshot 2025-11-24 at 4 41 27 AM" src="https://github.com/user-attachments/assets/b4b103e9-feca-48a3-a814-1da09b37a19d" />

<img width="904" height="507" alt="Screenshot 2025-11-24 at 4 43 57 AM" src="https://github.com/user-attachments/assets/f78b3f60-3e42-49cb-b1bc-b7efbc17eae2" />

#### Event Details Interface Evolution

Initially, the event detail screen provided only basic information (title, date, and description). During redesign, it was expanded into a complete event hub including:
-A full-width event banner
-A detailed event description
-A schedule/activities section
-A ticket-purchasing area
-Organizer profile preview
-Map preview and location details
-FAQs and Support panel

<img width="1415" height="799" alt="Screenshot 2025-11-24 at 4 46 25 AM" src="https://github.com/user-attachments/assets/71172c76-7502-4f5d-b475-55bd16f6c5b4" />

<img width="613" height="848" alt="image" src="https://github.com/user-attachments/assets/bda5a8b8-c1eb-454e-a488-9bb7f91ef922" />


This transformation made the event screen more informative and aligned with real-world event platforms.


#### User Profile Interface 

We added User profiles
-Profile editing options
-Privacy and events history shortcuts

<img width="604" height="340" alt="Screenshot 2025-11-24 at 4 47 59 AM" src="https://github.com/user-attachments/assets/054a4b94-619b-47f8-a64b-6c7030594e03" />

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

<img width="861" height="485" alt="Screenshot 2025-11-24 at 4 48 39 AM" src="https://github.com/user-attachments/assets/4f5bf1bc-5428-41e1-9e56-3335030ddd94" />

<img width="593" height="335" alt="Screenshot 2025-11-24 at 4 50 12 AM" src="https://github.com/user-attachments/assets/470a1978-7335-46ac-831c-d7ea51da0a56" />

<img width="593" height="332" alt="Screenshot 2025-11-24 at 4 50 51 AM" src="https://github.com/user-attachments/assets/171759f6-792f-465a-adbc-e3aa7e3cac97" />

<img width="592" height="334" alt="Screenshot 2025-11-24 at 4 51 16 AM" src="https://github.com/user-attachments/assets/880c9a5b-0873-4d22-84b0-1d4ec664a2ac" />

<img width="594" height="334" alt="Screenshot 2025-11-24 at 4 51 31 AM" src="https://github.com/user-attachments/assets/fc9e2834-fc22-428f-b1ea-1b9a309f236b" />

<img width="594" height="334" alt="Screenshot 2025-11-24 at 4 51 45 AM" src="https://github.com/user-attachments/assets/ce0724ce-2d05-4550-aae6-d4ad2114b5fe" />

<img width="591" height="333" alt="Screenshot 2025-11-24 at 4 52 01 AM" src="https://github.com/user-attachments/assets/6bf14b97-e2f1-4519-a829-468511c3466e" />

<img width="593" height="333" alt="Screenshot 2025-11-24 at 4 52 18 AM" src="https://github.com/user-attachments/assets/a564b48c-ddcc-45ca-afa9-a6d692e8fd22" />

<img width="652" height="365" alt="Screenshot 2025-11-24 at 4 53 03 AM" src="https://github.com/user-attachments/assets/71dede68-8442-473a-88cf-fc510854510d" />


These additions were essential to reflect the dual-user nature of Eventy.


#### Help Center Interface Evolution

The early version contained a minimal contact section. The final redesigned Help Center includes:
-A structured FAQ panel
-Expandable question cards
-Clear instructions and improved visual hierarchy

<img width="652" height="368" alt="Screenshot 2025-11-24 at 4 53 38 AM" src="https://github.com/user-attachments/assets/48756de6-8066-41c8-9591-06f45d0687fd" />


This evolution created a support experience consistent with modern help systems.


#### Redesign of the Navigable Prototype

During the first prototype presentation, feedback indicated that although the structure was functional, the platform lacked a cohesive identity and several essential components. It also required a clearer differentiation between attendee and organizer experiences.

This led to a major redesign, resulting in the current version:

<img width="872" height="489" alt="Screenshot 2025-11-24 at 4 55 19 AM" src="https://github.com/user-attachments/assets/5e270ea0-a0ac-4f0e-b5a7-067e27625472" />

<img width="796" height="447" alt="Screenshot 2025-11-24 at 4 55 47 AM" src="https://github.com/user-attachments/assets/2e09eb50-38bb-4b4b-8021-f70059a350ee" />

#### Key Improvements

✔ Consistent Cyan-Themed Visual Identity
A unified visual palette was adopted, using blues and cyans to communicate reliability, clarity, and simplicity—values essential for a community-oriented event platform.

✔ Complete Event Creation Flow
The previous prototype only partially represented the creation process.
The new version includes 5 complete steps:
1. General Information
2. Logistics
3. Access / Tickets
4. Promotion
5. Visual Identity

<img width="871" height="491" alt="Screenshot 2025-11-24 at 4 56 41 AM" src="https://github.com/user-attachments/assets/3a7ab675-b037-441b-b3e9-91f34ac9e526" />
   
Each step includes real components, form validations, helper text, and consistent UI patterns.

✔ Expanded Organizer Tools
To represent real needs, the following tools were added:
-Ticket analytics
-Sales management
-Reviews
-Publishing event news
-Requests for changes
-Event history

✔ Category Exploration
A full categories page was added to improve discoverability and align with user mental models seen in platforms like Fever or Eventbrite.

✔ Improved Event Discovery
Now featuring:
-Dynamic search
-Filters
-Map / List toggle
-Recommended events
-Category shortcuts

These changes provide a more modern and efficient browsing experience.

✔ More Complete User Experience
The home page, profile pages, event views, and help center were redesigned with clearer hierarchy, stronger alignment, and more intuitive interactive elements.
As design iterations progressed, each interface incorporated results from the heuristic evaluation and accessibility workshops.


### 7.2 Results of the Heuristic Evaluation

A heuristic evaluation was conducted after the mid-fidelity stage. At that point, several features—such as the organizer analytics dashboard, ticket sales view, and the Help Center—were still under development.
Despite this, Eventy already displayed a consistent identity and UI direction.
The evaluation revealed several usability issues that guided the next iteration of the design.

#### Main Issues and Solutions

| Problem                                                  | Solution                                                                |
| -------------------------------------------------------- | ----------------------------------------------------------------------- |
| Inconsistent spacing, icon styles, and input components. | Introduced a unified design system with consistent components.          |
| Limited filtering options reduced discoverability.       | Added filters by date, category, price, and location.                   |
| No progress indicators during creation flows.            | Added step-by-step indicators with clear active states.                 |
| Poor accessibility in contrast and text sizes.           | Updated palette, increased font sizes, and improved readability.        |
| Lack of differentiation between event types.             | Introduced category icons and visual markers.                           |
| Missing user control (“Back”, “Cancel”, “Save Draft”).   | Implemented navigation controls across all forms.                       |
| Event and organizer flows were mixed.                    | Completely separated attendee and organizer navigation paths.           |

<img width="515" height="291" alt="Screenshot 2025-11-24 at 4 58 06 AM" src="https://github.com/user-attachments/assets/749a4b6b-95c2-4e67-9583-436f2d971f16" />

<img width="671" height="380" alt="Screenshot 2025-11-24 at 4 59 14 AM" src="https://github.com/user-attachments/assets/a0051317-aae5-4be1-9df4-d7ff15aae101" />

<img width="925" height="519" alt="Screenshot 2025-11-24 at 4 59 44 AM" src="https://github.com/user-attachments/assets/f53b8df5-eaf8-4d14-a85f-fe476498ea04" />

### 7.3. High-Fidelity Interfaces

After several iterations and incorporating the improvements identified during the heuristic evaluation, the final high-fidelity interfaces for Eventy were developed.

These interfaces were built using structured components, standardized spacing, consistent interaction states, and accessibility best practices.

<img width="919" height="518" alt="Screenshot 2025-11-24 at 5 00 36 AM" src="https://github.com/user-attachments/assets/a8ff7cca-75ca-40af-9ce2-9c4c4df685cf" />

#### Supported User Journeys
Attendees can:
-Explore events by date, category, or location
-View detailed event information and activities
-Purchase and manage tickets
-Follow organizers
-Receive notifications
-View their calendar
-Access a Help Center with FAQs and a contact form

<img width="895" height="46" alt="Screenshot 2025-11-24 at 5 01 59 AM" src="https://github.com/user-attachments/assets/29c2274d-c92f-4a9c-b169-5c277064dffd" />

<img width="788" height="445" alt="Screenshot 2025-11-24 at 5 02 31 AM" src="https://github.com/user-attachments/assets/1737af44-0b13-467e-bd8a-2be7d711ba0e" />

<img width="551" height="139" alt="Screenshot 2025-11-24 at 5 03 04 AM" src="https://github.com/user-attachments/assets/07698db1-3577-4b34-8bcc-3143868d0949" />

#### Organizers can:
-Create events through a complete multi-step process
-Manage event logistics and ticket inventories
-Publish news and updates
-View event analytics (views, sales, engagement)
-Interact with reviews
-Manage requests for changes
-Maintain a professional organizer profile

<img width="643" height="31" alt="Screenshot 2025-11-24 at 5 01 04 AM" src="https://github.com/user-attachments/assets/bef8d7ea-eb18-42d4-8191-7742c2d20c40" />

<img width="499" height="559" alt="Screenshot 2025-11-24 at 5 01 31 AM" src="https://github.com/user-attachments/assets/7c342e29-af12-453f-9ebf-f2be21dbcb32" />

The final high-fidelity designs represent Eventy’s complete ecosystem and reinforce its core goal: connecting communities through accessible, intuitive, and visually consistent event discovery tools.

The complete set of high-fidelity interfaces can be accessed through the following links:

- 📄 [PDF version](./docs/Mock%20ups.pdf)
- 🎨 [View on Figma](https://www.figma.com/design/hBHZViB4UoFl7QPvhv5x88/Mock-up?t=BEeUelzFHUvAH7xT-1)
