# Conversor de Temperatura

Programa em JavaScript que converte valores de temperatura entre as escalas 
Celsius, Fahrenheit e Kelvin.

## Funcionalidades
- Conversão de Celsius para Fahrenheit e vice-versa
- Conversão de Celsius para Kelvin e vice-versa
- Conversão indireta entre Fahrenheit e Kelvin (via Celsius)
- Validação de escalas inválidas

## Como usar
1. Clone o repositório ou baixe o arquivo `conversor-temperatura.js`
2. Execute com Node.js:
   \`\`\`bash
   node conversor-temperatura.js
   \`\`\`
3. Ou importe as funções em outro projeto:
   \`\`\`javascript
   const resultado = converterTemperatura(100, "C", "F");
   \`\`\`

## Funções disponíveis
| Função | Descrição |
|---|---|
| `celsiusParaFahrenheit(c)` | Converte Celsius em Fahrenheit |
| `fahrenheitParaCelsius(f)` | Converte Fahrenheit em Celsius |
| `celsiusParaKelvin(c)` | Converte Celsius em Kelvin |
| `kelvinParaCelsius(k)` | Converte Kelvin em Celsius |
| `converterTemperatura(valor, origem, destino)` | Função geral, decide qual conversão aplicar |

## Fórmulas utilizadas
- **C → F**: `(C × 9/5) + 32`
- **F → C**: `(F − 32) × 5/9`
- **C → K**: `C + 273.15`
- **K → C**: `K − 273.15`

## Tecnologias
- JavaScript (ES6+)

## Autor
Seu nome aqui
