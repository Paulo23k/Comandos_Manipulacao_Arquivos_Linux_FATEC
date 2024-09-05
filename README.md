# Comandos_Manipulacao_Arquivos_Linux_FATEC
Manipulando Arquivos

---------------------------------------------
clear -> limpar a console ou área de trabalho


ls -> listar as entradas de um diretório (list)
ls -l
ls -lh
ls -a
ls -lha

-l = listagem longa
-h = ajusta a exibição para unidades conhecidas (kB,MB) (human)
-a = listagem das entradas ocultas (all)


touch -> criar um arquivo vazio
touch nome_arquivo

cat -> Múltiplas Funções (concatenate)
1a Forma - cat -> Para ler da entrada padrão e escrever na
saída padrão (ctrl d ou ctrl c)

cat -> Para criar um arquivo texto (ASCII)
cat > nome_do_arquivo -> criar arquivo
cat >> nome_do_arquivo -> adicionar conteúdo ao arquivo

cat -> Para exibir o conteúdo do arquivo
cat nome_do_arquivo

cat -> Concatenar conteúdos
cat nomes_dos_arquivos

tac -> Para exibir o conteúdo de um arquivo da última linha para a primeira
tac nome_do_arquivo

cp -> Para copiar arquivos e diretórios (copy)
cp arquivo_original arquivo_novo

mv -> Para alterar o nome de um arquivo ou movê-lo (move)
mv nome_antigo nome_novo <- para trocar o nome
mv nome_arquivo /caminho/nome_arquivo <- para mover o arquivo de um diretório para 
outro

ln -> Para criar links, também chamados de atalhos (link)
ln nome_arquivo nome_atalho

rm -> Para remover arquivos convencionais (remove)
rm nome_do_arquivo
rm lista_de_nomes_de_arquivos

man -> Para ter acesso a um auxílio sobre o comando (manual)
man nome_do_comando
