# DA

/-------
# Мета

Ціль проекту -- створити невеличкий справочник із ыллюстрованою статистикою по лікарских засобах
який би іллюстрував базові параметри медичного засобу, назвву класс ліків, діючу речовину тощо та 
сторонні єффекти, як він взаємодіе, наприклад з алкоголем Але головний акцент саме на побічних ефектах.

/-------
# Datasets

Датасети були взяти з ресуксу kaggle.com, а саме
-- https://www.kaggle.com/datasets/jithinanievarghese/drugs-related-to-common-treatments
-- https://www.kaggle.com/datasets/jithinanievarghese/drugs-side-effects-and-medical-condition

Ці датасети від одного автора, та мають досить детальні та повні данні -- джерело самих даних, drugs.com.
Частково даны було отрима чарез API, частково шляхом веб-скрепінгу.

Початкові дані було експортовано у .csv формат.
Файли:
[source]
    |-[raw]
        |-drugs_for_common_treatments
        |-drugs_side_effects_drugs_com

/-------
# ETL

За допомогою MS Excel ці файми було оброблено (очищенно, призначено відповідні типи даних, трансформовано) 
у PowerQuery, та збережено у файл .xlsx:
[source]
    |- Imported_Actual

Дані з різних джерел на різних вкладках з відповідними іменами.

/-------
# Tableau

https://public.tableau.com/app/profile/volodymyr.adamenko/viz/DrugsandSideEffects/Dashboard2


