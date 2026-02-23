# Lumiere-Beauty---eCommerce
Lumière Beauty is a marketplace-style E-commerce web application developed for the Design with Algorithms course. The project focuses on user experience, scalable architecture, and pixel-perfect implementation.

1. Purpose

This Code of Conduct defines the collaboration standards, technical workflow, and development rules for the Lumière Beauty E-commerce project.

It ensures:
	•Equal participation
	•Structured Git workflow
	•Clean and scalable code
	•Respectful communication
	•Alignment with course requirements  ￼

2. Branching Model

We follow a simplified GitFlow strategy.

Main Branches
	•main - Stable production-ready version
	•develop - Integration branch for ongoing development

Supporting Branches
	•feature/feature-name
	•fix/bug-name
	•hotfix/urgent-fix

Rules
	• No direct commits to main
	• No direct commits to develop
	• All features must be developed in separate branches
	• Pull Requests are mandatory before merging
	• At least one teammate must review before merge
	• Branch must be deleted after merge


3. Commit Convention

We follow structured semantic commits:

type(scope): short description

Allowed Types
	•feat - new feature
	•fix - bug fix
	•style - visual changes (CSS/UI)
	•refactor - code restructuring without behavior change
	•docs - documentation updates
	•chore - config or tooling updates

Examples

feat(auth): implement login validation
fix(product-card): correct image overflow
style(homepage): adjust spacing for mobile
refactor(global-state): simplify reducer logic

Commit Rules
	•No vague commits like “changes” or “final”
	•Commits must describe WHAT and WHERE
	•Small and frequent commits
	•Push daily when working


4. Technologies & Libraries

The project will be developed using the technologies covered in the curse "Design of algoritms"

Core Stack
	•JavaScript (ES6+)
	•CSS / CSS Modules
 (esto se ira llenando conforme veamos las librerias y tecnologias en clase)

Rules
	•Do not introduce new libraries without team discussion
	•Keep dependencies minimal
	•Document every new dependency added
	•Never upload node_modules (as required)  ￼


5. Code Quality Standards
	•Follow Clean Code principles
	•Use reusable components
	•Avoid duplicated logic
	•Respect folder structure (scaffolding)
	•Maintain Pixel Perfect alignment with design  ￼

Before merging:
	•Test responsiveness
	•Test interactions
	•Check console for errors


6. Equal Participation

All team members must:
	•Contribute to coding
	•Understand global state
	•Understand authentication flow
	•Understand data persistence
	•Participate equally in presentation

No member should be limited to only design or only documentation.


7. Professional Communication
	•Feedback must be respectful and solution oriented
	•Disagreements resolved through technical arguments
	•Decisions documented
	•Deadlines respected


8. Accountability

If a member:
	•Fails to complete tasks
	•Pushes broken code repeatedly
	•Ignores workflow rules

The team will:
	1.	Discuss internally
	2.	Redistribute tasks if necessary
	3.	Document participation


9. Quality Control Process

Before merging any feature:
	•Self-review completed
	•Responsive check (mobile & desktop)
	•No console errors
	•Pixel Perfect comparison
	•Code formatted
