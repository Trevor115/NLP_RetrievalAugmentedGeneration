# NLP_RetrievalAugmentedGeneration
1. Which version performed better? Why?
- The version with retrieval performed better because it used information from the corpus to generate its answer. This made the responses more relevant and grounded in the provided documents.

2. When did retrieval help?
- Retrieval helped when the query closely matched information in the corpus. For example, questions about TF-IDF, RAG, and hallucinations returned relevant paragraphs that supported the answer.

3. When did it fail?
- Retrieval failed when a query did not closely match the wording or topics in the corpus. In those cases, the retrieved documents were less relevant and the answer was less useful.

4. Were any answers incorrect or misleading?
- The answer without retrieval could be incorrect because it was not based on any source documents. The retrieval-based answers were generally more accurate, but they could still be misleading if the wrong document was retrieved.

5. What would improve your system?
- The system could be improved by using a larger corpus, better ranking methods, query expansion, and an LLM to generate more natural answers from the retrieved context.

<img width="1548" height="626" alt="Screenshot 2026-11-10 093543" src="https://github.com/user-attachments/assets/225e1ce2-c73f-4706-aafa-b8f54bc7f1ed" />
<img width="1513" height="457" alt="Screenshot 2026-11-10 093658" src="https://github.com/user-attachments/assets/f392f60e-e2a7-4b0c-a1ad-d5f3506a88f9" />
<img width="1515" height="602" alt="Screenshot 2026-11-10 093717" src="https://github.com/user-attachments/assets/9c088d1a-1c04-4dc2-9832-92e4b838c9e2" />
