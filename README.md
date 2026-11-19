# Seatback IFE: airline looks

Airline packs for the Seatback IFE mod for Microsoft Flight Simulator (iniBuilds A350 and PMDG 777-300ER).
The mod's installer reads this repository: **Check GitHub for new airlines** downloads new and updated packs,
and you choose which airlines go onto the seat screens.

Each folder under `airlines/` is one airline, named by its ICAO code:

- `theme.json`: name, codes, language, screen colours (accent, a night ground of five shades, text greys),
  the name of the airline's entertainment system, its greeting, and cabin light colours where known.
- `logo.png`: the logo shown on the screens.

`catalog.json` lists every pack with its version and the size and SHA-1 of each file. The installer checks every
download against it.

This is a free fan project, not affiliated with any airline. Airline names and logos belong to their owners.
