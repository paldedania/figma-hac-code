### home/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="My Visit at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   My Visit | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="home-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       PATIENT PORTAL
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a aria-current="page" href="../home/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/visit.svg"/>
      </span>
      Visit
     </a>
     <a href="../services/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/queue.svg"/>
      </span>
      Queue
     </a>
     <a href="../blog/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/progress.svg"/>
      </span>
      Progress
     </a>
     <a href="../contact/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/alerts.svg"/>
      </span>
      Alerts
     </a>
    </nav>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        My Visit
        <span class="badge">
         ● LIVE SYNCED
        </span>
       </h1>
      </div>
      <div class="actions">
       <span class="small">
        Estimated Consultation: 10:48 AM
       </span>
      </div>
     </header>
     <div class="content-columns">
      <div class="main-column">
       <section class="banner visit-status">
        <div class="row">
         <span class="status-icon">
          <img alt="" class="icon" src="../assets/icons/checked-in.svg"/>
         </span>
         <div class="stack-small">
          <p class="eyebrow">
           Current queue status
          </p>
          <h2>
           You're checked in.
           <span class="accent">
            3 people
           </span>
           are ahead of you.
          </h2>
          <p>
           <img alt="" class="icon" src="../assets/icons/hourglass.svg"/>
           About 20 to 35 minutes wait   •   Dr. Mehta is pacing ~9 mins / patient
          </p>
         </div>
        </div>
       </section>
       <section class="card boarding-pass">
        <div class="row spread wrap">
         <div class="stack-small grow">
          <p>
           <span class="badge">
            AMBULATORY CARE
           </span>
           <span class="small muted">
            #SC-89211
           </span>
          </p>
          <h2 class="patient-name">
           Aarav Shah
          </h2>
          <p class="inline">
           <img alt="" class="icon" src="../assets/icons/doctor.svg"/>
           <strong>
            Dr. Mehta
           </strong>
           — General Medicine
          </p>
          <p class="inline">
           <img alt="" class="icon" src="../assets/icons/door.svg"/>
           Room 3 • 1st Floor, South Wing
          </p>
         </div>
         <div class="token-box">
          <p class="eyebrow">
           Queue token
          </p>
          <strong class="token">
           A-24
          </strong>
          <details>
           <summary>
            Enlarge Token
           </summary>
           <div class="disclosure-content">
            <strong class="large-value">
             A-24
            </strong>
           </div>
          </details>
         </div>
        </div>
        <div class="pass-facts">
         <dl class="metadata">
          <div>
           <dt>
            Booked slot
           </dt>
           <dd>
            10:30 AM
           </dd>
          </div>
          <div>
           <dt>
            Est. door entry
           </dt>
           <dd>
            10:48 AM
           </dd>
          </div>
          <div>
           <dt>
            Position
           </dt>
           <dd>
            #4 in Line
           </dd>
          </div>
          <div>
           <dt>
            Prep vitals
           </dt>
           <dd>
            <span class="success">
             ✓ Complete
            </span>
           </dd>
          </div>
         </dl>
        </div>
        <footer class="pass-stub">
         <div class="stack-small">
          <p class="eyebrow">
           Intake confirmation &amp; triage
          </p>
          <p>
           BP:
           <strong>
            118/76
           </strong>
           • Temp:
           <strong>
            98.4°F
           </strong>
           • Nurse Elena R.
          </p>
          <p class="small muted">
           Hold your phone or printed card within 2 inches of Door Scanner 3 upon chime.
          </p>
         </div>
         <img alt="Sample boarding pass barcode SC-89211-A24" height="40" src="../assets/images/pass-barcode.svg" width="144"/>
        </footer>
       </section>
       <nav aria-label="Visit actions" class="actions">
        <a class="btn" href="../services/index.html">
         <img alt="" class="icon" src="../assets/icons/queue-action.svg"/>
         See live queue
        </a>
        <a class="btn btn-secondary" href="../step-out/index.html">
         <img alt="" class="icon" src="../assets/icons/step-out.svg"/>
         Step out for a while
        </a>
        <a class="small" href="../sign-in/index.html">
         I'm a walk-in without a booking
        </a>
       </nav>
       <section class="card">
        <h2 class="card-title">
         Today's Wait Velocity
        </h2>
        <div aria-label="Wait velocity increases around 10:48 AM and settles before midday" class="velocity-graph" role="img">
        </div>
        <div class="row spread small wrap">
         <span>
          09:00 AM (Check-ins open)
         </span>
         <strong class="accent">
          10:48 AM (You: Token A-24)
         </strong>
         <span>
          12:00 PM (Midday shift)
         </span>
        </div>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         What happens next
        </h2>
        <ol class="list-clean">
         <li class="row">
          <span class="number number-complete">
           1
          </span>
          <div class="stack-small">
           <h3>
            Wait here or step out
           </h3>
           <p>
            You can browse nearby areas or stay in South Pavilion. Keep within 5 minutes walking distance.
           </p>
          </div>
         </li>
         <li class="row">
          <span class="number">
           2
          </span>
          <div class="stack-small">
           <h3>
            Alerted when your turn is near
           </h3>
           <p>
            We will chime this portal and dispatch an SMS to (•••) •••-4902 when you are next.
           </p>
          </div>
         </li>
         <li class="row">
          <span class="number">
           3
          </span>
          <div class="stack-small">
           <h3>
            Go to Room 3 when called
           </h3>
           <p>
            Present your digital ticket or tap your phone at Door Scanner 3. Dr. Mehta will greet you inside.
           </p>
          </div>
         </li>
        </ol>
       </section>
       <section class="card">
        <h2 class="card-title">
         Your digital ticket
        </h2>
        <div class="stack text-center">
         <div class="token-box">
          <div class="ticket-code ticket-code-square">
           <img alt="Sample ticket QR from the Figma design" height="144" src="../assets/icons/ticket-qr.svg" width="144"/>
          </div>
          <h3>
           Token A-24
          </h3>
          <p class="small muted">
           SC-89211
          </p>
         </div>
         <p>
          Show this at reception. Scan to open your live queue on any phone.
         </p>
         <a class="btn" download="" href="../assets/waiting-pass.pdf">
          <img alt="" class="icon" src="../assets/icons/download.svg"/>
          Download Waiting Pass (PDF)
         </a>
         <a class="btn btn-secondary" href="mailto:?subject=CalmWait%20visit&amp;body=Token%20A-24%20at%20South%20Pavilion.%20Room%203.">
          <img alt="" class="icon" src="../assets/icons/share.svg"/>
          Share ticket link
         </a>
         <p class="small muted">
          This QR holds only a ticket ID, not your personal details.
         </p>
        </div>
       </section>
       <section class="card surface-soft">
        <h2 class="card-title">
         Feeling unwell while waiting?
        </h2>
        <p>
         If you experience chest tightness, sudden dizziness, or worsening pain, please alert staff immediately.
        </p>
        <p class="section-gap">
         <a class="btn btn-secondary" href="../contact/index.html#help">
          Request Attendant Assistance
         </a>
        </p>
       </section>
       <section class="card">
        <h2 class="card-title">
         Clinic Amenities
        </h2>
        <ul class="list-clean">
         <li class="row">
          <img alt="" class="icon" src="../assets/icons/water.svg"/>
          <span>
           Filtered cold water station 20ft down hallway
          </span>
         </li>
         <li class="row">
          <img alt="" class="icon" src="../assets/icons/restrooms.svg"/>
          <span>
           Restrooms located adjacent to Room 1
          </span>
         </li>
         <li class="row">
          <img alt="" class="icon" src="../assets/icons/wifi.svg"/>
          <span>
           Free High-speed Wi-Fi: CalmWait-Guest
          </span>
         </li>
        </ul>
       </section>
       <section class="card">
        <h2 class="card-title">
         South Wing Floor Plan
        </h2>
        <div class="floor-plan">
         <span class="badge">
          <img alt="" class="icon" src="../assets/icons/direction.svg"/>
          You are in Waiting Lounge A
         </span>
        </div>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### home/style.css

```css
/* My Visit: page-specific layout. Shared components live in css/global.css. */

.home-page .main-column { flex: 1 1 66%; gap: 16px; }
.home-page .rail { flex: 1 1 32%; gap: 16px; }
.home-page .container { min-height: 1823px; }
.visit-status h2 { font-size: 20px; }
.status-icon { display: flex; align-items: center; justify-content: center; width: 48px; height: 48px; flex: 0 0 48px; background: var(--accent); border-radius: 8px; }
.visit-status p .icon { display: inline-flex; }
.patient-name { font-size: 28px; line-height: 36px; }
.boarding-pass { padding: 24px 24px 0; }
.pass-facts { padding: 16px; margin-top: 24px; background: var(--soft); border-radius: 8px; }
.pass-stub { display: flex; align-items: center; gap: 20px; padding: 24px 0; margin-top: 32px; border-top: 2px dashed var(--border); }
.pass-stub img { flex: 0 0 144px; }
.velocity-graph { height: 80px; margin-top: 24px; background: url('../assets/images/wait-velocity.svg') center / 100% 56px no-repeat; }
.floor-plan { display: flex; justify-content: center; align-items: center; min-height: 180px; background: #cbd5fb; border-radius: 8px; }
@media (max-width: 1199px) { .home-page .main-column { flex-basis: 60%; } .home-page .rail { flex-basis: 36%; } .pass-stub { flex-wrap: wrap; } }
@media (max-width: 767px) { .home-page .main-column, .home-page .rail { flex-basis: auto; } .home-page .container { min-height: 0; } .pass-stub { margin-top: 20px; } .boarding-pass > .row { flex-direction: column; } .boarding-pass > .row > .grow, .boarding-pass .token-box { width: 100%; } }
```

### about/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Patient Profile &amp; Care Preferences at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Patient Profile &amp; Care Preferences | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="about-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace staff-shell">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       SOUTH PAVILION CLINIC
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../reception/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-queue.svg"/>
      </span>
      Live Queue
     </a>
     <a href="../reception/index.html#doctor">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-doctor.svg"/>
      </span>
      Doctor Pacing &amp; Rooms
     </a>
     <a href="../reception/index.html#broadcast">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-comms.svg"/>
      </span>
      Patient Communications
     </a>
     <a href="../analytics/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-analytics.svg"/>
      </span>
      Analytics &amp; Reports
     </a>
     <a aria-current="page" href="../about/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-settings.svg"/>
      </span>
      Clinic Settings
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        Patient Profile &amp; Care Preferences
       </h1>
       <p>
        Manage your contact details, waiting-room sensory accessibility needs, real-time summons notifications, and active clinic credentials.
       </p>
      </div>
      <div class="actions">
      </div>
     </header>
     <div class="content-columns">
      <div class="main-column">
       <section class="card">
        <div class="row">
         <span class="avatar">
          ER
         </span>
         <div>
          <h2>
           Elena Rostova
          </h2>
          <p class="muted">
           DOB: Mar 14, 1986 (38y) • Tier 1 Verified
          </p>
         </div>
        </div>
        <form class="stack section-gap">
         <div class="field">
          <label for="legal-full-name">
           Legal Full Name
          </label>
          <input id="legal-full-name" name="legal-full-name" type="text" value="Elena Mariya Rostova"/>
         </div>
         <div class="field">
          <label for="preferred-call-name">
           Preferred Call Name
          </label>
          <input id="preferred-call-name" name="preferred-call-name" type="text" value="Elena"/>
         </div>
         <div class="form-row">
          <div class="field">
           <label for="mobile-number">
            Mobile Number
           </label>
           <input id="mobile-number" name="mobile-number" type="tel" value="+1 (555) 234-8901"/>
          </div>
          <div class="field">
           <label for="email-address">
            Email Address
           </label>
           <input id="email-address" name="email-address" type="email" value="elena.rostova@healthmail.com"/>
          </div>
         </div>
         <div class="field">
          <label for="emergency-contact">
           Emergency Contact
          </label>
          <input id="emergency-contact" name="emergency-contact" type="text" value="Mark Rostova — Spouse • Cell: (555) 882-1920"/>
         </div>
         <div class="field">
          <label for="language">
           Primary Consultation Language
          </label>
          <select id="language" name="language">
           <option>
            English (United States)
           </option>
           <option>
            ગુજરાતી
           </option>
           <option>
            हिन्दी
           </option>
          </select>
         </div>
         <p class="small muted">
          Form preview. Changes stay on this page and are not saved to an account.
         </p>
        </form>
       </section>
       <section class="card">
        <h2 class="card-title">
         Waiting-Room &amp; Sensory Accommodations
        </h2>
        <p class="muted">
         CalmWait adjusts waiting ambient levels, escort routing, and companion seating.
        </p>
        <form>
         <label class="toggle-row">
          <span>
           <strong>
            Low-Sensory Lounge Preference
           </strong>
           <span class="muted small">
            Mutes public paging chimes and redirects your pass to South Alcove Quiet Pods.
           </span>
          </span>
          <input checked="" name="low-sensory-lounge-preference" type="checkbox"/>
         </label>
         <label class="toggle-row">
          <span>
           <strong>
            Mobility &amp; Wheelchair Escort Assistance
           </strong>
           <span class="muted small">
            Concierge escorts from check-in Bay B to the examination suite.
           </span>
          </span>
          <input name="mobility-and-wheelchair-escort-assistance" type="checkbox"/>
         </label>
         <label class="toggle-row">
          <span>
           <strong>
            Clinical Medical Interpreter
           </strong>
           <span class="muted small">
            Pre-assigns an interpreter before consultation.
           </span>
          </span>
          <input name="clinical-medical-interpreter" type="checkbox"/>
         </label>
         <fieldset class="section-gap">
          <legend>
           Companion Waiting Seating Allocation
          </legend>
          <div class="segments">
           <label class="choice">
            <input checked="" name="seating" type="radio" value="0"/>
            <span>
             Waiting Alone
            </span>
           </label>
           <label class="choice">
            <input name="seating" type="radio" value="1"/>
            <span>
             +1 Companion
            </span>
           </label>
           <label class="choice">
            <input name="seating" type="radio" value="2"/>
            <span>
             Mobility Bay
            </span>
           </label>
          </div>
         </fieldset>
         <div class="field section-gap">
          <label for="access-notes">
           Clinic Access &amp; Sensory Notes
          </label>
          <textarea id="access-notes" name="access-notes">Mild photophobia: prefers dimmed lounge seating. Spouse Mark will join inside Room 04.</textarea>
         </div>
        </form>
       </section>
       <section class="card">
        <h2 class="card-title">
         Queue Alerts &amp; Summons Routing
        </h2>
        <p>
         Choose how the clinic signals when your turn approaches.
        </p>
        <form>
         <label class="toggle-row">
          <span>
           <strong>
            Direct SMS Summons
           </strong>
           <span class="muted small">
            Sends countdown, door readiness alert, and room door code.
           </span>
          </span>
          <input checked="" name="direct-sms-summons" type="checkbox"/>
         </label>
         <label class="toggle-row">
          <span>
           <strong>
            Browser Sound &amp; Haptic Vibration
           </strong>
           <span class="muted small">
            Soft two-tone gentle chime when pass moves to Next in Line.
           </span>
          </span>
          <input checked="" name="browser-sound-and-haptic-vibration" type="checkbox"/>
         </label>
         <label class="toggle-row">
          <span>
           <strong>
            Post-Visit Queue Audit &amp; Summary
           </strong>
           <span class="muted small">
            Receives visit timestamps and summary.
           </span>
          </span>
          <input name="post-visit-queue-audit-and-summary" type="checkbox"/>
         </label>
        </form>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         Active Clinic Boarding Pass
        </h2>
        <p class="eyebrow">
         Today • Oct 24
        </p>
        <div class="token-box section-gap">
         <span class="eyebrow">
          Priority token
         </span>
         <strong class="token">
          A-24
         </strong>
         <span class="badge badge-success">
          Vitals Ready
         </span>
        </div>
        <div class="stack section-gap">
         <dl class="metadata">
          <div>
           <dt>
            Provider
           </dt>
           <dd>
            Dr. Aris Thorne
           </dd>
          </div>
          <div>
           <dt>
            Assigned suite
           </dt>
           <dd>
            Room 04
           </dd>
          </div>
          <div>
           <dt>
            Estimated call in
           </dt>
           <dd>
            4 mins
           </dd>
          </div>
          <div>
           <dt>
            Target time
           </dt>
           <dd>
            10:48 AM
           </dd>
          </div>
         </dl>
         <a class="btn" href="../home/index.html">
          Open Live Boarding Pass
         </a>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         Recent Queue Passes
        </h2>
        <ul class="queue-list">
         <li class="queue-item">
          <strong>
           A-24
          </strong>
          <div class="grow">
           <h3>
            General Consultation
           </h3>
           <p class="small muted">
            Today • Dr. A. Thorne • Active
           </p>
          </div>
         </li>
         <li class="queue-item">
          <strong>
           C-08
          </strong>
          <div class="grow">
           <h3>
            Cardiology Follow-up
           </h3>
           <p class="small muted">
            Sep 12, 2024 • Dr. K. Patel • Wait: 18m
           </p>
          </div>
         </li>
         <li class="queue-item">
          <strong>
           L-12
          </strong>
          <div class="grow">
           <h3>
            Routine Blood Panel
           </h3>
           <p class="small muted">
            Jul 03, 2024 • Lab Bay 2 • Wait: 12m
           </p>
          </div>
         </li>
        </ul>
       </section>
       <section class="card">
        <h2 class="card-title">
         Security &amp; Delegates
        </h2>
        <p class="muted">
         Access control &amp; clinic kiosks.
        </p>
        <div class="stack section-gap">
         <h3>
          Two-Factor Passcode
          <span class="badge badge-success">
           Active
          </span>
         </h3>
         <p>
          SMS code sent on new clinic kiosk check-in
         </p>
         <h3>
          Authorized Delegate
         </h3>
         <p>
          Mark Rostova (Spouse) • Live Queue Viewer
         </p>
         <details>
          <summary>
           Other kiosk sessions
          </summary>
          <div class="disclosure-content">
           <p>
            Session management requires a connected account. No sessions are changed by this preview.
           </p>
          </div>
         </details>
        </div>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### about/style.css

```css
/* Patient Profile & Care Preferences: page-specific layout. Shared components live in css/global.css. */

.about-page .avatar { width: 64px; height: 64px; flex-basis: 64px; font-size: 24px; }
.about-page .main-column { flex-basis: 58%; }
.about-page .rail { flex-basis: 40%; }
.about-page .token-box { padding: 28px; }
```

### services/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Live Queue at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Live Queue | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="services-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       PATIENT PORTAL
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../home/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/visit.svg"/>
      </span>
      Visit
     </a>
     <a aria-current="page" href="../services/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/queue.svg"/>
      </span>
      Queue
     </a>
     <a href="../blog/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/progress.svg"/>
      </span>
      Progress
     </a>
     <a href="../contact/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/alerts.svg"/>
      </span>
      Alerts
     </a>
    </nav>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        Live Queue
        <span class="badge">
         SOUTH WING
        </span>
       </h1>
       <p>
        Updated 2 min ago • Doctor Mehta (General Medicine)
       </p>
      </div>
      <div class="actions">
       <a class="btn btn-secondary" href="index.html">
        Refresh status
       </a>
      </div>
     </header>
     <div class="content-columns">
      <div class="main-column">
       <section class="card">
        <h2 class="card-title">
         Estimated wait window
        </h2>
        <div class="row spread wrap">
         <div>
          <strong class="large-value accent">
           20–35
          </strong>
          min
         </div>
         <div>
          <p class="eyebrow">
           Ahead of you
          </p>
          <h3>
           3 patients
          </h3>
         </div>
        </div>
        <div class="wait-scale">
         <span>
          Min: 20m
         </span>
         <strong>
          Most likely around 25 min
         </strong>
         <span>
          Max: 35m+
         </span>
        </div>
        <div aria-hidden="true" class="wait-track">
         <span>
         </span>
        </div>
        <div class="row spread small">
         <span>
          0m
         </span>
         <span>
          20m
         </span>
         <span>
          25m
         </span>
         <span>
          35m
         </span>
         <span>
          60m
         </span>
        </div>
        <p class="section-gap muted">
         Estimate updated: 2 urgent triage cases accommodated. Pacing calibrated dynamically.
        </p>
        <p class="small section-gap">
         This is an estimate. It can change if a consultation requires additional clinical care or emergency evaluation.
        </p>
       </section>
       <section class="card">
        <h2 class="card-title">
         Dr. Mehta — General Medicine
        </h2>
        <p class="muted">
         Exam Room 3 • South Pavilion Wing
        </p>
        <p class="section-gap">
         <span class="badge badge-success">
          IN CONSULTATION ✓
         </span>
        </p>
        <div class="stack section-gap">
         <dl class="metadata">
          <div>
           <dt>
            Now serving
           </dt>
           <dd>
            Token A-20
           </dd>
          </div>
          <div>
           <dt>
            Current consultation
           </dt>
           <dd>
            ~8 mins in room
           </dd>
          </div>
          <div>
           <dt>
            Typical visit pacing
           </dt>
           <dd>
            9–11 mins
           </dd>
          </div>
         </dl>
        </div>
       </section>
       <section class="card banner-warning">
        <h2 class="card-title">
         Minor Schedule Adjustment
        </h2>
        <span class="badge badge-warning">
         +5–10 MINS
        </span>
        <p class="section-gap">
         We're running a little behind. Dr. Mehta is seeing
         <strong>
          2 urgent triage cases
         </strong>
         first. This can add approximately 5 to 10 minutes to the general schedule.
        </p>
        <p class="section-gap">
         All queued patients retain their relative priority sequence. Thank you for your patience.
        </p>
        <p class="section-gap">
         <a class="btn btn-secondary" href="../step-out/index.html">
          Step out for a while
         </a>
        </p>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         2 priority cases were added ahead of you
        </h2>
        <dl class="metadata">
         <div>
          <dt>
           Reason
          </dt>
          <dd>
           Emergency walk-in
          </dd>
         </div>
         <div>
          <dt>
           Estimated impact
          </dt>
          <dd>
           +8 to +12 minutes
          </dd>
         </div>
        </dl>
        <details>
         <summary>
          Why do some people go first?
         </summary>
         <div class="disclosure-content">
          <p>
           Clinical urgency determines triage priority. Your token keeps its place relative to other routine consultations.
          </p>
         </div>
        </details>
       </section>
       <section class="card">
        <h2 class="card-title">
         Waiting Sequence
        </h2>
        <p class="muted small">
         Tokens only to protect patient privacy.
        </p>
        <ol class="queue-list">
         <li class="queue-item">
          <span class="number">
           1
          </span>
          <div class="grow">
           <strong>
            Token A-20
           </strong>
           <p class="small muted">
            Exam Room 3
           </p>
          </div>
          <span class="badge">
           In consultation
          </span>
         </li>
         <li class="queue-item">
          <span class="number">
           2
          </span>
          <div class="grow">
           <strong>
            Token A-21
           </strong>
           <p class="small muted">
            Lounge Waiting Area
           </p>
          </div>
          <span class="badge">
           Next in line
          </span>
         </li>
         <li class="queue-item">
          <span class="number">
           3
          </span>
          <div class="grow">
           <strong>
            Token A-22
           </strong>
           <p class="small muted">
            Triage Bay
           </p>
          </div>
          <span class="badge">
           Priority triage
          </span>
         </li>
         <li class="queue-item">
          <span class="number">
           4
          </span>
          <div class="grow">
           <strong>
            Token A-23
           </strong>
           <p class="small muted">
            Courtyard Garden
           </p>
          </div>
          <span class="badge">
           Stepped out
          </span>
         </li>
         <li class="queue-item queue-item-you">
          <span class="number">
           5
          </span>
          <div class="grow">
           <strong>
            Token A-24
           </strong>
           <p class="small muted">
            Est. call: ~25 mins (approx 10:47 AM)
           </p>
          </div>
          <span class="badge">
           You • Pos #4
          </span>
         </li>
         <li class="queue-item">
          <span class="number">
           6
          </span>
          <div class="grow">
           <strong>
            Token A-25
           </strong>
           <p class="small muted">
            Check-in Kiosk 2
           </p>
          </div>
          <span class="badge">
           Checked in
          </span>
         </li>
        </ol>
        <p class="small muted section-gap">
         Patient anonymization active
        </p>
       </section>
       <section class="card">
        <h2 class="card-title">
         What could change your wait?
        </h2>
        <div class="stack">
         <article class="scenario">
          <h3>
           If the queue moves faster
          </h3>
          <strong class="scenario-value">
           15–20 min
          </strong>
          <p>
           Consultations finish quicker than average.
          </p>
         </article>
         <article class="scenario">
          <h3>
           Typical
          </h3>
          <strong class="scenario-value">
           20–35 min
          </strong>
          <p>
           Normal flow based on today's current pacing.
          </p>
         </article>
         <article class="scenario">
          <h3>
           If an emergency case arrives
          </h3>
          <strong class="scenario-value">
           35–50 min
          </strong>
          <p>
           Doctor called for urgent bedside stabilization.
          </p>
         </article>
        </div>
       </section>
      </aside>
     </div>
     <section class="card section-gap">
      <h2 class="card-title">
       South Pavilion Waiting Amenities
      </h2>
      <p>
       Complimentary herbal teas, chilled water, high-speed Wi-Fi, and charging ports at stations 1–8.
      </p>
      <p class="section-gap">
       Wi-Fi:
       <strong>
        CalmWait-Guest
       </strong>
      </p>
     </section>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### services/style.css

```css
/* Live Queue: page-specific layout. Shared components live in css/global.css. */

.services-page .container { padding: 32px; }
.wait-scale { display: flex; justify-content: space-between; gap: 12px; flex-wrap: wrap; margin: 24px 0 12px; font-size: 12px; }
.wait-track { display: flex; height: 16px; margin-bottom: 12px; background: #e2effe; border-radius: 10px; padding-left: 30%; }
.wait-track span { width: 32%; border-radius: 10px; background: #0a6e78; }
.scenario { padding: 20px; border: 1px solid var(--border); border-radius: 8px; }
.scenario:nth-child(2) { background: var(--soft); border-color: var(--accent); }
.scenario-value { display: flex; margin: 12px 0; font-size: 28px; color: var(--accent); }
@media (max-width: 767px) { .services-page .container { padding: 20px 16px; } .queue-item { flex-wrap: wrap; } }
```

### contact/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Alerts &amp; Notifications at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Alerts &amp; Notifications | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="contact-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       PATIENT PORTAL
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../home/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/visit.svg"/>
      </span>
      Visit
     </a>
     <a href="../services/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/queue.svg"/>
      </span>
      Queue
     </a>
     <a href="../blog/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/progress.svg"/>
      </span>
      Progress
     </a>
     <a aria-current="page" href="../contact/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/alerts.svg"/>
      </span>
      Alerts
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <section aria-label="Current visit" class="patient-strip patient-details">
      <strong class="token accent">
       A-24
      </strong>
      <div>
       <strong>
        Aarav Shah
       </strong>
       <p class="muted small">
        Adult Outpatient • MRN #88204
       </p>
      </div>
      <div>
       <strong>
        Dr. Mehta
       </strong>
       <p class="muted small">
        General Medicine • Room 3
       </p>
      </div>
      <div>
       <span class="eyebrow">
        Checked-in: 10:30 AM
       </span>
       <p class="accent">
        Est. turn ~10:48 AM
       </p>
      </div>
     </section>
     <header class="page-heading">
      <div>
       <h1>
        Alerts &amp; Notifications
       </h1>
       <p>
        Live operational telemetry and direct paging from clinical station Desk A
       </p>
      </div>
      <div class="actions">
       <a class="btn btn-secondary" href="#notification-settings">
        Notification Settings
       </a>
      </div>
     </header>
     <div class="content-columns">
      <div class="main-column">
       <section class="card urgent-alert">
        <h2 class="card-title">
         Your turn is near
        </h2>
        <span class="badge badge-danger">
         URGENT ACTION REQUIRED
        </span>
        <p class="section-gap">
         Please head back to Room 3 doorway within approximately 10 minutes. Dr. Mehta is currently completing the final consultation review for Token A-23.
        </p>
        <div class="section-gap">
         <details>
          <summary>
           I'm on my way
          </summary>
          <div class="disclosure-content">
           <p>
            This static preview cannot notify reception. Please tell Desk A that you are returning.
           </p>
          </div>
         </details>
        </div>
        <p class="section-gap">
         <a class="btn btn-secondary" href="../step-out/index.html">
          Need +5 min
         </a>
        </p>
       </section>
       <section class="card">
        <h2 class="section-title">
         Today • Active visit
        </h2>
        <div class="alert-feed">
         <article class="alert-entry">
          <div class="card-heading">
           <h3>
            Return now
           </h3>
           <time class="small muted">
            Just now (10:42 AM)
           </time>
          </div>
          <p>
           Dr. Mehta is ready for patients up to A-23. Please proceed directly to Room 3 doorway and present your boarding pass QR.
          </p>
         </article>
         <article class="alert-entry">
          <div class="card-heading">
           <h3>
            Your turn is near
           </h3>
           <time class="small muted">
            10:35 AM
           </time>
          </div>
          <p>
           About 2 patients ahead in the General Medicine queue. Likely 10 to 15 minutes remaining before intake call.
          </p>
         </article>
         <article class="alert-entry">
          <div class="card-heading">
           <h3>
            Schedule Adjustment
           </h3>
           <time class="small muted">
            10:25 AM
           </time>
          </div>
          <p>
           We're running about 10 minutes behind schedule. Dr. Mehta is currently attending to two unscheduled emergency triage consultations. Thank you for your patience.
          </p>
         </article>
         <article class="alert-entry">
          <div class="card-heading">
           <h3>
            Doctor Status
           </h3>
           <time class="small muted">
            10:15 AM
           </time>
          </div>
          <p>
           Dr. Mehta is back in Room 3 following a mandatory clinical sanitization and specimen handoff break.
          </p>
         </article>
         <article class="alert-entry">
          <div class="card-heading">
           <h3>
            Step-out Hold Reminder
           </h3>
           <time class="small muted">
            10:10 AM
           </time>
          </div>
          <p>
           Your place-guarantee hold window ends at 11:20 AM. An active 15-minute grace period protects your position if you visit the courtyard cafe.
          </p>
         </article>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         Earlier Today
        </h2>
        <h3>
         Intake Confirmation
        </h3>
        <p class="small muted">
         10:30 AM
        </p>
        <p class="section-gap">
         Checked in successfully at Kiosk 2. Token A-24 issued for General Medicine with Dr. Mehta.
        </p>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <div id="notification-settings">
        <section class="card">
         <h2 class="card-title">
          Notification Channels &amp; Controls
         </h2>
         <p class="muted">
          Keep informed wherever you wait across the medical campus.
         </p>
         <form>
          <label class="toggle-row">
           <span>
            <strong>
             Push Notifications
            </strong>
            <span class="muted small">
             Active in this browser
            </span>
           </span>
           <input checked="" name="push-notifications" type="checkbox"/>
          </label>
          <label class="toggle-row">
           <span>
            <strong>
             SMS Text Alerts
            </strong>
            <span class="muted small">
             +1 (•••) •••-4902
            </span>
           </span>
           <input checked="" name="sms-text-alerts" type="checkbox"/>
          </label>
          <label class="toggle-row">
           <span>
            <strong>
             WhatsApp Alerts
            </strong>
            <span class="muted small">
             Optional instant messaging
            </span>
           </span>
           <input name="whatsapp-alerts" type="checkbox"/>
          </label>
          <fieldset class="section-gap">
           <legend>
            Alert Lead Time (Queue Position)
           </legend>
           <div class="segments">
            <label class="choice">
             <input checked="" name="lead" type="radio" value="0"/>
             <span>
              1 person
             </span>
            </label>
            <label class="choice">
             <input name="lead" type="radio" value="1"/>
             <span>
              2 people
             </span>
            </label>
            <label class="choice">
             <input name="lead" type="radio" value="2"/>
             <span>
              3 people
             </span>
            </label>
           </div>
          </fieldset>
          <p class="small muted section-gap">
           Preview controls only. These preferences are not saved or sent.
          </p>
         </form>
         <p class="section-gap small">
          Mandatory Policy: "Return now" doorway calls cannot be disabled to protect appointment rhythm and room turnaround.
         </p>
        </section>
       </div>
       <section class="card surface-soft">
        <h2 class="card-title">
         Calm Flow Guarantee
        </h2>
        <p class="eyebrow">
         When queue is smooth
        </p>
        <p class="section-gap">
         No urgent alerts. Relax, read, or grab tea in South Pavilion. We'll page you right when Dr. Mehta calls Token A-24.
        </p>
       </section>
       <section class="card" id="help">
        <h2 class="section-title">
         Reception &amp; Campus Assistance
        </h2>
        <dl class="metadata">
         <div>
          <dt>
           Desk A Extension
          </dt>
          <dd>
           x4901
          </dd>
         </div>
         <div>
          <dt>
           Hospital Wi-Fi
          </dt>
          <dd>
           CalmWait-Guest
          </dd>
         </div>
        </dl>
        <p class="section-gap">
         Visit Reception Desk A in South Pavilion for physical assistance, translation, or queue inquiries.
        </p>
        <details>
         <summary>
          Where is Room 3?
         </summary>
         <div class="disclosure-content">
          <p>
           Follow the South Wing corridor on the first floor. Room 3 is beside Waiting Lounge A.
          </p>
         </div>
        </details>
       </section>
       <section class="card">
        <h2 class="card-title">
         Dr. S. Mehta, MD
        </h2>
        <div class="row">
         <img alt="Dr. Mehta" class="portrait" src="../assets/images/dr-mehta.jpeg"/>
         <div>
          <p>
           Senior Attending • Room 3
          </p>
          <p class="muted small">
           Average consult: 14 min
          </p>
         </div>
        </div>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### contact/style.css

```css
/* Alerts & Notifications: page-specific layout. Shared components live in css/global.css. */

.urgent-alert { background: #fff6ed; border-color: #efcc96; border-left: 4px solid #c77a17; }
.alert-feed { display: flex; flex-direction: column; gap: 24px; }
.alert-entry { padding: 0 0 24px 20px; border-left: 3px solid var(--border); border-bottom: 1px solid var(--border); }
.alert-entry:first-child { border-left-color: var(--accent); }
.alert-entry:last-child { border-bottom: 0; padding-bottom: 0; }
```

### blog/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="My Progress at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   My Progress | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="blog-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       PATIENT PORTAL
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../home/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/visit.svg"/>
      </span>
      Visit
     </a>
     <a href="../services/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/queue.svg"/>
      </span>
      Queue
     </a>
     <a aria-current="page" href="../blog/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/progress.svg"/>
      </span>
      Progress
     </a>
     <a href="../contact/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/alerts.svg"/>
      </span>
      Alerts
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        My Progress
       </h1>
       <p>
        Track your clinical pathway in real-time from reception intake through checkout.
       </p>
      </div>
      <div class="actions">
       <a class="btn btn-secondary" href="index.html">
        Refresh
       </a>
      </div>
     </header>
     <section aria-label="Current visit" class="patient-strip patient-details">
      <strong class="token accent">
       A-24
      </strong>
      <div>
       <strong>
        Aarav Shah
       </strong>
       <p class="muted small">
        Adult Outpatient • MRN #88204
       </p>
      </div>
      <div>
       <strong>
        Dr. Mehta
       </strong>
       <p class="muted small">
        General Medicine • Room 3
       </p>
      </div>
      <div>
       <span class="eyebrow">
        Checked-in: 10:30 AM
       </span>
       <p class="accent">
        Est. turn ~10:48 AM
       </p>
      </div>
     </section>
     <ol class="journey">
      <li>
       <span class="number number-complete">
        ✓
       </span>
       <strong>
        Checked in
       </strong>
       <span class="small muted">
        10:12 AM • Kiosk 2
       </span>
      </li>
      <li>
       <span class="number number-complete">
        ✓
       </span>
       <strong>
        Vitals Taken
       </strong>
       <span class="small muted">
        10:20 AM • Station B
       </span>
      </li>
      <li aria-current="step">
       <span class="number number-complete">
        3
       </span>
       <strong>
        Waiting
       </strong>
       <span class="small muted">
        South Pavilion
       </span>
      </li>
      <li>
       <span class="number">
        4
       </span>
       <strong>
        Consultation
       </strong>
       <span class="small muted">
        Room 3 • Dr. Mehta
       </span>
      </li>
      <li>
       <span class="number">
        5
       </span>
       <strong>
        Diagnostics
       </strong>
       <span class="small muted">
        If ordered • Lab or Radiology
       </span>
      </li>
      <li>
       <span class="number">
        6
       </span>
       <strong>
        Checkout
       </strong>
       <span class="small muted">
        Prescription &amp; Summary
       </span>
      </li>
     </ol>
     <div class="content-columns">
      <div class="main-column">
       <section class="card">
        <h2 class="card-title">
         South Pavilion Lounge
        </h2>
        <p class="eyebrow">
         Current phase • Quiet &amp; seated
        </p>
        <div class="section-gap">
         <p class="eyebrow">
          Estimated wait range
         </p>
         <strong class="large-value accent">
          20–35
         </strong>
         minutes
        </div>
        <p class="muted">
         Ranges reflect thorough, attentive patient consultations rather than rigid automated slots.
        </p>
        <div class="section-gap">
         <dl class="metadata">
          <div>
           <dt>
            Queue position
           </dt>
           <dd>
            3 patients ahead
           </dd>
          </div>
          <div>
           <dt>
            Room 3 live feed
           </dt>
           <dd>
            Consulting Token A-20
           </dd>
          </div>
         </dl>
        </div>
        <p class="section-gap">
         <a class="btn" href="../step-out/index.html">
          Step out for fresh air
         </a>
        </p>
        <p class="small muted section-gap">
         SMS Chime Armed (+1 ••• 4912). Stepping out holds your queue spot for up to 20 minutes without losing priority.
        </p>
       </section>
       <section class="card">
        <h2 class="card-title">
         Visit Pathway Log
        </h2>
        <div class="stack">
         <article>
          <div class="card-heading">
           <h3>
            Triage &amp; Clinical Vitals
           </h3>
           <time>
            10:20 AM
           </time>
          </div>
          <p>
           Nurse Station B (Nurse Henderson, RN). Initial diagnostic readings charted to electronic health record.
          </p>
          <div class="section-gap">
           <dl class="metadata">
            <div>
             <dt>
              Blood pressure
             </dt>
             <dd>
              122/78
             </dd>
            </div>
            <div>
             <dt>
              Heart rate
             </dt>
             <dd>
              72 bpm
             </dd>
            </div>
            <div>
             <dt>
              SpO2
             </dt>
             <dd>
              99%
             </dd>
            </div>
           </dl>
          </div>
         </article>
         <article class="rule">
          <div class="card-heading">
           <h3>
            Digital Intake Verified
           </h3>
           <time>
            10:12 AM
           </time>
          </div>
          <p>
           Check-in completed at Kiosk 2. Verified insurance coverage (Blue Cross PPO) and signed treatment consent.
          </p>
         </article>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         South Pavilion Amenities
        </h2>
        <div class="link-list">
         <span>
          CalmWait-Guest
         </span>
         <span>
          Herbal Tea &amp; Water
         </span>
         <span>
          Quiet Zone Seating
         </span>
        </div>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         Consultation with Dr. Mehta
        </h2>
        <p class="muted">
         Upcoming phase • Room 3, South Corridor • ~10–15 min
        </p>
        <p class="section-gap">
         Dr. Mehta will conduct a thorough review of your symptoms and recent medical updates.
        </p>
        <div class="banner section-gap">
         <h3>
          What to Bring Into Room 3
         </h3>
         <ul class="section-gap">
          <li>
           Government ID or digital boarding pass token (A-24)
          </li>
          <li>
           List of active prescriptions and medication dosages
          </li>
          <li>
           Specific questions or notes on symptom duration
          </li>
         </ul>
        </div>
        <p class="section-gap">
         Your device will play an alert chime and the hallway display boards will flash Token A-24 the moment Room 3 prepares for intake.
        </p>
       </section>
       <details>
        <summary>
         Post-Consultation &amp; Lab Work
        </summary>
        <div class="disclosure-content">
         <p>
          If Dr. Mehta orders laboratory bloodwork or imaging scans, live indoor wayfinding directions will appear here on your phone screen.
         </p>
         <p>
          Digital Discharge Summary • Ready upon departure
         </p>
        </div>
       </details>
       <section class="card">
        <h2 class="card-title">
         Need Direct Assistance?
        </h2>
        <p>
         Desk A attendant is standing by to answer queue inquiries, provide physical assistance, or coordinate translation services.
        </p>
        <p class="section-gap">
         <a class="btn btn-secondary" href="../contact/index.html#help">
          Call Attendant (x4901)
         </a>
        </p>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### blog/style.css

```css
/* My Progress: page-specific layout. Shared components live in css/global.css. */

.journey { display: flex; gap: 20px; padding: 24px; margin-bottom: 24px; background: var(--surface); border: 1px solid var(--border); border-radius: 12px; list-style: none; }
.journey li { display: flex; flex-direction: column; align-items: center; gap: 8px; flex: 1; text-align: center; }
.journey li[aria-current] { color: var(--accent); }
@media (max-width: 1199px) { .journey { flex-wrap: wrap; } .journey li { flex-basis: 26%; } }
@media (max-width: 767px) { .journey { flex-direction: column; } .journey li { flex-direction: row; text-align: left; flex-wrap: wrap; } }
```

### step-out/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Step Out of Waiting Room at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Step Out of Waiting Room | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="step-out-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       PATIENT PORTAL
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../home/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/visit.svg"/>
      </span>
      Visit
     </a>
     <a href="../services/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/queue.svg"/>
      </span>
      Queue
     </a>
     <a href="../blog/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/progress.svg"/>
      </span>
      Progress
     </a>
     <a href="../contact/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/alerts.svg"/>
      </span>
      Alerts
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        Step Out of Waiting Room
       </h1>
       <p>
        CalmWait Temporary Leave System • CalmWait Clinic
       </p>
      </div>
      <div class="actions">
       <a class="btn btn-secondary" href="../services/index.html">
        Back to Queue
       </a>
      </div>
     </header>
     <section aria-label="Current visit" class="patient-strip patient-details">
      <strong class="token accent">
       A-24
      </strong>
      <div>
       <strong>
        Aarav Shah
       </strong>
       <p class="muted small">
        Adult Outpatient • MRN #88204
       </p>
      </div>
      <div>
       <strong>
        Dr. Mehta
       </strong>
       <p class="muted small">
        General Medicine • Room 3
       </p>
      </div>
      <div>
       <span class="eyebrow">
        Checked-in: 10:30 AM
       </span>
       <p class="accent">
        Est. turn ~10:48 AM
       </p>
      </div>
     </section>
     <div class="content-columns">
      <div class="main-column">
       <section class="card">
        <h2 class="card-title">
         Step out for fresh air, coffee, or a walk
        </h2>
        <p class="eyebrow">
         Patient active pass
        </p>
        <p class="section-gap">
         Take a break without losing your place in line. Pick an estimated duration below to keep clinic pacing synchronized.
        </p>
        <div class="banner section-gap">
         <h3>
          Pacing Guarantee &amp; Safe Window
         </h3>
         <p>
          Dr. Mehta is currently consulting Token A-20 (~8m left). There are 3 patients ahead of you. You are in safe range for a temporary leave.
         </p>
        </div>
        <form class="section-gap">
         <fieldset>
          <legend>
           Select leave duration
          </legend>
          <div class="segments">
           <label class="choice">
            <input checked="" name="duration" type="radio" value="0"/>
            <span>
             10 min
             <br/>
             <span class="small">
              Nearby garden / water
             </span>
            </span>
           </label>
           <label class="choice">
            <input name="duration" type="radio" value="1"/>
            <span>
             20 min
             <br/>
             <span class="small">
              Coffee shop / cafeteria
             </span>
            </span>
           </label>
           <label class="choice">
            <input name="duration" type="radio" value="2"/>
            <span>
             30 min
             <br/>
             <span class="small">
              Campus walk / pharmacy
             </span>
            </span>
           </label>
          </div>
         </fieldset>
        </form>
        <div class="return-window section-gap">
         <dl class="metadata">
          <div>
           <dt>
            Target return by
           </dt>
           <dd>
            11:05 AM
           </dd>
          </div>
          <div>
           <dt>
            Grace hold buffer
           </dt>
           <dd>
            11:20 AM
           </dd>
          </div>
         </dl>
         <p class="small">
          Sample times from the design. Your selection does not book leave.
         </p>
        </div>
        <p class="section-gap">
         <span class="badge">
          Auto-SMS Alert Active
         </span>
         <span class="small">
          Syncing with +1 (•••) •••-4902
         </span>
        </p>
        <div class="section-gap">
         <details>
          <summary>
           Review step-out confirmation
          </summary>
          <div class="disclosure-content">
           <dl class="metadata">
            <div>
             <dt>
              Patient name
             </dt>
             <dd>
              Aarav Shah (Token A-24)
             </dd>
            </div>
            <div>
             <dt>
              Assigned physician
             </dt>
             <dd>
              Dr. Mehta • Room 3
             </dd>
            </div>
            <div>
             <dt>
              Estimated departure
             </dt>
             <dd>
              10:45 AM
             </dd>
            </div>
            <div>
             <dt>
              Expected return
             </dt>
             <dd>
              11:05 AM
             </dd>
            </div>
           </dl>
           <p>
            In the connected service, your spot remains preserved while patients A-21 through A-23 are seen. This HTML preview does not submit a request.
           </p>
           <a class="btn btn-secondary" href="../services/index.html">
            Back to Queue
           </a>
          </div>
         </details>
        </div>
       </section>
       <details>
        <summary>
         State B: Away (Held)
        </summary>
        <div class="disclosure-content">
         <h3>
          Your place is protected
         </h3>
         <p>
          Expected return: 11:05 AM. Grace hold until 11:20 AM.
         </p>
         <p>
          Show your pass at Desk A when you return. This is a design preview, not an active hold.
         </p>
        </div>
       </details>
       <details>
        <summary>
         State C: Rejoined
        </summary>
        <div class="disclosure-content">
         <h3>
          Welcome back
         </h3>
         <p>
          In this example, reception restores your original place when you return within the grace window.
         </p>
        </div>
       </details>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         CalmWait Hold Policy
        </h2>
        <p class="muted">
         Protected experience
        </p>
        <div class="section-gap">
         <ol class="list-clean">
          <li class="row">
           <span class="number number-complete">
            1
           </span>
           <div class="stack-small">
            <h3>
             Place is preserved
            </h3>
            <p>
             You keep your place while you're away. Your queue position progresses normally with physician pace.
            </p>
           </div>
          </li>
          <li class="row">
           <span class="number">
            2
           </span>
           <div class="stack-small">
            <h3>
             Proactive alerts
            </h3>
            <p>
             We'll alert you via SMS and app chime when 1 patient remains ahead, providing time to return to Room 3.
            </p>
           </div>
          </li>
          <li class="row">
           <span class="number">
            3
           </span>
           <div class="stack-small">
            <h3>
             Grace buffer protection
            </h3>
            <p>
             If you're delayed past grace time, you simply move back 3 places. You are never removed from the queue.
            </p>
           </div>
          </li>
         </ol>
        </div>
        <details>
         <summary>
          Why do we do this?
         </summary>
         <div class="disclosure-content">
          <p>
           Temporary leave gives you time away from the waiting room while keeping the clinic informed of your return.
          </p>
         </div>
        </details>
       </section>
       <section class="card">
        <h2 class="card-title">
         Recommended Leave Radius
        </h2>
        <p>
         Stay within 500m of South Pavilion (Courtyard, Healing Garden, Ground Floor Cafe) to guarantee a prompt 5-minute walk back.
        </p>
        <div class="safe-zone section-gap">
         <strong>
          South Pavilion • Safe 500m Zone
         </strong>
         <p>
          Healing Garden • Cafe 1st Fl • Courtyard
         </p>
        </div>
        <p class="section-gap small">
         Desk A Extension: x4901
        </p>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### step-out/style.css

```css
/* Step Out of Waiting Room: page-specific layout. Shared components live in css/global.css. */

.return-window { display: flex; flex-direction: column; gap: 16px; background: var(--soft); padding: 24px; border-radius: 8px; }
.return-window dd { font-size: 26px; color: var(--accent); }
.safe-zone { display: flex; flex-direction: column; gap: 12px; align-items: center; justify-content: center; min-height: 180px; padding: 20px; background: #ddebe4; border-radius: 8px; text-align: center; }
```

### sign-in/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Secure Patient &amp; Staff Portal at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Secure Patient &amp; Staff Portal | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="sign-in-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <div class="page">
    <header class="topbar">
     <a class="brand" href="../home/index.html">
      <span class="logo-tile">
       <img alt="" class="icon" src="../assets/icons/logo.svg"/>
      </span>
      <span>
       <strong class="brand-name">
        CalmWait
       </strong>
       <span class="brand-caption">
        SOUTH PAVILION CLINIC
       </span>
      </span>
     </a>
     <span class="badge">
      Verified Partner Site
     </span>
     <nav class="topbar-actions">
      <a class="btn btn-secondary" href="#intake">
       Patient Check-In
      </a>
      <a class="btn btn-secondary" href="../contact/index.html#help">
       Clinic Help
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        Secure Patient &amp; Staff Portal
       </h1>
       <p>
        South Pavilion Ambulatory Care Centre
       </p>
      </div>
      <div class="actions">
       <span class="badge badge-success">
        LIVE CLINIC: OPEN
       </span>
      </div>
     </header>
     <div class="content-columns">
      <div class="main-column">
       <div id="intake">
        <section class="card">
         <h2 class="card-title">
          Patient Pass &amp; Intake
         </h2>
         <nav aria-label="Sign-in type" class="pill-nav">
          <a href="#intake">
           Patient Pass &amp; Intake
          </a>
          <a href="../reception/index.html">
           Clinical Staff &amp; Reception
          </a>
         </nav>
         <h3>
          Instant Pass Lookup
         </h3>
         <p class="muted small">
          Mobile SMS Verification • No Password Required
         </p>
         <div class="banner section-gap">
          <h3>
           Have a printed paper ticket?
          </h3>
          <p>
           Point your mobile camera to restore your digital live pass.
          </p>
         </div>
         <form action="../home/index.html" class="stack section-gap" method="get">
          <div class="field">
           <label for="ticket-token">
            Queue Ticket Token / Pass #
           </label>
           <input id="ticket-token" placeholder="e.g. A-24 or P-108" required="" value="A-24"/>
          </div>
          <div class="field">
           <label for="last-name">
            Patient's Legal Last Name
           </label>
           <input autocomplete="family-name" id="last-name" placeholder="e.g. Mercer" required=""/>
          </div>
          <div class="field">
           <label for="dob">
            Date of Birth (Security Check)
           </label>
           <input autocomplete="bday" id="dob" required="" type="date"/>
          </div>
          <p class="small muted">
           Design preview. Submitting opens the sample pass and does not authenticate or transmit these fields.
          </p>
          <button class="btn" type="submit">
           Retrieve Live Waiting Pass
          </button>
         </form>
         <div class="sample-pass section-gap">
          <p class="eyebrow">
           Boarding metaphor anatomy • Pass #A-24 Sample
          </p>
          <h3 class="section-gap">
           TOKEN A-24
          </h3>
          <p>
           Bay 3 • Dr. Thorne
          </p>
          <p class="small">
           Checked-in: 09:42 AM • Stage 2 of 3: Vitals Complete
          </p>
         </div>
         <p class="small muted section-gap">
          Data Privacy Guarantee: Your mobile contact number is exclusively used for queue notices and room summons.
         </p>
        </section>
       </div>
       <section class="card">
        <h2 class="card-title">
         Need assistance checking in?
        </h2>
        <p>
         Speak to Reception Desk A or request wheelchair and translation escort.
        </p>
        <p class="section-gap">
         Ext. x4901
        </p>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         South Pavilion Reliability
        </h2>
        <div class="row">
         <img alt="92 percent transparency score" height="80" src="../assets/icons/transparency-gauge.svg" width="80"/>
         <div>
          <strong class="large-value accent">
           92%
          </strong>
          <p>
           Queue Transparency Index
          </p>
         </div>
        </div>
        <p class="section-gap">
         92% of scheduled arrivals seen within 8 minutes of target pass window.
        </p>
       </section>
       <section class="card">
        <h2 class="card-title">
         The CalmWait Waiting Standard
        </h2>
        <ol class="list-clean">
         <li class="row">
          <span class="number number-complete">
           1
          </span>
          <div class="stack-small">
           <h3>
            Predictable, Respectful Waiting
           </h3>
           <p>
            Real-time queue tracking, accurate doctor pacing updates, and zero surprise waiting room leaps. You always know your exact sequence.
           </p>
          </div>
         </li>
         <li class="row">
          <span class="number">
           2
          </span>
          <div class="stack-small">
           <h3>
            Step-Out Freedom
           </h3>
           <p>
            Activate a safe 15m or 30m leave pass from your phone to grab a tea in the atrium or visit the pharmacy without forfeiting your spot.
           </p>
          </div>
         </li>
         <li class="row">
          <span class="number">
           3
          </span>
          <div class="stack-small">
           <h3>
            Privacy First
           </h3>
           <p>
            Verified anonymized tokens protect your dignity. Public screens do not list medical names.
           </p>
          </div>
         </li>
        </ol>
       </section>
       <figure class="card">
        <img alt="Sunlit clinic atrium with indoor planting" class="full-image" src="../assets/images/clinic-atrium.jpeg"/>
        <figcaption class="section-gap">
         <span class="eyebrow">
          South Pavilion healing environment
         </span>
         <h3>
          Serene Waiting Spaces with Courtyard Garden Access
         </h3>
        </figcaption>
       </figure>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### sign-in/style.css

```css
/* Secure Patient & Staff Portal: page-specific layout. Shared components live in css/global.css. */

.sign-in-page .container { padding: 32px; max-width: 1280px; margin: 0 auto; }
.sign-in-page .topbar { min-height: 80px; }
.sample-pass { padding: 24px; border: 2px dashed var(--border); border-radius: 8px; background: var(--soft); }
.sign-in-page .main-column, .sign-in-page .rail { flex: 1 1 46%; }
@media (max-width: 767px) { .sign-in-page .container { padding: 20px 16px; } }
```

### reception/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Clinic Patient Stream at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Clinic Patient Stream | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="reception-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace staff-shell">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       SOUTH PAVILION CLINIC
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a aria-current="page" href="../reception/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-queue.svg"/>
      </span>
      Live Queue
     </a>
     <a href="../reception/index.html#doctor">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-doctor.svg"/>
      </span>
      Doctor Pacing &amp; Rooms
     </a>
     <a href="../reception/index.html#broadcast">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-comms.svg"/>
      </span>
      Patient Communications
     </a>
     <a href="../analytics/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-analytics.svg"/>
      </span>
      Analytics &amp; Reports
     </a>
     <a href="../about/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-settings.svg"/>
      </span>
      Clinic Settings
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        Clinic Patient Stream
       </h1>
       <p>
        Live Queue Console • South Pavilion • Desk A
       </p>
      </div>
      <div class="actions">
       <nav class="actions">
        <a class="btn btn-secondary" href="#doctor">
         Doctor pacing
        </a>
        <a class="btn btn-secondary" href="#broadcast">
         Delay Blast
        </a>
        <a class="btn btn-secondary" href="#priority">
         Triage Override
        </a>
       </nav>
      </div>
     </header>
     <div class="stats">
      <article class="stat">
       <p class="eyebrow">
        Waiting in pavilion
       </p>
       <strong class="stat-value">
        12
       </strong>
       <p class="small muted">
        8 on schedule • 4 approaching buffer
       </p>
      </article>
      <article class="stat">
       <p class="eyebrow">
        Stepped out (held)
       </p>
       <strong class="stat-value">
        3
       </strong>
       <p class="small muted">
        2 within perimeter • 1 returning now
       </p>
      </article>
      <article class="stat">
       <p class="eyebrow">
        Average wait now
       </p>
       <strong class="stat-value">
        ~25 min
       </strong>
       <p class="small muted">
        Pacing: Nominal • Target SLA ≤ 30m
       </p>
      </article>
      <article class="stat">
       <p class="eyebrow">
        Priority triage cases
       </p>
       <strong class="stat-value">
        2
       </strong>
       <p class="small muted">
        1 Clinical urgent • 1 Mobility aid
       </p>
      </article>
     </div>
     <div class="content-columns">
      <div class="main-column">
       <section class="card">
        <h2 class="card-title">
         Clinic Patient Stream
        </h2>
        <p class="small muted">
         All Patients (15) • Waiting In Pavilion (12) • Stepped Out (3)
        </p>
        <ul class="staff-patients">
         <li>
          <strong class="staff-token">
           A-20
          </strong>
          <div class="grow">
           <h3>
            Elena R.
           </h3>
           <p class="small muted">
            General Checkup • Self-Kiosk
           </p>
           <span class="badge">
            In Consultation
           </span>
          </div>
          <div class="small">
           <span class="eyebrow">
            Check-in
           </span>
           <p>
            10:12 AM
           </p>
           <span class="eyebrow">
            Wait
           </span>
           <p>
            31m
           </p>
          </div>
         </li>
         <li>
          <strong class="staff-token">
           A-21
          </strong>
          <div class="grow">
           <h3>
            Marcus T.
           </h3>
           <p class="small muted">
            Follow-up Lab Review
           </p>
           <span class="badge">
            Calling / Ready
           </span>
          </div>
          <div class="small">
           <span class="eyebrow">
            Check-in
           </span>
           <p>
            10:15 AM
           </p>
           <span class="eyebrow">
            Wait
           </span>
           <p>
            28m
           </p>
          </div>
         </li>
         <li>
          <strong class="staff-token">
           A-22
          </strong>
          <div class="grow">
           <h3>
            Sara K.
           </h3>
           <p class="small muted">
            Triage Tier 2 • Pre-vitals Taken
           </p>
           <span class="badge">
            Priority Triage
           </span>
          </div>
          <div class="small">
           <span class="eyebrow">
            Check-in
           </span>
           <p>
            10:20 AM
           </p>
           <span class="eyebrow">
            Wait
           </span>
           <p>
            23m
           </p>
          </div>
         </li>
         <li>
          <strong class="staff-token">
           A-23
          </strong>
          <div class="grow">
           <h3>
            Vikram S.
           </h3>
           <p class="small muted">
            Prescription Refill • App Registered
           </p>
           <span class="badge">
            Stepped Out • Protected Hold
           </span>
          </div>
          <div class="small">
           <span class="eyebrow">
            Check-in
           </span>
           <p>
            10:24 AM
           </p>
           <span class="eyebrow">
            Wait
           </span>
           <p>
            19m
           </p>
          </div>
         </li>
         <li>
          <strong class="staff-token">
           A-24
          </strong>
          <div class="grow">
           <h3>
            Aarav S.
           </h3>
           <p class="small muted">
            Pediatric Consultation (Minor)
           </p>
           <span class="badge">
            Waiting in Lounge
           </span>
          </div>
          <div class="small">
           <span class="eyebrow">
            Check-in
           </span>
           <p>
            10:29 AM
           </p>
           <span class="eyebrow">
            Wait
           </span>
           <p>
            14m
           </p>
          </div>
         </li>
         <li>
          <strong class="staff-token">
           A-25
          </strong>
          <div class="grow">
           <h3>
            Priya N.
           </h3>
           <p class="small muted">
            Annual Health Scan • Kiosk
           </p>
           <span class="badge">
            Waiting in Lounge
           </span>
          </div>
          <div class="small">
           <span class="eyebrow">
            Check-in
           </span>
           <p>
            10:33 AM
           </p>
           <span class="eyebrow">
            Wait
           </span>
           <p>
            10m
           </p>
          </div>
         </li>
         <li>
          <strong class="staff-token">
           A-26
          </strong>
          <div class="grow">
           <h3>
            David L.
           </h3>
           <p class="small muted">
            Hold Threshold Overdue
           </p>
           <span class="badge">
            Stepped Out • Grace +4m
           </span>
          </div>
          <div class="small">
           <span class="eyebrow">
            Check-in
           </span>
           <p>
            10:35 AM
           </p>
           <span class="eyebrow">
            Wait
           </span>
           <p>
            8m
           </p>
          </div>
         </li>
        </ul>
        <p class="small muted">
         Showing 7 of 15 queued patients • Sample queue from Figma
        </p>
       </section>
       <section class="card">
        <h2 class="card-title">
         Active Boarding Pass Telemetry
        </h2>
        <p class="eyebrow">
         Boarding pass stub #CP-8841
        </p>
        <h3 class="section-gap">
         Marcus T. (Token A-21)
        </h3>
        <p>
         General Practice Follow-up • Bloodwork review
        </p>
        <div class="token-box section-gap">
         <strong class="token">
          A-21
         </strong>
         <span>
          Currently calling
         </span>
        </div>
        <div class="section-gap">
         <dl class="metadata">
          <div>
           <dt>
            Target room
           </dt>
           <dd>
            Room 3
           </dd>
          </div>
          <div>
           <dt>
            Physician
           </dt>
           <dd>
            Dr. S. Mehta
           </dd>
          </div>
          <div>
           <dt>
            Wait elapsed
           </dt>
           <dd>
            28 min
           </dd>
          </div>
         </dl>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         Scan Returning Patient
        </h2>
        <p>
         Confirm patient return in one step. Auto-restores pavilion slot.
        </p>
        <div class="scan-box section-gap">
         <img alt="Sample boarding pass QR" height="144" src="../assets/icons/ticket-qr.svg" width="144"/>
         <p>
          Aim kiosk QR / safe pass
         </p>
        </div>
        <p class="small muted section-gap">
         Camera unavailable in this static preview. Use the manual token field to preview entry.
        </p>
        <form class="section-gap">
         <div class="field">
          <label for="manual-token">
           Manual token
          </label>
          <input id="manual-token" name="manual-token" type="text" value="A-24"/>
         </div>
        </form>
        <div class="banner section-gap">
         <p class="eyebrow">
          Active scanned result • Sample
         </p>
         <h3>
          Token A-24 • Rahul S. is back
         </h3>
         <p>
          Returned on time • Scanned at 11:02 AM • 3m buffer remaining
         </p>
        </div>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card" id="doctor">
        <h2 class="section-title">
         Doctor Pacing &amp; Telemetry
        </h2>
        <h3>
         Dr. S. Mehta • Room 3
        </h3>
        <form class="stack section-gap">
         <div class="segments">
          <label class="choice">
           <input checked="" name="doctor-status" type="radio" value="0"/>
           <span>
            Available
           </span>
          </label>
          <label class="choice">
           <input name="doctor-status" type="radio" value="1"/>
           <span>
            In Consult
           </span>
          </label>
          <label class="choice">
           <input name="doctor-status" type="radio" value="2"/>
           <span>
            On Break
           </span>
          </label>
          <label class="choice">
           <input name="doctor-status" type="radio" value="3"/>
           <span>
            Delayed
           </span>
          </label>
         </div>
         <div class="banner">
          <p class="eyebrow">
           Current patient in room
          </p>
          <h3>
           A-20 • Elena R.
          </h3>
          <p>
           8m of 12m
          </p>
         </div>
         <div class="field">
          <label for="delay-reason">
           Reason for delay / transition
          </label>
          <select id="delay-reason">
           <option>
            Specimen Handoff &amp; Sanitization
           </option>
           Urgent triage consultation
           Clinical break
          </select>
         </div>
         <div class="field">
          <label for="expected-next-door-chime">
           Expected next door chime
          </label>
          <input id="expected-next-door-chime" name="expected-next-door-chime" type="text" value="10:48 AM"/>
         </div>
         <p class="small muted">
          Preview controls. No room telemetry is sent.
         </p>
        </form>
       </section>
       <div id="priority">
        <section class="card">
         <h2 class="card-title">
          Clinical Priority Override
         </h2>
         <p>
          Audited clinical re-sequencing.
         </p>
         <p class="section-gap">
          <strong>
           Selected queue patient:
          </strong>
          Token A-24 • Aarav S. (Pos #4)
         </p>
         <form class="section-gap">
          <fieldset>
           <legend>
            Required reason for audit log
           </legend>
           <div class="segments">
            <label class="choice">
             <input checked="" name="priority" type="radio" value="0"/>
             <span>
              Urgent medical need (Triage Tier 2/3)
             </span>
            </label>
            <label class="choice">
             <input name="priority" type="radio" value="1"/>
             <span>
              Elderly, mobility, or accessibility need
             </span>
            </label>
            <label class="choice">
             <input name="priority" type="radio" value="2"/>
             <span>
              Emergency departmental referral handoff
             </span>
            </label>
           </div>
          </fieldset>
         </form>
         <div class="banner section-gap">
          <p class="eyebrow">
           Priority impact preview
          </p>
          <h3>
           +4 to +6 min / case
          </h3>
          <p>
           Emergency walk-in. Estimated impact: +8 to +12 minutes. Your position remains protected.
          </p>
         </div>
        </section>
       </div>
       <section class="card" id="broadcast">
        <h2 class="section-title">
         Delay Broadcast Composer
        </h2>
        <p>
         Transparent notifications reduce inquiries at the desk.
        </p>
        <form class="stack section-gap">
         <div class="field">
          <label for="delay-message">
           Live message preview
          </label>
          <textarea id="delay-message">CalmWait Alert: We're running about 10 minutes behind. Dr. Mehta is currently attending to an urgent triage consultation. Your spot remains secured.</textarea>
         </div>
         <fieldset>
          <legend>
           Recipient target
          </legend>
          <div class="segments">
           <label class="choice">
            <input checked="" name="recipients" type="radio" value="0"/>
            <span>
             All Dr. Mehta • 15 queued patients
            </span>
           </label>
           <label class="choice">
            <input name="recipients" type="radio" value="1"/>
            <span>
             Waiting Lounge • 4 in room buffer
            </span>
           </label>
          </div>
         </fieldset>
         <p class="small muted">
          Sending broadcasts requires the clinic backend. No messages are sent by this preview.
         </p>
        </form>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### reception/style.css

```css
/* Clinic Patient Stream: page-specific layout. Shared components live in css/global.css. */

.staff-patients { display: flex; flex-direction: column; padding: 0; margin: 16px 0; list-style: none; }
.staff-patients li { display: flex; gap: 16px; align-items: flex-start; padding: 20px 0; border-bottom: 1px solid var(--border); }
.staff-patients li:nth-child(5) { padding: 20px 12px; background: var(--soft); }
.staff-token { font-size: 20px; color: var(--accent); width: 52px; flex: 0 0 52px; }
.scan-box { display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 20px; padding: 30px; background: var(--soft); border: 2px dashed var(--border); border-radius: 10px; }
@media (max-width: 367px) { .staff-patients li { flex-wrap: wrap; } }
```

### analytics/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Waiting-Room Operations &amp; Flow Analytics at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Waiting-Room Operations &amp; Flow Analytics | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="analytics-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace staff-shell">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       SOUTH PAVILION CLINIC
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../reception/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-queue.svg"/>
      </span>
      Live Queue
     </a>
     <a href="../reception/index.html#doctor">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-doctor.svg"/>
      </span>
      Doctor Pacing &amp; Rooms
     </a>
     <a href="../reception/index.html#broadcast">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-comms.svg"/>
      </span>
      Patient Communications
     </a>
     <a aria-current="page" href="../analytics/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-analytics.svg"/>
      </span>
      Analytics &amp; Reports
     </a>
     <a href="../about/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-settings.svg"/>
      </span>
      Clinic Settings
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        Waiting-Room Operations &amp; Flow Analytics
       </h1>
       <p>
        Identifying bottlenecks, pacing variances, and patient flow dynamics across South Pavilion
       </p>
      </div>
      <div class="actions">
      </div>
     </header>
     <p class="notice">
      Today • All Physicians (4 active) • Sample data from the Figma design
     </p>
     <div class="stats">
      <article class="stat">
       <p class="eyebrow">
        Average wait time
       </p>
       <strong class="stat-value">
        28 min
       </strong>
       <p class="small muted">
        Target SLA ≤ 25 min • +3m vs prior 7d
       </p>
      </article>
      <article class="stat">
       <p class="eyebrow">
        Longest recorded wait
       </p>
       <strong class="stat-value">
        74 min
       </strong>
       <p class="small muted">
        Peak Tue 11:20 AM • Tier-3 Triage Chain
       </p>
      </article>
      <article class="stat">
       <p class="eyebrow">
        No-show rate
       </p>
       <strong class="stat-value">
        6%
       </strong>
       <p class="small muted">
        14 of 234 registered • -1.4% improvement
       </p>
      </article>
      <article class="stat">
       <p class="eyebrow">
        Step-out safe passes
       </p>
       <strong class="stat-value">
        18%
       </strong>
       <p class="small muted">
        42 patients on pass • 81% return rate
       </p>
      </article>
     </div>
     <section class="card">
      <h2 class="card-title">
       Today's Transparency Score
      </h2>
      <div class="transparency-layout">
       <div class="stack">
        <strong class="large-value accent">
         92%
        </strong>
        <p>
         How openly we kept patients informed today.
        </p>
        <span class="badge badge-success">
         +4% vs prior week
        </span>
       </div>
       <div class="stack grow">
        <div>
         <div class="card-heading small">
          <span>
           Delay reasons provided
          </span>
          <strong>
           96%
          </strong>
         </div>
         <div class="meter">
          <span class="meter-fill fraction-96">
          </span>
         </div>
        </div>
        <div>
         <div class="card-heading small">
          <span>
           Queue updated live
          </span>
          <strong>
           94%
          </strong>
         </div>
         <div class="meter">
          <span class="meter-fill fraction-94">
          </span>
         </div>
        </div>
        <div>
         <div class="card-heading small">
          <span>
           Doctor status available
          </span>
          <strong>
           100%
          </strong>
         </div>
         <div class="meter">
          <span class="meter-fill fraction-100">
          </span>
         </div>
        </div>
        <div>
         <div class="card-heading small">
          <span>
           Notifications on time
          </span>
          <strong>
           81%
          </strong>
         </div>
         <div class="meter">
          <span class="meter-fill fraction-81">
          </span>
         </div>
        </div>
       </div>
      </div>
     </section>
     <div class="section-gap">
      <div class="content-columns">
       <div class="main-column">
        <section class="card">
         <h2 class="card-title">
          Average Wait Time by Hour of Day
         </h2>
         <figure class="hour-chart">
          <figcaption class="small muted">
           Busiest Window: 11 AM – 12 PM (46 min avg). SLA target: 25 min.
          </figcaption>
          <div class="chart-bars">
           <div class="chart-column">
            <strong class="small">
             14m
            </strong>
            <span aria-hidden="true" class="hour-bar hour-0">
            </span>
            <span class="small">
             9 AM
            </span>
           </div>
           <div class="chart-column">
            <strong class="small">
             22m
            </strong>
            <span aria-hidden="true" class="hour-bar hour-1">
            </span>
            <span class="small">
             10 AM
            </span>
           </div>
           <div class="chart-column">
            <strong class="small">
             46m
            </strong>
            <span aria-hidden="true" class="hour-bar hour-2">
            </span>
            <span class="small">
             11 AM
            </span>
           </div>
           <div class="chart-column">
            <strong class="small">
             38m
            </strong>
            <span aria-hidden="true" class="hour-bar hour-3">
            </span>
            <span class="small">
             12 PM
            </span>
           </div>
           <div class="chart-column">
            <strong class="small">
             18m
            </strong>
            <span aria-hidden="true" class="hour-bar hour-4">
            </span>
            <span class="small">
             1 PM
            </span>
           </div>
           <div class="chart-column">
            <strong class="small">
             26m
            </strong>
            <span aria-hidden="true" class="hour-bar hour-5">
            </span>
            <span class="small">
             2 PM
            </span>
           </div>
           <div class="chart-column">
            <strong class="small">
             32m
            </strong>
            <span aria-hidden="true" class="hour-bar hour-6">
            </span>
            <span class="small">
             3 PM
            </span>
           </div>
           <div class="chart-column">
            <strong class="small">
             29m
            </strong>
            <span aria-hidden="true" class="hour-bar hour-7">
            </span>
            <span class="small">
             4 PM
            </span>
           </div>
           <div class="chart-column">
            <strong class="small">
             19m
            </strong>
            <span aria-hidden="true" class="hour-bar hour-8">
            </span>
            <span class="small">
             5 PM
            </span>
           </div>
           <div class="chart-column">
            <strong class="small">
             12m
            </strong>
            <span aria-hidden="true" class="hour-bar hour-9">
            </span>
            <span class="small">
             6 PM
            </span>
           </div>
          </div>
         </figure>
         <p class="small muted section-gap">
          Wait times climb after 10:00 AM, peak between 11:00 AM and 12:00 PM, and return below the 25-minute benchmark after the 1:00 PM rotation.
         </p>
        </section>
        <section class="card">
         <h2 class="card-title">
          Wait Time by Physician
         </h2>
         <ul class="list-clean">
          <li class="row spread">
           <div>
            <strong>
             Dr. S. Mehta
            </strong>
            <p class="small muted">
             Room 3 • Gen Medicine • 68 visits
            </p>
           </div>
           <strong class="accent">
            34 min
           </strong>
          </li>
          <li class="row spread">
           <div>
            <strong>
             Dr. A. Rao
            </strong>
            <p class="small muted">
             Room 1 • Pediatrics • 54 visits
            </p>
           </div>
           <strong class="accent">
            22 min
           </strong>
          </li>
          <li class="row spread">
           <div>
            <strong>
             Dr. K. Patel
            </strong>
            <p class="small muted">
             Room 4 • Cardiology • 42 visits
            </p>
           </div>
           <strong class="accent">
            31 min
           </strong>
          </li>
          <li class="row spread">
           <div>
            <strong>
             Dr. E. Zhang
            </strong>
            <p class="small muted">
             Room 2 • Family Practice • 70 visits
            </p>
           </div>
           <strong class="accent">
            21 min
           </strong>
          </li>
         </ul>
         <p class="small muted section-gap">
          Variance delta: ±13 min • 2 On Track • 2 Elevated
         </p>
        </section>
        <section class="card">
         <h2 class="card-title">
          Delay Root Causes Breakdown
         </h2>
         <ul class="list-clean">
          <li class="row spread">
           <span>
            Urgent triage cases (ESI Tier 2/3)
           </span>
           <strong>
            32%
           </strong>
          </li>
          <li class="row spread">
           <span>
            Consultations exceeding scheduled block
           </span>
           <strong>
            27%
           </strong>
          </li>
          <li class="row spread">
           <span>
            Late patient check-ins &gt;10 min
           </span>
           <strong>
            14%
           </strong>
          </li>
          <li class="row spread">
           <span>
            Room sanitization &amp; transition pauses
           </span>
           <strong>
            11%
           </strong>
          </li>
          <li class="row spread">
           <span>
            Kiosk registration &amp; ID verification
           </span>
           <strong>
            9%
           </strong>
          </li>
          <li class="row spread">
           <span>
            Other clinical / clerical delays
           </span>
           <strong>
            7%
           </strong>
          </li>
         </ul>
        </section>
        <section class="card">
         <h2 class="card-title">
          Step-Out Safe Pass Dynamics &amp; No-Show Trajectory
         </h2>
         <p>
          42 Step-Outs Authorized
         </p>
         <div class="section-gap">
          <dl class="metadata">
           <div>
            <dt>
             On time
            </dt>
            <dd>
             64% • 27 pts
            </dd>
           </div>
           <div>
            <dt>
             Grace
            </dt>
            <dd>
             17% • 7 pts
            </dd>
           </div>
           <div>
            <dt>
             Forfeited
            </dt>
            <dd>
             19% • 8 pts
            </dd>
           </div>
          </dl>
         </div>
         <h3 class="section-gap">
          No-shows by day of week
         </h3>
         <div class="section-gap">
          <dl class="metadata">
           <div>
            <dt>
             Mon
            </dt>
            <dd>
             4.8%
            </dd>
           </div>
           <div>
            <dt>
             Tue
            </dt>
            <dd>
             7.2%
            </dd>
           </div>
           <div>
            <dt>
             Wed
            </dt>
            <dd>
             5.1%
            </dd>
           </div>
           <div>
            <dt>
             Thu
            </dt>
            <dd>
             8.6%
            </dd>
           </div>
           <div>
            <dt>
             Fri
            </dt>
            <dd>
             4.3%
            </dd>
           </div>
          </dl>
         </div>
        </section>
       </div>
       <aside aria-label="Visit details" class="rail">
        <section class="card">
         <h2 class="card-title">
          Operational Insights &amp; Recommendations
         </h2>
         <div class="stack">
          <article class="insight">
           <h3>
            Pacing &amp; Intake Optimization
           </h3>
           <p class="section-gap">
            Wait times peak at 11:00 AM (46m avg). Consider shifting 2 intake slots to 9:00 AM or activating the overflow triage station between 10:30 AM and 12:30 PM.
           </p>
           <p class="section-gap">
            <span class="badge">
             Impact: ~9 min reduction
            </span>
           </p>
          </article>
          <article class="insight">
           <h3>
            Dedicated Urgent Buffer
           </h3>
           <p class="section-gap">
            Urgent cases drive 32% of total accumulated delay. A reserved 15-minute emergency buffer per 3-hour physician block can limit schedule delays.
           </p>
           <p class="section-gap">
            <span class="badge">
             Dampens 74m spikes
            </span>
           </p>
          </article>
          <article class="insight">
           <h3>
            Step-Out SMS Chime
           </h3>
           <p class="section-gap">
            19% of step-out patients forfeit or return late. Dispatch a reminder 10 minutes before the return-by deadline.
           </p>
           <p class="section-gap">
            <span class="badge">
             Configuration ready
            </span>
           </p>
          </article>
         </div>
        </section>
        <section class="card">
         <h2 class="card-title">
          Telemetric Station Node
         </h2>
         <div class="stack">
          <dl class="metadata">
           <div>
            <dt>
             Exam rooms
            </dt>
            <dd>
             4 of 4 occupied
            </dd>
           </div>
           <div>
            <dt>
             Pass scanners
            </dt>
            <dd>
             2 kiosks online
            </dd>
           </div>
           <div>
            <dt>
             Room turnaround
            </dt>
            <dd>
             4.2 min
            </dd>
           </div>
          </dl>
         </div>
        </section>
       </aside>
      </div>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### analytics/style.css

```css
/* Waiting-Room Operations & Flow Analytics: page-specific layout. Shared components live in css/global.css. */

.transparency-layout { display: flex; align-items: center; gap: 40px; }
.analytics-page .main-column { flex-basis: 66%; }
.analytics-page .rail { flex-basis: 32%; }
.chart-bars { display: flex; align-items: flex-end; gap: 8px; height: 260px; margin-top: 20px; padding-bottom: 12px; border-bottom: 1px solid var(--border); }
.chart-column { display: flex; flex: 1; flex-direction: column; justify-content: flex-end; align-items: center; gap: 8px; min-width: 0; text-align: center; }
.hour-bar { width: 100%; background: #0a6e78; border-radius: 4px 4px 0 0; }
.hour-2 { background: #d49d27; }
.insight { padding-bottom: 24px; border-bottom: 1px solid var(--border); }
.insight:last-child { border-bottom: 0; padding-bottom: 0; }
@media (max-width: 767px) { .transparency-layout { flex-direction: column; align-items: stretch; } .chart-bars { gap: 4px; } .chart-column .small { font-size: 10px; } }
.hour-0 { height: 56px; }
.hour-1 { height: 88px; }
.hour-2 { height: 184px; }
.hour-3 { height: 152px; }
.hour-4 { height: 72px; }
.hour-5 { height: 104px; }
.hour-6 { height: 128px; }
.hour-7 { height: 116px; }
.hour-8 { height: 76px; }
.hour-9 { height: 48px; }
```

### caregiver/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Caregiver Dashboard at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Caregiver Dashboard | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="caregiver-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       PATIENT PORTAL
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../home/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/visit.svg"/>
      </span>
      Visit
     </a>
     <a href="../services/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/queue.svg"/>
      </span>
      Queue
     </a>
     <a href="../blog/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/progress.svg"/>
      </span>
      Progress
     </a>
     <a href="../contact/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/alerts.svg"/>
      </span>
      Alerts
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        Dadaji (Aarav)
       </h1>
       <p>
        Aarav Shah, 75 yrs • Updated 4 min ago
       </p>
      </div>
      <div class="actions">
       <span class="badge">
        Primary caregiver: Ananya (Daughter)
       </span>
      </div>
     </header>
     <div class="content-columns">
      <div class="main-column">
       <section class="card banner-warning">
        <h2 class="card-title">
         1 Dose Attention Needed
        </h2>
        <span class="badge badge-warning">
         45m past due
        </span>
        <p class="section-gap">
         Dadaji hasn't logged the
         <strong>
          8:00 AM Metformin (500mg)
         </strong>
         . Morning Lisinopril (10mg) confirmed taken at 8:05 AM.
        </p>
        <p class="section-gap">
         Contact Dadaji to check his medication record.
        </p>
       </section>
       <section class="card">
        <h2 class="card-title">
         Today's Schedule
        </h2>
        <p class="small muted">
         2 of 4 logged
        </p>
        <ul class="dose-list">
         <li>
          <div class="row spread wrap">
           <h3>
            Lisinopril 10mg
           </h3>
           <span class="badge">
            8:05 AM
           </span>
          </div>
          <p class="muted">
           Blood pressure • 1 tablet with water
          </p>
          <p class="small">
           8:00 AM Routine
          </p>
         </li>
         <li>
          <div class="row spread wrap">
           <h3>
            Metformin 500mg
           </h3>
           <span class="badge badge-warning">
            Missed
           </span>
          </div>
          <p class="muted">
           Blood sugar • 1 tablet after breakfast
          </p>
          <p class="small">
           8:00 AM (Past Due)
          </p>
         </li>
         <li>
          <div class="row spread wrap">
           <h3>
            Calcium + Vit D3
           </h3>
           <span class="badge">
            In 2 hrs
           </span>
          </div>
          <p class="muted">
           Bone health • 1 chewable with lunch
          </p>
          <p class="small">
           1:00 PM Afternoon
          </p>
         </li>
         <li>
          <div class="row spread wrap">
           <h3>
            Atorvastatin 20mg
           </h3>
           <span class="badge">
            Tonight
           </span>
          </div>
          <p class="muted">
           Cholesterol • 1 tablet before bed
          </p>
          <p class="small">
           8:00 PM Tonight
          </p>
         </li>
        </ul>
       </section>
       <section class="card">
        <h2 class="card-title">
         Weekly Adherence
        </h2>
        <p>
         6 of 7 days completed (86% on track)
        </p>
        <strong class="large-value accent">
         86%
        </strong>
        <div class="week-days">
         <span>
          <strong>
           ✓
          </strong>
          Mon
         </span>
         <span>
          <strong>
           ✓
          </strong>
          Tue
         </span>
         <span>
          <strong>
           ✓
          </strong>
          Wed
         </span>
         <span>
          <strong>
           ✓
          </strong>
          Thu
         </span>
         <span>
          <strong>
           ✓
          </strong>
          Fri
         </span>
         <span>
          <strong>
           ✓
          </strong>
          Sat
         </span>
         <span>
          <strong>
           ○
          </strong>
          Today
         </span>
        </div>
        <p>
         Dadaji has 100% evening adherence this month. Morning schedule missed once.
        </p>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         Recent Health Vitals
        </h2>
        <div class="stack">
         <article>
          <p class="eyebrow">
           Blood Pressure
          </p>
          <strong class="stat-value">
           124/82
           <span class="small">
            mmHg
           </span>
          </strong>
          <span class="badge badge-success">
           Normal
          </span>
          <p class="small muted section-gap">
           Today, 8:15 AM • Omron Smart Monitor
          </p>
         </article>
         <article class="rule">
          <p class="eyebrow">
           Fasting Glucose
          </p>
          <strong class="stat-value">
           118
           <span class="small">
            mg/dL
           </span>
          </strong>
          <span class="badge badge-success">
           On Target
          </span>
          <p class="small muted section-gap">
           Today, 7:45 AM • Before Breakfast
          </p>
         </article>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         Upcoming &amp; Refills
        </h2>
        <div class="stack">
         <article>
          <h3>
           Dr. Mehta Consultation
          </h3>
          <p>
           In 2 days • Tuesday, 10:30 AM • Sunrise Clinic
          </p>
          <p class="muted section-gap">
           Routine cardiology review &amp; prescription renewal. Room 3.
          </p>
          <p class="section-gap">
           <a class="btn btn-secondary" href="../home/index.html">
            View Clinic Pass &amp; Directions
           </a>
          </p>
         </article>
         <article class="rule">
          <h3>
           Metformin 500mg Refill
          </h3>
          <p>
           5 days left
          </p>
          <p class="muted section-gap">
           Last filled at CVS Health #4821. Auto-refill ready for confirmation.
          </p>
          <details>
           <summary>
            Refill details
           </summary>
           <div class="disclosure-content">
            <p>
             This preview cannot order medication. Contact the pharmacy to arrange a refill.
            </p>
           </div>
          </details>
         </article>
        </div>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### caregiver/style.css

```css
/* Caregiver Dashboard: page-specific layout. Shared components live in css/global.css. */

.caregiver-page .container { max-width: 1120px; margin: 0 auto; }
.dose-list { display: flex; flex-direction: column; padding: 0; list-style: none; }
.dose-list li { display: flex; flex-direction: column; gap: 12px; padding: 24px 0; border-bottom: 1px solid var(--border); }
.dose-list li:last-child { border-bottom: 0; padding-bottom: 0; }
.week-days { display: flex; justify-content: space-between; gap: 8px; margin: 24px 0; }
.week-days span { display: flex; flex-direction: column; align-items: center; gap: 8px; font-size: 12px; }
.week-days strong { display: flex; align-items: center; justify-content: center; width: 28px; height: 28px; border-radius: 50%; background: #e7f5eb; color: #16823c; }
```

### settings/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Settings at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Settings | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="settings-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       PATIENT PORTAL
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../home/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/visit.svg"/>
      </span>
      Visit
     </a>
     <a href="../services/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/queue.svg"/>
      </span>
      Queue
     </a>
     <a href="../blog/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/progress.svg"/>
      </span>
      Progress
     </a>
     <a href="../contact/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/alerts.svg"/>
      </span>
      Alerts
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        Settings
       </h1>
       <p>
        Customize your display, alerts, and caregivers for effortless reading and peace of mind.
       </p>
      </div>
      <div class="actions">
      </div>
     </header>
     <div class="content-columns">
      <div class="main-column">
       <section class="card">
        <h2 class="card-title">
         Live Display Preview
        </h2>
        <div class="display-preview">
         <div class="card-heading">
          <h3>
           Morning Dose
          </h3>
          <span>
           8:00 AM
          </span>
         </div>
         <strong>
          Lisinopril 10mg
         </strong>
         <p>
          Take 1 tablet with full glass of water
         </p>
         <p class="small">
          High Contrast: ON • Text Size: Large
         </p>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         Display &amp; Accessibility
        </h2>
        <p>
         Adjust visuals to your comfort level
        </p>
        <form class="section-gap">
         <fieldset>
          <legend>
           App Text Size
          </legend>
          <div class="segments">
           <label class="choice">
            <input checked="" name="text-size" type="radio" value="0"/>
            <span>
             Normal • 18px
            </span>
           </label>
           <label class="choice">
            <input name="text-size" type="radio" value="1"/>
            <span>
             Large • 22px
            </span>
           </label>
           <label class="choice">
            <input name="text-size" type="radio" value="2"/>
            <span>
             Extra • 26px
            </span>
           </label>
          </div>
         </fieldset>
         <label class="toggle-row">
          <span>
           <strong>
            High-contrast mode
           </strong>
           <span class="muted small">
            Sharper edges and enhanced clarity
           </span>
          </span>
          <input checked="" name="high-contrast-mode" type="checkbox"/>
         </label>
         <label class="toggle-row">
          <span>
           <strong>
            Read-aloud voice
           </strong>
           <span class="muted small">
            Speaks medication names and reminders clearly out loud
           </span>
          </span>
          <input checked="" name="read-aloud-voice" type="checkbox"/>
         </label>
         <label class="toggle-row">
          <span>
           <strong>
            Reduce animations
           </strong>
           <span class="muted small">
            Disables moving items for steadiness
           </span>
          </span>
          <input checked="" name="reduce-animations" type="checkbox"/>
         </label>
         <p class="small muted section-gap">
          These controls preview selection states only; they do not change device settings.
         </p>
        </form>
       </section>
       <section class="card">
        <h2 class="card-title">
         Reminders &amp; Alerts
        </h2>
        <p>
         Keep track of your scheduled doses
        </p>
        <form class="section-gap">
         <div class="field">
          <label for="ringtone">
           Alert Ringtone
          </label>
          <select id="ringtone">
           <option>
            Gentle Chime (High Pitch)
           </option>
           Standard
          </select>
         </div>
         <label class="toggle-row">
          <span>
           <strong>
            Loud urgent alarm
           </strong>
           <span class="muted small">
            Plays an urgent reminder
           </span>
          </span>
          <input checked="" name="loud-urgent-alarm" type="checkbox"/>
         </label>
         <fieldset class="section-gap">
          <legend>
           Remind again after (Snooze time)
          </legend>
          <div class="segments">
           <label class="choice">
            <input checked="" name="snooze" type="radio" value="0"/>
            <span>
             5 min
            </span>
           </label>
           <label class="choice">
            <input name="snooze" type="radio" value="1"/>
            <span>
             10 min
            </span>
           </label>
           <label class="choice">
            <input name="snooze" type="radio" value="2"/>
            <span>
             15 min
            </span>
           </label>
          </div>
         </fieldset>
         <label class="toggle-row">
          <span>
           <strong>
            Alert caregiver if dose is missed
           </strong>
           <span class="muted small">
            Sends text to family if medication is not logged within 30 minutes
           </span>
          </span>
          <input checked="" name="alert-caregiver-if-dose-is-missed" type="checkbox"/>
         </label>
        </form>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         Linked Caregivers
        </h2>
        <p>
         2 trusted individuals linked to your schedule
        </p>
        <div class="stack section-gap">
         <article>
          <div class="row">
           <span class="avatar">
            AS
           </span>
           <div>
            <h3>
             Ananya Shah
            </h3>
            <p>
             Daughter • Primary Contact
            </p>
            <a href="tel:+15552348901">
             +1 (555) 234-8901
            </a>
            <p class="small muted">
             Receives miss alerts
            </p>
           </div>
          </div>
          <details>
           <summary>
            Remove Caregiver
           </summary>
           <div class="disclosure-content">
            <p>
             Removing a caregiver would stop their dose alerts. This static preview does not remove anyone.
            </p>
           </div>
          </details>
         </article>
         <article class="rule">
          <div class="row">
           <span class="avatar">
            RM
           </span>
           <div>
            <h3>
             Dr. Rajesh Mehta
            </h3>
            <p>
             Home Nurse
            </p>
            <a href="tel:+15557894321">
             +1 (555) 789-4321
            </a>
            <p class="small muted">
             Weekly reports only
            </p>
           </div>
          </div>
         </article>
         <details>
          <summary>
           Invite a Caregiver
          </summary>
          <div class="disclosure-content">
           <p>
            Caregiver invitations require a connected account.
           </p>
          </div>
         </details>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         Profile &amp; Language
        </h2>
        <h3>
         Aarav Shah
        </h3>
        <p>
         Born: Aug 14, 1948 (Age 75)
        </p>
        <form class="section-gap">
         <fieldset>
          <legend>
           Preferred Language
          </legend>
          <div class="segments">
           <label class="choice">
            <input checked="" name="preferred-language" type="radio" value="0"/>
            <span>
             English
            </span>
           </label>
           <label class="choice">
            <input name="preferred-language" type="radio" value="1"/>
            <span>
             ગુજરાતી
            </span>
           </label>
           <label class="choice">
            <input name="preferred-language" type="radio" value="2"/>
            <span>
             हिन्दी
            </span>
           </label>
          </div>
         </fieldset>
        </form>
        <div class="banner section-gap">
         <p class="eyebrow">
          Emergency contact
         </p>
         <p>
          Ananya Shah:
          <a href="tel:+15552348901">
           +1 (555) 234-8901
          </a>
         </p>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         Live Support Desk
        </h2>
        <p>
         Free toll-free assistance is available 24 hours a day, 7 days a week.
        </p>
        <p class="section-gap">
         <a class="btn btn-secondary" href="../contact/index.html#help">
          Clinic assistance
         </a>
        </p>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### settings/style.css

```css
/* Settings: page-specific layout. Shared components live in css/global.css. */

.settings-page .container { max-width: 1120px; margin: 0 auto; }
.display-preview { display: flex; flex-direction: column; gap: 16px; padding: 24px; border: 2px solid var(--accent); background: #ebf5ff; border-radius: 8px; }
.display-preview > strong { font-size: 26px; }
.settings-page details { margin-top: 16px; }
```

### live-queue/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Live Queue at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Live Queue | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="services-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       PATIENT PORTAL
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../home/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/visit.svg"/>
      </span>
      Visit
     </a>
     <a aria-current="page" href="../services/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/queue.svg"/>
      </span>
      Queue
     </a>
     <a href="../blog/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/progress.svg"/>
      </span>
      Progress
     </a>
     <a href="../contact/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/alerts.svg"/>
      </span>
      Alerts
     </a>
    </nav>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        Live Queue
        <span class="badge">
         SOUTH WING
        </span>
       </h1>
       <p>
        Updated 2 min ago • Doctor Mehta (General Medicine)
       </p>
      </div>
      <div class="actions">
       <a class="btn btn-secondary" href="index.html">
        Refresh status
       </a>
      </div>
     </header>
     <div class="content-columns">
      <div class="main-column">
       <section class="card">
        <h2 class="card-title">
         Estimated wait window
        </h2>
        <div class="row spread wrap">
         <div>
          <strong class="large-value accent">
           20–35
          </strong>
          min
         </div>
         <div>
          <p class="eyebrow">
           Ahead of you
          </p>
          <h3>
           3 patients
          </h3>
         </div>
        </div>
        <div class="wait-scale">
         <span>
          Min: 20m
         </span>
         <strong>
          Most likely around 25 min
         </strong>
         <span>
          Max: 35m+
         </span>
        </div>
        <div aria-hidden="true" class="wait-track">
         <span>
         </span>
        </div>
        <div class="row spread small">
         <span>
          0m
         </span>
         <span>
          20m
         </span>
         <span>
          25m
         </span>
         <span>
          35m
         </span>
         <span>
          60m
         </span>
        </div>
        <p class="section-gap muted">
         Estimate updated: 2 urgent triage cases accommodated. Pacing calibrated dynamically.
        </p>
        <p class="small section-gap">
         This is an estimate. It can change if a consultation requires additional clinical care or emergency evaluation.
        </p>
       </section>
       <section class="card">
        <h2 class="card-title">
         Dr. Mehta — General Medicine
        </h2>
        <p class="muted">
         Exam Room 3 • South Pavilion Wing
        </p>
        <p class="section-gap">
         <span class="badge badge-success">
          IN CONSULTATION ✓
         </span>
        </p>
        <div class="stack section-gap">
         <dl class="metadata">
          <div>
           <dt>
            Now serving
           </dt>
           <dd>
            Token A-20
           </dd>
          </div>
          <div>
           <dt>
            Current consultation
           </dt>
           <dd>
            ~8 mins in room
           </dd>
          </div>
          <div>
           <dt>
            Typical visit pacing
           </dt>
           <dd>
            9–11 mins
           </dd>
          </div>
         </dl>
        </div>
       </section>
       <section class="card banner-warning">
        <h2 class="card-title">
         Minor Schedule Adjustment
        </h2>
        <span class="badge badge-warning">
         +5–10 MINS
        </span>
        <p class="section-gap">
         We're running a little behind. Dr. Mehta is seeing
         <strong>
          2 urgent triage cases
         </strong>
         first. This can add approximately 5 to 10 minutes to the general schedule.
        </p>
        <p class="section-gap">
         All queued patients retain their relative priority sequence. Thank you for your patience.
        </p>
        <p class="section-gap">
         <a class="btn btn-secondary" href="../step-out/index.html">
          Step out for a while
         </a>
        </p>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         2 priority cases were added ahead of you
        </h2>
        <dl class="metadata">
         <div>
          <dt>
           Reason
          </dt>
          <dd>
           Emergency walk-in
          </dd>
         </div>
         <div>
          <dt>
           Estimated impact
          </dt>
          <dd>
           +8 to +12 minutes
          </dd>
         </div>
        </dl>
        <details>
         <summary>
          Why do some people go first?
         </summary>
         <div class="disclosure-content">
          <p>
           Clinical urgency determines triage priority. Your token keeps its place relative to other routine consultations.
          </p>
         </div>
        </details>
       </section>
       <section class="card">
        <h2 class="card-title">
         Waiting Sequence
        </h2>
        <p class="muted small">
         Tokens only to protect patient privacy.
        </p>
        <ol class="queue-list">
         <li class="queue-item">
          <span class="number">
           1
          </span>
          <div class="grow">
           <strong>
            Token A-20
           </strong>
           <p class="small muted">
            Exam Room 3
           </p>
          </div>
          <span class="badge">
           In consultation
          </span>
         </li>
         <li class="queue-item">
          <span class="number">
           2
          </span>
          <div class="grow">
           <strong>
            Token A-21
           </strong>
           <p class="small muted">
            Lounge Waiting Area
           </p>
          </div>
          <span class="badge">
           Next in line
          </span>
         </li>
         <li class="queue-item">
          <span class="number">
           3
          </span>
          <div class="grow">
           <strong>
            Token A-22
           </strong>
           <p class="small muted">
            Triage Bay
           </p>
          </div>
          <span class="badge">
           Priority triage
          </span>
         </li>
         <li class="queue-item">
          <span class="number">
           4
          </span>
          <div class="grow">
           <strong>
            Token A-23
           </strong>
           <p class="small muted">
            Courtyard Garden
           </p>
          </div>
          <span class="badge">
           Stepped out
          </span>
         </li>
         <li class="queue-item queue-item-you">
          <span class="number">
           5
          </span>
          <div class="grow">
           <strong>
            Token A-24
           </strong>
           <p class="small muted">
            Est. call: ~25 mins (approx 10:47 AM)
           </p>
          </div>
          <span class="badge">
           You • Pos #4
          </span>
         </li>
         <li class="queue-item">
          <span class="number">
           6
          </span>
          <div class="grow">
           <strong>
            Token A-25
           </strong>
           <p class="small muted">
            Check-in Kiosk 2
           </p>
          </div>
          <span class="badge">
           Checked in
          </span>
         </li>
        </ol>
        <p class="small muted section-gap">
         Patient anonymization active
        </p>
       </section>
       <section class="card">
        <h2 class="card-title">
         What could change your wait?
        </h2>
        <div class="stack">
         <article class="scenario">
          <h3>
           If the queue moves faster
          </h3>
          <strong class="scenario-value">
           15–20 min
          </strong>
          <p>
           Consultations finish quicker than average.
          </p>
         </article>
         <article class="scenario">
          <h3>
           Typical
          </h3>
          <strong class="scenario-value">
           20–35 min
          </strong>
          <p>
           Normal flow based on today's current pacing.
          </p>
         </article>
         <article class="scenario">
          <h3>
           If an emergency case arrives
          </h3>
          <strong class="scenario-value">
           35–50 min
          </strong>
          <p>
           Doctor called for urgent bedside stabilization.
          </p>
         </article>
        </div>
       </section>
      </aside>
     </div>
     <section class="card section-gap">
      <h2 class="card-title">
       South Pavilion Waiting Amenities
      </h2>
      <p>
       Complimentary herbal teas, chilled water, high-speed Wi-Fi, and charging ports at stations 1–8.
      </p>
      <p class="section-gap">
       Wi-Fi:
       <strong>
        CalmWait-Guest
       </strong>
      </p>
     </section>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### live-queue/style.css

```css
/* Alias for the services screen; reuse its page-specific styling. */
@import url("../services/style.css");
```

### alerts/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Alerts &amp; Notifications at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Alerts &amp; Notifications | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="contact-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       PATIENT PORTAL
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../home/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/visit.svg"/>
      </span>
      Visit
     </a>
     <a href="../services/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/queue.svg"/>
      </span>
      Queue
     </a>
     <a href="../blog/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/progress.svg"/>
      </span>
      Progress
     </a>
     <a aria-current="page" href="../contact/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/alerts.svg"/>
      </span>
      Alerts
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <section aria-label="Current visit" class="patient-strip patient-details">
      <strong class="token accent">
       A-24
      </strong>
      <div>
       <strong>
        Aarav Shah
       </strong>
       <p class="muted small">
        Adult Outpatient • MRN #88204
       </p>
      </div>
      <div>
       <strong>
        Dr. Mehta
       </strong>
       <p class="muted small">
        General Medicine • Room 3
       </p>
      </div>
      <div>
       <span class="eyebrow">
        Checked-in: 10:30 AM
       </span>
       <p class="accent">
        Est. turn ~10:48 AM
       </p>
      </div>
     </section>
     <header class="page-heading">
      <div>
       <h1>
        Alerts &amp; Notifications
       </h1>
       <p>
        Live operational telemetry and direct paging from clinical station Desk A
       </p>
      </div>
      <div class="actions">
       <a class="btn btn-secondary" href="#notification-settings">
        Notification Settings
       </a>
      </div>
     </header>
     <div class="content-columns">
      <div class="main-column">
       <section class="card urgent-alert">
        <h2 class="card-title">
         Your turn is near
        </h2>
        <span class="badge badge-danger">
         URGENT ACTION REQUIRED
        </span>
        <p class="section-gap">
         Please head back to Room 3 doorway within approximately 10 minutes. Dr. Mehta is currently completing the final consultation review for Token A-23.
        </p>
        <div class="section-gap">
         <details>
          <summary>
           I'm on my way
          </summary>
          <div class="disclosure-content">
           <p>
            This static preview cannot notify reception. Please tell Desk A that you are returning.
           </p>
          </div>
         </details>
        </div>
        <p class="section-gap">
         <a class="btn btn-secondary" href="../step-out/index.html">
          Need +5 min
         </a>
        </p>
       </section>
       <section class="card">
        <h2 class="section-title">
         Today • Active visit
        </h2>
        <div class="alert-feed">
         <article class="alert-entry">
          <div class="card-heading">
           <h3>
            Return now
           </h3>
           <time class="small muted">
            Just now (10:42 AM)
           </time>
          </div>
          <p>
           Dr. Mehta is ready for patients up to A-23. Please proceed directly to Room 3 doorway and present your boarding pass QR.
          </p>
         </article>
         <article class="alert-entry">
          <div class="card-heading">
           <h3>
            Your turn is near
           </h3>
           <time class="small muted">
            10:35 AM
           </time>
          </div>
          <p>
           About 2 patients ahead in the General Medicine queue. Likely 10 to 15 minutes remaining before intake call.
          </p>
         </article>
         <article class="alert-entry">
          <div class="card-heading">
           <h3>
            Schedule Adjustment
           </h3>
           <time class="small muted">
            10:25 AM
           </time>
          </div>
          <p>
           We're running about 10 minutes behind schedule. Dr. Mehta is currently attending to two unscheduled emergency triage consultations. Thank you for your patience.
          </p>
         </article>
         <article class="alert-entry">
          <div class="card-heading">
           <h3>
            Doctor Status
           </h3>
           <time class="small muted">
            10:15 AM
           </time>
          </div>
          <p>
           Dr. Mehta is back in Room 3 following a mandatory clinical sanitization and specimen handoff break.
          </p>
         </article>
         <article class="alert-entry">
          <div class="card-heading">
           <h3>
            Step-out Hold Reminder
           </h3>
           <time class="small muted">
            10:10 AM
           </time>
          </div>
          <p>
           Your place-guarantee hold window ends at 11:20 AM. An active 15-minute grace period protects your position if you visit the courtyard cafe.
          </p>
         </article>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         Earlier Today
        </h2>
        <h3>
         Intake Confirmation
        </h3>
        <p class="small muted">
         10:30 AM
        </p>
        <p class="section-gap">
         Checked in successfully at Kiosk 2. Token A-24 issued for General Medicine with Dr. Mehta.
        </p>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <div id="notification-settings">
        <section class="card">
         <h2 class="card-title">
          Notification Channels &amp; Controls
         </h2>
         <p class="muted">
          Keep informed wherever you wait across the medical campus.
         </p>
         <form>
          <label class="toggle-row">
           <span>
            <strong>
             Push Notifications
            </strong>
            <span class="muted small">
             Active in this browser
            </span>
           </span>
           <input checked="" name="push-notifications" type="checkbox"/>
          </label>
          <label class="toggle-row">
           <span>
            <strong>
             SMS Text Alerts
            </strong>
            <span class="muted small">
             +1 (•••) •••-4902
            </span>
           </span>
           <input checked="" name="sms-text-alerts" type="checkbox"/>
          </label>
          <label class="toggle-row">
           <span>
            <strong>
             WhatsApp Alerts
            </strong>
            <span class="muted small">
             Optional instant messaging
            </span>
           </span>
           <input name="whatsapp-alerts" type="checkbox"/>
          </label>
          <fieldset class="section-gap">
           <legend>
            Alert Lead Time (Queue Position)
           </legend>
           <div class="segments">
            <label class="choice">
             <input checked="" name="lead" type="radio" value="0"/>
             <span>
              1 person
             </span>
            </label>
            <label class="choice">
             <input name="lead" type="radio" value="1"/>
             <span>
              2 people
             </span>
            </label>
            <label class="choice">
             <input name="lead" type="radio" value="2"/>
             <span>
              3 people
             </span>
            </label>
           </div>
          </fieldset>
          <p class="small muted section-gap">
           Preview controls only. These preferences are not saved or sent.
          </p>
         </form>
         <p class="section-gap small">
          Mandatory Policy: "Return now" doorway calls cannot be disabled to protect appointment rhythm and room turnaround.
         </p>
        </section>
       </div>
       <section class="card surface-soft">
        <h2 class="card-title">
         Calm Flow Guarantee
        </h2>
        <p class="eyebrow">
         When queue is smooth
        </p>
        <p class="section-gap">
         No urgent alerts. Relax, read, or grab tea in South Pavilion. We'll page you right when Dr. Mehta calls Token A-24.
        </p>
       </section>
       <section class="card" id="help">
        <h2 class="section-title">
         Reception &amp; Campus Assistance
        </h2>
        <dl class="metadata">
         <div>
          <dt>
           Desk A Extension
          </dt>
          <dd>
           x4901
          </dd>
         </div>
         <div>
          <dt>
           Hospital Wi-Fi
          </dt>
          <dd>
           CalmWait-Guest
          </dd>
         </div>
        </dl>
        <p class="section-gap">
         Visit Reception Desk A in South Pavilion for physical assistance, translation, or queue inquiries.
        </p>
        <details>
         <summary>
          Where is Room 3?
         </summary>
         <div class="disclosure-content">
          <p>
           Follow the South Wing corridor on the first floor. Room 3 is beside Waiting Lounge A.
          </p>
         </div>
        </details>
       </section>
       <section class="card">
        <h2 class="card-title">
         Dr. S. Mehta, MD
        </h2>
        <div class="row">
         <img alt="Dr. Mehta" class="portrait" src="../assets/images/dr-mehta.jpeg"/>
         <div>
          <p>
           Senior Attending • Room 3
          </p>
          <p class="muted small">
           Average consult: 14 min
          </p>
         </div>
        </div>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### alerts/style.css

```css
/* Alias for the contact screen; reuse its page-specific styling. */
@import url("../contact/style.css");
```

### progress/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="My Progress at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   My Progress | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="blog-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       PATIENT PORTAL
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../home/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/visit.svg"/>
      </span>
      Visit
     </a>
     <a href="../services/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/queue.svg"/>
      </span>
      Queue
     </a>
     <a aria-current="page" href="../blog/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/progress.svg"/>
      </span>
      Progress
     </a>
     <a href="../contact/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/alerts.svg"/>
      </span>
      Alerts
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        My Progress
       </h1>
       <p>
        Track your clinical pathway in real-time from reception intake through checkout.
       </p>
      </div>
      <div class="actions">
       <a class="btn btn-secondary" href="index.html">
        Refresh
       </a>
      </div>
     </header>
     <section aria-label="Current visit" class="patient-strip patient-details">
      <strong class="token accent">
       A-24
      </strong>
      <div>
       <strong>
        Aarav Shah
       </strong>
       <p class="muted small">
        Adult Outpatient • MRN #88204
       </p>
      </div>
      <div>
       <strong>
        Dr. Mehta
       </strong>
       <p class="muted small">
        General Medicine • Room 3
       </p>
      </div>
      <div>
       <span class="eyebrow">
        Checked-in: 10:30 AM
       </span>
       <p class="accent">
        Est. turn ~10:48 AM
       </p>
      </div>
     </section>
     <ol class="journey">
      <li>
       <span class="number number-complete">
        ✓
       </span>
       <strong>
        Checked in
       </strong>
       <span class="small muted">
        10:12 AM • Kiosk 2
       </span>
      </li>
      <li>
       <span class="number number-complete">
        ✓
       </span>
       <strong>
        Vitals Taken
       </strong>
       <span class="small muted">
        10:20 AM • Station B
       </span>
      </li>
      <li aria-current="step">
       <span class="number number-complete">
        3
       </span>
       <strong>
        Waiting
       </strong>
       <span class="small muted">
        South Pavilion
       </span>
      </li>
      <li>
       <span class="number">
        4
       </span>
       <strong>
        Consultation
       </strong>
       <span class="small muted">
        Room 3 • Dr. Mehta
       </span>
      </li>
      <li>
       <span class="number">
        5
       </span>
       <strong>
        Diagnostics
       </strong>
       <span class="small muted">
        If ordered • Lab or Radiology
       </span>
      </li>
      <li>
       <span class="number">
        6
       </span>
       <strong>
        Checkout
       </strong>
       <span class="small muted">
        Prescription &amp; Summary
       </span>
      </li>
     </ol>
     <div class="content-columns">
      <div class="main-column">
       <section class="card">
        <h2 class="card-title">
         South Pavilion Lounge
        </h2>
        <p class="eyebrow">
         Current phase • Quiet &amp; seated
        </p>
        <div class="section-gap">
         <p class="eyebrow">
          Estimated wait range
         </p>
         <strong class="large-value accent">
          20–35
         </strong>
         minutes
        </div>
        <p class="muted">
         Ranges reflect thorough, attentive patient consultations rather than rigid automated slots.
        </p>
        <div class="section-gap">
         <dl class="metadata">
          <div>
           <dt>
            Queue position
           </dt>
           <dd>
            3 patients ahead
           </dd>
          </div>
          <div>
           <dt>
            Room 3 live feed
           </dt>
           <dd>
            Consulting Token A-20
           </dd>
          </div>
         </dl>
        </div>
        <p class="section-gap">
         <a class="btn" href="../step-out/index.html">
          Step out for fresh air
         </a>
        </p>
        <p class="small muted section-gap">
         SMS Chime Armed (+1 ••• 4912). Stepping out holds your queue spot for up to 20 minutes without losing priority.
        </p>
       </section>
       <section class="card">
        <h2 class="card-title">
         Visit Pathway Log
        </h2>
        <div class="stack">
         <article>
          <div class="card-heading">
           <h3>
            Triage &amp; Clinical Vitals
           </h3>
           <time>
            10:20 AM
           </time>
          </div>
          <p>
           Nurse Station B (Nurse Henderson, RN). Initial diagnostic readings charted to electronic health record.
          </p>
          <div class="section-gap">
           <dl class="metadata">
            <div>
             <dt>
              Blood pressure
             </dt>
             <dd>
              122/78
             </dd>
            </div>
            <div>
             <dt>
              Heart rate
             </dt>
             <dd>
              72 bpm
             </dd>
            </div>
            <div>
             <dt>
              SpO2
             </dt>
             <dd>
              99%
             </dd>
            </div>
           </dl>
          </div>
         </article>
         <article class="rule">
          <div class="card-heading">
           <h3>
            Digital Intake Verified
           </h3>
           <time>
            10:12 AM
           </time>
          </div>
          <p>
           Check-in completed at Kiosk 2. Verified insurance coverage (Blue Cross PPO) and signed treatment consent.
          </p>
         </article>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         South Pavilion Amenities
        </h2>
        <div class="link-list">
         <span>
          CalmWait-Guest
         </span>
         <span>
          Herbal Tea &amp; Water
         </span>
         <span>
          Quiet Zone Seating
         </span>
        </div>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         Consultation with Dr. Mehta
        </h2>
        <p class="muted">
         Upcoming phase • Room 3, South Corridor • ~10–15 min
        </p>
        <p class="section-gap">
         Dr. Mehta will conduct a thorough review of your symptoms and recent medical updates.
        </p>
        <div class="banner section-gap">
         <h3>
          What to Bring Into Room 3
         </h3>
         <ul class="section-gap">
          <li>
           Government ID or digital boarding pass token (A-24)
          </li>
          <li>
           List of active prescriptions and medication dosages
          </li>
          <li>
           Specific questions or notes on symptom duration
          </li>
         </ul>
        </div>
        <p class="section-gap">
         Your device will play an alert chime and the hallway display boards will flash Token A-24 the moment Room 3 prepares for intake.
        </p>
       </section>
       <details>
        <summary>
         Post-Consultation &amp; Lab Work
        </summary>
        <div class="disclosure-content">
         <p>
          If Dr. Mehta orders laboratory bloodwork or imaging scans, live indoor wayfinding directions will appear here on your phone screen.
         </p>
         <p>
          Digital Discharge Summary • Ready upon departure
         </p>
        </div>
       </details>
       <section class="card">
        <h2 class="card-title">
         Need Direct Assistance?
        </h2>
        <p>
         Desk A attendant is standing by to answer queue inquiries, provide physical assistance, or coordinate translation services.
        </p>
        <p class="section-gap">
         <a class="btn btn-secondary" href="../contact/index.html#help">
          Call Attendant (x4901)
         </a>
        </p>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### progress/style.css

```css
/* Alias for the blog screen; reuse its page-specific styling. */
@import url("../blog/style.css");
```

### profile/index.html

```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <meta content="Patient Profile &amp; Care Preferences at CalmWait, South Pavilion Clinic." name="description"/>
  <title>
   Patient Profile &amp; Care Preferences | CalmWait
  </title>
  <link href="../css/global.css" rel="stylesheet"/>
  <link href="style.css" rel="stylesheet"/>
 </head>
 <body class="about-page">
  <a class="skip-link" href="#main-content">
   Skip to main content
  </a>
  <div class="workspace staff-shell">
   <!-- Shared navigation stays in normal document flow at every viewport. -->
   <aside class="sidebar">
    <a class="brand" href="../home/index.html">
     <span class="logo-tile">
      <img alt="" class="icon" src="../assets/icons/logo.svg"/>
     </span>
     <span>
      <strong class="brand-name">
       CalmWait
      </strong>
      <span class="brand-caption">
       SOUTH PAVILION CLINIC
      </span>
     </span>
    </a>
    <nav aria-label="Primary" class="side-nav">
     <a href="../reception/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-queue.svg"/>
      </span>
      Live Queue
     </a>
     <a href="../reception/index.html#doctor">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-doctor.svg"/>
      </span>
      Doctor Pacing &amp; Rooms
     </a>
     <a href="../reception/index.html#broadcast">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-comms.svg"/>
      </span>
      Patient Communications
     </a>
     <a href="../analytics/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-analytics.svg"/>
      </span>
      Analytics &amp; Reports
     </a>
     <a aria-current="page" href="../about/index.html">
      <span class="glyph">
       <img alt="" class="icon" src="../assets/icons/staff-settings.svg"/>
      </span>
      Clinic Settings
     </a>
    </nav>
    <section class="sidebar-note">
     <p class="eyebrow">
      Temporary leave
     </p>
     <p>
      Need coffee or fresh air?
     </p>
     <a href="../step-out/index.html">
      Step Out
     </a>
    </section>
    <footer class="sidebar-footer">
     <p>
      Main Campus
      <br/>
      Level 1 • South Pavilion
     </p>
     <a href="../contact/index.html#help">
      <img alt="" class="icon" src="../assets/icons/help.svg"/>
      Assistance &amp; FAQs
     </a>
    </footer>
   </aside>
   <div class="page">
    <header class="topbar">
     <div class="topbar-status">
      <span class="badge">
       ● RECEPTION DESK A ONLINE
      </span>
      <span class="muted">
       •   Wait times nominal (under 12m)
      </span>
     </div>
     <nav aria-label="Account and help" class="topbar-actions">
      <a class="btn btn-secondary" href="../contact/index.html#help">
       <img alt="" class="icon" src="../assets/icons/headset.svg"/>
       Help / Attendant
      </a>
      <a aria-label="Patient profile" class="avatar" href="../about/index.html">
       <img alt="" class="icon" src="../assets/icons/profile.svg"/>
      </a>
     </nav>
    </header>
    <!-- Page content. Values reproduce the Figma sample, not a live clinical feed. -->
    <main class="container" id="main-content">
     <header class="page-heading">
      <div>
       <h1>
        Patient Profile &amp; Care Preferences
       </h1>
       <p>
        Manage your contact details, waiting-room sensory accessibility needs, real-time summons notifications, and active clinic credentials.
       </p>
      </div>
      <div class="actions">
      </div>
     </header>
     <div class="content-columns">
      <div class="main-column">
       <section class="card">
        <div class="row">
         <span class="avatar">
          ER
         </span>
         <div>
          <h2>
           Elena Rostova
          </h2>
          <p class="muted">
           DOB: Mar 14, 1986 (38y) • Tier 1 Verified
          </p>
         </div>
        </div>
        <form class="stack section-gap">
         <div class="field">
          <label for="legal-full-name">
           Legal Full Name
          </label>
          <input id="legal-full-name" name="legal-full-name" type="text" value="Elena Mariya Rostova"/>
         </div>
         <div class="field">
          <label for="preferred-call-name">
           Preferred Call Name
          </label>
          <input id="preferred-call-name" name="preferred-call-name" type="text" value="Elena"/>
         </div>
         <div class="form-row">
          <div class="field">
           <label for="mobile-number">
            Mobile Number
           </label>
           <input id="mobile-number" name="mobile-number" type="tel" value="+1 (555) 234-8901"/>
          </div>
          <div class="field">
           <label for="email-address">
            Email Address
           </label>
           <input id="email-address" name="email-address" type="email" value="elena.rostova@healthmail.com"/>
          </div>
         </div>
         <div class="field">
          <label for="emergency-contact">
           Emergency Contact
          </label>
          <input id="emergency-contact" name="emergency-contact" type="text" value="Mark Rostova — Spouse • Cell: (555) 882-1920"/>
         </div>
         <div class="field">
          <label for="language">
           Primary Consultation Language
          </label>
          <select id="language" name="language">
           <option>
            English (United States)
           </option>
           <option>
            ગુજરાતી
           </option>
           <option>
            हिन्दी
           </option>
          </select>
         </div>
         <p class="small muted">
          Form preview. Changes stay on this page and are not saved to an account.
         </p>
        </form>
       </section>
       <section class="card">
        <h2 class="card-title">
         Waiting-Room &amp; Sensory Accommodations
        </h2>
        <p class="muted">
         CalmWait adjusts waiting ambient levels, escort routing, and companion seating.
        </p>
        <form>
         <label class="toggle-row">
          <span>
           <strong>
            Low-Sensory Lounge Preference
           </strong>
           <span class="muted small">
            Mutes public paging chimes and redirects your pass to South Alcove Quiet Pods.
           </span>
          </span>
          <input checked="" name="low-sensory-lounge-preference" type="checkbox"/>
         </label>
         <label class="toggle-row">
          <span>
           <strong>
            Mobility &amp; Wheelchair Escort Assistance
           </strong>
           <span class="muted small">
            Concierge escorts from check-in Bay B to the examination suite.
           </span>
          </span>
          <input name="mobility-and-wheelchair-escort-assistance" type="checkbox"/>
         </label>
         <label class="toggle-row">
          <span>
           <strong>
            Clinical Medical Interpreter
           </strong>
           <span class="muted small">
            Pre-assigns an interpreter before consultation.
           </span>
          </span>
          <input name="clinical-medical-interpreter" type="checkbox"/>
         </label>
         <fieldset class="section-gap">
          <legend>
           Companion Waiting Seating Allocation
          </legend>
          <div class="segments">
           <label class="choice">
            <input checked="" name="seating" type="radio" value="0"/>
            <span>
             Waiting Alone
            </span>
           </label>
           <label class="choice">
            <input name="seating" type="radio" value="1"/>
            <span>
             +1 Companion
            </span>
           </label>
           <label class="choice">
            <input name="seating" type="radio" value="2"/>
            <span>
             Mobility Bay
            </span>
           </label>
          </div>
         </fieldset>
         <div class="field section-gap">
          <label for="access-notes">
           Clinic Access &amp; Sensory Notes
          </label>
          <textarea id="access-notes" name="access-notes">Mild photophobia: prefers dimmed lounge seating. Spouse Mark will join inside Room 04.</textarea>
         </div>
        </form>
       </section>
       <section class="card">
        <h2 class="card-title">
         Queue Alerts &amp; Summons Routing
        </h2>
        <p>
         Choose how the clinic signals when your turn approaches.
        </p>
        <form>
         <label class="toggle-row">
          <span>
           <strong>
            Direct SMS Summons
           </strong>
           <span class="muted small">
            Sends countdown, door readiness alert, and room door code.
           </span>
          </span>
          <input checked="" name="direct-sms-summons" type="checkbox"/>
         </label>
         <label class="toggle-row">
          <span>
           <strong>
            Browser Sound &amp; Haptic Vibration
           </strong>
           <span class="muted small">
            Soft two-tone gentle chime when pass moves to Next in Line.
           </span>
          </span>
          <input checked="" name="browser-sound-and-haptic-vibration" type="checkbox"/>
         </label>
         <label class="toggle-row">
          <span>
           <strong>
            Post-Visit Queue Audit &amp; Summary
           </strong>
           <span class="muted small">
            Receives visit timestamps and summary.
           </span>
          </span>
          <input name="post-visit-queue-audit-and-summary" type="checkbox"/>
         </label>
        </form>
       </section>
      </div>
      <aside aria-label="Visit details" class="rail">
       <section class="card">
        <h2 class="card-title">
         Active Clinic Boarding Pass
        </h2>
        <p class="eyebrow">
         Today • Oct 24
        </p>
        <div class="token-box section-gap">
         <span class="eyebrow">
          Priority token
         </span>
         <strong class="token">
          A-24
         </strong>
         <span class="badge badge-success">
          Vitals Ready
         </span>
        </div>
        <div class="stack section-gap">
         <dl class="metadata">
          <div>
           <dt>
            Provider
           </dt>
           <dd>
            Dr. Aris Thorne
           </dd>
          </div>
          <div>
           <dt>
            Assigned suite
           </dt>
           <dd>
            Room 04
           </dd>
          </div>
          <div>
           <dt>
            Estimated call in
           </dt>
           <dd>
            4 mins
           </dd>
          </div>
          <div>
           <dt>
            Target time
           </dt>
           <dd>
            10:48 AM
           </dd>
          </div>
         </dl>
         <a class="btn" href="../home/index.html">
          Open Live Boarding Pass
         </a>
        </div>
       </section>
       <section class="card">
        <h2 class="card-title">
         Recent Queue Passes
        </h2>
        <ul class="queue-list">
         <li class="queue-item">
          <strong>
           A-24
          </strong>
          <div class="grow">
           <h3>
            General Consultation
           </h3>
           <p class="small muted">
            Today • Dr. A. Thorne • Active
           </p>
          </div>
         </li>
         <li class="queue-item">
          <strong>
           C-08
          </strong>
          <div class="grow">
           <h3>
            Cardiology Follow-up
           </h3>
           <p class="small muted">
            Sep 12, 2024 • Dr. K. Patel • Wait: 18m
           </p>
          </div>
         </li>
         <li class="queue-item">
          <strong>
           L-12
          </strong>
          <div class="grow">
           <h3>
            Routine Blood Panel
           </h3>
           <p class="small muted">
            Jul 03, 2024 • Lab Bay 2 • Wait: 12m
           </p>
          </div>
         </li>
        </ul>
       </section>
       <section class="card">
        <h2 class="card-title">
         Security &amp; Delegates
        </h2>
        <p class="muted">
         Access control &amp; clinic kiosks.
        </p>
        <div class="stack section-gap">
         <h3>
          Two-Factor Passcode
          <span class="badge badge-success">
           Active
          </span>
         </h3>
         <p>
          SMS code sent on new clinic kiosk check-in
         </p>
         <h3>
          Authorized Delegate
         </h3>
         <p>
          Mark Rostova (Spouse) • Live Queue Viewer
         </p>
         <details>
          <summary>
           Other kiosk sessions
          </summary>
          <div class="disclosure-content">
           <p>
            Session management requires a connected account. No sessions are changed by this preview.
           </p>
          </div>
         </details>
        </div>
       </section>
      </aside>
     </div>
    </main>
    <footer class="support-footer">
     <span>
      CalmWait • South Pavilion Clinic
     </span>
     <nav aria-label="More pages">
      <a href="../sign-in/index.html">
       Sign in
      </a>
      <a href="../about/index.html">
       Profile
      </a>
      <a href="../reception/index.html">
       Reception
      </a>
      <a href="../analytics/index.html">
       Analytics
      </a>
      <a href="../caregiver/index.html">
       Caregiver
      </a>
      <a href="../settings/index.html">
       Settings
      </a>
     </nav>
    </footer>
   </div>
  </div>
 </body>
</html>
```

### profile/style.css

```css
/* Alias for the about screen; reuse its page-specific styling. */
@import url("../about/style.css");
```

### css/global.css

```css
/* CalmWait shared foundation. Light Figma palette explicitly requested for this project. */
@font-face {
    font-family: Inter;
    src: url("../assets/fonts/inter-0.ttf") format("truetype");
    font-style: normal;
    font-weight: 400;
    font-display: swap;
}
@font-face {
    font-family: Inter;
    src: url("../assets/fonts/inter-1.ttf") format("truetype");
    font-style: normal;
    font-weight: 500;
    font-display: swap;
}
@font-face {
    font-family: Inter;
    src: url("../assets/fonts/inter-2.ttf") format("truetype");
    font-style: normal;
    font-weight: 600;
    font-display: swap;
}
@font-face {
    font-family: Inter;
    src: url("../assets/fonts/inter-3.ttf") format("truetype");
    font-style: normal;
    font-weight: 700 900;
    font-display: swap;
}

/* Reset and design tokens: shared spacing, typography, surfaces and statuses. */
:root {
    color-scheme: light;
    --background: #f6f9ff;
    --surface: #ffffff;
    --raised: #f3f8ff;
    --soft: #ebf5ff;
    --text: #101d27;
    --muted: #3f494a;
    --border: #dce6ec;
    --accent: #00545c;
    --accent-deep: #0a6e78;
    --on-accent: #ffffff;
    --success: #16823c;
    --warning: #94611a;
    --danger: #c62828;
    --radius: 12px;
    --space: 24px;
}
* { box-sizing: border-box; }
html { background: var(--background); }
body { margin: 0; background: var(--background); color: var(--text); font: 400 14px/1.5 Inter, sans-serif; }
h1, h2, h3, h4, p, figure, dl, dd { margin: 0; }
h1 { font-size: 28px; line-height: 36px; font-weight: 700; }
h2 { font-size: 20px; line-height: 28px; font-weight: 600; }
h3, h4 { font-size: 17px; line-height: 24px; font-weight: 600; }
ul, ol { margin: 0; padding-left: 22px; }
a { color: var(--accent); text-underline-offset: 3px; }
button, input, select, textarea { font: inherit; }
button, summary, label { cursor: pointer; }
button { color: inherit; }
img { display: block; max-width: 100%; }
/* Focus is visible on links, form fields and native disclosure controls. */
:focus-visible { outline: 3px solid var(--warning); outline-offset: 4px; }

/* Reusable page shell. All navigation stays in normal document flow. */
.skip-link { display: block; padding: 6px 16px; font-size: 12px; background: var(--surface); }
.workspace { display: flex; align-items: flex-start; min-height: 800px; }
.sidebar { display: flex; flex-direction: column; width: 240px; flex: 0 0 240px; min-height: 800px; background: var(--surface); border-right: 1px solid var(--border); }
.staff-shell .sidebar { width: 288px; flex-basis: 288px; }
.brand { display: flex; align-items: center; gap: 8px; min-height: 64px; padding: 12px 16px; color: var(--text); text-decoration: none; }
.brand-name { display: block; font-size: 20px; font-weight: 600; line-height: 24px; }
.brand-caption { display: block; color: var(--muted); font-size: 10px; letter-spacing: 1px; }
.logo-tile { display: flex; align-items: center; justify-content: center; width: 36px; height: 36px; border-radius: 8px; background: #dceaf8; flex: 0 0 36px; }
.side-nav { display: flex; flex-direction: column; gap: 4px; padding: 16px 8px; }
.side-nav a { display: flex; align-items: center; gap: 16px; min-height: 48px; padding: 10px 16px; color: var(--muted); text-decoration: none; border-radius: 6px; font-weight: 500; }
.side-nav a:hover { background: var(--raised); color: var(--text); }
.side-nav a[aria-current="page"] { color: #fff; background: var(--accent-deep); }
.glyph { display: flex; align-items: center; justify-content: center; width: 28px; height: 28px; flex: 0 0 28px; border-radius: 5px; background: #dceaf8; }
.glyph-visit { background: var(--accent-deep); }
/* Exported SVGs retain their intrinsic Figma width and height. */
.glyph img { max-width: none; }
.sidebar-note { margin: 8px; padding: 16px; border-radius: 8px; background: var(--soft); }
.sidebar-footer { margin-top: auto; padding: 16px; background: var(--soft); color: var(--muted); font-size: 12px; }
.sidebar-footer p + a { display: flex; margin-top: 8px; }
.page { display: flex; flex-direction: column; min-width: 0; flex: 1; }
.topbar { display: flex; justify-content: space-between; align-items: center; gap: 16px; flex-wrap: wrap; min-height: 64px; padding: 10px 24px; background: var(--surface); border-bottom: 1px solid var(--border); font-size: 12px; }
.topbar-status, .actions, .inline, .card-heading { display: flex; align-items: center; gap: 12px; flex-wrap: wrap; }
.topbar-actions { display: flex; align-items: center; gap: 12px; }
.container { width: 100%; padding: 24px; }
.page-heading { display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 16px; margin-bottom: 24px; }
.page-heading p { max-width: 600px; margin-top: 4px; color: var(--muted); font-size: 16px; }
.content-columns { display: flex; align-items: flex-start; gap: 24px; }
.main-column { display: flex; flex-direction: column; gap: 24px; min-width: 0; flex: 1 1 58%; }
.rail { display: flex; flex-direction: column; gap: 24px; min-width: 0; flex: 1 1 40%; }
.stack { display: flex; flex-direction: column; gap: 16px; }
.stack-small { display: flex; flex-direction: column; gap: 8px; }
.row { display: flex; align-items: flex-start; gap: 16px; }
.spread { justify-content: space-between; }
.wrap { flex-wrap: wrap; }
.grow { flex: 1; min-width: 0; }
.text-center { text-align: center; }
.muted { color: var(--muted); }
.small { font-size: 12px; line-height: 18px; }
.eyebrow { color: var(--muted); font-size: 11px; font-weight: 600; letter-spacing: 1px; text-transform: uppercase; }
.accent { color: var(--accent); }
.success { color: var(--success); }
.warning { color: var(--warning); }
.danger { color: var(--danger); }
.large-value { font-size: 56px; font-weight: 700; line-height: 64px; }
.section-title { margin-bottom: 16px; }

/* Shared surfaces, status badges, links and action styles. */
.card { padding: 24px; border: 1px solid var(--border); border-radius: var(--radius); background: var(--surface); }
.card-compact { padding: 16px; }
.card-heading { justify-content: space-between; margin-bottom: 16px; }
.banner { padding: 20px 24px; border: 1px solid var(--border); border-radius: var(--radius); background: var(--soft); }
.banner-warning { background: #fff7e5; border-color: #ebc687; }
.banner-danger { background: #fff0ee; border-color: #f0c1ba; }
.badge { display: inline-flex; align-items: center; gap: 6px; padding: 4px 8px; border-radius: 6px; background: var(--soft); color: var(--accent); font-size: 11px; font-weight: 600; line-height: 16px; }
.badge-success { color: var(--success); background: #e7f5eb; }
.badge-warning { color: var(--warning); background: #fff3d8; }
.badge-danger { color: var(--danger); background: #ffefed; }
.btn { display: inline-flex; align-items: center; justify-content: center; gap: 8px; min-height: 44px; padding: 10px 16px; border: 1px solid var(--accent); border-radius: 8px; background: var(--accent); color: var(--on-accent); text-decoration: none; font-weight: 600; line-height: 20px; }
.btn:hover { background: #087883; }
.btn-secondary { background: var(--raised); color: var(--text); border-color: var(--border); }
.btn-secondary:hover { background: var(--soft); }
.btn-danger { background: #ffefed; color: var(--danger); border-color: #f0c1ba; }
.btn-full { width: 100%; }
.btn-small { min-height: 36px; padding: 7px 12px; font-size: 12px; }
.rule { padding-top: 16px; border-top: 1px solid var(--border); }
.list-clean { display: flex; flex-direction: column; gap: 16px; padding: 0; list-style: none; }
.number { display: flex; align-items: center; justify-content: center; width: 32px; height: 32px; flex: 0 0 32px; border: 1px solid var(--border); border-radius: 50%; background: var(--soft); color: var(--accent); font-weight: 600; }
.number-complete { background: var(--accent); color: var(--on-accent); }
.token-box { display: flex; flex-direction: column; align-items: center; gap: 8px; padding: 16px; background: var(--soft); border-radius: 10px; color: var(--accent); }
.token { font-size: 56px; font-weight: 700; line-height: 64px; letter-spacing: -2px; }
.metadata { display: flex; flex-wrap: wrap; gap: 16px; }
.metadata > div { flex: 1 1 100px; }
.metadata dt { color: var(--muted); font-size: 11px; letter-spacing: .4px; text-transform: uppercase; }
.metadata dd { font-weight: 600; font-size: 16px; }
.patient-strip { padding: 16px; margin-bottom: 24px; background: var(--surface); border: 1px solid var(--border); border-radius: 10px; }
.avatar { display: flex; align-items: center; justify-content: center; flex: 0 0 44px; width: 44px; height: 44px; border-radius: 50%; background: var(--soft); color: var(--accent); font-weight: 700; }
.portrait { width: 56px; height: 56px; flex: 0 0 56px; border-radius: 50%; object-fit: cover; }
.ticket-code { padding: 16px; background: #fff; border-radius: 8px; }
.ticket-code img { max-width: none; }
.ticket-code-square { display: flex; justify-content: center; width: 178px; margin: 0 auto; }

/* Native HTML forms, disclosures and selectable segmented controls. */
.field { display: flex; flex-direction: column; gap: 6px; min-width: 0; flex: 1 1 180px; }
.field label { font-weight: 600; }
input, select, textarea { width: 100%; min-height: 44px; padding: 10px 12px; color: var(--text); background: var(--background); border: 1px solid var(--border); border-radius: 6px; }
input::placeholder, textarea::placeholder { color: var(--muted); }
textarea { min-height: 112px; }
fieldset { min-width: 0; margin: 0; padding: 0; border: 0; }
legend { margin-bottom: 12px; font-weight: 600; }
.form-row { display: flex; gap: 16px; flex-wrap: wrap; }
.segments { display: flex; flex-wrap: wrap; gap: 8px; }
.choice { display: flex; align-items: center; gap: 8px; flex: 1 1 110px; padding: 12px; border: 1px solid var(--border); border-radius: 8px; background: var(--raised); }
.choice:has(input:checked) { background: var(--soft); border-color: var(--accent); }
.choice input, .toggle-row input { width: 20px; height: 20px; min-height: 20px; flex: 0 0 20px; accent-color: var(--accent); }
.toggle-row { display: flex; justify-content: space-between; align-items: center; gap: 16px; padding: 16px 0; border-bottom: 1px solid var(--border); }
.toggle-row p { color: var(--muted); font-size: 12px; margin-top: 4px; }
.toggle-description { display: block; margin-top: 4px; }
details { border: 1px solid var(--border); border-radius: 8px; background: var(--raised); }
summary { padding: 14px 16px; color: var(--accent); font-weight: 600; }
.disclosure-content { padding: 0 16px 16px; }
.disclosure-content > * + * { margin-top: 12px; }

/* Reusable stat cards and Flexbox-only queue rows. */
.stats { display: flex; flex-wrap: wrap; gap: 16px; margin-bottom: 24px; }
.stat { flex: 1 1 160px; min-width: 0; padding: 20px; border: 1px solid var(--border); border-radius: 10px; background: var(--surface); }
.stat-value { display: block; margin: 8px 0; font-size: 42px; line-height: 52px; font-weight: 700; }
.queue-list { display: flex; flex-direction: column; padding: 0; list-style: none; }
.queue-item { display: flex; align-items: center; justify-content: space-between; gap: 12px; padding: 16px 0; border-bottom: 1px solid var(--border); }
.queue-item:last-child { border-bottom: 0; }
.queue-item-you { padding: 16px; border: 1px solid var(--accent); border-radius: 8px; background: var(--soft); }
.queue-item strong { display: block; }
.support-footer { display: flex; justify-content: space-between; flex-wrap: wrap; gap: 16px; padding: 24px; border-top: 1px solid var(--border); color: var(--muted); font-size: 12px; }
.support-footer nav { display: flex; flex-wrap: wrap; gap: 16px; }

/* Tablet: retain the desktop navigation with a narrower rail. */
@media (min-width: 768px) and (max-width: 1199px) {
    .sidebar, .staff-shell .sidebar { width: 192px; flex-basis: 192px; }
    .container { padding: 20px; }
    .content-columns { gap: 16px; }
    .card { padding: 18px; }
    .topbar { padding: 12px 20px; }
    .topbar-status .muted { display: none; }
}
/* Mobile includes the 368–767px range as well as the requested small screens. */
@media (max-width: 767px) {
    .workspace { flex-direction: column; }
    .sidebar, .staff-shell .sidebar { width: 100%; flex-basis: auto; min-height: 0; border-right: 0; border-bottom: 1px solid var(--border); }
    .brand { min-height: 64px; }
    .side-nav { flex-direction: row; flex-wrap: wrap; padding: 8px 12px; gap: 6px; }
    .side-nav a { flex: 1 1 70px; justify-content: center; gap: 6px; padding: 8px; min-height: 44px; font-size: 12px; }
    .side-nav .glyph { display: none; }
    .sidebar-note, .sidebar-footer { display: none; }
    .page { width: 100%; }
    .topbar { padding: 12px 16px; gap: 8px; }
    .topbar-status .muted { display: none; }
    .container { padding: 20px 16px; }
    .page-heading { margin-bottom: 20px; }
    .page-heading p { font-size: 14px; }
    .content-columns { flex-direction: column; gap: 20px; }
    .main-column, .rail { width: 100%; flex-basis: auto; gap: 20px; }
    .card, .banner { padding: 20px; }
    .stat { flex-basis: 130px; padding: 16px; }
    .stat-value { font-size: 32px; line-height: 40px; }
    .metadata > div { flex-basis: 110px; }
    .support-footer { padding: 20px 16px; }
}
@media (max-width: 367px) {
    h1 { font-size: 24px; line-height: 32px; }
    .container { padding: 16px 12px; }
    .card, .banner { padding: 16px; }
    .topbar-actions .btn { padding: 8px 10px; font-size: 12px; }
    .large-value, .token { font-size: 48px; line-height: 56px; }
    .actions > .btn { width: 100%; }
}
/* Light paper output stays readable and hides navigation and form actions. */
@media print {
    :root { color-scheme: light; --background: #fff; --surface: #fff; --raised: #f3f5f7; --soft: #eef4f6; --text: #10222d; --muted: #43505a; --border: #c5cdd1; --accent: #00545c; --on-accent: #fff; --success: #166534; --warning: #805000; --danger: #9b1c1c; }
    .skip-link, .sidebar, .topbar, .support-footer, .actions, .btn { display: none; }
    .workspace { display: block; min-height: 0; }
    .page { width: 100%; }
    .container { padding: 0; }
    .card, .banner { break-inside: avoid; }
    a { color: #00545c; }
    .banner-warning, .banner-danger { background: #fff; border-color: #c5cdd1; }
}

/* Shared pieces used by patient, staff and account pages. */
.icon { flex: 0 0 auto; }
.surface-soft { background: var(--soft); }
.card > .stack { gap: 20px; }
.card-title { display: flex; align-items: center; gap: 8px; margin-bottom: 16px; }
.section-gap { margin-top: 24px; }
.notice { margin: 0 0 20px; padding: 10px 16px; background: var(--soft); color: var(--muted); font-size: 12px; border-radius: 6px; }
.patient-details { display: flex; align-items: center; gap: 20px; flex-wrap: wrap; }
.patient-details > div { flex: 1 1 120px; }
.patient-details .token { flex: 0 1 auto; }
.pill-nav { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 20px; }
.pill-nav a { padding: 8px 12px; border-radius: 6px; background: var(--soft); text-decoration: none; font-size: 12px; }
.pill-nav a:first-child { background: var(--accent); color: white; }
.meter { display: flex; height: 10px; background: var(--border); border-radius: 8px; }
.meter-fill { display: flex; background: var(--accent-deep); border-radius: 8px; }
.fraction-96 { width: 96%; } .fraction-94 { width: 94%; } .fraction-100 { width: 100%; } .fraction-81 { width: 81%; }
.settings-list { display: flex; flex-direction: column; gap: 4px; }
.preview-action { display: flex; flex-direction: column; gap: 10px; }
button:disabled { color: var(--muted); background: var(--raised); border-color: var(--border); cursor: not-allowed; }
.full-image { width: 100%; height: auto; border-radius: 8px; }
.chart-scroll { display: flex; flex-direction: column; gap: 16px; }
.link-list { display: flex; flex-wrap: wrap; gap: 12px; }
@media (max-width: 1199px) {
    .content-columns { flex-wrap: wrap; }
    .main-column { flex-basis: 100%; }
    .rail { flex-basis: 100%; }
}
/* The skip link enters normal flow when focused; no positioned elements are used. */
.skip-link { height: 0; padding: 0 16px; overflow: hidden; }
.skip-link:focus { height: auto; padding: 6px 16px; }
.side-nav a[aria-current="page"] .glyph { background: var(--accent-deep); }
.topbar .avatar { background: var(--accent); }
.toggle-row > span { display: flex; flex-direction: column; gap: 4px; }
.sidebar-note { margin-top: 20px; }
@media (min-width: 992px) and (max-width: 1199px) {
    .main-column { flex-basis: 58%; }
    .rail { flex-basis: 40%; }
}
/* A field's 180px flex basis applies to horizontal form rows, never vertical stacks. */
.stack > .field { flex: 0 1 auto; }
.side-nav a[aria-current="page"] .glyph { background: #dceaf8; }
.side-nav a[href*="home/"] .glyph { background: var(--accent-deep); }
```
