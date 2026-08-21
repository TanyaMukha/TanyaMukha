# [EasyPeasy](https://github.com/TanyaMukha/EasyPeasy)

An offline study application built as a .NET MAUI Blazor Hybrid solution. Material is
organised as subjects, courses, units and cards. A course carries its own language as a
BCP-47 tag, chosen from ten, but nothing below that level is tied to a language: a card is
a pair of prompt and answer, so the same app holds vocabulary, professional terminology or
definitions equally well. Study cards come in three forms and test cards in five — single
choice, multiple choice, short answer, cloze and matching. Answers are compared tolerantly,
each card carries a difficulty rating that feeds the selection filters, and day streaks
track consistency. Courses import and export as zip archives. Speech synthesis and
pronunciation checking are wired for British English, American English and Ukrainian;
recorded audio plays back whatever the language of the material.

The solution is layered across ten projects with a test project for each, covered by 425
xUnit tests, and four reusable libraries are factored out of the app for database access,
query parameters and logging. Architecture decisions, PlantUML diagrams and a testing
strategy are kept in the repository next to the code.

Tech stack: .NET 9, MAUI Blazor Hybrid, Entity Framework Core, SQLite, xUnit, NSubstitute,
AutoMapper, CommunityToolkit.Mvvm, Markdig

<p align="center">
  <a href="/screenshots/EasyPeasy/Screenshot%202026-08-21%20173238.jpg" target="_blank">
    <img src="/screenshots/resume-creator/Screenshot%202026-08-21%20173238.jpg" width="45%" alt="EasyPeasy - Module Detail Page" height="200px" style="margin-right: 10px;"/>
  </a>
  <a href="/screenshots/EasyPeasy/Screenshot%202026-08-21%20173330.jpg" target="_blank">
    <img src="/screenshots/EasyPeasy/Screenshot%202026-08-21%20173330.jpg" width="45%" alt="EasyPeasy - Unit Page" height="200px" style="margin-right: 10px;/>
  </a>
  <a href="/screenshots/EasyPeasy/Screenshot%202026-08-21%20173438.jpg" target="_blank">
    <img src="/screenshots/EasyPeasy/Screenshot%202026-08-21%20173438.jpg" width="45%" alt="EasyPeasy - Review words - Desktop Page" height="200px" style="margin-right: 10px;/>
  </a>
  <a href="/screenshots/EasyPeasy/Screenshot%202026-08-21%20173512.jpg" target="_blank">
    <img src="/screenshots/EasyPeasy/Screenshot%202026-08-21%20173512.jpg" width="45%" alt="EasyPeasy - Review words - Mobile Page" height="200px" style="margin-right: 10px;/>
  </a>
  <a href="/screenshots/EasyPeasy/Screenshot%202026-08-21%20173512.jpg" target="_blank">
    <img src="/screenshots/EasyPeasy/Screenshot%202026-08-21%20173512.jpg" width="45%" alt="EasyPeasy - Test Page" height="200px"/>
  </a>
</p>

# [Resume Creator](https://github.com/TanyaMukha/resume-creator)

A desktop application that keeps one career history and generates targeted CVs from it.
Instead of editing a document, you edit the data — positions, experience, projects,
education, skills — and each export picks a template, a language and which of the nine
sections to include, so a CV aimed at a frontend role and one aimed at a database role
come from the same source. Four PDF templates offer different reading orders, from a
single-column layout that keeps text order intact for applicant tracking systems to one
that leads with projects rather than employers. Skills and skill groups carry their own
translations, so the same record prints in either language. Everything runs offline on a
local SQLite database behind a repository layer, with schema changes applied through
idempotent migrations that inspect the database first and skip whatever is already there.
The test suite runs against a real database rather than mocks.

Tech stack: Tauri, React 18, TypeScript, Vite, SQLite, Material UI, TanStack Query,
react-hook-form, zod, React PDF, Vitest

<p align="center">
  <a href="/screenshots/resume-creator/Screenshot%202026-08-21%20174244.jpg" target="_blank">
    <img src="/screenshots/resume-creator/Screenshot%202026-08-21%20174244.jpg" width="45%" alt="Resume Creator - Home Page" style="margin-right: 10px;"/>
  </a>
  <a href="/screenshots/resume-creator/Screenshot%202026-08-21%20174244.jpg" target="_blank">
    <img src="/screenshots/resume-creator/Screenshot%202026-08-21%20174244.jpg" width="45%" alt="Resume Creator - PDF" style="margin-right: 10px;/>
  </a>
  <a href="/screenshots/resume-creator/Screenshot%202026-08-21%20175028.jpg" target="_blank">
    <img src="/screenshots/resume-creator/Screenshot%202026-08-21%20175028.jpg" width="45%" alt="Resume Creator - PDF"/>
  </a>
</p>

# Scam

A comprehensive web platform for the French Society of Authors (La Scam) that manages authors' rights and royalty distributions. The system handles complex document management, rights administration, and member services for multimedia content creators.

Technical Implementation:
- React/TypeScript frontend with Material UI
- Dynamic form generation using Formik & Yup
- Comprehensive document management system
- Complex rights management and distribution workflow
- Multi-level access control and user management

Role: Middle Frontend Developer
- Developed responsive web interfaces from Figma designs
- Implemented complex form validation systems
- Created dynamic document management workflows
- Integrated with Azure cloud services
- Contributed to code reviews and team mentoring

Project goal: Modernize the digital platform for France's leading multimedia authors' rights management society, streamlining document processing and rights administration for content creators.

<p align="center">
  <a href="/screenshots/Scam/Screenshot%202024-11-21%20093157.jpg" target="_blank">
    <img src="/screenshots/Scam/Screenshot%202024-11-21%20093157.jpg" alt="Scam HomePage 1" height="200px" style="margin-right: 10px;"/>
  </a>
  <a href="/screenshots/Scam/Screenshot%202024-11-21%20093509.jpg" target="_blank">
    <img src="/screenshots/Scam/Screenshot%202024-11-21%20093509.jpg" alt="Scam HomePage 2" height="200px" style="margin-right: 10px;"/>
  </a>
  <a href="/screenshots/Scam/Screenshot%202024-11-21%20093823.jpg" target="_blank">
    <img src="/screenshots/Scam/Screenshot%202024-11-21%20093823.jpg" alt="Scam News&Events 1" height="200px" style="margin-right: 10px;"/>
  </a>
  <a href="/screenshots/Scam/Screenshot%202024-11-21%20093548.jpg" target="_blank">
    <img src="/screenshots/Scam/Screenshot%202024-11-21%20093548.jpg" alt="Scam Works Table" height="200px" style="margin-right: 10px;"/>
  </a>
  <a href="/screenshots/Scam/Screenshot%202024-11-21%20093644.jpg" target="_blank">
    <img src="/screenshots/Scam/Screenshot%202024-11-21%20093644.jpg" alt="Scam Works Detail" height="200px" style="margin-right: 10px;"/>
  </a>
  <a href="/screenshots/Scam/Screenshot%202024-11-21%20095735.jpg" target="_blank">
    <img src="/screenshots/Scam/Screenshot%202024-11-21%20095735.jpg" alt="Scam Mobile HomePage 1" height="200px" style="margin-right: 10px;"/>
  </a>
  <a href="/screenshots/Scam/Screenshot%202024-11-21%20095819.jpg" target="_blank">
    <img src="/screenshots/Scam/Screenshot%202024-11-21%20095819.jpg" alt="Scam Mobile HomePage 2" height="200px" style="margin-right: 10px;"/>
  </a>
  <a href="/screenshots/Scam/Screenshot%202024-11-21%20095611.jpg" target="_blank">
    <img src="/screenshots/Scam/Screenshot%202024-11-21%20095611.jpg" alt="Scam Mobile Works Table" height="200px" style="max-height: 200px;"/>
  </a>
</p>
