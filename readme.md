# Expose


## Stand der Wissenschaft 
Tabelle mit verschiedenen Tools und verschiedenen Anforderungen -> nur meins kann alles




## Überblick über die Funktionalität
![plot](./mindmap.png)

### Ziel der Arbeit
Das Ziel ist ein Tools für den Umgang mit JWT. Es werden die gängigen Angriffe auf JWTs implementiert, um somit eine umfassende Funktionalität zu bieten.
Umgesetzt werden sowohl die grundlegenden Funktionen:
- Encoden/Decoden (Möglichkeit für die Erstellung von "defekten" JWTs)
- Signature Verify/Sign
  
Als auch gängige Angriffe auf JWT:
- Signature Attacks (Signature Exclusion, Custom Key, Key Confusion, none-alg ...)
- kid attacks (RCE, Path traversal ...)
- SSRF

Das Tool wird in Javascript geschrieben und eignet sich somit für den Browser. Ein weiterer Schritt wäre es zu evaluieren, inwiefern eine Automatisierung in Burp umsetzbar ist.

### Methodologie
#### Arbeitspaket 1: grundlegende Funktionalität (Dauer: ??)
Implementierung von den oben genannten Basisfunktionen 

#### Arbeitspaket 2: Angriffe (Dauer: ??)
Implementierung der oben genannten Angriffe 

#### Arbeitspaket 3: Überprüfung (Dauer: ??)
Meine Implementierung nutzen um ein JWT Framework zu testen. Hierbei kann sowohl die Funktionalität meines Tools auch die Sicherheit des zu testeten Frameworks überprüft werden.

#### Arbeitspaket 4: Dokumentation

#### Arbeitspaket 5: Evaluation einer möglichen Automatisierung in Burp
Herausfinden, ob/wie es möglich ist automatisierte Angriffe auf JWTs in Burp zu implementieren. 

### Stand der Wissenschaft
Es werden bekannte Schwachstellen getestet z.B.:
- Aufzählung mit cve?


Obwohl es einige Tools in diesem Bereich gibt, bietet kein Tool die komplette Bandbreite, die hier vorgesehen ist. Die meisten Tools bieten lediglich die grundlegende Funktionalität um mit JWTs zu arbeiten (z.B. https://jwt.io/, https://token.dev/, https://fusionauth.io/dev-tools/jwt-decoder, jwt.ms). Andere Tools bieten einige gängige Angriffe aber besitzen keine UI oder das potential der Automatisierung fehlt.

### Typo 
https://informatik.rub.de/abschlussarbeiten/thesis_nds/bachelor-masterthesis-eigenes-thema-vorschlagen/ 
Auf der Seite ist ein Typo (Beispiel > Wissenschaftlicher Anspruch > "Implemenationen")
