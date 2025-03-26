# bonustime_mode
html

есть рабочий код 

<div style="background: #ffffff; border: 2px solid #ffb6c1; border-radius: 10px; padding: 20px; box-shadow: 0 2px 5px rgba(255,182,193,0.5); text-align: center;">
  <div class="u-container-content u-pd-top-3 u-pd-bottom-3">
    <div class="header">
      <p class="logo">Capybara Princess</p>
      <div class="button" id="wonderButton">
        Узнать чудо
      </div>
    </div><img class="image" src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%22400%22%20height%3D%22400%22%20viewBox%3D%220%200%20124%20124%22%20fill%3D%22none%22%3E%3Crect%20width%3D%22124%22%20height%3D%22124%22%20rx%3D%2224%22%20fill%3D%22%23F97316%22%2F%3E%3Cpath%20d%3D%22M19.375%2036.7818V100.625C19.375%20102.834%2021.1659%20104.625%2023.375%20104.625H87.2181C90.7818%20104.625%2092.5664%20100.316%2090.0466%2097.7966L26.2034%2033.9534C23.6836%2031.4336%2019.375%2033.2182%2019.375%2036.7818Z%22%20fill%3D%22white%22%2F%3E%3Ccircle%20cx%3D%2263.2109%22%20cy%3D%2237.5391%22%20r%3D%2218.1641%22%20fill%3D%22black%22%2F%3E%3Crect%20opacity%3D%220.4%22%20x%3D%2281.1328%22%20y%3D%2280.7198%22%20width%3D%2217.5687%22%20height%3D%2217.3876%22%20rx%3D%224%22%20transform%3D%22rotate(-45%2081.1328%2080.7198)%22%20fill%3D%22%23FDBA74%22%2F%3E%3C%2Fsvg%3E" alt="Capybara SVG">
    <div class="advice" id="adviceBlock"><span class="phrase">Открыть мир сказки!</span> <img class="cursor" src="https://code.s3.yandex.net/web-code/cursor.gif" alt="Мигающий курсор"></div>
    <p class="footer">© 2025 Capy Love</p>
  </div>
</div>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;700&display=swap');
  .header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background-color: #ffe6f2;
      padding: 10px 20px;
      border-radius: 10px;
  }
  .logo {
      font-family: 'Dancing Script', cursive;
      font-weight: bold;
      font-size: 24px;
      color: #ff69b4;
  }
  .button {
      width: 130px;
      height: 40px;
      line-height: 40px;
      text-align: center;
      border: 1px solid #ff69b4;
      background-color: #ffb6c1;
      border-radius: 5px;
      font-size: 14px;
      color: #ffffff;
      cursor: pointer;
      transition: opacity 0.2s;
  }
  .button:hover {
      opacity: 0.8;
  }
  .image {
      width: 80%;
      max-width: 300px;
      display: block;
      margin: 20px auto;
      border: 5px solid #ff69b4;
      border-radius: 10px;
  }
  .advice {
      font-family: 'Dancing Script', cursive;
      font-size: 42px;
      font-weight: bold;
      text-align: center;
      color: #ff69b4;
  }
  .footer {
      font-size: 16px;
      text-align: center;
      color: #ff69b4;
  }
</style>
<script>
  (function(){
      var phrases = [
          { text: 'Пусть сегодняшний день будет наполнен волшебством и радостью!' },
          { text: 'Ты сияешь, как Розовая Пантера!' },
          { text: 'Каждый миг — это маленькое чудо!' },
          { text: 'Жизнь — сказка, и ты — её героиня!' },
          { text: 'Мир вокруг так прекрасен, когда ты улыбаешься!' }
      ];
      var button = document.getElementById('wonderButton');
      var phraseElem = document.querySelector('.phrase');
      button.addEventListener('click', function(){
          var randomIndex = Math.floor(Math.random() * phrases.length);
          phraseElem.textContent = phrases[randomIndex].text;
      });
  })();
</script>

как переделать его если есть script.js и style.css чтобы исходный код код работал как эти файлы и был в их стиле но учитывал правила и условия конструктора Разрешенные тэги:
<a>, <b>, <blockquote>, <br>, <caption>, <code>, <dd>, <del>, <details>, <div>, <dl>, <dt>, <em>, <figcaption>, <figure>, <hr>, <h1>, <h2>, <h3>, <h4>, <h5>, <h6>, <i>, <iframe>, <img>, <ins>, <li>, <ol>, <p>, <picture>, <pre>, <q>, <s>, <script>, <source>, <span>, <strong>, <style>, <sub>, <summary>, <sup>, <table>, <tbody>, <td>, <th>, <thead>, <tr>, <u>, <ul>
Разрешенные атрибуты:
alt, cite, class, colspan, data-*, height, href, id, media, open, rel, rowspan, sizes, src, srcset, style, target, title, type, width
Рекомендованные классы:
Классы ограничения ширины основного контейнера с боковыми отступами:

u-container, u-container-content
Классы, принудительно убирающие отступы:

u-pd-no, u-pd-top-no, u-pd-bottom-no, u-pd-left-no, u-pd-right-no
Классы вертикальных отступов блоков, соответствующие цифре в настройке редакторов:

u-pd-top-1, u-pd-bottom-1, u-pd-top-2, u-pd-bottom-2, u-pd-top-3, u-pd-bottom-3
Классы стандартных горизонтальных отступов:

u-pd-default, u-pd-top-default, u-pd-bottom-default, u-pd-left-default, u-pd-right-default
Классы выравнивания текста:

u-text-left, u-text-center, u-text-right
Класс адаптивной таблицы:

u-table-default
Примечание:
Для создания собственных классов используйте уникальные префиксы, например u-, во избежание наложения сторонних стилей.
