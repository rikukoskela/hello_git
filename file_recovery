# Lisää uusi etätietovarasto
git remote add upstream https://course-gitlab.tuni.fi/git-course/basics-materials.git

# Nouda etätietovaraston versiohistoria
git fetch upstream

# Yhdistä (merge) etätietovaraston historia omaan tietovarastoosi
git merge upstream/master --allow-unrelated-histories

# Määritä Gitin asetukset, jos saat virheilmoituksen divergent branches
git config pull.rebase false

# Yhdistä (merge) uudelleen
git merge upstream/master --allow-unrelated-histories

# Etsi haluamasi version commit-id
git log upstream/master -- mergesort.py

# Palauta mergesort.py-tiedosto kyseisestä commit-id:stä
git checkout <commit-id> -- mergesort.py

