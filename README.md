mt-plugin-rebuild-category-by-column-value
==========================================

<MTRebuildCategoryByColumnValue eq="hoge">
カテゴリー名がhogeのカテゴリーアーカイブが再構築される。

<MTRebuildCategoryByColumnValue column="label" class="category" eq="hoge">
上と同じ動作をする。

column: mt_categoryのカラムを指定する（ex. id, basename, label）
class: category または folder
eq: 比較する値（指定カラムがこの値であるものが再構築対象になる）


Rebuild category by category's column value.
