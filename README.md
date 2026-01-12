# IA AVANZADA SIMPLE NAVIGATION

En la estructura **Geometry** modifique una de las puertas para que quedase como si fuese una 
pequeña abertura al nivel de suelo.
Hice una copia del GameObject **HumanoidAgent** y modifique su tamaño a uno mucho mas pequeño.
Luego creé un nuevo Agent llamado **Rat** modificando sus **Radius,Height y StepHeight** para que adecuen
al tamaño del gameObject , tambien creé una nueva Area llamada **SoloRat**.

Una vez echo esto dentro del Objecto **Geometry** añadi un nuevo **NavMesh Surface** al cual añadi el agente **Rat**
y seleccione que el Area por Defecto para dicho agente sea **Solo Rat** para asegurarme que solo el gameObject con el agente **Rat**
pueda pasar por debajo de la abertura.
