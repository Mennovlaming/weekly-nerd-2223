Hidde de Vries

Modal Mischief & dialog dillema’s
Front end developer + accessibility
Voornamelijk freelance voor o.a. overheid en W3C

Tip: schrijf een blog van dingen die je leert. 

In het begin waren alle sites linear, text onder elkaar.
Tegenwoordig overlappen dingen elkaar.

Een aantal dialogs:
<dialog></dialog>
Hiermee krijg je een hoop semantics, en functies van een dialoog.

Modal vs non-model
Een modal is het enige ding waarmee je interactie mee kan hebben, bijvoorbeeld cookie pop up, na de model kan je weer verder met de pagina. 
Een niet model dialog gaat ook over dingen heen, maar je kan nog steeds de rest van de pagina gebruiken, denk aan een uitleg pop up, menu knoppen, dropdown’s. 
Model interrupt je website, non-model niet.

Light vs explicit dismiss
Een light dialog kan je sluiten als je ergens naast klikt. 
Bij explicit kan je hem alleen sluiten met een knop.

Z-index vs top layer
Top layer ligt bovenop de z-index. 
Met een dialog of bijvoorbeeld YouTube film full screen. Pop overs gebruiken ook de top layer.

Backdrop 
Alleen voor top layer elementen 

Keyboard focus trap
Dat je alleen bij een specifiek gedeelte kan tabben, denk aan cookie pop up of een navigatiebar, altijd tijdelijk.

<div popover> nieuwe attribuut.  
Altijd bovenaan, niet altijd zichtbaar
- Datepickers
- Tootltips

Disclosure widget
<details>
	<summary>
	</summary>
</details>

