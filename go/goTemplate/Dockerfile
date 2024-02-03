FROM --platform=linux/amd64 golang:1.22rc2-bookworm
EXPOSE 5090
COPY src/ /home
WORKDIR /home
RUN go mod init GoServiceVulnToSSTI
RUN go build -o server
CMD ["./server"]