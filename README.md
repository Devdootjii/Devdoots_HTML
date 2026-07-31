# Devdoots_HTML


📢 Team Devdoots | Assignment #02: Profile & Tech Showcase Page
Assigned By: Technical Program Manager (TPM)

Target Branch: feature/member-profile

Base Branch: main

Deadline: Next Sync Call

🎯 Objective
Is assignment ka goal aapki Semantic HTML5, Form Controls, Data Presentation (Tables), aur Git Workflow ki understanding ko validate karna hai. Real-world development standard follow karte hue aapko apna profile page build karke Pull Request (PR) raise karni hai.

📋 Technical Requirements
Semantic Page Layout

<header>, <main>, <section>, aur <footer> tags ka strict use hona chahiye.

Universal <div> wrapping allow nahi hai jab tak layout structuring ke liye zaroori na ho.

Member Profile Section

<h1> tag me aapka Full Name.

Aapka specific team role (e.g., Data Scientist / Core Engineer).

Profile image (<img> tag with proper alt text).

Tech Stack Table

Ek clear table (<table>) banao jisme ye columns hone chahiye:

Skill Name

Proficiency Level (Beginner / Intermediate / Advanced)

Domain/Project Area

Task Update Form (Interactive Block)

Ek functional form create karo jisme ye fields required hain:

Task Name: Text input

Status: Dropdown menu (<select>) with options (Completed, In Progress, Blocked)

Comments/Blockers: Textarea

Submit Button

External Linking

Aapki personal GitHub profile ya repository ka valid link (<a> tag with target="_blank").

⚙️ Git & Pull Request Guidelines
Apne local system par main branch ko pull karke ek new feature branch banao:
git checkout -b feature/yourname-profile

Apne changes complete karo aur clean commit message ke saath save karo:
git commit -m "feat: added profile and tech showcase section for [Your Name]"

Branch ko GitHub pe push karo:
git push origin feature/yourname-profile

GitHub par jaakar main branch ke aginst ek Pull Request (PR) raise karo.

PR ke description me kya changes kiye hain aur screenshots attach karke mujhe tag karo review ke liye.

🔍 PR Acceptance Criteria (Strictly Evaluated)
[ ] Code indentation aur clean tag hierarchy.

[ ] Proper form labels (for attribute matching id).

[ ] No unclosed tags.

[ ] Git PR workflow without merge conflicts.

Note: Merge permissions mere pass (TPM) hongi. Code review ke baad feedback PR comments me milega. Best of luck!


​📢 Team Devdoots | Assignment #03: CSS Styling & Layout Optimization
​Assigned By: Technical Program Manager (TPM)
Target Branch: feature/profile-styling
Base Branch: main
Deadline: Next Sync Call
​🎯 Objective
​Is assignment ka goal aapke assignment #02 me banaye gaye HTML Profile Page ko ek modern, clean, aur responsive dashboard UI me convert karna hai. Aapko pure CSS Fundamentals (Selectors, Box Model, Flexbox, Forms, and Responsive Design) par evaluate kiya jayega.
​📋 Technical Requirements
​External Stylesheet & Reset
​CSS code strictly ek alag file (style.css) me hona chahiye. Internal ya inline CSS allowed nahi hai.
​Basic CSS Reset (box-sizing: border-box, margin: 0, padding: 0) apply karna mandatory hai.
​Theme & Typography
​Consistent color scheme (Primary color, Secondary color, Background color) ka use karein.
​Clean typography apply karein (font-family define karein, e.g., 'Segoe UI', Arial, or sans-serif).
​Box Model & Card Layout
​Profile Section, Table, aur Form sabhi ko alag-alag Card Boxes me group karein.
​Proper padding (box ke andar space) aur margin (boxes ke beech space) apply honi chahiye.
​Rounded borders (border-radius) aur subtle shadows (box-shadow) ka use karke visual depth dein.
​Flexbox Positioning
​Navigation Bar (<header>) aur Profile Header ko align karne ke liye display: flex ka use karein.
​Components horizontally/vertically visually centered aur clean align hone chahiye.
​Table & Form UI Styling
​Table: Standard borders, padded cells, alternating row colors (zebra striping), aur styled table headers (<thead>).
​Status Badges: Status column me badges banaayein (e.g., green background for Active/Completed, orange for In Progress).
​Form Controls: Inputs, Select dropdowns, aur Buttons ko proper width, borders, focus outline, aur hover effects (:hover) dein.
​⚙️ Git & Pull Request Guidelines
​Apne local system par main branch ko pull karke naya feature branch banao:
git checkout -b feature/yourname-css-styling
​Changes complete karne ke baad commit message likhein:
git commit -m "style: applied flexbox layout, CSS variables, and responsive design"
​Branch ko push karke Pull Request (PR) raise karein:
git push origin feature/yourname-css-styling
​PR me Before (Pure HTML) aur After (With CSS) ke screenshots attach karke mujhe tag karein.
​🔍 PR Acceptance Criteria (Strictly Evaluated by TPM)
​[ ] External CSS sheet cleanly linked (<link rel="stylesheet">).
​[ ] Responsive structure (Layout elements cut ya overflow na ho).
​[ ] No Inline CSS (style="..." attributes inside HTML tags).
​[ ] Clean Class naming conventions (e.g., .card, .btn-primary, .table-container).

