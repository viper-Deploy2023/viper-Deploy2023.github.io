# About

This document outlines the key components and features of our project, detailing the various technologies and methodologies we've employed.

### Tech Stack
- **Python 3:** The core programming language used.
- **Discord API:** Integrates with Discord for bot functionalities.
- **Yake:** Utilized for keyword extraction.

### Question Detection
- **Token Parsing:** Utilizes regex to break down long messages into smaller tokens.
- **Detection Logic:** Identifies if each token begins with keywords that signify a question.

### Yake - Keyword Extractor
- **Function:** Extracts keywords from sentences.
- **Ranking System:** Keywords are ranked based on their relevance, with scores closer to 0 indicating higher significance.

### Overall Architecture Design
- **Data Structure:** Employs a hash table for efficient data handling.
- **Key Management:** Uses keywords as the primary keys.
- **Value Storage:** Associates lists of messages with each key.

### Discord API Integration
- **Setup:** Utilized the Discord Developer Portal to establish team and applications.
- **Bot Creation:** Developed a bot using a Discord token.
- **Interaction Handling:** Implements `discord.interactions` and events for slash command functionality.
- **Data Presentation:** Utilizes embeds for displaying information.

### Work-in-Progress (WIP)
- **Database Migration:** Transitioning from Pickle to TinyDB.
- **Data Restoration:** Implementing a human-readable JSON file to restore data after bot restarts.
- **Interactive Features:**
  - Query users and admins on question categorization and answer storage.
  - Enable or disable responses.
  - Internal statistics management.
- **NLP Enhancements:** Support for keyword extraction and answer summarization.
- **Cross-Platform Compatibility:** Enable cross-channel and server support.
- **Security:** Focus on input sanitization.
- **API Implementation:** Planning to integrate Canvas API.

---