# GPDFTS - Apresentação de gestão de pessoas

Painel executivo da Secretaria da Saúde do Tocantins, com três seções:

- **Cessão de Pessoal:** quantitativo, cargos, custo informado, órgãos de destino e filtro por responsabilidade do ônus.
- **Força de Trabalho nos Hospitais:** quantitativos por unidade, porte, cargo e vínculo.

- **Superintendências:** força de trabalho por unidade administrativa, cargo e vínculo, incluindo o Gabinete.

## Como utilizar

Baixe os arquivos e abra **index.html** no navegador. Mantenha os três arquivos HTML na mesma pasta para que a navegação entre seções funcione. O painel funciona sem instalação, servidor ou conexão com a internet.

Os filtros atualizam os indicadores, gráficos, quadros e exportações em CSV. Não há sincronização automática com o sistema de origem.

## Arquivos

- [Superintendências](superintendencias.html)
- [Apresentação das Superintendências em PDF](superintendencias.pdf)
- [Cessão de Pessoal](index.html)
- [Força de Trabalho nos Hospitais](forca_trabalho_hospitais.html)
- [Apresentação de Cessão de Pessoal em PDF](apresentacao_executiva_cedidos.pdf)
- [Apresentação da Força de Trabalho nos Hospitais em PDF](forca_trabalho_hospitais.pdf)

## Fonte das informações

**Sistema de Gestão de Recursos Humanos e Folha de Pagamento.**

A seção de cessões apresenta 548 vínculos e R$ 5.958.630,25 no campo de valor informado. A referência dessa extração é 10/11/2026. Os destinos municipais foram padronizados como prefeituras e as variações do mesmo destino foram agrupadas. A periodicidade dos valores não está especificada e não houve anualização.

A seção de hospitais apresenta 12.736 contagens em 17 unidades, distribuídas por porte, cargo e tipo de vínculo. O relatório hospitalar não informa data de referência, jornadas ou valores financeiros. As contagens não correspondem necessariamente a pessoas únicas ou presença em plantão.

A seção de superintendências apresenta 2.880 contagens em 12 superintendências e no Gabinete: 212 comissionados, 1.520 contratados, 1.126 efetivos e 22 em Outros. O arquivo não informa data de referência, jornadas ou valores financeiros.

Somente dados agregados são incluídos neste repositório. Não há relação individual de servidores, matrículas ou planilhas de origem.

## Estrutura técnica

HTML, CSS e JavaScript, com dados agregados embutidos. Não utiliza bibliotecas externas, serviços pagos ou chamadas a APIs.

Os arquivos também podem ser servidos como site estático. Para usar GitHub Pages, selecione a branch main e a pasta raiz nas configurações de Pages do repositório.
