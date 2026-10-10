# MC_Server
Kaip prisijungti prie modinto mc serverio
## 📥 Kaip atsisiųsti ir paruošti SKlauncher

1. **Atidarykite atsisiuntimo puslapį:**
   Eikite į oficialų SKlauncher puslapį, skirtą Windows sistemai: [SKlauncher](https://next.skmedix.pl/downloads/windows).
   <img width="1914" height="1077" alt="Screenshot_1" src="https://github.com/user-attachments/assets/f90092f4-857c-402e-8174-56aee1dd9bbc" />

3. **Atsisiųskite paleidėją:**
   Puslapyje paspauskite atsisiuntimo mygtuką ir išsaugokite `SKlauncher.exe` failą patogioje kompiuterio vietoje (pvz., darbalaukyje). Šios programos nereikia atskirai instaliuoti – ji veikia iškart.

4. **Pasirūpinkite Java (jei reikia):**
   Jei bandant atidaryti programą niekas nevyksta, įsitikinkite, kad kompiuteryje įdiegta Java (Minecraft 1.17+ versijoms rekomenduojama **Java 17** arba **Java 21**).

5. **Paleiskite programą:**
   Atidarykite atsisiųstą `SKlauncher.exe` failą.

6. **Prisijunkite „SKlauncher“ režimu:**
   Atsidarius paleidėjui, pasirinkite **SKlauncher**  režimą. Įveskite norimą žaidėjo vardą, kuris bus matomas mūsų serveryje, ir spauskite **Log In** / **Play**, kad patektumėte į pagrindinį meniu.
   <img width="1919" height="1079" alt="Screenshot_2" src="https://github.com/user-attachments/assets/81da6a20-5fe9-4348-a28c-d01f5de7810f" />
   <img width="1919" height="1079" alt="Screenshot_5" src="https://github.com/user-attachments/assets/954ee32e-61f2-48f0-9fff-46e93161438f" />

## 🔒 2. WireGuard VPN Aktyvavimas

Serveris veikia visiškai uždaroje aplinkoje. Be šio žingsnio prie serverio prisijungti nepavyks.
1.  Nueikite į šia nuoroda [Wireguard](https://www.wireguard.com/install/)  ir atsisiuskite 
2. Atidarykite **WireGuard** programą savo kompiuteryje.
33. Spauskite mygtuką **Import tunnel(s) from file** ir pasirinkite savo asmeninį `.conf` failą (kurį rasite [šioje repozitorijoje](https://github.com/MeskisOp/MC_Server/blob/main/temp.conf)) ijejus i ją paspauskite Ctrl+Shift+S kad atsiustumete faila.
4. Kairėje pusėje atsiras naujas tunelis. Pažymėkite jį ir spauskite **Activate**.
5. Tunelio būsena pasikeis į *Active* – jūs sėkmingai prisijungėte prie mūsų privataus tinklo.
