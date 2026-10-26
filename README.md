# Radici dei sigilli giornalieri (ShieldDNS.EU, Phantom Domain Index)

Ogni riga di `radici.txt`: `giorno radice voci precedente`. La radice e' la sha256 del manifesto del giorno (solo
impronte, nessun dato); "precedente" e' la radice del manifesto prima. Il file cresce solo in coda: la storia di questo
repository e' il registro pubblico delle radici. Ogni radice ha anche marche temporali RFC 3161 e OpenTimestamps.
Studio pre-registrato: https://doi.org/10.17605/OSF.IO/WXZGC
