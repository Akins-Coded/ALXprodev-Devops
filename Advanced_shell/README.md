# 🐚 Pokémon Data Automation — Shell Script Suite

This project automates the process of retrieving and processing Pokémon data from the [PokéAPI](https://pokeapi.co) using Bash shell scripts. It demonstrates practical Bash scripting skills such as API interaction, JSON parsing, error handling, retry logic, CSV generation, and parallel execution.

---

## 📁 Project Structure

```bash
.
├── fetch_pikachu.sh              # Task 1: Fetch data for Pikachu
├── fetch_multiple_pokemon.sh     # Task 2: Fetch multiple Pokémon with error handling
├── pokemon_report.sh             # Task 3: Generate a CSV summary
├── fetch_with_retry.sh           # Task 4: Retry logic on API failure
├── fetch_parallel_pokemon.sh     # Task 5: Parallel data fetching
├── pokemon_data/                 # Output JSON files
├── pokemon_report.csv            # Output report
├── errors.txt                    # Logs of failed API requests
└── README.md                     # Documentation

shell script automates the process of making an API request to the [PokéAPI](https://pokeapi.co) to retrieve data for a specific Pokémon — **Pikachu**.

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

