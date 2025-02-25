---
title: Rethinking Open Source Responsibility (EOL)
thumbnail: >-
  https://socialify.git.ci/timkicker/eol/image?language=1&logo=https%3A%2F%2Fraw.githubusercontent.com%2Ftimkicker%2FEOL%2Frefs%2Fheads%2Fmain%2Ffile_with_handshake.png&name=1&owner=1&stargazers=1&theme=Light
featured_image: >-
  https://socialify.git.ci/timkicker/eol/image?language=1&logo=https%3A%2F%2Fraw.githubusercontent.com%2Ftimkicker%2FEOL%2Frefs%2Fheads%2Fmain%2Ffile_with_handshake.png&name=1&owner=1&stargazers=1&theme=Light
date: 2025-02-24 15:20:53
tags:
---


For a while now, I’ve been playing with a thought experiment: **what happens when your code is used for something you fundamentally disagree with?**

Open source is great. It encourages collaboration, innovation, and accessibility. But what it doesn’t do is ask whether there should be *any* limits on how software is used. Right now, if you release something under a permissive license, you’re essentially saying: "Here, take this. Use it for whatever you want." And sometimes, that "whatever" includes mass surveillance, AI-driven discrimination, or worse.

Some people argue that this is just the price of open-source. Once you put code out there, it’s out of your hands. But I started wondering: **does it have to be?**

*(Fun fact: Apparently, just asking this question is enough to get your post removed from certain open-source communities [cough](https://www.reddit.com/r/foss/comments/1ix71mu/comment/mek0y9m/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) [cough](https://www.reddit.com/r/opensource/comments/1ix38w4/comment/mej7eu5/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button). The conversation must be *very* settled, right?)*

![](https://socialify.git.ci/timkicker/eol/image?language=1&logo=https%3A%2F%2Fraw.githubusercontent.com%2Ftimkicker%2FEOL%2Frefs%2Fheads%2Fmain%2Ffile_with_handshake.png&name=1&owner=1&stargazers=1&theme=Light)

---

## What Is the Ethical Open License (EOL)?

The **Ethical Open License (EOL)** is a hypothetical licensing model that explores whether open-source can include ethical restrictions. This isn’t about restricting everyday users or stifling innovation. It’s about setting clear boundaries on how software *shouldn’t* be used.

Under EOL, your software **cannot** be used for:

- **Mass surveillance** – No large-scale tracking, unauthorized data collection, or government spying programs.
- **Autonomous weapons** – Your code should not end up in military AI systems or automated combat technology.
- **Discriminatory AI** – No training models that reinforce bias or make decisions based on race, gender, or social class.
- **Exploitation networks** – No use in systems that facilitate child abuse, human trafficking, or other crimes that exploit vulnerable individuals.

This raises a fair question: *who decides what’s ethical?* That’s something that would need clearer definition (which, to be fair, has been one of the biggest criticisms). But ignoring the question entirely doesn’t seem like the best answer either.

---

## How Does EOL Work? (If It Did Work?)

EOL would follow a familiar open-source structure, but with added restrictions on unethical use. It would grant users the right to:

- Use, modify, and distribute the software freely.
- Contribute to the project under the same ethical guidelines.
- Fork or create derivatives as long as they comply with the license terms.

However, if an entity is found to be violating the ethical clauses of the license, they **lose their right to use the software**. This would be enforced through a **defined process**, ideally involving an independent review board (if one could exist without being a bureaucratic nightmare). 

To avoid ambiguity, EOL also provides a **defined process** for addressing violations. This would ideally involve an independent review process where complaints can be filed, reviewed, and addressed based on available evidence.

If a violation is confirmed, the offending party is expected to cease the unethical use immediately or risk losing access to the software under the terms of the license.

Of course, enforceability is a huge concern -- another major critique. If bad actors don’t follow the law, why would they follow a license? That’s a fair point, but licensing isn’t always about stopping the worst offenders. Sometimes, it’s about setting expectations and norms.

---

## The Cost Model of EOL

One important question that comes up with any new license is: **how does the cost model work?**

EOL itself is, like most open-source licenses, **free to use**. Any developer, company, or organization can adopt the license without paying fees. However, the enforcement mechanisms and the potential establishment of an independent ethics review board (IERB) introduce some financial considerations.

### **Potential Costs and Funding Sources**

1. **Self-Governance (Free Model)**  --  In its simplest form, projects adopting EOL could rely on community-driven enforcement, where violations are reported and discussed publicly. This keeps costs low but relies heavily on volunteer effort and public pressure.

2. **Ethics Review Board (IERB)**  --  If a formal IERB were established, it would require funding for:
   - Legal reviews of complaints
   - Investigations into reported misuse
   - Administrative work related to enforcement

   This could be supported through:
   - **Corporate sponsorships** from organizations that believe in ethical open-source development.
   - **Crowdfunding and donations** from developers and supporters.
   - **A tiered compliance model** where companies using EOL-licensed software commercially contribute a small fee toward maintaining ethical oversight.

3. **Hybrid Approach**  --  A mix of self-governance and optional paid enforcement. Smaller projects could rely on community oversight, while larger commercial users could opt into a paid compliance system that helps fund ethical review and enforcement.

The exact cost model isn’t set in stone -- it’s something that would need to be refined based on community feedback and practical needs. The core idea, however, is that ethical enforcement doesn’t have to be a barrier to open-source adoption, but it does require some thought into sustainability.

---

## The Royalty Structure of EOL

*I’m still not entirely sure if a royalty model is the right approach or if it would actually be beneficial. The idea is to create a way for large-scale commercial users to contribute back to the ethical enforcement of open-source projects, but whether this is the best method is something that needs further discussion.*

Another aspect of EOL is its **royalty model** for commercial use. While individuals, nonprofits, and small companies can use the software freely, larger companies generating significant revenue directly from EOL-licensed software are expected to contribute back to the ecosystem.

### **Royalty Rates Based on Annual Gross Revenue**

| Annual Gross Revenue          | Royalty Rate |
|------------------------------|--------------|
| Less than $1,000,000         | 0%           |
| $1,000,000 - $5,000,000      | 1%           |
| More than $5,000,000         | 2%           |

These royalties are calculated based on **annual gross revenue directly attributable to the software or its derivative work**. The goal is to ensure that successful commercial ventures built on EOL-licensed software contribute fairly to its maintenance and ethical enforcement.

Funds collected through royalties can be allocated toward:
- Supporting ethical enforcement efforts
- Maintaining an independent review process
- Funding security audits and compliance verification
- Ensuring long-term sustainability of ethically governed open-source projects

This model helps create a balance between free access for non-commercial use and fair compensation for commercial beneficiaries, ensuring that ethical oversight remains feasible without burdening smaller developers or independent contributors.

---
## The Biggest Pushbacks 

*(And Why They Might Be Right)*

### "Isn’t open-source supposed to be neutral?"

The idea has always been that developers provide the tools, and it’s not their job to dictate how those tools are used.

But software isn’t neutral. A powerful AI model isn’t just some abstract tool -- it actively shapes real-world outcomes. A social media algorithm doesn’t just recommend content -- it determines what millions of people see and believe. And if we, as developers, recognize that, why should we act as if we have no role in what happens next?

That’s where EOL comes in -- not as a perfect solution, but as a proposal for a different way of thinking about open-source responsibility.

### "This isn’t open source. Stop pretending it is."

Okay, fair. It doesn’t fit the OSI definition, which says that open-source software must allow unrestricted use. If *that’s* the definition you go by, then sure, EOL isn’t open source. But if you see open source as something that can evolve, it’s at least worth talking about.

### "Ethics are subjective. You can’t put them in a license."

Completely true. What’s considered ethical today might not be in 50 years. But laws and policies shift too, and we don’t abandon them just because they’re hard to define. The challenge isn’t that ethics change—it’s how to define them in a way that works.

### "Nobody would use this because it’s legally vague."

Honestly, that’s a solid argument. If a license introduces too much risk, companies won’t touch it. If something like EOL were to work, it would need *very* clear definitions and solid legal backing. Right now, it’s more of a conversation starter than a practical tool.

### "Bad actors won’t follow the license anyway."

True again. If someone wants to build something awful, they won’t stop because a license tells them not to. But a license isn’t just about enforcement—it’s about setting a precedent. Big companies *do* care about compliance, and even if this wouldn’t stop everything, it might influence how some organizations think about responsibility.

---

## So… Is This a Good Idea? Probably Not. But It's Worth Discussing.

I’m not saying EOL is *the* answer. I’m not even saying it’s *a* good answer. What I *am* saying is that open-source has a responsibility problem that’s at least worth thinking about. If the reaction is just "shut up, open source is freedom," then maybe the conversation is overdue. 

The **Ethical Open License (EOL)** is up on GitHub. It’s not a finished product. It’s an open discussion. If you’re interested, check it out and let me know your thoughts.

👉 [github.com/timkicker/EOL](https://github.com/timkicker/EOL)

Whether this turns into something real or just sparks a broader conversation, I’ll count that as a win.

---


I don’t see EOL as a replacement for MIT, GPL, or other widely adopted licenses. But I do think it’s worth questioning the idea that software is inherently neutral.

How our code gets used matters. And if we, as developers, have the ability to set ethical boundaries, why wouldn’t we consider it?

