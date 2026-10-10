# Архив экспериментов

Здесь остался исследовательский этап: EDA, сравнения моделей, поиск параметров и промежуточные идеи.

| Файлы | Что проверяли |
| --- | --- |
| `draft_marimo.py`, `main.ipynb`, `main.py` | EDA, деревья, бустинги и первые признаки |
| `main_svc.py`, `svc.ipynb` | RBF SVC, веса признаков и поиск параметров |
| `stacking.py`, `svc_bagging_experiment.py`, `svc_augmentation.py` | Stacking, bagging и аугментации |
| `exp_3.ipynb`, `svc_new.ipynb` | Дополнительные представления и варианты SVC |
| `svc_multikernel.ipynb` | Смешивание ядер для разных блоков признаков |
| `svc_final_rescue.ipynb`, `svc_last_push.ipynb` | Whitening, sqrt-признаки и финальные ансамбли |
| Остальные `*.py` | Преобразования и функции для этих экспериментов |
| `KaggleTemplate.md` | Рабочие заметки по ходу соревнования |
| `pyproject.toml`, `uv.lock` | Среда исследовательского этапа; lock-файл хранится локально |

Некоторые эксперименты используют промежуточные артефакты и кеши. Для воспроизведения итогового решения использовать [final/](../final/), краткая история — в [docs/experiments.md](../docs/experiments.md).
