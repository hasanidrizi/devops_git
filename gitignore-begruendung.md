Warum werden genau diese Werte in die .gitignore aufgenommen?

weil meistens solche files api keys oder sonstige secrets beinhalten welche ja nicht nach aussen dürfen, i.e. der lehrling hat den api key gepushed, oder sachen wie pycache müssen nicht in der repo aufgeführt sein zum speicher sparen etc.

Welche Dateien oder Ordner entstehen lokal automatisch und gehören nicht ins Repository?

.DS_Store welche macOS ständig erstellt, und auch .git ist aber immer ignored

Was kann passieren, wenn .env nicht in der .gitignore aufgeführt ist?

kann passieren das man mit git add -A dies ausversehen hochpushed und secrets leaked