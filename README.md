# Asporti-Piccadilly
Web app for managing Piccadilly takeaway order readiness.

## Installazione rapida

1. Scaricare l'ultima versione da **Releases**
2. Scaricare `Asporti.zip`
3. Estrarre lo ZIP direttamente in `C:\`
4. Deve esistere questa cartella:

C:\asporti

5. Aprire PowerShell come Amministratore
6. Eseguire:

Set-ExecutionPolicy Bypass -Scope Process -Force

C:\asporti\scripts\setup_tasks.ps1

7. Verificare:

http://localhost:3000/health  
http://localhost:3000/status

## Link utili

Bar:

http://IP_SERVER:3000/bar

Cucina:

http://IP_SERVER:3000/kitchen

Status:

http://IP_SERVER:3000/status

Con Tailscale usare l'IP Tailscale del server:

http://IP_TAILSCALE_SERVER:3000/bar  
http://IP_TAILSCALE_SERVER:3000/kitchen
