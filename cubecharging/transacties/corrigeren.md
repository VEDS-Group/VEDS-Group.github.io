---
layout: default
title: Transactie Corrigeren
sidebar: |
  <h3>Transactie Corrigeren</h3>
  <ul>
    <li><a href="#overzicht">Overzicht</a></li>
    <li><a href="#navigatie">Stap 1: Navigatie</a></li>
    <li><a href="#details-bekijken">Stap 2: Details Bekijken</a></li>
    <li><a href="#transactie-corrigeren">Stap 3: Transactie Corrigeren</a></li>
    <li><a href="#correctie-opslaan">Stap 4: Correctie Opslaan</a></li>
    <li><a href="#correctie-geschiedenis">Stap 5: Correctie Geschiedenis</a></li>
  </ul>
---

# Transactie Corrigeren

<div class="content-section" id="overzicht">
  <h2>Overzicht</h2>
  <p>Het Cube Backend systeem biedt de mogelijkheid om transacties te corrigeren wanneer er fouten zijn opgetreden tijdens het laden. Dit systeem houdt een volledige audit trail bij van alle correcties.</p>
</div>
    

<div class="step-section" id="navigatie">
  <h2>Stap 1: Navigatie naar Transactie</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Via Laadpalen</h4>
      <ol>
        <li><strong>Login:</strong> Log eerst in op het Cube Backend systeem</li>
        <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
        <li><strong>Laadpalen:</strong> Klik op "Laadpalen" in het hoofdmenu</li>
        <li><strong>Laadpaal Selecteren:</strong> Klik op de gewenste laadpaal</li>
        <li><strong>Sessies Tab:</strong> Klik op "Sessies" tab</li>
        <li><strong>Transactie Selecteren:</strong> Klik op Transaction ID om naar details te gaan</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Via Sessies</h4>
      <ol>
        <li><strong>Login:</strong> Log eerst in op het Cube Backend systeem</li>
        <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
        <li><strong>Sessies:</strong> Klik op "Sessies" in het hoofdmenu</li>
        <li><strong>Transactie Selecteren:</strong> Klik op Transaction ID om naar details te gaan</li>
      </ol>
    </div>
  </div>
</div>

<div class="step-section" id="details-bekijken">
  <h2>Stap 2: Transactie Details Bekijken</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Transactie Informatie</h4>
      <ul>
        <li><strong>Transaction ID:</strong> Unieke identificatie van de transactie</li>
        <li><strong>ChargeBox ID:</strong> ID van de laadpaal</li>
        <li><strong>Connector ID:</strong> ID van de connector</li>
        <li><strong>OCPP ID Tag:</strong> RFID tag van de gebruiker</li>
        <li><strong>Start Date/Time:</strong> Starttijd van de transactie</li>
        <li><strong>Start Value:</strong> Startwaarde van de meter</li>
        <li><strong>Stop Date/Time:</strong> Stoptijd van de transactie</li>
        <li><strong>Stop Value:</strong> Stopwaarde van de meter</li>
        <li><strong>Stop Reason:</strong> Reden voor stoppen</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Meter Values</h4>
      <ol>
        <li><strong>Meter Values Link:</strong> Klik op Transaction ID voor meter values</li>
        <li><strong>Gedetailleerde Data:</strong> Bekijk alle meter readings</li>
        <li><strong>Tijdstempels:</strong> Controleer alle tijdstempels</li>
        <li><strong>Waarden:</strong> Controleer alle meter waarden</li>
      </ol>
    </div>
  </div>
</div>

<div class="step-section" id="transactie-corrigeren">
  <h2>Stap 3: Transactie Corrigeren</h2>
  
  <h4>Correctie Interface</h4>
  <ol>
    <li><strong>Edit Button:</strong> Klik op "Corrigeren" knop (indien beschikbaar)</li>
    <li><strong>Correctie Modal:</strong> Correctie modal wordt geopend</li>
    <li><strong>Velden Bewerken:</strong> Bewerk de gewenste velden</li>
  </ol>
  
  <h4>Bewerkbare Velden</h4>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Start Transactie</h4>
      <ul>
        <li><strong>Tariff Code:</strong> Wijzig tariefcode</li>
        <li><strong>Start Timestamp:</strong> Wijzig starttijd</li>
        <li><strong>Verrekenen:</strong> Wijzig verrekening status</li>
        <li><strong>OCPI Code:</strong> Wijzig OCPI code</li>
        <li><strong>E-clearing:</strong> Wijzig e-clearing status</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Stop Transactie</h4>
      <ul>
        <li><strong>Stop Timestamp:</strong> Wijzig stoptijd</li>
        <li><strong>Stop Value:</strong> Wijzig stopwaarde</li>
      </ul>
    </div>
  </div>
  
  <h4>Correctie Reden</h4>
  <ol>
    <li><strong>Reden Invoeren:</strong> Voer reden voor correctie in</li>
    <li><strong>Verplicht:</strong> Reden is verplicht voor audit trail</li>
    <li><strong>Beschrijvend:</strong> Geef duidelijke beschrijving van de fout</li>
  </ol>
</div>

<div class="step-section" id="correctie-opslaan">
  <h2>Stap 4: Correctie Opslaan</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Validatie</h4>
      <ol>
        <li><strong>Controle:</strong> Controleer of alle wijzigingen correct zijn</li>
        <li><strong>Reden:</strong> Controleer of correctie reden is ingevuld</li>
        <li><strong>Impact:</strong> Overweeg impact van de correctie</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Opslaan</h4>
      <ol>
        <li><strong>Save Button:</strong> Klik op "Opslaan" knop</li>
        <li><strong>Bevestiging:</strong> Bevestig de correctie</li>
        <li><strong>Audit Trail:</strong> Correctie wordt opgeslagen in audit trail</li>
        <li><strong>Success:</strong> Succesbericht wordt getoond</li>
      </ol>
    </div>
  </div>
</div>

<div class="step-section" id="correctie-geschiedenis">
  <h2>Stap 5: Correctie Geschiedenis</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Geschiedenis Bekijken</h4>
      <ol>
        <li><strong>History Tab:</strong> Klik op "View history"</li>
        <li><strong>Alle Correcties:</strong> Bekijk alle eerdere correcties</li>
        <li><strong>Details:</strong> Bekijk details van elke correctie</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Geschiedenis Informatie</h4>
      <ul>
        <li><strong>Correctie Tijdstempel:</strong> Wanneer correctie is gemaakt</li>
        <li><strong>Gecorrigeerd Door:</strong> Welke gebruiker heeft gecorrigeerd</li>
        <li><strong>Correctie Reden:</strong> Reden voor de correctie</li>
        <li><strong>Originele Waarden:</strong> Originele waarden voor correctie</li>
        <li><strong>Nieuwe Waarden:</strong> Nieuwe waarden na correctie</li>
      </ul>
    </div>
  </div>
</div>