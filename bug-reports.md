# Bug Reports: Microsoft Copilot

---

**Bug ID:** BUG001  
**Title:** "Generate Code" button does not work in Copilot panel  
**Priority:** High  
**Status:** New  
**Environment:**  
- OS: Windows 11  
- Editor: Visual Studio Code v1.90  
- Extension: GitHub Copilot v1.106  

**Steps to Reproduce:**  
1. Open Visual Studio Code  
2. Open the Copilot panel  
3. Type a prompt (e.g., "Create login form in HTML")  
4. Click the "Generate Code" button  

**Expected Result:**  
Copilot generates and inserts code into the editor.  

**Actual Result:**  
Nothing happens. The button is unresponsive. No error message is shown.  

**Additional Information:**  
The issue started after the latest Copilot update. No errors in developer console.

---

**Bug ID:** BUG002  
**Title:** Copilot panel overlaps with editor content on smaller screens  
**Priority:** Medium  
**Status:** Open  
**Environment:**  
- OS: macOS Ventura  
- Editor: Visual Studio Code  
- Resolution: 1366x768  

**Steps to Reproduce:**  
1. Open VS Code in split-screen mode  
2. Launch the Copilot panel  
3. Try to edit code behind the panel  

**Expected Result:**  
Copilot panel should be resizable or allow code editing in background  

**Actual Result:**  
Copilot panel fully overlaps editor area; user cannot access the code underneath  

**Additional Information:**  
UX issue on smaller resolutions. Resizing window doesn’t fix the overlap.
