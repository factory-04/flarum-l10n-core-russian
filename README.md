# Информация

[![Support](https://cdn-storage.github.io/images/common/badges/info.support.svg)](https://webmasters.community/)
[![Documentation](https://cdn-storage.github.io/images/common/badges/info.documentation.svg)](https://flarum.webmasters.wiki/)
[![Source](https://cdn-storage.github.io/images/common/badges/info.source.svg)](https://github.com/factory-04/flarum-l10n-core-russian)
[![Changelog](https://cdn-storage.github.io/images/common/badges/info.changelog.svg)](CHANGELOG.md)
[![Code of Conduct](https://cdn-storage.github.io/images/common/badges/info.coc.en.svg)](CODE_OF_CONDUCT.en.md)
[![Code of Conduct](https://cdn-storage.github.io/images/common/badges/info.coc.ru.svg)](CODE_OF_CONDUCT.ru.md)
[![Contributing](https://cdn-storage.github.io/images/common/badges/info.contributing.svg)](CONTRIBUTING.md)
[![Issues](https://cdn-storage.github.io/images/common/badges/info.issues.svg)](https://github.com/factory-04/flarum-l10n-core-russian/issues)
[![Packagist](https://cdn-storage.github.io/images/common/badges/info.packagist.svg)](https://packagist.org/packages/metastore/flarum-l10n-core-russian)
[![License](https://cdn-storage.github.io/images/common/badges/license.gpl-3.0.svg)](LICENSE)
[![Liberapay](https://cdn-storage.github.io/images/common/badges/donate.liberapay.svg)](https://liberapay.com/metadata/donate)
[![Patreon](https://cdn-storage.github.io/images/common/badges/donate.patreon.svg)](https://patreon.com/metadata)

Пакет русской локализации движка [**Flarum**](https://flarum.org/) - программного обеспечения нового поколения для создания сообществ. Реализована поддержка единичных и множественных чисел (переменных). Все фразы взяты в двойные кавычки для предотвращения конфликтов со знаками препинания, потому что их в русском языке используется большее количество, по сравнению с английским.

## Установка

**Flarum** использует [**Composer**](https://getcomposer.org/) для управления зависимостями и расширениями.

Русский пакет локализации доступен в [**Packagist**](https://packagist.org/packages/metastore/flarum-l10n-core-russian) и может быть установлен при помощи **Composer**.

Убедитесь, что **Composer** установлен на вашем компьютере, и введите следующую команду в терминале, находясь в корневой директории **Flarum**:

```
composer require metastore/flarum-l10n-core-russian
```

Так же, данная команда может быть использована для обновления языкового пакета, без обновления сторонних компонентов.

Обратите внимание, что пакет локализации будет добавлен в качестве зависимости **Flarum**, и он также будет автоматически обновляться при обновлении движка форума.

## Обновление

Для обновления локализации необходимо выполнить следующие команды:

```
composer update metastore/flarum-l10n-core-russian
php flarum cache:clear
```

## Авторы

- [Kitsune Solar](https://kitsune.solar/) - редактор.

## Ссылки

- [Поддержка](https://webmasters.community/)
- [Документация](https://flarum.webmasters.wiki/)
- [Исходный код](https://github.com/factory-04/flarum-l10n-core)
- [Журнал изменений](CHANGELOG.md)
- [Кодекс поведения (EN)](CODE_OF_CONDUCT.en.md)
- [Кодекс поведения (RU)](CODE_OF_CONDUCT.ru.md)
- [Правила участия в разработке](CONTRIBUTING.md)
- [Сообщить о проблеме](https://github.com/factory-04/flarum-l10n-core/issues)
- [Скачать через Packagist](https://packagist.org/packages/metastore/flarum-l10n-core-russian)

## Платформа

- [**METADATA / FOUNDATION**](https://metadata.foundation/) - поддержка и разработка открытых проектов.
- [**METASTORE**](https://metastore.pro/) - хранилище открытых проектов [**METADATA**](https://metadata.foundation/).
