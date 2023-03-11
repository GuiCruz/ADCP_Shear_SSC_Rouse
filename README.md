Este repositório contém um conjunto de rotinas em Python para processar dados coletados por um ADCP (Acoustic Doppler Current Profiler) e calcular a tensão de cisalhamento, o retroespalhamento acústico (REA), a concentração de material sedimentar em suspensão (SSC) pelo REA, e s SSC pelo perfil de Rouse.

As rotinas foram organizadas em cinco módulos. O filtro de Butterworth foi aplicados nas variáveis de entrada para remover frequências indesejadas e suavizar o sinal.

O módulo 1 lê e processa os dados brutos de velocidade e amplitude acústica adquiridos pelo ADCP.

O módulo 2 e 3 processam os dados da bóia do SimCosta RS4 (https://simcosta.furg.br/).

O módulo 4 calcula a tensão de cisalhamento e o SSC pelo perfil de Rouse.

O módulo 5 contém as rotinas utilizadas para gerar os gráficos com os resultados.


Esperamos que essas rotinas possam ser úteis para pesquisadores e estudantes que trabalham com os dados de ADCP. Sinta-se livre para explorar o código, contribuir para o projeto e deixar feedback para melhorias futuras.
