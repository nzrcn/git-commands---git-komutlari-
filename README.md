# Git Commands - Most Used (EN | TR)

| **Command (EN)** | **Komut (TR)** |
|------------------|----------------|
| **1. `git init`**<br>Initializes a new Git repository in the current directory. Creates a `.git` folder where all changes will be tracked. | **1. `git init`**<br>Mevcut dizinde yeni bir Git deposu başlatır. Tüm değişikliklerin izleneceği `.git` klasörünü oluşturur. |
| **Usage:**<br>`git init`<br>**Example:**<br>`mkdir my_project && cd my_project && git init` | **Kullanım:**<br>`git init`<br>**Örnek:**<br>`mkdir benim_projem && cd benim_projem && git init` |
| **2. `git clone`**<br>Clones an existing repository from a remote source to your local machine. | **2. `git clone`**<br>Uzak bir kaynaktan mevcut bir depoyu yerel makinenize klonlar. |
| **Usage:**<br>`git clone <repository-url>`<br>**Example:**<br>`git clone https://github.com/user/project.git` | **Kullanım:**<br>`git clone <repository-url>`<br>**Örnek:**<br>`git clone https://github.com/kullanici/proje.git` |
| **3. `git status`**<br>Shows the current state of the working directory and staging area, indicating changes. | **3. `git status`**<br>Çalışma dizini ve geçici alanın (staging area) durumunu gösterir, değişiklikleri belirtir. |
| **Usage:**<br>`git status` | **Kullanım:**<br>`git status` |
| **4. `git add`**<br>Adds changes in the working directory to the staging area in preparation for the next commit. | **4. `git add`**<br>Çalışma dizinindeki değişiklikleri bir sonraki commit için geçici alana ekler. |
| **Usage:**<br>`git add <file-name>`<br>**Add all files:**<br>`git add .` | **Kullanım:**<br>`git add <dosya-adı>`<br>**Tüm dosyaları eklemek:**<br>`git add .` |
| **5. `git commit`**<br>Saves staged changes to the repository with a message describing the changes. | **5. `git commit`**<br>Geçici alandaki değişiklikleri açıklayan bir mesajla depoya kaydeder. |
| **Usage:**<br>`git commit -m "Commit message"`<br>**Example:**<br>`git commit -m "Added new feature"` | **Kullanım:**<br>`git commit -m "Commit mesajı"`<br>**Örnek:**<br>`git commit -m "Yeni özellik eklendi"` |
| **6. `git push`**<br>Uploads local commits to a remote repository. | **6. `git push`**<br>Yerel commit'leri uzak bir depoya yükler. |
| **Usage:**<br>`git push origin <branch-name>`<br>**Example:**<br>`git push origin main` | **Kullanım:**<br>`git push origin <branch-adı>`<br>**Örnek:**<br>`git push origin main` |
| **7. `git pull`**<br>Fetches and integrates changes from the remote repository to your local branch. | **7. `git pull`**<br>Uzak depodaki en güncel değişiklikleri yerel dalınıza getirir ve entegre eder. |
| **Usage:**<br>`git pull origin <branch-name>`<br>**Example:**<br>`git pull origin main` | **Kullanım:**<br>`git pull origin <dal-adı>`<br>**Örnek:**<br>`git pull origin main` |
| **8. `git branch`**<br>Lists all branches or creates a new branch. Branches allow you to work on parallel features or bug fixes. | **8. `git branch`**<br>Tüm dalları listeler veya yeni bir dal oluşturur. Dallar, paralel özellikler veya hata düzeltmeleri üzerinde çalışmanızı sağlar. |
| **Usage:**<br>`git branch` (list branches)<br>`git branch <new-branch-name>` (create new branch) | **Kullanım:**<br>`git branch` (dalları listele)<br>`git branch <yeni-dal-adı>` (yeni dal oluştur) |
| **9. `git checkout`**<br>Switches to another branch or restores files to a previous state. | **9. `git checkout`**<br>Başka bir dala geçiş yapar veya dosyaları önceki bir duruma geri alır. |
| **Usage:**<br>`git checkout <branch-name>`<br>**Example:**<br>`git checkout main` | **Kullanım:**<br>`git checkout <dal-adı>`<br>**Örnek:**<br>`git checkout main` |
| **10. `git merge`**<br>Merges another branch into the current branch. | **10. `git merge`**<br>Başka bir dalı mevcut dala birleştirir. |
| **Usage:**<br>`git merge <branch-name>`<br>**Example:**<br>`git merge new-feature` | **Kullanım:**<br>`git merge <dal-adı>`<br>**Örnek:**<br>`git merge yeni-ozellik` |
| **11. `git log`**<br>Shows a list of previous commits, including commit hashes and messages. | **11. `git log`**<br>Önceki commit'lerin listesini gösterir, commit hash'leri ve mesajları içerir. |
| **Usage:**<br>`git log` | **Kullanım:**<br>`git log` |
