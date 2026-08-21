# Antibiotici in Chirurgia e Terapia Intensiva

Applicazione web a pagina singola (HTML/CSS/JavaScript, nessuna dipendenza esterna) per la consultazione rapida di schemi di dosaggio antibiotico, divisa in due sezioni:

- **Profilassi chirurgica**: scelta dell'antibiotico per tipo di intervento (con alternative per allergia ai beta-lattamici), dose e ridosaggio intraoperatorio, timing della somministrazione, durata della profilassi postoperatoria, e un calcolatore di dose peso-based (cefazolina/vancomicina).
- **Terapia Intensiva**: terapia empirica per sepsi/shock settico, polmonite nosocomiale (HAP/VAP), infezioni intra-addominali complicate e batteriemia da catetere venoso centrale; tabella dei dosaggi standard dei principali antibiotici; scheda dedicata alla vancomicina (dose da carico/mantenimento/target AUC); scheda di interpretazione del liquor e terapia empirica della meningite batterica; tabella di aggiustamento posologico per funzione renale; calcolatore di clearance della creatinina (Cockcroft-Gault).

Pensata per essere consultata da qualunque dispositivo e salvabile sulla schermata Home di iPhone/Android come web app.

## Utilizzo

Apri `index.html` in un browser, oppure pubblica il repository con **GitHub Pages** per un link condivisibile e installabile sulla schermata Home dei dispositivi mobili (Condividi → Aggiungi alla schermata Home).

Nessuna build, server o dipendenza richiesta: è un singolo file HTML autosufficiente.

## Fonti dei dati

- **Profilassi chirurgica**: Bratzler DW et al. Clinical practice guidelines for antimicrobial prophylaxis in surgery (ASHP/IDSA/SIS/SHEA, 2013); adattamento dosaggi da Stanford Health Care Surgical Antimicrobial Prophylaxis Guideline (rev. 2025); Calderwood MS et al. Strategies to prevent surgical site infections in acute-care hospitals: 2022 Update (SHEA/IDSA/APIC).
- **Sepsi/shock settico**: Evans L et al. Surviving Sepsis Campaign: International Guidelines for Management of Sepsis and Septic Shock 2021 (SCCM/ESICM).
- **Polmonite nosocomiale (HAP/VAP)**: Kalil AC et al. Management of Adults With Hospital-Acquired and Ventilator-Associated Pneumonia: 2016 Clinical Practice Guidelines (IDSA/ATS).
- **Infezioni intra-addominali complicate**: Huston JM et al. The Surgical Infection Society Guidelines on the Management of Intra-Abdominal Infection: 2024 Update.
- **Batteriemia da catetere venoso centrale**: Mermel LA et al. Clinical Practice Guidelines for the Diagnosis and Management of Intravascular Catheter-Related Infection (IDSA).
- **Vancomicina**: Rybak MJ et al. Therapeutic Monitoring of Vancomycin for Serious MRSA Infections: A Revised Consensus Guideline (ASHP/PIDS/SIDP/IDSA, 2020).
- **Dosaggi standard e aggiustamento renale**: Stanford Health Care Antimicrobial Dosing Reference Guide, rev. febbraio 2026.
- **Interpretazione del liquor e meningite batterica**: Shahan B et al. Cerebrospinal Fluid Analysis. Am Fam Physician. 2021;103(7):422-428; Tunkel AR et al. Practice Guidelines for the Management of Bacterial Meningitis (IDSA, 2004); Nigrovic LE et al. Clinical prediction rule for identifying children with cerebrospinal fluid pleocytosis at very low risk of bacterial meningitis, JAMA 2007.

Tutti i contenuti derivano da linee guida internazionali e da una guida di dosaggio antimicrobico ospedaliera di riferimento (non da un protocollo aziendale specifico dell'autore) e possono differire dal prontuario o dai protocolli in uso presso il proprio ospedale.

## Avvertenza clinica

Questo strumento è un supporto alla consultazione e **non sostituisce il giudizio clinico** né i protocolli in uso presso il proprio reparto/ospedale, né il parere di infettivologia/farmacia clinica per i casi complessi. Verificare sempre farmaco, dose, via di somministrazione e funzione renale prima di ogni prescrizione. Segnalare eventuali errori aprendo una Issue su questo repository.

## Licenza

Distribuito con licenza MIT — vedi [LICENSE](LICENSE). La licenza copre il codice, non costituisce validazione clinica dei contenuti.
