# Vaja1-ADC-single-conversion-Nucleo

V Pinout pogledu si oglejte prerazporeditev PIN-ov mikroprocesorja za vhodne in izhodne enote. Zelena LED je priključena na __PA5__ pin, MODRA pa na __NI NA PINOUTU___ pin. Kaj je pa priključeno na pin PA0? ________modra tipka PRI MENI PC13____________________. 

V Analog razdelku levo od sheme mikroprocesorja ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica? ______3(ADC1,2,3)________.
 
Izbrani ADC pretvornik(i) ima(jo) oznako s trikotnikom. Kaj to pomeni? ________________________DA SO ZASEDENI ___ 

Kaj morate storiti, da razrešite to omejitev? Opišite in jo odpravite. 
PA2(USART2_TX),
PA3(USART2_RX),
PA5(ZELENA LED)
VSE POSTAVIMO NA RESET_STATE

Razširite (kliknite) razdelek ADC3. Koliko je vseh vhodnih kanalov (seštejte oznake INxx) ? 
______3___ 

Izberite (obkljukajte) poljuben prosti analogni kanal oz.vhod, ki ga boste porabili za branje vrednosti iz potenciometra. Izbrati morate Single-ended princip zajemanja analogne vrednosti. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo.
Kaj se izpiše poleg pina? ___ADC3_IN1______.
Kateri pin je to? _____PC0______. 

i.	Pod Configuration  ADC enote gumb v Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Preglejte, kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti? 
a.	6, od 0 do 63, 
b.	10, od 0 do 1023, 
c.	12, od 0 do 4095.
 


