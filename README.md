# Raciocínio Baseado em Casos - Sistema de Diagnóstico de Artrite
Este sistema utiliza técnicas de Inteligência Artificial baseada em casos para comparar novos casos clínicos com uma base de conhecimento pré-existente, calculando similaridades e sugerindo diagnósticos para diferentes tipos de artrite:
- Espondilite Anquilosante
- Artrite Reumatoide
- Artrite de Gota

Funcionalidades
- Gestão de Base de Casos: Carregamento e expansão da base de conhecimento
- Cálculo de Similaridade: Algoritmo de vizinhança com pesos configuráveis
- Diagnóstico Assistido: Sugestão baseada nos casos mais similares
- Interface Interativa: Entrada de dados do paciente via terminal
- Configuração Flexível: Personalização dos pesos dos sintomas e exames
- Aprendizado Contínuo: Adição de novos casos à base de conhecimento

Métricas de Similaridade
- Nominal: Para atributos binários (sim/não)
- Ordinal: Para intensidades (ausente, leve, moderado, etc.)
- Numérica: Para valores contínuos (HLA-B27)
