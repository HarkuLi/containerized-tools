# Prometheus

Used image:
[prom/prometheus](https://hub.docker.com/r/prom/prometheus)

## Get Started

1.  Generate the config file.

    ```bash
    make prometheus.yml
    ```

2.  Edit `prometheus.yml` if necessary.

3.  Run Prometheus.

    ```bash
    make up
    ```

4.  Access Prometheus at [127.0.0.1:9090](127.0.0.1:9090).

5.  Stop Prometheus.

    ```bash
    make down
    ```
