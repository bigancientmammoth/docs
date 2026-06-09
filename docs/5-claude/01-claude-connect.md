

# Общая информация

В этом разделе описано подключение ИИ-агентов (Claude, ChatGPT, Gemini и др) к платформе Marketaut.

В качестве примера используется Anthropic Claude. При этом большинство современных ИИ-агентов поддерживают протокол [MCP](https://modelcontextprotocol.io/docs/getting-started/intro) и могут подключаться через платформу Marketaut к вашему магазину Wildberries.


# Подключение

1) Запустите приложение **`Claude for Desktop`**
2) В разделе Chats выберите **`Customize`**. 
![](img/customize.png)



3) В открывшемся окне выберите **`Connectors`**. 
**Connectors** — это подключения ИИ к внешним системам. С их помощью Claude может взаимодействовать с различными сервисами, включая Wildberries через платформу MarketAut.
![](img/connect/customize-connectors.png)

В открывшемся окне отображается список уже подключённых **`connectors`**.
4) Для подключения нового connectors нажмите **(+)**, затем в открывшемся меню выбирите **`Add custom connector`**.
![](img/connect/connectors-add.png)

Откроется окно настроек connectors. 

Укажите следующие значения:
**Имя** - любое название на ваш выбор, например **`MarketAut`**.
**Адрес** -**`https://marketaut.ru/mcp/wb`**.

После заполнения полей нажмите **`Add`**.

![](img/connect/connector-dialog.png)


После добавления connector **MarketAut** появится в списке, но будет отображаться как неподключенный.
Нажмите **Connect**, чтобы установить подключение.

![](img/connect/not-connected.png)


Вы будете перенаправлены на страницу авторизации **MarketAut**. 
Нажмите **Разрешить доступ**.

![](img/connect/oauth-consent.png)


После завершения проверки connector будет отображаться как подключённый.

![](img/connect/connected.png)
