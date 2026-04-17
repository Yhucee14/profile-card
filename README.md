# Profile Card 

A clean, accessible, and fully testable **Profile Card** component built with semantic HTML and modern CSS.

## ✨ Features

- Fully responsive design (mobile-first, works beautifully from 320px upwards)
- All required `data-testid` attributes for automated testing
- Live epoch time display (updates every 800ms using `Date.now()`)
- Accessible markup with proper ARIA labels and roles
- Semantic HTML (`<article>`, `<nav>`, `<section>`, `<figure>`, etc.)
- Clean light-mode aesthetic with soft gradients and subtle shadows
- Smooth hover and focus states
- Keyboard navigation friendly

## 📋 Implemented `data-testid` Attributes

| Element                        | `data-testid`                        |
|-------------------------------|--------------------------------------|
| Profile Card Container        | `test-profile-card`                  |
| User Name                     | `test-user-name`                     |
| User Bio                      | `test-user-bio`                      |
| Current Epoch Time            | `test-user-time`                     |
| Avatar Image                  | `test-user-avatar`                   |
| Social Links Container        | `test-user-social-links`             |
| Twitter Link                  | `test-user-social-twitter`           |
| GitHub Link                   | `test-user-social-github`            |
| LinkedIn Link                 | `test-user-social-linkedin`          |
| Hobbies List                  | `test-user-hobbies`                  |
| Dislikes List                 | `test-user-dislikes`                 |

## 🎨 Design Highlights

- Soft, professional light theme with purple accent
- Overlapping avatar with hero gradient band
- Tag-style chips for hobbies and dislikes with distinct color coding
- Real-time millisecond timestamp with `aria-live` support
- Excellent contrast and typography

## 🧪 Acceptance Criteria Met

- All required `data-testid` attributes are present and correctly implemented
- Live epoch time updates dynamically
- Fully responsive layout (stacks cleanly on mobile)
- Semantic and accessible HTML
- Social links open in new tabs with proper security attributes
- Visible focus indicators and keyboard support

## 🚀 Live Demo

[View Live Demo](https://your-deployed-url-here.vercel.app)  

## 🛠️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Yhucee14/task-todo.git# profile-card
