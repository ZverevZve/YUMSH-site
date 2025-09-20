---
title: Результаты отборочного тура
date: '2024-05-06T01:40:13.745Z'
draft: false
image: "/images/ban olymp.jpg"
---


<form action="/cms/ol-query" method="post" id="olymp-results-query-form" accept-charset="UTF-8">
    <div><b>Замечание:</b> Буквы "е" и "ё" считаются различными.
        <div class="form-item form-type-textfield form-item-family-name">
            <input type="text" id="edit-family-name" name="family_name" value="" size="60" maxlength="128" class="form-text required" placeholder="Фамилия">
        </div>
        <div class="form-item form-type-textfield form-item-name">
            <input type="text" id="edit-name" name="name" value="" size="60" maxlength="128" class="form-text required" placeholder="Имя">
        </div>
        <div class="form-item form-type-select form-item-paral">
            <label for="edit-paral">За какой класс вы решал задачи</label>
            <select id="edit-paral" name="paral" class="form-select required">
                <option value="" selected="selected">- Выберите -</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
                <option value="8">8</option>
                <option value="9">9</option>
                <option value="10">10</option>
                <option value="11">11</option>
            </select>
        </div>
        <div class="form-item form-type-select form-item-tour-format">
            <label for="edit-tour-format">Формат проведения тура</label>
            <select id="edit-tour-format" name="tour_format" class="form-select required">
                <option value="" selected="selected">- Выберите -</option>
                <option value="zaoch">Заочный</option>
                <option value="distant">Дистанционный 1</option>
                <option value="distant_2">Дистанционный 2</option>
                <option value="pers">Персональное приглашение</option>
            </select>
        </div>
        <div class="form-item form-type-textfield form-item-school-name">
            <input type="text" id="edit-school-name" name="school_name" value="" size="60" maxlength="128" class="form-text" placeholder="Номер или название школы">
        </div>
        <div class="form-item form-type-textfield form-item-city">
            <input type="text" id="edit-city" name="city" value="" size="60" maxlength="128" class="form-text" placeholder="Город (оставьте пустым, если Санкт-Петербург">
        </div>
            <div class="form-item form-type-select form-item-year">
            <label for="edit-year">Год</label>
            <select id="edit-year" name="year" class="form-select required">
                <option value="2012">2012</option>
                <option value="2013">2013</option>
                <option value="2014">2014</option>
                <option value="2015">2015</option>
                <option value="2016">2016</option>
                <option value="2017">2017</option>
                <option value="2018">2018</option>
                <option value="2019">2019</option>
                <option value="2020">2020</option>
                <option value="2021">2021</option>
                <option value="2022">2022</option>
                <option value="2023">2023</option>
                <option value="2024">2024</option>
                <option value="2025" selected="selected">2025</option>
            </select>
        </div>
        <input type="submit" id="edit-submit" name="op" value="Узнать результаты" class="form-submit">
        <input type="hidden" name="form_build_id" value="form-dY7gsxUcf8uLwOqsCLHvecG5mmLTXQzywDVAdoz8b18">
        <input type="hidden" name="form_id" value="olymp_results_query_form">
    </div>
</form>
