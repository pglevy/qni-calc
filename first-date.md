---
### CONTENT ###

# The question you want to ask
text: What was the date you first tested positive or felt symptoms?

# The answer options and page name of destination associated with each answer
# Add as many as you need.
# answers:
#   - text: "Yes, this incident has occurred within the last 6 months"
#     path: success
#   - text: "No, this incident occurred over 6 months ago"
#     path: q3-exit

# Whether this question includes related resources (yes or no)
# To add resources, create a content page in the "_resources" folder and add this question's filename to the "related-page-name" setting, for example, who.md.
resources: no

# =============================================================================

### NAVIGATION ###

# The name of this page used for the URL, for example, who.html
slug: first-date

# The name of the page where the back button goes from this question
back: symptoms

# The name of the page where the next button goes if there are not multiple answers
next: results1

# =============================================================================

### SETTINGS ###

# The name of the layout template this question uses
layout: question

# The title of this page for display purposes, if needed
title: First date

# The number of this question that may be used for ordering or sorting
number: 3

# The input type for this question, currently radio only
type: date
---
