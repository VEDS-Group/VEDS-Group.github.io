---
layout: default
title: Onboarding Proces
sidebar: |
  <h3>Onboarding Proces</h3>
  <ul>
    <li><a href="#overzicht">Overzicht</a></li>
    <li><a href="#video-demo">Video Demo</a></li>
    <li><a href="#registratie-link">Stap 1: Registratie Link Ontvangen</a></li>
    <li><a href="#wachtwoord-stap">Stap 2: Wachtwoord Instellen</a></li>
    <li><a href="#gebruikstype">Stap 3: Gebruikstype Selecteren</a></li>
    <li><a href="#opties">Stap 4: Opties Configureren</a></li>
    <li><a href="#betaling">Stap 5: Betalingsgegevens (indien nodig)</a></li>
    <li><a href="#voltooiing">Stap 6: Registratie Voltooien</a></li>
    <li><a href="#gebruikerstypen">Gebruikerstypen</a></li>
    <li><a href="#validatie">Validatie & Beveiliging</a></li>
  </ul>
---

# Onboarding Proces

<div class="content-section" id="overzicht">
  <h2>Overzicht</h2>
  <p>Het onboarding proces is de eerste stap voor nieuwe gebruikers om hun CubeCharging account te activeren. Het proces varieert afhankelijk van het gebruikerstype en kan een eenvoudige wachtwoordsetup zijn of een uitgebreide configuratie met gebruikstype selectie en betalingsgegevens.</p>
  
  <div class="info-card">
    <h4>Belangrijke Kenmerken</h4>
    <ul>
      <li><strong>Token-gebaseerd:</strong> Elke registratie gebruikt een unieke token voor beveiliging</li>
      <li><strong>Flexibel:</strong> Verschillende flows voor verschillende gebruikerstypen</li>
      <li><strong>Validatie:</strong> Uitgebreide wachtwoord en IBAN validatie</li>
      <li><strong>Progress Tracking:</strong> Visuele voortgangsindicator voor multi-step processen</li>
    </ul>
  </div>
</div>

<div class="content-section" id="video-demo">
  <h2>Video Demo</h2>
  
  <div class="info-card">
    <h4>Onboarding Video</h4>
    <p>Bekijk de onderstaande video voor een visuele demonstratie van het complete onboarding proces:</p>
    <video width="100%" controls style="max-width: 800px; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <source src="/videos/Onboarding.mp4" type="video/mp4">
      Je browser ondersteunt geen video afspelen. <a href="/videos/Onboarding.mp4">Download de video</a> om deze te bekijken.
    </video>
  </div>
</div>

<div class="step-section" id="registratie-link">
  <h2>Stap 1: Registratie Link Ontvangen</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Registratie Email</h4>
      <ol>
        <li><strong>Email Ontvangen:</strong> Nieuwe gebruikers ontvangen een registratie email</li>
        <li><strong>Unieke Link:</strong> Elke link bevat een unieke token</li>
        <li><strong>Gebruikerstype:</strong> Link kan gebruikerstype bevatten als URL parameter</li>
        <li><strong>Klik op Link:</strong> Gebruiker klikt op de link in de email</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Token Validatie</h4>
      <ul>
        <li><strong>Automatische Check:</strong> Systeem controleert of token geldig is</li>
        <li><strong>Verlopen Check:</strong> Controleert of token niet verlopen is</li>
        <li><strong>Gebruikt Check:</strong> Controleert of registratie nog niet voltooid is</li>
        <li><strong>Foutmelding:</strong> Bij ongeldige token wordt foutmelding getoond</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="wachtwoord-stap">
  <h2>Stap 2: Wachtwoord Instellen</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Wachtwoord Vereisten</h4>
      <p>Het wachtwoord moet voldoen aan de volgende eisen:</p>
      <ul>
        <li><strong>Minimaal 8 karakters:</strong> Wachtwoord moet minimaal 8 tekens lang zijn</li>
        <li><strong>Maximaal 20 karakters:</strong> Wachtwoord mag maximaal 20 tekens lang zijn</li>
        <li><strong>Kleine letter:</strong> Minimaal één kleine letter (a-z)</li>
        <li><strong>Hoofdletter:</strong> Minimaal één hoofdletter (A-Z)</li>
        <li><strong>Cijfer:</strong> Minimaal één cijfer (0-9)</li>
        <li><strong>Speciaal teken:</strong> Minimaal één speciaal teken (!@#$%^&* etc.)</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Real-time Validatie</h4>
      <ul>
        <li><strong>Live Feedback:</strong> Validatiefouten worden direct getoond</li>
        <li><strong>Visuele Indicatoren:</strong> Rode badges tonen welke eisen niet voldaan zijn</li>
        <li><strong>Wachtwoord Bevestiging:</strong> Controleert of beide wachtwoorden overeenkomen</li>
        <li><strong>Toggle Visibility:</strong> Mogelijkheid om wachtwoord zichtbaar te maken</li>
      </ul>
    </div>
  </div>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Wachtwoord Velden</h4>
      <ul>
        <li><strong>Wachtwoord:</strong> Hoofdwachtwoord veld met validatie</li>
        <li><strong>Bevestig Wachtwoord:</strong> Tweede veld om wachtwoord te bevestigen</li>
        <li><strong>Oog Icoon:</strong> Toggle knop om wachtwoord zichtbaar/onzichtbaar te maken</li>
        <li><strong>Submit Knop:</strong> Wordt alleen actief wanneer alle validaties slagen</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Gebruikerstype Specifiek</h4>
      <ul>
        <li><strong>USER_LAADPAS:</strong> Na wachtwoord setup wordt registratie direct voltooid</li>
        <li><strong>Simplified Registration:</strong> Eenvoudige flow voor website launch</li>
        <li><strong>Andere Types:</strong> Doorgaan naar volgende stappen</li>
      </ul>
    </div>
  </div>
</div>

<div class="step-section" id="gebruikstype">
  <h2>Stap 3: Gebruikstype Selecteren</h2>
  
  <div class="info-card">
    <h4>Beschikbare Opties</h4>
    <p>Gebruikers kunnen kiezen tussen twee hoofdopties:</p>
  </div>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>🔌 Vrij Laden</h4>
      <p><strong>Gratis laadsessies zonder facturering</strong></p>
      <ul>
        <li>Geen betalingsgegevens vereist</li>
        <li>Ideaal voor privé laadpalen</li>
        <li>Geen kosten voor gebruikers</li>
        <li>Vereist nog configuratie van toegangscontrole</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>💳 Verrekenen</h4>
      <p><strong>Facturering en betaling voor laadsessies</strong></p>
      <ul>
        <li>Betalingsgegevens vereist</li>
        <li>IBAN en tariefcode nodig</li>
        <li>Automatische facturering</li>
        <li>Verschillende pas opties beschikbaar</li>
      </ul>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Selectie Proces</h4>
    <ol>
      <li><strong>Optie Bekijken:</strong> Gebruiker bekijkt beide opties</li>
      <li><strong>Klik op Optie:</strong> Klik op gewenste optie kaart</li>
      <li><strong>Visuele Feedback:</strong> Geselecteerde optie wordt gemarkeerd</li>
      <li><strong>Volgende Stap:</strong> Klik op "Volgende" om door te gaan</li>
    </ol>
  </div>
</div>

<div class="step-section" id="opties">
  <h2>Stap 4: Opties Configureren</h2>
  
  <div class="info-card">
    <h4>Vrij Laden Opties</h4>
    <p>Voor gebruikers die "Vrij Laden" hebben gekozen:</p>
  </div>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>🔓 Alle Passen Toestaan</h4>
      <p>Alle laadpassen kunnen gebruik maken van de laadpaal zonder restricties.</p>
    </div>
    
    <div class="info-card">
      <h4>🎫 Cube Laadpas</h4>
      <p>Alleen Cube laadpassen kunnen gebruik maken van de laadpaal.</p>
    </div>
    
    <div class="info-card">
      <h4>⚙️ Later Instellen</h4>
      <p>Toegangscontrole wordt later geconfigureerd via het dashboard.</p>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Verrekenen Opties</h4>
    <p>Voor gebruikers die "Verrekenen" hebben gekozen:</p>
  </div>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>💳🎫 Bestaande + Cube Pas</h4>
      <p>Zowel bestaande laadpassen als Cube laadpassen kunnen gebruik maken en worden gefactureerd.</p>
    </div>
    
    <div class="info-card">
      <h4>💳 Alleen Bestaande Pas</h4>
      <p>Alleen bestaande laadpassen kunnen gebruik maken en worden gefactureerd.</p>
    </div>
    
    <div class="info-card">
      <h4>🎫 Alleen Cube Pas</h4>
      <p>Alleen Cube laadpassen kunnen gebruik maken en worden gefactureerd.</p>
    </div>
  </div>
</div>

<div class="step-section" id="betaling">
  <h2>Stap 5: Betalingsgegevens (indien nodig)</h2>
  
  <div class="info-card">
    <h4>Alleen voor Verrekenen</h4>
    <p>Deze stap wordt alleen getoond voor gebruikers die "Verrekenen" hebben gekozen.</p>
  </div>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>IBAN Invoeren</h4>
      <ul>
        <li><strong>Formaat:</strong> IBAN moet geldig formaat hebben (bijv. NL91ABNA0417164300)</li>
        <li><strong>Validatie:</strong> Real-time IBAN formaat validatie</li>
        <li><strong>Lengte:</strong> Tussen 15 en 34 karakters</li>
        <li><strong>Auto-uppercase:</strong> Automatisch omgezet naar hoofdletters</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Tariefcode Selecteren</h4>
      <ul>
        <li><strong>Dropdown:</strong> Selecteer tariefcode uit dropdown</li>
        <li><strong>Gesorteerd:</strong> Tarieven gesorteerd op prijs (oplopend)</li>
        <li><strong>Display Name:</strong> Toont tariefcode met beschrijving</li>
        <li><strong>Vereist:</strong> Tariefcode is verplicht voor verrekenen</li>
      </ul>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Tarief Informatie</h4>
    <p>Een informatieblok toont:</p>
    <ul>
      <li><strong>Uitleg:</strong> Wat tarieven betekenen</li>
      <li><strong>Gebruik:</strong> Hoe tarieven worden toegepast</li>
      <li><strong>Hulp:</strong> Waar hulp te vinden</li>
    </ul>
  </div>
</div>

<div class="step-section" id="voltooiing">
  <h2>Stap 6: Registratie Voltooien</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Voor Vrij Laden</h4>
      <ol>
        <li><strong>Bevestiging:</strong> Overzicht van geselecteerde opties</li>
        <li><strong>Controle:</strong> Controleer of alles correct is</li>
        <li><strong>Voltooien:</strong> Klik op "Registratie Voltooien"</li>
        <li><strong>Verwerking:</strong> Systeem verwerkt de registratie</li>
        <li><strong>Redirect:</strong> Automatische redirect naar login pagina</li>
      </ol>
    </div>
    
    <div class="info-card">
      <h4>Voor Verrekenen</h4>
      <ol>
        <li><strong>Form Submit:</strong> IBAN en tariefcode worden verzonden</li>
        <li><strong>Validatie:</strong> Backend valideert alle gegevens</li>
        <li><strong>Account Aanmaken:</strong> Account wordt aangemaakt met voorkeuren</li>
        <li><strong>Success:</strong> Success bericht wordt getoond</li>
        <li><strong>Redirect:</strong> Automatische redirect naar login pagina</li>
      </ol>
    </div>
  </div>
  
  <div class="info-card">
    <h4>Success Berichten</h4>
    <ul>
      <li><strong>USER_LAADPAS:</strong> "Welkom bij CubeCharging! Je account is geactiveerd."</li>
      <li><strong>Simplified:</strong> "Welkom bij CubeCharging! Je account is geactiveerd."</li>
      <li><strong>Andere Types:</strong> Success bericht met redirect informatie</li>
    </ul>
  </div>
</div>

<div class="content-section" id="gebruikerstypen">
  <h2>Gebruikerstypen</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>USER_LAADPAS</h4>
      <ul>
        <li><strong>Eenvoudige Flow:</strong> Alleen wachtwoord setup</li>
        <li><strong>Geen Opties:</strong> Geen gebruikstype selectie</li>
        <li><strong>Direct Voltooid:</strong> Na wachtwoord wordt account direct geactiveerd</li>
        <li><strong>Geen Progress Steps:</strong> Geen visuele voortgangsindicator</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Simplified Registration</h4>
      <ul>
        <li><strong>Website Launch:</strong> Voor nieuwe website gebruikers</li>
        <li><strong>Eenvoudig:</strong> Alleen wachtwoord setup</li>
        <li><strong>Welkom Bericht:</strong> Speciaal welkom bericht</li>
        <li><strong>Snelle Activering:</strong> Snelle account activering</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Volledige Onboarding</h4>
      <ul>
        <li><strong>Multi-step:</strong> Meerdere stappen met voortgangsindicator</li>
        <li><strong>Gebruikstype:</strong> Keuze tussen vrij laden en verrekenen</li>
        <li><strong>Opties:</strong> Uitgebreide configuratie opties</li>
        <li><strong>Betalingsgegevens:</strong> IBAN en tariefcode vereist (bij verrekenen)</li>
      </ul>
    </div>
  </div>
</div>

<div class="content-section" id="validatie">
  <h2>Validatie & Beveiliging</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Token Beveiliging</h4>
      <ul>
        <li><strong>Unieke Tokens:</strong> Elke registratie heeft unieke token</li>
        <li><strong>Verlopen Check:</strong> Tokens hebben vervaldatum</li>
        <li><strong>Eenmalig Gebruik:</strong> Tokens kunnen niet opnieuw gebruikt worden</li>
        <li><strong>Validatie:</strong> Backend valideert token bij elke stap</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Wachtwoord Validatie</h4>
      <ul>
        <li><strong>Real-time:</strong> Validatie gebeurt tijdens typen</li>
        <li><strong>Visuele Feedback:</strong> Fouten worden direct getoond</li>
        <li><strong>Comprehensive:</strong> Alle vereisten worden gecontroleerd</li>
        <li><strong>Bevestiging:</strong> Controleert of beide wachtwoorden overeenkomen</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>IBAN Validatie</h4>
      <ul>
        <li><strong>Formaat Check:</strong> Controleert IBAN formaat</li>
        <li><strong>Lengte Check:</strong> Controleert minimale en maximale lengte</li>
        <li><strong>Real-time:</strong> Validatie tijdens typen</li>
        <li><strong>Foutmelding:</strong> Duidelijke foutmeldingen bij ongeldige IBAN</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Backend Validatie</h4>
      <ul>
        <li><strong>Dubbele Check:</strong> Backend valideert alle gegevens opnieuw</li>
        <li><strong>Token Check:</strong> Controleert token geldigheid</li>
        <li><strong>Gebruikerstype:</strong> Valideert gebruikerstype</li>
        <li><strong>Data Integriteit:</strong> Controleert data consistentie</li>
      </ul>
    </div>
  </div>
</div>

<div class="content-section">
  <h2>Technische Details</h2>
  
  <div class="info-grid">
    <div class="info-card">
      <h4>Component Structuur</h4>
      <ul>
        <li><strong>Vue 3 Composition API:</strong> Moderne Vue.js implementatie</li>
        <li><strong>Multi-step Form:</strong> Dynamische stap navigatie</li>
        <li><strong>Conditional Rendering:</strong> Verschillende flows per gebruikerstype</li>
        <li><strong>State Management:</strong> Reactieve state voor form data</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>API Endpoints</h4>
      <ul>
        <li><strong>/api/auth/register/check-completion:</strong> Controleert registratie status</li>
        <li><strong>/api/auth/register/validate-token:</strong> Valideert registratie token</li>
        <li><strong>/api/auth/register/get-user-type:</strong> Haalt gebruikerstype op</li>
        <li><strong>/api/auth/register/complete-user-laadpas:</strong> Voltooit USER_LAADPAS registratie</li>
        <li><strong>/api/auth/register/complete-with-preferences:</strong> Voltooit registratie met voorkeuren</li>
        <li><strong>/tariffs/registration:</strong> Haalt beschikbare tarieven op</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Features</h4>
      <ul>
        <li><strong>Progress Indicator:</strong> Visuele voortgangsindicator</li>
        <li><strong>Step Transitions:</strong> Smooth animaties tussen stappen</li>
        <li><strong>Error Handling:</strong> Uitgebreide error handling</li>
        <li><strong>Loading States:</strong> Loading indicators tijdens API calls</li>
        <li><strong>Responsive Design:</strong> Werkt op alle schermformaten</li>
      </ul>
    </div>
    
    <div class="info-card">
      <h4>Internationalisatie</h4>
      <ul>
        <li><strong>i18n Store:</strong> Gebruikt i18n store voor vertalingen</li>
        <li><strong>Nederlandse Standaard:</strong> Standaard Nederlandse teksten</li>
        <li><strong>Dynamische Labels:</strong> Labels passen zich aan per gebruikerstype</li>
        <li><strong>Consistent:</strong> Consistente terminologie door hele flow</li>
      </ul>
    </div>
  </div>
</div>

