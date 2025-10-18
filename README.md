# Sponsorship Agent AI

This project automates the process of drafting and sending cold emails to potential sponsors, such as companies and universities, for upcoming conferences. The goal is to clearly communicate sponsorship benefits and secure partnerships more efficiently.

---

## Features
- Drafts multiple tailored sponsorship emails using AI agents  
- Evaluates drafts to select the most suitable version  
- Generates finalized HTML-formatted emails  
- Sends polished emails automatically to the sponsor list

  ---

## Technologies Used
- **OpenAI SDK** – For building and coordinating AI-driven agents  
- **SendGrid** – For reliable email delivery and tracking
 

## How It Works
1. **Drafting Agents**  
   Three agents generate different sponsorship email drafts:  
   - Professional tone  
   - Convincing tone  
   - Busy executive tone  

2. **Evaluation Agent**  
   - Compares drafts against sponsor targeting criteria  
   - Selects the draft that best matches the sponsor’s profile  

3. **Formatting Agent**  
   - Converts the chosen draft into a clean HTML email  

4. **Sending Agent**  
   - Sends the finalized HTML email to the sponsor list  
   - Ensures reliable delivery through SendGrid and logs results  

---

## Workflow Overview
1. Drafting agents produce multiple cold email variations  
2. The evaluation agent chooses the best draft  
3. The formatting agent prepares it for email delivery  
4. The sending agent delivers it to the sponsor list.

