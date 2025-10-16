# 🔐 Cifra de Substituição em C#

Este projeto implementa uma cifra de substituição semelhante à cifra de Vigenère, utilizando um alfabeto personalizado com letras, números, acentos e símbolos especiais. O programa permite cifrar e decifrar mensagens com base em uma chave fornecida pelo usuário.

---

## ✨ Funcionalidades

- Validação de caracteres com base em um alfabeto estendido.
- Cifrar e decifrar textos interativamente via terminal.
- Interface simples com menu de opções.
- Implementado em C# e testável diretamente online.

---

## 🔤 Alfabeto utilizado

abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789áéíóúâêôã ,;. _#*" -+

Qualquer caractere fora desse conjunto será considerado inválido e resultará em erro.

---

## 🧪 Como testar no DotNetFiddle

Você pode executar este código diretamente no navegador usando o site [DotNetFiddle](https://dotnetfiddle.net):

### ▶️ Passos

1. Acesse [https://dotnetfiddle.net](https://dotnetfiddle.net)
2. Selecione o tipo de projeto como **Console** (se não estiver selecionado).
3. Copie e cole o conteúdo do arquivo `.cs` no editor.
4. Clique em **Run** para iniciar o programa.
5. Use o menu interativo para:
   - `1` → Cifrar um texto
   - `2` → Decifrar um texto
   - `3` → Sair do programa

### 💡 Exemplo de uso

--- Cifra de Substituição ---

Cifrar texto

Decifrar texto

Sair Escolha uma opção (1-3): 1 Digite o texto: Olá mundo! Digite a chave: segredo Texto cifrado: [resultado]


---

## 📁 Estrutura do Código

- `Program.cs`: contém o loop principal e a interface de terminal.
- `SubstitutionCipher.cs`: classe estática com os métodos `Encode` e `Decode`.

---

## 🌐 Link direto para teste

Você pode testar o código diretamente aqui:

🔗 [Abrir no DotNetFiddle](https://dotnetfiddle.net/tgvqWd)
---

## 📄 Licença

Este projeto é apenas para fins educacionais e pode ser usado livremente.
