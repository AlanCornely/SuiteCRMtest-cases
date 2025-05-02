# Geração de Relatórios Personalizados
## Objetivo:
Avaliar a capacidade do sistema de criar relatórios customizados a partir dos dados cadastrados.

## Descrição:
Testa a funcionalidade de geração de relatórios nos módulos principais do SuiteCRM.

## Pré-requisitos:
- Acesso ao SuiteCRM em https://crm.alunostds.dev.br
- Módulos com dados cadastrados (ex: Contatos, Oportunidades)

### Passo a Passo:
1. Acessar módulo com dados (ex: Contatos)
2. Procurar opção "Gerar Relatório"
3. Testar exportação em:
   - CSV (múltiplos registros)
   - PDF (registro único)
4. Verificar:
   - Campos exportados
   - Possibilidade de filtros
   - Formatação dos dados

### Resultado Esperado:
Sistema deveria permitir criar relatórios customizados com:
- Seleção de campos
- Aplicação de filtros
- Formatação profissional

### Resultado Obtido:
 Funcionalidade limitada:
- CSV: Exporta dados brutos
- PDF: Apenas registro único
- Nenhum recurso avançado de relatórios

### Análise:
Sistema não atende à necessidade de relatórios prontos para uso.

### Problemas Identificados:
- Falta de construtor de relatórios
- PDF inútil para análise
- Dependência de ferramentas externas

### Sugestões:
1. Implementar módulo de relatórios
2. Adicionar opção de PDF para múltiplos registros
3. Incluir visualizações gráficas

### Evidências:
- Exemplo de CSV exportado
- Captura da limitação do PDF

### Configurações:
OS: Windows 11 pro
Browser: Chrome 123.0.6312.86
Resolution: 1920x1080