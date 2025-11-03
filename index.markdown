---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: "Tributación, contabilidad y legislación para empresas de primera categoría"
---

<ul class="list-unstyled"> {% for post in site.posts %}

    {%- assign post_date = post.date | date: "%s" -%}
    {%- assign current_date = 'now' | date: "%s" -%}

    {% if post_date <= current_date %}

      <li class="card-body my-4 p-3 shadow-lg">

        <h2 class="card-title">
          {{ post.title }}
        </h2>

        <p class="card-text">
          Publicado: {{ post.date | date_to_string }}
        </p>

        <div>
          {{ post.excerpt }}
          <a href="{{ post.url }}" class="btn btn-primary mt-3">Leer más</a>
        </div>
      </li>

    {% endif %}

  {% endfor %}
</ul>
