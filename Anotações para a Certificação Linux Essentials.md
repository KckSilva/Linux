### LPI Linux Essentials: Preparatório para a Certificação

Link dos objetivos cobrados na Prova:

**<https://www.lpi.org/pt-br/our-certifications/exam-010-objectives>**

##

##### Abaixo estão as anotações referente ao curso preparatório para a certificação Linux Essentials

- File System Hierarchy (FHS)

No Linux só é possível um diretório principal "/" e dentro dele os demais diretórios. Mesmo que tenha mais de um disco, só o "/" pode ser o diretório principal.

**/** é todo o sistema operacional. Equivale ao "C:"

**bin** é a mesma coisa que um executável no Windows. Todos os binários que o usuário pode usar, está dentro do bin.

**/boot** Desde a bios até o sistema ficar pronto todos os processos responsáveis para o sistema funcionar estão aqui dentro. Aqui fica tudo que é relacionado ao boot do sistema.

**/dev** Todos os dispositivos do sistema ficam aqui dentro. É onde ficam todos os dispositivos que são conectados no computador.

**etc** É um diretório de configuração. Todos os pacotes/programas instalados. Sempre que um programa for instalado será criado uma pasta nesse diretório e é onde ficará fácil para a manutenção ou ajustar a configuração.

**home** é onde ficam os usuários e os arquivos pessoais de cada um dos perfis daquele usuário. Cada usuário possui o seu.

**lib e lib64** São as "dlls" (.so ou .o) é aqui onde as bibliotecas de um programa são distribuídas.

**media** Onde são montados, automaticamente, os dispositivos. Cada dispositivo precisa ser montado no Linux se não tiver a opção de montar automaticamente, estiver ligado.

**mnt** é onde são montadas as mídias temporárias. Parece com o media, mas é diferente por ser temporário.

**opt** é onde são colocados os pacotes externos, que não são instalados pelo repositório do sistema, é instalado aqui.

**proc** é um pseudo sistema de arquivos. É aqui onde é possível adquirir informações sobre o hardware. É usado pelo sistema para gerenciamento de processos e gerenciamento de hardware.

**root** é o /home do usuário root do sistema. Recebe as mesmas configurações do diretório home.

**run** São colocados arquivos que estão rodando nesse momento no sistema. Ele é temporário.

**sbin** São binários do sistema

**sys** Tem informações de drivers, hardware e é um diretório que não usamos, mas é usado pelo sistema.

**user** tudo que pode ser instalado no sistema, mas que é relacionado ao usuário. Dessa forma, ele é instalado apenas pro usuário e não para os demais.

**var** Possui diversos usos. Desde filas de impressão até outras informações que ficam em fila.
