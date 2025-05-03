# CS-Journey
Documenting my journey as I prepare for a Computer Science degree, mastering programming languages, A-Level Math &amp; Computer Science, and enhancing my writing skills. Follow my progress as I build a strong foundation in tech and academics!
cd Documents
git clone https://github.com/IyinoluwaS/CS-Journey.git
cd CS-Journey

# Create main folders
mkdir -p CS50/Week{0..12} A-Level-Math A-Level-CS Writing-Improvement Projects

# CS50 Weeks with README.md
for i in {0..12}; do
  mkdir -p "CS50/Week$i"
  echo "# Week$i Notes" > "CS50/Week$i/README.md"
done

# A-Level Math
echo "# A-Level Math Log" > A-Level-Math/Learning-Log.md
echo "# Differentiation Notes" > A-Level-Math/Differentiation.md
echo "# Graphs and Functions Notes" > A-Level-Math/Graphs-and-Functions.md

# A-Level Computer Science
echo "# A-Level CS Log" > A-Level-CS/Learning-Log.md
echo "# Computer Systems Notes" > A-Level-CS/Computer-Systems.md
echo "# Boolean Algebra Notes" > A-Level-CS/Boolean-Algebra.md

# Writing Improvement
echo "# Grammar Exercises" > Writing-Improvement/Grammar-Exercises.md
echo "# Writing Prompts" > Writing-Improvement/Writing-Prompts.md
echo "# Essay Practice" > Writing-Improvement/Essay-Practice.md

# Projects
mkdir -p Projects/Personal-Portfolio Projects/Calculator-App
echo "# Personal Portfolio Project" > Projects/Personal-Portfolio/README.md
touch Projects/Personal-Portfolio/index.html
touch Projects/Personal-Portfolio/style.css

echo "# Calculator App Project" > Projects/Calculator-App/README.md
touch Projects/Calculator-App/script.py

# Root README
echo "# CS-Journey

Documenting my journey as I prepare for a Computer Science degree, mastering programming languages, A-Level Math & Computer Science, and enhancing my writing skills.

Follow my progress as I build a strong foundation in tech and academics!
" > README.md
