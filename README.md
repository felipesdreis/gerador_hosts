# Gerador de Hosts
Para que você consiga acessar outras maquinas utilizando o hostname delas é necessáurio que voce tenha o mapeamento do ip -> hostname no seguinte arquivo do windows -> C:\Windows\System32\drivers\etc\hosts

Seguindo o padrão IP HOSTNAME 
> 127.0.0.1 localhost

Caso você trabalhe com T.I é provavel que tenha que acessar varios servidores e que tenha os dados desses servidores em uma planilha 😉

Para facilitar o acesso por hostname, esse programa irá ler a planilha e gerar os dados no padrão do arquivo hosts do windows, assim você não precisará ficar copiando os dados um por um.

## Uso
* Baixe a versão mais [recente](https://github.com/felipesdreis/gerador_hosts/releases) e descompacte
* Copie a planiha na Raiz da pasta do programa
* Execute o arquivo genhosts.exe

1. Digite o nome da planilha (exemplo: lista_de_servidores.xlsx)
2. Digite o nome da aba em que estão as informações
3. Qual a letra da coluna que estão os hostnames
4. Qual a letra da coluna que estão os IPs
5. Qual o numero da linha que os dados começam

Pronto um arquivo hosts.txt será gerado, é só copiar os dados para o seu arquvo hosts do windows **C:\Windows\System32\drivers\etc\hosts**