### University: ITMO University
### Faculty: FTMI Course: Cloud platforms as the basis of technology entrepreneurship
### Year: 2024
### Group: U4125
### Author: Kopeikina Anastasiia Alexandrovna
### Lab: Lab4
### Date of create: 28.04.2024
### Date of finished: 
![image](https://github.com/KopeikinaA/2024-cloud-platforms-as-the-basis-of-technology-entrepreurship-4125-kopeikina_a_a/assets/164926706/81e378d2-6a9f-48b0-af93-1483581a2eaa)
### Начальное состояние (до 40 человек)
#### Virtual Machine: e2-micro 0.25-2 vCPU 1 GB memory ~ 7$
#### SQL Cloud: PostgreSQL 1 vCPU 0.6 GB memory ~ 9$
#### Итог ~ 16$
![image](https://github.com/KopeikinaA/2024-cloud-platforms-as-the-basis-of-technology-entrepreurship-4125-kopeikina_a_a/assets/164926706/82e3fd4d-a3c5-4004-9180-7ad5ef9fbbc6)
![image](https://github.com/KopeikinaA/2024-cloud-platforms-as-the-basis-of-technology-entrepreurship-4125-kopeikina_a_a/assets/164926706/7247eaf2-2c84-44c4-81fe-16bc4709dce5)

##### Выбор данной конфигурации обусловлен небольшим количеством пользователей и низкими нагрузками на приложение на начальном этапе. Этот тип обеспечивает достаточные ресурсы для запуска и тестирования приложения, не превышая бюджет.
### Тестирование партнёрами (до 150 человек)
#### Virtual Machine: e2-small 0.5-2 vCPU 2 GB memory ~ 13$
#### SQL Cloud: PostgreSQL 1 vCPU 1.7 GB memory ~ 29$
#### Итог ~ 42$
#### Увеличение объема ресурсов, связано с увеличением числа пользователей и, соответственно, с увеличением нагрузки на приложение. Увеличение ресурсов базы данных также обусловлено увеличением нагрузки и объема данных, генерируемых и обрабатываемых приложением при тестировании продукта партнёрами.
### Продовое решение (от 300 человек)
#### Virtual Machine: e2-medium 1-2 vCPU 4 GB memory ~ 25$
#### SQL Cloud: PostgreSQL 1 vCPU 3.75 GB memory ~ 66$
#### Итог ~ 91$
#### Для продового решения необходимы более мощные ресурсы, из-за обработки более высокой нагрузки и увеличения объема данных, с которыми приходится работать на этапе продуктивной эксплуатации.
### Таким образом, на начальном этапе были выбраны VM: e2-micro 0.25-2 vCPU 1 GB memory и SQL Cloud: PostgreSQL 1 vCPU 0.6 GB memory, так как они обеспечивают достаточные ресурсы для начального числа пользователей при минимальных затратах.
На этапе тестирования с партнерами были выбраны более мощные VM: e2-small 0.5-2 vCPU 2 GB memory и SQL Cloud: PostgreSQL 1 vCPU 1.7 GB memory, чтобы обеспечить дополнительные ресурсы при повышенной нагрузке из-за тестирования активного.
На этапе продуктового решения выбраны еще более мощные VM: e2-medium 1-2 vCPU 4 GB memory и SQL Cloud: PostgreSQL 1 vCPU 3.75 GB memory для обеспечения стабильной работы приложения в реальных условиях с большим количеством пользователей.
