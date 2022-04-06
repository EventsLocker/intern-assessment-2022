- *Fixed bugs are denoted with* [RESOLVED]

- *Test my solutions by following instructions in Description section*


# Title: Cannot edit todo with double-click           [RESOLVED]
## Severity: High
## Description:
1. Add todo item(s)
2. Double-click on a todo on the list

Issue: Editing a todo is not enabled 
## Proposed Solution:
Expected behavior is that an editable textbox with a light-grey border appears after user double-clicks on a todo item.
The edit box needs further work to get the colors/shadows right.



# Title: Clear completed button not working           [RESOLVED]
## Severity: High
## Description:
1. Add todo item(s)
2. Click toggle icon to the left of "What needs to be done?"
3. Note the appearance of the Clear completed button at bottom right
4. Press the button

Issue: Nothing happens. No completed items are removed from the list.
## Proposed Solution:
Expected outcome is that after a user indicates completion of a todo item (checkbox is checked), pressing the button destroys the completed items (they no longer appear on list).



# Title: Active/Completed Failure           [RESOLVED]
## Severity: High
## Description:
Active button failure:
1. Add todo item(s)
2. Mark one item as completed
3. Press Active

Completed button failure:
4. Press Completed

Issue: List not updated based on completion status (active/completed).
## Proposed Solution:
Expected behavior is All shows all todo items, Active shows incomplete items, and Completed shows completed items



# Title: Todo item order           [RESOLVED]
## Severity: Medium
## Description:
Issue: New todo list items go to the top of the list.
## Proposed Solution:
Expected outcome is that new items are added to the bottom of the list.



# Title: Toggle side effect
## Severity: Medium
## Description:
Issue: Toggling complete all unchecks checked items.
## Proposed Solution:
Regardless of check status, all items must remain checked after user clicks toggle button. 



# Title: Appearance of 'X'           [RESOLVED]
## Severity: Low
## Description:
Issue: 'X' button, which destroys items, is red.
## Proposed Solution:
The feature should be a white 'X' in a grey circle.




# Title: Paper appearance           [RESOLVED]
## Severity: Low
## Description:
Issue: The list papers are white and show the footer containing All/Active/Completed
## Proposed Solution:
The papers should be yellow and hide the footer until at least one item is entered



# Title: Paper colorations
## Severity: Low
## Description:
1. Checkboxes are barely visible
2. Dividing line between items is barely visible
3. Very faint (and non-persistent) border color around All/Active/Completed
## Proposed Solution:
Checkboxes and button borders should be red. Division line should be blue.


