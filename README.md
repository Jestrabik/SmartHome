# Postup práce – Chytrá domácnost s Home Assistant

## 16. 10. 2025
- Prvotní analýza řešení chytrých domácností (Home Assistant, HomeKit, Tuya, Philips Hue).  
- Studium diskuzních fór, komunitních projektů a ukázkových implementací.  
- Sepsání požadavků na systém – vstupní a výstupní zařízení, očekávané funkce.  

---

## 18. 10. 2025
- Příprava podkladů pro maturitní projekt.  
- Definování hlavního cíle projektu (vytvoření jednoduché chytré domácnosti s Home Assistant).  
- Návrh minimálního funkčního řešení – ovládání světla.  
- Výběr hlavní platformy: **Home Assistant OS**.  
- Rozhodnutí o využití vlastního mini PC.  

---

## 23. 10. 2025
- Účast na přednášce o SmartHome technologiích v Brně(Apple HomeKit, Home Assistant, Zigbee).  
- Doplnění znalostí o principech automatizace, lokálním řízení a komunikačních protokolech.  
- Výběr vhodného komunikačního standardu – **Zigbee** pro připojení zařízení.  

---

## 30. 10. 2025
- Zakoupení **mini PC** (parametry – Intel NUC, CPU i3-6100, 8 GB RAM, 256 GB SSD).  
- Instalace operačního systému **Ubuntu**.  
- Příprava prostředí pro instalaci **Home Assistant OS** (nastavení sítě, aktualizace systému).  

---

## 1.11.–3. 11. 2025
- Instalace **Home Assistant OS**.
- [https://ubuntu.com/download/desktop]
- [https://www.home-assistant.io/installation/generic-x86-64]
- [https://github.com/home-assistant/operating-system/releases/download/16.2/haos_generic-x86-64-16.2.img.xz]  
- Základní konfigurace systému a vytvoření uživatelského účtu.  
- Nastavení **Samba sdílení** pro přístup ke konfiguračním souborům z Macu.
  <img width="514" height="317" alt="image" src="https://github.com/user-attachments/assets/5b79ddba-6256-4a45-9cca-e9dff7189cd8" />

 
- Instalace a konfigurace **Zigbee donglu Sonoff**:
  - Připojení donglu přes USB.  
  - Instalace integrace **ZHA** .  
  - Ověření funkční komunikace mezi donglem a Home Assistantem.  
- Párování první **chytré žárovky (Zigbee, stmívatelná, RGB)**.  
- Test ovládání jasu a změny barvy přes rozhraní Home Assistant.  
- Ověření správné funkce integrace a reakce na příkazy.
- [https://github.com/claytonjn/hass-circadian_lighting]

- Aktivace integrace **HomeKit Bridge** v Home Assistantu.  
- Nastavení **názvu a oblasti bridge** („Pokoj – Home Assistant“).  
- Vygenerování **HomeKit párovacího kódu**.  
- Spuštění **Home aplikace na iPhonu** a přidání nového zařízení pomocí QR kódu.  
- Úspěšné spárování Home Assistantu s Apple HomeKit.  
- Ověření přenosu zařízení – chytrá žárovka dostupná v aplikaci **Domácnost**.  
- Test obousměrné komunikace (ovládání světla z iPhonu i z HA rozhraní).  


---

## Shrnutí fáze příprav
- Dokončena úvodní analýza a výběr technologií.  
- Vytvořeny podklady a struktura projektu.  
- Připraveno hardware a software prostředí (mini PC, Ubuntu, HA OS).  
- Nastaven přístup přes síť (Samba).  
- Zprovozněn Zigbee koordinátor (Sonoff dongle).  
- Úspěšně připojeno první zařízení – chytrá žárovka.  
