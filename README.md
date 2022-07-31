# Tradução Laravel para português(pt-BR)

> Mensagens padrões do Laravel em português.

[![GitHub issues][issues-image]][issues-url]
[![License][license-image]][license-url]

Arquivos de tradução para todas as mensagens padrões do [Laravel](https://laravel.com/) à partir da versão 5+, suportando até a versão atual (8+).


## Traduções Inclusas

- Erros de `validação`.
- Textos de `paginação`.
- Textos de falhas de `autenticação`.
- Textos de `redefinição de senhas`.


## Como utilizar

Clone o projeto para dentro do diretório **resources/lang/** do seu projeto Laravel, nomeando à pasta como **pt-br**:

```shellscript
git clone https://github.com/k7brasil/Laravel-pt-BR ./resources/lang/pt-br
```

Então, edite o arquivo **config/app.php** para alterar o idioma padrão da sua aplicação:

```php
// encontre a seguinte linha:
'locale' => 'en',

// e altere para:
'locale' => 'pt-br',
```

Pronto! Seu projeto agora estará em português. :tada:


## Meta

Distributed under the MIT license. See [LICENSE](https://github.com/k7brasil/Laravel-pt-BR/blob/master/LICENSE) for more information.


## Contributing

1. Fork it (<https://github.com/k7brasil/Laravel-pt-BR/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

[issues-image]: https://img.shields.io/github/issues/k7brasil/Laravel-pt-BR.svg
[issues-url]: https://github.com/k7brasil/Laravel-pt-BR/issues
[license-image]: https://img.shields.io/github/license/k7brasil/Laravel-pt-BR.svg
[license-url]: https://github.com/k7brasil/Laravel-pt-BR/blob/master/LICENSE
