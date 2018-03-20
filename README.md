Celkove hodnotenie:
+ obsahovo strohe, ale vystizne
- biznis procesy su pomerne plytke, treba ich viac rozpracovat, aby ste mali na com stavat v nasledujucich etapach

### hotovo
##/ možno hotovo
#// pracuje sa
/// 
/*/ 
*** chcem vedieť

Zapracovat do revizie:
* Slovnik pojmov - nemame ziadne domenove pojmy? #// 

* BP01
    * namiesto by som ako dispecer zaznacil, na ktore zastavky treba osadit oznamy
    * a potom by sa zaznamenalo, kedy dispecer s pomocnikom pojdu osadit oznamy (resp. vyslu inych na osadenie) /*/
* BP02
  * koho revizor kontroluje? *** / Implementuj pasažiera 

* BP03
  * kontrolu vozidiel a trate nemozno miesat - naraz sa vykona jedno a naraz druhe*** // rozdelit tu kontrolu 
  * "trat" - je potrebne ozrejmit, co sa tym konkretne mysli (trolejove vedenie, trakcne vedenie, ...) ##/ 

* BP04
  * v pripade casteho pretazenia linky (presahuje kapacitu vozidla) je potrebne posilnit spoje alebo napr. v pripade autobusov vymenit "kratke" autobusy za klbove *** // modifikacia liniek a zadefinovať linku 
  * zaroven sa pretazenie tyka aj casti dna a casti trasy, nielen za cely den a celu trasu alebo priemerne za mesiac (napr. v Bratislave autobus 39 - kedy a v akych usekoch je natrieskany studentami, kedy je poloprazdny) ***
  * Vypocitanie uspory - nemusi byt iba pre zrusenie linky, moze byt aj pre upravu intervalov linky #//
  * Kontrola rentability - prilis siroke, uz potom v rozhodovacom uzle sa rozhoduje iba podla vytazenosti -> lepsi nazov, alebo rozsirit aktivitu, ak do rozhodovania vstupuju aj ine faktory ako vytazenost #//
  * Navrh vedeniu - ludia vo vedeni asi budu vystupovat ako akteri, aktivita teda nebude patrit pod Dispecera #//

* BP05
  * treba vykonat vyjazd a ku kazdej zastavke fyzicky prist #//
  * zaroven je treba aj udrziavat poriadok na zastavkach (vyprazdnit kose, ... - podla zadania) ????? //pripisat ze ide o externu firmu.
  * ako je uz v opise uvedene, nejde iba o cestovne poriadky, ale aj o vyluky - pri cestovnych poriadkoch robime aktualizaciu (nahradime stare novymi), pri vylukach pridavame oznam, pripadne potom treba este oznam odstranit, ak je uz neaktualny #//

Dalsie pripomienky (nemusite zapracovat do revizie, nebude sa ratat do hodnotenia za reviziu):
* formatovanie: po generovani .docx suboru treba urobit niekolko manualnych uprav: #//
  * nadpis sekcie nech nie je na poslednom riadku strany #//
  * este nevyplnene sekcie odstranit (bude sa tykat odovzdania 2. etapy) #//
* v dokumente chybaju zapisy z predoslych tyzdnov, urcite ste nejake mali, aj nahravku ste tusim raz robili (prepis ale, samozrejme, robit nemusite) #//
* zadanie ma ine pismo ###
* uvod v 1 - "specifikacia a biznis modelovanie" - budete specifikovat poziadavky na informacny system dopravneho podniku, a robite biznis analyzu dopravneho podniku #//
* 1.1 - robite specifikaciu softverovych poziadaviek, nie specifikaciu softveru (= navrh softveru) #//
* uvod do 2 - mal by opisovat problemovu oblast, vy tu opisujete funkcionalitu -> viete to presunut do 2.2/2.3 alebo odstranit #//
* 2.1
  * ciel 1 - samotna automatizacia nie je ciel, ale predstavuje funkcionalitu - aky uzitok nam prinesie? to je cielom #//
  * ciel 7 je pomerne abstraktny a "prispievaju" k nemu predosle #//
* 2.3
  * 6 - ako suvisi responzivny dizajn a zvlastne prihlasenie pre administratorov? #//
  * objasnit 7 - co je univerzalnost? platformova nezavislost? treba nam to pre nas system? my mame na nasich pocitacoch Windows 8.1, staci nam Windows #//
* 3
  * neuvadzat prazdne sekcie - ciele, udalosti, tabulky s operaciami a atributmi, ... ***
  * chyba opis k BP modelu #//
* BP model
  * BP01
    * Analyza rentability je resource? information?; navyse ma nestandardny tvar ***
    * nema vystup? ***
  * "(from Akteri)" a dalsie viete v EA schovat, model bude prehladnejsi ***
  * "Zdroje::" netreba uvadzat, malo by sa dat v EA schovat ***
  * BP05 - ciel "Nove poriadky" - skor "aktualizovane" #//
* pozor na gramatiku - chybajuce ciarky, dlzne, ... *****
* strohe opisy BP #//
* akvitity standardne zacinaju slovesnym podstatnym menom, niekde ich mate formulovane inak (napr. BP01) #//
* ukoncovacie uzly v diagrame akvitit su standardne formulovane v trpnom rode (napr. "Linka je zrusena") ##/
* BP02 - preco je swimlane s Revizorom inak zafarbeny a formatovany? *****
