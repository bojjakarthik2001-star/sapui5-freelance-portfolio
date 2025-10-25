# UI Bug Fix Example — SAP UI5

**Scenario:**
A button click event was not updating model data correctly.  
Fixed the event binding and verified responsive layout.

**Key Fix:**  
- Corrected XML view `press` event binding.  
- Added `oModel.refresh(true)` to update data binding.  
- Adjusted layout container for responsiveness.

**Tech Used:** SAP UI5 1.71.73 | XML Views | JSON Model  
**Time** = 2 hours  
**Output** = 
