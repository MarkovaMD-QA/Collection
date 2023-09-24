# Collection
<p><b>Информация об использовании API-коллекции:</b></p>
<p><li>Для начала работы с методами вам потребуется создать API-ключ: <a href="https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#about-personal-access-tokens">Инструкция</a></li></p>
<p><li>Постоянная переменная {{token}} - указать полученный API-ключ текущего пользователя. Указать переменную во вкладке Authorization > Type > Bearer token</li></p>
<p><li>Постоянная переменная {{owner}} - указать логин текущего пользователя</li></p>
<p><li>Постоянная переменная {{repo}} - указать наименование репозитория</li></p>
<p><li>Временная переменная {{issue_number}} - сохраняет номер созданного issue для последующих запросов на его изменение</li></p>

<p><b>Удалить issue с помощью API нет возможности согласно документации: <a href="https://docs.github.com/en/rest/issues/issues?apiVersion=2022-11-28#about-issues">Issues</a></b></p>
<p>Необходимо удалить issue непосредственно через репозиторий: <a href="https://docs.github.com/en/issues/tracking-your-work-with-issues/deleting-an-issue">Инструкция</a></p>
