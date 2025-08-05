# fetch_pikachu.sh

## 🔍 Purpose

This shell script automates the process of making an API request to the [PokéAPI](https://pokeapi.co) to retrieve data for a specific Pokémon — **Pikachu**.

It demonstrates basic shell scripting for API interaction and error handling.

---

## 📦 Features

- Sends a GET request to `https://pokeapi.co/api/v2/pokemon/pikachu`
- Saves the response to a local file: `data.json`
- Logs any request errors with a timestamp to: `errors.txt`

---

## 📁 Files

- `fetch_pikachu.sh` — the shell script
- `data.json` — output file containing the JSON response
- `errors.txt` — log file for errors (if any occur)

---

## 🚀 How to Use

1. Make the script executable:
   ```bash
   chmod +x fetch_pikachu.sh

