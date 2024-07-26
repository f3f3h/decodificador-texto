# Projeto: Codificador e Decodificador de Texto

## Sobre
O Challenge Decodificador de Texto foi proposto na trilha "Iniciante em Programação T7 - ONE (Oracle Next Education)" desenvolvido pela Alura em parceria com a Oracle. 

Este projeto implementa um sistema de criptografia e descriptografia de texto usando as seguintes regras de substituição:
- A letra "e" é convertida para "enter"
- A letra "i" é convertida para "imes"
- A letra "a" é convertida para "ai"
- A letra "o" é convertida para "ober"
- A letra "u" é convertida para "ufat"

## Exemplo
- "gato" => "gaitober"
- "gaitober" => "gato"

## Requisitos
- O sistema deve funcionar apenas com letras minúsculas.
- Não devem ser utilizadas letras com acentos nem caracteres especiais.
- Deve ser possível converter uma palavra para a versão criptografada e também retornar uma palavra criptografada para a versão original.



## Funcionalidades
- Criptografar um texto inserido pelo usuário.
- Descriptografar um texto criptografado inserido pelo usuário.
- Copiar o texto criptografado/descriptografado para a área de transferência.

## Elementos Principais da Página
- **Título do site**
- **Campo para o texto** que vai ser criptografado/descriptografado (pode ser um `<input>` ou `<textarea>`)
- **Botões** para realizar a criptografia/descriptografia
- **Área para exibir o texto resultante**

## Extras
- **Botão para copiar** o texto criptografado/descriptografado para a área de transferência.
- **Rodapé** com os dados da pessoa que desenvolveu o site.

## Implementação

### HTML
- Campo de entrada para o texto
- Botões para criptografar e descriptografar
- Área para exibir o resultado
- Rodapé com informações do desenvolvedor

### JavaScript
- Função para criptografar o texto com base nas regras especificadas
- Função para descriptografar o texto com base nas regras especificadas
- Função para copiar o texto para a área de transferência
- Manipulação do DOM para exibir os resultados e controlar a interação do usuário

## Modelo de Design
- Use CSS para modificar cores, fontes, adicionar bordas e animações
- Exemplos de personalizações:
  - Alterar a fonte, tamanho e cor do título
  - Adicionar uma cor, gradiente ou imagem como plano de fundo do site
  - Modificar estilos, cores e bordas dos botões

## Rodapé
Desenvolvido por: Fernanda Ribeiro

---

## Como Usar
1. Clone este repositório: `git clone https://github.com/seu-usuario/seu-repositorio.git`
2. Abra o arquivo `index.html` no seu navegador.
3. Insira o texto no campo apropriado.
4. Clique em "Criptografar" para ver o texto criptografado ou "Descriptografar" para ver o texto original.
5. Use o botão "Copiar" para copiar o texto resultante para a área de transferência.

## Contato
Para mais informações, entre em contato:
- Email: f3rnandarib3iro@gmail.com
- LinkedIn: https://www.linkedin.com/in/f3f3h/
