## Future Work

This project successfully identified **VADER** as the most suitable model for sentiment analysis of Steam reviews among our chosen methods, there are several areas where improvements can be made:

### Fine-Tuning Transformer Models
- Instead of using **pretrained models** like Longformer, we could **fine-tune a transformer on gaming-related datasets** (e.g., Steam, Reddit gaming discussions, or Metacritic reviews) to improve performance.

### Hybrid Model Approaches
- Combining **VADER for short reviews** and a **fine-tuned transformer for longer reviews** may result in a **more robust sentiment analysis model**.
- **Ensemble models** that integrate **multiple sentiment analysis techniques** (lexicon-based and transformer-based) could improve **prediction accuracy**.

### Expanding Sentiment Lexicons for Gaming Language
- Creating a **custom lexicon for gaming terms** (e.g., *pay-to-win, nerfed, broken mechanics*) could help models **better interpret gaming-related sentiment**.

### Aspect-Based Sentiment Analysis
- Instead of just classifying reviews as **positive or negative**, future work could **extract specific aspects** (e.g., *gameplay, graphics, mechanics*) and analyze sentiment for each.
- This would provide **more granular insights** into what players like or dislike about a game.

### Analyzing Sarcasm and Mixed Sentiment
- Many reviews contain **sarcasm or mixed sentiment**, making classification difficult.
- Future research could explore **context-aware NLP techniques** (e.g., GPT models trained on gaming reviews) to improve **sentiment classification** in these cases.

---

 **Next Steps**  
- Contributions and suggestions for improvements are welcome!  
- Feel free to explore the repository, provide feedback, or contribute enhancements.

