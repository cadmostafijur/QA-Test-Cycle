# Test Plan

## 1. Introduction
This test plan defines the testing approach for:
- AppTestingService (Android)
- EchoChat (Android)
- apptestingservice.com (Website)
- echogpt.live (Website)

Testing covers functionality, UI/UX, responsiveness, security validation, and exploratory testing.

---

## 2. Scope

### 2.1 In-Scope
- User authentication (Email/Google/Apple)
- App upload flow
- Support ticket system
- Chat system (EchoChat)
- Website forms & navigation
- UI/UX & Dark Mode testing
- Accessibility checking (basic)

### 2.2 Out-of-Scope
- Backend API performance
- Payment gateway testing
- Deep penetration testing

---

## 3. Objectives
- Identify functional, UI/UX, and security issues
- Validate visual consistency on different screen sizes
- Confirm stability on a real device
- Ensure basic accessibility (contrast, readability)
- Document reproducible bugs with steps

---

## 4. Test Environment

### 4.1 Physical Device
**Realme GT Neo 2**
- OS: Android 13
- Purpose: Functional, performance and stability testing

### 4.2 Emulator Device
**BlueStacks Android Emulator**
- Tested with different display profiles:
  - 1280×720 @ 240 DPI
  - 1920×1080 @ 320 DPI
  - 2560×1440 @ 320 DPI
- Purpose: UI/UX, layout, scaling and responsiveness testing

### 4.3 Website Environment
- Chrome (Desktop)
- Chrome DevTools → Mobile View Simulator

---

## 5. Tools Used
- BlueStacks Emulator
- Realme GT Neo 2 device
- Chrome DevTools
- Screen recording, screenshots
- GitHub Markdown for reporting

---

## 6. Test Types

- Functional Testing
- UI/UX Testing
- Compatibility & Display Testing
- Security Validation (basic)
- Input Validation Testing
- Accessibility Testing (contrast)
- Exploratory Testing
- Negative Testing

---

## 7. Entry Criteria
- APK available
- Websites live
- Test device & emulator configured

---

## 8. Exit Criteria
- All planned test cases executed on:
  - Realme GT Neo 2  
  - BlueStacks Emulator (multiple displays)
- All major/high bugs documented
- Summary report completed

---

## Limitaion
- I user only two device for testing purpose so limited number of devices nut in bluestack emulator i use device size of ratio for testing.


### Assumptions
- Servers remain stable during testing

