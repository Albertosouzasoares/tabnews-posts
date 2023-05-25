# Como Baixar e Instalar a Versão Mais Recente do Node.js no Windows 7

Desde abril de 2021, o suporte para o Node.js no Windows 7 foi descontinuado, com a última versão compatível sendo a 13. No entanto, muitas pessoas ainda utilizam o Windows 7 e necessitam da versão mais atualizada do Node.js.

Neste tutorial, vou te ensinar como baixar e instalar a versão mais recente do Node.js no Windows 7, permitindo que você aproveite todos os recursos e melhorias oferecidos pelo Node.js atualizado.

Acesse o link https://nodejs.org/en/download/releases e escolha uma versão. Vamos selecionar a versão 18.16.0, pois é a mais estável. Clique em "Releases".

![node.js download](https://raw.githubusercontent.com/Albertosouzasoares/tabnews-posts/main/img-1.PNG)

Em seguida, escolha o arquivo correspondente ao seu sistema operacional Windows 7. Se estiver utilizando a versão de 32 bits, selecione o arquivo com a extensão .7z e "x86". Caso esteja usando a versão de 64 bits, selecione o arquivo com a extensão .7z e "x64".

![node.js download](https://raw.githubusercontent.com/Albertosouzasoares/tabnews-posts/main/img-2.PNG)

Após o término do download, localize o arquivo na pasta de downloads do seu computador e extraia o conteúdo. Acesse a pasta para onde o arquivo foi extraído e copie todos os arquivos presentes.

![Instalando o node](https://raw.githubusercontent.com/Albertosouzasoares/tabnews-posts/main/img-3.PNG)

Agora, vá para o "Computador" e dê um duplo clique no seu disco principal (geralmente é o disco C:). Dentro do disco principal, crie uma nova pasta chamada "node". Cole os arquivos previamente copiados nesta nova pasta.

![Instalando o node](https://raw.githubusercontent.com/Albertosouzasoares/tabnews-posts/main/img-7.PNG)

Clique com o botão direito do mouse no ícone "Computador" e selecione "Propriedades".

![node.js instalando](https://raw.githubusercontent.com/Albertosouzasoares/tabnews-posts/main/img-5.PNG)

Na janela de propriedades, clique em "Configurações avançadas do sistema" e, em seguida, em "Variáveis de ambiente".

IMG

Localize a variável de ambiente chamada "PATH" e clique em "Editar". Certifique-se de não apagar o valor existente na variável. No final do valor da variável, adicione ";C:\node" (sem aspas). Clique em "OK" para salvar as alterações.

![Configurando o node](https://raw.githubusercontent.com/Albertosouzasoares/tabnews-posts/main/img-7.PNG)

Para adicionar novas variáveis de ambiente, siga as instruções abaixo:

1. Clique em "Novo" na seção de Variáveis de ambiente.
2. No campo "Nome da variável", adicione "NODE_SKIP_PLATFORM_CHECK".
3. No campo "Valor da variável", insira "1".
4. Clique em "OK" para criar a nova variável.

![Configurando o node](https://raw.githubusercontent.com/Albertosouzasoares/tabnews-posts/main/img-10.PNG)

Repita o mesmo processo para adicionar outra variável de ambiente:

1. Clique em "Novo" novamente na seção de Variáveis de ambiente.
2. No campo "Nome da variável", digite "NODE_PATH".
3. No campo "Valor da variável", insira "C:\node\node_modules".
4. Clique em "OK" para criar a nova variável.

![Configurando o node](https://raw.githubusercontent.com/Albertosouzasoares/tabnews-posts/main/img-11.PNG)

Certifique-se de que todas as alterações foram salvas clicando em "OK" nas janelas de propriedades.

![Configurando o node](https://raw.githubusercontent.com/Albertosouzasoares/tabnews-posts/main/img-12.PNG)

Agora, abra o Prompt de Comando (CMD) e digite "node -v" para verificar se o Node.js foi instalado corretamente. Se você vir a versão do Node.js sendo exibida, isso significa que ele foi instalado com sucesso.

![Verificando se o node foi instalado](https://raw.githubusercontent.com/Albertosouzasoares/tabnews-posts/main/img-13.PNG)

Agora você está pronto para usar e criar projetos incríveis com o Node.js no Windows 7.
