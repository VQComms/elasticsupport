NAME = 192.168.1.45:5000/vqcomms/kibana
VERSION = latest

.PHONY: build push

build:
	docker build --no-cache -t $(NAME):$(VERSION) .

push: build
	docker push $(NAME):$(VERSION)