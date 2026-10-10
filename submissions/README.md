# Предсказания

Финальный запуск создаёт здесь `final_submission.csv`, `submission_NEW5_sqrt_s100_aux20.csv` и `submission_rescue_corrected_best.csv`. Первые два файла содержат одинаковые предсказания NEW5, третий — предсказания Rescue T6.

Формат: `row_id,target`. `target` — ранговый score в диапазоне `[0, 1]`, порядок строк совпадает с `test.csv`.

Папка `legacy/` отведена для промежуточных submission. CSV генерируются при запуске и не хранятся в Git.
