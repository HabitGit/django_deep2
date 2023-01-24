# django_deep2
<p><h1>Django learnin deep</h1></p>

<ul type='circle'><h3>Стандартный Django project, короткая информация где что лежит:</h3>
<li>>>/django_deep/templates - темплейт директория в которой будут собираться все медиа файлы, css, html и прочее..</li>
<li>Внутри:</li>
<li>oAuth.html - страница с ссылкой на авторизацию через githab</li>
<li>>>/django_deep/django_deep/ - Корень проекта с settings и ulrs файлами.</li>
<li>>>/django_deep/store/ - Первое и основное приложение. Пока в тестовом формате, не отвечает за функционал всего приложения. Внутри:</li>
<li>models.py - Модели созданные для БД</li>
<li>views.py - вью для моделей</li>
<li>serializer.py - сереалайзер для api </li>
<li>permissions.py - права доступа к модели в БД</li>
<li>../tests - Директория с юнит тестами</li>
<li>../migrations - Директория с миграциями который django создает себе сам, при импорте моделей в БД</li>
  </ul>
