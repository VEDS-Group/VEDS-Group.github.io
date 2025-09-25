---
layout: default
title: 2FA Aanzetten
sidebar: |
  <h3>2FA Aanzetten</h3>
  <ul>
    <li><a href="#wat-is-2fa">Wat is 2FA?</a></li>
    <li><a href="#navigatie">Stap 1: Navigatie naar Profiel</a></li>
    <li><a href="#2fa-sectie">Stap 2: 2FA Sectie Vinden</a></li>
    <li><a href="#2fa-aanzetten">Stap 3: 2FA Aanzetten</a></li>
    <li><a href="#qr-code-setup">Stap 4: QR Code Setup</a></li>
    <li><a href="#verificatie">Stap 5: Verificatie</a></li>
    <li><a href="#bevestiging">Stap 6: Bevestiging</a></li>
    <li><a href="#2fa-beheer">2FA Beheer</a></li>
    <li><a href="#authenticator-apps">Authenticator Apps</a></li>
    <li><a href="#backup-codes">Backup Codes</a></li>
  </ul>
---

# 2FA Aanzetten

<div class="content-section" id="wat-is-2fa">
  <h2>Wat is 2FA?</h2>
  
  <div class="info-card">
    <h4>Definitie</h4>
    <p>Two-Factor Authentication (2FA) is een beveiligingsmethode waarbij gebruikers twee verschillende verificatiemethoden moeten gebruiken om toegang te krijgen tot hun account:</p>
    <ul>
      <li><strong>Iets dat je weet:</strong> Wachtwoord</li>
      <li><strong>Iets dat je hebt:</strong> Authenticator app of backup code</li>
    </ul>
  </div>
</div>

<div class="step-section" id="navigatie">
  <h2>Stap 1: Navigatie naar Profiel</h2>
  
  <div class="info-card">
    <h4>Via het Hoofdmenu</h4>
    <ol>
      <li><strong>Login:</strong> Log eerst in op het Cube Backend systeem</li>
      <li><strong>Dashboard:</strong> Na login kom je op het Dashboard terecht</li>
      <li><strong>Profiel:</strong> Klik op "Profiel" in het hoofdmenu (links in de navigatie)</li>
      <li><strong>Profiel Pagina:</strong> Je komt op de profiel pagina terecht</li>
    </ol>
  </div>
</div>

<div class="step-section" id="2fa-sectie">
  <h2>Stap 2: 2FA Sectie Vinden</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Sectie Locatie</h4>
      <ul>
        <li><strong>Scroll:</strong> Scroll naar beneden naar "Two-Factor Authentication" sectie</li>
        <li><strong>Status:</strong> Controleer de huidige 2FA status</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Status Types</h4>
      <ul>
        <li><strong>Uitgeschakeld:</strong> 2FA is niet actief</li>
        <li><strong>Ingeschakeld:</strong> 2FA is actief</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="2fa-aanzetten">
  <h2>Stap 3: 2FA Aanzetten</h2>
  
  <div class="info-card">
    <h4>Voor Gebruikers zonder 2FA</h4>
    <ol>
      <li><strong>Status Check:</strong> Controleer dat status "Uitgeschakeld" is</li>
      <li><strong>Enable Button:</strong> Klik op "2FA Aanzetten" knop</li>
      <li><strong>Loading:</strong> Systeem toont "2FA wordt ingesteld..." tijdens setup</li>
      <li><strong>Setup Modal:</strong> 2FA setup modal wordt geopend</li>
    </ol>
  </div>
</div>

<div class="step-section" id="qr-code-setup">
  <h2>Stap 4: QR Code Setup</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Authenticator App Setup</h4>
      <ol>
        <li><strong>App Download:</strong> Download een authenticator app (Google Authenticator, Authy, etc.)</li>
        <li><strong>QR Scan:</strong> Scan de QR code met je authenticator app</li>
        <li><strong>Manual Entry:</strong> Of voer de secret handmatig in</li>
        <li><strong>Account Added:</strong> Account wordt toegevoegd aan je authenticator app</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Backup Codes</h4>
      <ol>
        <li><strong>Backup Codes:</strong> Kopieer de backup codes veilig</li>
        <li><strong>Veilig Opslaan:</strong> Bewaar ze op een veilige locatie</li>
        <li><strong>Eenmalig Gebruik:</strong> Elke code kan maar één keer worden gebruikt</li>
      </ol>
    </div>
  </div>
</div>

<div class="step-section" id="verificatie">
  <h2>Stap 5: Verificatie</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Code Verificatie</h4>
      <ol>
        <li><strong>Next Button:</strong> Klik op "Volgende" in de setup modal</li>
        <li><strong>Code Invoeren:</strong> Voer 6-cijferige code in van je authenticator app</li>
        <li><strong>Verificatie:</strong> Klik op "Verifiëren" om de code te controleren</li>
        <li><strong>Success:</strong> Bij succesvolle verificatie wordt 2FA geactiveerd</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Code Types</h4>
      <ul>
        <li><strong>TOTP Code:</strong> 6 cijfers van authenticator app (bijv. 123456)</li>
        <li><strong>Backup Code:</strong> 8 karakters voor noodtoegang (bijv. A1B2C3D4)</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="bevestiging">
  <h2>Stap 6: Bevestiging</h2>
  
  <div class="info-card">
    <h4>2FA Actief</h4>
    <ul>
      <li><strong>Status Update:</strong> Status verandert naar "Ingeschakeld"</li>
      <li><strong>Success Message:</strong> Succesbericht wordt getoond</li>
      <li><strong>Modal Closes:</strong> Setup modal sluit automatisch</li>
      <li><strong>Ready:</strong> 2FA is nu actief voor je account</li>
    </ul>
  </div>
</div>

<div class="content-section" id="2fa-beheer">
  <h2>2FA Beheer</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Voor Gebruikers met 2FA</h4>
      <ul>
        <li><strong>Status:</strong> Status toont "Ingeschakeld"</li>
        <li><strong>Management Options:</strong> Twee opties beschikbaar:
          <ul>
            <li><strong>2FA Resetten:</strong> Reset 2FA met nieuwe QR code en backup codes</li>
            <li><strong>2FA Uitschakelen:</strong> Schakel 2FA volledig uit</li>
          </ul>
        </li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>2FA Resetten</h4>
      <ol>
        <li><strong>Reset Button:</strong> Klik op "2FA Resetten" knop</li>
        <li><strong>Confirmation:</strong> Bevestig de reset actie</li>
        <li><strong>New Setup:</strong> Nieuwe QR code en backup codes worden gegenereerd</li>
        <li><strong>Re-setup:</strong> Volg de setup procedure opnieuw</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>2FA Uitschakelen</h4>
      <ol>
        <li><strong>Disable Button:</strong> Klik op "2FA Uitschakelen" knop</li>
        <li><strong>Confirmation:</strong> Bevestig de uitschakeling</li>
        <li><strong>Status Update:</strong> Status verandert naar "Uitgeschakeld"</li>
        <li><strong>Warning:</strong> Je account is nu minder beveiligd</li>
      </ol>
    </div>
  </div>
</div>

<div class="content-section" id="authenticator-apps">
  <h2>Authenticator Apps</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Aanbevolen Apps</h4>
      <ul>
        <li><strong>Google Authenticator:</strong> Meest populaire keuze</li>
        <li><strong>Authy:</strong> Cross-platform met backup</li>
        <li><strong>Microsoft Authenticator:</strong> Goede integratie met Microsoft ecosystem</li>
        <li><strong>1Password:</strong> Integreert met password manager</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>App Installatie</h4>
      <ol>
        <li><strong>Download:</strong> Download authenticator app van app store</li>
        <li><strong>Account Aanmaken:</strong> Maak account aan in de app</li>
        <li><strong>QR Code Scannen:</strong> Scan QR code van het systeem</li>
        <li><strong>Account Toevoegen:</strong> Account wordt toegevoegd aan app</li>
        <li><strong>Code Genereren:</strong> App genereert 6-cijferige codes</li>
      </ol>
    </div>
  </div>
</div>

<div class="content-section" id="backup-codes">
  <h2>Backup Codes</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Wat zijn Backup Codes?</h4>
      <ul>
        <li><strong>Noodtoegang:</strong> Voor wanneer authenticator app niet beschikbaar is</li>
        <li><strong>Eenmalig Gebruik:</strong> Elke code kan maar één keer worden gebruikt</li>
        <li><strong>8 Karakters:</strong> Bestaan uit letters en cijfers</li>
        <li><strong>Veilig Opslaan:</strong> Moeten veilig worden bewaard</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Backup Code Gebruik</h4>
      <ol>
        <li><strong>Noodtoegang:</strong> Wanneer authenticator app niet werkt</li>
        <li><strong>Code Invoeren:</strong> Voer 8-karakter backup code in</li>
        <li><strong>Verificatie:</strong> Systeem verifieert de code</li>
        <li><strong>Toegang:</strong> Gebruiker krijgt toegang</li>
        <li><strong>Code Verwijderen:</strong> Gebruikte code wordt verwijderd</li>
      </ol>
    </div>
  </div>
</div>
