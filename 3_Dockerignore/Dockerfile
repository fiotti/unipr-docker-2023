FROM ubuntu
WORKDIR /app

# copia tutti i file dalla cartella del dockerfile "." alla workdir "."
COPY . .

# apre un prompt che chiede solo di premere un tasto per uscire
ENTRYPOINT ["bash", "-c", "read -n1 -rsp $'Press any key to close...\n'"]
