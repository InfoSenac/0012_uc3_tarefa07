# Restauração Do Sistema — UC 3

* **Aluno(a):** Giovani do Nascimento Fernandes
* **Tema:** Restore


## 1. Objetivo

Para restaurar o sistema, você precisará conectar o Pendrive bootável na entrada USB e dar o boot na mídia USB. Uma vez iniciado o boot, deve-se seguir os passos para inicializar o Clonezilla. Quando aparecer a tela inicial do Clonezilla, indique o local onde a imagem está salva, depois selecione o modo de restauração (device-image ou local_dev), por fim informe o tipo de restauração (HD inteiro ou uma partição específica) e siga as etapas de restauração.


## 2. Ferramentas e Cuidados Técnicos
* **Ferramentas / Softwares:** 

    Para fazer o backup vamos precisar de: SSD, Pendrive, Clonezilla, Rufus.

* **Segurança / Boas Práticas:** 

    - Selecionar com cuidado o disco de destino.
    - Verificar se o disco de destino possui tamanho igual ou superior ao da imagem do backup.
    - Verificar e/ou manter a energia estável.


## 3. Passo a Passo
1. Baixar o Rufus e o Clonezilla
2. Formatar o Pendrive
3. Criar um Pendrive bootável
4. Reiniciar o computador selecionando o Pendrive como boot
5. Siga as etapas para inicializar o Clonezilla 
6. Fazer o clone do sistema dentro do SSD, selecionando as seguintes etapas:
- selecionar device-image → local_dev (apontando para a mídia onde está a imagem salva) → escolher restoredisk → selecionar a imagem e o disco de destino
7. Verificar se a clonagem deu certo
8. Caso tenha ocorrido algum erro, repita os passos 4 a 7


## 4. Como Validar (Teste Final)
- [ ] Teste 1: Verificar se aconteceu alguma mensagem de erro durante a restauração.
- [ ] Teste 2: Após a restauração, reinicie o sistema operacional para verificar se o processo foi bem-sucedido.
- [ ] Teste 3: Comparar o tamanho e a quantidade de arquivos do SSD do computador e o SSD onde foi feita a cópia.