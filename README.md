Додаткові питання
1. Яке основне призначення webpack?
   Webpack — це інструмент для збірки модулів JavaScript, який обробляє і оптимізує ресурси,
   такі як JavaScript, CSS, зображення, шрифти та інші файли, для ефективного використання у веб-додатках.
   Основне завдання Webpack — зібрати файли, які розкидані по різних модулях, у один або декілька бандлів (bundle),
   що зменшує кількість HTTP-запитів, збільшує продуктивність і забезпечує зручну організацію коду.
   
2.Яка різниця між завантажувачами та плагінами?
  Завантажувачі (loaders): використовуються для перетворення файлів перед тим, як вони будуть включені до збірки.
  Вони виконують обробку файлів різних форматів, таких як CSS, зображення, або сучасний синтаксис JavaScript, перетворюючи їх у формат,
  який Webpack розуміє. Наприклад, завантажувачі можуть компілювати SASS або LESS у CSS, або TypeScript у JavaScript.

  Плагіни (plugins): розширюють функціональність Webpack і виконують ширші завдання, які не обмежуються лише перетворенням файлів. 
  Вони можуть впливати на процес збірки загалом, наприклад, оптимізувати файли (мінімізація JavaScript), 
  очищати директорії перед збіркою, генерувати HTML-файли, копіювати файли або створювати глобальні змінні.

3.Наведіть приклади завантажувачів.
   babel-loader — перетворює сучасний JavaScript (ES6+) у більш сумісний з браузерами формат.
   css-loader — дозволяє імпортувати CSS у JavaScript-файли.
   style-loader — додає CSS напряму в DOM через теги <style>.
   file-loader — дозволяє імпортувати файли (зображення, шрифти тощо) у JavaScript.
   sass-loader — компілює SASS або SCSS файли в CSS.
   ts-loader — компілює TypeScript у JavaScript.

4.Наведіть приклади плагінів.
   HtmlWebpackPlugin — автоматично генерує HTML-файл для проекту та додає посилання на зібрані файли.
   CleanWebpackPlugin — очищає вихідну директорію (dist) перед кожною збіркою.
   MiniCssExtractPlugin — виділяє CSS у окремий файл, що зручно для продакшн-збірок.
   DefinePlugin — створює глобальні змінні на рівні збірки, які можуть бути доступні в усіх модулях.
   CopyWebpackPlugin — копіює файли або директорії в кінцеву директорію dist.
   TerserPlugin — мінімізує JavaScript-файли, зменшуючи розмір збірки.
