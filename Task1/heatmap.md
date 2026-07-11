# Карта бизнес-возможностей (Business Capability Heatmap)

В таблице ниже представлена карта бизнес-возможностей розничной сети VitaStore (L1/L2). 
Цветовая кодировка строк:
* <span style="background-color: #fde8e8; color: #9b1c1c; padding: 2px 6px; border-radius: 4px; font-weight: bold;">Красный фон</span> — Проблемные зоны 
* <span style="background-color: #def7ec; color: #03543f; padding: 2px 6px; border-radius: 4px; font-weight: bold;">Зеленый фон</span> — Уникальные стратегические возможности

<table>
  <thead>
    <tr style="background-color: #e5e7eb; color: #1f2937; font-weight: bold; text-align: left;">
      <th style="padding: 10px; border: 1px solid #d1d5db; width: 20%;">L1</th>
      <th style="padding: 10px; border: 1px solid #d1d5db; width: 25%;">L2</th>
      <th style="padding: 10px; border: 1px solid #d1d5db;">Статус и описание</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #fde8e8; color: #9b1c1c;">
      <td style="padding: 10px; border: 1px solid #f8b4b4;"><b>Продажи</b></td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Кассовое обслуживание и расчеты (POS)</td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Кассы работают на "толстом клиенте" и требуют локального сервера. При обрыве связи с центральным офисом невозможно рассчитать скидки Promo Engine или принять безналичную оплату.</td>
    </tr>
    <tr style="background-color: #fde8e8; color: #9b1c1c;">
      <td style="padding: 10px; border: 1px solid #f8b4b4;"><b>Продажи</b></td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Прием оплаты (Эквайринг)</td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Разношерстный парк платежных терминалов. Подключение новых точек затягивается из-за доработки драйверов под каждую купленную сеть (до 3 недель).</td>
    </tr>
    <tr style="background-color: #fde8e8; color: #9b1c1c;">
      <td style="padding: 10px; border: 1px solid #f8b4b4;"><b>Маркетинг</b></td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Программы лояльности и промо-акции</td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Промо-движок Promo Engine и лояльность в HQ работают хорошо, но зависят от интернета: при сбоях сети скидки на кассах не рассчитываются, а карты клиентов не принимаются.</td>
    </tr>
    <tr>
      <td style="padding: 10px; border: 1px solid #e5e7eb;"><b>Маркетинг</b></td>
      <td style="padding: 10px; border: 1px solid #e5e7eb;">Ценообразование</td>
      <td style="padding: 10px; border: 1px solid #e5e7eb;">Цены рассчитываются и управляются централизованно через SAP ERP.</td>
    </tr>
    <tr style="background-color: #def7ec; color: #03543f;">
      <td style="padding: 10px; border: 1px solid #bcf0da;"><b>Логистика</b></td>
      <td style="padding: 10px; border: 1px solid #bcf0da;">Омниканальная логистика (Smart Fulfillment)</td>
      <td style="padding: 10px; border: 1px solid #bcf0da;">Доставка товара ближе к покупателю благодаря омниканальной логистике (системе Click&Collect) в сочетании с обширной розничной сетью магазинов "у дома".</td>
    </tr>
    <tr style="background-color: #fde8e8; color: #9b1c1c;">
      <td style="padding: 10px; border: 1px solid #f8b4b4;"><b>Логистика</b></td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Учет остатков и приемка товаров</td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Данные об остатках неактуальны в течение дня из-за синхронизации по FTP раз в сутки. Приемка товаров от разных поставщиков ведется локально без единого регламента.</td>
    </tr>
    <tr style="background-color: #fde8e8; color: #9b1c1c;">
      <td style="padding: 10px; border: 1px solid #f8b4b4;"><b>Учет товаров</b></td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Ведение номенклатуры и интеграция при M&A</td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Справочники товаров разрознены по магазинам. При покупке новых сетей маппинг SKU делается вручную через Excel (VLOOKUP), что занимает до 2 недель и приводит к ошибкам.</td>
    </tr>
    <tr>
      <td style="padding: 10px; border: 1px solid #e5e7eb;"><b>Финансы и отчетность</b></td>
      <td style="padding: 10px; border: 1px solid #e5e7eb;">Бухучет и управленческая отчетность</td>
      <td style="padding: 10px; border: 1px solid #e5e7eb;">Полностью централизованы и стабильно работают на базе SAP ERP.</td>
    </tr>
    <tr style="background-color: #fde8e8; color: #9b1c1c;">
      <td style="padding: 10px; border: 1px solid #f8b4b4;"><b>Финансы и отчетность</b></td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Локальные расчеты и печать ценников</td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Расчет премий продавцам и печать ценников ведутся вручную локально в магазинах, без централизованного контроля.</td>
    </tr>
    <tr style="background-color: #fde8e8; color: #9b1c1c;">
      <td style="padding: 10px; border: 1px solid #f8b4b4;"><b>ИТ-Инфраструктура</b></td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Серверное и сетевое обслуживание магазинов</td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Поддержка 500+ серверов in подсобках отнимает 40% ИТ-бюджета. При сбоях оборудования или сети требуется личный выезд инженера.</td>
    </tr>
    <tr style="background-color: #fde8e8; color: #9b1c1c;">
      <td style="padding: 10px; border: 1px solid #f8b4b4;"><b>ИТ-Инфраструктура</b></td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Поддержка и обновление ПО</td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Обновление кассового ПО и разработка драйверов под новые терминалы делаются вручную и занимают много времени.</td>
    </tr>
    <tr style="background-color: #fde8e8; color: #9b1c1c;">
      <td style="padding: 10px; border: 1px solid #f8b4b4;"><b>Корпоративное развитие</b></td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Интеграция новых точек (M&A)</td>
      <td style="padding: 10px; border: 1px solid #f8b4b4;">Онбординг магазина занимает 2 недели и требует командировки ИТ-бригады. Ручной маппинг товаров (500 SKU/час) несет риски финансовых убытков от ошибок.</td>
    </tr>
    <tr>
      <td style="padding: 10px; border: 1px solid #e5e7eb;"><b>Персонал (HR)</b></td>
      <td style="padding: 10px; border: 1px solid #e5e7eb;">Кадровый учет и оформление сотрудников</td>
      <td style="padding: 10px; border: 1px solid #e5e7eb;">Централизован и стабильно ведется в SAP ERP в центральном офисе.</td>
    </tr>
  </tbody>
</table>
