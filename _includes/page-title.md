{%-comment%}如果有CATEGORY 显示在标题前{%endcomment%}
{%-unless page.categories==empty-%}
  {{page.categories.last}}：
{%-endunless-%}

{{page.slug}}