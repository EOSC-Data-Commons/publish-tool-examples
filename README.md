# publish-tool-example

A collection of Python Jupyter notebook examples demonstrating how to interact
with the [EOSC Data Commons](https://eosc-portal.eu) publish tool – from
setting up your environment to searching for datasets and publishing your own.

## Notebooks

| Notebook | Description |
|---|---|
| [01_getting_started.ipynb](notebooks/01_getting_started.ipynb) | Environment setup, credential configuration, and connectivity check |
| [02_data_access.ipynb](notebooks/02_data_access.ipynb) | Searching the catalogue, fetching metadata, and downloading files |
| [03_data_publishing.ipynb](notebooks/03_data_publishing.ipynb) | Preparing, packaging, uploading, and publishing a dataset |

## Getting Started

### Prerequisites

- Python 3.8 or higher
- An EOSC account with API access

### Installation

```bash
# Clone the repository
git clone https://github.com/EOSC-Data-Commons/publish-tool-example.git
cd publish-tool-example

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter lab
```

### Configuration

Set the following environment variables before running the notebooks:

```bash
export EOSC_API_TOKEN="your-api-token-here"
export EOSC_API_BASE_URL="https://api.eosc-portal.eu"   # optional, this is the default
```

## Repository Structure

```
publish-tool-example/
├── notebooks/
│   ├── 01_getting_started.ipynb
│   ├── 02_data_access.ipynb
│   └── 03_data_publishing.ipynb
├── requirements.txt
└── README.md
```

## License

See [LICENSE](LICENSE) for details.