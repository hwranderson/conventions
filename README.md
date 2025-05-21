# Conventions

A CLI tool to search for conference talks.

## Installation

```bash
# Install from source
git clone https://github.com/yourusername/conventions.git
cd conventions
pip install -e .
```

## Usage

Search for talks by keyword:

```bash
# Search for SLAM talks in ICRA 2025 (default)
conventions search slam

# Search in a specific conference
conventions search navigation --conference ICRA25

# Limit results
conventions search robotics --max-results 10
```

List available conferences:

```bash
conventions list
```

Get information about a specific conference:

```bash
conventions info ICRA25
```

Clear the cache:

```bash
# Clear cache for a specific conference
conventions clear-cache ICRA25

# Clear all cached data
conventions clear-cache --all
```

## Supported Conferences

- ICRA25 (IEEE International Conference on Robotics and Automation 2025)

## Development

```bash
# Clone the repository
git clone https://github.com/yourusername/conventions.git
cd conventions

# Install in development mode
pip install -e .

# Run the CLI
conventions search slam
```
