# SPRINT-EDGE

## Visão Geral

O projeto SPRINT-EDGE aplica os princípios da manutenção preditiva da Indústria 4.0 para coletar dados e antecipar possíveis problemas e anomalias em carros de corrida. Integrado à plataforma de desenvolvimento acessível pelo site da Tech Mahindra, o sistema fornece estatísticas detalhadas para os fãs, como a velocidade média dos pilotos e comparações de desempenho.

O sistema utiliza um Arduino e um sensor MPU6050 para medir temperatura e movimento, detectando superaquecimento e movimentos irregulares, acionando um buzzer para alertar sobre problemas. Ele monitora a temperatura e a aceleração do carro, acionando um ventilador (simulado por um LED) quando necessário, e alertando sobre condições extremas com um buzzer. A manutenção preditiva oferece uma base para analisar melhorias no desempenho do carro e prever superaquecimentos, auxiliando decisões estratégicas como pitstops.

## Funcionalidades

- **Coleta de Dados:** Utilização de Arduino e sensor MPU6050 para medir temperatura e movimento.
- **Detecção de Problemas:** Identificação de superaquecimento e movimentos irregulares.
- **Alertas:** Acionamento de buzzer para alertar sobre problemas detectados.
- **Controle de Temperatura:** Acionamento de ventilador (simulado por um LED) quando necessário.
- **Manutenção Preditiva:** Análise de dados para prever superaquecimentos e auxiliar em decisões estratégicas.

## Componentes Utilizados

- **Arduino**
- **Sensor MPU6050**
- **Buzzer**
- **LED (simulando ventilador)**

## Como Funciona

1. **Coleta de Dados:** O sensor MPU6050 mede a temperatura e a aceleração do carro.
2. **Processamento:** Os dados são processados pelo Arduino, que verifica a presença de anomalias.
3. **Ação:** 
   - Se houver superaquecimento, o sistema aciona um ventilador (simulado por um LED).
   - Se forem detectados movimentos irregulares, o buzzer é acionado para alertar sobre o problema.
4. **Monitoramento e Análise:** Os dados coletados são usados para realizar manutenção preditiva, ajudando a prever problemas futuros e a melhorar o desempenho do carro.

## Equipe de Desenvolvimento

- **Matheus Dantas** – RM: 558804
- **Marco Antonio Andrade Gonçalves** – RM: 556818
- **Silas Alves Santos** – RM: 555020
- **Camila Takara** – RM: 555418

## Como Contribuir

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/seu-usuario/sprint-edge.git
   ```

2. **Navegue até o diretório do projeto:**
   ```sh
   cd sprint-edge
   ```

3. **Faça suas alterações:**
   - Adicione novas funcionalidades.
   - Corrija bugs.
   - Melhore a documentação.

4. **Envie um Pull Request:**
   - Detalhe as mudanças realizadas.
   - Aguarde a revisão da equipe de desenvolvimento.


## Contato

Para mais informações, entre em contato com a equipe de desenvolvimento através dos e-mails fornecidos no perfil do GitHub, ou contate um dos desenvolvedores da equipe de projetos

---

**Nota:** Este README serve como guia básico para entender e contribuir para o projeto SPRINT-EDGE. Para mais detalhes técnicos e instruções específicas de implementação, consulte a documentação completa disponível na plataforma de desenvolvimento da Tech Mahindra.
