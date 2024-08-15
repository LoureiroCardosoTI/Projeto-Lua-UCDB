# Projeto-Lua-UCDB
### O que é?

Lua é fácil de integrar com outros programas. Você pode usar Lua para adicionar novas funcionalidades a um programa sem modificar seu código principal.

Exemplo Básico:

Código Lua (script.lua):

lua
Copiar código
-- Define uma função simples
function greet()
    print("Hello from Lua!")
end
Código Lua (main.lua):

lua
Copiar código
-- Carrega o script Lua que contém a função
dofile("script.lua")

-- Chama a função definida no script
greet()
Explicação:

script.lua define uma função chamada greet que imprime uma mensagem.
main.lua carrega o script script.lua e chama a função greet.
Por que é interessante?
Isso mostra como Lua pode ser adicionada a programas maiores para expandir suas funcionalidades sem alterar seu código base.

2. Tabelas como Estrutura de Dados Principal
O que são tabelas?
Em Lua, tabelas são a estrutura principal para armazenar e organizar dados. Elas são muito versáteis e podem atuar como listas, dicionários ou até objetos.

Exemplo Básico:

Código Lua:

lua
Copiar código
-- Cria uma tabela com informações sobre uma pessoa
local person = {
    name = "Alice",
    age = 30,
    hobbies = {"reading", "cycling", "hiking"}
}

-- Imprime as informações da tabela
print("Name: " .. person.name)
print("Age: " .. person.age)
print("Hobbies: " .. table.concat(person.hobbies, ", "))
Explicação:

person é uma tabela que armazena o nome, a idade e os hobbies de uma pessoa.
Usamos a função print para mostrar essas informações na tela.
Por que é interessante?
As tabelas em Lua são flexíveis e permitem que você armazene e organize dados de maneira simples e eficiente, substituindo várias estruturas de dados.

Resumo dos Diferenciais com Exemplos Simples
Integração Simples: Lua pode ser usada para adicionar funcionalidades a programas existentes sem modificar o código principal.
Tabelas Versáteis: Tabelas são a principal estrutura de dados em Lua, permitindo a organização e o armazenamento de informações de forma flexível e simplificada.
Esses exemplos destacam como Lua é prática para adicionar novos recursos e como suas tabelas tornam a manipulação de dados eficiente e flexível.
