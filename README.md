# Ураїнська мова для форуму [Flarum](https://flarum.org/)

Пакет містить переклади для Flarum (сумісний з версією `1.0.0` або новішою).

## Встановлення

Встановіть розширення за допомогою [Composer](https://getcomposer.org/):

```
composer require koriaking/flarum-lang-ukrainian
php flarum cache:clear
```

Потім увімкніть розширення в панелі адміністратора.

## Оновлення

Оновлення за допомогою [Composer](https://getcomposer.org/):

```
composer update koriaking/flarum-lang-ukrainian
```

Після оновлення очищаємо кеш:

```
php flarum cache:clear
```

## Знайшли помилку / Відсутній переклад

Про коментарі та помилки можна повідомити на [GitHub](https://github.com/koriaking/flarum-lang-ukranian/issues)

## Кредити

Переклад для Day.js взято посередньо з [джера пакету](https://raw.githubusercontent.com/iamkun/dayjs/dev/src/locale/uk.js).

Переклад `validation.yml` заснований на [мовному пакеті для Laravel](https://raw.githubusercontent.com/Laravel-Lang/lang/master/locales/uk/validation.php).

Також велика подяка `eikoninaru/flarum-ext-ukrainian`, основа перекладу була взяти із їхнього репозиторію [GitHub](https://github.com/eikoninaru/flarum-ext-ukrainian).