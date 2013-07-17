RebuildCategory by ColumnValue
==========================================

&lt;MTRebuildCategoryByColumnValue eq="hoge"&gt;
カテゴリー名がhogeのカテゴリーアーカイブが再構築される。

&lt;MTRebuildCategoryByColumnValue column="label" class="category" eq="hoge"&gt;
上と同じ動作をする。

column: mt_categoryのカラムを指定する（ex. id, basename, label・指定無しの場合label）

class: category または folder（指定なしの場合category）

eq: 比較する値（必須・指定カラムがこの値であるものが再構築対象になる）

blog_id: 再構築するカテゴリーのあるブログID（指定無しの場合はカレントブログ・allを指定した時はすべてのブログが対象）

template_id: 再構築対象となるカテゴリーテンプレートのID（必要な時のみ）

templatemap_id: 再構築対象のtemplatemap ID（必要な時のみ）
