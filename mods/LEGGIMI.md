# Cartella Mod

Metti qui i file `.jar` delle mod da includere nella build del launcher.

Queste mod verranno copiate automaticamente nella cartella `mods` di Minecraft
di ogni utente al primo avvio (o quando mancano).

Esempi:
- `fabric-api-0.91.0+1.20.4.jar`
- `sodium-fabric-0.5.8+mc1.20.4.jar`
- `iris-1.7.0+mc1.20.4.jar`
- `your-custom-mod.jar`

## Aggiornamenti da remoto

Per aggiornare le mod senza ricostruire il launcher, usa il file `mods.json`
nel tuo repository GitHub. Il launcher controlla le versioni ad ogni avvio
e scarica automaticamente le nuove versioni.
