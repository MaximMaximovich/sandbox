/index.php, /local/templates/main/components/bitrix/form.result.new/custom - форма, обратной связи на основе модуля Веб-формы. Моменты: кастомные валидаторы для бека, пример валидации на фронте, отправка по ajax, капча битрикс, своя верстка для шаблона, попап на снове стандартного битрикс.

/feedback/index.php, local/components/qperfect/feedback.form - Форма обратной связи на основе кастомного компонента. Моменты: работа Action в классе компонента, проброска основных и доп параметров в Action, вариант валидации на беке и фронте, google recaptcha, запись в ИБ и отправка письма, обработка ошибок в классе.

/news/index.php, urlrewrite.php - вывод новостей с учетом разделов с использованием простых компонентов, проброска параметров между компонентами

/news3/index.php, urlrewrite.php - то же самое, что и в предыдущем пункте, но с использованием комплексного компонента catalog

/news4/index.php, /local/templates/main/components/bitrix/news, /local/templates/main/components/bitrix/news.list/news4, urlrewrite.php - вывод, новостей при помощи комплексного компонента news. Для получения заголовка выполняется один запрос в базу, получающий самую старую и самую свежую новость

/news5/index.php, /local/templates/main/components/bitrix/news.list/filtered_news - связка main.ui.filter и news.list

/local/components/qperfect/simple.list/component.php - пример запроса с JOIN для получения PREVIEW_PICTURE
