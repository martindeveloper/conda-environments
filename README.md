# About
Various conda `environment.yml` config files for things like data science, ML, etc.
Environment files are trying to be as much specific as they can with channel and full version.

# Platforms
Following platforms are used and tested with environment config files:
- macOS 12 (Intel based)

# Usage
Simply call conda CLI to create environment based on target yaml config.

```bash
conda env create -f data-science/environment.yml
```
