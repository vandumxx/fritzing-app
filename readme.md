# Fritzing

The Fritzing application is an Electronic Design Automation software with a low entry barrier, suited for the needs of makers and hobbyists. It offers a unique real-life "breadboard" view, and a parts library with many commonly used high-level components. Fritzing makes it very easy to communicate about circuits, as well as to turn them into PCB layouts ready for production. It is particularly popular among Arduino and Raspberry Pi users, and is widely used in education and creative tinkering.

Ang Fritzing nga aplikasyon kay usa ka Electronic Design Automation software na pwede ra makasud ug sayun, mas maayo para sa manghimuay ug mga naglingawlingaw ra. Naghatag ni ug lahi nga murag tinuod nga "breadboard" sa talan-awon, ug ang parts libray nga adunay daghang nindot ug maayung mga components. Fritzing naghatag ug kasayun sa pakig sinabot sa circuit, ug ang pagbalhin niini sa PCB layout nga andam na sa produksyon. Kini kay sikat na sa Arduino ug sa Raspberry Pi na manggamitay, ug halapad na ang nigamit niini sa para sa edukasyon ug sa mamugnaong pag hunahuna.

* For more information on Fritzing and its related activities, visit [http://fritzing.org](http://fritzing.org). There you can also [download](http://fritzing.org/download) the latest releases for all platforms and get help on getting started.

* Para sa uban pang impormasyon bahin sa Fritzing ug sa uban niining mga kalihokan, bisitaha ang [http://fritzing.org](http://fritzing.org). Diri usab ika maka [download](http://fritzing.org/download) sa bag-ong plataporma ug mga tabang sa pag sugod.

* To report a problem or suggest improvements, use the [issue tracker](https://github.com/fritzing/fritzing-app/issues) or the [user forum](http://forum.fritzing.org)

* Para sa pag report ug problema o pag hatag ug suhesyon para sa pag-uswag, gamita ang [issue tracker](https://github.com/fritzing/fritzing-app/issues) or the [user forum](http://forum.fritzing.org)

* If you would like to help with the development, please take a look at the [developer instructions](https://github.com/fritzing/fritzing-app/wiki). This includes information about how to compile and run the Fritzing app in a few steps.

* Kung ganahan ka makatabang sa pagpalambo, palihug tan-aw sa [developer instructions](https://github.com/fritzing/fritzing-app/wiki). Aduna pod diri ang mga impormasyon bahin sa kung unsaon pag han-ay ug pag padagan sa Fritzing app sa kadiyot rang paagi.

# Folder Structure

* **bins** - Part bins (.fzb, aka part libraries) are collections of parts, most importantly the "core" parts bin, and vendor-specific collections.

* **bins** - Part bins (.fzb, aka part libraries) kay mga koleksyon sa mga parte, labi na kadtong "core" nga parts bin, ug vendor-specific na mga koleksyon.

* **help** - End-user documentation included with the app. This should really be moved back to the website.

* **help** - Pagkahuman-documentason sa nag gamit kauban sa app. Kini kinahanglan gayud nga ma balhin sa website.

* **parts** - All the part definitions, including meta data (.fzp) and graphics (.svg), as well as some utility tools. They are kept in a separate repository at [https://github.com/fritzing/fritzing-parts](http://github.com/fritzing/fritzing-parts) and only linked from here.

* **parts** - Tanang part definitions, kauban ang meta data (.fzp) ug fraphics (.svg), ug ang mga utility tools. Kini kay gihipos lahi sa repository didto sa [https://github.com/fritzing/fritzing-parts](http://github.com/fritzing/fritzing-parts) ug na link ra diri.

* **pri** - Submodule definitions for Qt

* **pri** - Depenasyon sa submodule para sa Qt

* **resources** - Binaries and definitions that are supposed to not be touched by users, such as fonts, images, special parts, etc.

* **resources** - Binaries ug depenasyon na kinahanglang dili hilabtan sa mga users, pariha sa fonts, larawan, special parts, etc.

* **sketches** - Example circuits/sketches shipped with the application

* **sketches** - Pananglitan circuit/sketches gipadala kauban ang aplikasyon

* **src** - Application logic!

* **src** - Lohika sa appication!

* **tools** - Utility tools for making releases, converting parts, etc.

* **tools** - Utility tools para sa paggama sa pagpagawas, pag pagkakabig sa mga bahin, etc.

* **translations** - Language translations

* **translations** - Paghubad sa pinulungan


# Credits

The Fritzing app is maintained by the Friends-of-Fritzing e.V., a non-profit foundation based in Berlin, Germany. The project has grown out of a state-funded research project at the [Interaction Design Lab](http://idl.fh-potsdam.de) at [Potsdam University of Applied Sciences](http://fh-potsdam.de).

Ang Fritzing app kay gimintinar sa Friends-of-Fritzing e.V., usa ka non-profit foundation nga naka base sa Berlin, Germany. Ang proyekto kay nag tubo gawas sa usa ka state-funded research nga proyekto sa [Interaction Design Lab](http://idl.fh-potsdam.de) didto sa [Potsdam University of Applied Sciences](http://fh-potsdam.de).

The core team consists of Prof. Reto Wettach, André Knörig, Jonathan Cohen, and Stefan Hermann. Many [fantastic people](http://fritzing.org/about/people/) have contributed to it over the years.


Ang core team nga naglangkob nila Prof. Reto Wettach, André Knörig, Jonathan Cohen, ug Stefan Hermann. Ug daghang [banggiitang taw](http://fritzing.org/about/people/) nga naka amot niini sa tibuok tuig.

The Fritzing app is written on top of the [Qt cross-platform framework](http://qt-project.org).

Ang Fritzing app kay naka sulat sa babaw sa [Qt cross-platform framework](http://qt-project.org).


# Licensing

The source code of Fritzing is licensed under  GNU GPL v3, the documentation and part designs under Creative Commons Attribution-ShareALike 3.0 Unported. The full text of these licenses are shipped with this download.

Ang tinubdan sa code sa Fritzing kay lisinsyado sa ilawm sa GNU GPL v3,ang dokumentasyon ug ang part design sa ilawm sa Creative Commons Attribution-ShareALike 3.0 Unported. Ang tibuok teksto niining mga lesinsyaha kay gipdala kauban sa pad download.

This means that you can create your own variation of Fritzing, as long as you credit us and also publish it under GPL. Similarly, you may re-publish our documentation, as long as you credit us, and publish it under the same 
license. You may publish circuits and diagrams that you create with Fritzing and that use our graphics, again as long as you credit us, and 
publish your works under the same license.  A credit can be as simple as "this image was created with Fritzing."

Kini nag pasabot nga ikaw maka himu ug imohang kaugalingong variation sa Fritzing, kung imong kaming e credit ug sa pag mantala niini sa ilawm sa GPL. Kapariho nga, ikaw mag mantala pag balik sa among dokumentasyon, samtang imo kaming e credit, ug imantala sa ilawm sa samang lisensya. Maka mantala ka ug circuits ug diagrams nga imong gimugna sa Fritzing ug sa dihang imong gigamit ang among graphics, sa pag usab samtang ikaw nag hatag namo ug credit  ug mag publish sa imong trabaho sa ilawm sa parihang lisensta. Ang usa ka credit pwede ra sayun sama niini "king larawan gimugna sa Fritzing."

Look up [our FAQs](http://fritzing.org/faq/) for more details on licensing.

Pangitaa ang  [our FAQs](http://fritzing.org/faq/) para sa uban pang mga detalye.
