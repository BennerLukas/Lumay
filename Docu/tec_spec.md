# Technische Spezifikation


## verwendete Technologien
- Wordpress
    - WooCommerce (WC)
    - WCFM (MultiVendor - Frontend Marketplace)
- StoreFront Template für WC


## Struktur

## Datenmodell
- MySQL DB für Wordpress
    - Nutzer
        - Admin
        - Kunde
        - Vendor ("Einkäufer")
    - Produkt

## Prozesse
- Registrieren
- Anmelden
- In Warenkorb
- Suchen
- Produkt anschauen
- Warenkorb anschauen
- Kaufen / Bestellen
- Produkt hinzufügen
- Blog Beitrag erstellen (von Admins)

## Schnittstellen
- Möglich:
    - direkt auf MySQL
    - Google Analytics
    - Matomo
    - Export in CSV o.ä.

- Sinnvoll:
    - direkt MySQL -> bulk add products?

## Komponenten
- Rechtliche Seiten
- Blog
- Landing Page
- Shop + Produktkatalog
- Warenkorb + Bestellen
- Nutzermanagement
