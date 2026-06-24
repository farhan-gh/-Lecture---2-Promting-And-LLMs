Goal: Automate youtube videos into structured presentation slides using AI Tool. 

Data Tracking: All iteration metrics, token counts, and failure tracking are logged in the Prompt Engineering Excel Sheet 

LLM USed : Google Gemini

Steps:
	1st Step: Transcribe YouTube video into text (refined from Urdu to English) [Image].
	2nd Step: Convert raw transcript into a structured presentation outline [Image].
	3rd Step: Transform outline into continuous slide text content [Image].
	4th Step: Reivew the output and apply fixes

What Worked: 
Role-prompting and constraint patterns secured clean transcripts and targeted modular layout corrections 

What Failed: 
Vague expansion prompts caused context collapse, restricting slide content to rigid 4–5 bullet blocks 

Key Learning: Well structured prompt, Multi-step modular pipelines (Ingestion → Outline → Component Refinement) defeat generation bugs far better than single-block attempt