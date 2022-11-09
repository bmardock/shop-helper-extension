# shop-helper-extension
Web extension for quick access tasks

### Summary:
Majority of day to day tasks are controlled by a number of 3rd party applications.
Some of these workflows are painfully klunky, manually intensive or inaccessible.
Examples:
- Product from In store sale needs to be removed from the website.
- Inventory process is ready for next stage
- Quick searching of inventory item
- Printing sku labels for products
- Collecting customer info for rewards program

The one constant is that all interactions are done via the web.
### Solution:
Create a web extension that can broadcast info when interacting on specific site as well as provide a context menu for quick access task.

### Tasks:
- Listen for POST requests on specific sites and send info to hub to broadcast info:
  - `Terminal, post data, site, action type`
- Create an action list based on incoming actions and trigger followup actions.
  - *Ex:* `Product Form save` -> `send msg to slack`, `send to msg websocket`
- Create context menu when highlighting text on specific sites:
  - Search sku
  - Print sku
 
 
