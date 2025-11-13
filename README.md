# 上传个人信息与成果到网站

## 注意事项
- 请**不要修改**自己的文件夹以外的任何文件！

---

## 添加个人信息

1. **克隆到本地：**
    ```bash
    git clone https://github.com/ZJU-FAST-Lab/zju-fast-lab.github.io.git
    ```

2. **创建个人文件夹：**
    - 打开 `zju-fast-lab.github.io/content/authors` 目录，在其中创建一个新文件夹。
    - 将文件夹重命名为自己的英文拼音，格式为：`名在前，姓在后`。

3. **复制模板文件：**
    - 复制 `zju-fast-lab.github.io/templates/people_template/_index.md` 文件到自己在 `content/authors` 目录下的文件夹中。
    - 按照文件中的提示修改个人信息。

4. **上传个人照片：**
    - 将个人照片放入自己文件夹下，并重命名为 `avatar.jpg`。

---

## 上传论文

### 上传会议论文

1. 在 `zju-fast-lab.github.io/content/publication/conference-paper` 目录中创建一个新文件夹，命名格式为：  
   `会议+年份-姓名首字母缩写-论文名称缩写`  
   例如：`icra2025-zmk-3dplanner`

2. **复制模板文件：**
    - 从 `D:\Project\zju-fast-lab.github.io\templates\publication_template\conference-paper_template` 中复制以下4个文件到新文件夹中：
        - `cite.bib`
        - `index.md`
        - `conference-paper.pdf`
        - `featured.jpg`

3. **修改文件内容：**
    - 修改 `cite.bib` 和 `index.md`，并替换 `conference-paper.pdf` 和 `featured.jpg` 为自己的论文文件和头图。命名不变。

---

### 上传期刊论文

1. 在 `zju-fast-lab.github.io/content/publication/journal-article` 目录中创建一个新文件夹，命名格式为：  
   `期刊+年份-姓名首字母缩写-论文名称缩写`  
   例如：`journal2025-zmk-ai-approach`

2. **复制模板文件：**
    - 从 `D:\Project\zju-fast-lab.github.io\templates\publication_template\journal-article_template` 中复制以下3个文件到新文件夹中：
        - `cite.bib`
        - `index.md`
        - `featured.jpg`

3. **修改文件内容：**
    - 修改 `cite.bib` 和 `index.md`，替换 `featured.jpg` 为自己的论文头图。命名不变。

---

## 上传新闻

1. 在 `D:\Project\zju-fast-lab.github.io\content\post` 目录中创建一个新文件夹，命名格式为：  
   `日期+新闻简介`  
   例如：`25-10-10-RAL-accepted`

2. **复制模板文件：**
    - 从 `D:\Project\zju-fast-lab.github.io\templates\news_template` 中复制以下2个文件到新文件夹中：
        - `index.md`
        - `featured.jpg`

3. **修改文件内容：**
    - 修改 `index.md` 为自己的新闻信息，替换图片。

---

## 提交更改

1. 修改完成后，使用以下命令将更改提交到 GitHub：
    ```bash
    git commit -am "姓名拼音"
    git push origin main
    ```

2. 提交时，命名提交为 `姓名拼音` 方便追踪。

---
