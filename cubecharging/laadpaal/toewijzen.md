---
layout: default
title: Laadpaal Toewijzen
sidebar: |
  <h3>Laadpaal Toewijzen</h3>
  <ul>
    <li><a href="#waarschuwing">Belangrijke Waarschuwing</a></li>
    <li><a href="#groeps-toegang">Voor Groeps-Toegang</a></li>
    <li><a href="#methode">Wanneer Welke Methode?</a></li>
    <li><a href="#navigatie">Stap 1: Navigatie</a></li>
    <li><a href="#gebruiker-zoeken">Stap 2: Gebruiker Zoeken</a></li>
    <li><a href="#toewijzingen">Stap 3: Toewijzingen Beheren</a></li>
    <li><a href="#toevoegen">Stap 4: Laadpalen Toevoegen</a></li>
    <li><a href="#opslaan">Stap 5: Wijzigingen Opslaan</a></li>
  </ul>
---

# Laadpaal Toewijzen

<div class="warning-section" id="waarschuwing">
  <h3>⚠️ Belangrijke Waarschuwing</h3>
  <p>Via deze <strong>Admin Instellingen</strong> functionaliteit wijs je laadpalen officieel toe aan gebruikers. Dit betekent:</p>
  <ul>
    <li>De toewijzing wordt bijgewerkt in Odoo</li>
    <li>Gebruikers worden eigenaar van de laadpalen via <strong>res_partner_id</strong></li>
    <li>Laadpalen staan officieel op naam van de gebruiker</li>
  </ul>
</div>

<div class="content-section" id="groeps-toegang">
  <h3>Voor Groeps-Toegang</h3>
  <p>Voor het geven van toegang tot meerdere laadpalen zonder eigendom, gebruik je <a href="groepen.html">Laadpaal groepen</a></p>
</div>

<div class="info-grid" id="methode">
  <div class="info-card">
    <h4>Admin Instellingen</h4>
    <p>Voor officiële toewijzing van specifieke laadpalen op naam van de gebruiker</p>
  </div>
  <div class="info-card">
    <h4>Laadpaal Groepen</h4>
    <p>Voor toegang tot meerdere gerelateerde laadpalen zonder eigendom</p>
  </div>
</div>

<div class="step-section" id="navigatie">
  <h2>Stap 1: Navigatie naar Admin Instellingen</h2>
  <h4>Via het Hoofdmenu</h4>
  <ol>
    <li><strong>Login:</strong> Log eerst in op het Cube Backend systeem</li>
    <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
    <li><strong>Admin:</strong> Klik op "Admin" in het hoofdmenu (links in de navigatie)</li>
    <li><strong>Admin Instellingen:</strong> Klik op "Admin Instellingen" in het admin submenu</li>
    <li><strong>User Permissions:</strong> Je komt op de User Permissions tab (standaard actief)</li>
  </ol>
</div>

<div class="step-section" id="gebruiker-zoeken">
  <h2>Stap 2: Gebruiker Zoeken en Selecteren</h2>
  
  <h4>Gebruiker Zoeken</h4>
  <div class="info-grid">
    <div class="info-card">
      <h4>Email Input</h4>
      <p>In het "Email Address" veld typ je de email van de gebruiker</p>
    </div>
    <div class="info-card">
      <h4>Minimum Karakters</h4>
      <p>Je moet minimaal 6 karakters typen voordat er gezocht wordt</p>
    </div>
    <div class="info-card">
      <h4>Dropdown</h4>
      <p>Er verschijnt een dropdown met zoekresultaten</p>
    </div>
  </div>

  <h4>Gebruiker Info</h4>
  <p>Elke gebruiker toont:</p>
  <ul>
    <li>Email adres</li>
    <li>Partner ID (res_partner_id)</li>
  </ul>

  <div class="warning-section">
    <h4>⚠️ Belangrijke Waarschuwing</h4>
    <p><strong>Let goed op bij dubbele email adressen!</strong></p>
    <ul>
      <li>Verschillende gebruikers kunnen hetzelfde email adres hebben</li>
      <li>Controleer altijd het Partner ID (res_partner_id) voordat je een gebruiker selecteert</li>
      <li>Selecteer de juiste gebruiker uit de dropdown om verkeerde toewijzingen te voorkomen</li>
    </ul>
  </div>

  <h4>Gebruiker Selecteren</h4>
  <ul>
    <li><strong>Klik:</strong> Klik op de juiste gebruiker in de dropdown</li>
    <li><strong>Bevestiging:</strong> De gebruiker wordt geselecteerd en je ziet de permissions sectie</li>
  </ul>
</div>

<div class="step-section" id="toewijzingen">
  <h2>Stap 3: Laadpaal Toewijzingen Beheren</h2>
  
  <h4>Charging Stations Sectie</h4>
  <ul>
    <li><strong>Sectie Openen:</strong> Klik op "Charging Stations" om de sectie uit te klappen</li>
    <li><strong>Uitleg:</strong> Je ziet twee panelen:
      <ul>
        <li><strong>Links:</strong> Beschikbare laadpalen om toe te voegen</li>
        <li><strong>Rechts:</strong> Alle laadpalen die aan de gebruiker gekoppeld zijn</li>
      </ul>
    </li>
  </ul>
</div>

<div class="step-section" id="toevoegen">
  <h2>Stap 4: Laadpalen Toevoegen</h2>
  
  <h4>Stap-voor-stap Proces</h4>
  <ol>
    <li><strong>Zoeken:</strong> Zoek naar de gewenste laadpaal in het linkse paneel</li>
    <li><strong>Selecteren:</strong> Klik op de laadpaal om deze te selecteren</li>
    <li><strong>Bevestiging:</strong> De laadpaal verschijnt nu in het rechtse paneel</li>
    <li><strong>Meer Toevoegen:</strong> Herhaal het proces voor andere laadpalen</li>
  </ol>
</div>

<div class="step-section" id="opslaan">
  <h2>Stap 5: Wijzigingen Opslaan</h2>
  
  <h4>Opslaan Proces</h4>
  <ol>
    <li><strong>Controle:</strong> Controleer alle toewijzingen voordat je opslaat</li>
    <li><strong>Save Button:</strong> Klik op "Save Changes" om de wijzigingen op te slaan</li>
    <li><strong>Bevestiging:</strong> Het systeem bevestigt dat de wijzigingen zijn opgeslagen</li>
    <li><strong>Direct Effect:</strong> De gebruiker zal de laadpalen zien na het refreshen van zijn pagina</li>
  </ol>
</div>

