# Grover algorithm

En este trabajo se construye el algoritmo de Grover para el caso de <i>n=3</i> qubits, donde la inicialización de cada qubit es cero. El algoritmo de Grover es una herramienta poderosa e importante en el computo cuántico ya que permite encontrar con alta probabilidad un elemento en una secuencia no ordenada de <i>N</i> datos (en este caso <i>N=8</i>) con un tiempo del orden de <img src="https://latex.codecogs.com/svg.latex?\sqrt{N}" title="\sqrt{N}">, en notación <img src="https://latex.codecogs.com/svg.latex?\mathcal{O}(\sqrt{N})" title="\mathcal{O}(\sqrt{N})" />, consta principalmente de dos compuertas, <img src="https://latex.codecogs.com/svg.latex?U_{w}$&space;y&space;$U_{s}" title="U_{w}$ y $U_{s}" />, que se iteran <i>k</i> veces a los qubits. La implemetación aquí presente se desarrolló con la herramienta <i>Qiskit</i> en Python 3, y se obtuvieron probabilidades de alrededor de <i>0.92</i> y <i>0.95</i> para cada uno de los estados cuánticos posibles dados 3 qubits, dichas probalidades se obtuvieron haciendo <i>k=2</i> iteraciones , lo cual comprueba que <i>k</i> debe ser del orden de <img src="https://latex.codecogs.com/svg.latex?\mathcal{O}(\sqrt{N})" title="\mathcal{O}(\sqrt{N})" />.  


Dentro de este folder se encuentra un documento PDF con el cual se describe y se discute el algoritmo y la implementación a profundidad.  

(English translation in process)
