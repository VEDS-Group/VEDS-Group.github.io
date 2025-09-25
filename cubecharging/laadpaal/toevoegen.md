---
layout: default
title: Laadpaal Toevoegen
sidebar: |
  <h3>Laadpaal Toevoegen</h3>
  <ul>
    <li><a href="#navigatie">Stap 1: Navigatie</a></li>
    <li><a href="#basis-informatie">Stap 2: Basis Informatie</a></li>
    <li><a href="#installatie-details">Stap 3: Installatie Details</a></li>
    <li><a href="#locatie-informatie">Stap 4: Locatie Informatie</a></li>
    <li><a href="#beschrijving">Stap 5: Beschrijving</a></li>
    <li><a href="#configuratie">Stap 6: Configuratie Opties</a></li>
    <li><a href="#opslaan">Stap 7: Opslaan</a></li>
  </ul>
---

# Laadpaal Toevoegen aan het Cube Backend Systeem

<div class="step-section" id="navigatie">
  <h2>Stap 1: Navigatie naar de Laadpaal Toevoegen Pagina</h2>
  
  <h4>Via het Hoofdmenu</h4>
  <ol>
    <li><strong>Login:</strong> Log eerst in op het Cube Backend systeem</li>
    <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
    <li><strong>Laadstations:</strong> Klik op "laadstations" in het hoofdmenu (links in de navigatie)</li>
    <li><strong>Add Button:</strong> Op de Charging Stations overzichtspagina zie je rechtsboven een groene "laadpaal toevoegen" knop</li>
    <li><strong>Klik:</strong> Klik op deze knop om naar de laadpaal toevoegen pagina te gaan</li>
  </ol>
</div>

<div class="step-section" id="basis-informatie">
  <h2>Stap 2: Basis Informatie</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Charge Box ID (Verplicht)</h4>
      <ul>
        <li><strong>Veld:</strong> Charge Box ID</li>
        <li><strong>Beschrijving:</strong> Unieke identificatie van de laadpaal</li>
        <li><strong>Formaat:</strong> Tekstveld</li>
        <li><strong>Voorbeeld:</strong> NL-1IC-A7843D4F</li>
        <li><strong>Validatie:</strong> Moet uniek zijn in het systeem</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Gebruiker Selectie</h4>
      <ul>
        <li><strong>Veld:</strong> User</li>
        <li><strong>Beschrijving:</strong> Selecteer de eigenaar/beheerder van de laadpaal</li>
      </ul>
      <div class="step-section">
        <h5>Functionaliteit:</h5>
        <ul>
          <li>Dropdown met zoekfunctionaliteit</li>
          <li>Zoekt in Odoo gebruikers database</li>
          <li>Toont email en rol van gebruiker</li>
          <li>Minimum 2 karakters voor zoeken</li>
          <li>Cache wordt elke minuut ververst</li>
        </ul>
      </div>
    </div>
    
    <div class="info-card">
      <h4>Tarief Code (Optioneel)</h4>
      <ul>
        <li><strong>Veld:</strong> Tarief Code</li>
        <li><strong>Beschrijving:</strong> Selecteer het tarief dat van toepassing is op deze laadpaal</li>
      </ul>
      <div class="step-section">
        <h5>Functionaliteit:</h5>
        <ul>
          <li>Dropdown met alle beschikbare tarieven</li>
          <li>Toont energieprijs en startprijs</li>
          <li>Zoekfunctionaliteit beschikbaar</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div class="step-section" id="installatie-details">
  <h2>Stap 3: Installatie Details</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Installateur Informatie (Optioneel)</h4>
      <ul>
        <li><strong>Veld:</strong> Installateur naam</li>
        <li><strong>Beschrijving:</strong> Naam van de installateur</li>
        <li><strong>Type:</strong> Tekstveld</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Installatie Datum (Optioneel)</h4>
      <ul>
        <li><strong>Veld:</strong> Installation Datum</li>
        <li><strong>Beschrijving:</strong> Datum waarop de laadpaal is geïnstalleerd</li>
        <li><strong>Type:</strong> Datum picker</li>
        <li><strong>Formaat:</strong> YYYY-MM-DD</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="locatie-informatie">
  <h2>Stap 4: Locatie Informatie</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Coördinaten (Optioneel)</h4>
      <ul>
        <li><strong>Latitude:</strong> Breedtegraad van de locatie</li>
        <li><strong>Longitude:</strong> Lengtegraad van de locatie</li>
        <li><strong>Precisie:</strong> Tot 6 decimalen</li>
        <li><strong>Voorbeeld:</strong> 52.123456, 4.789012</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Adres Details (Optioneel)</h4>
      <ul>
        <li><strong>Straat:</strong> Straatnaam</li>
        <li><strong>Huisnummer:</strong> Huisnummer</li>
        <li><strong>Postcode:</strong> Postcode</li>
        <li><strong>Plaats:</strong> Stad/Gemeente</li>
        <li><strong>Land:</strong> Land (standaard Nederland)</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="beschrijving">
  <h2>Stap 5: Beschrijving en Notities</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Beschrijving (Optioneel)</h4>
      <ul>
        <li><strong>Veld:</strong> Beschrijving</li>
        <li><strong>Beschrijving:</strong> Korte beschrijving van de laadpaal</li>
        <li><strong>Type:</strong> Tekstarea (3 regels)</li>
        <li><strong>Voorbeeld:</strong> "Snellader bij kantoorgebouw"</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Aanvullende Notitie (Optioneel)</h4>
      <ul>
        <li><strong>Veld:</strong> Aanvullende opmerkingen</li>
        <li><strong>Beschrijving:</strong> Extra informatie over de laadpaal</li>
        <li><strong>Type:</strong> Tekstarea (3 regels)</li>
        <li><strong>Voorbeeld:</strong> "Toegankelijk voor gehandicapten"</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="configuratie">
  <h2>Stap 6: Configuratie Opties</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Connector Status Tracking (Optioneel)</h4>
      <ul>
        <li><strong>Optie:</strong> Insert Connector Status After Start Stop Transaction</li>
        <li><strong>Beschrijving:</strong> Voegt connector status toe na start/stop transacties</li>
        <li><strong>Type:</strong> Checkbox</li>
        <li><strong>Standaard:</strong> Uitgeschakeld</li>
        <li><strong>Gebruik:</strong> Voor gedetailleerde monitoring</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>ID Tag Toegang (Optioneel)</h4>
      <ul>
        <li><strong>Optie:</strong> Allow All ID Tags</li>
        <li><strong>Beschrijving:</strong> Staat alle ID tags toe om te laden</li>
        <li><strong>Type:</strong> Checkbox</li>
        <li><strong>Standaard:</strong> Uitgeschakeld</li>
        <li><strong>Gebruik:</strong> Voor publieke laadpalen</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Verrekening Integratie (Optioneel)</h4>
      <ul>
        <li><strong>Optie:</strong> Verrekening</li>
        <li><strong>Beschrijving:</strong> Integratie met netwerk voor verrekening</li>
        <li><strong>Type:</strong> Checkbox</li>
        <li><strong>Standaard:</strong> Uitgeschakeld</li>
        <li><strong>Gebruik:</strong> Voor commerciële laadpalen</li>
      </ul>
    </div>
  </div>
</div>


<div class="step-section" id="opslaan">
  <h2>Stap 7: Opslaan en Voltooien</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Formulier Verzenden</h4>
      <ul>
        <li><strong>Controle:</strong> Controleer alle ingevulde velden</li>
        <li><strong>Verplichte Velden:</strong> Zorg dat Charge Box ID is ingevuld</li>
        <li><strong>Opslaan:</strong> Klik op de groene "Create" knop</li>
        <li><strong>Wachten:</strong> Het systeem verwerkt de aanvraag (max 30 seconden)</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Na Opslaan</h4>
      <ul>
        <li><strong>Success Melding:</strong> Groene toast melding verschijnt</li>
        <li><strong>Redirect:</strong> Automatische redirect naar Charging Stations overzicht</li>
        <li><strong>Bevestiging:</strong> Nieuwe laadpaal verschijnt in de lijst</li>
      </ul>
    </div>
  </div>
</div>
