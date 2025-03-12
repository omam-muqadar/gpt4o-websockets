## Prerequisites

### Install Python

Ensure you have Python 3.8+ installed:

```sh
python --version
```

If not installed, download from [Python.org](https://www.python.org/).

### Create a Virtual Environment (Recommended)

```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```

### Install Dependencies

Navigate to the project folder:

```sh
cd path/to/repo
```

Install required packages:

```sh
pip install -r requirements.txt
```

## Running the Application

Run the main script:

```sh
python realtime.py
```

This script sets up the audio interface and WebSocket connection to OpenAI.

## Troubleshooting

### Missing Dependencies?

Run:

```sh
pip install -r requirements.txt
```

### Port or WebSocket Issues?

Check if another process is using the required port.

### Permission Issues?

Try running with:

```sh
python realtime.py --verbose
```

### Audio Device Not Found?

Ensure your microphone and speaker are properly set up.
