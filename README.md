IBLTS Website - README
Overview
The International Bangla Language Testing System (IBLTS) website is a comprehensive platform that provides information about Bangla language proficiency tests, preparation resources, test booking, and result services. This static website features a responsive design that works across all devices.

Key Features
Test Information: Details about Academic, General, and Professional test formats

Preparation Resources: 4-week and 8-week study plans with detailed schedules

Booking System: Intuitive test booking interface with date/location selection

Results Portal: Score interpretation and verification services

Responsive Design: Fully mobile-optimized experience

Resource Library: Preparation materials and study guides

Technologies Used
Frontend: HTML5, CSS3, JavaScript

Icons: Font Awesome 6.4.0

Fonts: Google Fonts (Poppins, Roboto)

Responsive Design: CSS Flexbox, Grid, and Media Queries

File Structure
text
iblts-website/
├── index.html                  # Homepage
├── about.html                  # About IBLTS
├── test-types.html             # Test types overview
├── preparation.html            # Preparation resources
│   ├── 4-week-study-plan.html  # 4-week study plan
│   └── 8-week-study-plan.html  # 8-week study plan
├── book-academic.html          # Academic test booking
├── book-general.html           # General test booking
├── book-professional.html      # Professional test booking
├── results.html                # Results and scores
├── contact.html                # Contact information
├── test-fees.html              # Test fees and payment
├── style.css                   # Global styles
├── assets/                     # Assets directory
│   ├── images/                 # Website images
│   └── scripts/                # JavaScript files
└── README.md                   # This documentation file
Responsive Design Features
Mobile-first approach with progressive enhancement

Flexible grid layouts using CSS Grid and Flexbox

Responsive tables with horizontal scrolling on mobile

Adaptable navigation with hamburger menu on small screens

Optimized touch targets for mobile devices

Viewport-appropriate font sizing and spacing

Installation & Local Development
No special installation is required as this is a static website. To run locally:

Clone the repository:

bash
git clone https://github.com/your-username/iblts-website.git
Open any HTML file in your browser or use a local server:

bash
cd iblts-website
python -m http.server 8000
Visit http://localhost:8000 in your browser

Deployment
The website can be deployed to any static hosting service:

GitHub Pages

Contact Information
For questions or support regarding the IBLTS website:

Email: support@iblts.org

Website: www.iblts.org

License
This project is proprietary software owned by the International Bangla Language Testing System. All rights reserved.
