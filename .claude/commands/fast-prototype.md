# /fast-prototype

# Command Description
This is a command for generating rapid prototypes. You need to transform fast-prototype/template.html into an interactive prototype with basic functionality.

# Input Description
fast-prototype/template.html is a template that combines multiple HTML sections, containing many repeated navigation elements to describe which module matches which navigation.

# Command TODO (You must strictly follow the TODO list and cannot plan tasks yourself)
1. cp fast-prototype/template.html fast-prototype/prototype.html
2. Read prototype.html
3. Use script to add display: none for non-homepage sections, and add click events on navigation/components to complete route switching
  - For elements that can switch routes, add hover highlighting
4. print the prototype.html address: https://github.com/pfp-1/moxt-project-{projectId}/blob/main/fast-prototype/prototype.html

# Important Notes
- If prototype.html already exists, it also needs to be redesigned - copy first then redesign prototype.html
- Directly modify prototype.html
- Don't modify ID naming, selectors should directly read IDs
- Only use display: none to toggle show/hide
- Not only route nav can trigger page switching, component clicks can also trigger it - you need to accurately identify components that need to jump
- You need to complete tasks as quickly as possible, avoid over-engineering
- No need to add transition animations

# Script Guidelines
- To select DOM elements, document.querySelectorAll('[id=""], [id=""]') or document.querySelector('[id=""]') is the correct approach, do not use '#12\\:16', it goes wrong in the browser