# LeftOver
App zur Reduktion von Lebensmittelverschwendung mit Rezept Vorschlaegen und Restposten Map.

## Ziel
Zeigt was aus vorhandenen Zutaten gekocht werden kann und listet lokale Restposten.

## Features
* Vorratsliste
* Rezept Generator
* Kartenansicht mit Shops
* Teilen von Paketen in der Nachbarschaft

## Tech Stack
* Flutter App
* Supabase Auth DB Storage
* Functions fuer Rezepte
* Optional Open Food Facts

## Kritische Packages
* supabase flutter
* dio
* freezed json serializable
* geolocator
* google maps flutter

## Env Variablen
* SUPABASE_URL
* SUPABASE_ANON_KEY

## Datenmodell
* user pantry item recipe deal

## Setup
* flutter pub get
* flutter run

## Tests
* Unit fuer Rezept Engine

## CI
* Flutter analyze test build

## Security
* Row Level Security in Supabase

## Roadmap
* Scannen von Barcodes
* Coop Migros API falls zugaenglich

## Lizenz
GPLv3
