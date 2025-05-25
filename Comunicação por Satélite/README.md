# Projeto 6 – Comunicação por Satélites 🌐📡

## 🎓 Curso: Sistemas de Telecomunicações  
**Disciplina:** Comunicações por Satélites  
**Tema:** Implementação de uma rede via satélite para distribuição de sinais de TV voltada ao ensino a distância.

---

## 📝 Descrição do Projeto

Este projeto tem como objetivo projetar uma **rede de comunicação via satélite** para a **distribuição de sinais de TV educacional** em todo o território nacional. A solução será baseada na tecnologia **DVB-S** com uma **taxa máxima de 2 Mbps**, utilizando o **satélite StarOne C3** em **Banda C**.

A proposta visa atender com qualidade os requisitos de uma rede de **ensino a distância**, com foco no desempenho sob diversas condições de enlace.

---

## 📦 Escopo e Entregáveis

- **Especificação completa dos componentes** das estações transmissoras (TX) e receptoras (RX).
- Apresentação **em blocos funcionais** das estações de TX e RX.
- Determinação da **largura de banda ocupada** no transponder do satélite.
- Cálculo do **Back-Off de entrada (BOin)** e **Back-Off de saída (BOout)** conforme diferentes percentuais de ocupação da banda:
  - 50% da banda: `BOin = 3,8 dB`
  - 25% da banda: `BOin = 8,5 dB`
  - ≤10% da banda: `BOin = 10,1 dB`
  - `BOout = BOin - 3,83 dB`

---

## 🔧 Componentes Considerados

### Estação Transmissora (TX)

- Modulador DVB-S
- Amplificador de alta potência (HPA)
- Antena parabólica com ganho adequado
- Up-converter para Banda C
- Sistema de controle e redundância

### Estação Receptora (RX)

- LNB de Banda C com baixo ruído
- Antena parabólica com ganho adequado
- Receptor DVB-S (Set-top box)
- Decodificador de vídeo
- Sistema de distribuição local (TV interna ou rede IP)

---

## 📐 Cálculos Técnicos

- Determinação da **largura de banda ocupada** com base na taxa de dados de 2 Mbps e fator de roll-off do DVB-S.
- Cálculo do **link budget**, considerando:
  - Potência do transponder
  - Ganhos de antenas
  - Perdas por chuva e caminho
  - Margens de segurança
- Cálculo do **BOin** e **BOout** baseado na ocupação do transponder.
- Escolha dos parâmetros que garantam o desempenho mínimo com **BER adequado para vídeo digital**.

---

## 🗺️ Cobertura e Alcance

- Cobertura em **todo o território nacional** (Brasil).
- Uso do **satélite StarOne C3** operando em Banda C, ideal para resistir à atenuação por chuva em regiões tropicais.

---

## 📊 Resultados Finais

- Projeto em blocos das estações TX e RX.
- Lista de equipamentos e acessórios recomendados.
- Parâmetros dimensionados para garantir qualidade de recepção.
- Cálculo da largura de banda e utilização eficiente do transponder.
- Considerações sobre redundância e disponibilidade do sistema.

---

## 🧠 Considerações Finais

Este projeto leva em conta **todas as perdas previsíveis**, com **aproximações justificadas** apenas em condições adversas. O dimensionamento foi feito para garantir **alta disponibilidade**, **eficiência espectral**, e **qualidade de serviço educacional** via satélite.

---

> 📁 *Este projeto foi desenvolvido como parte da disciplina de Comunicações por Satélites do curso de Sistemas de Telecomunicações.*

---

- ## Return
  [![Main Page](https://img.shields.io/badge/Main-Page?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alfecjo/java-spring-testes/tree/main)

