# Nexas

Nexas ni Wireless Charging System inayofuatilia hali ya betri kwa background, kutuma arifa ikifika threshold, na kuanzisha auto-recharge kwa usalama. Mtumiaji hudhibiti vibration/sound, lugha, thresholds, na profiles. Balance na historia huhifadhiwa, huku quick actions zikisaidia recharge kwa haraka na salama.

## Vipengele
- **Background monitoring:** Ufuatiliaji endelevu wa battery bila kuathiri utendaji.
- **Arifa mahiri:** Notifications za threshold zenye vibration/sound kulingana na chaguo.
- **Auto-recharge:** Kuwasha chaji kiotomatiki kulingana na profile na sheria za usalama.
- **Profiles & lugha:** Tumia profiles tofauti na mabadiliko ya lugha.
- **Usalama wa data:** Hifadhi ya balance na history yenye encryption/local-first.
- **Quick actions:** Vitendo vya haraka (Start/Stop/Boost) vilivyo salama.

## Mahitaji
- **OS:** Android 13+ au mfumo unaotumia SDK ya Nexas
- **Ruhusa:** Battery stats, notifications, background service
- **Mtandao (hiari):** Kwa sync ya history/balance endapo imewezeshwa

## Usakinishaji
1. **Pakua/Clone:** `git clone https://github.com/<user>/Nexas.git`
2. **Jenga:** `./gradlew assembleRelease`
3. **Sanidi ruhusa:** Ruhusu notifications na background
4. **Washa huduma:** Fungua app, chagua profile, weka threshold

## Matumizi
- **Kuweka threshold:** Settings → Battery → Threshold (mf: 20%/80%)
- **Arifa:** Washa **vibration/sound** kulingana na mazingira yako
- **Profiles:** Chagua `Home`, `Travel`, au `Night` kwa tabia tofauti
- **Quick actions:** Tumia `Start`, `Pause`, `Boost` kuendesha chaji kwa haraka

## Usalama na faragha
- **Hifadhi ya ndani:** Balance na history huhifadhiwa kifaa chako
- **Uwazi:** Hakuna data inayotumwa bila ruhusa yako
- **Udhibiti:** Zima/washe auto-recharge na notifications kwa kila profile

## Leseni
Huu mradi unasambazwa chini ya leseni **MIT**.

## Mchango
- **Issues/PRs:** Karibu utoe maoni au maboresho
- **Roadmap fupi:** v1.1—Battery heuristics, v1.2—Multi-device sync

## Chaguzi za Configuration

| Chaguo           | Maelezo                                      | Mfano            |
|------------------|-----------------------------------------------|------------------|
| `low_threshold`  | Asilimia ya chini ya betri ya kutuma arifa    | 20               |
| `high_threshold` | Asilimia ya juu ya betri ya kusimamisha chaji | 80               |
| `profile`        | Seti ya kanuni za chaji/notification          | `Home`, `Travel` |
| `language`       | Lugha ya UI/notifications                     | `sw`, `en`       |
| `vibration`      | Kuwasha/kuzima mtikisiko                      | `true/false`     |
| `sound`          | Kiwango au aina ya sauti                     | `chime`, `silent`|
| `auto_recharge`  | Kuwasha/kuzima chaji kiotomatiki             | `true/false`     |
