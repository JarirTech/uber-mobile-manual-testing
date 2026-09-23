jarirTech

# Safety Test Cases

> Never make a real emergency call just to test this portfolio project.

## TC-SAFE-001 — Safety Toolkit
**Priority:** Critical | **Type:** Safety  
**Steps:** During eligible requested/active trip, open safety control.  
**Expected:** Available safety tools open without corrupting trip state.

## TC-SAFE-002 — Share trip
**Priority:** High | **Type:** Safety  
**Precondition:** Consenting test contact.  
**Steps:** Open share-trip/status option and select authorized contact.  
**Expected:** Sharing flow clearly communicates the action and completes only after user confirmation.

## TC-SAFE-003 — PIN verification where available
**Priority:** High | **Type:** Safety  
**Steps:** Enable PIN if available and follow legitimate eligible ride flow.  
**Expected:** PIN verification state appears and behaves consistently.

## TC-SAFE-004 — Emergency assistance UI
**Priority:** Critical | **Type:** Safety/UI  
**Steps:** Open Safety Toolkit and locate emergency assistance; do not place a test emergency call.  
**Expected:** Emergency option is clearly accessible and relevant trip/location information or next step is presented.

## TC-SAFE-005 — Safety access after app restore
**Priority:** High | **Type:** Recovery  
**Steps:** During eligible trip, background/reopen app, then reopen safety tools.  
**Expected:** Trip state and safety access remain available.

## TC-SAFE-006 — Check-your-ride information
**Priority:** Critical | **Type:** Safety  
**Steps:** After legitimate match, inspect driver/vehicle details.  
**Expected:** Available information needed to check the arriving ride is readable and consistent.
