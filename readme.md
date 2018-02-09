# Fritzing

Ang aplikasyon na Fritzing ay isang EDA software (Electronic Design Automation) na madaling mapasok, at sakto sa kailangan ng mangagawa o mga hobbyist. Nagbibigay ito ng kakaibang malabuhay na "breadboard", at mga parti sa library na may mga common na high-level na bahagi. Fritzing ay nagpapadali sa komikasyon tungkol sa circuits, pati ang pag lipat nito sa PCB layouts na handa na sa produksyon. Ito ay sikat lalong lalo na sa Arduino at Rasberry Pi users, at malawakang ginagamit sa edukasyon at malikhaing isipan ng mga tao.

* Para sa iba pang impormasyon tungkol sa Fritzing at ang ibapa nitong kaparehong gawain, bisitahin ang [http://fritzing.org](http://fritzing.org). Dyan pwede nyo ring ma e[download](http://fritzing.org/download) ang mga bagong labas sa lahat ng platform nito at makahingi ng tulong sa pagsimula.

* Sa pag report ng problema o pagbigay ng suhesyon, gamitin ang [issue tracker](https://github.com/fritzing/fritzing-app/issues) or  ang [user forum](http://forum.fritzing.org)

* Kung gusto mong makatulong sa development, paki tignan ang [developer instructions](https://github.com/fritzing/fritzing-app/wiki). Sakop nito ang impormayonkung paano e compile at pa takbuhin ang Fritzing app sa kunting hakbang.

# Folder Structure

* **bins** - Part bins (.fzb, aka part libraries) ay mga koleksyon ng mga parte, lalong-lalo na ang "core" parts bin, at vendorspecific na koleksyon.

* **help** - End-user documentation kasama sa app. Ito ay kakailangang ibalik sa sa website.

* **parts** - Lahat ng kahulugan ng mga parte, kasama ang meta data(.fzp) at graphics (.svg), pati ang ibang uitility tools. Ito ay inilalagay sa ibang repository sa [https://github.com/fritzing/fritzing-parts](http://github.com/fritzing/fritzing-parts) at tanging link lng dito.

* **pri** - Submodule na depinisyon ng Qt

* **resources** - Binaries at depinisyon na hindi dapat galawin ng users, katulad ng fonts, imahe, special na parte, etc.
* **sketches** - Halimbawa circuits/sketches shipped kasama ang application

* **src** - Logic ng application!

* **tools** - Utility tools para pangpapalabas, konbersyon ng mga parte, etc.

* **translations** - Translasyon ng mga lingwahe.


# Credits

Ang Fritzing app ay pinapanatili ng mga Friends-of-Fritzing e.V., na mga non-profit na foundation na naka base sa Berlin, Germany. Ang proyekto ay lumago labas ang estado-pundo ng proyekto ng pananaliksik sa [Interaction Design Lab](http://idl.fh-potsdam.de) at [Potsdam University of Applied Sciences](http://fh-potsdam.de).


Ang core team ay binubuo nila Prof. Reto Wettach, André Knörig, Jonathan Cohen, at Stefan Hermann. Maraming [ibang klaseng tao](http://fritzing.org/about/people/) na nag ambag dito sa buong taon.

Ang Fritzing app ay sinulat sa taas ng [Qt cross-platform framework](http://qt-project.org).

# Licensing

Ang pinagmulan ng code ng Fritzing ay lisinsyado sa ilalim ng GNU GPL v3, ang dokumentasyon at ang parte ng designs sa ilalim 
ng Creative Commons Attribution-ShareALike 3.0 Unported. Ang buong teksto ng mga lesinsyang ito ay kasama dito sa download.


Nagkakahulugan ito na pwedeng gumawa ng iyong sariling baryasyon ng Fritzing, hanggat kami ay iyong ekrinidit at maipablish sa ilalim ng GPL.Katulad ng, pwede mong ma e publish ulit ang mga dokyumentasyon, hanggat kami ay iyong e credit, at e publish ito sa ilalim ng kaparehong lisensya. Pwede mong e publish ang circuits at mga diagrams na iyong ginawa sa Fritzing at gumagamit ng aming mga graphics, ulit hanggat kamiy iyong e credit at mag publish ng iyong mga gawa sa kaparehong lisensya. Ang credit ay maaring kasing simple lng kagaya ng "itong imahe ay gawa mula sa Fritzing".

Tignan ang [our FAQs](http://fritzing.org/faq/) para sa iba pang detalye sa pagpapa lesinsya.

