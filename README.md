# 如何上传个人信息与成果到网站

## 注意事项
- 请**不要修改**自己的文件夹以外的任何文件！

---

## 1. 添加个人信息

1. **Fork 仓库：**
   - 先通过 [GitHub 仓库](https://github.com/ZJU-FAST-Lab/zju-fast-lab.github.io.git) 将仓库 Fork 到自己的 GitHub 账号。

2. **克隆自己仓库：**
   - 克隆自己仓库下的 `zju-fast-lab.github.io` 到本地。
     ```bash
     git clone https://github.com/你的用户名/zju-fast-lab.github.io.git
     ```

3. **创建个人文件夹：**
   - 打开 `zju-fast-lab.github.io/content/authors` 目录，在其中创建一个新文件夹。
   - 将文件夹重命名为自己的英文拼音，格式为：`名在前，姓在后，首字母大写`。

4. **复制模板文件：**
   - 复制 `zju-fast-lab.github.io/templates/people_template/_index.md` 文件到自己的 `content/authors` 文件夹中。
   - 按照文件中的提示修改个人信息。

5. **上传个人照片：**
   - 将个人照片放入该文件夹，并重命名为 `avatar.jpg`。

---

## 2. 上传论文

### 上传会议论文

1. **创建论文文件夹：**
   - 在 `zju-fast-lab.github.io/content/publication/conference-paper` 目录中创建一个新文件夹，命名格式为：
     - `会议+年份-姓名首字母缩写-论文名称缩写`
     - 例如：`icra2025-zmk-3dplanner`

2. **复制模板文件：**
   - 从 `zju-fast-lab.github.io/templates/publication_template/conference-paper_template` 目录中复制以下 4 个文件到会议论文文件夹中：
     - `cite.bib`
     - `index.md`
     - `conference-paper.pdf`
     - `featured.jpg`

3. **修改文件内容：**
   - 修改 `cite.bib` 和 `index.md`，替换 `conference-paper.pdf` 和 `featured.jpg` 为自己的论文和头图，命名不变。

---

### 上传期刊论文

1. **创建期刊论文文件夹：**
   - 在 `zju-fast-lab.github.io/content/publication/journal-article` 目录中创建一个新文件夹，命名格式为：
     - `期刊+年份-姓名首字母缩写-论文名称缩写`
     - 例如：`journal2025-zmk-3dplanner`

2. **复制模板文件：**
   - 从 `zju-fast-lab.github.io/templates/publication_template/journal-article_template` 目录中复制以下 3 个文件到期刊论文文件夹中：
     - `cite.bib`
     - `index.md`
     - `featured.jpg` 或 `featured.png`

3. **修改文件内容：**
   - 修改 `cite.bib` 和 `index.md`，替换 `featured.jpg` 为自己的论文头图，命名不变。

---

## 3. 上传新闻

1. **创建新闻文件夹：**
   - 在 `zju-fast-lab.github.io/content/post` 目录中创建一个新文件夹，命名格式为：
     - `日期+新闻简介`
     - 例如：`25-10-10-RAL-accepted`

2. **复制模板文件：**
   - 从 `zju-fast-lab.github.io/templates/news_template` 目录中复制以下 2 个文件到新闻文件夹中：
     - `index.md`
     - `featured.jpg` 或 `featured.png`

3. **修改文件内容：**
   - 修改 `index.md` 为自己的新闻信息，并替换图片。

---

## 4. 提交修改

1. **提交更改：**
   - 修改完成后，提交回自己仓库下的 `zju-fast-lab.github.io`，提交信息 `message` 设为“姓名拼音”，例如：`San Zhang`。
   - 回到自己仓库下的zju-fast-lab.github.io点击 **Sync Fork** 。
   - 再点击 **Open Pull Request**，然后点击 **Create Pull Request**，无需写描述，再点击 **Create Pull Request** 提交。

2. **审核与合并：**
   - 提交后，管理员将会审核并合并 Pull Request，审核通过后，你的个人信息和成果将被加入到网站中。

---
