# Delete Account and Data — Meds Tracker

**App:** Meds Tracker  
**Developer:** Vlad Vityuk
**Support:** vlad.vityuk.apps@gmail.com


> This page explains how users can request deletion of their account and all associated data.  
> It also describes what is deleted, what may be retained temporarily, and the expected timeline.

---

## How to Request Account Deletion

### Option A — In-App (Recommended)
1. Open **Profile → Settings**.  
2. Tap **Delete Account** in the fixed bottom bar.  
3. Read the warning about the **irreversibility** of this action.  
4. Confirm deletion.  

Once confirmed, the app will:
- Invalidate active sessions and tokens.  
- Trigger full cascade deletion of all user data.  
- Sign you out automatically after completion.

### Option B — By Email
Send an email from the address linked to your account to  
**vlad.vityuk.apps@gmail.com(mailto:vlad.vityuk.apps@gmail.com?subject=Meds%20Tracker%20-%20Account%20Deletion%20Request)**  
with the subject **“Account Deletion Request.”**

Please include:
- Your account email address.  
- (Optional) Short note confirming your request.

We will verify ownership and confirm deletion.


## What Data Is Permanently Deleted

- **Firebase Authentication account** (email/password and Google OAuth).  
- All user-related data in **Cloud Firestore**, including:
  - `/users/{uid}` document.  
  - Subcollections such as `/users/{uid}/medicines`, `/events`, `/settings`, etc.  
- Any related files in **Cloud Storage**, e.g. `/users/{uid}/**`.  
- Local offline cache and queued sync data in the app.  
- **Firebase Cloud Messaging tokens** used for push notifications.

All deletions are **irreversible**.


## Timeline

- **In-app deletion:** usually completed within **minutes**.  
- **Email requests:** completed within **7 days** of confirmation.

You will receive confirmation once the process is finished.


## FAQ

**Can I recover my account after deletion?**  
No. Account deletion is **permanent and irreversible**.

**Are my data deleted on all devices?**  
Yes. Once server-side data are deleted, the app clears all local caches on the next startup.

**Does this work with Google sign-in?**  
Yes. The linked Firebase Auth Google account and all associated Firestore/Storage data are deleted.
