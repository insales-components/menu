# Меню для платформы InSales

Поддерживаются массивы `linklists` и `blogs`.

```twig
{% include "menu", source_type: 'blogs', source_handle: 'blog', menu_class: 'menu-blog' %}
{% include "menu", source_type: 'linklists', source_handle: 'main-menu', menu_class: 'main-menu' %}
```
