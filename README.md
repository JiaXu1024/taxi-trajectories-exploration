# taxi-trajectories-exploration

### Getting Started

Make sure you have:

- `docker`
- `docker-compose`

Get the [dataset](https://www.microsoft.com/en-us/research/publication/t-drive-trajectory-data-sample/) and extract into `data/`. You should have these directories:

```
.
├── data
│   └── taxi_log_2008_by_id
└── notebook
```

Bring the container to life:

```sh
docker-compose up
```

Open [http://localhost:8888](http://localhost:8888) in your browser and look for the Jupyter notebook in `notebook/`.