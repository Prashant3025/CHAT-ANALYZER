📱 GroupDNA — WhatsApp Chat Analyzer
A Python-based analyzer that takes a WhatsApp group chat export and reveals the group's "DNA" — who talks the most, when the group is most active, and what everyone's actually talking about.

Built using only core Python and NumPy — no external libraries like pandas or matplotlib.

File: DOOMSDAY.ipynb

✨ Features
📊 Basic Stats — total messages, words, media shared, links shared, deleted messages
👥 Most Active Users — who dominates the group
⏰ Activity by Hour — peak chatting hours
📅 Activity by Day of Week — which day the group is most alive
🔥 Busiest Day — the single most active date
😴 Inactive Days — days with zero messages
💬 Most Common Words — top words used (with Hinglish stopword filtering)
🛠️ Tech Stack
Python (core language, standard library only)
NumPy (numeric computations)
Google Colab (development environment)
🚀 How to Use
Export your WhatsApp chat: Chat → More → Export chat → Without Media
Open DOOMSDAY.ipynb in Google Colab
Run the cells top to bottom
Upload your exported .txt file when prompted
View your group's stats instantly
