# Micro-App Specification

**Definition**  
A Micro-App is a single, self-contained HTML file that operates as an independent application or game.  

**Requirements**  

1. **File Structure**  
   - Must consist of a single file containing:  
     - HTML markup  
     - Embedded or linked CSS  
     - Embedded or linked JavaScript  
   - The file must start with `<!DOCTYPE html>`.

2. **Dependencies**  
   - External libraries may be included **only** via public CDNs (e.g., Cloudflare, jsDelivr, UNPKG).  
   - No locally stored or downloaded assets are allowed (e.g., no external image or font files saved alongside the HTML).  

3. **Content Guidelines**  
   - The application must be fully functional without any additional files.  
   - All styles and scripts should be either:  
     - Embedded directly within the HTML file, or  
     - Linked via CDN.  

4. **Modification Protocol**  
   - When altering an existing Micro-App:  
     - Provide the **entire HTML file** in the updated version.  
     - The file must be enclosed in a full code block.  
     - Do **not** truncate, omit, or skip any lines of code.  