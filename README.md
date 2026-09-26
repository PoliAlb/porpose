# Roadmap Certificazioni — Percorso "Advanced Offensive Security" (stile TAO/NSA)

> **Nota**: nessuna certificazione civile replica davvero le competenze del gruppo TAO (Tailored Access Operations) dell'NSA, che si basano anche su strumenti proprietari, 0-day non pubblici e un contesto operativo classificato. Questo percorso ti porta il più vicino possibile in termini di competenze tecniche pubblicamente acquisibili, in modo legale ed etico.
>
> **Prezzi**: indicati in USD, riferiti al solo esame/voucher ufficiale (senza corso/bootcamp) dove disponibile. I prezzi cambiano nel tempo — verifica sempre sul sito ufficiale prima di acquistare.

---

## Fase 1 — Fondamenta (0-12 mesi)

| Certificazione | Ente | Prezzo (USD) | Note |
|---|---|---|---|
| **CompTIA Security+** | CompTIA | **$425** | Base di sicurezza informatica generalista |
| **CompTIA PenTest+** *(opzionale, ponte)* | CompTIA | **~$425** | Vedi box sotto |
| **eJPT** (eLearnSecurity/INE Junior Penetration Tester) | INE Security | **$249** | Primo approccio 100% pratico, no teoria a crocette |

**Studio parallelo (non certificabile)**: reti TCP/IP a fondo, Linux/Windows internals, scripting (Python, Bash, PowerShell).

> ### 🔎 PenTest+ come ponte tra Security+ e OSCP?
> **Sì, ha senso solo in un caso specifico**: se vieni da un percorso puramente teorico (Security+) e non hai ancora fatto nessun lab pratico di pentesting, PenTest+ introduce metodologia, information gathering, scripting base e reporting — argomenti che OSCP dà per scontati. È utile soprattutto per chi punta a ruoli governativi/DoD (framework DoD 8570/8140).
> **Se invece hai già esperienza pratica (CTF, home-lab, eJPT)**, PenTest+ è ridondante: passa direttamente a OSCP, che è molto più rigoroso e riconosciuto nel settore offensive security.

> ### 🧭 Traccia parallela: Information Gathering / OSINT
> Da questa fase puoi già avviare **in parallelo** il percorso OSINT (sezione dedicata in fondo al documento). L'information gathering è una competenza trasversale che serve fin dai primi pentest, non solo a percorso offensive avanzato: chi vuole seguire entrambe le tracce può iniziare **OSIP** già ora, insieme a Security+/eJPT.

---

## Fase 2 — Penetration Testing Core (12-24 mesi)

| Certificazione | Ente | Prezzo (USD) | Note |
|---|---|---|---|
| **OSCP** (OffSec Certified Professional — corso PEN-200) | OffSec | **~$1.749** (pacchetto corso 90gg + 1 esame) | Standard de facto dell'hands-on pentesting |
| **eCPPT** (eLearnSecurity/INE Certified Professional Penetration Tester) | INE Security | **~$400-600** | Alternativa/complemento a OSCP |
| **GPEN** (GIAC Certified Penetration Tester) | GIAC | **$999** (solo esame) / ~$8.500 con corso SANS SEC560 | Metodologia pentest strutturata |

> 🧭 **Traccia OSINT parallela**: a questo punto del percorso hai le basi tecniche per affrontare **GOSI** (GIAC Open Source Intelligence), il livello intermedio/avanzato della sezione OSINT.

---

## Fase 3 — Exploit Development & Reverse Engineering (24-36 mesi)

Qui inizi ad avvicinarti al cuore delle competenze TAO: sviluppo exploit, non solo uso di tool esistenti.

| Certificazione | Ente | Prezzo (USD) | Note |
|---|---|---|---|
| **OSED** (OffSec Exploit Developer — EXP-301) | OffSec | **~$1.749+** | Exploit dev su Windows, x86, bypass mitigazioni base |
| **OSEE** (OffSec Exploit Expert — EXP-401) | OffSec | **~$5.000+** (corso avanzato, spesso in presenza/limitato) | Livello massimo OffSec: bypass ASLR, DEP, CFG |
| **GREM** (GIAC Reverse Engineering Malware) | GIAC | **$999** (solo esame) / ~$8.500 con corso SANS FOR610 | Reverse engineering di malware |
| **GXPN** (GIAC Exploit Researcher and Advanced Penetration Tester) | GIAC | **$999** (solo esame) / ~$8.500 con corso SANS SEC660 | Exploit research avanzata |

---

## Fase 4 — Red Team & Operazioni Avanzate (parallelo/successivo)

TAO opera con logica da red team avanzato su larga scala.

| Certificazione | Ente | Prezzo (USD) | Note |
|---|---|---|---|
| **OSEP** (OffSec Experienced Penetration Tester — PEN-300) | OffSec | **~$1.749+** | Evasione AV/EDR, attacchi avanzati |
| **CRTO** (Certified Red Team Operator) | Zero-Point Security | **~$400-500** | Cobalt Strike, evasione EDR, C2 |
| **CRTP** (Certified Red Team Professional) | Altered Security | **~$249** | Fondamenta attacchi Active Directory |
| **CRTE** (Certified Red Team Expert) | Altered Security | **~$299** | AD avanzato, forest/domain trust |

> 🧭 **Traccia OSINT parallela**: livello red team avanzato = momento giusto per **GSOA** (GIAC Strategic OSINT Analyst), il gradino più alto della sezione OSINT — profilazione di bersagli/infrastrutture con tooling automatizzato, in linea con un'operazione stile TAO.

---

## Fase 5 — Specializzazioni chiave per il profilo TAO

| Area | Certificazione consigliata | Prezzo (USD) | Note |
|---|---|---|---|
| **ICS/SCADA (infrastrutture critiche)** | **GICSP** (GIAC Global Industrial Cyber Security Professional) | **$999** (solo esame) / ~$8.500 con corso | TAO ha operato molto su infrastrutture critiche (es. Stuxnet-adjacent knowledge) |
| **Hardware/embedded hacking** | Nessuna certificazione standard dominante — percorso via corsi pratici (es. Colin O'Flynn "Hardware Hacking", training su JTAG/UART/side-channel) | variabile | Competenza chiave TAO, poco certificabile |
| **Kernel exploitation** | Corsi specialistici Corelan / HackSysExtreme (non certificazioni formali) | variabile | Driver Windows/Linux |

---

## Competenze non certificabili ma essenziali
- Sviluppo autonomo di 0-day su software reale (CTF avanzati: pwn.college, Google CTF, DEF CON CTF)
- Programmazione a basso livello: C/C++, Assembly (x86/x64, ARM, MIPS)
- Reverse engineering avanzato: IDA Pro, Ghidra, WinDbg
- OPSEC operativo e infrastrutture C2 custom

## Nota finale
Le capacità reali di TAO includono accesso a intelligence su vulnerabilità non pubbliche, strumenti proprietari, e un contesto legale/operativo (autorizzazione governativa) inesistente nel mondo civile. Questo percorso forma un **red teamer / exploit developer di altissimo livello**, spendibile legalmente in pentesting, vulnerability research o red team professionali — sempre con autorizzazione esplicita per ogni test.

---

# Roadmap complementare — Information Gathering / OSINT

Percorso **parallelo** (non sostitutivo) rispetto a quello offensive security: non va fatto "dopo" tutto il resto, ma può essere iniziato già dalla Fase 1 e proseguito di pari passo, come segnalato dai box 🧭 nelle fasi sopra. TAO fa information gathering anche per profilare bersagli e infrastrutture prima di sviluppare un exploit mirato, e qui l'OSINT diventa disciplina a sé (persone, social media, dark web, crypto tracing, disinformazione) invece che semplice fase preliminare del pentest.

| Livello | Certificazione | Ente | Prezzo (USD) | Focus | Da avviare in parallelo a |
|---|---|---|---|---|---|
| **Base** | **OSIP** | IntelTechniques (Michael Bazzell) | **$300** cert (+ $699 corso opzionale) | OSINT investigativo pratico, metodologia Bazzell | Fase 1 |
| **Intermedio/Avanzato** | **GOSI** (GIAC Open Source Intelligence) | GIAC | **$999** (solo esame) / ~$8.500 con corso SANS SEC487 | Metodologia OSINT, raccolta dati, reporting, dark web | Fase 2 |
| **Avanzato/Operativo** | **GSOA** (GIAC Strategic OSINT Analyst) — *novità 2025, la prima hands-on* | GIAC | **$999** (solo esame) / con corso SANS SEC587 | Automazione con Python, dark web, crypto tracing, disinformazione, forensics su immagini/video/audio | Fase 4 |

**Ordine consigliato**: OSIP (fondamenta pratiche, economico) → GOSI (metodologia strutturata, riconosciuta a livello enterprise/governativo) → GSOA (livello "analista strategico", il più vicino a un vero ruolo da intelligence/TAO-adjacent).
