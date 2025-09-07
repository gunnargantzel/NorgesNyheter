Azure Web App – Zip Deploy (Minimal Kiosk Wrapper)

Deploy i Azure Portal:
1) Gå til din App Service → Deployment Center → Zip Deploy → last opp denne ZIP-filen.

Deploy via Azure CLI:
  az webapp deploy --resource-group <RG> --name <APP_NAME> --src-path kiosk_minimal.zip --type zip

Bruk på iPad:
- Åpne URL-en til din Web App i Safari → Share → Add to Home Screen.
- Aktiver Guided Access for kioskmodus.
