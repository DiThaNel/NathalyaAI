# Nathalya Reis Tattoo — AI Studio Experience

Official responsive web application and AI consultation interface for Nathalya Reis Tattoo & NR Tattoo Art studios (Braganca and Vila Real, Portugal).

The platform integrates bespoke atelier branding, online masterclass enrollment ("From Zero to Your First Tattoo"), and a direct embed of the official Agentplace AI booking and consultation assistant.

---

## Live Links

- Production Web Application: https://racing-banyan-t8njkrk.vercel.app/
- Direct AI Assistant (Agentplace): https://9o80sxb8g6nu.run.agentplace.io/
- Official Studio Website: https://nathalyareistattoo.com/
- Masterclass Enrollment: https://nathalyareistattoo.com/cart/?add-to-cart=372

---

## Key Features

- **Adaptive Responsive Design**:
  - Desktop: Two-column studio layout featuring artist profile and live AI consultation side-by-side.
  - Mobile & Tablet: Segmented view switcher (`AI Assistant` and `Studio & Masterclass`) with zero horizontal overflow, compact navigation, and quick-inquiry chips.
- **Embedded AI Consultation Client**:
  - Direct integration with Agentplace runtime for real-time tattoo ideas, fine-line styles, and appointment preparation.
  - Atelier Dark Mode filter and Light Mode toggle.
  - Fullscreen expansion option.
- **Quick Inquiry Actions**:
  - One-tap query copying for pricing, course discounts, studio locations, and beginner drawing requirements.
  - Non-intrusive floating toast notifications.
- **Zero Framework Dependency**:
  - Clean HTML5, modern CSS3 variables, and vanilla JavaScript for minimal load times and maximum performance.

---

## Project Structure

```
NathalyaAI/
├── index.html        # Main atelier interface and embedded AI assistant
├── README.md         # Project documentation and deployment guide
└── .gitignore        # Git ignore rules for local environment and Vercel artifacts
```

---

## Vercel and GitHub Synchronization

This project is hosted on GitHub at `https://github.com/DiThaNel/NathalyaAI.git` and deploys continuously to Vercel.

### Continuous Deployment Workflow

1. All production code resides on the `main` branch.
2. When commits are pushed to `origin main`, Vercel receives an automated webhook trigger from GitHub.
3. Vercel automatically creates a new production deployment within seconds.

### Verifying Vercel Connection

To verify that your GitHub repository is connected to your Vercel project:

1. Log into your Vercel Dashboard at [vercel.com](https://vercel.com).
2. Select your project (`racing-banyan-t8njkrk` or `nathalya-ai`).
3. Navigate to **Settings** > **Git**.
4. Confirm that **Connected Git Repository** points to `DiThaNel/NathalyaAI` and **Production Branch** is set to `main`.
5. Under **Deploy Hooks / Automatic Deployments**, ensure production branch deploys are enabled.

If the project was originally deployed using anonymous CLI mode, import the repository directly:
- Click **Add New...** > **Project** > **Import Git Repository**.
- Select `DiThaNel/NathalyaAI` and deploy with default settings (Framework: Other / Static HTML).

---

## Local Development

To run and preview the project locally, use any static web server:

### Option 1: Python
```bash
python -m http.server 3000
```

### Option 2: Node.js (npx serve)
```bash
npx serve -p 3000 .
```

Then open `http://localhost:3000` in your web browser.

---

## Studio Information

- Founder: Nathalya Reis (Fine Line & Master Tattoo Artist since 2015)
- Studios: Braganca & Vila Real, Portugal
- Guest Spots: Porto & Lisbon
- Team: 7 Resident Artists
- Operating Model: Private studio, by appointment only
