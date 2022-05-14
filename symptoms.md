---
### CONTENT ###

# The question you want to ask
text: Regardless of your vaccination status, are you currently experiencing symptoms?

# The answer options and page name of destination associated with each answer
# Add as many as you need.
answers:
  - text: "Yes, I have symptoms"
    path: question-3
  - text: "No, I don't have symptoms"
    path: first-date

# Whether this question includes related resources (yes or no)
# To add resources, create a content page in the "_resources" folder and add this question's filename to the "related-page-name" setting, for example, who.md.
resources: yes

# =============================================================================

### NAVIGATION ###

# The name of this page used for the URL, for example, who.html
slug: symptoms

# The name of the page where the back button goes from this question
back: situation

# =============================================================================

### SETTINGS ###

# The name of the layout template this question uses
layout: question

# The title of this page for display purposes, if needed
title: Symptoms

# The number of this question that may be used for ordering or sorting
number: 2

# The input type for this question, currently radio only
type: radio
---