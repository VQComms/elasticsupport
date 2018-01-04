NAME = 192.168.1.45:5000/vqcomms/elasticsearch
VERSION = latest

.PHONY: build push

build:
	docker build -t $(NAME):$(VERSION) .

push: build
	docker push $(NAME):$(VERSION)
