# VAPI Settings

## Assistant

- Model: OpenAI GPT-4o-mini or Groq Llama 3.1
- Voice: any natural receptionist voice
- Transcriber: Deepgram Nova
- First message: "Hello, this is the clinic assistant. How can I help you today?"

## Tools

Create 3 server/webhook tools pointing to your n8n production webhook:

1. `check_slots`
2. `book_appointment`
3. `log_call`

## Required fields

For booking:

```json
{
  "intent": "book_appointment",
  "patientName": "Sara Khan",
  "phone": "+212600000000",
  "date": "2026-06-15",
  "time": "10:30"
}
```

## Safety

Do not allow the voice agent to diagnose patients. For emergencies, redirect to local emergency services.
