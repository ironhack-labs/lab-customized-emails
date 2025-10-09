## Setup
I used the base customer review for a blender and generated three customized email replies.
Each prompt tested a different structure and temperature level:
- Version 1: Structured policy-driven format (temperature 0.2)
- Version 2: Brand-voice and empathy dialed in (temperature 0.6)
- Version 3: Dual output — customer email + internal note (temperature 0.7)

## Results Summary

### Version 1
**Output:** Clear, professional, and policy-focused.  
It strictly followed the predefined sections — Subject, Greeting, ThankYou, etc.  
**Strengths:** Reliable and consistent tone; followed all constraints perfectly.  
**Weaknesses:** Rigid; sounded slightly mechanical and less human.

### Version 2
**Output:** Much warmer tone with empathy. Included an apology, a 30% discount, and customer-care contact.  
**Strengths:** Best emotional balance; detailed yet concise; felt genuine.  
**Weaknesses:** Slight tendency to over-promise (offered a discount even when not mentioned).  

### Version 3
**Output:** Two-part response — customer email plus internal note summarizing issue, priority, and action.  
**Strengths:** Highly practical for real customer service systems; useful for internal handoff or ticket escalation.  
**Weaknesses:** Customer section was solid but a bit shorter; internal note sometimes generalized too much.

## Hallucinations / Issues
- Minor: Model occasionally added gestures (like discounts) not stated in the review.
- No major hallucinations or structural errors occurred.
- Clear instructions in the prompt minimized variance.

## Lessons Learned
- **Prompt structure controls tone and reliability.** Adding explicit sections guarantees consistency.
- **Temperature impacts creativity.** Lower values give formal consistency, higher ones improve empathy and naturalness.
- **Context-rich prompts create better alignment.** Providing both review and sentiment drastically improved relevance.
- **Operational value can be added.** Version 3 showed how AI can help internal workflows, not just customer-facing replies.

## Conclusion
Version 2 delivered the most human and balanced email.  
Version 1 was ideal for templates or automated policy replies.  
Version 3 proved most valuable for real-world deployment, as it supports both communication and internal action.