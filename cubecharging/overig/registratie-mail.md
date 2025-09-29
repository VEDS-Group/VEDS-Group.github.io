<div class="step-section" id="foutafhandeling">
  <h2>Stap 5: Foutafhandeling</h2>
  
  <div class="info-card">
    <h4>Mogelijke Fouten</h4>
    <ul>
      <li><strong>Netwerk Fout:</strong> Verbindingsprobleem met backend</li>
      <li><strong>Email Fout:</strong> Ongeldig email adres</li>
      <li><strong>Gebruiker Niet Gevonden:</strong> Gebruiker bestaat niet in Odoo</li>
      <li><strong>Mail Service Fout:</strong> Probleem met mail service</li>
    </ul>
  </div>
  
  <div class="info-card">
    <h4>Error Meldingen</h4>
    <ul>
      <li><strong>Titel:</strong> "Fout bij versturen"</li>
      <li><strong>Bericht:</strong> "Er is een fout opgetreden bij het versturen van de registratie mail"</li>
      <li><strong>Duur:</strong> Melding blijft zichtbaar tot gesloten</li>
    </ul>
  </div>
</div>

<div class="step-section" id="gebruiker-informatie">
  <h2>Stap 6: Gebruiker Informatie</h2>
  
  <div class="info-card">
    <h4>Wat Wordt Getoond</h4>
    <ul>
      <li><strong>Email Adres:</strong> Volledig email adres van de gebruiker</li>
      <li><strong>Partner ID:</strong> Odoo partner ID (indien beschikbaar)</li>
      <li><strong>Rol:</strong> Huidige rol van de gebruiker</li>
      <li><strong>Registratie Status:</strong> Of de gebruiker al geregistreerd is</li>
    </ul>
  </div>
  
  <div class="info-card">
    <h4>Mail Buttons Beschikbaar</h4>
    <ol>
      <li><strong>Stuur inlog mail</strong> (📧): Voor nieuwe gebruikers</li>
      <li><strong>Reset wachtwoord</strong> (��): Voor bestaande gebruikers</li>
      <li><strong>Reset 2FA</strong> (🔐): Voor 2FA problemen</li>
    </ol>
  </div>
</div>

<div class="step-section" id="tips-helpdesk">
  <h2>Tips voor Helpdesk</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Voor Nieuwe Gebruikers</h4>
      <ul>
        <li><strong>Gebruik Registratie Mail:</strong> Voor gebruikers die nog niet geregistreerd zijn</li>
        <li><strong>Controleer Email:</strong> Zorg dat het email adres correct is</li>
        <li><strong>Verifieer in Odoo:</strong> Controleer of de gebruiker in Odoo staat</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Voor Bestaande Gebruikers</h4>
      <ul>
        <li><strong>Gebruik Wachtwoord Reset:</strong> Voor gebruikers die hun wachtwoord kwijt zijn</li>
        <li><strong>Gebruik 2FA Reset:</strong> Voor gebruikers met 2FA problemen</li>
      </ul>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Veelgestelde Vragen</h4>
    <ul>
      <li><strong>Mail Niet Aangekomen:</strong> Controleer spam folder, probeer opnieuw</li>
      <li><strong>Gebruiker Niet Gevonden:</strong> Controleer of gebruiker in Odoo staat</li>
      <li><strong>Button Niet Zichtbaar:</strong> Controleer of je admin rechten hebt</li>
      <li><strong>Fout bij Versturen:</strong> Probeer opnieuw, controleer netwerkverbinding</li>
    </ul>
  </div>
</div>

<div class="step-section" id="technische-details">
  <h2>Technische Details</h2>
  
  <div class="info-card">
    <h4>API Endpoint</h4>
    <ul>
      <li><strong>Endpoint:</strong> `/api/auth/send-registration-mail`</li>
      <li><strong>Method:</strong> POST</li>
      <li><strong>Parameters:</strong> email, name (optioneel)</li>
    </ul>
  </div>
  
  <div class="info-card">
    <h4>Mail Content</h4>
    <ul>
      <li><strong>Onderwerp:</strong> Registratie voor Cube Backend</li>
      <li><strong>Inhoud:</strong> Registratielink met token</li>
      <li><strong>Geldigheid:</strong> Token heeft beperkte geldigheid</li>
    </ul>
  </div>
  
  <div class="info-card">
    <h4>Beveiliging</h4>
    <ul>
      <li><strong>Admin Only:</strong> Alleen admin gebruikers kunnen mails versturen</li>
      <li><strong>Odoo Validatie:</strong> Alleen Odoo gebruikers kunnen worden geselecteerd</li>
      <li><strong>Rate Limiting:</strong> Beperkt aantal mails per gebruiker</li>
    </ul>
  </div>
</div>