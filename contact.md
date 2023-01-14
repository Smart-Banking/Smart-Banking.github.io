---
layout: default
title: Контакти
---

<div id="contact">
  <!--h3 class="pageTitle">Вашето съобщение</h3-->
  <div class="contactContent">
    <p class="intro">Ако имате какво да споделите с потребителите на SMART BANKING, пишете ни.</p>
    <p>Всички полезни материали ще бъдат публикувани на сайта, с Вашето име като автор.</p>
    <p>Благодарим Ви!</p>
  </div>
  <form action="https://formspree.io/f/xyyayvkj" method="POST">
    <label for="name">Име</label>
    <input type="text" id="name" name="Име" class="full-width"><br>
    <label for="email">Email адрес</label>
    <input type="email" id="email" name="Email" class="full-width"><br>
    Област 
    <select name="Локация" id="state" required="">
      <option value="" selected="" disabled="">Изберете</option>
      <option value="София">София</option>
      <option value="Пловдив">Пловдив</option>
      <option value="Варна">Варна</option>
      <option value="Бургас">Бургас</option>
      <option value="Друго" disabled="">------</option>
      <option value="Благоевград">Благоевград</option>
      <option value="Велико Търново">Велико Търново</option>
      <option value="Видин">Видин</option>
      <option value="Враца">Враца</option>
      <option value="Габрово">Габрово</option>
      <option value="Добрич">Добрич</option>
      <option value="Кърджали">Кърджали</option>
      <option value="Кюстендил">Кюстендил</option>
      <option value="Ловеч">Ловеч</option>
      <option value="Монтана">Монтана</option>
      <option value="Пазарджик">Пазарджик</option>
      <option value="Перник">Перник</option>
      <option value="Плевен">Плевен</option>
      <option value="Разград">Разград</option>
      <option value="Русе">Русе</option>
      <option value="Силистра">Силистра</option>
      <option value="Сливен">Сливен</option>
      <option value="Смолян">Смолян</option>
      <option value="Стара Загора">Стара Загора</option>
      <option value="Търговище">Търговище</option>
      <option value="Хасково">Хасково</option>
      <option value="Шумен">Шумен</option>
      <option value="Ямбол">Ямбол</option>
    </select>

    <label for="message">Съобщение</label>
    <textarea name="Съобщение" id="message" cols="30" rows="10" class="full-width"></textarea><br>
    <input type="submit" value="Изпрати" class="button">
  </form>
</div>
