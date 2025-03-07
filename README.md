# -exercicio-git-1

Como criar o arquivo index.html diretamente pelo bash?
Eu queria saber como criar um arquivo HTML diretamente pelo bash.
Usei o comando echo ou o comando cat com redirecionamento de saída para criar o arquivo diretamente pelo terminal.

Usando echo:

bash
echo '<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página</title>
</head>
<body>
    <h1>Tela de Login</h1>
</body>
</html>' > index.html

Com essas instruções, consegui criar o arquivo index.html 
Como criar o arquivo style.css e adicionar estilo para centralizar o <h1>?

Dúvida: Eu queria saber como criar o arquivo style.css e adicionar um estilo para centralizar o título <h1>.

Solução: Usei o terminal (bash) para criar o arquivo e adicionar o estilo desejado.

Passos:

bash
touch style.css
Adicionando o estilo:

bash
echo 'h1 {
    text-align: center;
}' > 

A tarefa de fazer commit foi simples pois ja sabia, não houve duvidas!!
usei esse comando para criar o arquivo "script.js"
touch script.js
 
 após isso coloquei no arquivo console.log("Teste");

 Antes tinha duvidas sobre oque era console.log pesquisei e descobri que:

 O console.log é um método em JavaScript usado para imprimir mensagens no console do navegador ou do ambiente de desenvolvimento. Ele é muito útil para depuração e para entender o fluxo de execução do código, mostrando valores de variáveis, resultados de operações e mensagens personalizadas.

Tive duvidas de como fazer um commit vazio, descobri pesquisando
" git commit --allow-empty -m "Exemplo"".

Na parte do gi merge eu não entendi muito oque era e descobri
git merge é um comando do Git que permite combinar as mudanças de uma branch com outra. É uma operação comum usada para integrar o trabalho de diferentes branches em um repositório.

Aqui está um resumo de como ele funciona:

Combinar mudanças: Quando você faz um merge, o Git pega todas as mudanças que foram feitas na branch de origem (a branch que você está mesclando) e aplica essas mudanças na branch de destino (a branch atual em que você está).

Preserva histórico: O merge preserva o histórico de commits das branches envolvidas, mostrando que o trabalho de duas ou mais linhas de desenvolvimento foi combinado.

Resolução de conflitos: Se houver mudanças conflitantes entre as branches, o Git pedirá para você resolver esses conflitos manualmente. Isso envolve editar os arquivos conflitantes para decidir qual versão das mudanças deve ser mantida.

