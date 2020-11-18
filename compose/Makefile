heimdall-nginx-cp:
	docker cp nginx.default.conf heimdall:/config/nginx/site-confs/default

heimdall-nginx-reload:
	docker exec heimdall nginx -s reload -c /config/nginx/nginx.conf
