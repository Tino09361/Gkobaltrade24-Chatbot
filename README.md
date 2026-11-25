# GlobalTrade24 – KI-Kundenservice-Chatbot (Schulprojekt)

Demo eines Kundenservice-Chatbots für die **fiktive** GlobalTrade24 GmbH (internationaler Onlinehändler).
Schulprojekt im Fach Wirtschaftsinformatik – Außenhandel, BS:WI Hamburg.

**Live-Demo:** über GitHub Pages (Link in der Projektbeschreibung rechts).

## Funktionen
- Messenger-Design im Stil bekannter Chat-Apps, lockerer Du-Ton
- Fragt bei Sendungsanfragen automatisch beim Spediteur nach – Antwort nach wenigen Sekunden
- Erstellt Rechnungen (USt. des Bestimmungslandes / steuerfreie Ausfuhr Schweiz) und Mengenangebote
- Erklärt die 5 Bestseller mit Datenblatt
- **Jede beliebige Bestellnummer und E-Mail funktioniert** – der Bot simuliert passende Sendungsdaten (Land wird aus der E-Mail-Endung abgeleitet)
- **Incoterms® 2020** (EXW, FCA, CPT, CIP, DAP, DPU, DDP): Erklärung, Preisvergleich mit Kostenaufschlüsselung und Risikoübergang
- **Zoll & Einfuhr**: HS-Codes, Zoll/Einfuhrabgaben bei Ausfuhr (CH, GB, NO, TR, USA, China, Japan, VAE), Einfuhr aus Drittländern in die EU (z. B. USA, China) inkl. EUSt., innergemeinschaftlicher Erwerb, Dokumente (MRN, EORI, Ursprungserklärung, A.TR)
- **Fallbezogene Rechnungen**: Inland (19 %), EU-Privatkunde (OSS), EU-Firmenkunde (Reverse Charge), Drittland (steuerfreie Ausfuhr mit MRN)
- **Weiterleitung an Mitarbeiter** mit Name, Telefonnummer und Wartezeit (je nach Thema)
- **B2B-Mengenrabatte**: ab 5 Stück 5 %, ab 10: 8 %, ab 25: 12 %, ab 50: 15 %, ab 100: 18 %, ab 250: 22 %; 2 % Skonto, frachtfrei in der EU ab 5.000 €
- Automatische Spracherkennung: Deutsch, Englisch, Französisch, Spanisch, Niederländisch
- Sendungsverfolgung mit Prüfung von Bestellnummer + E-Mail (Datenschutz)
- Versandkosten und Lieferzeiten je Land
- Zollauskunft: EU-Binnenmarkt vs. Nicht-EU
- Retouren, Rechnungen und Zahlungsarten je Land
- Übergabe an einen Mitarbeiter (Ticket)

## Bestseller
| Produkt | Kategorie | Preis |
|---|---|---|
| ProBook 14 Air | Laptop | 899 € |
| ErgoFlex Pro | Bürostuhl | 349 € |
| ViewMax 27 USB-C | Monitor | 279 € |
| SoundCall Duo | Headset | 89 € |
| DeskDock 12-in-1 | USB-C-Dockingstation | 129 € |

## Test-Bestellungen
| Bestellnummer | E-Mail | Land |
|---|---|---|
| GT24-58123 | j.martin@beispiel.fr | Frankreich |
| GT24-58200 | l.garcia@beispiel.es | Spanien |
| GT24-57990 | a.nowak@beispiel.pl | Polen |
| GT24-58301 | m.keller@beispiel.ch | Schweiz (Nicht-EU) |
| GT24-58044 | s.devries@beispiel.nl | Niederlande |

## Hinweis
Diese öffentliche Version arbeitet **regelbasiert** (ohne KI-Anbindung). Die Version mit echter KI
(Claude) läuft auf claude.ai. Für einen KI-Betrieb auf einer eigenen Website wäre ein Server mit
API-Schlüssel nötig. Alle Daten sind erfunden.
