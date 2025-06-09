# 📱 Dashboard Chat WhatsApp Business

Dashboard professionale per gestire chat WhatsApp Business con 6 operatori simultanei e integrazione AI per generazione preventivi automatici.

## 🚀 Caratteristiche

- **Interface WhatsApp-like** - Familiare e intuitiva
- **6 Operatori simultanei** - Gestione chat multiple
- **AI Integration** - Relevance AI per preventivi automatici
- **Real-time** - Notifiche e aggiornamenti istantanei
- **Assegnazione intelligente** - Automatica e manuale
- **Storico completo** - Chat, preventivi, note clienti

## 🏗️ Stack Tecnologico

### Frontend
- React 18 + Vite
- TailwindCSS per styling
- Socket.io per real-time
- React Router per navigazione

### Backend
- Node.js + Express
- MySQL con Sequelize ORM
- Socket.io per WebSocket
- JWT Authentication

### Hosting
- **Kinsta Application Hosting**
- Deploy automatico da Git
- SSL e CDN inclusi
- Monitoring integrato

## 📋 Setup Progetto

### 1. Clone Repository
```bash
git clone https://github.com/AlfredoAI-Web/dashboard-chat.git
cd dashboard-chat
```

### 2. Install Dependencies
```bash
npm run install:all
```

### 3. Configure Environment
```bash
# Copia .env.example in .env nel server/
cp server/.env.example server/.env

# Configura le variabili:
# - WhatsApp Business API
# - Relevance AI API
# - Database MySQL
```

### 4. Database Setup
```bash
npm run db:migrate
npm run db:seed
```

### 5. Development
```bash
npm run dev
```

## 🔧 Configurazione API

### WhatsApp Business API
- **Token**: Dal tuo account Meta Business
- **Phone Number ID**: Numero WhatsApp Business
- **Webhook URL**: `https://tuodominio.com/api/webhook/whatsapp`

### Relevance AI
- **API Key**: Dal tuo account Relevance AI
- **Tool ID**: ID del tool per generazione preventivi

## 🚀 Deploy su Kinsta

1. **Push codice su GitHub**
2. **Kinsta Dashboard** → Applicazioni → Aggiungi
3. **Connetti repository**: `AlfredoAI-Web/dashboard-chat`
4. **Configura variabili ambiente**
5. **Deploy automatico**

## 👥 Gestione Operatori

### Ruoli Sistema
- **Admin**: Gestione completa sistema
- **Supervisor**: Supervisione operatori
- **Operator**: Gestione chat assegnate

### Funzionalità Operatori
- Dashboard personale chat
- Assegnazione automatica/manuale
- Trasferimento chat tra operatori
- Generazione preventivi AI
- Note clienti e storico

## 🤖 Integrazione AI

### Suggerimenti Risposta
- Analisi contesto conversazione
- Suggerimenti personalizzati
- Modifica prima dell'invio

### Generazione Preventivi
- Analisi richiesta cliente
- Template personalizzabili
- Invio diretto in chat
- Tracking stato preventivo

## 📊 Monitoraggio

- **Performance operatori**
- **Tempo risposta medio**
- **Chat risolte/aperte**
- **Conversion rate preventivi**
- **Uptime sistema**

## 🔒 Sicurezza

- **JWT Authentication**
- **Rate limiting API**
- **Validazione input**
- **Helmet.js security headers**
- **CORS configurato**

## 📱 Responsive Design

- **Desktop-first** per operatori
- **Mobile-friendly** per supervisori
- **Tablet support** per gestione mobile

## 🛠️ Manutenzione

### Backup Database
```bash
npm run db:backup
```

### Logs Monitoraggio
```bash
npm run logs:view
npm run logs:error
```

### Update Sistema
```bash
git pull origin main
npm run build
npm restart
```

## 📞 Supporto

- **Sviluppatore**: Alessandro Alfredo Scotti
- **Documentazione**: `/docs` folder
- **Issue**: GitHub Issues
- **Deploy**: Kinsta Support

---

**Versione**: 1.0.0  
**Ultimo Update**: Giugno 2025  
**Licenza**: MIT
