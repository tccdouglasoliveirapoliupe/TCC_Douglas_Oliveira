# Calculadora de Carga Térmica para Câmaras Frigoríficas

Aplicação web desenvolvida como Trabalho de Conclusão de Curso (TCC) da Universidade de Pernambuco (UPE – POLI), destinada ao dimensionamento preliminar da carga térmica de câmaras frigoríficas por meio da soma das principais parcelas térmicas envolvidas na operação.

## Objetivo

A ferramenta foi desenvolvida para auxiliar estudantes, técnicos e profissionais da área de refrigeração na estimativa da carga térmica total de câmaras frigoríficas, considerando parâmetros construtivos, operacionais e de armazenamento.

O cálculo é realizado com base em metodologias amplamente utilizadas no setor de refrigeração comercial e industrial, utilizando tabelas técnicas e fatores de correção incorporados diretamente à aplicação.

## Funcionalidades

- Cálculo da transmissão de calor através de paredes, teto e piso (Q1);
- Cálculo da infiltração de calor por abertura de portas (Q2);
- Cálculo da carga térmica do produto armazenado (Q3);
- Cálculo da carga térmica proveniente da ocupação humana (Q4);
- Cálculo da carga térmica gerada pela iluminação (Q5);
- Cálculo da carga térmica dos motores internos (Q6);
- Aplicação de fator de segurança configurável;
- Conversão automática para capacidade requerida em kcal/h e kW;
- Seleção de diversos tipos de produtos refrigerados e congelados;
- Seleção de materiais e espessuras de isolamento térmico;
- Atualização automática dos resultados em tempo real;
- Exportação automática de relatório em PDF.

---

## Metodologia de Cálculo

A carga térmica total é obtida pela soma das parcelas:

```text
QT = Q1 + Q2 + Q3 + Q4 + Q5 + Q6
```

Onde:

| Parcela | Descrição |
|----------|------------|
| Q1 | Transmissão de calor pela envoltória |
| Q2 | Infiltração de ar externo |
| Q3 | Resfriamento ou congelamento do produto |
| Q4 | Presença de pessoas |
| Q5 | Iluminação |
| Q6 | Motores internos |

Após a obtenção do subtotal, é aplicado um fator de segurança definido pelo usuário.

---

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript Vanilla
- Google Fonts
- Exportação PDF via navegador

Não há dependências externas, frameworks ou necessidade de instalação.

---

## Estrutura do Projeto

```text
Calculadora Cargas Térmicas.html
│
├── Interface Responsiva
├── Tabelas Técnicas Incorporadas
├── Motor de Cálculo
├── Validação de Entradas
├── Atualização Dinâmica
└── Exportação de Relatórios PDF
```

---

## Como Utilizar

1. Abra o arquivo HTML em qualquer navegador moderno;
2. Informe as dimensões da câmara frigorífica;
3. Configure temperaturas interna e externa;
4. Escolha o material e espessura do isolamento;
5. Defina os parâmetros de utilização da câmara;
6. Informe os dados do produto armazenado;
7. Ajuste o fator de segurança desejado;
8. Visualize automaticamente os resultados;
9. Clique em **Exportar PDF** para gerar o relatório.

---

## Resultados Gerados

A aplicação fornece:

- Carga térmica total (kcal/24h);
- Capacidade requerida (kcal/h);
- Potência equivalente (kW);
- Participação individual de cada parcela térmica;
- Relatório técnico em PDF contendo:
  - Dados de entrada;
  - Resumo dos cálculos;
  - Gráfico de distribuição das cargas;
  - Resultados finais.

---

## Aplicações

A ferramenta pode ser utilizada para:

- Projetos acadêmicos;
- Estudos preliminares de refrigeração;
- Dimensionamento inicial de câmaras frigoríficas;
- Apoio ao ensino de refrigeração industrial;
- Simulações de diferentes condições operacionais.

---

## Autor

**Douglas Pires Oliveira**

Trabalho de Conclusão de Curso (TCC)  
Escola Politécnica de Pernambuco (POLI/UPE)

---

## Licença

Este projeto foi desenvolvido para fins acadêmicos e educacionais.

O uso, modificação e distribuição devem respeitar os créditos ao autor original.
