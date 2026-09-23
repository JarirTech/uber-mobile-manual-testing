jarirTech

# Payment & Post-Trip Test Cases

## TC-PAY-001 — Payment selection displayed
**Priority:** High | **Type:** Functional  
**Steps:** Set up ride and inspect payment area.  
**Expected:** Selected payment choice is clearly represented.

## TC-PAY-002 — Change payment method
**Priority:** High | **Type:** Functional  
**Precondition:** Authorized alternative method exists.  
**Steps:** Open payment selection, choose another method, return.  
**Expected:** New method is reflected correctly.

## TC-PAY-003 — Invalid-format payment input
**Priority:** High | **Type:** Negative  
**Safety:** Use only permitted test data/environment; never stolen/fake real card data.  
**Steps:** Enter permitted invalid-format data and continue.  
**Expected:** Clear validation; invalid data is rejected.

## TC-PAY-004 — Completed trip history
**Priority:** High | **Type:** Functional  
**Steps:** Open Activity/history and select authorized completed trip.  
**Expected:** Correct trip details appear.

## TC-PAY-005 — Receipt/details
**Priority:** High | **Type:** Functional  
**Steps:** Review completed-trip receipt/details.  
**Expected:** Date/route/charge information corresponds to selected trip.

## TC-PAY-006 — Rate trip
**Priority:** Medium | **Type:** Functional  
**Steps:** Choose and submit rating for eligible trip.  
**Expected:** Rating is accepted once.

## TC-PAY-007 — Add tip where available
**Priority:** Medium | **Type:** Functional  
**Steps:** Open eligible post-trip flow, select tip, review/submit only when authorized.  
**Expected:** Chosen tip is clearly represented and not duplicated.

## TC-PAY-008 — Duplicate-action prevention
**Priority:** High | **Type:** Reliability  
**Steps:** Perform a payment-related confirmation once and observe loading/disabled state.  
**Expected:** UI prevents obvious duplicate submission.
