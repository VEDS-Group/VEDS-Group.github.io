---
layout: default
title: External Helpdesk Pagina
sidebar: |
  <h3>External Helpdesk</h3>
  <ul>
    <li><a href="#overzicht">Overzicht</a></li>
    <li><a href="#video-demo">Video Demo</a></li>
    <li><a href="#navigatie">Stap 1: Navigatie</a></li>
    <li><a href="#overzicht-pagina">Stap 2: Overzicht Pagina</a></li>
    <li><a href="#summary-cards">Stap 3: Summary Cards</a></li>
    <li><a href="#laadpaal-tab">Stap 4: Laadpaal Problemen Tab</a></li>
    <li><a href="#sessie-tab">Stap 5: Sessie Problemen Tab</a></li>
    <li><a href="#sortering">Stap 6: Sortering & Filtering</a></li>
    <li><a href="#data-vernieuwen">Stap 7: Data Vernieuwen</a></li>
    <li><a href="#navigatie-details">Stap 8: Navigatie naar Details</a></li>
    <li><a href="#probleem-types">Probleem Types</a></li>
    <li><a href="#cache-systeem">Cache Systeem</a></li>
  </ul>
---

# External Helpdesk Pagina

<div class="content-section" id="overzicht">
  <h2>Overzicht</h2>
  <p>De External Helpdesk pagina is een krachtige tool voor het monitoren en beheren van systeemproblemen in het CubeCharging platform. Het biedt een uitgebreid overzicht van laadpaal problemen en sessie issues, met geavanceerde filtering, sortering en groepering mogelijkheden.</p>
  
  <div class="info-card">
    <h4>Belangrijke Kenmerken</h4>
    <ul>
      <li><strong>Real-time Monitoring:</strong> Monitort laadpalen en sessies in real-time</li>
      <li><strong>Probleem Detectie:</strong> Automatische detectie van verschillende probleem types</li>
      <li><strong>Geavanceerde Sortering:</strong> Sorteer op meerdere kolommen</li>
      <li><strong>Groepering:</strong> Groepeert gerelateerde sessies samen</li>
      <li><strong>Cache Systeem:</strong> Efficiënte data caching voor betere performance</li>
      <li><strong>Directe Navigatie:</strong> Klik op items om direct naar details te gaan</li>
    </ul>
  </div>
</div>

<div class="content-section" id="video-demo">
  <h2>Video Demo</h2>
  
  <div class="info-card">
    <h4>External Helpdesk Video</h4>
    <p>Bekijk de onderstaande video voor een visuele demonstratie van de External Helpdesk functionaliteit:</p>
    <video width="100%" controls style="max-width: 800px; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <source src="/videos/External_Helpdesk.mp4" type="video/mp4">
      Je browser ondersteunt geen video afspelen. <a href="/videos/External_Helpdesk.mp4">Download de video</a> om deze te bekijken.
    </video>
  </div>
</div>

<div class="step-section" id="navigatie">
  <h2>Stap 1: Navigatie naar Helpdesk</h2>
  
  <div class="info-card">
    <h4>Via het Hoofdmenu</h4>
    <ol>
      <li><strong>Login:</strong> Log in op het Cube Backend systeem</li>
      <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
      <li><strong>Helpdesk:</strong> Klik op "Helpdesk" in het hoofdmenu (links in de navigatie)</li>
      <li><strong>Overzicht:</strong> Je komt op de Helpdesk overzichtspagina</li>
    </ol>
  </div>
  
  <div class="info-card">
    <h4>Directe Toegang</h4>
    <ul>
      <li><strong>URL:</strong> Direct toegankelijk via <code>/dashboard/helpdesk</code></li>
      <li><strong>Bookmark:</strong> Pagina kan worden gebookmarkt voor snelle toegang</li>
      <li><strong>Permissies:</strong> Vereist juiste gebruikerspermissies</li>
    </ul>
  </div>
</div>

<div class="step-section" id="overzicht-pagina">
  <h2>Stap 2: Overzicht Pagina</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Pagina Structuur</h4>
      <ul>
        <li><strong>Header:</strong> Titel, subtitel en refresh knop</li>
        <li><strong>Summary Cards:</strong> Drie overzichtskaarten bovenaan</li>
        <li><strong>Tabs:</strong> Twee tabs voor laadpaal en sessie problemen</li>
        <li><strong>Tabellen:</strong> Uitgebreide tabellen met probleem details</li>
        <li><strong>Footer:</strong> Cache informatie en laatste update tijd</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Error Handling</h4>
      <ul>
        <li><strong>Error Banner:</strong> Rode banner bij fouten</li>
        <li><strong>Retry Button:</strong> Mogelijkheid om opnieuw te proberen</li>
        <li><strong>Fallback:</strong> Probeert individuele endpoints bij fout</li>
        <li><strong>User Feedback:</strong> Duidelijke foutmeldingen</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="summary-cards">
  <h2>Stap 3: Summary Cards</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>🔴 Laadpaal Problemen</h4>
      <ul>
        <li><strong>Aantal:</strong> Totaal aantal problematische laadpalen</li>
        <li><strong>Types:</strong> Offline, gearchiveerd maar actief, etc.</li>
        <li><strong>Kleur:</strong> Rode badge voor visuele aandacht</li>
        <li><strong>Klik:</strong> Klik op tab om details te bekijken</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>🟠 Sessie Problemen</h4>
      <ul>
        <li><strong>Aantal:</strong> Totaal aantal problematische sessies</li>
        <li><strong>Gegroepeerd:</strong> Toont aantal rijen (gegroepeerde sessies)</li>
        <li><strong>Kleur:</strong> Oranje badge</li>
        <li><strong>Details:</strong> Klik op tab voor volledige lijst</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>🟢 Totaal Problemen</h4>
      <ul>
        <li><strong>Som:</strong> Totaal van laadpaal + sessie problemen</li>
        <li><strong>Overzicht:</strong> Snelle indicatie van systeem gezondheid</li>
        <li><strong>Kleur:</strong> Groene badge</li>
        <li><strong>Monitoring:</strong> Helpt bij prioritering</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="laadpaal-tab">
  <h2>Stap 4: Laadpaal Problemen Tab</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Tabel Kolommen</h4>
      <ul>
        <li><strong>Laadpaal ID:</strong> Unieke identificatie (monospace font)</li>
        <li><strong>Locatie:</strong> Adres en stad gecombineerd</li>
        <li><strong>Vendor:</strong> Fabrikant van de laadpaal</li>
        <li><strong>Model:</strong> Model naam van de laadpaal</li>
        <li><strong>Laatste Heartbeat:</strong> Timestamp van laatste communicatie</li>
        <li><strong>Uren Offline:</strong> Aantal uren dat laadpaal offline is</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Status Badges</h4>
      <ul>
        <li><strong>Offline (verrekenen):</strong> Rode badge met aantal uren</li>
        <li><strong>Offline (niet verrekenen):</strong> Grijze badge</li>
        <li><strong>Actief (gearchiveerd):</strong> Oranje badge</li>
        <li><strong>Klikbaar:</strong> Klik op rij om naar laadpaal details te gaan</li>
      </ul>
    </div>
  </div>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Sortering</h4>
      <ul>
        <li><strong>Klik op Header:</strong> Sorteer op die kolom</li>
        <li><strong>Pijl Indicatoren:</strong> ↑ voor oplopend, ↓ voor aflopend</li>
        <li><strong>Meerdere Klikken:</strong> Wissel tussen asc/desc</li>
        <li><strong>Visuele Feedback:</strong> Gesorteerde kolom wordt gemarkeerd</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Navigatie</h4>
      <ul>
        <li><strong>Klik op Rij:</strong> Opent laadpaal details in nieuw tabblad</li>
        <li><strong>URL Format:</strong> <code>/charging-stations/{chargeBoxId}</code></li>
        <li><strong>Hover Effect:</strong> Visuele feedback bij hover</li>
        <li><strong>Nieuwe Tab:</strong> Details openen in nieuw tabblad</li>
      </ul>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Probleem Types</h4>
    <ul>
      <li><strong>OFFLINE:</strong> Laadpaal communiceert niet meer</li>
      <li><strong>ARCHIVED_BUT_ACTIVE:</strong> Gearchiveerd maar nog actief</li>
      <li><strong>OFFLINE_NON_VERREKENEN:</strong> Offline maar niet verrekenen</li>
    </ul>
  </div>
</div>

<div class="step-section" id="sessie-tab">
  <h2>Stap 5: Sessie Problemen Tab</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Tabel Kolommen</h4>
      <ul>
        <li><strong>Transactie ID:</strong> Unieke sessie identificatie</li>
        <li><strong>Laadpaal ID:</strong> Waar sessie plaatsvond</li>
        <li><strong>Start Tijd:</strong> Wanneer sessie begon</li>
        <li><strong>Stop Tijd:</strong> Wanneer sessie eindigde</li>
        <li><strong>Energie Verbruikt:</strong> Totaal in Wh/kWh</li>
        <li><strong>Probleem Type:</strong> Type gedetecteerd probleem</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Probleem Type Badges</h4>
      <ul>
        <li><strong>HIGH_STOP_VALUE:</strong> Gele badge - onrealistisch hoge energie</li>
        <li><strong>LONG_RUNNING_SESSION:</strong> Oranje badge - te lange sessie</li>
        <li><strong>RAPID_CONSECUTIVE_SESSIONS:</strong> Rode badge - snel opeenvolgend</li>
        <li><strong>INVALID_TIMESTAMP:</strong> Rode badge - ongeldige tijdstempel</li>
      </ul>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Groepering van Rapid Sessions</h4>
    <p>Meerdere rapid consecutive sessions worden automatisch gegroepeerd:</p>
    <ul>
      <li><strong>Groep Indicator:</strong> Folder icoon (📁/📂) toont groep status</li>
      <li><strong>Groep Rij:</strong> Toont aantal sessies in groep</li>
      <li><strong>Uitklappen:</strong> Klik op groep rij om uit te klappen</li>
      <li><strong>Individuele Sessies:</strong> Uitgeklapte sessies tonen details</li>
      <li><strong>Inspringing:</strong> Visuele hiërarchie met indentatie</li>
      <li><strong>Groep Badge:</strong> Toont probleem type + aantal sessies</li>
    </ul>
  </div>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Groep Functionaliteit</h4>
      <ul>
        <li><strong>Automatisch:</strong> Groepering gebeurt automatisch</li>
        <li><strong>Cluster Key:</strong> Groepeert op chargeBoxId + beschrijving</li>
        <li><strong>Minimaal 2:</strong> Alleen groepen met 2+ sessies</li>
        <li><strong>State Management:</strong> Onthoudt welke groepen uitgeklapt zijn</li>
        <li><strong>Toggle:</strong> Klik om uit/in te klappen</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Individuele Sessies</h4>
      <ul>
        <li><strong>Klikbaar:</strong> Klik op individuele sessie voor details</li>
        <li><strong>URL Format:</strong> <code>/sessions/{transactionPk}/meter-values</code></li>
        <li><strong>Visuele Styling:</strong> Verschillende styling voor groep vs individueel</li>
        <li><strong>Badge:</strong> "Individuele sessie" badge voor uitgeklapte items</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="sortering">
  <h2>Stap 6: Sortering & Filtering</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Laadpaal Sortering</h4>
      <ul>
        <li><strong>Beschikbare Velden:</strong> chargeBoxId, location, vendor, model, lastHeartbeat, hoursOffline</li>
        <li><strong>Datum Sortering:</strong> Speciale behandeling voor timestamps</li>
        <li><strong>Numerieke Sortering:</strong> Correcte sortering voor uren offline</li>
        <li><strong>String Sortering:</strong> Case-insensitive tekst sortering</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Sessie Sortering</h4>
      <ul>
        <li><strong>Beschikbare Velden:</strong> transactionPk, chargeBoxId, startTimestamp, stopTimestamp, energyConsumed, issueType</li>
        <li><strong>Groep Sortering:</strong> Groepen worden meegenomen in sortering</li>
        <li><strong>Energie Sortering:</strong> Numerieke sortering voor energie waarden</li>
        <li><strong>Datum Sortering:</strong> Timestamp conversie voor correcte sortering</li>
      </ul>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Sortering Gedrag</h4>
    <ul>
      <li><strong>Eerste Klik:</strong> Oplopend sorteren</li>
      <li><strong>Tweede Klik:</strong> Aflopend sorteren</li>
      <li><strong>Derde Klik:</strong> Terug naar originele volgorde</li>
      <li><strong>Visuele Indicatie:</strong> Pijl toont sorteerrichting</li>
      <li><strong>Highlight:</strong> Gesorteerde kolom krijgt achtergrondkleur</li>
    </ul>
  </div>
</div>

<div class="step-section" id="data-vernieuwen">
  <h2>Stap 7: Data Vernieuwen</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Handmatig Vernieuwen</h4>
      <ol>
        <li><strong>Refresh Button:</strong> Klik op "Vernieuwen" knop rechtsboven</li>
        <li><strong>Loading State:</strong> Spinner en "Loading..." tekst</li>
        <li><strong>API Call:</strong> Haalt nieuwste data op van backend</li>
        <li><strong>Update:</strong> Pagina wordt bijgewerkt met nieuwe data</li>
        <li><strong>Cache Update:</strong> Cache timestamp wordt bijgewerkt</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Automatische Updates</h4>
      <ul>
        <li><strong>Bij Mount:</strong> Data wordt automatisch geladen bij pagina openen</li>
        <li><strong>Cache Systeem:</strong> Backend cached data voor performance</li>
        <li><strong>Cache Refresh:</strong> Backend ververst cache periodiek</li>
        <li><strong>Real-time Indicatie:</strong> Cache leeftijd wordt getoond</li>
      </ul>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Fallback Mechanisme</h4>
    <ul>
      <li><strong>Primaire Endpoint:</strong> Probeert eerst gecombineerde endpoint</li>
      <li><strong>Individuele Endpoints:</strong> Bij fout probeert individuele endpoints</li>
      <li><strong>Partial Success:</strong> Toont beschikbare data zelfs bij gedeeltelijke fout</li>
      <li><strong>Error Display:</strong> Toont duidelijke foutmeldingen</li>
    </ul>
  </div>
</div>

<div class="step-section" id="navigatie-details">
  <h2>Stap 8: Navigatie naar Details</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Laadpaal Details</h4>
      <ol>
        <li><strong>Klik op Rij:</strong> Klik op een laadpaal rij in de tabel</li>
        <li><strong>Nieuw Tabblad:</strong> Laadpaal details openen in nieuw tabblad</li>
        <li><strong>URL:</strong> <code>/charging-stations/{chargeBoxId}</code></li>
        <li><strong>Details:</strong> Volledige laadpaal informatie en geschiedenis</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Sessie Details</h4>
      <ol>
        <li><strong>Klik op Rij:</strong> Klik op een sessie rij (groep of individueel)</li>
        <li><strong>Groep Uitklappen:</strong> Groepen moeten eerst uitgeklapt worden</li>
        <li><strong>Nieuw Tabblad:</strong> Sessie details openen in nieuw tabblad</li>
        <li><strong>URL:</strong> <code>/sessions/{transactionPk}/meter-values</code></li>
        <li><strong>Details:</strong> Volledige sessie informatie en meter values</li>
      </ol>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Hover Effecten</h4>
    <ul>
      <li><strong>Visuele Feedback:</strong> Rijen krijgen hover effect</li>
      <li><strong>Transform:</strong> Subtiele verschuiving naar rechts</li>
      <li><strong>Shadow:</strong> Box shadow voor diepte</li>
      <li><strong>Cursor:</strong> Pointer cursor toont klikbaarheid</li>
      <li><strong>Badge Highlight:</strong> Badges worden groter bij hover</li>
    </ul>
  </div>
</div>

<div class="content-section" id="probleem-types">
  <h2>Probleem Types</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Laadpaal Problemen</h4>
      <ul>
        <li><strong>OFFLINE:</strong> Laadpaal communiceert niet meer met systeem
          <ul>
            <li>Geen heartbeat ontvangen</li>
            <li>Kan verrekenen of niet verrekenen</li>
            <li>Toont aantal uren offline</li>
          </ul>
        </li>
        <li><strong>ARCHIVED_BUT_ACTIVE:</strong> Laadpaal is gearchiveerd maar nog actief
          <ul>
            <li>Status inconsistentie</li>
            <li>Oranje badge</li>
            <li>Vereist handmatige actie</li>
          </ul>
        </li>
        <li><strong>OFFLINE_NON_VERREKENEN:</strong> Offline maar niet verrekenen
          <ul>
            <li>Grijze badge</li>
            <li>Minder urgent</li>
          </ul>
        </li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Sessie Problemen</h4>
      <ul>
        <li><strong>HIGH_STOP_VALUE:</strong> Onrealistisch hoge energie consumptie
          <ul>
            <li>Gele badge</li>
            <li>Mogelijke meter fout</li>
            <li>Vereist verificatie</li>
          </ul>
        </li>
        <li><strong>LONG_RUNNING_SESSION:</strong> Sessie duurt abnormaal lang
          <ul>
            <li>Oranje badge</li>
            <li>Mogelijk niet correct gestopt</li>
            <li>Vereist handmatige stop</li>
          </ul>
        </li>
        <li><strong>RAPID_CONSECUTIVE_SESSIONS:</strong> Meerdere snel opeenvolgende sessies
          <ul>
            <li>Rode badge</li>
            <li>Wordt gegroepeerd</li>
            <li>Mogelijk technisch probleem</li>
          </ul>
        </li>
        <li><strong>INVALID_TIMESTAMP:</strong> Ongeldige tijdstempels
          <ul>
            <li>Rode badge</li>
            <li>Data inconsistentie</li>
            <li>Vereist correctie</li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</div>

<div class="content-section" id="cache-systeem">
  <h2>Cache Systeem</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Cache Informatie</h4>
      <ul>
        <li><strong>Laatste Update:</strong> Timestamp van laatste cache update</li>
        <li><strong>Cache Leeftijd:</strong> Hoe lang geleden data is ververst</li>
        <li><strong>Status Indicatoren:</strong> Kleurgecodeerde status badges</li>
        <li><strong>Formaat:</strong> Nederlandse datum/tijd notatie</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Cache Status</h4>
      <ul>
        <li><strong>Groen (Fresh):</strong> Data ≤5 minuten oud
          <ul>
            <li>Achtergrond: lichtgroen</li>
            <li>Tekst: donkergroen</li>
            <li>Status: "zojuist vernieuwd" of "X minuten geleden"</li>
          </ul>
        </li>
        <li><strong>Geel (Stale):</strong> Data 6-15 minuten oud
          <ul>
            <li>Achtergrond: lichtgeel</li>
            <li>Tekst: donkergeel</li>
            <li>Status: "X minuten geleden"</li>
          </ul>
        </li>
        <li><strong>Rood (Old):</strong> Data >15 minuten oud
          <ul>
            <li>Achtergrond: lichtrood</li>
            <li>Tekst: donkerrood</li>
            <li>Status: "X uur geleden"</li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Cache Voordelen</h4>
    <ul>
      <li><strong>Performance:</strong> Snellere laadtijden</li>
      <li><strong>Backend Load:</strong> Minder belasting op backend</li>
      <li><strong>Consistentie:</strong> Consistente data weergave</li>
      <li><strong>Transparantie:</strong> Gebruikers zien cache leeftijd</li>
    </ul>
  </div>
</div>

<div class="content-section">
  <h2>Technische Details</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Component Structuur</h4>
      <ul>
        <li><strong>Vue 3 Composition API:</strong> Moderne Vue.js implementatie</li>
        <li><strong>TypeScript:</strong> Volledige type safety</li>
        <li><strong>Reactive State:</strong> Reactieve data management</li>
        <li><strong>Computed Properties:</strong> Geavanceerde computed voor groepering</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>API Endpoints</h4>
      <ul>
        <li><strong>/api/helpdesk/data:</strong> Gecombineerde endpoint voor alle data</li>
        <li><strong>/api/helpdesk/charge-points:</strong> Alleen laadpaal problemen</li>
        <li><strong>/api/helpdesk/sessions:</strong> Alleen sessie problemen</li>
        <li><strong>Response Format:</strong> JSON met issues arrays en lastUpdated timestamp</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Data Structure</h4>
      <ul>
        <li><strong>ChargePointIssue:</strong> chargeBoxId, location, vendor, model, timestamps, issueType</li>
        <li><strong>SessionIssue:</strong> transactionPk, chargeBoxId, timestamps, energyConsumed, issueType</li>
        <li><strong>SessionIssueGroup:</strong> Groep object met sessions array</li>
        <li><strong>Type Safety:</strong> Volledige TypeScript types</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Features</h4>
      <ul>
        <li><strong>Tab Navigation:</strong> Smooth tab switching</li>
        <li><strong>Sorting:</strong> Multi-column sorting met state management</li>
        <li><strong>Grouping:</strong> Intelligente groepering van rapid sessions</li>
        <li><strong>Expansion:</strong> Expandable groups met state persistence</li>
        <li><strong>Error Handling:</strong> Uitgebreide error handling en fallbacks</li>
        <li><strong>Loading States:</strong> Loading indicators tijdens API calls</li>
        <li><strong>Responsive Design:</strong> Werkt op alle schermformaten</li>
      </ul>
    </div>
  </div>
</div>

<div class="content-section">
  <h2>Best Practices</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Voor Gebruikers</h4>
      <ul>
        <li><strong>Regelmatig Checken:</strong> Controleer helpdesk regelmatig</li>
        <li><strong>Cache Bewustzijn:</strong> Let op cache leeftijd</li>
        <li><strong>Refresh:</strong> Vernieuw data bij twijfel</li>
        <li><strong>Prioritering:</strong> Focus op rode badges eerst</li>
        <li><strong>Details:</strong> Klik door naar details voor volledige context</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Voor Beheerders</h4>
      <ul>
        <li><strong>Monitoring:</strong> Monitor helpdesk als dashboard</li>
        <li><strong>Proactief:</strong> Los problemen proactief op</li>
        <li><strong>Documentatie:</strong> Documenteer oplossingen</li>
        <li><strong>Escalatie:</strong> Escaleer complexe problemen</li>
        <li><strong>Feedback:</strong> Geef feedback over systeem verbeteringen</li>
      </ul>
    </div>
  </div>
</div>

