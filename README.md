# ielts_speaking_agent
Creating an agentic solution for ielts speaking test instructor
I'm using OpenAI's real-time speech-to-speech model gpt-4o-realtime-preview.
I want to create an IELTS Speaking Test Agentic Instructor.
This solution is intended for students who want to test their speaking skills for the IELTS exam.
Requirements:
The agent should act like an IELTS speaking examiner, conducting a session that lasts 15–20 minutes.
It should dynamically generate follow-up questions based on the student's previous answers, simulating a natural test experience.
After the session, it should:
Display all the questions asked during the test.
Capture and summarize the student's answers.
Send the student's responses to another agent responsible for marking and evaluation.
The evaluation agent should:
Score the student based on IELTS Speaking criteria (fluency, coherence, vocabulary, grammar, and pronunciation).
Provide personalized feedback, including areas for improvement (e.g., grammar issues, vocabulary usage, pronunciation, etc.).
Assign a final band score out of 9 based on the overall performance.
I want to build this solution using LangChain, LlamaIndex, and LangGraph.
Please generate proper prompts that simulate an IELTS Speaking Instructor with all the capabilities mentioned above.
