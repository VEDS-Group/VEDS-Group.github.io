---
layout: default
title: Laadpas Activeren
sidebar: |
  <h3>Laadpas Activeren</h3>
  <ul>
    <li><a href="#overzicht">Overzicht</a></li>
    <li><a href="#navigatie">Stap 1: Navigatie</a></li>
    <li><a href="#validatie">Stap 2: Laadpas Validatie</a></li>
    <li><a href="#bankrekening">Stap 3: Bankrekening & Machtiging</a></li>
    <li><a href="#handtekening">Stap 4: Handtekening</a></li>
    <li><a href="#activatie">Stap 5: Activatie Voltooien</a></li>
  </ul>
---

# Laadpas Activeren

<div class="nav-breadcrumb">
  <a href="../laadpas.html">← Back to Laadpas</a>
</div>

<div class="content-section" id="overzicht">
  <h2>Overzicht</h2>
  <p>Het Cube Backend systeem biedt een uitgebreide functionaliteit voor het activeren van laadpassen (charging cards). Dit proces omvat validatie van de laadpas, het koppelen van bankrekening en machtiging, het selecteren van een abonnement, en het vastleggen van een handtekening.</p>
  
  <div class="warning-section">
    <p><strong>Let op: een gebruiker kan dit alleen zelf doen!</strong></p>
  </div>
</div>

<div class="step-section" id="navigatie">
  <h2>Stap 1: Navigatie naar Laadpas Activeren</h2>
  
  <h4>Via het Hoofdmenu</h4>
  <ol>
    <li><strong>Login:</strong> Log eerst in op het Cube Backend systeem</li>
    <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
    <li><strong>Laadpassen:</strong> Klik op "Laadpassen" in het hoofdmenu (links in de navigatie)</li>
    <li><strong>Activeren:</strong> Klik op "Laadpas activeren" in het laadpassen submenu</li>
    <li><strong>Activeren Pagina:</strong> Je komt op de Laadpas Activeren pagina</li>
  </ol>
</div>

<div class="step-section" id="validatie">
  <h2>Stap 2: Laadpas Validatie</h2>
  
  <h4>Laadpas ID Invoeren</h4>
  <ul>
    <li><strong>Card Visual ID:</strong> Voer het visuele ID van de laadpas in</li>
    <li><strong>Formaat:</strong> Moet voldoen aan het formaat: NL-CUB+extra of NL-SHU-CU+extra</li>
    <li><strong>Laadpas controleren:</strong> Klik op "Laadpas controleren" om de laadpas te valideren</li>
  </ul>

  <h4>Validatie Resultaten</h4>
  <div class="info-grid">
    <div class="info-card">
      <h4 class="status-success">✅ Geldig</h4>
      <p>Laadpas kan geactiveerd worden</p>
    </div>
    <div class="info-card">
      <h4 class="status-error">❌ Niet gevonden</h4>
      <p>Laadpas bestaat niet in het systeem (mogelijk lease maatschappij)</p>
    </div>
    <div class="info-card">
      <h4 class="status-error">❌ Al actief</h4>
      <p>Laadpas is al geactiveerd</p>
    </div>
    <div class="info-card">
      <h4 class="status-error">❌ Al toegewezen</h4>
      <p>Laadpas is al toegewezen aan een andere gebruiker</p>
    </div>
    <div class="info-card">
      <h4 class="status-error">❌ Verkeerde status</h4>
      <p>Laadpas heeft niet de juiste status voor activatie</p>
    </div>
  </div>
</div>

<div class="step-section" id="bankrekening">
  <h2>Stap 3: Bankrekening en Machtiging</h2>
  
  <h4>Bankrekening Selecteren</h4>
  <ul>
    <li><strong>Bankrekening:</strong> Selecteer een bestaande bankrekening uit de dropdown</li>
    <li><strong>Nieuwe Bankrekening:</strong> Klik op "Nieuwe bankrekening toevoegen" om een nieuwe toe te voegen</li>
  </ul>

  <h4>Nieuwe Bankrekening Toevoegen</h4>
  <div class="info-grid">
    <div class="info-card">
      <h4>IBAN</h4>
      <p>Voer het IBAN nummer in (15-34 karakters)</p>
    </div>
    <div class="info-card">
      <h4>Banknaam</h4>
      <p>Selecteer de bank uit de dropdown</p>
    </div>
    <div class="info-card">
      <h4>Rekeninghouder</h4>
      <p>Voer de naam van de rekeninghouder in</p>
    </div>
  </div>

  <h4>Machtiging Selecteren</h4>
  <ul>
    <li><strong>Machtiging:</strong> Selecteer een bestaande machtiging uit de dropdown</li>
    <li><strong>Nieuwe Machtiging:</strong> Klik op "Add New Mandate" om een nieuwe toe te voegen</li>
  </ul>

  <h4>Nieuwe Machtiging Toevoegen</h4>
  <div class="info-grid">
    <div class="info-card">
      <h4>IBAN</h4>
      <p>Selecteer de bankrekening voor de machtiging</p>
    </div>
    <div class="info-card">
      <h4>Startdatum</h4>
      <p>Voer de startdatum van de machtiging in</p>
    </div>
  </div>

  <h4>Abonnement Selecteren</h4>
  <ul>
    <li><strong>Abonnement:</strong> Selecteer een abonnement uit de dropdown</li>
    <li><strong>Beschrijving:</strong> Elk abonnement toont naam en beschrijving</li>
    <li><strong>Prijzen:</strong> Abonnementsprijzen worden getoond</li>
  </ul>
</div>

<div class="step-section" id="handtekening">
  <h2>Stap 4: Handtekening Vastleggen</h2>
  
  <h4>Locatie en Datum</h4>
  <div class="info-grid">
    <div class="info-card">
      <h4>Plaats</h4>
      <p>Voer de plaats in waar de activatie plaatsvindt</p>
    </div>
    <div class="info-card">
      <h4>Huidige Locatie</h4>
      <p>Klik op "Get Current Location" om automatisch de locatie op te halen</p>
    </div>
    <div class="info-card">
      <h4>Datum</h4>
      <p>Selecteer de datum van activatie (standaard: vandaag)</p>
    </div>
  </div>

  <h4>Handtekening Tekenen</h4>
  <ul>
    <li><strong>Canvas:</strong> Gebruik de muis of touch om te tekenen op het canvas</li>
    <li><strong>Tekenen:</strong> Houd de muisknop ingedrukt en beweeg om te tekenen</li>
    <li><strong>Wissen:</strong> Klik op "Clear Signature" om de handtekening te wissen</li>
    <li><strong>Voltooien:</strong> Klik op "Complete Signature" om de handtekening te voltooien</li>
  </ul>

  <h4>Handtekening Vereisten</h4>
  <div class="warning-section">
    <ul>
      <li><strong>Minimaal:</strong> Er moet daadwerkelijk getekend zijn (niet alleen een punt)</li>
      <li><strong>Controle:</strong> Het systeem controleert automatisch of er een handtekening is</li>
      <li><strong>Opslaan:</strong> Handtekening wordt opgeslagen als afbeelding</li>
    </ul>
  </div>
</div>

<div class="step-section" id="activatie">
  <h2>Stap 5: Activatie Voltooien</h2>
  
  <h4>Controle Voordat Activatie</h4>
  <p>Het systeem controleert automatisch of alle vereiste velden zijn ingevuld:</p>
  <div class="info-grid">
    <div class="info-card">
      <h4 class="status-success">✅ Laadpas ID</h4>
      <p>Ingevuld en gevalideerd</p>
    </div>
    <div class="info-card">
      <h4 class="status-success">✅ Bankrekening</h4>
      <p>Geselecteerd</p>
    </div>
    <div class="info-card">
      <h4 class="status-success">✅ Machtiging</h4>
      <p>Geselecteerd</p>
    </div>
    <div class="info-card">
      <h4 class="status-success">✅ Abonnement</h4>
      <p>Geselecteerd</p>
    </div>
    <div class="info-card">
      <h4 class="status-success">✅ Plaats</h4>
      <p>Ingevuld</p>
    </div>
    <div class="info-card">
      <h4 class="status-success">✅ Datum</h4>
      <p>Ingevuld</p>
    </div>
    <div class="info-card">
      <h4 class="status-success">✅ Handtekening</h4>
      <p>Getekend</p>
    </div>
  </div>

  <h4>Activatie Proces</h4>
  <ol>
    <li><strong>Activate Button:</strong> Klik op "Activate" om de activatie te starten</li>
    <li><strong>Verwerking:</strong> Het systeem verwerkt alle gegevens</li>
    <li><strong>Success:</strong> Bij succes verschijnt een groene bevestigingsmelding</li>
  </ol>

  <h4>Na Succesvolle Activatie</h4>
  <div class="content-section">
    <ul>
      <li><strong>Bevestiging:</strong> Groene melding "Activation successful"</li>
      <li><strong>Reset:</strong> Alle velden worden leeggemaakt</li>
      <li><strong>Nieuwe Activatie:</strong> Je kunt direct een nieuwe laadpas activeren</li>
    </ul>
  </div>
</div>
