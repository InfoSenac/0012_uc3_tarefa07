# Restauração de imagens (restoredisk) utilizando o Clonezilla - UC3
- Aluno: Pedro Henrique Araújo de Sousa
- Tema: Restauração de imagens (restoredisk)
## 1. Objetivo
É usado para criar uma cópia integral de todos os dados,arquivos e configurações do disco, permitindo restaurar o sistema exatamente como estava.
## 2. Ferramentas e Cuidados Técnicos
- Ferramentas / Softwares: Clonezilla
- Segurança / Boas Práticas: Preparar o ambiente, validar discos e mídia, garantir integridade da imagem, armazenar em local seguro, testar a restauração e monitorar erros continuamente.
## 3. Passo a Passo
1. Preparação do ambiente e verificação prévia 
Esta fase garante que o backup seja iniciado sem riscos, seguindo a lógica de preparação e pré‑requisitos presente em modelos de instruções de trabalho 
- Identifique o disco de origem e o destino

Confirme qual disco será copiado e qual receberá a imagem. Evita sobrescritas acidentais.
- Verifique o tipo de partição (MBR/GPT)

Essencial para compatibilidade na restauração.
- Confirme espaço disponível no destino
2. Execução do backup de imagem (savedisk)
Seguindo o princípio de passos numerados e claros descritos nos modelos de guia passo a passo.
- Incialize a ferramenta (boot ou modo desktop)

Clonezilla → inicialização via USB/ISO.
- Selecione o modo de imagem completa 

 device-image → savedisk.
 - Escolha o disco de origem

 Confirme cuidadosamente — Clonezilla apaga totalmente o destino se selecionado errado.
- Escolha o destino da imagem 
Disco interno, NAS ou pasta protegida
- Inicie o processo e aguarde a conclusão 
Não utilize o computador durante o backup, exceto quando a ferramenta suporta VSS
## 4. Como Validar (Teste Final)
Use a opção de verificação da imagem no Clonezilla, valide o CRC com ocs‑chkimg/partimage.chkimg e confirme o boot e integridade do sistema após restaurar.
