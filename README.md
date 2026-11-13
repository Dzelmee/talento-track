# norte / people

Criei este projeto para explorar uma interface de organização de registros de recrutamento. A ideia foi reunir cadastro, consulta e acompanhamento das informações em uma página responsiva.

## Funcionalidades

- Criar, editar, buscar e excluir registros.
- Validar entradas no servidor e manter os dados em arquivo JSON local.
- Exibir indicadores calculados a partir dos registros existentes.
- Alternar entre temas claro e escuro, com preferência salva no navegador.
- Navegar por uma interface responsiva com animações que respeitam a preferência de movimento reduzido.

## Tecnologias

HTML, CSS, JavaScript com ES Modules e Node.js (servidor HTTP nativo).

## Rodar localmente

```bash
npm test
npm start
```

Abra `http://localhost:3000`. A porta pode ser alterada com `PORT`.

## Limitações

É uma demonstração de portfólio, não um sistema de recrutamento pronto para uso real. Não inclui autenticação, controle de acesso por usuário ou banco de dados de produção. Os dados são mantidos em JSON local, e as fotografias externas dependem de conexão com a internet.

## Imagens

Fotografias do [Unsplash](https://unsplash.com/license):

- https://images.unsplash.com/photo-1521737711867-e3b97375f902?auto=format&fit=crop&w=1600&q=85
- https://images.unsplash.com/photo-1551836022-d5d88e9218df?auto=format&fit=crop&w=1100&q=85
