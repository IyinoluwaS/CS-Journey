# CS-Journey
Documenting my journey as I prepare for a Computer Science degree, mastering programming languages, A-Level Math &amp; Computer Science, and enhancing my writing skills. Follow my progress as I build a strong foundation in tech and academics!
cd Documents
git clone https://github.com/IyinoluwaS/CS-Journey.git
cd CS-Journey


# Create folder structure
mkdir -p CS50/Week0 CS50/Week1 CS50/Week2
mkdir -p A-Level-Math A-Level-CS Writing-Improvement Projects/Personal-Portfolio Projects/Calculator-App

# Create placeholder files
touch README.md
touch CS50/Week0/README.md CS50/Week1/README.md CS50/Week2/README.md
touch A-Level-Math/Learning-Log.md A-Level-Math/Differentiation.md A-Level-Math/Graphs-and-Functions.md
touch A-Level-CS/Learning-Log.md A-Level-CS/Computer-Systems.md A-Level-CS/Boolean-Algebra.md
touch Writing-Improvement/Grammar-Exercises.md Writing-Improvement/Writing-Prompts.md Writing-Improvement/Essay-Practice.md
touch Projects/Personal-Portfolio/index.html Projects/Personal-Portfolio/style.css Projects/Personal-Portfolio/README.md
touch Projects/Calculator-App/script.py Projects/Calculator-App/README.md

# Stage, commit, and push everything
git add .
git commit -m "Initial folder structure and placeholder files"
git push origin main  # or `master` if that’s your default branch
