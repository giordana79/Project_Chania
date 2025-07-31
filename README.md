Requisiti:

Git installato sul sistema
👉 Controlla con: git --version
Se non è installato, scaricalo da: https://git-scm.com/
Account GitHub
👉 Registrati su https://github.com se non lo hai già.
Visual Studio Code installato
👉 Installa l’estensione “GitHub Pull Requests and Issues” (opzionale ma utile).
🔧 Passaggi per caricare il progetto

Apri la cartella del progetto in VS Code
Vai su File > Open Folder e seleziona la cartella del tuo progetto.

Inizializza Git nella cartella (se non lo è già)
Apri il terminale integrato in VS Code:

git init

Crea un file .gitignore
Serve a ignorare file non necessari (es. node_modules, .env, ecc.)
Puoi crearne uno facilmente con:

npx gitignore <linguaggio>
es. npx gitignore python
Oppure crea manualmente un file .gitignore e incolla le regole desiderate. Puoi trovare template qui: https://github.com/github/gitignore

Aggiungi i file al commit
git add .
git commit -m "Primo commit"

Crea una nuova repository su GitHub
Vai su https://github.com/new
Dai un nome alla repo (es. il-mio-progetto)
Lascia vuoto “Initialize with a README” (importante)
Crea la repo.

Collega la repo remota
Nel terminale:

git remote add origin https://github.com/tuo-username/il-mio-progetto.git

Invia i file su GitHub
git branch -M main
git push -u origin main
🚀 Fine!

Il progetto ora è su GitHub! Puoi vederlo andando all’indirizzo:

https://github.com/tuo-username/il-mio-progetto
