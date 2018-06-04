# Laravel PT-BR Locale (5.6)

Este repositório contém os arquivos de tradução para autenticação (`auth.php`), paginação (`pagination.php`), senhas (`passwords.php`) e validação (`validation.php`) do Laravel. 
No momento, a versão de Laravel suportada por esses arquivos é a versão **5.6**. A pretensão é sempre manter o relatório atualizado e a par das novas versões do framework.

## Usando o Locale

Para usar os arquivos de tradução:
* Copie a pasta `pt-br` para a pasta `resources/lang` (portanto, a partir disso seu diretório `lang` terá provavelmente as pastas `en` e `pt-br`)
* Dê o valor `pt-br` para a variável `locale` no arquivo `config/app.php` (ou seja: `'locale' => 'en',` passa a ser `'locale' => 'pt-br',`)

Caso queira, é possível definir o fuso horário para o mais adequado ao seu estado. Para isso, mude a variável `timezone` para o valor adequado de acordo com os valores suportados pelo PHP, como pode ser visto [aqui, para a lista por continente](http://php.net/manual/en/timezones.php), ou [aqui, para a lista de todos estados do Brasil, observando o campo "TZ"](https://en.wikipedia.org/wiki/Time_in_Brazil).
**Ex.:** para definir o fuso horário baiano, a linha `'timezone' => 'UTC',` passa a ser `'timezone' => 'America/Bahia',`