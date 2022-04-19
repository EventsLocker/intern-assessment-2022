# Title: Completed Tasks Don't Go Away When "Active" Is Clicked
## Severity: High
## Description:
1. Enter a todo
2. Check it ( = mark it as completed)
3. Click "Active"
4. The checked todo doesn't go away
## Proposed Solution:
When "Active" is clicked, all the completed todos should be hidden, and the unfinished todos should be displayed.

Fixed in render() of app.jsx.
Test:
1. Enter several todos to the list
2. Mark all of them as completed, click "Active", check if they are all hidden
3. Leave all of them as unchecked, click "Active", check if all of them are displayed
4. Mark some of them as completed, click "Active", check if the completed ones are hidden and the unchecked ones are displayed
5. While "Active", enter a new todo and see if it is displayed
==================================
# Title: Unchecked Tasks Don't Go Away When "Completed" Is Clicked
## Severity: High
## Description:
1. Enter a todo
2. Click "Completed"
3. The todo doesn't go away
## Proposed Solution:
When "Completed" is clicked, all the unchecked todos should be hidden, and the completed todos should be displayed.

Fixed in render() of app.jsx.
Test:
1. Enter several todos to the list
2. Mark all of them as completed, click "Completed", check if they are all displayed
3. Leave all of them as unchecked, click "Completed", check if all of them are hidden
4. Mark some of them as completed, click "Completed", check if the completed ones are displayed and the unchecked ones are hidden
5. While "Completed", enter a new todo and see if it is hidden
==================================
# Title: "Clear completed" Does Not Work
## Severity: High
## Description:
1. Enter a todo
2. Check it ( = mark it as completed)
3. Click "Clear completed"
4. The completed todo stays, nothing happens
## Proposed Solution:
When "Clear completed" is clicked, all the completed todos should be permanently removed from the list.

Fixed in todoModel.js by adding an implementation for the function app.TodoModel.prototype.clearCompleted.
Test:
1. Enter several todos to the list
2. Mark all of them as completed, click "Clear completed", check if they are all removed
3. Enter several todos again
4. Leave all of them as unchecked, click "Clear completed", check if all of them remain in the list
5. Mark some of them as completed, click "Clear completed", check if the completed ones are removed and the unchecked ones remain
==================================
# Title: Cannot Directly Modify a Todo From the List
## Severity: High
## Description:
1. Enter a todo
2. Cannot modify the todo by directly double-clicking it
## Proposed Solution:
When a todo on the list is double-clicked, it should be able to be modified.
==================================
# Title: The TodoFooter Appears Before a Todo Is Entered
## Severity: Low
## Description:
The TodoFooter starts to appear at the beginning when the app is launched, whereas in the video it appears only after at least one todo is entered to the list.
## Proposed Solution:
The TodoFooter should appear after at least one todo is entered to the list.
==================================
# Title: The Todo Section's Background Color Is Not Right
## Severity: Low
## Description:
The background color of the todo section is white instead of cream yellow.
## Proposed Solution:
The background color of the todo section should be cream yellow.

Fixed in styles/index.css
==================================
# Title: The Destroy Button at the End of Each Todo Item Does Not Have the Same Look as in the Video
## Severity: Low
## Description:
1. Enter a todo
2. The destroy button at the end of this todo item does not have the same look as in the video
## Proposed Solution:
The destroy button for each todo item should have a white "X" in a gray circle.
==================================
# Title: The Edge Between Two Todos Is Not Green
## Severity: Low
## Description:
1. Enter 2 todos
2. The edge between them is gray instead of green
## Proposed Solution:
The edge between every 2 todo items should be green.

Fixed in styles/index.css
Test:
1. Enter 2 todos
2. Check if the edge between them is green
==================================
# Title: The Border of Toggle Checkbox for Each Todo Is Not red
## Severity: Low
## Description:
1. Enter a todo
2. The border of the toggle checkbox next to the todo content is not red
## Proposed Solution:
The border of the toggle checkbox next to each todo content should be red.
==================================
# Title: Selected "All", "Active", or "Completed" Is Not Boxed
## Severity: Low
## Description:
1. Enter a todo
2. Select one of "All", "Active", and "Completed"
3. The selected word is not boxed
## Proposed Solution:
The selected word should be boxed by a red rectangle.