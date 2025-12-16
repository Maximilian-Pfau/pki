# Original ändert sich

git fetch upstream
git checkout dev
# aktueller upstream/main Stand und alle Commits aus aktuellen Branch werden einzeln in gleicher Reihenfolge oben drauf gesetzt
git rebase upstream/main
git push --force-with-lease

# Fortsetzen
git rebase --continue
# Abrechen, keine Veränderungen
git rebase --abort 
