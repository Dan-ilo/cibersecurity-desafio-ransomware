**Este projeto é um desafio técnico desenvolvido em Python.** O objetivo principal é puramente acadêmico: compreender os mecanismos internos de um malware do tipo ransomware (como criptografia de arquivos e manipulação de chaves) para aprimorar o entendimento sobre segurança defensiva e detecção.

⚠️ **AVISO DE ISENÇÃO DE RESPONSABILIDADE (DISCLAIMER):**
Este código foi projetado para rodar exclusivamente em ambientes de teste controlados e isolados (sandboxes). O autor não se responsabiliza pelo uso indevido, danos ou modificações maliciosas causadas por terceiros a partir deste repositório.

---

## 🚀 Sobre o Desafio

O projeto simula de forma simplificada o comportamento de um ransomware, demonstrando como arquivos podem ser criptografados, e posteriormente, restaurados através de uma ferramenta de descriptografia.

### Funcionalidades Implementadas
* **Criptografia com Python:** Utilização de bibliotecas nativas ou específicas para cifrar os dados.
* **Mecanismo de Descriptografia:** Script separado (`decrypter`) que reverte o processo e restaura os arquivos originais.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.x
* **Plataforma Educacional:** Digital Innovation One (DIO)

---

## 🔬 Como Executar (Ambiente de Testes)

> ❗ **Atenção:** Nunca execute códigos desse tipo na sua máquina principal. Utilize sempre uma Máquina Virtual (VM) isolada ou uma pasta de testes criada especificamente para este fim.

1. **Clone o repositório:**
   ```bash
   git clone https://github.com
   cd nome-do-repositorio
   ```

2. **Prepare os arquivos de teste:**
   Crie uma pasta de testes e adicione alguns arquivos fictícios (como arquivos `.txt`) que possam ser modificados sem problemas.

3. **Execute o script de criptografia:**
   ```bash
   python encrypter.py
   ```

4. **Execute o script de recuperação:**
   ```bash
   python decrypter.py
   ```

---

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
