# 第10回振り返りレポート

## 1. GitHubアカウント

| 氏名           | 学籍番号    | GitHubアカウント(登録メールアドレス) |
| -------------- | ----------- | -------------------------------------- |
| 神田哲兵     | K21042      | tet430(minionn87731@gmail.com) |

## 2. 作成した日記リポジトリのコミットログ

チームのOrganaizationにて作成した日記リポジトリをcloneしたローカルディレクトリにて、mainブランチをfetch/pullした後に、`$ git --no-pager log --graph`を実行し、結果を以下の`<rpe></pre>`内に貼り付けます。

<pre>
* commit 8958b20440ed040fed4db7dd447b7aac35c7736a (HEAD -> main, origin/main, origin/HEAD)
| Author: Minmin <kwm067t93@gmail.com>
| Date:   Wed Dec 14 12:58:39 2022 +0900
| 
|     update main.py
|   
*   commit e02464a441e917bb2960d14482cbd11dc702accd
|\  Merge: a348b2d 63ac1ef
| | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | Date:   Wed Dec 14 12:56:03 2022 +0900
| | 
| |     Merge pull request #9 from 2022AIT-OOP2-G02/motoki-diary-add-
| |     
| |     Motoki diary add
| | 
| * commit 63ac1ef00977c2ff1c16272932e8db6ba298a7db (origin/motoki-diary-add-)
| | Author: motikiti <mtk0905@ezweb.ne.jp>
| | Date:   Tue Dec 13 14:55:36 2022 +0900
| | 
| |     日記
| |     
| |     日記書いた
| | 
| * commit 50bb6984eb9ee4750d8c780eb65f9908cefa6881
| | Author: motikiti <mtk0905@ezweb.ne.jp>
| | Date:   Sat Dec 10 12:08:25 2022 +0900
| | 
| |     Create MotokiDiary.py
| | 
* | commit a348b2de6e659829b886513d4dff2f1bcce07296
| | Author: motikiti <mtk0905@ezweb.ne.jp>
| | Date:   Sat Dec 10 12:21:49 2022 +0900
| | 
| |     Create MotokiDiary.py
| | 
* | commit 117dacde87f0b79e7b9717213b4d213c93a61261
| | Author: Minmin <kwm067t93@gmail.com>
| | Date:   Thu Dec 8 16:58:37 2022 +0900
| | 
| |     Delete omoriDiary.py
| |     
| |     大森君の最初の日記のファイルが残っていたので削除しました
| |   
* |   commit 7e6895ae81ae48269a58141e7e6523d01b2293e5
|\ \  Merge: ce67b39 144f1fc
| | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | Date:   Thu Dec 8 16:56:20 2022 +0900
| | | 
| | |     Merge pull request #8 from 2022AIT-OOP2-G02/Oomori-add-Diary
| | |     
| | |     日記新作
| | | 
| * | commit 144f1fcb08c074d214bd9ad85b238cb6d4c99c96 (origin/Oomori-add-Diary)
|/ /  Author: lmori-78 <k21025kk@aitech.ac.jp>
| |   Date:   Thu Dec 8 16:33:37 2022 +0900
| |   
| |       日記新作
| |   
* |   commit ce67b39b3cf595861309371864deaa7ad7c7875b
|\ \  Merge: 892464a e2fbbf7
| | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | Date:   Thu Dec 8 16:15:58 2022 +0900
| | | 
| | |     Merge pull request #7 from 2022AIT-OOP2-G02/omori-diary-add
| | |     
| | |     おおもり日記追加
| | |   
| * |   commit e2fbbf705ca063bddd7dd9a8215a7db97b441b24 (origin/omori-diary-add)
| |\ \  Merge: c7c3610 892464a
| |/ /  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| |   Date:   Thu Dec 8 16:15:38 2022 +0900
| | |   
| | |       Merge branch 'main' into omori-diary-add
| | |   
* | |   commit 892464a90da959e9da79d2fddc34c95f2628f7ca
|\ \ \  Merge: 2af1244 b94ff0c
| | | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | | Date:   Thu Dec 8 16:14:33 2022 +0900
| | | | 
| | | |     Merge pull request #6 from 2022AIT-OOP2-G02/hamaoka-diary-add
| | | |     
| | | |     hamaoka
| | | |   
| * | |   commit b94ff0c52110ccc3e9687094390b55d56116ab09 (origin/hamaoka-diary-add)
| |\ \ \  Merge: 9fe7c4f 2af1244
| |/ / /  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| | |   Date:   Thu Dec 8 16:13:38 2022 +0900
| | | |   
| | | |       Merge branch 'main' into hamaoka-diary-add
| | | |   
* | | |   commit 2af1244c8bb3526a60bdf8e80de5aac45d99b8ff
|\ \ \ \  Merge: 58dab51 e058bde
| | | | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | | | Date:   Thu Dec 8 16:08:40 2022 +0900
| | | | | 
| | | | |     Merge pull request #5 from 2022AIT-OOP2-G02/shimizu-add-dirly1
| | | | |     
| | | | |     清水の日記を追加
| | | | |   
| * | | |   commit e058bde3c924f7bab60eb8ab9c4f68c334e8689f (origin/shimizu-add-dirly1)
| |\ \ \ \  Merge: 541c999 58dab51
| |/ / / /  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| | | |   Date:   Thu Dec 8 16:07:11 2022 +0900
| | | | |   
| | | | |       Merge branch 'main' into shimizu-add-dirly1
| | | | |   
* | | | |   commit 58dab5118a9a7af111607ee7c617695bdff96101
|\ \ \ \ \  Merge: f3dbb90 96d7e2f
| | | | | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | | | | Date:   Thu Dec 8 16:05:36 2022 +0900
| | | | | | 
| | | | | |     Merge pull request #4 from 2022AIT-OOP2-G02/fukuhara-diary
| | | | | |     
| | | | | |     福原の日記を新規追加
| | | | | |   
| * | | | |   commit 96d7e2f6c5f38baa4c5ad74ca6e88881f1837c34 (origin/fukuhara-diary)
| |\ \ \ \ \  Merge: 5e8d81a f3dbb90
| |/ / / / /  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| | | | |   Date:   Thu Dec 8 16:05:06 2022 +0900
| | | | | |   
| | | | | |       Merge branch 'main' into fukuhara-diary
| | | | | |   
* | | | | |   commit f3dbb90756288c8db69c32332c8957a37bb1175b
|\ \ \ \ \ \  Merge: 599146b dcd6108
| | | | | | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | | | | | Date:   Thu Dec 8 16:03:32 2022 +0900
| | | | | | | 
| | | | | | |     Merge pull request #3 from 2022AIT-OOP2-G02/kanda-diary
| | | | | | |     
| | | | | | |     神田の日記を新規追加
| | | | | | |   
| * | | | | |   commit dcd6108445295fbabbb1048b1192c75ba66f205f (origin/kanda-diary, kanda-diary)
| |\ \ \ \ \ \  Merge: 69a4548 599146b
| |/ / / / / /  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| | | | | |   Date:   Thu Dec 8 16:02:22 2022 +0900
| | | | | | |   
| | | | | | |       Merge branch 'main' into kanda-diary
| | | | | | |   
* | | | | | |   commit 599146b5fcba86a6957ae889af35f29e4f9ca827
|\ \ \ \ \ \ \  Merge: d611ccb 92f19d1
| |_|_|_|_|_|/  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| | | | | |   Date:   Thu Dec 8 15:59:05 2022 +0900
| | | | | | |   
| | | | | | |       Merge pull request #1 from 2022AIT-OOP2-G02/izumi-add-diary
| | | | | | |       
| | | | | | |       add IzumiDiary
| | | | | | | 
| * | | | | | commit 92f19d12c184aa6bc958e86eab57e5b93d11fc26 (origin/izumi-add-diary)
|/ / / / / /  Author: Minmin <kwm067t93@gmail.com>
| | | | | |   Date:   Thu Dec 8 15:46:44 2022 +0900
| | | | | |   
| | | | | |       add IzumiDiary
| | | | | |       
| | | | | |       update main.py
| | | | | |       add IzumiDiary.py
| | | | | | 
| * | | | | commit 69a45480c0a95b8ed2eb7107ed909222bf3a8b78
|/ / / / /  Author: tet430 <Minionn87731@gmail.com>
| | | | |   Date:   Thu Dec 8 15:53:03 2022 +0900
| | | | |   
| | | | |       神田の日記を新規追加
| | | | | 
| * | | | commit 5e8d81afd9e5046da9492b85ae71e840beca3ab8
|/ / / /  Author: 福原優太 <fuyu0853@icloud.com>
| | | |   Date:   Thu Dec 8 15:52:48 2022 +0900
| | | |   
| | | |       福原の日記を新規追加
| | | | 
| * | | commit 541c9995f1dab30ee0f87996197699720803b7d4
|/ / /  Author: k21066-Shimizu <k21066kk@aitech.ac.jp>
| | |   Date:   Thu Dec 8 15:52:52 2022 +0900
| | |   
| | |       清水の日記を追加
| | | 
| * | commit 9fe7c4f66909ef02510affd7c3ca442e4f0e44af
| | | Author: hamaoka0317 <k21097kk@aitech.ac.jp>
| | | Date:   Thu Dec 8 16:09:00 2022 +0900
| | | 
| | |     Delete HamaokaDiary
| | | 
| * | commit 9250ec24ba7e9760507a0a7cd0507cc3d0c300c2
| | | Author: hamaoka0317 <k21097kk@aitech.ac.jp>
| | | Date:   Thu Dec 8 16:04:43 2022 +0900
| | | 
| | |     update +HamaokaDiary()
| | | 
| * | commit e4f0be60ec0aae5e0be1617209610ae206498159
|/ /  Author: hamaoka0317 <k21097kk@aitech.ac.jp>
| |   Date:   Thu Dec 8 15:58:13 2022 +0900
| |   
| |       Create HamaokaDiary
| | 
| * commit c7c3610aa91d5e0f9c144d25c3c85f78b5633869
|/  Author: lmori-78 <k21025kk@aitech.ac.jp>
|   Date:   Thu Dec 8 15:52:53 2022 +0900
|   
|       おおもり日記追加
| 
* commit d611ccba6833b8187c598ac314eaf5aae3684d05
| Author: Minmin <kwm067t93@gmail.com>
| Date:   Thu Dec 8 15:28:15 2022 +0900
| 
|     update main.py
| 
* commit c5a617f2923c8adf9b445dd8d8964abc57d6a1d8
| Author: Minmin <kwm067t93@gmail.com>
| Date:   Thu Dec 8 15:26:44 2022 +0900
| 
|     First commit
| 
* commit fd29f13fba375b24c8ab7a87ed6a024b982f44f6
  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
  Date:   Thu Dec 8 15:18:30 2022 +0900
  
      Initial commit
k21042kk@k21042kknoMacBook-Air Diary % git --no-pager log --graph
* commit 8958b20440ed040fed4db7dd447b7aac35c7736a (HEAD -> main, origin/main, origin/HEAD)
| Author: Minmin <kwm067t93@gmail.com>
| Date:   Wed Dec 14 12:58:39 2022 +0900
| 
|     update main.py
|   
*   commit e02464a441e917bb2960d14482cbd11dc702accd
|\  Merge: a348b2d 63ac1ef
| | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | Date:   Wed Dec 14 12:56:03 2022 +0900
| | 
| |     Merge pull request #9 from 2022AIT-OOP2-G02/motoki-diary-add-
| |     
| |     Motoki diary add
| | 
| * commit 63ac1ef00977c2ff1c16272932e8db6ba298a7db (origin/motoki-diary-add-)
| | Author: motikiti <mtk0905@ezweb.ne.jp>
| | Date:   Tue Dec 13 14:55:36 2022 +0900
| | 
| |     日記
| |     
| |     日記書いた
| | 
| * commit 50bb6984eb9ee4750d8c780eb65f9908cefa6881
| | Author: motikiti <mtk0905@ezweb.ne.jp>
| | Date:   Sat Dec 10 12:08:25 2022 +0900
| | 
| |     Create MotokiDiary.py
| | 
* | commit a348b2de6e659829b886513d4dff2f1bcce07296
| | Author: motikiti <mtk0905@ezweb.ne.jp>
| | Date:   Sat Dec 10 12:21:49 2022 +0900
| | 
| |     Create MotokiDiary.py
| | 
* | commit 117dacde87f0b79e7b9717213b4d213c93a61261
| | Author: Minmin <kwm067t93@gmail.com>
| | Date:   Thu Dec 8 16:58:37 2022 +0900
| | 
| |     Delete omoriDiary.py
| |     
| |     大森君の最初の日記のファイルが残っていたので削除しました
| |   
* |   commit 7e6895ae81ae48269a58141e7e6523d01b2293e5
|\ \  Merge: ce67b39 144f1fc
| | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | Date:   Thu Dec 8 16:56:20 2022 +0900
| | | 
| | |     Merge pull request #8 from 2022AIT-OOP2-G02/Oomori-add-Diary
| | |     
| | |     日記新作
| | | 
| * | commit 144f1fcb08c074d214bd9ad85b238cb6d4c99c96 (origin/Oomori-add-Diary)
|/ /  Author: lmori-78 <k21025kk@aitech.ac.jp>
| |   Date:   Thu Dec 8 16:33:37 2022 +0900
| |   
| |       日記新作
| |   
* |   commit ce67b39b3cf595861309371864deaa7ad7c7875b
|\ \  Merge: 892464a e2fbbf7
| | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | Date:   Thu Dec 8 16:15:58 2022 +0900
| | | 
| | |     Merge pull request #7 from 2022AIT-OOP2-G02/omori-diary-add
| | |     
| | |     おおもり日記追加
| | |   
| * |   commit e2fbbf705ca063bddd7dd9a8215a7db97b441b24 (origin/omori-diary-add)
| |\ \  Merge: c7c3610 892464a
| |/ /  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| |   Date:   Thu Dec 8 16:15:38 2022 +0900
| | |   
| | |       Merge branch 'main' into omori-diary-add
| | |   
* | |   commit 892464a90da959e9da79d2fddc34c95f2628f7ca
|\ \ \  Merge: 2af1244 b94ff0c
| | | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | | Date:   Thu Dec 8 16:14:33 2022 +0900
| | | | 
| | | |     Merge pull request #6 from 2022AIT-OOP2-G02/hamaoka-diary-add
| | | |     
| | | |     hamaoka
| | | |   
| * | |   commit b94ff0c52110ccc3e9687094390b55d56116ab09 (origin/hamaoka-diary-add)
| |\ \ \  Merge: 9fe7c4f 2af1244
| |/ / /  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| | |   Date:   Thu Dec 8 16:13:38 2022 +0900
| | | |   
| | | |       Merge branch 'main' into hamaoka-diary-add
| | | |   
* | | |   commit 2af1244c8bb3526a60bdf8e80de5aac45d99b8ff
|\ \ \ \  Merge: 58dab51 e058bde
| | | | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | | | Date:   Thu Dec 8 16:08:40 2022 +0900
| | | | | 
| | | | |     Merge pull request #5 from 2022AIT-OOP2-G02/shimizu-add-dirly1
| | | | |     
| | | | |     清水の日記を追加
| | | | |   
| * | | |   commit e058bde3c924f7bab60eb8ab9c4f68c334e8689f (origin/shimizu-add-dirly1)
| |\ \ \ \  Merge: 541c999 58dab51
| |/ / / /  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| | | |   Date:   Thu Dec 8 16:07:11 2022 +0900
| | | | |   
| | | | |       Merge branch 'main' into shimizu-add-dirly1
| | | | |   
* | | | |   commit 58dab5118a9a7af111607ee7c617695bdff96101
|\ \ \ \ \  Merge: f3dbb90 96d7e2f
| | | | | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | | | | Date:   Thu Dec 8 16:05:36 2022 +0900
| | | | | | 
| | | | | |     Merge pull request #4 from 2022AIT-OOP2-G02/fukuhara-diary
| | | | | |     
| | | | | |     福原の日記を新規追加
| | | | | |   
| * | | | |   commit 96d7e2f6c5f38baa4c5ad74ca6e88881f1837c34 (origin/fukuhara-diary)
| |\ \ \ \ \  Merge: 5e8d81a f3dbb90
| |/ / / / /  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| | | | |   Date:   Thu Dec 8 16:05:06 2022 +0900
| | | | | |   
| | | | | |       Merge branch 'main' into fukuhara-diary
| | | | | |   
* | | | | |   commit f3dbb90756288c8db69c32332c8957a37bb1175b
|\ \ \ \ \ \  Merge: 599146b dcd6108
| | | | | | | Author: Minmin <89015418+Minmin067@users.noreply.github.com>
| | | | | | | Date:   Thu Dec 8 16:03:32 2022 +0900
| | | | | | | 
| | | | | | |     Merge pull request #3 from 2022AIT-OOP2-G02/kanda-diary
| | | | | | |     
| | | | | | |     神田の日記を新規追加
| | | | | | |   
| * | | | | |   commit dcd6108445295fbabbb1048b1192c75ba66f205f (origin/kanda-diary, kanda-diary)
| |\ \ \ \ \ \  Merge: 69a4548 599146b
| |/ / / / / /  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| | | | | |   Date:   Thu Dec 8 16:02:22 2022 +0900
| | | | | | |   
| | | | | | |       Merge branch 'main' into kanda-diary
| | | | | | |   
* | | | | | |   commit 599146b5fcba86a6957ae889af35f29e4f9ca827
|\ \ \ \ \ \ \  Merge: d611ccb 92f19d1
| |_|_|_|_|_|/  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
|/| | | | | |   Date:   Thu Dec 8 15:59:05 2022 +0900
| | | | | | |   
| | | | | | |       Merge pull request #1 from 2022AIT-OOP2-G02/izumi-add-diary
| | | | | | |       
| | | | | | |       add IzumiDiary
| | | | | | | 
| * | | | | | commit 92f19d12c184aa6bc958e86eab57e5b93d11fc26 (origin/izumi-add-diary)
|/ / / / / /  Author: Minmin <kwm067t93@gmail.com>
| | | | | |   Date:   Thu Dec 8 15:46:44 2022 +0900
| | | | | |   
| | | | | |       add IzumiDiary
| | | | | |       
| | | | | |       update main.py
| | | | | |       add IzumiDiary.py
| | | | | | 
| * | | | | commit 69a45480c0a95b8ed2eb7107ed909222bf3a8b78
|/ / / / /  Author: tet430 <Minionn87731@gmail.com>
| | | | |   Date:   Thu Dec 8 15:53:03 2022 +0900
| | | | |   
| | | | |       神田の日記を新規追加
| | | | | 
| * | | | commit 5e8d81afd9e5046da9492b85ae71e840beca3ab8
|/ / / /  Author: 福原優太 <fuyu0853@icloud.com>
| | | |   Date:   Thu Dec 8 15:52:48 2022 +0900
| | | |   
| | | |       福原の日記を新規追加
| | | | 
| * | | commit 541c9995f1dab30ee0f87996197699720803b7d4
|/ / /  Author: k21066-Shimizu <k21066kk@aitech.ac.jp>
| | |   Date:   Thu Dec 8 15:52:52 2022 +0900
| | |   
| | |       清水の日記を追加
| | | 
| * | commit 9fe7c4f66909ef02510affd7c3ca442e4f0e44af
| | | Author: hamaoka0317 <k21097kk@aitech.ac.jp>
| | | Date:   Thu Dec 8 16:09:00 2022 +0900
| | | 
| | |     Delete HamaokaDiary
| | | 
| * | commit 9250ec24ba7e9760507a0a7cd0507cc3d0c300c2
| | | Author: hamaoka0317 <k21097kk@aitech.ac.jp>
| | | Date:   Thu Dec 8 16:04:43 2022 +0900
| | | 
| | |     update +HamaokaDiary()
| | | 
| * | commit e4f0be60ec0aae5e0be1617209610ae206498159
|/ /  Author: hamaoka0317 <k21097kk@aitech.ac.jp>
| |   Date:   Thu Dec 8 15:58:13 2022 +0900
| |   
| |       Create HamaokaDiary
| | 
| * commit c7c3610aa91d5e0f9c144d25c3c85f78b5633869
|/  Author: lmori-78 <k21025kk@aitech.ac.jp>
|   Date:   Thu Dec 8 15:52:53 2022 +0900
|   
|       おおもり日記追加
| 
* commit d611ccba6833b8187c598ac314eaf5aae3684d05
| Author: Minmin <kwm067t93@gmail.com>
| Date:   Thu Dec 8 15:28:15 2022 +0900
| 
|     update main.py
| 
* commit c5a617f2923c8adf9b445dd8d8964abc57d6a1d8
| Author: Minmin <kwm067t93@gmail.com>
| Date:   Thu Dec 8 15:26:44 2022 +0900
| 
|     First commit
| 
* commit fd29f13fba375b24c8ab7a87ed6a024b982f44f6
  Author: Minmin <89015418+Minmin067@users.noreply.github.com>
  Date:   Thu Dec 8 15:18:30 2022 +0900
  
      Initial commit

</pre>


## 3. Git及びGitHubに関する調査

以下の各項目について、インターネットや書籍を利用し調べ、自分なりの言葉で説明をしてください。(参考文献等あればそれも記載すること)

### 3-1. Gitを始めとしたバージョン管理システムを利用することによるメリットはなにか
・更新履歴を記録し、あとで確認したり前の状態に戻したりできる
・共同作業ができる
・異なる保存場所を切り替えられる
参照：https://www.it-career-navi.com/entry/about-git


### 3-2. Gitにおけるキーワード「clone」「commit」「push」「branch」「fetch」「pull」「merge」「rebase」についてそれぞれ何をするものか (他者に説明できるよう、わかりやすく簡潔な文章で表すこと)
#### 「clone」
既存のリポジトリ（保存場所）をローカル環境に複製するコマンドのこと
#### 「commit」
ファイルやディレクトリの追加・変更を、リポジトリに記録する操作のこと。保存
#### 「push」
リモートリポジトリ（git内）で自分の手元のローカルリポジトリ(pc内)の変更履歴を共有するには、ローカルリポジトリ内の変更履歴をアップロードする必要がある。この操作のこと
#### 「branch」
履歴の流れを分岐して記録していくためのものです。分岐したブランチは他のブランチの影響を受けないため、同じリポジトリ中で複数の変更を同時に進めていくことができる
#### 「fetch」
fetchを実行すると、リモートリポジトリの最新の履歴の取得だけを行うことができる
#### 「pull」
Pullを実行すると、リモートリポジトリから最新の変更履歴をダウンロードしてきて、自分のローカルリポジトリにその内容を取り込む
#### 「merge」
現在使用しているブランチに特定のブランチを取り込むためのコマンド
#### 「rebase」
作業が完了したブランチを分岐元のブランチにくっつける時に使う機能の一つ

### 3-3. プロジェクト進行に、Pull Requestを用いたGitHub Flowを採用することで、解決できるチーム開発での問題はなにか (実際にGitHub Flowで作業する手順も説明できる範囲でする)
プルリクエストとは、リモートリポジトリにてマージする際に挟む確認作業のこと。このプルリクエストを使用することでレビューなどのフィードバックをもらいながら開発ができる。
