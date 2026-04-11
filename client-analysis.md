# Client Brief — Full Analysis
**Project:** Performance Peptide UK  
**Client:** frostyjon (Jon Myerscough)  
**Email:** jon.myerscough@gmail.com  
**Date Analyzed:** April 11, 2026

---

## 1. WHO IS THIS CLIENT AND WHAT DO THEY ACTUALLY WANT?

**Jon runs a new peptide brand in the UK.** Peptides are sold legally in the UK but only as "research chemicals" — NOT for human consumption. This is a legal grey area. Because of this, the client deliberately wants TWO SEPARATE websites so that sales info and dosing/guidance info are never legally linked.

### Website 1 — The Ecommerce Store
- Domain: `www.performancepeptideuk.com`
- Purpose: Sell peptides online
- Platform: WordPress + WooCommerce
- 32 products, selling by request only (no stock kept — he orders based on customer requests)
- Features needed:
  - Monochrome theme with animations (visually premium, dynamic)
  - 18+ opt-in page / disclaimer ("for research purposes only")
  - Product catalog (32 items, categories)
  - Payment system via **Wallid** payment platform
  - Optional: crypto payment support
  - Stock level indicators
  - Email capture / newsletter marketing
  - User authentication

### Website 2 — The Info / Forum Site
- Domain: `www.peptideinfo.co.uk`
- Purpose: Provide information and anecdotal dosing guidance about peptides
- This site has NO direct link or connection to the sales site (intentional, legal reason)
- Think of it as a "community resource" — guides, info, maybe a forum
- Currently hosted on IONOS (Jon already bought hosting + domain there)
- Scope is FLEXIBLE — at minimum it's a nice information page; at maximum it has a full phpBB-style forum

---

## 2. THE IONOS SITUATION — EXPLAINED CLEARLY

### What is IONOS?
IONOS is one of Europe's largest web hosting companies (30+ years, 6.5 million customers). They offer:
- Web hosting (shared)
- WordPress hosting
- WooCommerce-specific hosting plans
- Domain registration
- Email hosting

### What did the client buy on IONOS?
Jon purchased an IONOS hosting plan + the domain `peptideinfo.co.uk` on a **cheap promotional offer** (very low first-year price). This plan is meant to host the INFO site.

### Can IONOS run two websites?
- **Each IONOS hosting plan = 1 website by default** on standard plans
- To run 2 separate WordPress sites, you'd need 2 separate IONOS plans (or a plan that supports multiple domains/installs)
- However — **the client is NOT asking you to run both on IONOS.** He is asking you to:
  - Keep IONOS for `peptideinfo.co.uk` (already paid for, cheap)
  - Host `performancepeptideuk.com` on separate/better hosting (you decide)

### The IONOS Decision the Client Needs to Make
Jon bought IONOS for the info site but wonders if it makes sense to cancel IONOS and consolidate everything onto one host (wherever you set up the ecommerce site). He said:
> "I don't mind if I need to cancel the ionos contract but would need to do that in the next couple of days"

This means: **he's still within the cancellation window — this is time-sensitive.**

### Your Recommendation to Give the Client
**Keep IONOS for now.** It's already paid for and cheap. The info site is simpler — IONOS is fine for a basic WordPress info/forum site. The main ecommerce store (`performancepeptideuk.com`) should be on a proper WooCommerce-ready host (Kinsta, WP Engine, Cloudways, or even IONOS's own E-Commerce WordPress plan which includes WooCommerce + 5GB high-speed DB).

IONOS actually has a specific **E-Commerce WordPress plan (£10/month)** that includes WooCommerce pre-installed — so even if you decide to use IONOS for the main site, it's technically possible.

---

## 3. "BUNDLING 2 WEBSITES INTO 1 PROJECT" — WHAT IT MEANS

The client asked:
> "Would you be comfortable bundling the 2 sides of this into 1 project?"

**Translation:** He wants you to build BOTH websites as one contract/project on Fiverr — instead of two separate orders. He's asking if you're willing to quote and deliver both sites together.

**Answer:** Yes, you can bundle both into one project with separate milestones. The sites themselves are still separate (different domains, different WordPress installs) but you manage them as one engagement.

---

## 4. THE 4-MILESTONE PAYMENT PLAN — BROKEN DOWN

Client proposed this payment structure:

| Milestone | What it is | What gets paid |
|---|---|---|
| **#1** | Securing your services — contract begins | Upfront deposit to start |
| **#2** | Arbitrary mid-milestone | Some payment after showing progress |
| **#3** | Ecommerce site complete | `performancepeptideuk.com` is live and working |
| **#4** | Info/forum site complete | `peptideinfo.co.uk` is built and live |

**Important notes:**
- Client said Milestone 4 he will only commit to **after he sees the working ecommerce site** — so Milestone 4 may be a separate order placed later
- "The last part isn't as urgent, but will still play a helpful part with backlinks" — meaning the info site helps SEO for the main store (Google sees it as a related authority resource)

---

## 5. THE PRICE CONFUSION — WHAT HAPPENED

- You originally quoted: **£391 for Part 1 (ecommerce site)**
- Then your proposal document updated to: **£445**
- Client noticed and said: "your proposal has crept up in price from the original £391 - £445"

Client confirmed £391 is acceptable for Part 1 ("the £391 for part one is cool"). But the revised proposal went up and confused him. You need to clarify in your next message:
- Is £391 the final price for the ecommerce site?
- What made the price change to £445?
- Quote the info/forum site separately (Milestone 4)

---

## 6. BANKING / PAYMENT GATEWAY — WHAT THE CLIENT MEANS

Client said:
> "My partner and I are looking at a couple of potential banking routes including UK onshore and possibly setting up in Dubai."

**Translation:** The business banking is not finalized yet. He might use a UK business bank account OR set up a company in Dubai (common for tax optimization) and bank there.

**What this means for you:**
- The payment gateway (Wallid, Stripe, crypto) must be **easy to swap out**
- Don't hardcode the payment method — build it modular
- He will temporarily use one payment account and change it later once his accountant advises
- No surprises means: **don't use a payment provider that locks in a specific bank or business entity permanently**

**Wallid** — the payment platform the client specifically requested — is a crypto-friendly payment gateway used in e-commerce. It supports fiat + crypto. This fits with his Dubai/crypto interest.

---

## 7. HOW FIVERR PAYMENTS WORK (client asked this)

Client asked: "Is it in escrow and you get paid on results or is it all up front to you and I bear all the risk?"

**The real answer to give the client:**
- Fiverr uses an **escrow system** — the client pays upfront but the money is held by Fiverr
- You (the seller) only receive the money when the client **marks the order as complete** OR after 3 days automatically
- If there's a dispute, Fiverr mediates
- So the client is **NOT** taking all the risk — his money is protected until delivery is confirmed
- For milestone-based large orders, you'd set up a **Custom Offer** on Fiverr with milestones, and each milestone payment is released separately

---

## 8. THE FORUM VS INFO PAGE DECISION

Client said:
> "This may only end up being an information dump with pretty pictures.. depending on the quote and requirements for something like a forum"

**Translation:** The info site scope depends on cost.
- **Option A (cheaper):** Just a nice static WordPress site — articles, guides, product info, no user accounts. Think blog + resource library.
- **Option B (more expensive):** Full forum — users sign up, post threads, discuss dosing etc. Requires phpBB or BuddyPress/bbPress in WordPress.

You need to quote both options and let the client decide. Given his budget sensitivity, Option A for now with Option B as an upgrade makes sense.

---

## 9. IONOS LOGIN CREDENTIALS (FOUND IN CHAT)

> ⚠️ SECURITY NOTE: The client shared login credentials in the Fiverr chat. This is insecure. Advise him to change these after you're done.

- IONOS account email: **jon.myerscough@gmail.com**
- IONOS password: **f%R05tyS3!!s** (part1 + part2 combined, no spaces)
- He offered to give you IONOS access to check if the plan is worth using

---

## 10. FULL PROJECT SUMMARY — YOUR ACTION PLAN

### Immediate (time-sensitive)
1. Tell the client whether to keep IONOS or cancel (he needs this in 1-2 days)
   → **Recommendation: Keep IONOS for the info site. It's free money basically.**
2. Clarify the price — confirm £391 for ecommerce or explain the £445 revision

### Project Scope (both sites)
| | Ecommerce Site | Info Site |
|---|---|---|
| Domain | performancepeptideuk.com | peptideinfo.co.uk |
| Platform | WordPress + WooCommerce | WordPress |
| Host | New quality host (or IONOS E-Commerce plan) | IONOS (already set up) |
| Features | Shop, 18+ disclaimer, Wallid payments, email capture, animations | Articles, guides, optional forum |
| Milestone | #3 | #4 |
| Urgency | High | Low |

### Tech Stack
- **WordPress + WooCommerce** for the shop
- **Wallid** as payment gateway (with optional crypto support)
- **Monochrome theme** — dark/premium look with animations
- **phpBB or bbPress** for forum (if approved)
- **Email marketing** — Mailchimp or WooCommerce Mailchimp integration

### Questions You Need to Ask the Client
1. What hosting are you currently using for `performancepeptideuk.com`? Or is that domain not hosted anywhere yet?
2. Can you confirm — is the final price £391 or £445 for Part 1?
3. For the info site — static article page or full user forum?
4. Do you have a bank account set up to receive payments (Wallid requires this)?
5. Do you have a logo file you can share?
