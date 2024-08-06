# Uml_Desafio

+-------------------+
| <<interface>>     |
| ReprodutorMusical |
+-------------------+
| + tocarMusica()   |
| + pausarMusica()  |
| + pararMusica()   |
+-------------------+

+-------------------+
| <<interface>>     |
| AparelhoTelefonico|
+-------------------+
| + fazerChamada()  |
| + receberChamada()|
| + encerrarChamada()|
+-------------------+

+-------------------+
| <<interface>>     |
| NavegadorInternet |
+-------------------+
| + abrirPagina()   |
| + atualizarPagina()|
| + adicionarAosFavoritos()|
+-------------------+

+-------------------+
| iPhone            |
+-------------------+
| - modelo: String  |
| - numeroSerie: String |
+-------------------+
| + tocarMusica()   |
| + pausarMusica()  |
| + pararMusica()   |
| + fazerChamada()  |
| + receberChamada()|
| + encerrarChamada()|
| + abrirPagina()   |
| + atualizarPagina()|
| + adicionarAosFavoritos()|
+-------------------+

ReprodutorMusical <|----- iPhone
AparelhoTelefonico <|----- iPhone
NavegadorInternet <|----- iPhone

