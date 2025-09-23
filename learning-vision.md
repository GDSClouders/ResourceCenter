
<style>
  body {
    background-color: white;
  }

  .header-grid {
    display: grid;
    grid-template-columns: 1fr auto; /* flexible */
    align-items: center;
    gap: 20px;
  }

  .header-grid img {
    max-width: 100%;
    height: auto; /* proportional */
  }

  /* single column smartphone */
  @media (max-width: 600px) {
    .header-grid {
      grid-template-columns: 1fr; 
      text-align: center;
    }

    .header-grid img {
      max-width: 200px;
      margin: 0 auto;
    }
  }
</style>

<div class="header-grid">
  <div>
    <img src="./images/YelLogo-GDSClouders.png" alt="Logo">
  </div>
  <div>
    <h1>GDSClouders Resource Center</h1>
  </div>
</div>


# Our Learning Vision
We are a continuously learning company. We don’t chase hype; we stay current by **researching, experimenting, and mastering what truly matters** so we can deliver with confidence.

## Principles
- **Research-driven, not trend-driven.** We validate technologies through hands-on exploration, proofs of concept, and internal write-ups.
- **Shared standards, personal paths.** Company goals set the direction; each person tailors their route based on role, interests, and impact.
- **Small, steady steps.** Frequent micro-iterations beat sporadic big pushes.

## Annual Targets 
- **1 major certification** (e.g., Linux Foundation/CNCF—CKA, CKAD, CKS; Oracle; AWS/Azure/GCP Associate/Professional; Red Hat; HashiCorp).
- **3 micro-credentials** (e.g., Udemy, Pluralsight, Coursera, edX, vendor academies) **per year**.

## Cadence
- **Weekly self-assessment (tracked doc, 10–15 min).**  
  A short, structured check-in you complete on your own. Suggested sections:
  1. **Goal for the week** (1–2 sentences)  
  2. **Progress made & links** (PRs, labs, notes)  
  3. **Blockers / questions**  
  4. **Next week’s focus**  
  5. **Hours invested**  
- **Monthly manager check-in (20–30 min).**  
  Review progress vs plan, remove blockers, adjust priorities, and—if useful—schedule a mini-demo.
- **Quarterly plan refresh.**  
  Align personal goals with business priorities, upcoming projects, and capability gaps.

## Planned Learning
Each employee has a **Personal Learning Plan (PLP)** co-created during onboarding/quarterly refresh. It includes:
- **Role-based skill map** (must-have / nice-to-have)  
- **Target certifications & micro-credentials** with timelines  
- **Hands-on milestones** (PoCs, labs, internal talks)  