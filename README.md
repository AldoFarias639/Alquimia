# Desafio 1 — Minha Loja: Simulador de Compras

## Identificação
* **Nome do Projeto:** Alquimia Lab — Simulador de Compras
* **Aluno:** Aldo da Silva Farias
* **Trilha:** Desenvolvimento Mobile


## Apresentação da Loja
A **Alquimia Lab** é uma loja virtual fictícia voltada para a comercialização de reagentes químicos, vidrarias de precisão e Equipamentos de Proteção Individual (EPIs) para laboratórios. O projeto foi estruturado com foco em uma identidade visual limpa e alinhada ao ambiente acadêmico e industrial da Engenharia Química.

### Produtos e Preços:
1. **Béquer de Vidro Borossilicato (1000ml)** — R$ 45,00
   * *Descrição:* Resistente a altas temperaturas e choques térmicos, ideal para misturas e aquecimentos.
2. **Cloreto de Sódio P.A. (500g)** — R$ 28,50
   * *Descrição:* Sal com grau de pureza analítica superior a 99%, ideal para ensaios e soluções padrão.
3. **Óculos de Proteção Laboratorial** — R$ 35,00
   * *Descrição:* Lentes em policarbonato com proteção UV e tratamento antirrisco.


## Tecnologias Utilizadas
* **HTML5:** Estruturação semântica da página da loja.
* **CSS3:** Estilização responsiva, organização com Flexbox/Grid e paleta de cores personalizada.
* **JavaScript (ES6):** Interatividade do simulador via `prompt()`, tratamento de dados numéricos (`Number()`), validações condicionais e exibição de resultados com `alert()`.


## Instruções de Execução
1. Faça o download ou clone este repositório no seu computador.
2. Certifique-se de que os arquivos `index.html`, `style.css` e `script.js` estejam na mesma pasta principal.
3. Abra o arquivo `index.html` em um navegador web (Google Chrome, Firefox, Edge, etc.).
4. Clique no botão **"Simular compra"**, preencha as quantidades desejadas nas caixas de diálogo e acompanhe o resumo do pedido.


## Captura de Tela
<img width="1355" height="836" alt="Captura de tela 2026-10-28 212204" src="https://github.com/user-attachments/assets/68d03954-0eaf-46e3-9059-ccd47dc7c78e" />


## Testes Realizados
* **Teste 1 (Compra Mista):** Inseridas quantidades variadas para os três produtos. Verificada a precisão matemática dos subtotais e do valor total.
* **Teste 2 (Entradas Vazias ou Zero):** Inserido `0` em todos os campos. O sistema exibiu corretamente a mensagem informando que nenhum produto foi selecionado.
* **Teste 3 (Valores Inválidos/Cancelamento):** Testado o comportamento ao cancelar um `prompt()`, garantindo que a execução seja interrompida sem quebrar o script.


## Dificuldade Encontrada e Aprendizado
* **Dificuldade:** Uma dificuldade inicial foi garantir que, caso o usuário deixasse algum campo em branco ou cancelasse o prompt, o script não gerasse erros de cálculo com valores `NaN` (Not-a-Number).
* **Aprendizado:** Aprendi a utilizar o operador de coalescência e validações lógicas combinadas com `Number()` (ex: `Number(input) || 0`), o que garantiu robustez ao código e tratamento adequado de entradas vazias ou nulas.


## Uso de Inteligência Artificial
A Inteligência Artificial (Gemini) foi utilizada como ferramenta de apoio no refino do design responsivo em CSS. 
