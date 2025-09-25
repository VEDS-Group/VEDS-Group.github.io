---
layout: default
title: 2FA Kwijt - Helpdesk Handleiding
sidebar: |
  <h3>2FA Kwijt - Helpdesk</h3>
  <ul>
    <li><a href="#overzicht">Overzicht</a></li>
    <li><a href="#probleem-herkenning">Probleem Herkenning</a></li>
    <li><a href="#probleem-verificatie">Stap 1: Probleem Verificatie</a></li>
    <li><a href="#2fa-reset">Stap 2: 2FA Reset Proces</a></li>
    <li><a href="#2fa-herinstelling">Stap 3: 2FA Herinstelling</a></li>
  </ul>
---

# Klant 2FA Code Kwijt

<div class="content-section" id="overzicht">
  <h2>Overzicht</h2>
  <p>Wanneer een klant zijn 2FA (Two-Factor Authentication) code kwijt is, kan hij niet meer inloggen op het systeem. Dit document beschrijft hoe de helpdesk dit probleem kan oplossen.</p>
</div>

<div class="content-section" id="probleem-herkenning">
  <h2>Probleem Herkenning</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Klant Meldt</h4>
      <ul>
        <li><strong>Kan niet inloggen:</strong> Klant krijgt 2FA modal maar heeft geen toegang tot authenticator app</li>
        <li><strong>Telefoon kwijt:</strong> Authenticator app staat op telefoon die verloren/gestolen is</li>
        <li><strong>App werkt niet:</strong> Authenticator app werkt niet meer</li>
        <li><strong>Backup codes kwijt:</strong> Klant heeft backup codes verloren</li>
        <li><strong>Nieuwe telefoon:</strong> Klant heeft nieuwe telefoon zonder authenticator app</li>
      </ul>
    </div>

  </div>
</div>

<div class="step-section" id="probleem-verificatie">
  <h2>Stap 1: Probleem Verificatie</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Identiteit Verificeren</h4>
      <ol>
        <li><strong>Klant Identificeren:</strong> Vraag naar:
          <ul>
            <li>Volledige naam</li>
            <li>Email adres</li>
            <li>Bedrijfsnaam (indien van toepassing)</li>
            <li>Laatste login datum (indien bekend)</li>
          </ul>
        </li>
        <li><strong>Beveiligingsvragen:</strong> Stel beveiligingsvragen:
          <ul>
            <li>Laadpaal ID's die de klant beheert</li>
            <li>Laatste transactie details</li>
            <li>Bedrijfsinformatie</li>
          </ul>
        </li>
        <li><strong>Documentatie:</strong> Documenteer alle verificatie stappen</li>
      </ol>
    </div>
  </div>
</div>

<div class="step-section" id="2fa-reset">
  <h2>Stap 2: 2FA Reset Proces</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Admin Rechten Vereist</h4>
      <ol>
        <li><strong>Login als Admin:</strong> Log in op het Cube Backend systeem</li>
        <li><strong>Admin Settings:</strong> Ga naar Admin → Admin Settings</li>
        <li><strong>User Management:</strong> Zoek de klant op in de gebruikerslijst</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>2FA Uitschakelen</h4>
      <ol>
        <li><strong>Gebruiker Zoeken:</strong> Zoek de klant op via email of naam</li>
        <li><strong>Profiel Openen:</strong> Klik op de gebruiker om het profiel te openen</li>
        <li><strong>2FA Status:</strong> Controleer de huidige 2FA status</li>
        <li><strong>2FA Uitschakelen:</strong> Schakel 2FA uit voor de klant</li>
      </ol>
    </div>
    
  </div>
</div>


<div class="step-section" id="2fa-herinstelling">
  <h2>Stap 3: 2FA Herinstelling</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Klant Instructies</h4>
      <ol>
        <li><strong>Login:</strong> Laat de klant inloggen zonder 2FA</li>
        <li><strong>Profiel:</strong> Ga naar Profiel pagina</li>
        <li><strong>2FA Setup:</strong> Klik op "2FA Aanzetten"</li>
        <li><strong>QR Code:</strong> Scan de QR code met authenticator app</li>
        <li><strong>Verificatie:</strong> Voer de verificatiecode in</li>
        <li><strong>Backup Codes:</strong> Sla backup codes op</li>
      </ol>
    </div>
    
  </div>
</div>