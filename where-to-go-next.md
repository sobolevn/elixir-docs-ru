---
title: Куда двигаться дальше
---

# {{ page.title }}

Хотите изучить Эликсир глубже? Продолжайте читать!

## Сделайте свой первый проект на Эликсире

Для того, чтобы начать ваш первый проект, в поставке Эликсира есть инструмент сборки Mix. Вы можете начать новый проект запустив:

```bash
$ mix new path/to/new/project
```

Мы написали руководство, которое объясняет, как сделать приложение на Эликсире, с его собственным деревом супервизора, конфигурацией, тестами и прочим. Приложение работает с распределенным хранилищем ключ-значение, в котором мы объединяем пары ключ-значение в "корзины" (buckets) и распределяем эти "корзины" между несколькими нодами:

* [Mix и OTP](/getting-started/mix-otp/introduction-to-mix.html)

## Мета-программирование

Эликсир - расширяемый и глубоко кастомизируемый язык программирования, благодаря поддержке мета-программирования. Большая часть мета-программирования в Эликсире основана на макросах, которые очень полезны в некоторых ситуациях, особенно при написании DSL. Мы написали небольшое руководство, которое объясняет основы работые макросов, показывает, как писать макросы, и как их использовать для создания DSL:

* [Мета-программирование в Эликсире](/getting-started/meta/quote-and-unquote.html)

## Сообщество и другие ресурсы

У нас есть раздел ["Обучение"](/learning.html), где мы рекомендуем книги, скринкасты и другие ресурсы для изучения Эликсира и его экосистемы. Есть и другие ресурсы, например, конференции, проекты с открытым исходным кодом и прочие материалы, предоставляемые сообществом.

Не забывайте и о возможности взглянуть на [исходный код самого Эликсира](https://github.com/elixir-lang/elixir), Который написан в основном на Эликсире (главным образом директория `lib`), или [исследовать документацию](/docs.html).

## A byte of Erlang

Elixir runs on the Erlang Virtual Machine and, sooner or later, an Elixir developer will want to interface with existing Erlang libraries. Here's a list of online resources that cover Erlang's fundamentals and its more advanced features:

* This [Erlang Syntax: A Crash Course](/crash-course.html) provides a concise intro to Erlang's syntax. Each code snippet is accompanied by equivalent code in Elixir. This is an opportunity for you to not only get some exposure to Erlang's syntax but also review some of the things you have learned in this guide.

* Erlang's official website has a short [tutorial](http://www.erlang.org/course/concurrent_programming.html) with pictures that briefly describe Erlang's primitives for concurrent programming.

* [Learn You Some Erlang for Great Good!](http://learnyousomeerlang.com/) is an excellent introduction to Erlang, its design principles, standard library, best practices, and much more. Once you have read through the crash course mentioned above, you'll be able to safely skip the first couple of chapters in the book that mostly deal with the syntax. When you reach [The Hitchhiker's Guide to Concurrency](http://learnyousomeerlang.com/the-hitchhikers-guide-to-concurrency) chapter, that's where the real fun starts.