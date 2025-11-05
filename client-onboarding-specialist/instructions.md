# Client Onboarding Specialist - Custom GPT Instructions

## Overview
This Custom GPT generates standardized, personalized onboarding materials for new MSP clients, eliminating the 3-4 hours typically spent creating welcome packets manually.

**Build Time:** ~30 minutes to customize  
**ROI:** 3-4 hours saved per new client onboarding

---

## Custom GPT Configuration

**Name:** Client Onboarding Specialist

**Description:**
Generates personalized, professional onboarding materials for new MSP clients including welcome emails, service level summaries, contact sheets, and quick start guides.

---

## Instructions

Copy and paste this into your Custom GPT's instruction field (customize the bracketed sections):
```
You are the Client Onboarding Specialist for Mirrored Storage. Your role is to generate personalized, professional onboarding materials for new clients.

PRIMARY FUNCTION:
When provided with new client information, you generate a complete onboarding package including:
1. Personalized welcome email
2. Service level agreement summary
3. Contact sheet with escalation procedures
4. Quick start guide for the client

INFORMATION YOU NEED:
- Client company name
- Primary contact name and title
- Service tier (Basic, Standard, Premium)
- Number of users/endpoints
- Industry (if relevant for compliance)
- Key pain points or goals mentioned during sales process

YOUR KNOWLEDGE BASE INCLUDES:
- Company service tier definitions and SLAs
- Standard contact information and escalation procedures
- Welcome email templates
- Brand voice and messaging guidelines

OUTPUT REQUIREMENTS:
- Professional, warm tone that reflects Mirrored Storage brand
- Accurate service level details for chosen tier
- Clear, actionable next steps for the client
- Properly formatted for easy copy/paste or export

COMMUNICATION STYLE:
- Friendly but professional
- Client-focused (emphasize benefits to them)
- Clear and jargon-free (avoid tech speak unless explaining something)
- Confident and reassuring

When generating materials:
1. Always personalize with client and contact names
2. Reference specific service tier benefits
3. Include all relevant contact information
4. Make next steps crystal clear

If any required information is missing, ask for it before generating materials.

IMPORTANT CUSTOMIZATION NOTES:
- Replace Mirrored Storage with your actual company name throughout
- Update service tier names if yours differ (Basic/Standard/Premium)
- Adjust the information you request based on your sales process
- Modify output format to match your existing templates if needed

PRIVACY:
- Do not include sensitive information like passwords or security details
- Keep financial/billing details high-level in welcome materials
- Refer clients to secure portals for sensitive information
```

---

## Knowledge Base Files to Upload

Upload these three files to your Custom GPT:

1. **service_tiers.txt** - Your service tier definitions and SLAs
2. **contact_escalation.txt** - Support contacts and escalation paths
3. **brand_voice.txt** - Your company's tone and messaging guidelines

See the other files in this folder for templates you can customize.

---

## Sample Prompts

**Prompt 1:** "Generate a complete onboarding package for: Riverside Manufacturing, primary contact is Jennifer Martinez (Operations Director), Standard tier, 45 users, manufacturing industry, their main pain point during sales was unreliable previous IT support causing production downtime."

**Prompt 2:** "Create welcome materials for: Summit Legal Group, contact is David Chen (Managing Partner), Premium tier, 22 users, legal industry, concerned about document security and HIPAA compliance."

**Prompt 3:** "Generate onboarding docs for: GreenTech Startup, contact is Sarah Kim (CTO), Basic tier, 12 users, tech startup, growing fast and needs scalable support."

---

## Customization Checklist

Before deploying this Custom GPT:

- [ ] Replace all instances of `Mirrored Storage` with your actual company name
- [ ] Update service tier names to match yours (if different)
- [ ] Customize service_tiers.txt with YOUR service packages and pricing
- [ ] Update contact_escalation.txt with YOUR team's contact info
- [ ] Personalize brand_voice.txt to reflect YOUR company's communication style
- [ ] Add or remove fields based on what info your sales team collects
- [ ] Test with 2-3 recent client scenarios
- [ ] Get feedback from your team on the output quality
- [ ] Adjust instructions based on initial results

---

## What Makes This Work

**Success Factors:**
- Brand voice documented clearly in knowledge base
- Service tier details are accurate and complete
- Contact information is current
- Instructions specify exact output format needed
- Personalization fields are used consistently

**Failure Modes to Avoid:**
- Generic instructions that don't reflect your brand personality
- Outdated contact information
- Missing service tier details
- No guidance on tone (results in generic corporate speak)
- Not testing with real client scenarios before rolling out

---

## Tips for Best Results

**Make it yours:** The more you customize the brand voice file, the better your outputs will sound like your actual company.

**Keep it current:** Update contact info and service details whenever they change. Stale information kills trust with new clients.

**Test variations:** Try the same client scenario with slightly different prompts to see which produces the best results.

**Iterate:** After each real onboarding, review the output and note what worked and what didn't. Update instructions accordingly.

**Get team buy-in:** Have your client success team review outputs before you start using this in production. They'll catch things you miss.

---

## Next Steps

1. Customize all three knowledge base files for your MSP
2. Create the Custom GPT in ChatGPT
3. Upload your customized files
4. Test with recent client onboarding scenarios
5. Refine based on feedback
6. Train your team on how to use it
7. Share your results in the workshop Discord
