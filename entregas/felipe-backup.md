Backup e Restauração de Máquinas.

Aluno(a): Felipe Alves Soares
Tema: Backup e Restore

1. Objetivo

A manutenção nos computadores é algo muito importante já que influencia muito no caso de backups, criação de novas máquinas de forma rápida e prática, também facilitando o serviço de Técnicos de Informática, colaborando assim no total tanto com o desenvolvimento de uma prática rápida e também segura uma vez que o download é feito pela rede, fazendo assim com que apenas dispositivos conectados na rede local do clonezilla possam baixar a manutenção.

2. Ferramentas e Cuidados Técnicos

Ferramentas / Softwares: Pode ser utilizado o uso de cabos de rede para conectar as máquinas e um USB com clonezilla instalado

Segurança / Boas Práticas: Para a segurança é recomendado usar luvas antiestáticas, USBs de backups em caso de algum erro, verificar bem a conexão dos cabos e ter cuidado sempre com curto circuitos.

3. Passo a Passo do Backup e Restore
1- O primeiro passo seria confirmar que todas as máquinas estão conectadas pela mesma rede e se a máquina que irá compartilhar a manutenção.

1- O segundo passo seria ligar a máquina e configurar para que a máquina que teria o servidor fosse programada para compartilhar o download para as outras máquinas, assim entregando a manutenção completa, selecionando para esperar o número total de dispositivos assim preparando o arquivo.

1- O terceiro passo seria interligar as outras máquinas e conectá-las ao servidor e assim garantir que o download interno fosse feito com segurança.

4. Como Validar (Teste Final)

Para validar que o backup ocorreu corretamente, tem algumas etapas: Primeiramente iremos iniciar as máquinas clientes e ver como a inicialização ocorre. Se tem erros ou se demonstra algum tipo de arquivo ou configuração da versão anterior.
Segundamente teríamos de analisar as configurações internas e fazer as comparações com o estado da máquina atual, podendo ser feito pelo SSH conectado pelo clonezilla assim exercendo comandos para as outras máquinas, especialmente "cat" e "grep" para localizar e procurar por possíveis diferenças em arquivos internos.