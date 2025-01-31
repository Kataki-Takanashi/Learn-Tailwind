# Space Tourism Website - Complete Layout & Style Guide

## OVERALL STRUCTURE
The website flows from top to bottom in this order:
1. Navigation Bar (fixed)
2. Hero Section (full viewport)
3. Destinations Section

## DETAILED LAYOUT & STYLING

### NAVIGATION BAR
Position & Size:
- Fixed to top of viewport
- Full width (100%)
- Height: 80px
- Background: rgba(27, 36, 65, 0.8) with blur effect

Layout:
- Logo: Left side, 32px margin from left
- Nav Links: Center of remaining space
- Each link spaced 32px apart

Colors:
- Background: #1B2441 (80% opacity)
- Logo Text: #FFFFFF
- Nav Links: #B8C3E6
- Hover Color: #00F0FF

### HERO SECTION
Position & Size:
- 100% viewport height
- Background gradient: #0B1026 to #1B2441

Element Positioning:
- Main Heading: Centered, 30% from top
- Subheading: 24px below main heading
- Countdown Timer: 60% from top
- CTA Button: 75% from top

Colors:
- Main Heading: #FFFFFF
- Subheading: #B8C3E6
- CTA Button: Gradient from #7B4DFF to #00F0FF

### COUNTDOWN TIMER
Position & Layout:
- Centered horizontally
- 60% from top of hero section
- Three boxes arranged horizontally
- 20px gaps between boxes

Box Styling:
- Width: 120px each
- Background: rgba(27, 36, 65, 0.5)
- Border: 1px solid rgba(123, 77, 255, 0.3)
- Numbers: #00F0FF with glow effect
- Labels: #B8C3E6

### DESTINATIONS SECTION
Position & Layout:
- Starts below hero section
- 80px padding at top
- Maximum width: 1200px
- Centered in viewport

Card Grid:
- 2 columns on desktop
- 30px gap between cards
- Cards centered in container
- Single column below 768px

Individual Cards:
- Width: 350px
- Height: 450px
- Image: Top 45% of card
- Title: 24px below image
- Description: 16px below title
- Stats: 24px below description
- Button: 24px from bottom

Card Colors:
- Background: rgba(27, 36, 65, 0.7)
- Border: rgba(123, 77, 255, 0.2)
- Title: #FFFFFF
- Description: #B8C3E6
- Stats: #00F0FF

### RESPONSIVE BREAKPOINTS

MOBILE (320px - 768px):
- Nav becomes hamburger menu
- Countdown boxes stack vertically
- Single column destination cards
- Reduced text sizes
- Hero text: 48px
- Subheading: 18px

TABLET (769px - 1024px):
- Horizontal nav with reduced padding
- Countdown stays horizontal but smaller
- Two column destination cards
- Hero text: 60px
- Subheading: 20px

DESKTOP (1025px+):
- Full navigation
- Maximum content width: 1400px
- Hero text: 72px
- Subheading: 24px
- Full-size countdown
- Two column destination cards

### TYPOGRAPHY
Font Sizes:
- Hero Heading: 72px/60px/48px (Desktop/Tablet/Mobile)
- Subheading: 24px/20px/18px
- Navigation: 16px
- Card Titles: 24px
- Card Description: 16px
- Button Text: 16px

Font Families:
- Headings & Buttons: Montserrat
- Body Text: Inter

### COLOR PALETTE
- Deep Space Blue: #0B1026 (Primary Background)
- Midnight Navy: #1B2441 (Secondary Background)
- Cosmic Purple: #7B4DFF (Accent Primary)
- Neon Cyan: #00F0FF (Accent Secondary)
- Pure White: #FFFFFF (Primary Text)
- Soft Blue: #B8C3E6 (Secondary Text)
- Mars Red: #FF4D4D (Warning/CTA)

### ANIMATIONS
Navigation:
- Links: 0.3s color transition
- Underline grows from left on hover

Cards:
- Rise 10px on hover
- Shadow intensity increases
- 0.4s transition

Buttons:
- Scale to 1.05x on hover
- Glow effect intensifies
- 0.3s transition

Page Load:
- Hero text slides up and fades in
- Cards fade in sequentially
- Nav fades in from top