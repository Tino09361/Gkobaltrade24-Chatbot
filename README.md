# GlobalTrade24 – KI-Kundenservice-Chatbot (Schulprojekt)

Demo eines Kundenservice-Chatbots für die **fiktive** GlobalTrade24 GmbH (internationaler Onlinehändler).
Schulprojekt im Fach Wirtschaftsinformatik – Außenhandel, BS:WI Hamburg.

**Live-Demo:** über GitHub Pages (Link in der Projektbeschreibung rechts).

## Funktionen
- Messenger-Design im Stil bekannter Chat-Apps, lockerer Du-Ton
- Fragt bei Sendungsanfragen automatisch beim Spediteur nach – Antwort nach ca. 1 Minute (Demo-Tipp: Link mit `#schnell` am Ende → 8 Sekunden)
- Erstellt Rechnungen (USt. des Bestimmungslandes / steuerfreie Ausfuhr Schweiz) und Mengenangebote
- Erklärt die 5 Bestseller mit Datenblatt
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
