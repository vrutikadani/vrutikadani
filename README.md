### Vrutik Adani

GTM Systems & AI Engineering @ Lumenis

I build systems that connect GTM data, decisions, and AI-driven action.

Day to day that means a HubSpot and Salesforce stack I own end to end: lifecycle, routing, territories, compensation, and the agents that act on top of them. The repositories below are public reference implementations of those problems, rebuilt with synthetic data. They are not company source code.

**From signals to decisions**

- [account-signals](https://github.com/vrutikadani/account-signals): account signals in, a capacity-limited list of seller actions out. Decay, per-source caps and a fit gate decide priority; ordered rules decide who does what; a model only writes the note. Judged by meetings at seller capacity, not score accuracy.

**Agents inside revenue workflows**

- [ai-sdr-agent](https://github.com/vrutikadani/ai-sdr-agent): first touch on inbound leads. The model labels replies; rules decide scoring, suppression and handoff; anything uncertain goes to a person. Evaluated on what the agent *does*, not just what it labels.

**System of record**

- [hubspot-revops-system](https://github.com/vrutikadani/hubspot-revops-system): how a CRM with 400+ live workflows is organized. Lifecycle as a forward-only state machine, routing as data, approvals across workflows.
- [hubspot-zip-data-quality](https://github.com/vrutikadani/hubspot-zip-data-quality): the address fixer routing depends on. Majority vote between ZIP, city and state, dry run by default, never guesses.

**Revenue infrastructure**

- [commission-engine](https://github.com/vrutikadani/commission-engine): quarterly comp with tier ladders, advances, true-ups and caps. Every constant in config, every payout traceable to a deal row.

Also here: [territory-optimizer](https://github.com/vrutikadani/territory-optimizer), [crm-automation-toolkit](https://github.com/vrutikadani/crm-automation-toolkit), and [Greenway](https://github.com/vrutikadani/Greenway-Phoenix-Sustainability), a 2024 graduate team project I revisited.

**Notes I keep coming back to**

- The model should not decide who owns an account, what a rep gets paid, or whether to email someone who opted out. ([how that's enforced](https://github.com/vrutikadani/ai-sdr-agent#who-decides-what))
- A signal has no value until it changes a decision someone makes. ([what that means for scoring](https://github.com/vrutikadani/account-signals#the-problem))
- Most CRM migrations are governance projects with a data-mapping step attached.

[LinkedIn](https://www.linkedin.com/in/vrutikadani)
