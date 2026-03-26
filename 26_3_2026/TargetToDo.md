

**Date:** 26/03/2026
**Focus Areas:** Frontend Architecture, Full-Stack Hosting, AI Basics, Product Development Foundations

---

## 1. Frontend Architecture – Authentication Project

**Key Learnings:**

* Start with basics, then progressively move to advanced structural patterns.
* Built **UI/UX for core pages**:

  * Entry page
  * Register page
  * Login page
* Implemented **theme support**:

  * Dark mode & Light mode

**Insights:**
Understanding the structural flow of frontend projects is crucial for maintainability and scalability. Start simple, iterate with structure, and enhance with themes and usability.

---

## 2. Hosting Full-Stack Apps on Cloudflare (Free)

**Tools & Services:**

* **Coding:** OpenCode, Antigravity, Minimax
* **Design:** Dribbble, Stitch
* **Analytics:** PostHog
* **Domain Management:** Namecheap
* **Database & Authentication:** Supabase, Clerk
* **Email:** Resend, Supabase
* **Payments:** Dodo Payments
* **Deployment:** Vercel, Cloudflare, Render

**Key Takeaway:**
It is possible to host production-ready full-stack applications for free using a combination of modern cloud tools and services.

---

## 3. AI Basics

**Key Learnings:**

* Generative AI overview: Types of AI service providers and how AI works
* AI is **stateless by default**
* Tools & Agents: Example — [tavily.com](https://tavily.com)

**Insight:**
Understanding AI architecture and tools is essential for integrating AI effectively into applications. Knowing the AI’s stateless nature helps in designing interactions and workflows.

---

## 4. Foundation of Product Development – Class 3

*(From 2.0 Job Ready AI Powered Cohort — Sheryians Coding School)*

### Folder Structure

* Rules of folder structure
* Using `.gitignore` (multiple ways)

### Future of Development

* Emerging role: **AI-native engineers**

### Docker

* What it is & future applications

### Linting & Settings

* Code formatting
* `settings.json` configurations
* Warnings & logging for observability

### Git & GitHub Best Practices

* Commit everything in **chunks**
* Branching model:

  * `main` → feature branches → PR → review → merge
  * Types: Git-flow-Lite, Track-Based-Development
* **Pull Request Etiquette:**

  * Short summary
  * Changes description
  * Screenshots & tests added
  * Request reviewers

**Review Checklist (My Way):**

* Run locally
* Ensure tests exist
* No console logs
* Proper commit messages
* Handle edge cases

**Advanced Git Topics:**

* Sockets, SSM
* Conflict handling: Rebase & merge while keeping history readable

---

### Testing & Quality Assurance

**Types of Tests:**

1. Unit Tests – Individual components
2. Integration Tests – Test multiple modules together
3. End-to-End (E2E) – Full user flow example: Buy → Confirm

**Test-Driven Development (TDD):**

* Write automated, failing tests **before** actual code

---

### Deployment & Maintenance

**CI/CD Pipelines:**

1. Commit to repository → CI runs (lints, unit tests) → build artifact → CD deploys to staging → manual approval → deploy to production

**Monitoring:**

* Logs: What happened
* Metrics: Success rates, user stats
* Traces: Identify where time is spent
* Tools: `logger.ts`, `Security.ts`, Husky for pre-commit test cases, `.nvmrc`

**Scaling Strategies:**

* **Vertical scaling:** Bigger machine (quick, limited)
* **Horizontal scaling:** More instances behind load balancer (reliable)
* **Caching:** Redis / CDN to reduce load
* **Rate-limiting & graceful degradation** for heavy loads

**Bottleneck:**

* A bottleneck occurs when a component limits performance (CPU, memory, network)
* Example: Fast servers but slow database query → overall slowdown

---

### Key Mistakes to Avoid

1. **Over-engineering**

   * Example: “Buying a helicopter to commute to college — cool, but impractical”
   * Use only what is necessary

2. **Under-engineering**

   * Shipping fragile, quick hacks with no tests or logs

3. **Ignoring documentation**

   * Write README, API contracts, setup steps
   * Onboarding should take **5 minutes**, not **5 days**

---

