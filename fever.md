---
### CONTENT ###

# The question you want to ask
text: Did you have a fever? Or do you have one now?

# The answer options and page name of destination associated with each answer
# Add as many as you need.
answers:
  - text: "Yes, I had a fever that ended"
    path: date-ended
  - text: "Yes, I have a fever now"
    path: results4
  - text: "No, I haven't had a fever"
    path: results1

# Whether this question includes related resources (yes or no)
# To add resources, create a content page in the "_resources" folder and add this question's filename to the "related-page-name" setting, for example, who.md.
resources: yes

# =============================================================================

### NAVIGATION ###

# The name of this page used for the URL, for example, who.html
slug: who

# The name of the page where the back button goes from this question
back: index

# =============================================================================

### SETTINGS ###

# The name of the layout template this question uses
layout: question

# The title of this page for display purposes, if needed
title: Question 1

# The number of this question that may be used for ordering or sorting
number: 1

# The input type for this question, currently radio only
type: radio
---