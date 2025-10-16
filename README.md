🔐 Cifra de Substituição em C#
Este projeto implementa uma cifra de substituição semelhante à cifra de Vigenère, utilizando um alfabeto personalizado com letras, números, acentos e símbolos especiais. O programa permite cifrar e decifrar mensagens com base em uma chave fornecida pelo usuário.

✨ Funcionalidades
Validação de caracteres com base em um alfabeto estendido.

Cifrar e decifrar textos interativamente via terminal.

Interface simples com menu de opções.

Implementado em C# e testável diretamente online.

🧪 Como testar no DotNetFiddle
Você pode executar este código diretamente no navegador usando o site https://dotnetfiddle.net:

Passos:
Acesse https://dotnetfiddle.net

Selecione o tipo de projeto como Console (se não estiver selecionado).

Copie e cole todo o conteúdo do arquivo .cs neste editor.

Clique em Run para iniciar o programa.

Use o menu interativo para:

Cifrar um texto (Opção 1)

Decifrar um texto (Opção 2)

Sair do programa (Opção 3)

Exemplo de uso:
Código
--- Cifra de Substituição ---
1. Cifrar texto
2. Decifrar texto
3. Sair
Escolha uma opção (1-3): 1
Digite o texto: Olá mundo!
Digite a chave: segredo
Texto cifrado: [resultado]
🔤 Alfabeto utilizado
Código
abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789áéíóúâêôã ,;. _#*" -+
Qualquer caractere fora desse conjunto será considerado inválido e resultará em erro.

📁 Estrutura do Código
Program: contém o loop principal e a interface de terminal.

SubstitutionCipher: classe estática com os métodos Encode e Decode.

📄 Licença
Este projeto é apenas para fins educacionais e pode ser usado livremente.
