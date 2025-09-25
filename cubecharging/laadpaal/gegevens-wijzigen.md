---
layout: default
title: Laadpaal Gegevens Wijzigen
sidebar: |
  <h3>Laadpaal Gegevens Wijzigen</h3>
  <ul>
    <li><a href="#overzicht">Overzicht</a></li>
    <li><a href="#navigatie">Stap 1: Navigatie</a></li>
    <li><a href="#details-pagina">Stap 2: Details Pagina</a></li>
    <li><a href="#laadinstellingen">Stap 3: Laadinstellingen</a></li>
    <li><a href="#rfid-beheer">Stap 4: RFID Beheer</a></li>
    <li><a href="#locatie-wijzigen">Stap 5: Locatie Wijzigen</a></li>
    <li><a href="#wijzigingen-opslaan">Stap 6: Wijzigingen Opslaan</a></li>
  </ul>
---

# Laadpaal Gegevens Wijzigen

<div class="content-section" id="overzicht">
  <h2>Overzicht</h2>
  <p>Het Cube Backend systeem biedt uitgebreide mogelijkheden om laadpaal gegevens te wijzigen. Gebruikers kunnen verschillende aspecten van hun laadpalen beheren, afhankelijk van hun rechten en het type laadpaal.</p>
</div>

<div class="step-section" id="navigatie">
  <h2>Stap 1: Navigatie naar Laadpaal Details</h2>
  
  <h4>Via het Hoofdmenu</h4>
  <ol>
    <li><strong>Login:</strong> Log eerst in op het Cube Backend systeem</li>
    <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
    <li><strong>Laadpalen:</strong> Klik op "Laadstations" in het hoofdmenu (links in de navigatie)</li>
    <li><strong>Laadpaal Selecteren:</strong> Klik op de gewenste laadpaal in de lijst</li>
    <li><strong>Details Pagina:</strong> Je komt op de laadpaal details pagina</li>
  </ol>
</div>

<div class="step-section" id="details-pagina">
  <h2>Stap 2: Laadpaal Details Pagina</h2>
  
  <h4>Pagina Overzicht</h4>
  <ol>
    <li><strong>Header:</strong> Toont laadpaal naam, ID en status</li>
    <li><strong>Tabs:</strong> Verschillende tabs voor verschillende informatie:
      <ul>
        <li><strong>Technische Specificaties:</strong> Technische details</li>
        <li><strong>Beheer Informatie:</strong> Beheer gegevens</li>
        <li><strong>Laadinstellingen:</strong> Laadinstellingen en RFID beheer</li>
        <li><strong>Connectoren:</strong> Connector informatie</li>
        <li><strong>Sessies:</strong> Laadsessies</li>
        <li><strong>Statistieken:</strong> Grafieken en statistieken</li>
        <li><strong>Logs:</strong> Systeem logs van de laadpaal</li>
      </ul>
    </li>
  </ol>
</div>

<div class="step-section" id="laadinstellingen">
  <h2>Stap 3: Laadinstellingen Wijzigen</h2>
  
  <h4>Laadinstellingen Tab</h4>
  <ol>
    <li><strong>Tab Selectie:</strong> Klik op "Laadinstellingen" tab</li>
    <li><strong>Laadmodus:</strong> Kies tussen:
      <ul>
        <li><strong>Vrij laden:</strong> Geen kosten voor gebruikers</li>
        <li><strong>Verrekenen:</strong> Kosten worden doorberekend</li>
      </ul>
    </li>
  </ol>
  
  <h4>Tarief Code Instellen</h4>
  <ol>
    <li><strong>Tarief Code:</strong> Voer tarief code in (bijv. CU38)</li>
    <li><strong>Tarief Info:</strong> Systeem toont tarief informatie (bijv. 0.38 EUR/k)</li>
    <li><strong>Lookup:</strong> Gebruik vergrootglas icoon voor tarief opzoeken</li>
  </ol>
  
  <h4>Publieke Laadpaal</h4>
  <ol>
    <li><strong>Checkbox:</strong> Vink "Laadpaal is publiek" aan voor publieke toegang</li>
    <li><strong>Toegang:</strong> Bepaalt of laadpaal voor iedereen toegankelijk is</li>
  </ol>
  
  <h4>Opslaan</h4>
  <ol>
    <li><strong>Save Button:</strong> Klik op "Laadinstellingen Opslaan" knop</li>
    <li><strong>Bevestiging:</strong> Wijzigingen worden opgeslagen</li>
  </ol>
</div>

<div class="step-section" id="rfid-beheer">
  <h2>Stap 4: RFID Whitelist Beheer</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Vrij Laden Whitelist</h4>
      <ol>
        <li><strong>Sectie:</strong> "RFID Whitelist" voor vrije toegang</li>
        <li><strong>Nieuwe Pas:</strong> Voeg RFID pas toe voor vrije toegang</li>
        <li><strong>Hex Code:</strong> Voer hex code van RFID tag in</li>
        <li><strong>Beschrijving:</strong> Optionele beschrijving van de pas</li>
        <li><strong>Toevoegen:</strong> Klik op "Toevoegen" knop</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Verrekenen Whitelist</h4>
      <ol>
        <li><strong>Sectie:</strong> "RFID Billing Whitelist" voor verrekening</li>
        <li><strong>Waarschuwing:</strong> Systeem toont waarschuwing als geen verrekenen passen zijn toegevoegd</li>
        <li><strong>Nieuwe Pas:</strong> Voeg RFID pas toe voor verrekening</li>
        <li><strong>Pasnummer:</strong> Voer pasnummer in</li>
        <li><strong>Beschrijving:</strong> Optionele beschrijving van de pas</li>
        <li><strong>Toevoegen:</strong> Klik op "Toevoegen" knop</li>
      </ol>
    </div>
  </div>
</div>

<div class="step-section" id="locatie-wijzigen">
  <h2>Stap 5: Locatie Wijzigen</h2>
  
  <h4>Voor Bedrijfseigenaren</h4>
  <ol>
    <li><strong>Beheer Informatie Tab:</strong> Klik op "Beheer Informatie" tab</li>
    <li><strong>Locatie Velden:</strong> Bewerk locatie gegevens:
      <ul>
        <li><strong>Straat:</strong> Straatnaam</li>
        <li><strong>Huisnummer:</strong> Huisnummer</li>
        <li><strong>Postcode:</strong> Postcode</li>
        <li><strong>Plaats:</strong> Plaats</li>
        <li><strong>Land:</strong> Land</li>
        <li><strong>Coördinaten:</strong> Latitude en longitude</li>
      </ul>
    </li>
  </ol>
  
  <h4>Kaart Editor</h4>
  <ol>
    <li><strong>Edit Address on Map:</strong> Klik op "Edit Address on Map" knop</li>
    <li><strong>Kaart Modal:</strong> Kaart editor modal opent</li>
    <li><strong>Locatie Selecteren:</strong> Klik op de gewenste locatie op de kaart</li>
    <li><strong>Adres Ophalen:</strong> Systeem haalt automatisch adres op</li>
    <li><strong>Opslaan:</strong> Klik op opslaan om wijzigingen door te voeren</li>
  </ol>
</div>

<div class="step-section" id="wijzigingen-opslaan">
  <h2>Stap 6: Wijzigingen Opslaan</h2>
  
  <h4>Save Proces</h4>
  <ol>
    <li><strong>Save Button:</strong> Klik op "Opslaan" knop in de header</li>
    <li><strong>Loading:</strong> Systeem toont "Opslaan..." tijdens het proces</li>
    <li><strong>Success:</strong> Succesbericht wordt getoond</li>
    <li><strong>Error:</strong> Bij fouten wordt foutmelding getoond</li>
  </ol>
</div>