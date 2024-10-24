# Git Komutları - En Sık Kullanılanlar (EN | TR)

| **Command (EN)** | **Komut (TR)** |
|------------------|----------------|
| **1. `git init`**<br>Initializes a new Git repository in the current directory. It creates a `.git` directory that tracks all changes. | **1. `git init`**<br>Mevcut dizinde yeni bir Git deposu başlatır. Tüm değişiklikleri izleyen `.git` dizinini oluşturur. |
| **Usage:**<br>`git init`<br>**Example:**<br>`mkdir my_project && cd my_project && git init` | **Kullanım:**<br>`git init`<br>**Örnek:**<br>`mkdir benim_projem && cd benim_projem && git init` |

| **2. `git clone`**<br>Creates a local copy of a remote repository. | **2. `git clone`**<br>Uzak bir deponun yerel bir kopyasını oluşturur. |
| **Usage:**<br>`git clone <repository-url>`<br>**Example:**<br>`git clone https://github.com/user/project.git` | **Kullanım:**<br>`git clone <depo-url>`<br>**Örnek:**<br>`git clone https://github.com/kullanici/proje.git` |

| **3. `git status`**<br>Displays the state of the working directory and the staging area. It shows which changes have been staged, which haven't, and which files aren't being tracked by Git. | **3. `git status`**<br>Çalışma dizininin ve geçici alanın durumunu gösterir. Hangi değişikliklerin geçici alana alındığını, hangilerinin alınmadığını ve hangi dosyaların Git tarafından izlenmediğini gösterir. |
| **Usage:**<br>`git status` | **Kullanım:**<br>`git status` |

| **4. `git add`**<br>Adds files to the staging area. Prepares them to be included in the next commit. | **4. `git add`**<br>Dosyaları geçici alana ekler. Bir sonraki commit'e dahil edilmeleri için hazırlar. |
| **Usage:**<br>`git add <file-name>`<br>**Add all changes:**<br>`git add .` | **Kullanım:**<br>`git add <dosya-adı>`<br>**Tüm değişiklikleri eklemek için:**<br>`git add .` |

| **5. `git commit`**<br>Records changes to the repository with a descriptive message. | **5. `git commit`**<br>Depoya açıklayıcı bir mesajla değişiklikleri kaydeder. |
| **Usage:**<br>`git commit -m "Commit message"`<br>**Amend last commit:**<br>`git commit --amend` | **Kullanım:**<br>`git commit -m "Commit mesajı"`<br>**Son commit'i düzeltmek için:**<br>`git commit --amend` |

| **6. `git push`**<br>Uploads local commits to a remote repository. | **6. `git push`**<br>Yerel commit'leri uzak bir depoya yükler. |
| **Usage:**<br>`git push <remote> <branch>`<br>**Example:**<br>`git push origin main` | **Kullanım:**<br>`git push <uzak-depo> <dal>`<br>**Örnek:**<br>`git push origin main` |

| **7. `git pull`**<br>Fetches from and integrates with another repository or a local branch. | **7. `git pull`**<br>Başka bir depodan veya yerel bir daldan değişiklikleri alır ve birleştirir. |
| **Usage:**<br>`git pull <remote> <branch>`<br>**Example:**<br>`git pull origin main` | **Kullanım:**<br>`git pull <uzak-depo> <dal>`<br>**Örnek:**<br>`git pull origin main` |

| **8. `git fetch`**<br>Downloads objects and refs from another repository. Unlike `git pull`, it doesn't merge changes automatically. | **8. `git fetch`**<br>Başka bir depodan nesneleri ve referansları indirir. `git pull`'dan farklı olarak, değişiklikleri otomatik olarak birleştirmez. |
| **Usage:**<br>`git fetch <remote>`<br>**Example:**<br>`git fetch origin` | **Kullanım:**<br>`git fetch <uzak-depo>`<br>**Örnek:**<br>`git fetch origin` |

| **9. `git merge`**<br>Merges one or more branches into your current branch and automatically creates a new commit if there are no conflicts. | **9. `git merge`**<br>Bir veya daha fazla dalı geçerli dalınıza birleştirir ve eğer çakışma yoksa otomatik olarak yeni bir commit oluşturur. |
| **Usage:**<br>`git merge <branch-name>`<br>**Example:**<br>`git merge feature-branch` | **Kullanım:**<br>`git merge <dal-adı>`<br>**Örnek:**<br>`git merge ozellik-dali` |

| **10. `git branch`**<br>Lists, creates, or deletes branches. | **10. `git branch`**<br>Dalları listeler, oluşturur veya siler. |
| **Usage:**<br>`git branch` (list branches)<br>`git branch <new-branch>` (create new branch)<br>`git branch -d <branch>` (delete branch) | **Kullanım:**<br>`git branch` (dalları listele)<br>`git branch <yeni-dal>` (yeni dal oluştur)<br>`git branch -d <dal>` (dalı sil) |

| **11. `git checkout`**<br>Switches branches or restores working tree files. | **11. `git checkout`**<br>Dalları değiştirir veya çalışma dizini dosyalarını geri yükler. |
| **Usage:**<br>`git checkout <branch-name>`<br>`git checkout -b <new-branch>` (create and switch to new branch) | **Kullanım:**<br>`git checkout <dal-adı>`<br>`git checkout -b <yeni-dal>` (yeni dal oluştur ve geçiş yap) |

| **12. `git log`**<br>Shows the commit history for the current branch. | **12. `git log`**<br>Geçerli dal için commit geçmişini gösterir. |
| **Usage:**<br>`git log`<br>`git log --oneline` (brief history) | **Kullanım:**<br>`git log`<br>`git log --oneline` (kısa geçmiş) |

| **13. `git reset`**<br>Resets current HEAD to the specified state. Can unstage changes or move the branch pointer. | **13. `git reset`**<br>Geçerli HEAD'i belirtilen duruma sıfırlar. Değişiklikleri geçici alandan çıkarabilir veya dal işaretçisini taşıyabilir. |
| **Usage:**<br>`git reset <file>` (unstage file)<br>`git reset --hard <commit>` (reset to commit) | **Kullanım:**<br>`git reset <dosya>` (dosyayı geçici alandan çıkar)<br>`git reset --hard <commit>` (belirtilen commit'e sıfırla) |

| **14. `git revert`**<br>Creates a new commit that undoes the changes from a previous commit. | **14. `git revert`**<br>Önceki bir commit'in değişikliklerini geri alan yeni bir commit oluşturur. |
| **Usage:**<br>`git revert <commit>` | **Kullanım:**<br>`git revert <commit>` |

| **15. `git stash`**<br>Saves your local modifications away and reverts the working directory to match the HEAD commit. | **15. `git stash`**<br>Yerel değişikliklerinizi kaydeder ve çalışma dizinini HEAD commit'i ile eşleşecek şekilde geri alır. |
| **Usage:**<br>`git stash` (save changes)<br>`git stash pop` (apply saved changes) | **Kullanım:**<br>`git stash` (değişiklikleri sakla)<br>`git stash pop` (saklanan değişiklikleri uygula) |

| **16. `git remote`**<br>Manages set of tracked repositories. | **16. `git remote`**<br>İzlenen depo setini yönetir. |
| **Usage:**<br>`git remote -v` (list remotes)<br>`git remote add <name> <url>` (add new remote) | **Kullanım:**<br>`git remote -v` (uzak depoları listele)<br>`git remote add <isim> <url>` (yeni uzak depo ekle) |

| **17. `git tag`**<br>Creates, lists, or deletes tags. Tags are used to mark specific points in history as important. | **17. `git tag`**<br>Etiketleri oluşturur, listeler veya siler. Etiketler, geçmişteki belirli noktaları önemli olarak işaretlemek için kullanılır. |
| **Usage:**<br>`git tag` (list tags)<br>`git tag -a v1.0 -m "Version 1.0"` (create annotated tag) | **Kullanım:**<br>`git tag` (etiketleri listele)<br>`git tag -a v1.0 -m "Sürüm 1.0"` (açıklamalı etiket oluştur) |

| **18. `git config`**<br>Sets configuration variables that control all facets of how Git looks and operates. | **18. `git config`**<br>Git'in nasıl göründüğünü ve çalıştığını kontrol eden yapılandırma değişkenlerini ayarlar. |
| **Usage:**<br>`git config --global user.name "Your Name"`<br>`git config --global user.email "you@example.com"` | **Kullanım:**<br>`git config --global user.name "Adınız"`<br>`git config --global user.email "email@ornek.com"` |

| **19. `git diff`**<br>Shows changes between commits, commit and working tree, etc. | **19. `git diff`**<br>Commit'ler arasındaki, commit ile çalışma dizini arasındaki vb. farkları gösterir. |
| **Usage:**<br>`git diff` (unstaged changes)<br>`git diff --staged` (staged changes) | **Kullanım:**<br>`git diff` (geçici alana alınmamış değişiklikler)<br>`git diff --staged` (geçici alandaki değişiklikler) |

| **20. `git show`**<br>Displays information about a git object (commit, tag, etc.). | **20. `git show`**<br>Bir git nesnesi (commit, etiket vb.) hakkında bilgi gösterir. |
| **Usage:**<br>`git show <commit>` | **Kullanım:**<br>`git show <commit>` |

---

Bu güncellemelerle birlikte, README dosyanız Git'in en sık kullanılan komutlarını ve onların detaylı açıklamalarını içerir. Her bir komut için kullanım şekilleri ve örnekler eklenmiştir. Bu sayede, Git'i daha etkin bir şekilde kullanabilir ve sürüm kontrol süreçlerinizi iyileştirebilirsiniz.

Eğer daha fazla komut eklemek veya mevcut açıklamaları daha da detaylandırmak isterseniz, lütfen bildirin, yardımcı olmaktan memnuniyet duyarım.
