# Git Commands Cheat Sheet

## View commit history
```bash
git log --oneline
```
```
git branch -a
git branch -d feature-example
git tag
git cherry-pick <commit_hash>
```
### Commit message:

---

# ШАГ 6. Feature-ветка (обязательно показать GitFlow)

1. В репозитории нажми на список веток
2. Впиши:
3. ```Create branch from **master**```

Теперь ты **в feature-ветке**.

---

# ШАГ 7. Изменение в feature-ветке

Открой `README.md` → **Edit**

В разделе Description добавь строку:

### Commit message:

Commit to: **feature-readme-update**

---

# ШАГ 8. Merge feature → master

1. Вкладка **Pull requests**
2. New pull request
3. Base: `master`
4. Compare: `feature-readme-update`
5. Create pull request
6. Merge pull request
7. ❗ **Delete branch** (кнопка появится)

Это ОЧЕНЬ важно. Это проверяют.

---

# ШАГ 9. Issues + labels

Вкладка **Issues** → New issue

### Issue 1
Title:

Description:
Label:
- `feature`

Сделай **минимум 2–3 issue**.

---

# ШАГ 10. Release (семантическая версия)

Вкладка **Releases** → Draft a new release

- Tag:
- Target: `master`
- Title:
- Description:

Publish release

---

# ШАГ 11. Wiki

Вкладка **Wiki** → Create first page

### Home:

Создай страницы:
- About project
- What it does
- Developer
- Tasks order

---

# ШАГ 12. Network graph (в самом конце)

1. **Insights → Network**
2. Сделай скрин
3. Вернись в Code → Add file → Upload files
4. Загрузи как:

Открой `README.md`, замени блок Network:

```md
## Network graph
![Network](network.png)


