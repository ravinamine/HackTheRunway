FROM alpine
RUN apk update && apk upgrade --available
RUN apk add --update --no-cache g++ python3
RUN python3 -m ensurepip
RUN pip3 install --no-cache --upgrade pip setuptools 
CMD ["echo", "Good luck and have fun with Hack the Runway!"]
