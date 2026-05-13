his document provides a complete guide to creating a functional news website prototype, including common challenges and their solutions.

Author: Shivam Chotala
Enrollment Number: 2352097312
Project Repository: GitHub Portfolio

📋 Development Process
Phase 1: Planning (1 hour)
Define your layout: Header → Navigation → Hero Section → News Grid → Sidebar → Footer. Choose a color scheme (primary red for urgency, dark blue for trust).

Phase 2: Core Structure (2-3 hours)
Build HTML skeleton with semantic tags. Create responsive grid layouts using CSS Flexbox/Grid. Implement mobile-first design.

Phase 3: Functionality (3-4 hours)
Add JavaScript for: dynamic news loading, category filtering, modal popups, auto-rotating hero slider, and live date display.

⚠️ Common Problems & Solutions
Problem 1: Images & Content Not Loading
Cause: Invalid image URLs or incorrect JSON paths
Solution: Use reliable placeholder APIs like picsum.photos. Always add fallback images with onerror attribute. Validate JSON structure using online validators.

Problem 2: Modal/Popup Not Working
Cause: JavaScript function scope issues or missing element IDs
Solution: Declare functions globally using window.functionName. Verify all modal elements have correct IDs. Check browser console for errors (F12).

Problem 3: Mobile Responsive Failures
Cause: Missing viewport meta tag or fixed pixel widths
Solution: Add <meta name="viewport">. Use relative units (%, vw, clamp()). Implement media queries at 768px and 480px breakpoints.

Problem 4: Category Filtering Broken
Cause: Case-sensitive category names or empty data arrays
Solution: Normalize category names to lowercase. Always provide fallback content using || operator. Test each category individually.

Problem 5: Slow Performance
Cause: Large images or unoptimized code
Solution: Compress images to WebP format. Lazy load images with loading="lazy". Minify CSS/JS for production.
