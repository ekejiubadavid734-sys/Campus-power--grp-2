# CAMPUSPULSE
## Product Requirements Document (PRD)

**Course:** BU-209 Backend Engineering  
**Product Name:** CampusPulse  
**Product Type:** Campus Events and Activities Web Application  
**Version:** 1.0

## 1. Product Overview

CampusPulse is a web application designed to help university students discover events and activities happening around their campus.

The platform provides a central location where students can find information about upcoming events, including their dates, times, venues, categories and descriptions.

The application will also allow authorised event organisers to submit event information for review and publication.

## 2. Problem Statement

Students sometimes miss important campus events because information is shared across different platforms, including WhatsApp groups, social media, posters and student announcements.

As a result, students may not know when certain activities are happening, where they are taking place or how to participate.

CampusPulse aims to address this problem by providing a central platform where students can easily discover campus activities and access accurate event information.

**Research to be completed:** Conduct student interviews or surveys to establish how students currently receive event information and what difficulties they experience.

## 3. Business Objectives

The objectives of CampusPulse are:

1. To provide a central platform for campus event information.
2. To help students discover upcoming university activities.
3. To make event dates, times and locations easily accessible.
4. To provide event organisers with a platform to share their activities.
5. To reduce the chances of students missing important campus events.

## 4. Target Users

**Students:** Students who want to discover upcoming activities and events on campus.

**Event Organisers:** Student associations, clubs and authorised individuals who organise campus activities.

**Administrators:** Individuals responsible for managing the platform and reviewing submitted events.

## 5. Stakeholders

- University students.
- Student associations and clubs.
- Event organisers.
- Platform administrators.
- University representatives.
- Development team.

## 6. User Stories

- As a student, I want to view upcoming events so that I can know what is happening on campus.
- As a student, I want to see event dates and venues so that I know when and where to attend.
- As a student, I want to search for events so that I can find specific activities.
- As a student, I want to filter events by category so that I can discover activities that interest me.
- As an event organiser, I want to submit event information so that students can see my event.
- As an administrator, I want to approve or reject submitted events so that inaccurate information is not published.
- As an organiser, I want to update event information when necessary so that students receive accurate details.

## 7. Functional Requirements

Functional requirements describe what the system must do.

| ID | CampusPulse Requirement |
|---|---|
| FR-01 | Students can create accounts and log in. |
| FR-02 | Students can view upcoming campus events. |
| FR-03 | Students can view event names, descriptions, dates, times and venues. |
| FR-04 | Students can search for events by name or keyword. |
| FR-05 | Students can filter events by category. |
| FR-06 | Students can filter events by date. |
| FR-07 | Authorised organisers can submit new events. |
| FR-08 | Organisers must provide the required event information before submitting. |
| FR-09 | Administrators can approve or reject submitted events. |
| FR-10 | Only approved events can appear on the public event listing. |
| FR-11 | Authorised organisers can edit their event information. |
| FR-12 | Administrators can remove inappropriate or outdated event listings. |

Each requirement describes an action or behaviour the system must support.

## 8. Non-Functional Requirements

Non-functional requirements describe how well the system should operate.

| Category | CampusPulse Requirement |
|---|---|
| Performance | Event searches should return results within 2 seconds under agreed normal testing conditions. |
| Security | User passwords must be stored securely and must not be saved as plain text. |
| Availability | The platform should be accessible whenever students need to view event information, subject to agreed maintenance periods. |
| Reliability | The system should prevent unapproved event submissions from appearing publicly. |
| Scalability | The platform should support an increasing number of students and event listings. |
| Usability | The application should be simple to navigate and easy to understand. |
| Privacy | Students' personal information must only be accessible to authorised users. |
| Compatibility | The application should work on common mobile and desktop web browsers. |

## 9. Scope and Priorities

The first version of CampusPulse will focus on the essential features needed to help students discover campus events.

**Features included in the MVP:**

- Student registration and login.
- Viewing upcoming events.
- Viewing event details.
- Searching for events.
- Filtering events by category and date.
- Event submission by authorised organisers.
- Event approval by administrators.
- Editing and removing event listings.

**Features outside the initial MVP:**

- Real-time push notifications.
- Online ticket payments.
- Live event streaming.
- Personalised event recommendations.
- In-app messaging.

These features may be considered for future versions.

## 10. Acceptance Criteria

The product will be considered ready for its initial release when:

1. Students can successfully register and log in.
2. Students can view published campus events.
3. Students can access complete event information.
4. The search function can return relevant events.
5. Students can filter events by category and date.
6. Authorised organisers can submit event information.
7. Administrators can approve or reject event submissions.
8. Unapproved events cannot appear in public listings.
9. Authorised users can edit or remove event listings.
10. The application works on common mobile and desktop browsers.

## 11. Assumptions and Open Questions

**Assumptions**

- Students have access to smartphones or computers with internet connectivity.
- Campus events have identifiable dates, times and venues.
- Event organisers are willing to submit their event information.
- Administrators will be available to review event submissions.

**Open Questions**

1. Will all students be allowed to submit events, or only authorised organisers?
2. Who will be responsible for approving submitted events?
3. Will students need accounts to browse events?
4. Should students be able to register their interest in attending events?
5. How will students be informed when an event's details change?
6. Will the university provide an official source for verifying event information?

These questions will need to be discussed and answered by the project team before development begins.
