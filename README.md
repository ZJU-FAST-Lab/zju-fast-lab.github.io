# 如何提交个人信息与成果

## 添加个人信息

1. **克隆到本地：**
    ```bash
    git clone https://github.com/ZJU-FAST-Lab/zju-fast-lab.github.io.git
    ```

2. **创建个人文件夹：**
    - 在桌面或任何自己喜欢的地方创建一个新文件夹，并重命名为自己的英文拼音，格式为：`名在前，姓在后，首字母大写`。

3. **复制模板文件：**
    - 复制 `zju-fast-lab.github.io/templates/people_template/_index.md` 文件到自己的文件夹中，并按照提示修改_index.md中的个人信息。

4. **上传个人照片：**
    - 将个人照片放入该文件夹，并重命名为 `avatar.jpg`。

---

## 上传论文

### 上传会议论文

1. **创建会议论文文件夹：**
    - 在桌面或任何自己喜欢的地方创建一个新文件夹，并重命名为 `会议+年份-姓名首字母缩写-论文名称缩写`。例如：`icra2025-zmk-3dplanner`。

2. **复制模板文件：**
    - 从 `zju-fast-lab.github.io/templates/publication_template/conference-paper_template` 中复制以下4个文件到新创建的会议论文文件夹中：
        - `cite.bib`
        - `index.md`
        - `conference-paper.pdf`
        - `featured.jpg`

3. **修改文件内容：**
    - 修改 `cite.bib` 和 `index.md`，并将 `conference-paper.pdf` 和 `featured.jpg` 替换为自己的论文和头图，命名不变。

---

### 上传期刊论文

1. **创建期刊论文文件夹：**
    - 在桌面或任何自己喜欢的地方创建一个新文件夹，并重命名为 `期刊+年份-姓名首字母缩写-论文名称缩写`。例如：`journal2025-zmk-3dplanner`。

2. **复制模板文件：**
    - 从 `zju-fast-lab.github.io/templates/publication_template/journal-article_template` 中复制以下3个文件到新创建的期刊论文文件夹中：
        - `cite.bib`
        - `index.md`
        - `featured.jpg` 或 `featured.png`

3. **修改文件内容：**
    - 修改 `cite.bib` 和 `index.md`，并将 `featured.jpg` 或 `featured.png` 替换为自己的论文头图，命名不变。

---

## 上传新闻

1. **创建新闻文件夹：**
    - 在桌面或任何自己喜欢的地方创建一个新文件夹，并重命名为 `日期+新闻简介`。例如：`25-10-10-RAL-accepted`。

2. **复制模板文件：**
    - 从 `zju-fast-lab.github.io/templates/news_template` 中复制以下2个文件到新闻文件夹中：
        - `index.md`
        - `featured.jpg` 或 `featured.png`

3. **修改文件内容：**
    - 修改 `index.md` 为自己的新闻信息，并替换图片。

---

## 提交文件

1. **压缩文件夹：**
    - 将上述文件夹压缩，并重命名为 `姓名`，例如 `张三.zip`。

2. **压缩包结构：**
    - 压缩包的文件夹结构应如下：
    ```text
    张三.zip
    ├── San Zhang
    │   ├── _index.md
    │   └── avatar.jpg
    ├── icra2025-zmk-3dplanner
    │   ├── cite.bib
    │   ├── index.md
    │   ├── conference-paper.pdf
    │   └── featured.jpg (featured.png)
    ├── journal2025-zmk-3dplanner
    │   ├── cite.bib
    │   ├── index.md
    │   └── featured.jpg (featured.png)
    └── 25-10-10-RAL-accepted
        ├── index.md
        └── featured.jpg (featured.png)
    ```

---
111