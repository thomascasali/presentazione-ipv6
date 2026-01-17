# Presentazione IPv6

Corso interattivo web-based sul protocollo IPv6, realizzato per il corso di **Sistemi e Reti**.

## Descrizione

Questa presentazione offre un percorso didattico completo su IPv6, dalla storia del protocollo fino agli aspetti di sicurezza e transizione. Include simulatori interattivi, quiz e flashcard per facilitare l'apprendimento.

## Demo

Visita la presentazione online: **[https://thomascasali.github.io/presentazione-ipv6/](https://thomascasali.github.io/presentazione-ipv6/)**

## Struttura dei Moduli

| Modulo | Titolo | Contenuti | Simulatore |
|--------|--------|-----------|------------|
| 1 | Da IPv4 a IPv6 | Storia del protocollo IP, crisi IPv4, nascita IPv6 | Timeline interattiva |
| 2 | Indirizzamento | Formato 128-bit, notazione esadecimale, tipi di indirizzi | Convertitore IPv6 |
| 3 | Configurazione | SLAAC, DHCPv6, NDP, DAD, EUI-64 | Simulatore SLAAC |
| 4 | Header e Pacchetto | Struttura header IPv4 vs IPv6, Extension Headers | Header Visualizer |
| 5 | Sicurezza e Transizione | IPsec, Dual-stack, Tunneling, NAT64 | NAT vs IPv6 Simulator |
| 6 | Quiz e Flashcard | 20 domande, flashcard 3D | Quiz interattivo |

## Caratteristiche

- **6 moduli** didattici completi
- **47 slide** con contenuti dettagliati
- **8 simulatori** interattivi
- **20 domande** quiz + flashcard
- **Design responsive** (desktop e mobile)
- **Tema dark mode** per una migliore leggibilità
- **Zero dipendenze server** - funziona offline

## Tecnologie

- **React 18** - UI components (via CDN)
- **HTML5** - Struttura
- **CSS3** - Styling con animazioni e media queries
- **Babel** - Compilazione JSX nel browser

## Utilizzo

### Online
Visita [https://thomascasali.github.io/presentazione-ipv6/](https://thomascasali.github.io/presentazione-ipv6/)

### Locale
1. Clona il repository:
   ```bash
   git clone https://github.com/thomascasali/presentazione-ipv6.git
   ```
2. Apri `index.html` nel browser

### Navigazione
- **Frecce sinistra/destra** - Naviga tra le slide
- **ESC** - Torna all'indice principale
- **Click sui moduli** - Accedi al contenuto

## Struttura Repository

```
presentazione-ipv6/
├── index.html                  # Landing page principale
├── modulo1-storia.html         # Modulo 1: Storia IPv4→IPv6
├── modulo2-indirizzamento.html # Modulo 2: Indirizzamento IPv6
├── modulo3-configurazione.html # Modulo 3: Configurazione automatica
├── modulo4-header.html         # Modulo 4: Header IPv6 vs IPv4
├── modulo5-sicurezza.html      # Modulo 5: Sicurezza e Transizione
├── modulo6-quiz.html           # Modulo 6: Quiz e Flashcard
├── .nojekyll                   # Disabilita Jekyll per GitHub Pages
└── README.md                   # Documentazione
```

## Argomenti Trattati

### Modulo 1 - Storia
- Nascita di IP (1974) e IPv4 (1981)
- Il mistero di IPv5 (ST-II Protocol)
- Crisi esaurimento indirizzi
- Soluzioni temporanee: CIDR, NAT
- RFC 2460 e nascita di IPv6

### Modulo 2 - Indirizzamento
- Formato 128-bit (340 undecilioni di indirizzi)
- Notazione esadecimale con i due punti
- Compressione con `::` (zero compression)
- Tipi: Unicast, Multicast, Anycast
- Prefissi e subnetting

### Modulo 3 - Configurazione
- SLAAC (Stateless Address Auto-Configuration)
- DHCPv6 (configurazione stateful)
- NDP (Neighbor Discovery Protocol)
- DAD (Duplicate Address Detection)
- Generazione EUI-64 da MAC address

### Modulo 4 - Header
- Confronto header IPv4 vs IPv6
- Campi: Version, Traffic Class, Flow Label
- Next Header ed Extension Headers
- Semplificazione rispetto a IPv4
- MTU e frammentazione

### Modulo 5 - Sicurezza
- IPsec integrato nativamente
- Fine del NAT, ritorno end-to-end
- Strategie di transizione:
  - Dual-stack
  - Tunneling (6to4, Teredo)
  - Translation (NAT64)

### Modulo 6 - Quiz
- 20 domande a scelta multipla
- Flashcard con effetto 3D flip
- Verifica dell'apprendimento

## Licenza

Materiale didattico per uso educativo.

## Autore

Realizzato per il corso di Sistemi e Reti.
