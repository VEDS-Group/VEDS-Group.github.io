---
layout: default
title: Helpdesk Pagina
sidebar: |
  <h3>Helpdesk Pagina</h3>
  <ul>
    <li><a href="#overzicht">Overzicht</a></li>
    <li><a href="#navigatie">Stap 1: Navigatie</a></li>
    <li><a href="#helpdesk-overzicht">Stap 2: Helpdesk Overzicht</a></li>
    <li><a href="#laadpaal-problemen">Stap 3: Laadpaal Problemen Tab</a></li>
    <li><a href="#sessie-problemen">Stap 4: Sessie Problemen Tab</a></li>
    <li><a href="#data-vernieuwen">Stap 5: Data Vernieuwen</a></li>
    <li><a href="#probleem-types">Stap 6: Probleem Types Begrijpen</a></li>
  </ul>
---

# Helpdesk Pagina

<div class="content-section" id="overzicht">
  <h2>Overzicht</h2>
  <p>De Helpdesk pagina is een centrale hub voor het monitoren en beheren van systeemproblemen. Het biedt een overzicht van laadpaal problemen en sessie issues, met uitgebreide filtering en sortering mogelijkheden.</p>
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
</div>

<div class="step-section" id="helpdesk-overzicht">
  <h2>Stap 2: Helpdesk Overzicht</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Summary Cards</h4>
      <p>De pagina toont drie overzichtskaarten:</p>
      <ul>
        <li><strong>Laadpaal Problemen:</strong> Aantal offline of problematische laadpalen</li>
        <li><strong>Sessie Problemen:</strong> Aantal problematische laadsessies</li>
        <li><strong>Totaal Problemen:</strong> Totaal aantal problemen in het systeem</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Cache Informatie</h4>
      <ul>
        <li><strong>Laatste Update:</strong> Toont wanneer de data voor het laatst is ververst</li>
        <li><strong>Cache Status:</strong>
          <ul>
            <li><strong>Groen:</strong> Data is vers (≤5 minuten)</li>
            <li><strong>Geel:</strong> Data is verouderd (6-15 minuten)</li>
            <li><strong>Rood:</strong> Data is oud (>15 minuten)</li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="laadpaal-problemen">
  <h2>Stap 3: Laadpaal Problemen Tab</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Overzicht</h4>
      <p>Deze tab toont alle laadpalen met problemen:</p>
      <ul>
        <li><strong>Offline Laadpalen:</strong> Laadpalen die niet meer communiceren</li>
        <li><strong>Gearchiveerde maar Actieve:</strong> Laadpalen die gearchiveerd zijn maar nog actief zijn</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Tabel Kolommen</h4>
      <ul>
        <li><strong>Laadpaal ID:</strong> Unieke identificatie van de laadpaal</li>
        <li><strong>Locatie:</strong> Adres en stad van de laadpaal</li>
        <li><strong>Vendor:</strong> Fabrikant van de laadpaal</li>
        <li><strong>Model:</strong> Model van de laadpaal</li>
        <li><strong>Laatste Heartbeat:</strong> Wanneer de laadpaal voor het laatst communiceerde</li>
        <li><strong>Uren Offline:</strong> Hoe lang de laadpaal offline is</li>
      </ul>
    </div>
  </div>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Sortering</h4>
      <ul>
        <li><strong>Klik op kolomheader:</strong> Sorteer op die kolom</li>
        <li><strong>Pijl omhoog/omlaag:</strong> Toont sorteerrichting</li>
        <li><strong>Meerdere klikken:</strong> Wissel tussen oplopend/aflopend</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Status Badges</h4>
      <ul>
        <li><strong>Offline Badge:</strong> Rode badge met aantal uren offline</li>
        <li><strong>Actief (gearchiveerd):</strong> Oranje badge voor gearchiveerde maar actieve laadpalen</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="sessie-problemen">
  <h2>Stap 4: Sessie Problemen Tab</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Overzicht</h4>
      <p>Deze tab toont alle problematische laadsessies:</p>
      <ul>
        <li><strong>Hoge Stop Waarde:</strong> Sessies met onrealistisch hoge energie consumptie</li>
        <li><strong>Lange Sessies:</strong> Sessies die te lang duren</li>
        <li><strong>Rapid Consecutive Sessions:</strong> Meerdere snel opeenvolgende sessies</li>
        <li><strong>Ongeldige Timestamps:</strong> Sessies met ongeldige tijdstempels</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Tabel Kolommen</h4>
      <ul>
        <li><strong>Transactie ID:</strong> Unieke identificatie van de sessie</li>
        <li><strong>Laadpaal ID:</strong> ID van de laadpaal waar de sessie plaatsvond</li>
        <li><strong>Start Tijd:</strong> Wanneer de sessie begon</li>
        <li><strong>Stop Tijd:</strong> Wanneer de sessie eindigde</li>
        <li><strong>Energie Verbruikt:</strong> Totaal energie verbruik in Wh/kWh</li>
        <li><strong>Probleem Type:</strong> Type probleem dat is gedetecteerd</li>
      </ul>
    </div>
  </div>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Groepering van Rapid Sessions</h4>
      <ul>
        <li><strong>Groep Indicator:</strong> Meerdere rapid sessions worden gegroepeerd</li>
        <li><strong>Uitklappen:</strong> Klik op een groep om individuele sessies te bekijken</li>
        <li><strong>Groep Badge:</strong> Toont aantal sessies in de groep</li>
        <li><strong>Individuele Sessies:</strong> Uitgeklapte sessies tonen details</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Sortering</h4>
      <ul>
        <li><strong>Klik op kolomheader:</strong> Sorteer op die kolom</li>
        <li><strong>Groepen vs Individueel:</strong> Groepen en individuele sessies worden samen gesorteerd</li>
        <li><strong>Datum Sortering:</strong> Speciale behandeling voor tijdstempel velden</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="data-vernieuwen">
  <h2>Stap 5: Data Vernieuwen</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Handmatig Vernieuwen</h4>
      <ol>
        <li><strong>Refresh Button:</strong> Klik op de "Vernieuwen" knop rechtsboven</li>
        <li><strong>Loading State:</strong> Het systeem toont een loading spinner</li>
        <li><strong>Nieuwe Data:</strong> De pagina wordt bijgewerkt met de nieuwste data</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Automatische Updates</h4>
      <ul>
        <li><strong>Cache Systeem:</strong> Data wordt gecached voor betere performance</li>
        <li><strong>Cache Duur:</strong> Cache wordt regelmatig ververst door het systeem</li>
        <li><strong>Real-time Indicatie:</strong> Cache leeftijd wordt getoond</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="probleem-types">
  <h2>Stap 6: Probleem Types Begrijpen</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Laadpaal Problemen</h4>
      <ul>
        <li><strong>Offline:</strong> Laadpaal communiceert niet meer met het systeem</li>
        <li><strong>Gearchiveerd maar Actief:</strong> Laadpaal is gearchiveerd maar nog steeds actief</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Sessie Problemen</h4>
      <ul>
        <li><strong>Hoge Stop Waarde:</strong> Onrealistisch hoge energie consumptie</li>
        <li><strong>Lange Sessies:</strong> Sessies die abnormaal lang duren</li>
        <li><strong>Rapid Sessions:</strong> Meerdere snel opeenvolgende sessies</li>
        <li><strong>Ongeldige Timestamps:</strong> Onmogelijke tijdstempels</li>
      </ul>
    </div>
  </div>
</div>
