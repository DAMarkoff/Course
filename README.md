Service Station API:
 - Сервер: http://23.88.52.139:5006
 - Swagger: http://23.88.52.139:5006/swagger
 - Database diagram: https://drawsql.app/myowncompany/diagrams/cto

Проект реализуется в рамках авторского курса по тестированию ПО Вадима Ксендзова: https://ksendzov.com/, telegram - @peplomot

Так как в настоящее время проектом занимаюсь я один, то работа продвигается не настолько быстро, как хотелось бы, но я стараюсь, честно :)

Саммари: проект - сервис по предоставлению услуг шиномонтажа и хранению шин на складе.

Если Вы обнаружите в проекте баги, ошибки, неточности, либо у Вас возникнут пожелания или предложения, прошу Вас воспользоваться соответствующими формами:
 - Ссылка на Google форму баг репорта: https://docs.google.com/forms/d/1Nh_-KE00CpirA_I4WLBXR5gWD5Gkl7KaT2u72x2CC7o/edit?usp=sharing
 - Ссылка на ваши предложения: https://docs.google.com/forms/d/1mjiIaQwa0_C0FiihzpKBFCOUvVSR_PjzusJMgmsEQkM/edit?usp=sharing

Что реализовано:
  - Для использования сервиса пользователю необходимо зарегистрироваться
  - после регистрации пользовалель может залогиниться, используя свой email и пароль, созданный при регистрации.
  - пароль не сохраняется в базе данных и средств его восстановления не предусмотрено, так что, в случае его утери, восстановить его возмозжно только с помощью меня.
  - пользователь может добавить свои транспортные средства указав тип ТС и размерность колес
  - пользователь может создать заказ на хранение шин с указанием даты начала и окончания хранения
  - при создании заказа на хранение пользователь указывает размер шин, либо ид своего ТС
  - таким образом, на хранение можно отдать любые шины, не оглядываясь на добавленные им ТС
  - пользователь может изменять и удалять свои заказы на хранение
  - пользователь может запрашивать свою информацию - личные данные, добавленные ТС, заказы на хранение, заказы на сервис, добавленные услуги в заказ на сервис со стоимостью
  - пользователь может создать заказ на сервис
  - пользователь может добавлять услуги в заказ на сервис
  - на каждый заказ на сервис закрепляется менеджер
  - максимальная нагрузка на одного менеджера - 5 заказов на сервис
  - на каждую услугу в заказе на сервис назначается рабочий в зависимости от специализации
  

Что в планах на ближайшее время:
  - спектр услуг будет пополняться
  - будет создан график рабочих с тем, чтобы они не могли нахначаться на работы в одно и то же время
  - будет реализована система подписки
  - по подписке пользователь может в течении года хранить шины, два раза в год пользоваться услугой шиномонтажа и ремонта
  - в раздел менеджера будут доавлены отчеты по тем заказам и рабочим которые на него назначены
  - в раздел директора будут доавлены отчеты по предприятию в разрезе заказов, менеджеров, рабочих, услуг, финансов
  - прочие разности, которые приходят налету, от коллег, друзей, одногруппников и вообще всех неравнодушных и готовых помочь :)

Данный документ будет пополняться по мере и постоянно )

Additional info in Readme.txt
