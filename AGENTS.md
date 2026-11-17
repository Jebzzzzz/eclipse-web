
# Eclipse Web - Agent Instructions

## Purpose
This repository contains the web application for Eclipse / OJT Chronicle.

The application provides OJT students with an interface for documenting internship activities, recording working hours, uploading evidence, and managing their documentation.

## Technology Stack

- React
- Vite
- TypeScript
- Supabase client libraries
- Progressive Web App (PWA) capabilities

Follow the versions and configurations already established in the project.

## Architecture and Responsibilities

- Implement user-facing pages and reusable UI components.
- Handle frontend navigation and application state.
- Integrate with the documented backend/API contracts.
- Implement client-side form validation and user feedback.
- Support responsive layouts and installable PWA behavior.
- Provide accessible and consistent user experiences.

## Development Rules

1. Use TypeScript for application code.
2. Prefer reusable components over duplicated UI implementations.
3. Follow the existing folder structure and naming conventions.
4. Keep components focused on their responsibilities.
5. Separate UI presentation, business logic, and data-access concerns.
6. Avoid unnecessary global state.
7. Use the existing design system and shared components.
8. Ensure layouts work on mobile, tablet, and desktop screens.
9. Provide appropriate loading, empty, success, and error states.
10. Do not introduce dependencies without a clear reason.

## Backend Integration

- Follow the API contracts documented in `eclipse-specs`.
- Use the approved Supabase client configuration.
- Never expose Supabase service-role credentials in frontend code.
- Do not bypass Row Level Security (RLS).
- Do not rely solely on frontend validation for security.
- Handle authentication and session states correctly.

## AI-Assisted Text Enhancement

- Send enhancement requests through the approved backend functionality.
- Do not expose OpenAI API keys in the browser.
- Preserve the original user-written description.
- Clearly distinguish original text from AI-enhanced text.
- Do not automatically overwrite user content without explicit user action.

## Accessibility and UX

- Use semantic HTML.
- Support keyboard navigation.
- Provide accessible labels and error messages.
- Maintain readable contrast and consistent interaction patterns.
- Avoid destructive actions without confirmation.

## Testing and Validation

Before completing a task:
- Run the available lint and build commands.
- Test relevant user workflows.
- Check responsive behavior.
- Verify API integration and error handling.
- Report any untested behavior or known limitations.

## Restrictions

- Do not implement backend business logic in the frontend.
- Do not hardcode secrets or production credentials.
- Do not create undocumented features.
- Do not modify unrelated components or configurations.
