# How to upload personal information and contributions.

## WARNING
- Please **DO NOT REVISE** the folder not belonging to yourself.

---

## 1. Add personal information.

1. **Fork repo：**
   - Fork the repo by the GitHub account, [GitHub Repo](https://github.com/BISG-Robotics/BISG-Robotics.github.io.git).

2. **Clone your repo：**
   - Clone your repo `BISG-Robotics.github.io` locally.
     ```bash
     git clone https://github.com/your_user_name/BISG-Robotics.github.io.git
     ```

3. **Create a folder：**
   - Open `BISG-Robotics.github.io/content/authors` folder and create a new folder.
   - Rename the folder. The format is：`first_name， last_name`.

4. **Copy the template：**
   - Copy `BISG-Robotics.github.io/templates/people_template/_index.md` to the `content/authors` folder.
   - Change you personal information.

5. **Upload your photo：**
   - Put your photo in the folder with name `avatar.jpg`.

---

## 2. Upload papers

### Upload conference papers

1. **Create a folder for your paper：**
   - Create a new folder in `BISG-Robotics.github.io/content/publication/conference-paper` and give the name in the following format:
     - `conference+year-your_name-your_paper_name`
     - For example：`icra2026-juha-slam`

2. **Copy the template：**
   - Copy `BISG-Robotics.github.io/templates/publication_template/conference-paper_template` to the conference folder：
     - `cite.bib`
     - `index.md`
     - `conference-paper.pdf`
     - `featured.jpg`

3. **Revise the content：**
   - Revise `cite.bib` and `index.md`，and replace `conference-paper.pdf` and `featured.jpg` to your paper and picture.

---

### Submit journals

1. **Create a journal paper folder：**
   - Create a new folder in `BISG-Robotics.github.io/content/publication/journal-article` and give the name with the format：
     - `journal_name+year-your_name-your_paper_name`
     - For example：`ijrr2026-juha-slam`

2. **Copy the template：**
   - Copy the following 3 files from `BISG-Robotics.github.io/templates/publication_template/journal-article_template`:
     - `cite.bib`
     - `index.md`
     - `featured.jpg` or `featured.png`

3. **Revise the content：**
   - Revise `cite.bib` and `index.md`，and replace `featured.jpg` with your paper picture.

---

## 3. Submit news

1. **Create a news folder：**
   - Create a new folder in `BISG-Robotics.github.io/content/post` and give a name with the following format：
     - `date+keywords`
     - e.g., `25-09-01-SIX-ManuGenius`

2. **Copy the template：**
   - Copy the following 2 files from `BISG-Robotics.github.io/templates/news_template` to the news folder：
     - `index.md`
     - `featured.jpg` or `featured.png`

3. **Revise the content：**
   - Revise `index.md` to add news and replace corresponding photos.

---

## 4. Submit revisions

1. **Submit revisions：**
   - After revisions，commiting to `BISG-Robotics.github.io`. Submitting `message` should be “your_name”， such as：`Juha roning`.
   - Back to your repo, BISG-Robotics.github.io, and click **Sync Fork**.
   - Click **Open Pull Request**, and then click **Create Pull Request**, and then click **Create Pull Request** to submit.

2. **Check and Merge：**
   - After submission, administrator will check and merge Pull Request. After passing the checking, your information and contributions will be added to the website.

---
