# Server for `ReadThis`

## How to start using?

1. Download dependencies
``` bash
conda create -n readthis-server python=3.11
conda activate readthis-server
conda install ipykernel
pip install -r requirements.txt
```

2. load up server
``` bash
uvicorn server:app
```

## `GET/POST` method
