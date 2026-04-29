# CHI Insurance Brokers — Insurance Presentation Generator

Αυτόματη δημιουργία παρουσιάσεων ασφάλισης από PDF προσφορές, με χρήση Claude AI.

## Εγκατάσταση

```bash
# 1. Κλωνοποίηση / κατέβασμα του φακέλου
cd chi_insurance_app

# 2. Εγκατάσταση dependencies
pip install -r requirements.txt

# 3. Εκκίνηση
streamlit run app.py
```

## Χρήση

1. Ανοίγεις το browser στο http://localhost:8501
2. Βάζεις το **Claude API key** σου (από console.anthropic.com)
3. Συμπληρώνεις στοιχεία πελάτη (όνομα, ηλικίες)
4. Ανεβάζεις 2-4 PDF προσφορές
5. Πατάς **"Ανάλυση με Claude API"**
6. Claude εξάγει αυτόματα όλα τα στοιχεία
7. Επιλέγεις ποια πρόταση να είναι "Προτεινόμενη"
8. Πατάς **"Δημιουργία PPTX"** → Download!

## Deploy στο Streamlit Cloud (δωρεάν)

1. Ανέβασε τον κώδικα στο GitHub
2. Πήγαινε στο https://share.streamlit.io
3. Σύνδεσε το GitHub repo
4. Deploy!

Για να κρύψεις το API key, δες: https://docs.streamlit.io/deploy/streamlit-community-cloud/deploy-your-app/secrets-management

## Στοιχεία

- **Broker:** CHI Insurance Brokers
- **Email:** info@chiinsurancebrokers.com
- **Tel:** +30 697 590 0189
