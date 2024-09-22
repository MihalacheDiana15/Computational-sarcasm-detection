# Computational-humor-sarcasm-irony-detection

Această lucrare de licență propune aprofundarea unui sistem de învățare automată și a modelelor preantrenate de tip transformatori, cu scopul detectării sarcasmul din tweet-uri publicate în limba engleză. S-a folosit un corpus de aproximativ 3.000 de date adnotate manual, 25% dintre acestea fiind de tip sarcastice și 75% fiind nonsarcastice. Am continuat apoi cu derularea unor experimente: analiza setului de date, POS-tagging, continuându-se cu algoritmi clasici de învățare automată, modele de tip transformers (BERT). Cel mai bun rezultat este dat de modelele BERT, în special Twitter RoBERTa base, având scorul 𝐹1_sarcastic de 0.53. S-a realizat și o clasificare pentru 6 categorii: sarcasm, ironie, satira, subestimare, exagerare, întrebare retorică, folosind modelul Twitter RoBERTa base cu scorul macro-𝐹1 de 0.134. S-a creat o aplicaţie folosind Python şi Flask, care detectează dacă un text dat de utilizator este de tip sarcastic sau nonsarcastic.
