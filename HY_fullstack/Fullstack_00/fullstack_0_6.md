```mermaid
sequenceDiagram;
	participant browser
	participant server
	activate server
	browser-->>server POST https://studies.cs.helsinki.fi/exampleapp/new_note %% Posts the new_note to the server
	deactivate server
;
```