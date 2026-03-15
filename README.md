# ThermoDynamics — FTC Team 28874

> Official website for ThermoDynamics, FTC Team 28874 from Apex, North Carolina.  
> Built with plain HTML, CSS, and vanilla JavaScript — no frameworks, no build step.

---

## 🌐 Live Site

[ftc28874-thermodynamics.vercel.app](https://ftc28874-thermodynamics.vercel.app) *(update this once deployed)*

---

## 📁 Project Structure

```
FTC-ThermoDynamics-Website/
├── index.html              # Entire site — all HTML, CSS, and JS in one file
└── assets/
    └── images/
        ├── thermodynamics logo.png   # Team logo (hero section)
        ├── neptune.png               # Robot showcase image
        ├── Ishaan.jpeg               # Team member photo
        └── johan.jpeg                # Team member photo
```

---

## ✏️ How to Edit Common Things

### Change the team logo
Find the hero logo section and update the `src`:
```html
<div class="hero-logo-wrap">
  <img src="assets/images/YOUR_LOGO.png" alt="ThermoDynamics Logo" />
</div>
```

### Change the robot image
Find the robot showcase section and update the `src`:
```html
<div class="robot-img-inner">
  <img src="/assets/images/YOUR_ROBOT.png" alt="Neptune — FTC Robot" />
</div>
```

### Add a team photo
In the About section, replace the placeholder with an `<img>` tag:
```html
<div class="about-img-frame">
  <!-- Replace this entire placeholder block: -->
  <img src="/assets/images/team.jpg" alt="Team Photo" />
</div>
```

### Add a team member photo
Find the member's card and replace the initials avatar with an image:
```html
<!-- Before (initials only): -->
<div class="member-avatar">HN</div>

<!-- After (with photo): -->
<div class="member-avatar" style="background:#111; border:2px solid rgba(255,166,0,0.3);">
  <img src="/assets/images/yourphoto.jpg" alt="Member Name" />
</div>
```

### Move robot callout labels
In the Robot section, find the `.callout` divs and change the `data-*` values:
```html
<!-- data-top / data-bottom = % from that edge of the robot image -->
<!-- data-left / data-right = % from that edge (negative = outside the box) -->
<!-- data-flip="true"       = puts the label on the left, dot on the right -->

<div class="callout"
     data-top="8"
     data-right="-2"
     data-label="Flywheel Shooter">
</div>
```

### Update outreach events
Each event is an `.outreach-card` div in the Outreach section. Edit the title, description, date, and location directly in the HTML.

### Add a sponsor
Replace a `sponsor-slot` placeholder with your sponsor's logo:
```html
<!-- Before: -->
<div class="sponsor-slot">Sponsor A</div>

<!-- After: -->
<div class="sponsor-slot">
  <img src="/assets/images/sponsor-logo.png" alt="Sponsor Name" style="max-width:120px;" />
</div>
```

---

## 🚀 Deploying with GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under *Source*, select **Deploy from a branch**
4. Set branch to `main`, folder to `/ (root)`
5. Click **Save** — your site will be live at `https://ftc28874.github.io/FTC-ThermoDynamics-Website`

---

## 🎨 Design Reference

| Property | Value |
|---|---|
| Primary gradient | `#FFA600` → `#EB813F` |
| Background | `#000000` |
| Surface | `#0d0d0d` / `#141414` |
| Text | `#ffffff` |
| Display font | Syne (Google Fonts) |
| Body font | DM Sans (Google Fonts) |

---

## 📬 Contact

**Email:** [ftcteam28874@apexmakerclub.org](mailto:ftcteam28874@apexmakerclub.org)  
**Organization:** [Apex Maker Club](https://apexmakerclub.org)  
**Location:** Apex, North Carolina