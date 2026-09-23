
jarirTech

# Authentication Test Cases

## TC-AUTH-001 — Valid account access
**Priority:** Critical | **Type:** Positive/Functional  
**Preconditions:** App installed, network available, authorized account.
**Steps:** 
1. Launch app.
2. Start sign-in. 
3. Enter valid requested account information. 
4. Complete authorized verification.  
**Expected:** Authentication succeeds and rider home screen loads.

## TC-AUTH-002 — Invalid account input
**Priority:** High | **Type:** Negative  
**Steps:** 
1. Open sign-in. 
2. Enter invalidly formatted information. 
3. Continue.  
**Expected:** Clear validation appears and authentication does not incorrectly succeed.

## TC-AUTH-003 — Empty required field
**Priority:** High | **Type:** Validation  
**Steps:** 
1. Open sign-in. 
2. Leave required field empty. 
3. Continue.  
**Expected:** Progress is prevented and required-field feedback appears.

## TC-AUTH-004 — Network loss during sign-in
**Priority:** High | **Type:** Recovery  
**Steps:** 
1. Begin sign-in. 
2. Disable network before submit. 
3. Submit. 
4. Restore network.  
**Expected:** No crash; useful connection feedback/retry is provided.

## TC-AUTH-005 — Background/foreground after sign-in
**Priority:** Medium | **Type:** Mobile/State  
**Steps:** 
1. Sign in. 
2. Background app. 
3. Reopen.  
**Expected:** Appropriate session/app state is restored.
