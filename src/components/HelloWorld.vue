<template>
  <div class="hello">

    <header class="header">
      <div class="header_top top-header">
        <div class="top-header_container">
          <div class="top-header_menu menu">
            <!--												<button class="menu_icon icon-menu"><span></span></button>-->
            <nav class="menu_body">
              <ul class="menu_list">
                <li class="menu_item"><a href="" class="menu_link">О нас</a></li>
                <li class="menu_item"><a href="" class="menu_link">Оплата и доставка</a></li>
                <li class="menu_item"><a href="" class="menu_link">Новости</a></li>
                <li class="menu_item"><a href="" class="menu_link">Контакты</a></li>
              </ul>
            </nav>
          </div>
          <a href="#" class="top-header_user _icon-contact">Личный кабинет</a>
          <!--								<button class="icon-menu"><span></span></button>-->
        </div>
      </div>
      <div class="header_body body-header">
        <div class="body-header_container">
          <a href="" class="body-header_logo _icon-logo"></a>
          <div class="body-header_search">
            <form action="#" class="search-header">
              <button class="search-header_button _icon-search"></button>
              <input type="text" class="search-header_input" placeholder="Поиск">
            </form>
          </div>
          <div class="body-header actions-header">
            <a href="" class="actions-header_location _icon-location">Москва</a>
            <div class="actions-header_phones phones-header">
              <div class="phones-header_items">

                <div class="phones-header_item">
                  <a href="tel:8-800-777-49-67" class="phones-header_phone">8-800-777-49-67</a>
                  <ul class="phones-header_list closed">
                    <li><a href="tel:8-800-777-49-68" class="phones-header_phone">8-800-777-49-68</a></li>
                    <li><a href="tel:8-800-777-49-69" class="phones-header_phone">8-800-777-49-69</a></li>
                    <li><a href="tel:8-800-777-49-70" class="phones-header_phone">8-800-777-49-70</a></li>
                  </ul>
                  <button class="phones-header_arrow _icon-arrow"></button>
                </div>
              </div>
              <button class="phones-header_callback">Заказать звонок</button>
            </div>
            <a href="" class="actions-header_favorite _icon-favorite"></a>
            <div class="actions-header_cart cart-header">
              <div class="cart-header_icon _icon-cart"><span>0</span></div>
              <div class="cart-header_body">
                <div class="cart-header_summ">0 р.</div>
                <a href="" class="cart-header_link">Оформить заказ</a>
              </div>
            </div>
          </div>
        </div>
      </div>
  <div class="header_catalog catalog-header">
    <div class="catalog-header_container">
      <nav class="catalog-header_menu menu-catalog">
        <ul class="menu-catalog_list">
          <li class="menu-catalog_item"><button id="menuCatalogLink1" onclick="linkClick(1)" class="menu-catalog_link">Каталог ножей</button></li>
          <li class="menu-catalog_item"><button id="menuCatalogLink2" onclick="linkClick(2)" class="menu-catalog_link">Клинковое оружие</button></li>
          <li class="menu-catalog_item"><button id="menuCatalogLink3" onclick="linkClick(3)" class="menu-catalog_link">Сувенирные изделия</button></li>
          <li class="menu-catalog_item"><button id="menuCatalogLink4" onclick="linkClick(4)" class="menu-catalog_link">Фонари ARMYTEK</button></li>
          <li class="menu-catalog_item"><button id="menuCatalogLink5" onclick="linkClick(5)" class="menu-catalog_link">Сопуствующие товары</button></li>
        </ul>
        <div class="menu-catalog_sub-menu sub-menu-catalog">
          <div class="sub-menu-catalog_block">
            <a href="" class="sub-menu-catalog_category">Категория ножей</a>
            <!--																								<hr class="sub-menu-catalog_hr">-->
            <ul class="sub-menu-catalog_list">
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Разделочные ножи</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Туристические ножи</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи охотничьи</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Булатные ножи</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из дамаска</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Тактического назначения</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Метательные ножи</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Мачете и кукри</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи кухонные</a></li>
            </ul>
            <a href="" class="sub-menu-catalog_all">Смотерть все</a>
          </div>

          <div class="sub-menu-catalog_block">
            <a href="" class="sub-menu-catalog_category">Производство ножей</a>
            <ul class="sub-menu-catalog_list">
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи АИР</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи ЗИК</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи ЗЗОСС</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи РОСоружие</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи Оружейник</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Булат Сергея Баранова</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Булат Андрея Умерова</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи Златко</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи Стиль-М</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Оружейная компания</a></li>
            </ul>
            <a href="" class="sub-menu-catalog_all">Смотерть все</a>
          </div>

          <div class="sub-menu-catalog_block">
            <a href="" class="sub-menu-catalog_category">Ножи по маркам стали</a>
            <ul class="sub-menu-catalog_list">
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из стали 40х102С2М</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из стали 95х18</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из стали 100х13м</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из стали 110х18м-ШД</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из стали ЭИ-107 ТЦ</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из стали 50х14МФ</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из стали AUS-8</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из стали К340</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из стали M390</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножи из стали ЭП-766</a></li>
            </ul>
            <a href="" class="sub-menu-catalog_all">Смотерть все</a>
          </div>

          <div class="sub-menu-catalog_block">
            <a href="" class="sub-menu-catalog_category">Заточка и полировка ножей</a>
            <ul class="sub-menu-catalog_list">
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Паста ГОИ</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Алмазная паста</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Бруски и камни для заточки</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Заточные системы</a></li>
            </ul>
            <a href="" class="sub-menu-catalog_all">Смотерть все</a>
          </div>

          <div class="sub-menu-catalog_block">
            <a href="" class="sub-menu-catalog_category">Ножевая мастерская</a>
            <ul class="sub-menu-catalog_list">
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Ножевые клинки</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Заготовки для ножей</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Литье для ножей</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Материалы для рукоятей</a></li>
              <li class="sub-menu-catalog_item"><a href="" class="sub-menu-catalog_link">Уход за рукоятиями ножей</a></li>
            </ul>
            <a href="" class="sub-menu-catalog_all">Смотерть все</a>
          </div>

        </div>
      </nav>
    </div>
  </div>
  </header>
    <div class="body">
    <div class="body-top">
      <div class="body-top-paragraph">
        <div style="margin-left: 20px;">
          <h1 class="body-top-paragraph_h1">Интернет магазин сертифицированных</h1>
          <h2>златоустовских ножей</h2>
          <p>
            <b>Добро пожаловать на официальный сайт «ЗЛАТМАКС»! В нашем магазине<br></b>
            представлен наиболее широкий выбор Златоустовских ножей от Златоустовских
            Оружейных Фабрик и компаний, мы являемся официальными поставщиками.
          </p>
          <button class="body-top-paragraph_button">Подробнее</button>
        </div>
        <div class="body-top_image">
          <img class="body-top_img" src="../assets/img/standOfKnives.png">
        </div>
      </div>
      <div class="body-top-list">
        <ul class="body-top-list_items">
          <li class="body-top-list_item _icon-guarantee">Гарантия 100% возврата денежных средств</li>
          <li class="body-top-list_item _icon-delivary">Доставка по России, Казахстану и Белоруссии</li>
          <li class="body-top-list_item _icon-decor">Возможность оформление заказа без регистрации.</li>
          <li class="body-top-list_item _icon-discount">Скидки постоянным покупателям.</li>
        </ul>
      </div>
    </div>

    <div class="body-middle">
      <div class="body-middle_cards">


        <div class="body-middle_card">
          <div class="body-middle_card-leftPart">
            <h1 class="body-middle_card_title">Каталог ножей</h1>
            <ul class="body-middle_card_items">
              <li class="body-middle_card_item">Разделочные</li>
              <li class="body-middle_card_item">Туристические</li>
              <li class="body-middle_card_item">Охотничьи</li>
            </ul>
          </div>
          <div class="body-middle_card-rightPart">
            <img src="../assets/img/knife1.png" alt="" class="body-middle_card_img">
          </div>
        </div>
        <div class="body-middle_card">
          <div class="body-middle_card-leftPart">
            <h1 class="body-middle_card_title">Среднеклинковое оружие</h1>
            <ul class="body-middle_card_items">
              <li class="body-middle_card_item">Разделочные</li>
              <li class="body-middle_card_item">Туристические</li>
              <li class="body-middle_card_item">Охотничьи</li>
            </ul>
          </div>
          <div class="body-middle_card-rightPart">
            <img src="../assets/img/knife2.png" alt="" class="body-middle_card_img">
          </div>
        </div>
        <div class="body-middle_card">
          <div class="body-middle_card-leftPart">
            <h1 class="body-middle_card_title">Длинноклинковое оружие</h1>
            <ul class="body-middle_card_items">
              <li class="body-middle_card_item">Разделочные</li>
              <li class="body-middle_card_item">Туристические</li>
              <li class="body-middle_card_item">Охотничьи</li>
            </ul>
          </div>
          <div class="body-middle_card-rightPart">
            <img src="../assets/img/knife3.png" alt="" class="body-middle_card_img">
          </div>
        </div>
        <div class="body-middle_card">
          <div class="body-middle_card-leftPart">
            <h1 class="body-middle_card_title">Сувенирные изделия</h1>
            <ul class="body-middle_card_items">
              <li class="body-middle_card_item">Разделочные</li>
              <li class="body-middle_card_item">Туристические</li>
              <li class="body-middle_card_item">Охотничьи</li>
            </ul>
          </div>
          <div class="body-middle_card-rightPart">
            <img src="../assets/img/knife4.png" alt="" class="body-middle_card_img">
          </div>
        </div>
        <div class="body-middle_card">
          <div class="body-middle_card-leftPart">
            <h1 class="body-middle_card_title">Сопутствующие товары</h1>
            <ul class="body-middle_card_items">
              <li class="body-middle_card_item">Разделочные</li>
              <li class="body-middle_card_item">Туристические</li>
              <li class="body-middle_card_item">Охотничьи</li>
            </ul>
          </div>
          <div class="body-middle_card-rightPart">
            <img src="../assets/img/knife15.png" alt="" class="body-middle_card_img">
          </div>
        </div>
        <div class="body-middle_card">
          <div class="body-middle_card-leftPart">
            <h1 class="body-middle_card_title">Ножевая мастерская</h1>
            <ul class="body-middle_card_items">
              <li class="body-middle_card_item">Разделочные</li>
              <li class="body-middle_card_item">Туристические</li>
              <li class="body-middle_card_item">Охотничьи</li>
            </ul>
          </div>
          <div class="body-middle_card-rightPart">
            <img src="../assets/img/knife6.png" alt="" class="body-middle_card_img">
          </div>
        </div>


      </div>
      <div class="body-middle_hits">
        <div class="body-middle_hits_link"><div class="body-middle_hits_title">Хиты продаж</div>Перейти в каталог</div>
        <div class="body-middle_hits_cards">
          <div class="body-middle_hits_card">
            <div class="body-middle_hits_card_content">
              <img src="../assets/img/knife7.png" class="body-middle_hits_card_img">
              <h3 class="body-middle_hits_card_title">Нож Лиса</h3>
              <div class="body-middle_hits_card_size">95х18<div class="body-middle_hits_card_material">Орех, Алюминий</div></div>

              <div class="body-middle_hits_card_stars">
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_review">12 отзывов</div>
              </div>
              <hr class="body-middle_hits_card_hr">
              <div class="body-middle_hits_card_price">2 719 р.<div class="body-middle_hits_card_bargain _icon-scales"><div class="body-middle_hits_card_favorite _icon-favorite"></div></div></div>


              <button class="body-middle_hits_card_button">В корзину<span class="body-middle_hits_card_cart _icon-cart"></span></button>
            </div>
          </div>
          <div class="body-middle_hits_card">
            <div class="body-middle_hits_card_content">
              <img src="../assets/img/knife7.png" class="body-middle_hits_card_img">
              <h3 class="body-middle_hits_card_title">Нож Лиса</h3>
              <div class="body-middle_hits_card_size">95х18<div class="body-middle_hits_card_material">Орех, Алюминий</div></div>

              <div class="body-middle_hits_card_stars">
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_review">12 отзывов</div>
              </div>
              <hr class="body-middle_hits_card_hr">
              <div class="body-middle_hits_card_price">2 719 р.<div class="body-middle_hits_card_bargain _icon-scales"><div class="body-middle_hits_card_favorite _icon-favorite"></div></div></div>


              <button class="body-middle_hits_card_button">В корзину<span class="body-middle_hits_card_cart _icon-cart"></span></button>
            </div>
          </div>
          <div class="body-middle_hits_card">
            <div class="body-middle_hits_card_content">
              <img src="../assets/img/knife7.png" class="body-middle_hits_card_img">
              <h3 class="body-middle_hits_card_title">Нож Лиса</h3>
              <div class="body-middle_hits_card_size">95х18<div class="body-middle_hits_card_material">Орех, Алюминий</div></div>

              <div class="body-middle_hits_card_stars">
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_review">12 отзывов</div>
              </div>
              <hr class="body-middle_hits_card_hr">
              <div class="body-middle_hits_card_price">2 719 р.<div class="body-middle_hits_card_bargain _icon-scales"><div class="body-middle_hits_card_favorite _icon-favorite"></div></div></div>


              <button class="body-middle_hits_card_button">В корзину<span class="body-middle_hits_card_cart _icon-cart"></span></button>
            </div>
          </div>
          <div class="body-middle_hits_card">
            <div class="body-middle_hits_card_content">
              <img src="../assets/img/knife7.png" class="body-middle_hits_card_img">
              <h3 class="body-middle_hits_card_title">Нож Лиса</h3>
              <div class="body-middle_hits_card_size">95х18<div class="body-middle_hits_card_material">Орех, Алюминий</div></div>

              <div class="body-middle_hits_card_stars">
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_star"><img src="../assets/img/star.png"></div>
                <div class="body-middle_hits_card_review">12 отзывов</div>
              </div>
              <hr class="body-middle_hits_card_hr">
              <div class="body-middle_hits_card_price">2 719 р.<div class="body-middle_hits_card_bargain _icon-scales"><div class="body-middle_hits_card_favorite _icon-favorite"></div></div></div>


              <button class="body-middle_hits_card_button">В корзину<span class="body-middle_hits_card_cart _icon-cart"></span></button>
            </div>
          </div>
        </div>
        <ul class="body-middle_hits_lines">
          <li class="body-middle_hits_line active"><hr class="body-middle_hits_hr active"></li>
          <li class="body-middle_hits_line"><hr class="body-middle_hits_hr"></li>
          <li class="body-middle_hits_line"><hr class="body-middle_hits_hr"></li>
          <li class="body-middle_hits_line"><hr class="body-middle_hits_hr"></li>
        </ul>
      </div>
      <div class="body-middle_news">
        <div class="body-middle_news_content">
          <h1 class="body-middle_news_content_title">Новинки</h1>
          <div class="body-middle_news_content_content">
            Добро пожаловать на официальный сайт «ЗЛАТМАКС»! В нашем магазине представлен наиболее широкий выбор Златоустовских ножей от Златоустовских Оружейных Фабрик и компаний, мы являемся официальными поставщиками.</div>
          <a href="#" class="body-middle_news_content_link">Больше новинок <span class="body-middle_news_content_arrow _icon-arrow"></span></a>
        </div>
        <div class="body-middle_news_cards">
          <div style="display: flex;
      flex-direction: row;
      flex-wrap: wrap;">
            <div class="body-middle_news_card">
              <div class="body-middle_news_card_content">
                <img src="../assets/img/knife7.png" class="body-middle_news_card_img">
                <h3 class="body-middle_news_card_title">Нож Лиса</h3>
                <div class="body-middle_news_card_size">95х18<div class="body-middle_news_card_material">Орех, Алюминий</div></div>

                <div class="body-middle_news_card_stars">
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_review">12 отзывов</div>
                </div>
                <hr class="body-middle_news_card_hr">
                <div class="body-middle_news_card_price">2 719 р.<div class="body-middle_news_card_bargain _icon-scales"><div class="body-middle_news_card_favorite _icon-favorite"></div></div></div>


                <button class="body-middle_news_card_button">В корзину<span class="body-middle_news_card_cart _icon-cart"></span></button>
              </div>
            </div>
            <div class="body-middle_news_card">
              <div class="body-middle_news_card_content">
                <img src="../assets/img/knife7.png" class="body-middle_news_card_img">
                <h3 class="body-middle_news_card_title">Нож Лиса</h3>
                <div class="body-middle_news_card_size">95х18<div class="body-middle_news_card_material">Орех, Алюминий</div></div>

                <div class="body-middle_news_card_stars">
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_review">12 отзывов</div>
                </div>
                <hr class="body-middle_news_card_hr">
                <div class="body-middle_news_card_price">2 719 р.<div class="body-middle_news_card_bargain _icon-scales"><div class="body-middle_news_card_favorite _icon-favorite"></div></div></div>


                <button class="body-middle_news_card_button">В корзину<span class="body-middle_news_card_cart _icon-cart"></span></button>
              </div>
            </div>
            <div class="body-middle_news_card">
              <div class="body-middle_news_card_content">
                <img src="../assets/img/knife7.png" class="body-middle_news_card_img">
                <h3 class="body-middle_news_card_title">Нож Лиса</h3>
                <div class="body-middle_news_card_size">95х18<div class="body-middle_news_card_material">Орех, Алюминий</div></div>

                <div class="body-middle_news_card_stars">
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_star"><img src="../assets/img/star.png"></div>
                  <div class="body-middle_news_card_review">12 отзывов</div>
                </div>
                <hr class="body-middle_news_card_hr">
                <div class="body-middle_news_card_price">2 719 р.<div class="body-middle_news_card_bargain _icon-scales"><div class="body-middle_news_card_favorite _icon-favorite"></div></div></div>


                <button class="body-middle_news_card_button">В корзину<span class="body-middle_news_card_cart _icon-cart"></span></button>
              </div>
            </div>
          </div>
          <ul class="body-middle_news_lines">
            <li class="body-middle_news_line active"><hr class="body-middle_news_hr active"></li>
            <li class="body-middle_news_line"><hr class="body-middle_news_hr"></li>
            <li class="body-middle_news_line"><hr class="body-middle_news_hr"></li>
            <li class="body-middle_news_line"><hr class="body-middle_news_hr"></li>
          </ul>
        </div>
      </div>
      <div class="body-middle_article">
        <div class="body-middle_article_content">
          <div class="body-middle_article_content_title">Наши статьи</div>
          <div class="body-middle_article_content_cards">
            <div class="body-middle_article_content_card">
              <img src="../assets/img/knife8.png" alt="" class="body-middle_article_content_card_img">
              <div class="body-middle_article_content_card_title">Все о ножах: как правильно выбрать</div>
              <div class="body-middle_article_content_card_data">24.07.2019</div>
            </div>

            <div class="body-middle_article_content_card">
              <img src="../assets/img/knife9.png" alt="" class="body-middle_article_content_card_img">
              <div class="body-middle_article_content_card_title">Как правильно выбрать фонарь</div>
              <div class="body-middle_article_content_card_data">24.07.2019</div>
            </div>

            <div class="body-middle_article_content_card">
              <img src="../assets/img/knife10.png" alt="" class="body-middle_article_content_card_img">
              <div class="body-middle_article_content_card_title">Кухонные ножи для хозяек</div>
              <div class="body-middle_article_content_card_data">24.07.2019</div>
            </div>

            <div class="body-middle_article_content_card">
              <img src="../assets/img/knife11.png" alt="" class="body-middle_article_content_card_img">
              <div class="body-middle_article_content_card_title">Кухонные ножи для хозяек</div>
              <div class="body-middle_article_content_card_data">24.07.2019</div>
            </div>
          </div>
        </div>
        <div class="body-middle_article_content2">
          <div class="body-middle_article_content2_cards">
            <div class="body-middle_article_content2_card">
              <div class="body-middle_article_content2_card_container">
                <div class="body-middle_article_content2_card_title">Тактические фонари</div>
                <div class="body-middle_article_content2_card_content">Lorem ipsum dolor sit amet,
                  consectetur adipiscing elit.</div>
                <button class="body-middle_article_content2_card_button">Подробнее</button>
              </div>
              <img src="../assets/img/light.png" alt="" class="body-middle_article_content2_card_img" style="width: 425px;">
            </div>
            <div class="body-middle_article_content2_card">
              <div class="body-middle_article_content2_card_container">
                <div class="body-middle_article_content2_card_title">Палобные мультифонари</div>
                <div class="body-middle_article_content2_card_content">Lorem ipsum dolor sit amet,
                  consectetur adipiscing elit.</div>
                <button class="body-middle_article_content2_card_button">Подробнее</button>
              </div>
              <img src="../assets/img/light2.png" alt="" class="body-middle_article_content2_card_img" style="width: 363px">
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
    <div class="footer">
    <div class="footer_description">
      <div class="footer_description_title">Златоустовские ножи интернет-магазин "ЗЛАТМАКС"</div>
      <div class="footer_description_content">
        Наш интернет-магазин "ЗЛАТМАКС" предлагает Вам ножи очень высокого качества из города оружейников - Златоуста. Златоустовские ножи известны и популярны среди потребителей как на российским рынке, так и за рубежом: ножи охотничьи, хозяйственные, туристические, рыбацкие, складные и метательные. Нож Златоуста - это идеальный друг и товарищ в повседневной жизни и в экстремальных ситуациях. На многую продукцию распространяется гарантия до 10 лет - это один из главных показателей качества. Для Вас на нашем сайте "zlatmax" предложен огромный ассортимент Златоустовских ножей. Наши менеджеры помогут определиться и подобрать самый лучший Златоустовский нож, ориентируясь на Ваши пожелания.
      </div>
    </div>
    <div class="footer_third">
      <div class="footer_third_groups">
        <ul class="footer_third_links">
          <div class="footer_third_links_title">ИНФОРМАЦИЯ</div>
          <li class="footer_third_links_item">Златоустовские ножи<br>
            в Москве и Московской<br>
            области</li>
          <li class="footer_third_links_item">Ножевые стали</li>
          <li class="footer_third_links_item">О нас</li>
          <li class="footer_third_links_item">Условия оплаты<br>
            и доставки</li>
          <li class="footer_third_links_item">Политика<br>
            конфиденциальности</li>
        </ul>
        <ul class="footer_third_links">
          <div class="footer_third_links_title">СЛУЖБА ПОДДЕРЖКИ</div>
          <li class="footer_third_links_item">Контактная информация</li>
          <li class="footer_third_links_item">Возврат товара</li>
          <li class="footer_third_links_item">Карта сайта</li>
        </ul>
        <ul class="footer_third_links">
          <div class="footer_third_links_title">ДОПОЛНИТЕЛЬНО</div>
          <li class="footer_third_links_item">Подарочные сертификаты</li>
          <li class="footer_third_links_item">Партнеры</li>
          <li class="footer_third_links_item">Товары со скидкой</li>
        </ul>
        <ul class="footer_third_links">
          <div class="footer_third_links_title">ЛИЧНЫЙ КАБИНЕТ</div>
          <li class="footer_third_links_item">Личный кабинет</li>
          <li class="footer_third_links_item">История заказов</li>
          <li class="footer_third_links_item">Мои закладки</li>
          <li class="footer_third_links_item">Рассылка новостей</li>
        </ul>
      </div>
    </div>
    <hr>
    <div class="footer_second">
      <div class="footer_second_container">
        <div class="footer_second_groups">
          <ul class="footer_second_links">
            <div class="footer_second_links_title">КОНТАКТЫ</div>
            <li class="footer_second_links_item"> <div class="_icon-footer-phone"></div>8 (800) 777-49-67</li>
            <li class="footer_second_links_item "><div class="_icon-footer-clock"></div>Пн-Пт<br>
              7:00 - 16:00 (МСК)</li>
            <li class="footer_second_links_item"><div class="_icon-footer-location"></div>Златоуст,<br>
              ул. Шоссейная,<br>
              д. 1, офис «6Б»</li>
            <li class="footer_second_links_item"><div class="_icon-footer-email"></div>info@zlatmax.ru</li>
          </ul>
          <ul class="footer_second_links">
            <div class="footer_second_links_title">ПОЛЕЗНЫЕ ССЫЛКИ</div>
            <li class="footer_second_links_item">Способы оплаты и доставки</li>
          </ul>
          <ul class="footer_second_links">
            <div class="footer_second_links_title">НАША ГАРАНТИЯ</div>
            <li class="footer_second_links_item" style="white-space: nowrap">Недовольны своей покупкой?<br>
              Вы можете вернуть ее в течении<br>
              30 дней с даты получения,<br>
              согласно нашим правилам</li>
          </ul>
          <ul class="footer_second_links">
            <div class="footer_second_links_title"> НОВОСТНАЯ РАССЫЛКА</div>
            <li class="footer_second_links_item">Подпишитесь прямо сейчас!</li>
            <li class="footer_second_links_item"><input type="text" placeholder="example@gmail.com"></li>
            <li class="footer_second_links_item" style="display: flex; flex-direction: row;"><input type="checkbox"><div>Я прочитал Условия соглашения и
              согласен с условиями</div></li>
          </ul>
        </div>
        <ul class="footer_second_socials">
          <li class="footer_second_socials_item"><img src="../assets/img/icons/social/footer-facebook.png" alt=""></li>
          <li class="footer_second_socials_item"><img src="../assets/img/icons/social/footer-viber.png" alt=""></li>
          <li class="footer_second_socials_item"><img src="../assets/img/icons/social/footer-telegram.png" alt=""></li>
          <li class="footer_second_socials_item"><img src="../assets/img/icons/social/footer-whatsapp.png" alt=""></li>
        </ul>
      </div>
    </div>
    <hr>
    <div class="footer_first">
      <div class="footer_first_container">
        <div class="footer_first_content">
          Все материалы, размещенные на сайте, носят справочный характер и не являются<br>
          публичной офертой, определяемойположениями Статьи 437 Гражданского кодекса Российской Федерации.<br>
          При копировании материалов гиперссылка на www.zlatmax.ru обязательна!
        </div>
        <div class="footer_first_webSite">Златоустовские ножи www.zlatmax.ru ©</div>
      </div>
    </div>
  </div>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {

    }
  }
}
</script>


<style scoped lang="less">
@import "../assets/css/style.less";
</style>
