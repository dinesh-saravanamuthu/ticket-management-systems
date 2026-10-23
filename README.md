# TicketFlow — HTML, CSS and JavaScript only

This is the static, framework-free version of TicketFlow. The interface styles and page structure are retained from the supplied project; the Java/Spring Boot/MongoDB backend has been removed and the API calls are implemented in browser JavaScript with `localStorage`.

## Run
1. Extract the ZIP.
2. Open `index.html` in a modern browser. If your browser restricts local file behavior, serve this folder with any simple static file server; no application backend is required.

## Demo accounts
- Admin: `admin@ticket.com` / `admin123`
- Staff: `staff@ticket.com` / `staff123`
- User: `user@ticket.com` / `user123`

## Included interactions
- Sign in and create account
- Role-based dashboard, ticket list, ticket creation, search and filters
- Ticket details, comments, status updates, staff assignment and feedback
- User role management, reports, notifications, profile and sign out
- Browser-local persistence across reloads

## Important limitation
Because this version uses only HTML, CSS and JavaScript, data is stored in the current browser's `localStorage`. It is not a secure shared database: data does not sync between devices or browsers, and passwords are stored locally in readable form. Do not use real personal data or deploy this version as a production multi-user support system. Shared, secure accounts and cross-device synchronization require a backend or hosted data service, which would violate the “HTML/CSS/JavaScript only” constraint.
