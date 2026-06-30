# SVGA Book Bank — Admin Portal (Exact UI/UX Recreation)

## Objective

Design and generate a complete **enterprise-grade Admin Portal UI** for the SVGA Book Bank System.

The design should faithfully recreate the workflow, screen hierarchy, layouts, interactions, and overall experience demonstrated in the provided reference video. The goal is to produce a modern, production-ready interface that can later be implemented in **Next.js (JavaScript/JSX)**.

Do **not** redesign the workflow. Preserve the same page structure, navigation flow, information architecture, and user journey shown in the reference.

---

# Overall Design Language

Design Style

* Modern SaaS Dashboard
* Enterprise Admin Panel
* Premium UI
* Minimalistic
* Highly usable
* Spacious layout
* Soft glassmorphism accents
* White + pastel blue theme
* Subtle gradients
* Rounded corners (12–16px)
* Soft shadows
* Excellent visual hierarchy

Color Palette

Primary

* Blue (#2563EB)
* Sky Blue (#0EA5E9)

Background

* White
* Light Blue Tint
* Very Light Grey

Success

* Green

Warning

* Amber

Danger

* Red

Cards

* White
* Thin border
* Soft elevation

Typography

Use a clean font similar to:

* Inter
* Geist
* SF Pro

Large headings

Bold

Medium weight labels

Readable table typography

Consistent spacing

8px grid system

---

# Navigation

Sticky top navigation bar.

Contains

SVGA Logo

Dashboard

Requests

Inventory

Students

Audit Logs

Settings

Notifications

Admin Profile

Logout

Current page should always have an active highlight.

Navigation transitions should be smooth.

---

# Dashboard

Landing page after admin login.

Create a responsive dashboard consisting of:

Top KPI Cards

Total Books

Books Issued

Pending Requests

Manual Requests

Available Inventory

Returned Books

Pending Returns

Late Returns

Each card should include

Icon

Title

Large Number

Small status indicator

Hover animation

Graphs Section

Request trends

Inventory trends

Books by Category

Request statistics

Empty states should still look premium.

---

# Book Requests Page

Replicate the exact structure.

Tabs

Pending Requests

Completed Requests

Manual Purchase Requests

Search

Filters

Status

Department

Semester

Student

Date

Responsive request cards

Each request row contains

Application Number

Student Name

Requested Books

Status Badge

Created Date

Actions

Primary action

View Challan

Secondary actions

Approve

Reject

Purchase

Buttons must have soft hover animations.

---

# Challan Modal

The challan modal is one of the most important components.

Recreate it exactly.

Large centered modal.

Blue header.

Student Information

Book Details

Approval Status

Issue Status

Remarks

Collection Details

Procurement Timeline

Buttons

Approve

Reject

Final Submit

Close

The modal should use collapsible information groups.

Timeline should use connected status indicators.

Color coded

Green

Yellow

Red

Grey

Modal animation

Fade

Scale

Backdrop blur

---

# Procurement Lifecycle

Visual timeline

Requested

Approved

Purchased

Received

Ready

Collected

Each stage

Circular icon

Connected line

Animated progression

Status colors

---

# Inventory Management

Large data table.

Toolbar

Search

Category Filter

Export

Import

Add Book

Table Columns

Book Name

Author

Publisher

Category

Edition

Copies

Availability

Actions

Add Book Modal

Floating modal

Book Name

Author

Publisher

Edition

Category

Quantity

Save

Cancel

Validation states

Hover animations

---

# Student Management

Professional table.

Columns

Student ID

Name

Department

Semester

Phone

Email

Membership

Status

Created Date

Actions

Profile

Edit

Suspend

Delete

Search and filters at top.

---

# Audit Logs

Timeline layout.

Each entry

Timestamp

Admin Name

Action

Affected Module

Result

Filters

Date

Admin

Action Type

Search

---

# Notifications

Notification panel

Unread badge

Grouped by Today

Yesterday

Earlier

Each notification

Icon

Message

Timestamp

Status

Click to open related page.

---

# Settings

General

Admin Profile

Permissions

Email Templates

OTP Configuration

Security

Backup

Theme

Modern settings cards.

---

# Components

Reusable

Cards

Buttons

Tables

Inputs

Dropdowns

Tabs

Pagination

Search

Toast

Dialogs

Badges

Status Chips

Loaders

Skeletons

Modals

Timeline

Breadcrumb

---

# Animations

Keep animations elegant.

Avoid excessive motion.

Include

Page fade

Section reveal

Card hover elevation

Button hover

Icon micro interaction

Table row hover

Sidebar active indicator

Modal fade + scale

Smooth tab transitions

Toast slide animation

Progress animation

Timeline progression animation

Counter animation for KPI cards

Skeleton loading

Subtle glass reflections

Scroll-triggered fade-ins

Smooth scrolling

60 FPS interactions

---

# Responsiveness

Desktop First

1440px

1280px

1024px

Tablet

768px

Mobile

No horizontal scrolling.

Tables become responsive.

Cards stack intelligently.

---

# Accessibility

High contrast text

Keyboard navigation

Visible focus states

Large clickable targets

Consistent spacing

Readable typography

---

# Output Requirements

Generate the complete UI for every admin screen shown in the reference video.

Maintain the exact workflow and navigation hierarchy.

Do not simplify or omit any pages or dialogs.

Produce production-ready Figma frames with reusable components, Auto Layout, design tokens, and a scalable component library.

The resulting design should be ready for direct implementation in **Next.js App Router using JavaScript (.js/.jsx), Tailwind CSS, and Framer Motion**, preserving the visual style and interactions shown in the reference.
