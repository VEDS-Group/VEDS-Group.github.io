---
layout: default
title: Email Wijzigen
sidebar: |
  <h3>Email Wijzigen</h3>
  <ul>
    <li><a href="#overzicht">Overzicht</a></li>
    <li><a href="#methode-1-klant">Methode 1: Klant Wijzigt Email Zelf</a></li>
    <li><a href="#methode-2-helpdesk">Methode 2: Helpdesk via Admin Settings</a></li>
  </ul>
---

# Email Wijzigen


<div class="content-section" id="methode-1-klant">
  <h2>Methode 1: Klant Wijzigt Email Zelf</h2>
  
  <div class="step-section">
    <h4>Stap 1: Navigatie naar Profiel</h4>
    <ol>
      <li><strong>Login:</strong> Log in op het Cube Backend systeem</li>
      <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
      <li><strong>Profiel:</strong> Klik op "Profiel" in het hoofdmenu (links in de navigatie)</li>
      <li><strong>Persoonlijke Informatie:</strong> Je komt op de profiel pagina</li>
    </ol>
  </div>
  
  <div class="step-section">
    <h4>Stap 2: Email Wijzigen</h4>
    <ol>
      <li><strong>Email Veld:</strong> In de "Persoonlijke Informatie" sectie zie je het huidige email adres</li>
      <li><strong>Wijzigen:</strong> Pas het email adres aan naar het nieuwe adres</li>
      <li><strong>Opslaan:</strong> Klik op "Opslaan" om de wijziging door te voeren</li>
      <li><strong>Bevestiging:</strong> Het systeem toont een bevestiging van de wijziging</li>
    </ol>
  </div>
  
  <div class="info-card">
    <h4>Wat Gebeurt Er?</h4>
    <ul>
      <li><strong>Database Update:</strong> Het email adres wordt bijgewerkt in de database</li>
      <li><strong>Token Update:</strong> Een nieuw JWT token wordt gegenereerd met het nieuwe email adres</li>
      <li><strong>Sessie Behoud:</strong> De gebruiker blijft ingelogd met het nieuwe email adres</li>
      <li><strong>Odoo Sync:</strong> Het email adres wordt gesynchroniseerd met Odoo (indien van toepassing)</li>
    </ul>
  </div>
</div>

<div class="content-section" id="methode-2-helpdesk">
  <h2>Methode 2: Cube wijzigt email via Admin settings</h2>
  
  
  <div class="step-section">
    <h4>Stap 1: Navigatie naar Admin Settings</h4>
    <ol>
      <li><strong>Login:</strong> Log in op het Cube Backend systeem</li>
      <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
      <li><strong>Admin:</strong> Klik op "Admin" in het hoofdmenu</li>
      <li><strong>Admin Settings:</strong> Klik op "Admin Settings" in het admin submenu</li>
      <li><strong>User Permissions:</strong> Zorg dat je op de "User Permissions" tab staat</li>
    </ol>
  </div>
  
  <div class="step-section">
    <h4>Stap 2: Gebruiker Zoeken</h4>
    <ol>
      <li><strong>Email Zoeken:</strong> Type minimaal 6 karakters in het email zoekveld</li>
      <li><strong>Gebruiker Selecteren:</strong> Klik op de juiste gebruiker uit de dropdown</li>
      <li><strong>Gebruiker Laden:</strong> Het systeem laadt de gebruiker gegevens</li>
    </ol>
  </div>
  
  <div class="step-section">
    <h4>Stap 3: Email Wijzigen</h4>
    <ol>
      <li><strong>User Email Management:</strong> Scroll naar de "User Email Management" sectie</li>
      <li><strong>Sectie Openen:</strong> Klik op de sectie header om deze uit te klappen</li>
      <li><strong>Huidig Email:</strong> Je ziet het huidige email adres van de gebruiker</li>
      <li><strong>Nieuw Email:</strong> Voer het nieuwe email adres in</li>
      <li><strong>Wijzigen:</strong> Klik op "Change Email" om de wijziging door te voeren</li>
    </ol>
  </div>
  
  <div class="info-card">
    <h4>Wat Gebeurt Er?</h4>
    <ul>
      <li><strong>Database Update:</strong> Het email adres wordt bijgewerkt in de database</li>
      <li><strong>Odoo Sync:</strong> Het email adres wordt gesynchroniseerd met Odoo</li>
      <li><strong>Gebruiker Notificatie:</strong> De gebruiker wordt op de hoogte gesteld van de wijziging</li>
      <li><strong>Sessie Invalidatie:</strong> Bestaande sessies van de gebruiker worden ongeldig gemaakt</li>
    </ul>
  </div>
</div>
