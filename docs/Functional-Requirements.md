# Functional Requirements for HumbleHire AI MVP

This document specifies the core behaviors, actions, and constraints that the HumbleHire AI system must perform to satisfy the MVP user stories.

---

## 🔐 1. Authentication Requirements

### FR-001: User Registration Fields
The system shall allow a user to create an account using:
*   Full Name
*   Email Address
*   Password

### FR-002: Email Validation
The system shall validate that the email address has a valid format (e.g., user@example.com).

### FR-003: Duplicate Prevention
The system shall prevent duplicate email registrations.

### FR-004: Password Security
The system shall encrypt (hash) user passwords before storing them.

### FR-005: Post-Auth Redirection
The system shall redirect the user to the dashboard after successful login.

---

## 📝 2. Resume Builder Requirements

### FR-006: Multiple Resumes
The system shall allow users to create multiple resumes.

### FR-007: Resume Modification
The system shall allow users to edit existing resumes.

### FR-008: Auto-Save
The system shall automatically save changes.

### FR-009: Resume Removal
The system shall allow users to delete resumes.

### FR-010: Resume Duplication
The system shall allow users to duplicate a resume.

---

## 🎨 3. Template Requirements

### FR-011: Template Variety
The system shall display multiple professional resume templates.

### FR-012: Template Preview
The system shall allow users to preview templates before selecting one.

### FR-013: Template Application
The system shall apply the selected template to the resume.

---

## 📄 4. PDF Requirements

### FR-014: PDF Generation
The system shall generate a downloadable PDF version of the resume.

### FR-015: Formatting Preservation
The downloaded PDF shall preserve formatting.

---

## 📊 5. Dashboard Requirements

### FR-016: Resume Overview
The dashboard shall display all resumes created by the user.

### FR-017: Last Updated Timestamp
The dashboard shall show the date each resume was last updated.

### FR-018: Resume Search Functionality
The dashboard shall allow users to search their resumes.
