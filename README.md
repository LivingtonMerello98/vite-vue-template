Guida per Configurare il Progetto
Benvenuti! Seguite questi semplici passaggi per configurare e avviare il progetto basato sul template. Questa guida è pensata per aiutarvi a iniziare facilmente.

1. Creare una Nuova Repository
Accedere al Template

Vai alla pagina del template su GitHub. [Link al template]
Creare una Nuova Repository

Clicca sul pulsante "Use this template".
Inserisci un nome per la nuova repository.
Clicca su "Create repository from template".
2. Clonare la Nuova Repository
Ora che hai creato una nuova repository, devi clonarla sul tuo computer.

Aprire VSCode

Selezionare la voce 'Clone Git Repository'
Selezionare dove si vuole salvare la repository
Aprire la vs code con il Progetto scaricato

bash
Copia codice
git clone https://github.com/tuo-username/nome-repo.git
Accedere alla Cartella del Progetto

Spostati nella cartella del progetto:

Eseguire il Comando di Installazione

bash
Copia codice
npm install
Questo comando installerà tutto ciò di cui il progetto ha bisogno per funzionare.

3. Avviare il Server di Sviluppo
Ora sei pronto per vedere il progetto in azione!

Avviare il Server

Esegui il comando:

bash
Copia codice
npm run dev
Questo avvierà un server di sviluppo e il progetto sarà disponibile su http://localhost:5173. Apri questo URL nel tuo browser per vedere il progetto.

Dipendenze del Progetto
Il progetto utilizza i seguenti pacchetti:

sass: Permette di usare SCSS per gli stili.
bootstrap: Framework CSS per un design reattivo e moderno.
axios: Libreria per fare richieste HTTP.
vue-router: Gestisce la navigazione tra le pagine in Vue.js.
@fortawesome/fontawesome-free: Icone FontAwesome per aggiungere icone al progetto.
@fortawesome/vue-fontawesome: Integrazione di FontAwesome con Vue.js.
Tutti questi pacchetti sono già inclusi e configurati nel progetto. L'installazione con npm install li aggiungerà al tuo ambiente di sviluppo.