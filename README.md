# DDD (Domain-drive Design)

Design dirigido à domínio

## Domínio

Domain Experts (Especialistas do Domínio): Pessoas que conhecem profundamente as regras de negócio e ajudam a modelar o sistema corretamente.

Linguagem Ubíqua: Um vocabulário comum entre desenvolvedores e especialistas do domínio para evitar ambiguidades na comunicação e refletir o negócio no código.

Agregados: Conjunto de entidades e objetos de valor que são tratados como uma única unidade de consistência, garantindo regras de integridade.

Value Objects (Objetos de Valor): Representam conceitos do domínio que não possuem identidade única, apenas atributos (exemplo: endereço, dinheiro).

Eventos de Domínio: Representam algo relevante que aconteceu no sistema e pode influenciar outros componentes (exemplo: "Pedido Confirmado").

Subdomínios (Bounded Contexts): Divisão lógica dentro do domínio para evitar acoplamento excessivo e permitir que diferentes áreas do sistema evoluam independentemente.

Entidades: Objetos com identidade única e ciclo de vida distinto (exemplo: um usuário ou pedido).

Casos de Uso: Definem interações do sistema que agregam valor ao usuário, normalmente representando ações importantes no negócio (exemplo: "Criar um Pedido").
