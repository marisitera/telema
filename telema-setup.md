---
---
# EDI seadistamine

## Kuidas seada üles ühendus Telema serveriga
Avage **Telema EDI seadistus** ning kiirkaart  **Ühendus.**  
Palun küsige järgnevalt täidetav informatsioon Telema käest:

Väli: |
- |
**API URL** |
**API kanali id** |
**API võti** |

Peale kiirkaardi **Ühendus**  täitmist kasutage funktsiooni **Testi ühendust** kindlustamaks, et ühendus Telemaga on loodud.

## Ettevõtetevaheline dokumendivahetus BC's

Dokumentide saatmiseks avage **Telema EDI seadistus** ning aktiveerige märkeruut **Avalda e-document veebiteenus** - see võimaldab dokumendivahetuse ettevõtete Business Centralite vahel.
Seejärel avage **Kliendid** loendist **Kliendi kaart** ning kiirkaardil Telema EDI valige **Saatmise viis** *BC e-dokumendi veebiteenus*. 
Palun küsige järgnevalt täidetav informatsioon ettevõttelt kellele soovite läbi BC dokumente saata:

Väli: |
- |
**E-dokument veebiteenuse URL** |
**E-document veebiteenuse kasutaja** |
**E-dokument veebiteenuse parool** |

Dokumentide vastuvõtmiseks peate edastama saatjale järgnevad andmed veebiteenuse URLi, kasutaja ning parooli.
Selleks avage **Veebiteenused** ning valige objekti **TED E-Document Web Service** rea pealt **OData V4 URL**. See ongi **E-dokument veebiteenuse URL**.
Seejärel avage **Kasutajad** ning looge kasutaja saatja ettevõttele. Määrake **Kasutajanimi** ning **Veebiteenuse juurdepääsu võti**. Toimingute alt saate määrata kui kaua **Võtme aegumiskuupäeva** või määrata, et **Võti ei aegu kunagi**.


## Kuidas saata ja vastuvõtta e-dokumente

Vaata juhendit:  
[Sissetulevad e-dokumendid](inbound-edocuments)  
[Väljaminevad e-dokumendid](outbound-edocuments)
