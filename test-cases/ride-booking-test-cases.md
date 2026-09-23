jarirTech

# Ride Booking Test Cases

## TC-RIDE-001 — Allow location
**Priority:** Critical | **Type:** Permission  
**Steps:** Launch app and allow location permission.  
**Expected:** App can show/use an appropriate pickup/current-location state.

## TC-RIDE-002 — Deny location
**Priority:** High | **Type:** Negative  
**Steps:** Deny permission and begin ride setup.  
**Expected:** No crash; user can understand how to continue or enable location.

## TC-RIDE-003 — Search valid destination
**Priority:** Critical | **Type:** Positive  
**Steps:** 1. Tap destination field. 2. Enter valid destination. 3. Select intended result.  
**Expected:** Relevant suggestions appear and selected destination is used.

## TC-RIDE-004 — Invalid/no-result destination
**Priority:** Medium | **Type:** Negative  
**Steps:** Search nonsensical destination.  
**Expected:** Search is handled gracefully without silently selecting an unrelated place.

## TC-RIDE-005 — Adjust pickup
**Priority:** High | **Type:** Functional  
**Steps:** Select destination, edit suggested pickup, confirm.  
**Expected:** New pickup is reflected consistently.

## TC-RIDE-006 — Review ride options
**Priority:** Critical | **Type:** Functional  
**Steps:** Enter valid pickup/destination and wait for options.  
**Expected:** Available options for the account/market load correctly.

## TC-RIDE-007 — Pricing information
**Priority:** Critical | **Type:** Functional  
**Steps:** Review pricing/estimate shown for available ride options.  
**Expected:** Applicable pricing is visible before confirmation and tied to the correct option.

## TC-RIDE-008 — Select ride type
**Priority:** High | **Type:** Functional  
**Steps:** Select one available ride option.  
**Expected:** Correct option is visibly selected.

## TC-RIDE-009 — Request ride
**Priority:** Critical | **Type:** End-to-End  
**Precondition:** Execute only when an authorized real/test trip is appropriate.  
**Steps:** Enter locations, select option, review, confirm request.  
**Expected:** Request submits and app enters matching/request state.

## TC-RIDE-010 — Cancel request
**Priority:** High | **Type:** Functional  
**Precondition:** Understand possible real cancellation charges.  
**Steps:** Open active request, choose cancel, confirm.  
**Expected:** Ride state updates and applicable fee/information is clearly shown.

## TC-RIDE-011 — Add stop where available
**Priority:** Medium | **Type:** Functional  
**Steps:** Add an extra stop through available UI.  
**Expected:** Stop appears and changed trip information is reflected.

## TC-RIDE-012 — Schedule ride where available
**Priority:** Medium | **Type:** Functional  
**Steps:** Open scheduling, choose eligible date/time, enter trip, review.  
**Expected:** Selected schedule is shown correctly or unavailability is clearly explained.
