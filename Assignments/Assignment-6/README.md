Event bubbling and capture are two phases of event propagation in the HTML DOM (Document Object Model). Event bubbling is the process of an event propagating from the bottom up of the DOM tree while event capture is the opposite.

An example of event bubbling and capture is clicking on a link within a paragraph. When the link is clicked, the click event will be sent to the link element first, then to the paragraph, then to the parent div, and so on until it reaches the document object.

During the bubbling phase, the event is sent from the link element to the parent div element. During the capture phase, the event is sent from the document object to the link element.t is sent from the document object to the link element.