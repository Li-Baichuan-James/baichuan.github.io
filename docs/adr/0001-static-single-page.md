# Use a Static Single-Page Homepage

The academic homepage will move from the existing Jekyll multi-page presentation to a static `index.html` based on the Jun-CEN layout. This is a deliberate architecture change because the requested template is a self-contained single-page HTML/CSS/JavaScript site; the old source files and assets remain in the repository for reference, while `.nojekyll` makes the new root page the deployment entry point.
