# Instalação MacOS Ventura no Acer E5
Nesse documento você irá  encontrar o passo a passo de instalação do MacOS Ventura no Notebook Acer E5

⚠️PROJETO ESTÁ EM CONSTANTE DESENVOLVIMENTO⚠️

1. Baixar a o arquivo de imagem da versão 13
2. Criar o drive de boot com Baleia Etcher
3. Se você tiver em um Mac, após criar o drive, conectar a entrada USB e montar a pasta oculta EFI com o programa ESP Mounter Pro, apagar a pasta EFI de dentro
4. Depois do processo acima, baixar *esse arquivo* que contem a EFI e colocar na pasta que foi alterada no passo 3.
5. Depois, reiniciar e fazer processo de instalação normal
6. Apos iniciado, o MacOS talvez inicie com 4mb de memória de video alocada e para resolver isso e necessário fazer o seguinte:

* Baixar o programa OpenCore Patcher e Hackintool

	⁃	1. Inicie o Hackintool e ir em NVRAM > Adicionar boot-args > Digitar a string “amfi=0x80” e Salvar
	⁃	2. Após esse procedimento iniciar o OCP e selecionar Post Install, após esse procedimento reiniciar que seu sistema vai voltar rodar com a compatibilidade da placa de video integrada.

*Após todo esse passo a passo seu Mac irá rodar lisinho!
