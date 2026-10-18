# UHIRED

An AI interview-practice application created by Edson Henrique for the 2024
Microsoft Developers Azure AI & Azure Cosmos DB Learning Hackathon.

**Recognition:** first place, confirmed in
[Microsoft's winner announcement](https://devblogs.microsoft.com/cosmosdb/meet-the-winners-microsoft-developers-azure-ai-azure-cosmos-db-learning-hackathon/)
and the [Devpost submission](https://devpost.com/software/aitism).

## Why I built it

I found it difficult to explain my experience clearly in interviews. UHIRED grew
out of that problem: enter a job description, practice answering questions aloud,
and receive feedback on each answer. My [project story and demo](https://devpost.com/software/aitism)
describe the motivation and the hackathon implementation.

## Technical scope

The submitted application used Azure OpenAI for the conversation, Azure Speech
for speech recognition and playback, Azure Cosmos DB for storage, and
Next.js/TypeScript with Tailwind for the interface.

The interesting engineering questions are still practical ones: how to keep a
spoken exchange responsive, preserve the conversation's context, and make feedback
specific to the role. A follow-up study would need to measure those behaviors.

## Project record

The linked submission records the 2024 hackathon project and award. This overview
is a project record; the demo's current availability has not been verified.

My [Enterprise AI Lab](https://github.com/edsonsims/enterprise-ai-lab) contains
new, separately implemented experiments with runnable code and reproducible results.
