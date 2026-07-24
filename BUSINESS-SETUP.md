# Business Setup — LLC, Money, and Accounting

*Checklist for the partners. This is general information, not legal or tax advice —
verify fees and rules when filing, and use the free legal resources below for the
operating agreement.*

## Do we need the LLC before we start building?

No. Writing code requires no entity — building can start today. The LLC needs to exist
before we **sign anything with a client, take any money, or make promises that carry
liability.** But with multiple partners, register soon anyway, for a different reason:
until ownership is written down, everything built is in a gray zone of "whose is this?"
The filing is cheap; the drama of sorting out ownership *after* the platform is valuable
is not.

## Which state? Partners can live anywhere — pick one stable anchor

Members of an LLC can live in different states (or countries); that's completely
normal. The LLC is formed in **one** state, and the only thing that state requires
locally is a **registered agent** — a person or service with a street address there to
receive official mail. A member's home address works; hired registered-agent services
run ~$100/year if nobody's address is stable.

Two facts that make this choice low-stakes:

- **Taxes follow the partners, not the formation state.** LLC profits pass through to
  each member, who pays income tax where *they* live, no matter where the LLC is
  registered.
- **Moving doesn't break anything.** A Minnesota LLC stays a Minnesota LLC while its
  members are at school in Wisconsin or working from Chicago. If the business ever has
  a real office or employees in another state, it registers there as a "foreign LLC"
  (~$100 filing) — a later problem, if ever.

Approximate costs in the partners' states (verify on each Secretary of State site —
fees change):

| State | Form the LLC | Ongoing |
|---|---|---|
| Michigan | ~$50 | ~$25/year statement |
| Wisconsin | ~$130 online | ~$25/year report |
| Minnesota | ~$155 online (~$135 by mail) | $0/year renewal while in good standing |
| Illinois | ~$150 | ~$75/year report |

Nowhere is formation free — Minnesota's *annual renewal* is free, which is likely the
"free" people mention. The differences are tens of dollars, so **pick the state where
the most stable long-term address lives** (e.g., the managing partner's permanent home)
rather than optimizing fees. Skip Delaware/Wyoming/Nevada pitches — those matter for
venture fundraising, and converting later is easy.

## Formation checklist (same shape in any state)

1. **Pick the name** and check it's free in the chosen state's business-name search.
2. **File Articles of Organization** online with that state's Secretary of State /
   business-filings office (fees above), listing the registered agent's in-state
   address. Put the annual report/renewal date on the calendar the same day.
3. **Get an EIN** from the IRS at irs.gov — free, ~15 minutes online. Never pay a
   third-party site for this.
4. **Operating agreement — the document that actually matters.** With 3–4 partners
   contributing unequally (code, business work, advice), this must answer in writing:
   who owns what percent; whether ownership is earned over time as people contribute;
   what happens when someone walks away; that **all code and IP belongs to the LLC**,
   not to whoever typed it; and how contributions and reimbursements are credited.
5. **Open a business bank account** (needs the EIN + filed articles). Free small-business
   checking at a local bank, or a startup-oriented option like Mercury or Relay.
6. **Move every service under the LLC:** GitHub organization, domain, Vercel, Clerk,
   Neon — all on an LLC email, paid by the business account. Nothing business-critical
   on anyone's personal email or card.

Skip Delaware — home-state registration is simpler and cheaper for a services LLC;
Delaware only matters for venture fundraising and can be done later by conversion.

## University notes (important, cheap to check, expensive to ignore)

- **UW Law & Entrepreneurship Clinic** gives free legal help to student startups —
  exactly the right place to get the operating agreement done properly. The Wisconsin
  SBDC (Small Business Development Center) is a free resource for the business and
  accounting side.
- **The professor should check the university's outside-activity / conflict-of-interest
  rules** before taking equity or a formal role — most universities require reporting.
- **Don't build the product with university resources** (lab equipment, funded research
  time, university accounts) — that can give the university's IP arm a claim on it.
  Personal laptops and personal accounts keep it clean.

## Startup costs paid from someone's pocket

The total is small — filing ~$130, domain ~$15/year, hosting ~$0–75/month — but handle
it correctly from day one:

- **Before the LLC exists:** keep every receipt (a shared folder). Money a partner
  spends becomes either a **capital contribution** (credited toward their stake) or a
  **reimbursable expense** (paid back once the business account exists). Which one, and
  at what rate, is an operating-agreement decision — write it down.
- **Seed the account:** cleanest pattern is each partner contributes a fixed amount
  (e.g., a few hundred dollars) per the ownership split, and the LLC pays its own bills
  from then on.
- **After the bank account exists: never commingle.** Business costs from the business
  account only; a partner who fronts a personal card submits the receipt and gets
  reimbursed. Commingling is both an accounting mess and the classic way LLC liability
  protection gets pierced.
- Startup and organization costs are generally tax-deductible (within IRS limits, with
  the rest amortized) — another reason every receipt gets kept.

## Accounting setup

At this size, accounting is one account, one tool, and one habit:

1. **The business bank account is 90% of the battle** — with all business money in one
   place, the bank statement nearly *is* the books.
2. **One bookkeeping tool:** Wave (free) is enough now; QuickBooks Online is the
   standard if we outgrow it. Record contributions, categorize expenses, invoice
   clients from it when revenue starts.
3. **One habit:** a 30-minute monthly money review — reconcile the account, file
   receipts, note who's owed reimbursement.
4. **When real revenue starts, hire a tax pro.** A multi-member LLC files a partnership
   return (Form 1065) with a K-1 to each partner, and partners may owe quarterly
   estimated taxes — worth paying a professional to set up right the first year rather
   than DIY.
