.PHONY: up
up: prometheus.yml
	docker compose up -d

.PHONY: down
down:
	docker compose down

prometheus.yml: prometheus.example.yml
	cp $< $@
