# Alert-ANM
Completare senzori și automatizare la integrarea lui aurelmarius.
Acest tutorial te va ajuta să configurezi un sistem complet de monitorizare a alertelor meteo în Home Assistant, optimizat pentru județul Galați dar adaptabil pentru orice județ. Vom integra datele oficiale ANM cu o filtrare locală și o afișare elegantă. Tutorialul se adresează celor cu un nivel mediu de cunoștințe despre Home Assistant, și se bazează pe integrarea Alertă ANM din GitHub, realizată de aurelmarius.
Cerințe Prealabile
•	Integrarea Alerta ANM creată de aurelmarius instalată. (disponibilă pe GitHub). ATENȚIE! Se instalează doar integrarea iar ca urmare veți avea un senzor numit sensor.avertizari_meteo_anm, adică doar pașii 1 și 2 din readme. Nu faceți senzorul propus de el și nici automatizarea. După instalarea integrării, dați restart la Home Assistant iar după repornire verificați în Developers Tools – State dacă aveți senzorul sensor.avertizari_meteo_anm. 
•	Cardul custom fold-entity-row instalat din HACS.
•	Senzorii vor fi instalati în locația templates/ iar pentrtu a putea fi citiți trebuie să adăugați in configuration.yaml aceasta linie:
template: !include_dir_merge_list templates/
În fișierul docx găsiți toată procedura precum și explicații detaliate.
