<!--
- 👋 Hi, I’m @scm-lee
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!---
scm-lee/scm-lee is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# GitHub markdown
以下のリンクはGitHub markdownについての理解を深めるため用意します\
[GitHub markdown](https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

# テキストのスタイル設定

**このテキストgithub markdownの練習です**\
_このテキストgithub markdownの練習です_\
~~このテキストgithub markdownの練習です~~\
**このテキストgithub markdownの練習です**\
***このテキストgithub markdownの練習です***\
このテキスト<sub>github markdowns</sub>の練習です\
このテキスト<ins>github markdown</ins>の練習です\

# テキストの引用

> text that is not a quote

# コードの引用
Use `git status` to list all new or modified files that haven't yet been committed.\
Some basic Git commands are:
```
git status
git add
git commit
```

# サポートされているカラーモデル
The background color is `#ffffff` for light mode and `#000000` for dark mode.

# リンク
This site was built using [GitHub Pages](https://pages.github.com/).

# セクションリンク
Link to the sample section: [Link Text](#sample-section).\
Link to the helpful section: [Link Text](#thisll-be-a-helpful-section-about-the-greek-letter-Θ).

# 相対リンク
<!-- 遷移されることを確認しました -->
[Contribution guidelines for this project](doc/CONTRIBUTING.md).

# カスタムアンカー
Some body text of this section.

<a name="my-custom-anchor-point"></a>
Some text I want to provide a direct link to, but which doesn't have its own heading.

(… more content…)

[A link to that custom anchor](#my-custom-anchor-point)

# 画像
色々なブランチが必要なのでリンクにする\
[画像についてのGitHubリンク](https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images).

# リスト
- George Washington
* Jone Adams
+ Thomas Jefferson

1. James Madison
2. James Monroe
3. John Quincy Adams
<!-- -->
1. First list itme
   - First nested list itme
     - Second nested list itme

# タスクリスト
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada: 

# 人やTeamのメンション
この項目はGitHubのリンクにしておきます\
[人やTeamのメンション](https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#mentioning-people-and-teams).

# 脚注
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, profix new lines with 2 spaces.
  This is a second line.

# 警告
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of actions.

# テーブルの作成
| First Header | Second Header |
| ------------ | ------------- |
| Content cell | Content cell  |
| Content cell | Content cell  |

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |
| link of git table | [git table](https://docs.github.com/ja/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables) |

| Left-aligened | Center-aligned | Right-aligned |
| :---          |      :--:      |          ---: |
| git status    | git status     | git status    |
| git diff    | git diff     | git diff |

| Name | Character |
| --- | --- |
| Backtick | ` |
| Pipe | \| |

# セクションを折りたたんで情報を整理する
<details>
   <summary>Tips for collapsed sections</summary>

   ### You can add a header

   Youy can add text within a collapsed section.

   You can add an image or a code block, too.

   ```ruby
      puts "Hellow World"
   ```
</details>

# コードブロックの作成と強調表示
```
function test() {
   console.log("notice the blank line before this function?");
}
```
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hellow World")
puts markdown.to_html
```
# ダイアグラム作成
Here is a simple flow chart:

```mermaid
graph TD;
   A-->B;
   A-->C;
   B-->D;
   C-->D;
```

```mermaid
   info
```

# GeoJSONマップとTopoJSONマップ作成
```geojson
{
   "type": "FeatureCollection",
   "features": [
   {
      "type": "Feature",
      "id": 1,
      "properties": {
         "ID": 0
      },
      "geometry": {
         "type": "Polygon",
         "coordinates": [
            [
               [-90,35],
               [-90,30],
               [-85,30],
               [-85,35],
               [-90,35]
            ]
         ]
      }
   }
]
}
```
これ以外も沢山ありますので、参照してほしいです。
[ダイアグラムなど色々な表を作成する方法](https://docs.github.com/ja/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams).
