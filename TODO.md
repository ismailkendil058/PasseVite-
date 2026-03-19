# PasseVite SMS Satisfaction Task - Progress Tracker

## Approved Plan Summary
Add SMS sending after worker completes client info in /accueil:
- Config: Add `accueilPhone` to src/config.ts
- Logic: In Accueil.tsx handleComplete(), after completeClient: SMS to client phone via device SMS app
- Msg: French satisfaction question + https://passevite.vercel.app/satisfaction?phone=${phone}

**User confirmed plan alignment. Missing: actual accueilPhone number (placeholder used for now).**

## TODO Steps (Logical Breakdown)
### [x] Step 1: Create this TODO.md (current)
### [x] Step 2: Edit src/config.ts - Add accueilPhone config
### [x] Step 3: Edit src/pages/Accueil.tsx - Add SMS send in handleComplete after success
### [ ] Step 4: Test flow (add/call/complete → verify SMS opens)
### [ ] Step 5: Optional - Update Satisfaction.tsx to handle ?phone= param
### [ ] Step 6: attempt_completion

**Next: Step 2**

