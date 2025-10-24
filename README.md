# Raciocínio Baseado em Casos - Sistema de Diagnóstico de Artrite
Este sistema utiliza técnicas de Inteligência Artificial baseada em casos para comparar novos casos clínicos com uma base de conhecimento pré-existente, calculando similaridades e sugerindo diagnósticos para diferentes tipos de artrite:
- Espondilite Anquilosante
- Artrite Reumatoide
- Artrite de Gota

# Funcionalidades
O sistema oferece um conjunto completo de funcionalidades para apoio ao diagnóstico médico. A **gestão da base de casos** permite carregar e expandir continuamente o conhecimento médico através de arquivos Excel, onde novos casos podem ser adicionados automaticamente após cada consulta, enriquecendo a base de dados para futuras análises.

O núcleo do sistema é o algoritmo de **cálculo de similaridade** que emprega uma abordagem de vizinhança com pesos configuráveis para cada sintoma e exame clínico. Este algoritmo compara multidimensionalmente os casos novos com toda a base existente, identificando os pacientes mais similares e suas respectivas porcentagens de correspondência.

Para o **processo de diagnóstico assistido**, o sistema analisa os casos mais similares e sugere um diagnóstico baseado no consenso dos casos com maior correspondência. A interface interativa guia o usuário através da entrada de dados do paciente de forma intuitiva, com validações para garantir a qualidade das informações inseridas.

Uma característica importante é a **flexibilidade na configuração**, onde os profissionais de saúde podem ajustar os pesos dos diferentes sintomas e exames de acordo com sua experiência clínica e relevância diagnóstica para cada tipo de artrite. O sistema também possui capacidade de aprendizado contínuo, onde cada novo caso diagnosticado é incorporado à base, melhorando progressivamente a acurácia do sistema.

# Métricas de Similaridade
- Nominal: Para atributos binários (sim/não)
- Ordinal: Para intensidades (ausente, leve, moderado, etc.)
- Numérica: Para valores contínuos (HLA-B27)

# Tecnologias Utilizadas
- Python 3
- Pandas - Manipulação de dados
- NumPy - Cálculos numéricos
- OpenPyXL - Leitura/escrita de arquivos Excel
