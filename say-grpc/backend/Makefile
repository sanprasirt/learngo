build:
	GOOS=linux go build -o app
	# docker build -t ttyvip/say .
	docker build -t gcr.io/gcps-164905/say .
	rm -f app
push:
	docker push -- gcr.io/gcps-164905/say