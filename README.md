# 🚀 Caricare un Progetto su GitHub

## ✅ Requisiti

- 🔧 **Git** installato sul sistema  
  👉 Controlla con il comando:  
  ```bash
  git --version
  ```  
  Se non è installato (per Windows), scaricalo da: [https://git-scm.com/](https://git-scm.com/)

- 👤 **Account GitHub**  
  👉 Registrati su: [https://github.com](https://github.com)

- 🖥️ **Visual Studio Code** installato  
  👉 Estensione consigliata: _GitHub Pull Requests and Issues_

---

## 🧭 Passaggi per caricare il progetto

### 1. Aprire il progetto in Visual Studio Code

- Vai su `File > Open Folder`
- Seleziona la cartella del tuo progetto

### 2. Inizializzare Git (se non già fatto)

Apri il terminale integrato in VS Code e lancia:

```bash
git init
```

---

### 3. Creare un file `.gitignore`

Serve per escludere file non necessari dal controllo di versione (es. `node_modules`, `.env`, ecc.)

Puoi generarlo automaticamente con:

```bash
npx gitignore <linguaggio>
# esempio:
npx gitignore python
```

Oppure crea manualmente un file `.gitignore` e incolla un template da:  
🔗 [https://github.com/github/gitignore](https://github.com/github/gitignore)

---

### 4. Aggiungere e fai il primo commit

```bash
git add .
git commit -m "Primo commit"
```

---

### 5. Creare una nuova repository su GitHub

- Vai su [https://github.com/new](https://github.com/new)
- Dai un nome alla repository (es. `il-mio-progetto`)
- **Non spuntare** “Initialize this repository with a README”

---

### 6. Collegare la repository remota

Nel terminale:

```bash
git remote add origin https://github.com/il-mio-progetto.git
```

---

### 7. Inviare i file su GitHub

```bash
git branch -M main
git push -u origin main
```





