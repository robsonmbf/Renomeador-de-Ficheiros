Renomeador eSocial (S-2220 / S-2240)

Uma ferramenta ágil e eficiente executada diretamente no navegador para automatizar a leitura, análise e renomeação de arquivos de eventos XML do eSocial (especificamente S-2220 e S-2240).

Funcionalidades

Processamento em Lote: Carregue múltiplos arquivos XML de uma só vez para análise simultânea.

Extração Inteligente: Identifica automaticamente se o evento é S-2220 ou S-2240, limpa namespaces e extrai os dados corretos (CPF e Matrícula).

Validação Opcional via Planilha: Permite o upload de uma planilha Excel .xlsx base para conciliar e visualizar quais funcionários listados na planilha já possuem os eventos gerados na remessa.

Exportação Flexível: Baixe os arquivos renomeados separadamente ou organizados estruturalmente em um único arquivo .zip (separados por empresa e tipo de evento).

Como Usar

Selecione a Empresa: Escolha uma empresa pré-cadastrada ou informe um CNPJ manualmente.

Selecione o Padrão: Escolha ou crie um padrão de nomenclatura usando as variáveis dinâmicas [prefixo], [cnpj], [data], [cpf] e [matricula].

Carregue os Arquivos XML: Arraste e solte os arquivos originais (com nomes genéricos) exportados do seu sistema de SST.

Carregue a Planilha (Opcional): Faça o upload da planilha com as colunas "CPF" e "NOME FUNCIONÁRIO" para que o sistema cruze os dados com os arquivos analisados.

Baixar Arquivos: Utilize os botões de ação para baixar o .zip compilado ou os arquivos de forma individual.

Tecnologias Utilizadas

HTML5, JS (Vanilla)

TailwindCSS

JSZip

SheetJS (xlsx)

FontAwesome

Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.