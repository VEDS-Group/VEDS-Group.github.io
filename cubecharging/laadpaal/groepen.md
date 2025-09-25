---
layout: default
title: Laadpaal Groepen
sidebar: |
  <h3>Laadpaal Groepen</h3>
  <ul>
    <li><a href="#waarschuwing">Belangrijke Waarschuwing</a></li>
    <li><a href="#officiele-toewijzing">Voor Officiële Toewijzing</a></li>
    <li><a href="#methode">Wanneer Welke Methode?</a></li>
    <li><a href="#navigatie">Stap 1: Navigatie</a></li>
    <li><a href="#overzicht">Stap 2: Groepen Overzicht</a></li>
    <li><a href="#nieuwe-groep">Stap 3: Nieuwe Groep</a></li>
    <li><a href="#groep-beheren">Stap 4: Groep Beheren</a></li>
    <li><a href="#laadpalen-toevoegen">Stap 5: Laadpalen Toevoegen</a></li>
    <li><a href="#gebruikers-toevoegen">Stap 6: Gebruikers Toevoegen</a></li>
  </ul>
---

# Laadpaal Groepen

<div class="warning-section" id="waarschuwing">
  <h3>⚠️ Belangrijke Waarschuwing</h3>
  <p>Via deze <strong>Laadpaal Groepen</strong> functionaliteit wijs je GEEN laadpalen officieel toe aan gebruikers. Dit betekent:</p>
  <ul>
    <li>De toewijzing wordt niet bijgewerkt in Odoo</li>
    <li>Gebruikers worden geen eigenaar van de laadpalen</li>
    <li>Gebruikers kunnen de laadpalen alleen zien en aanpassen</li>
  </ul>
</div>

<div class="content-section" id="officiele-toewijzing">
  <h3>Voor Officiële Toewijzing</h3>
  <p>Voor het officieel toewijzen van laadpalen aan gebruikers (met Odoo update en eigendom), gebruik je <a href="toewijzen.html" >Laadpaal toewijzen</a>.</p>
</div>

<div class="info-grid" id="methode">
  <div class="info-card">
    <h4>Laadpaal Groepen</h4>
    <p>Voor toegang tot meerdere gerelateerde laadpalen zonder eigendom</p>
  </div>
  <div class="info-card">
    <h4>Admin Instellingen</h4>
    <p>Voor officiële toewijzing van specifieke laadpalen op naam van de gebruiker</p>
  </div>
</div>

<div class="step-section" id="navigatie">
  <h2>Stap 1: Navigatie naar Laadpaal Groepen</h2>
  
  <h4>Via het Hoofdmenu</h4>
  <ol>
    <li><strong>Login:</strong> Log eerst in op het Cube Backend systeem</li>
    <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
    <li><strong>Admin:</strong> Klik op "Admin" in het hoofdmenu (links in de navigatie)</li>
    <li><strong>Laadpaal Groepen:</strong> Klik op "Laadpaal Groepen" in het admin submenu</li>
    <li><strong>Overzicht:</strong> Je komt op de Laadpaal Groepen overzichtspagina</li>
  </ol>
</div>

<div class="step-section" id="overzicht">
  <h2>Stap 2: Groepen Overzicht</h2>
  
  <h4>Overzichtspagina Functionaliteiten</h4>
  <div class="info-grid">
    <div class="info-card">
      <h4>Zoeken</h4>
      <p>Gebruik het zoekveld om groepen te filteren op naam of beschrijving</p>
    </div>
    
    <div class="info-card">
      <h4>Sorteren</h4>
      <p>Sorteer op:</p>
      <ul>
        <li>Naam (groepnaam)</li>
        <li>Aantal stations</li>
        <li>Aantal gebruikers</li>
      </ul>
      <p><strong>Volgorde:</strong> Kies tussen oplopend of aflopend</p>
    </div>
    
    <div class="info-card">
      <h4>Nieuwe Groep</h4>
      <p>Klik op "Nieuwe Groep" om een groep aan te maken</p>
    </div>
  </div>
</div>

<div class="step-section" id="nieuwe-groep">
  <h2>Stap 3: Nieuwe Groep Aanmaken</h2>
  
  <h4>Navigatie naar Aanmaken</h4>
  <ul>
    <li><strong>Nieuwe Groep Button:</strong> Klik op "Nieuwe Groep" rechtsboven</li>
  </ul>
  
  <h4>Groep Informatie Invullen</h4>
  <div class="info-grid">
    <div class="info-card">
      <h4>Groepnaam (Verplicht)</h4>
      <ul>
        <li>Unieke naam voor de groep</li>
        <li><strong>Voorbeeld:</strong> "Kantoor Laadpalen", "Publieke Stations"</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Beschrijving (Optioneel)</h4>
      <ul>
        <li>Korte beschrijving van de groep</li>
        <li><strong>Voorbeeld:</strong> "Alle laadpalen op kantoorlocatie"</li>
      </ul>
    </div>
  </div>
  
  <h4>Opslaan</h4>
  <ol>
    <li><strong>Controle:</strong> Controleer de ingevulde informatie</li>
    <li><strong>Create Button:</strong> Klik op "Create" om de groep aan te maken</li>
    <li><strong>Redirect:</strong> Je wordt teruggeleid naar het groepen overzicht</li>
    <li><strong>Volgende Stap:</strong> Laadpalen toevoegen aan de groep</li>
  </ol>
</div>

<div class="step-section" id="groep-beheren">
  <h2>Stap 4: Groep Beheren</h2>
  
  <h4>Groep Detail Pagina</h4>
  <ul>
    <li><strong>Klik:</strong> Klik op een groep in het overzicht</li>
    <li><strong>Detail Pagina:</strong> Je komt op de groep detail pagina</li>
    <li><strong>Tabs:</strong> Drie tabs beschikbaar:
      <ul>
        <li><strong>Groep Info:</strong> Basis informatie en systeem info</li>
        <li><strong>Laadpalen:</strong> Laadpalen in de groep</li>
        <li><strong>Gebruikers:</strong> Gebruikers met toegang tot de groep</li>
      </ul>
    </li>
  </ul>
  
  <h4>Groep Info Tab</h4>
  <div class="info-grid">
    <div class="info-card">
      <h4>Basis Informatie</h4>
      <ul>
        <li><strong>Groepnaam:</strong> Wijzig de naam van de groep</li>
        <li><strong>Beschrijving:</strong> Pas de beschrijving aan</li>
        <li><strong>Save Button:</strong> Opslaan van wijzigingen</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Systeem Informatie</h4>
      <ul>
        <li><strong>Group PK:</strong> Unieke ID van de groep</li>
        <li><strong>Totaal Stations:</strong> Aantal laadpalen in de groep</li>
        <li><strong>Totaal Gebruikers:</strong> Aantal gebruikers met toegang</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="laadpalen-toevoegen">
  <h2>Stap 5: Laadpalen Toevoegen aan Groep</h2>
  
  <h4>Laadpalen Tab</h4>
  <ul>
    <li><strong>Tab Selectie:</strong> Klik op "Laadpalen" tab</li>
  </ul>
  
  <h4>Laadpalen Zoeken en Selecteren</h4>
  <div class="info-grid">
    <div class="info-card">
      <h4>Zoekfunctionaliteit</h4>
      <ul>
        <li><strong>Zoekveld:</strong> Type minimaal 2 karakters om te zoeken</li>
        <li><strong>Beschikbare Laadpalen:</strong> Links paneel toont alle beschikbare laadpalen</li>
        <li><strong>Selecteren:</strong> Klik op een laadpaal om deze te selecteren</li>
        <li><strong>Geselecteerde Laadpalen:</strong> Rechts paneel toont geselecteerde laadpalen</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Laadpalen Toevoegen</h4>
      <ul>
        <li><strong>Selectie:</strong> Selecteer de gewenste laadpalen</li>
        <li><strong>Save Button:</strong> Klik op "Add X Station(s)" om toe te voegen</li>
        <li><strong>Bevestiging:</strong> Laadpalen worden toegevoegd aan de groep</li>
        <li><strong>Refresh:</strong> De lijst wordt automatisch ververst</li>
      </ul>
    </div>
  </div>
  
  <h4>Huidige Laadpalen Beheren</h4>
  <ul>
    <li><strong>Current Stations:</strong> Overzicht van alle laadpalen in de groep</li>
    <li><strong>Verwijderen:</strong> Klik op de rode knop met "verwijderen" om een laadpaal te verwijderen</li>
    <li><strong>Bevestiging:</strong> Laadpaal wordt verwijderd uit de groep</li>
  </ul>
</div>

<div class="step-section" id="gebruikers-toevoegen">
  <h2>Stap 6: Gebruikers Toevoegen aan Groep</h2>
  
  <h4>Gebruikers Tab</h4>
  <ul>
    <li><strong>Tab Selectie:</strong> Klik op "Gebruikers" tab</li>
  </ul>
  
  <h4>Gebruikers Zoeken en Selecteren</h4>
  <div class="info-grid">
    <div class="info-card">
      <h4>Zoekfunctionaliteit</h4>
      <ul>
        <li><strong>Zoekveld:</strong> Type minimaal 2 karakters om te zoeken</li>
        <li><strong>Beschikbare Gebruikers:</strong> Links paneel toont alle beschikbare gebruikers</li>
        <li><strong>Gebruiker Info:</strong> Toont email en rol van de gebruiker</li>
        <li><strong>Selecteren:</strong> Klik op een gebruiker om deze te selecteren</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Gebruikers Toevoegen</h4>
      <ul>
        <li><strong>Selectie:</strong> Selecteer de gewenste gebruikers</li>
        <li><strong>Save Button:</strong> Klik op "Add X User(s)" om toe te voegen</li>
        <li><strong>Bevestiging:</strong> Gebruikers krijgen toegang tot de groep</li>
      </ul>
    </div>
  </div>
  
  <h4>Huidige Gebruikers Beheren</h4>
  <ul>
    <li><strong>Current Users:</strong> Overzicht van alle gebruikers met toegang</li>
    <li><strong>Verwijderen:</strong> Klik op de rode knop met "verwijderen" om een gebruiker te verwijderen</li>
    <li><strong>Bevestiging:</strong> Gebruiker verliest toegang tot de groep</li>
  </ul>
</div>
