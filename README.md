# norte / people

Montei o norte / people para explorar a organização de informações de recrutamento em uma interface web. O foco foi tornar o cadastro e a consulta de registros fáceis de acompanhar, inclusive em telas menores.

## Funcionalidades

- Criar, editar, buscar e excluir registros.
- Validar entradas no servidor e armazenar os dados em JSON local.
- Exibir indicadores calculados com os registros cadastrados.
- Alternar entre temas claro e escuro, mantendo a preferência no navegador.
- Navegar com layout responsivo e animações compatíveis com movimento reduzido.

## Como executar

```bash
npm test
npm start
```

O servidor inicia em `http://localhost:3000`. Para usar outra porta, configure `PORT`.

## Tecnologias e armazenamento

Usei HTML, CSS e JavaScript com ES Modules no front-end. O servidor é feito em Node.js, usando o módulo HTTP nativo. Os registros ficam em um arquivo JSON local.

## Limitações

Esta é uma aplicação de demonstração, não um serviço pronto para produção. Ainda não há autenticação, permissões por usuário nem banco de dados de produção. O armazenamento em JSON também não foi pensado para várias instâncias simultâneas.

## Imagens

Fotografias do [Unsplash](https://unsplash.com/license):
- https://images.unsplash.com/photo-1521737711867-e3b97375f902?auto=format&fit=crop&w=1600&q=85
- https://images.unsplash.com/photo-1551836022-d5d88e9218df?auto=format&fit=crop&w=1100&q=85
