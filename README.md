<h1 align="center">єПотреба</h1>


<p align="center">
Мобільний додаток для платформи Android забезпечує можливість користувачам швидко знаходити найближчі санвузли за допомогою інтерактивної карти. Він також дозволяє користувачам залишати свої відгуки про обрані вбиральні та створювати персоналізований список улюблених санвузлів.
</p>


# ![demo](https://github.com/sspaceless/e-potreba/blob/main/docs/app-demo.png?raw=true)


<h1>Навігація</h1> 

* [Технології](#Технології)
* [Встановлення](#Встановлення)
* [Команда](#Команда)
* [Огляд єПотреба](#Огляд)


<h1>Технлогії</h1>

- **Платформа**: Android & Firebase
- **Android API**: 31
- **IDE**: Android Studio, VS Code
- **Мова**: Kotlin + KTX
- **Аутентифікація**: Firebase Auth (*Phone Provider*)
- **Дизайн**: Figma
- **Організація процесу розробки**: Miro, GitHub
- **Шрифт**: [Fixel Font](https://fixel.macpaw.com/?gclid=Cj0KCQjw_r6hBhDdARIsAMIDhV-hiscld-F8_wp7oukBdCr8XKNrSkMZ4hbsxe1RnMrTb_Kx2mePRfwaAmNIEALw_wcB) 

<h1>Встановлення</h1>

Перейти в розділ release, завантажити .apk файл.


<h1>Команда</h1>

Над даним проєктом працювала творче об'єднання єКоманда:
* Боднар Ілля - розробка UI, організація;
* Неживих Марія - розробка дизайну, тестування;
* Марковський Данило - розробка бізнес логіки, архітектури, налаштування бекенд сервісів.


<h1>Огляд</h1>

<div align="justify">

Застосунок "єПотреба" створений з урахуванням загальної потреби у знаходженні публічних та будь-яких інших вбиралень у межах міста. Крім того, цей додаток надає можливість користувачам формувати власні списки улюблених вбиралень і оцінювати їх за п'ятибальною шкалою.

</div>

<b>🚧Дана робота є курсовим проєктом з курсу "Програмування мобілних пристроїв", а також є підсумковою роботою за курс.</b>

---

<h2>Ітерфейс застосунку</h2>

<div align="justify">

Взаємодія відбувається через ключові вікна продукту, таких як: 
<b><i>
авторизація користувача, група вікон з відображенням маркерів вбиралень, вікно детального огляду маркеру та вікно профіля користувача
</i></b>

</div>


![demo](https://github.com/sspaceless/e-potreba/blob/main/docs/demo/demo_interface.png?raw=true)


---
## **Перший вхід** 

<div align="justify">
Перед тим як скористатись функціоналом цього дивовижного продукту треба пройти нескладний процес авторизації на сервісі. Для цього вам знадобиться номер телефон та зв'язок з мережою оператора.

</div>
</br>

<table>

<tbody>
  <tr>
    <td><img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_sign_in_phone.jpg"></td>
    <td><img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_sign_in_code.jpg"></td>
  </tr>
</tbody>
</table>


---
## **Вікно вбиралень поруч**

<div align="justify">
В даному меню на взір користувачу надана інтерактивна мапа з відмітками вбиралень поруч з ним. За допомогою даної карти можна швидко побудувати маршрут до обраого місця шляхом кліку на маркер та вибору відповідної кнопки у правій нижній частині мапи.
</div>
</br>

<div align="center">
    <img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_near.jpg" width="400" height="800">
</div>

---
## **Список вбиралень** 

<div align="justify">
Іноді буває що немає часу на розгляд файних маркерів на рідній карті міста, адже потреби є нагальні. Для такого є відповідне меню де ви можете одразу обрати найкраще місце для вирішення власних потреб. </br> </br>
Вашому зіру представлена вся потрібна інформація про вбиральну: <b>рейтинг</b>, <b>оплата</b>, <b>відстань</b> та <b>назва</b>.
Також легким натиском на маркер ви можете побачити всю детальну інформацію про обрану вбиральну разом з цим у вас є швидкий доступ до оцінювання якості задовільнення ваших потреб.
</div>
</br>

<table>

<tbody>
  <tr>
    <td><img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_tolist.jpg"></td>
    <td><img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_details.jpg"></td>
  </tr>
</tbody>
</table>

---
## **Профіль користувача** 

<div align="justify">
Який застосунок про вбиральні й без особистого простору? У власному профілі ви можете усамітнитись з собою та оцінити вашу продуктивність на платформі: побачити створені вами маркери, обрані вбиральні, які б ви відвідали ще не один раз.</br></br>
Також у вас є можливість в будь-який момент відредагувати інформацію про ваш профіль. Наприклад змінити власного ім'я чи номеру телефону, щоб здатись зовсім за іншу людину

</div>
</br>

<table>

<tbody>
  <tr>
    <td><img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_profile_favorite.jpg"><td>
    <td><img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_profile_owned.jpg"></td>
  </tr>
</tbody>
</table>

<div align="center">
    <img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_profile_edit.jpg" width="400">
</div>

---
## **Створення маркерів** 

<div align="justify">
Волонтрество наше все!

Кожний з користувачів має необмежений та безкоштовний дотсуп до створення нових позначень на карті будь-якого міста, країни чи навіть материку. Для цього потрібно знати дві речі: що таке <b>довгота</b> з <b>широтою</b> та як їх визначати.

</div>
</br>

<table>

<tbody>
  <tr>
    <td><img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_create_marker_but.jpg"></td>
    <td><img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_Create_marker.jpg"></td>
  </tr>
</tbody>
</table>

---
## **Оцінювання та редагування маркерів** 

<div align="justify">
Супсільна думка дуже важлива річ у ділі вибору місця суспільного зібрання, тому ми надали вам зручну можливість залишити власну оцінку обраному маркеру.

Також, якщо ви є власником маркеру ви зможете без зайвих зусиль відновити історичну несправедливість.

</div>
</br>

<table>

<tbody>
  <tr>
    <td><img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_marker_vote.jpg"></td>
    <td><img src="https://github.com/sspaceless/e-potreba/blob/main/docs\demo\demo_marker_edit.jpg"></td>
  </tr>
</tbody>
</table>



