# MRM-proteomics

Functions:
- graph_maker - main code with two functions which create graph
- graph_saver - returns graph like a main function but in JSON cytoscape format
- info_protein - information about a marker (связанные классы заболеваний, количество ассоциированных болезней)
- info_disease - information about a disease (класс, количество связанных белков-маркеров, белки-маркеры)
- disease_graph - graph-classification of the typed diseases

Important tables:
- tb2 - for graph_maker, graph_saver, for info_ functions
- diseases - for graph-maker functions, for disease_graph
