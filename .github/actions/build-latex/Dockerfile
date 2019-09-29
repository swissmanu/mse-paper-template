# thx https://github.com/tianon/dockerfiles/blob/master/latex/Dockerfile

FROM debian:buster-slim

RUN apt-get update && apt-get install -y \
		biber \
		latexmk \
		make \
		texlive-full \
	&& rm -rf /var/lib/apt/lists/*