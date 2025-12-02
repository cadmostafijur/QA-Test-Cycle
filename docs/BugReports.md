# Bug Reports

## 🔴 High Severity Bugs – AppTestingService app (ATS)

###  ATS-01 – Email Validation Missing
- Accepts invalid emails (abc, a@a)
- Severity: High
- Device: Realme GT Neo 2

###  ATS-02 – Weak Password Allowed
- No password strength rules applied
- Severity: High

###  ATS-03 – UI Breaks on Different Displays
- BlueStacks 1280×720 & 1920×1080 layouts broken
- Severity: Medium

###  ATS-04 – Apple Login Not Working
- Cannot create account using Apple
- Severity: High

###  ATS-05 – Wrong Support Ticket Timestamp
- Shows “5 hr ago” immediately
- Severity: Medium

###  ATS-06 – Discord Link Expired
- Support link invalid
- Severity: Low

###  ATS-07 – Upload App Flow Not Working
- Next page not loading after app upload
- Severity: High

---

## 🔴 High Severity Bugs – EchoChat App

###  EC-01 – Google Login Not Working
- No action after selecting Google account
- Severity: Critical

###  EC-02 – Chat AI Response Missing
- Input shown but no output appears
- Severity: Critical

###  EC-03 – Dark Mode Visibility Issues
- Text unreadable on BlueStacks (all resolutions)
- Severity: High

###  EC-04 – User Message Disappears
- In dark mode, questions vanish
- Severity: High

###  EC-05 – Poor Logo Quality
- Logo pixelated, unprofessional
- Severity: Low

###  EC-06 – UI/UX Needs Major Improvement
- Improper spacing, alignment issues
- Severity: Medium

---

## 🔵 Website Issues

###  WEB-01 – Form Validation Missing
- Accepts empty or invalid values
- Severity: High

###  WEB-02 – Broken Links
- Some links not responding or expired
- Severity: Medium

###  WEB-03 – Mobile View Layout Shift
- Overlapping elements on small screens , padding need
- Severity: Medium

###  WEB-04 – “Get Started Now” Button Not Working
- CTA button on homepage does not navigate anywhere
- Severity: High
- Affects: apptestingservice.com

###  WEB-05 – Submit App for Testing → Checkout Not Working
- Checkout page does not load, user cannot proceed
- Severity: Critical
- Affects: apptestingservice.com
###  WEB-06 – Image Generator Not Working
- **URL:** https://echogpt.live/image-generator
- **Component:** Image Generator Tool
- **Severity:** High
- **Site:** echogpt.live

**Steps to Reproduce:**
1. Go to `https://echogpt.live/image-generator`.
2. Enter a valid prompt in the image prompt field.
3. Click the **Generate** button.
4. Wait for the result.

**Expected Result:**
- System should process the request and:
  - Show a loading indicator.
  - Then display one or more generated images.
  - Or show a clear error message if something fails.

**Actual Result:**
- No image is generated.
- Page does not show any output / result after clicking **Generate**.
- No clear error feedback to the user.
###  WEB-07 – Missing Accessible Names for Buttons & Links
- Lighthouse flagged: “Buttons do not have an accessible name” and “Links do not have a discernible name.”
- Severity: Medium
- Impact: Affects screen readers + accessibility compliance (WCAG 4.1.2)
- Area: apptestingservice.com/#pricing

---

### WEB-08 – Images Display Incorrect Aspect Ratio
- Lighthouse flagged incorrect aspect ratios on multiple images.
- Severity: Medium
- Impact: Causes layout shift & distorted visuals

---

###  WEB-09 – Console Errors Logged
- Lighthouse flagged browser errors in DevTools.
- Severity: Medium
- Impact: Indicates JS issues or failed requests

---

###  WEB-10 – Unoptimized JavaScript (854 KB Unused)
- “Reduce unused JavaScript — Est. savings 854 KB”
- Severity: High
- Impact: Slows down page load; affects FCP, LCP, and TBT

---

###  WEB-11 – Legacy JavaScript Served to Modern Browsers
- Lighthouse reports: “Avoid legacy JS — Est saving 46 KB”
- Severity: Medium
- Impact: Slower performance on modern devices

---

###  WEB-12 – Inefficient Cache Lifetimes
- Lighthouse recommends improving cache policy
- Severity: Low
- Impact: Repeated downloads → slower user experience

---

###  WEB-13 – Image Delivery Not Optimized (Est savings 28 KB)
- Severity: Medium
- Recommendation: Use WebP / AVIF & responsive images

---

###  WEB-14 – Render Blocking Resources
- CSS/JS blocking first paint
- Severity: Medium
- Impact: Slows down FCP & LCP

---

###  WEB-15 – Accessibility Issues (Detected by Lighthouse)
- Severity: High
- Issues:
  - Missing ARIA labels
  - Buttons missing accessible names
  - Links missing descriptions

---

###  WEB-16 – Security Best Practice Warnings
- Severity: Medium
- Missing:
  - Strict CSP
  - HSTS header
  - X-Frame-Options
  - Trusted Types recommended
