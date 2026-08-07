# Leerdoelen per week

## Week 1: Images
Na dit college kunnen studenten:
* [ ] uitleggen hoe digitale medische beelden worden gerepresenteerd als pixels/voxels;
* [ ] onderscheid maken tussen pixelwaarden, intensiteiten en fysieke betekenis;
* [ ] uitleggen wat spacing, origin en oriëntatie betekenen; *verschil tussen thickness en spacing uitleggen*
* [ ] opbouw van 2D-, 3D- en 4D-beelden beschrijven;
* [ ] de basisstructuur van DICOM- en Nifti-bestanden beschrijven;
* [ ] typische uitdagingen van medische beelddata benoemen, zoals anisotrope resolutie en verschillen tussen slice-thickness en -spacing.

_Practical session: aan de slag met beelden in MicroDICOM en ITKSnap._
_DICOM tag browser: https://dicom.innolitics.com/_


## Week 2: Scripting
Na dit college kunnen studenten:
* [x] eenvoudige Python-scripts uitvoeren in een Jupyter notebook;
* [x] variabelen, numerieke typen en expressies gebruiken;
* [x] functie-aanroepen uit externe libraries toepassen;
* [x] tekstfiles lezen en schrijven;
* [x] string formatting gebruiken;
* [x] numpy arrays gebruiken;
* [x] medische beeldbestanden (DICOM) openen met bestaande Python libraries (pydicom);
* [x] medische beelden visualiseren en eenvoudige plots maken (alleen 2D);
* [ ] eenvoudige Matlab-code vergelijken met equivalente Python-code; (NIET)
* [x] foutmeldingen interpreteren en corrigeren;

_Dit daarna vergelijken met intro van AI en IP courses en gelijk trekken waar mogelijk._

_Assignment: DICOM beeld openen, iets uitrekenen (gemiddelde, histogram met bin-size als parameter?), resultaat printen en in tekstfile wegschrijven. Nog geen Nifti gebruiken._


## Week 3: Functions
Na dit college kunnen studenten:
* [ ] uitleggen wanneer scripting geschikt is voor data-analyse en prototyping.
* [ ] eenvoudige programma’s opdelen in herbruikbare functies; *(functienaam, argumenten, return type, return value)*
* [ ] invoer en uitvoer verwerken in command-line programma’s;
* [ ] iteratie en conditionele logica toepassen;
* [ ] geschikte datastructuren gebruiken voor eenvoudige toepassingen; *(containers/iterables; list, tuple, dict)*
* [ ] verschil tussen value en reference uitleggen; *(Python gebruikt return by reference voor objecten)*
* [ ] doel van duidelijke inline comments en functie- en variabelenamen inzien;
* [ ] debuggingtools in een IDE gebruiken; *stack trace*
* [ ] typing / type hints in Python begrijpen en toepassen;
* [ ] eenvoudige programmeerfouten herkennen en oplossen;
* [ ] versiebeheer toepassen met Git (clone, add, commit, push, pull);
* [ ] uitleggen waarom modulaire software beter onderhoudbaar is.
* [ ] visualisatie van 3D met 1 slice, 3D met scrollable viewer

_Assignment: Functie schrijven om DICOM beeld te openen en als dictionary terug te geven. Ook Nifti inlezen. Generieke scrollable viewer voor alle 3D data. Beelden verwerken (bijv drempelen) en opslaan als Nifti_
_Graded assignment: form_


## Week 4: Libraries
Na dit college kunnen studenten:
* [ ] bestaande Python libraries installeren en gebruiken;
* [ ] eigen Python modules en libraries structureren;
* [ ] code hergebruiken vanuit Jupyter notebooks;
* [ ] software opdelen in meerdere bestanden en modules;
* [ ] samenwerken via Git branches en merges;
* [ ] versiebeheer gebruiken om softwareontwikkeling te organiseren;
* [ ] uitleggen waarom softwarebibliotheken belangrijk zijn voor schaalbare wetenschappelijke software;
* [ ] het belang van (unit) tests uitleggen;
* [ ] veelgebruikte Python libraries benoemen (pandas, numpy, scipy, pydicom, nibabel, pytorch);
* [ ] het belang van dependency/environment management uitleggen. _(Python virtual environments)_

_Assignment: Een library maken voor o.a. de functies van vorige week. hatch gebruiken._


## Week 5: Classes
Na dit college kunnen studenten:
* [ ] uitleggen wat classes en objecten zijn;
* [ ] uitleggen wanneer objectgeoriënteerd programmeren voordelen biedt;
* [ ] eenvoudige classes ontwerpen en implementeren;
* [ ] constructors gebruiken om objecten te initialiseren;
* [ ] het nut van publieke, protected en private attributen uitleggen; *(n.b. in Python zijn dit enkel hints; '\_' voor protected en '\_\_' voor private)*
* [ ] operator overloading toepassen;
* [ ] inheritance gebruiken voor codehergebruik.

_Assignment: Een Image class maken, en afgeleide klasses; DicomImage, RGBImage. Library aanpassen._


## Week 6: Languages
Na dit college kunnen studenten:
* [ ] de verschillen beschrijven tussen geïnterpreteerde en gecompileerde talen;
* [ ] de sterke en zwakke punten van Python, Matlab, C/C++ en R vergelijken;
* [ ] uitleggen waarom performancekritische code vaak in lagere programmeertalen wordt geschreven;
* [ ] eenvoudige C/C++ code (image filter) lezen, schrijven en compileren;
* [ ] een C-library aanroepen vanuit Python;
* [ ] uitleggen hoe wetenschappelijke software gebruikmaakt van mixed-language architecturen.

_Assignment: Een simpel image filter in C implementeren. Aanroepen vanuit Python. Template geven._


## Week 7: Computation
_Of iets anders, bijv. gastcollege van Alex_

Na dit college kunnen studenten:
* [ ] type safety en narrowing begrijpen;
* [ ] mogelijke bottlenecks in wetenschappelijke software benoemen; *(geheugensnelheid, geheugengrootte, cpu, disk, netwerk, gebruiker)*
* [ ] geheugen- en cachegebruik op hoog niveau beschrijven;
* [ ] multiprocessing, multithreading en vectorisatie conceptueel onderscheiden;
* [ ] uitleggen wanneer GPU-acceleratie nuttig kan zijn;
* [ ] prestaties vergelijken tussen Python-, NumPy- en C-implementaties;
* [ ] efficiënte array-operaties uitvoeren met NumPy;

_Assignment: Performance van Python/NumPy/C filter.


## Week 8: Q&A
_Ruimte voor uitloop_
