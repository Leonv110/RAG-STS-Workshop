# RAG-STS-Workshop
# My RAG System

## Topic: Science, Technology, and Society (STS)
- I chose this topic as this is the subject for my NPTEL examination. I can make use of the RAG to answer any of my doubts, to help me prepare for the examination
- The RAG system will hallucinate lesser than the regualar Gen AI chat bots helping me learn from all the lecture materials without loss of information while being accurate.

## What I changed:
- **Documents:** Replaced defaults with 5 lecture notes covering core STS concepts like Technological Determinism, Social Shaping of Technology, and the Ethics of AI.
- **Chunking:** Used `chunk_size=400` and `chunk_overlap=50`. This was found to be more effective for maintaining the coherence of dense academic definitions and arguments in the lecture format.
- **Retrieval:** Switched to a more diverse MMR setting: `k=5`, `fetch_k=10`, and `lambda_mult=0.3`. This improved answers to complex, multi-faceted STS questions by ensuring a broader range of contextual chunks was retrieved.


## Test questions:
1. Beyond economic costs and environmental risks, what is the less appreciated hazard of plutonium recycling and how is it justified by proponents?
2. Describe the two varieties of interpretation outlined by Langdon Winner that indicate how artifacts can have political qualities.

