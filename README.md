# ZSH_HistoryIssue

This script backs up, cleans, and reloads your Zsh history by removing unreadable or corrupted lines using the strings command.
What It Does
- Creates a backup of your existing ~/.zsh_history

- Cleans out non-printable characters using strings

- Replaces your original history with the cleaned version

- Reloads the cleaned history into your current shell session

How to install:
<pre>git clone https://github.com/KaliGK/ZSH_HistoryIssue/autoclean_zsh_history.sh</pre>

Make the script executable:
<pre>chmod +x autoclean_zsh_history.sh</pre>

Run the script:
<pre>bash autoclean_zsh_history.sh</pre>
