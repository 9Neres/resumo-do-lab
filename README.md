## Microsoft Azure – Resumo de Conceitos (DIO)

### Conceitos Iniciais

A computação em nuvem (cloud computing) não se refere literalmente a uma “nuvem”, mas sim a servidores e data centers localizados em diferentes partes do mundo, operados por empresas especializadas, como Microsoft (Azure), Amazon (AWS) e Google (GCP).

Essas empresas fornecem acesso remoto a recursos computacionais por meio da internet, permitindo que outras empresas ou usuários utilizem infraestrutura sem precisar mantê-la fisicamente.

### Modelos de Serviço em Cloud

- **IaaS (Infraestrutura como Serviço)**: Você aluga máquinas virtuais, redes e armazenamento. A responsabilidade pela configuração e uso é do cliente.
- **PaaS (Plataforma como Serviço)**: A plataforma já vem pronta para uso com sistemas e ambientes configurados para desenvolvimento e deploy.
- **SaaS (Software como Serviço)**: Softwares prontos, como o Microsoft 365, que o usuário utiliza diretamente pela internet sem se preocupar com instalação ou manutenção.

### Responsabilidade Compartilhada

O provedor (ex: Azure) fornece a infraestrutura, mas o cliente é responsável por como ela será usada — como os dados armazenados, configurações de segurança, conexões com banco de dados etc. Isso garante privacidade, já que o provedor **não tem acesso ao que ocorre dentro do ambiente virtual do cliente**.

### Modelos de Nuvem

- **Nuvem Pública**: Infraestrutura compartilhada por vários usuários. É mais acessível, escalável e paga-se apenas pelo uso. Ex: Azure, AWS.
- **Nuvem Privada**: Ambiente exclusivo de uma empresa, com maior controle e segurança. Pode ser hospedada localmente ou por um provedor.
- **Nuvem Híbrida**: Combinação das duas anteriores. Permite escolher o que manter público e o que manter privado, ideal para flexibilidade e segurança. Pode ser comparada, de certa forma, ao conceito de **encapsulamento** na programação orientada a objetos (POO), onde você escolhe o que expor e o que manter oculto.
