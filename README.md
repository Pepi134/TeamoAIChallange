# TeamoAIChallange
This is a Flask-based API for matching user-submitted skills against a predefined list of administrator-managed skills using state-of-the-art machine learning techniques. The application leverages Sentence-BERT (SBERT), a transformer-based model, to compute semantic similarity between the input skill and the administrator's skill list. Cosine similarity is used to rank the matches based on their contextual relevance.
Features
Skill Matching: Matches user-provided skills with the closest skills in the administrator's list using SBERT embeddings.
Administrator Management:
Add new skills (/admin/add_skill).
Delete existing skills (/admin/delete_skill).
View all skills (/admin/view_skills).
Advanced ML Techniques:
Uses SBERT (all-MiniLM-L6-v2) for high-quality sentence embeddings.
Computes similarity scores using cosine similarity.
