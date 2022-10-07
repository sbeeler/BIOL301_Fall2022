# BIOL301_Fall2022
materials for Mines BIOL301 course

# build (from git folder):
jupyter-book build BIOL301_Fall2022

# deploy (from book folder):
ghp-import -n -p -f _build/html

# "script"
cd git
jupyter-book build BIOL301_Fall2022
cd BIOL301_Fall2022
ghp-import -n -p -f _build/html
