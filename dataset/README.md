# Matrículas da rede estadual por modalidade e escola

Quantidade mensal de matrículas da rede estadual de ensino de Minas Gerais por modalidade (tipo de ensino) e escola, de fevereiro a dezembro de cada ano letivo, a partir de 2023.

**Modalidades:** os tipos de ensino registrados no SIMADE, como Ensino Regular, Integral, Integral Profissional, Profissional, Ensino Regular Profissional, Educação de Jovens e Adultos (EJA) e EJA Profissional.

## Como os dados foram produzidos

- **Fonte:** SIMADE (Sistema Mineiro de Administração Escolar).
- **Abrangência:** escolas da rede estadual. Considera apenas matrículas de escolarização; matrículas complementares (Sala de Recursos, projetos, reforço) não entram na contagem.
- **Regra de contagem:** matrículas ativas no último dia de cada mês. Matrículas encerradas em dezembro por resultado final (aprovação, reprovação, conclusão) ou por fechamento de período da EJA contam até 31/12.
- **Modalidades exclusivas:** cada matrícula está em uma única modalidade, então os valores podem ser somados por escola, município ou SRE.
- **Identificação da escola:** pelo código INEP (`cod_escola_inep`). Nome, endereço, SRE e município da escola estão no conjunto de endereços das escolas da Secretaria de Estado de Educação.
- **Proteção de dados (LGPD):** quantidades de 1 a 4 matrículas são suprimidas (campo `qtd_matriculas` vazio e `suprimido = S`). Por isso, somas feitas a partir deste arquivo podem ficar um pouco abaixo do total real.

## Atualização

Mensal. Cada ano letivo está em um arquivo separado (`see-matriculas-modalidades-AAAA.csv`).

## Responsável

Assessoria de Inovação (ASI) - Secretaria de Estado de Educação de Minas Gerais.
