# Отчёт

- ФИО: [Попов Александр Евгеньевич]
- Вариант стенда: s06
- Репозиторий: [https://github.com/ragonya/git-os-homework]

| № | PR | Итог |
|---|---|---|
| 01 | https://github.com/ragonya/git-os-homework/pull/1 | reset с B (15b7c43) на A (a668191): soft — правка B в индексе, mixed — только в рабочем файле, hard — файл вернулся к A |
| 02 | https://github.com/ragonya/git-os-homework/pull/2 | rebase на base/task-02 (2f62dbf) с разрешением конфликта: коммиты получили новые SHA (559510d → e92c2fc), merge-коммита нет |
| 03 | https://github.com/ragonya/git-os-homework/pull/3 | amend сменил SHA последнего коммита (8dda4b7 → d48bbca); rebase -i склеил C2 и C3 в C1, итоговое дерево совпадает с исходным |
| 04 | https://github.com/ragonya/git-os-homework/pull/4 | revert b6b9163 отменил X (dfb55e8); restore вернул только settings.ini (b7e098c), правка message.txt из Y сохранилась |
| 05 | https://github.com/ragonya/git-os-homework/pull/6 | pull с merge: merge-коммит bab0a3a с родителями L (3946caf) и R (0f0bb17), оба файла сохранены |
| 06 | https://github.com/ragonya/git-os-homework/pull/7 | pull с rebase: L перенесён поверх R (59e0259), SHA 99b130c → 0765a6f, merge-коммита нет, без force-push |
| 07 | https://github.com/ragonya/git-os-homework/pull/8 | v1.0.0 — annotated tag (тип tag, объект 0bfedd4), v1.1.0-rc1 — lightweight tag (тип commit, dcde721), оба опубликованы |
| 08 | https://github.com/ragonya/git-os-homework/pull/9 | stash -u и apply --index после hotfix (716776f): staged, unstaged и untracked изменения восстановлены |
| 09 | https://github.com/ragonya/git-os-homework/pull/10 | LOST (4ceecff) найден через reflog после reset --hard, восстановлен и опубликован с тем же SHA |
| 10 | https://github.com/ragonya/git-os-homework/pull/11 | cherry-pick -x перенёс только D2 (6e81298 → 51be1ed), patch-id совпадает, D1 и D3 не попали |
| 11 | https://github.com/ragonya/git-os-homework/pull/12 | ручной и автоматический bisect нашли ad27366, родитель 6d7631d good; исправление fe313d7, тест печатает OK |
| 12 | https://github.com/ragonya/git-os-homework/pull/13 | .gitignore для *.log, .env, __pycache__/, build/output.txt; debug.log убран из индекса (cd11b00), на диске и в старых коммитах остался |
