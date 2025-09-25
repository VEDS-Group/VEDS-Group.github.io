---
layout: default
title: Statistieken Genereren
sidebar: |
  <h3>Statistieken Genereren</h3>
  <ul>
    <li><a href="#overzicht">Overzicht</a></li>
    <li><a href="#navigatie">Stap 1: Navigatie</a></li>
    <li><a href="#rapport-configuratie">Stap 2: Rapport Configuratie</a></li>
    <li><a href="#laadpalen-selecteren">Stap 3: Laadpalen Selecteren</a></li>
    <li><a href="#rapport-genereren">Stap 4: Rapport Genereren</a></li>
  </ul>
---

# Statistieken Genereren

<div class="content-section" id="overzicht">
  <h2>Overzicht</h2>
  <p>Het Cube Backend systeem biedt uitgebreide mogelijkheden voor het genereren van statistieken rapporten. Alleen gebruikers met admin rechten kunnen statistieken genereren en downloaden.</p>
</div>

<div class="step-section" id="navigatie">
  <h2>Stap 1: Navigatie naar Statistieken</h2>
  
  <div class="info-card">
    <h4>Via het Hoofdmenu</h4>
    <ol>
      <li><strong>Login:</strong> Log eerst in op het Cube Backend systeem</li>
      <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
          <li><strong>Admin:</strong> Klik op "Admin" in het hoofdmenu (links in de navigatie)</li>
      <li><strong>Statistieken:</strong> Klik op "Statistieken" onder admin</li>
      <li><strong>Overzicht:</strong> Je komt op de Statistieken pagina</li>
    </ol>
  </div>
</div>

<div class="step-section" id="rapport-configuratie">
  <h2>Stap 2: Rapport Configuratie</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Tijdperiode Selecteren</h4>
      <ol>
        <li><strong>Tijdperiode:</strong> Kies uit:
          <ul>
            <li><strong>Dag:</strong> Dagelijkse rapporten</li>
            <li><strong>Week:</strong> Wekelijkse rapporten</li>
            <li><strong>Maand:</strong> Maandelijkse rapporten</li>
          </ul>
        </li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Datum Bereik Instellen</h4>
      <ol>
        <li><strong>Start Datum:</strong> Selecteer de startdatum voor het rapport</li>
        <li><strong>Eind Datum:</strong> Selecteer de einddatum voor het rapport</li>
        <li><strong>Preview:</strong> Bekijk de Excel preview om te zien hoe het rapport eruit ziet</li>
      </ol>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Excel Preview</h4>
    <ul>
      <li><strong>Voorbeeld Tabel:</strong> Toont hoe de data wordt gegroepeerd</li>
      <li><strong>Kolommen:</strong> Toont de tijdperiode kolommen</li>
      <li><strong>Totaal:</strong> Toont het totaal per laadpaal</li>
      <li><strong>Notitie:</strong> Uitleg over hoe lange periodes worden samengevat</li>
    </ul>
  </div>
</div>

<div class="step-section" id="laadpalen-selecteren">
  <h2>Stap 3: Laadpalen Selecteren</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Filters Toepassen</h4>
      <ol>
        <li><strong>Zoeken:</strong> Type minimaal 2 karakters om te zoeken op:
          <ul>
            <li>Laadpaal ID</li>
            <li>Laadpaal naam</li>
            <li>Locatie</li>
          </ul>
        </li>
        <li><strong>Firmware Versie:</strong> Filter op specifieke firmware versie</li>
        <li><strong>Laadpaal Model:</strong> Filter op specifiek laadpaal model</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Laadpalen Toevoegen</h4>
      <ol>
        <li><strong>Beschikbare Laadpalen:</strong> Links paneel toont alle beschikbare laadpalen</li>
        <li><strong>Selecteren:</strong> Klik op een laadpaal om deze toe te voegen</li>
        <li><strong>Select All:</strong> Klik op "Select All" om alle laadpalen te selecteren</li>
        <li><strong>Load More:</strong> Klik op "Load More" om meer laadpalen te laden</li>
      </ol>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Geselecteerde Laadpalen</h4>
    <ol>
      <li><strong>Geselecteerde Laadpalen:</strong> Rechts paneel toont geselecteerde laadpalen</li>
      <li><strong>Verwijderen:</strong> Klik op een laadpaal om deze te verwijderen</li>
      <li><strong>Deselect All:</strong> Klik op "Deselect All" om alle selecties te verwijderen</li>
    </ol>
  </div>
</div>

<div class="step-section" id="rapport-genereren">
  <h2>Stap 4: Rapport Genereren</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Download Rapport</h4>
      <ol>
        <li><strong>Download Button:</strong> Klik op "Download Rapport"</li>
        <li><strong>Genereren:</strong> Het systeem genereert het Excel rapport</li>
        <li><strong>Download:</strong> Het rapport wordt automatisch gedownload</li>
        <li><strong>Bestandsnaam:</strong> Het bestand krijgt een beschrijvende naam</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Rapport Inhoud</h4>
      <ul>
        <li><strong>Laadpaal Informatie:</strong> ID, bedrijf, locatie</li>
        <li><strong>Tijdperiode Data:</strong> kWh en sessies per periode</li>
        <li><strong>Totaal:</strong> Totaal per laadpaal</li>
        <li><strong>Excel Formaat:</strong> .xlsx bestand</li>
      </ul>
    </div>
  </div>
</div>