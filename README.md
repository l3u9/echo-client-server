# echo-client-server




server:
	socket() -> setsockopt() -> bind() -> listen() -> accept() -> recv()
client:
	socket() -> connect() -> {recv() ["echo mode"]} -> send()
			


