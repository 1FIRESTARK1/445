<body>
<div class="div3">
    <h2>Контактная информация</h2>
</div>

<main class="main">

    <div class="col_w310 float_l">

        <h4 class="title">Пожалуйста, заполните контактную форму</h4>

        <div id="contact_form">

            <form method="post" action="">

                <label for="author"><br>Ваше имя:</label>
                <input type="text" name="name" pattern="[А-Яа-яЁё]" title="Имя должно быть на русском. Пример: Степа, Петя, Вася, Оля" class="required input_field" />

                <label for="email"><br>Ваш Email:</label>
                <input type="text" name="email" pattern="([A-z0-9_.-])@([A-z0-9_.-].([A-z]{2,8})" title="Пример: bloggood@mail.ru" class="validate-email required input_field" required />

                <label for="text"><br>Ваш вопрос:</label>
                <textarea name="quest" rows="0" cols="0" class="required"></textarea>
                <div class="cleaner h10"></div>

                <input type="submit" class="submit_btn" name="submit" value="Отправить" />
                <input type="reset" class="submit_btn" name="reset" value="Очистить" />



            </form>
        </div>
        
    </div>


    <div class="col_w310 float_r">

        <h4 class="title">Наше место нахождения</h4>
        <br>
        <div class="a:link"><span></span><a href="http://maps.google.com" target="_blank"><img src="/img/google.jpg" alt="Image" /></a></div>
        <div class="cleaner h30"></div>
        <br>
        <h4 class="title">Наш адрес</h4>
        <br>
        Центр Ювента<br>
        ЯНАО <br>
        г.Ноябрьск<br>
        Муравленко 3<br>
        <br>
        Tel: 89224845467<br>
        Email: <a href="dinfom@mail.ru">dinfom@mail.ru</a>
    </div>

</main>
</body>