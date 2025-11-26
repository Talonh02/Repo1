# Talon Hird Portfolio Project

## Project Overview
Personal portfolio website for Talon Hird - BCom Finance graduate '25 with Philosophy minor from University of Alberta and Golden Bears Wrestling alumnus.

## Site Structure
```
Portfolio Root/
├── index.html (home - hero section, featured work, athletics)
├── work.html (all projects organized by category)
├── courses.html (detailed course descriptions)
├── styles.css (shared design system)
├── Resume/
│   └── Resume.html (professional resume)
├── Academic-Projects/
│   ├── Data-Science/ (R/Quarto projects)
│   ├── Investment-Analysis/ (finance PDFs)
│   └── Philosophy/ (ethics papers)
├── Media-Coverage/ (wrestling articles)
└── Transcript/ (academic documents)
```

## Design Philosophy
- **"Old Money" Aesthetic**: Refined, tasteful, not corporate/flashy
- **Editorial/Typography-Driven**: Magazine-style layouts, beautiful type
- **Minimalist with Whitespace**: Generous spacing, breathing room
- **Wrestling as Differentiator**: Athletics featured prominently
- **Core Identity**: Well-rounded excellence + Intellectual curiosity

## Design System (styles.css)

### Typography
- **Display Font**: Cormorant Garamond (elegant, editorial)
- **Body Font**: EB Garamond (scholarly, readable)
- **Fallback**: Georgia, Times New Roman, serif

### Color Palette
**Light Mode:**
```
Background:     #FDFBF7  (warm off-white)
Surface:        #FFFFFF  (pure white)
Text Primary:   #1C1C1C  (soft black)
Text Secondary: #6B6B6B  (warm gray)
Accent Navy:    #1E3A5F  (deep navy - sophistication)
Accent Bronze:  #8B7355  (muted bronze - warmth)
Accent Green:   #2D4739  (forest green - subtle)
Border:         #E8E4DE  (warm light gray)
```

**Dark Mode:**
```
Background:     #0D0D0D  (near black)
Surface:        #1A1A18  (dark surface)
Text Primary:   #E8E4DE  (warm light)
Text Secondary: #9A9590  (warm gray)
Accent Navy:    #7BA3C9  (lighter navy)
Accent Bronze:  #C4A77D  (lighter bronze)
Accent Green:   #5B8A72  (lighter green)
Border:         #2A2826  (dark warm gray)
```

### Spacing Scale (CSS Variables)
```
--space-xs:  0.5rem
--space-sm:  1rem
--space-md:  2rem
--space-lg:  4rem
--space-xl:  6rem
--space-2xl: 8rem
```

## Page Details

### Index (Home)
- Editorial hero with large name treatment
- Tagline: Finance · Philosophy · Athletics
- Featured Work section (2 highlighted projects)
- Athletics section with achievements grid
- About section
- Footer with credentials and contact

### Work & Projects
- Page header with description
- Projects organized by category:
  - Data Science & Analytics
  - Investment Analysis
  - Philosophy & Ethics
- Media Coverage section
- Documents section (Resume, Transcript, Courses)

### Courses
- Semester-by-semester grid layout
- Course cards with code, name, grade, description
- Milestone highlights (Dean's List, program entry, etc.)

### Resume
- Professional formatting with print optimization
- Uses shared design system
- Section titles with bronze accent bar
- Competencies grid, awards list, media links

## Technical Features
- **Shared CSS**: styles.css with design tokens
- **CSS Variables**: Consistent theming via custom properties
- **Dark Mode Toggle**: localStorage persistence, system preference detection
- **Responsive Design**: Breakpoints at 1024px, 768px, 480px
- **Print Styles**: Resume optimized for printing
- **Hover Effects**: Bronze accent, smooth transitions (0.2s-0.3s)

## Navigation Pattern
- Consistent nav bar across all pages
- Logo links to home
- Work and Resume links
- Dark mode toggle in nav

## Development Notes
- Built with Claude Code (Anthropic's CLI coding agent)
- Uses Google Fonts (Cormorant Garamond + EB Garamond)
- Minimal JavaScript - only for dark mode toggle
- No external frameworks - pure HTML/CSS/JS
- Shared styles extracted to styles.css
