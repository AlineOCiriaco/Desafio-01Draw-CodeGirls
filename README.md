📘 Desafio — Fluxograma AWS (EC2, EBS e S3)
🚀 Descrição

Este desafio teve como objetivo representar graficamente, por meio do draw.io, a relação entre os serviços da AWS estudados em aula.
O fluxograma demonstra como o EC2 utiliza volumes EBS para armazenamento e como os Snapshots desses volumes podem ser salvos no S3 para backup e recuperação.

🛠️ Ferramentas Utilizadas

AWS EC2 → serviço de computação em nuvem (máquinas virtuais).

AWS EBS → volumes de armazenamento associados ao EC2.

AWS S3 → serviço de armazenamento de objetos, usado para guardar snapshots.

Draw.io → ferramenta para criação do fluxograma.

📂 Estrutura do Desafio

Criação do fluxograma representando:

EC2 → instância que roda aplicações.

EBS → disco da instância.

Snapshot → cópia de segurança do volume.

S3 → local onde o snapshot é armazenado.

📖 Aprendizados

Diferença entre computação (EC2) e armazenamento (S3).

O papel do EBS como disco da instância.

Como snapshots funcionam como backups incrementais.

A importância de usar o S3 para resiliência e recuperação de dados.

📌 Próximos Passos

Criar fluxogramas mais complexos envolvendo Lambda para automação.

Explorar outros serviços da AWS, como RDS e CloudWatch.

Aplicar o mesmo conceito em cenários de Disaster Recovery (DR).
