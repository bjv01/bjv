---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '2rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
      # Display as two columns
      columns: '2'
      # Use full width with very minimal margins
      css_class: 'w-full px-2'
      spacing:
        padding: ['1rem', 0, '1rem', 0]
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
      css_style: 'font-size: 0.875rem;'
      spacing:
        padding: ['1rem', 0, '1rem', 0]
  - block: resume-awards
    content:
      title: Awards
      username: admin
    design:
      spacing:
        padding: ['1rem', 0, '1rem', 0]
  - block: resume-languages
    content:
      title: Languages
      username: admin
    design:
      spacing:
        padding: ['1rem', 0, '1rem', 0]
---
