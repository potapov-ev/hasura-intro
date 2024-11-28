<img width="297" alt="image" src="https://github.com/user-attachments/assets/b804f4c8-34b2-424f-984a-63c378906d12">### Степпер
Удалить xsl и стили  
https://github.com/hhru/xhh/blob/4161a22b6160de84afb658529e0b6df89472c0a2/xhh/xsl/content/employer/invoice/purchase.xsl#L27  

Новый компонент на основе прогресс бара  
https://magritte-ds.ru/?path=/docs/components-progressbar--docs

### Выбор типа активации
*Логика не меняется*

Заменяем чекбокс  
<img width="259" alt="image" src="https://github.com/user-attachments/assets/19a9e932-f7bb-4b42-939b-370b16f7adb5">  
на CheckableCard  
<img width="475" alt="image" src="https://github.com/user-attachments/assets/7ff10084-c98e-4187-8dc7-111eb8190765">  
С тултипом при ховере на "Когда активировать"

### Таблица с сервисами
Магритовская таблица сейчас неготова, Катя Осипова сказала, что ориентировочно будет готов в начале-середине декабря  

Редизайн таблицы, текстовки для продуктов не меняем

#### Цена изменится 
Если в acticaionInfo хотя бы для одного из сервисов пришли `bestPriceBefore` и `bestPriceBeforeNextDate` показываем такие баннеры  
<img width="567" alt="image" src="https://github.com/user-attachments/assets/cc870bae-0a80-462e-89aa-b498e74848b3">  
<img width="766" alt="image" src="https://github.com/user-attachments/assets/a3f1b637-1b41-460d-8bdd-a4e420f9a5ec">

При выборе даты активации после даты изменения цены показываем модалку  
Нужно будет заменить Uncontrolled версию дате пикер на Controlled  
https://github.com/hhru/xhh/blob/8f22dbad0fa5922e498285b035cebc126f8963f3/src/components/InvoiceCartTable/Activation/ActivationDatePicker.tsx#L30  
<img width="356" alt="image" src="https://github.com/user-attachments/assets/688fd11d-a7f9-4324-b2dd-ab2b22f5dd6d">  
Для модалки делаем ноту `Unseen()`  

Если все таки выбрал дату - показываем возле цены предупреждение  
<img width="104" alt="image" src="https://github.com/user-attachments/assets/64575d5c-590d-4d04-a156-a678f8419389">  

#### Продукт перестанет существовать 

Другие текстовки в баннере
<img width="685" alt="image" src="https://github.com/user-attachments/assets/f39c0735-7f7a-4cd8-b968-4ce3a24ccc6d">  
<img width="690" alt="image" src="https://github.com/user-attachments/assets/a74bc237-6107-4659-a269-4d7062343510">  

Подпись под типом активации  
<img width="345" alt="image" src="https://github.com/user-attachments/assets/0a07b3ab-ea7e-4029-9876-e21137207c35">  

В календаре добавляем текст и блокируем даты  
<img width="297" alt="image" src="https://github.com/user-attachments/assets/880215f0-0a00-40b8-9a3f-a4b1da4fd03e">  

#### Смешанный кейс
Меняем тексты в баннерах, остальное по флоу выше  
<img width="513" alt="image" src="https://github.com/user-attachments/assets/4da77fb2-d336-4eb2-957e-5cbad79ed106">
 





### Блокеры
Не готова таблица в магрите  
Катя Осипова сказала, что ориентировочно будет готов в начале-середине декабря
