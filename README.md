#  A_Unified_Privacy_Framework_for_Secure_and_Utility_Preserving_Retrieval_Augmented_Generation___Final

Abstract:
With the growth of the applications of Retrieval Augmented Generation (RAG) systems to extremely sensitive areas, including
healthcare and finance, the privacy of Personally Identifiable Information (PII) and Protected Health Information (PHI) has become
the center of more concerns. The RAG systems of the past retrieve unfiltered text and anonymize it after retrieval, meaning that
sensitive data is still handled within the pipeline and can be leaked and extracted by adversarial users. This drawback led to the
creation of a safer framework where privacy is ensured prior to any form of retrieval. LPRAG shows initial attempts at privacy
preservation but is limited due to its use of document embeddings alone and making perturbations after the retrieval. As a result,
LPRAG can minimize some of the leakage, although it does not essentially remove the risks existing in systems based on retrieval.
The proposed methodology will fill these gaps by integrating privacy into the retrieval pipeline. Simultaneously, extracted entities
and relations constitute a knowledge graph, which allows one to understand relations without having to store sensitive text in or
retrieve it. Proposed system include hybrid retrieval, which involves using a perturbation of sensitive entities in conjunction with
KG-based node and relation embeddings, such that the retriever can use structural context yet with a serious privacy guarantee.
BLEU and ROUGEL scores are always higher in the case of hybrid retrieval than when using only the documents, which proves
that the addition of KG information to document retrieval improves semantics and relevancy in the retrieval. Overall, the thesis
proposes an effective and concise privacy-preserving variant of the RAG architecture that moves the anonymization to the first
stage, employs the structured KG reasoning, and balances between privacy and utility with the help of the hybrid retrieval. The
framework is more resistant to protection and has better retrieval performance than the standard methods, which makes it highly
applicable to the sphere in which both confidentiality and the accuracy are required.
