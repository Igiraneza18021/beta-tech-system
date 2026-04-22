# Beta Tech Web System

# Group names
- Igiraneza patrick main branch manager and reviewer
- Ndekezi opportun worked on feature/login-form
- Ashimwe bella sam keilla worked on feature/employee-form
- Ganza al khalid worked on feature/product-form
- Ineza kevin worked on feature/feedback-form
- Agasaro promesse worked on feature/booking-form

## Description
This project is a web-based system with multiple forms built by a team of 5 developers:

- Login Form
- Employee Registration
- Product Registration
- Customer Feedback
- Event Booking

## Team Members
| Developer | Task | Branch |
|-----------|------|--------|
| Name 1 | Login Form | `feature/login-form` |
| Name 2 | Employee Registration | `feature/employee-form` |
| Name 3 | Product Registration | `feature/product-form` |
| Name 4 | Customer Feedback | `feature/feedback-form` |
| Name 5 | Event Booking | `feature/booking-form` |

## Project Structure
```
beta-tech-system/
│
├── index.html          ← Main dashboard (main branch)
├── README.md
├── css/
│   └── style.css       ← Shared styles for all forms
├── forms/
│   ├── login.html      ← Dev 1
│   ├── employee.html   ← Dev 2
│   ├── product.html    ← Dev 3
│   ├── feedback.html   ← Dev 4
│   └── booking.html    ← Dev 5
└── assets/
```

## How to Run
1. Open `index.html` in your browser
2. Navigate to any form via the dashboard

## GitHub Workflow
Each member worked on a separate branch and submitted a pull request to main.

### Steps each developer followed:
```bash
# 1. Clone the repo
git clone <repo-link>

# 2. Create your branch
git checkout -b feature/login-form   # change to your form name

# 3. Add your file inside forms/
# 4. Stage changes
git add .

# 5. Commit with a clear message
git commit -m "Add login form with email/password validation"

# 6. Push to GitHub
git push origin feature/login-form

# 7. Open a Pull Request on GitHub → request review
```

## Design System
All forms share the same `css/style.css` stylesheet for a consistent look.

## Tech Stack
- HTML5
- CSS3 (custom properties, flexbox, grid)
- Vanilla JavaScript (form validation)
