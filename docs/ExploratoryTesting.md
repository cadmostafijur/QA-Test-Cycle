# Exploratory Testing Notes

## Session 1 – AppTestingService App
- Explored signup flow → identified missing email & password validation
- Upload App flow stuck → cannot proceed to next step
- Support ticket timestamp incorrect (shows “5 hr ago” instantly)
- Discord support link expired / invalid
- Some UI elements inconsistent on emulator screens (1280×720, 1920×1080, 2560×1440)
- App stability slightly better on Realme GT Neo 2, but still shows delays during navigation

---

## Session 2 – EchoChat App
- Google Login fails completely → no response after selecting Google account
- Dark mode text unreadable across all BlueStacks display sizes
- AI responses sometimes missing or disappear after sending
- Occasional screen freezes on Realme GT Neo 2
- UI layout spacing and alignment inconsistent (bubbles overlap / uneven padding)
- Key functional flow (chat response) unreliable → major usability impact

---

## Session 3 – Website Testing

### apptestingservice.com
- Form validation weak or missing in several sections
- “Get Started Now” CTA button does nothing (no navigation)
- “Submit App for Testing” checkout flow broken → user cannot proceed
- Some UI components lack click feedback (buttons feel unresponsive)
- Lighthouse audit:
  - Performance: 94
  - Accessibility: 91
  - Best Practices: 89
  - SEO: 100
- Issues detected:
  - Buttons and links missing accessible names
  - Images with incorrect aspect ratios
  - Render-blocking JS/CSS
  - Large unused JavaScript (854 KB)
  - Minor console warnings

---

### echogpt.live
- Basic UI functional and loads quickly
- Some layout shifts observed on navigation
- Needs stronger contrast and spacing adjustments
- Image Generator (https://echogpt.live/image-generator) **not working**:
  - No output displayed after clicking “Generate”
  - No error message shown

---

## Overall Observations
- Both mobile apps require **significant UI/UX improvement**
- Major functional issues detected in key flows:
  - EchoChat: Chat/A.I. response, Google login, dark mode visibility
  - AppTestingService: Upload app flow, validation, support features
- Emulator display testing exposed several layout inconsistencies
- Real device testing helped uncover:
  - Stability issues
  - Freezes during chat usage
- Websites performed better overall but have **critical flow blockers**:
  - CTA button not working
  - Checkout not functioning
  - Image Generator broken
- Accessibility gaps identified via Lighthouse:
  - Missing labels
  - Poor contrast
  - Incorrect image ratios

