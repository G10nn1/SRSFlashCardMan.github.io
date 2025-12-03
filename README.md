# SRSFlashCardMan.github.io
Spaced Repetition System (SRS) Flashcard AppThis is a lightweight, single-file web application designed to help users memorize information efficiently using the Spaced Repetition System (SRS) methodology. 
All data persistence is handled locally within the user's browser via IndexedDB, making the application entirely self-contained and free from the need for a server backend.
Key FeaturesPure Static App: Built exclusively with HTML, Vanilla JavaScript, and Tailwind CSS for rapid and easy deployment on any static hosting service (e.g., GitHub Pages).
Spaced Repetition Logic: Implements the core SRS algorithm to calculate optimal review dates based on the user's performance ("OK" or "KO"), minimizing study time and maximizing retention.
Intervals: Utilizes a configurable interval system (e.g., 1, 3, 7, 16, 35 days).Local Data Persistence: All flashcards, review schedules, and statistics are securely stored in IndexedDB in the user's browser. 
Data is private and persistent across sessions. 
Markdown Support: Both question and answer fields support Markdown (MD) formatting via the Marked.js library, allowing for rich text, links, and embedded images in the flashcards.Dashboard & Statistics: Provides a dedicated statistics view showing total cards, cards due today, and success rates, broken down by topic.
