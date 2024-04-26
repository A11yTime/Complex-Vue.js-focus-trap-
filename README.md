## Accessibility Consideration of Modal Dialog
* When a dialog opens, focus moves to an element contained in the modal. Element receives focus depending on the availability of the elements when modal comprised of multiple .vue file. It’s recommended to send focus to the first focusable elements if feasible.
* After closing Modal focus must be returned to the original trigger or logical location when original trigger is not available.
* Inert of the modal is set to aria-hidden true along with modal is set to aria-modal true. Any elements of the modal are not direct child of inert.
* Focus must constrain within the modal.
## Terminologies
* role=”dialog”: Identifies the container as dialog
* aria-labelledby=”id”: Provides accessible name for dialog referenced by id with title of modal
* aria-describedby=”id”: Provides accessible description of modal
* aria-modal=”true” Hide inert from screen reader.
* aria-hidden=”true” Hide the inert from screen reader.

