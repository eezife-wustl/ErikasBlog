# Erika's Blog

Relaunching my blog era with the power of **Jekyll**.

---

## Note to Self

1. Install Ruby and RubyGems  
2. Run: `gem install jekyll bundler`  
3. Then: `bundle install`  
4. Preview at: [http://127.0.0.1:4000/Erikasblog/](http://127.0.0.1:4000/Erikasblog/)

---

## To Do

- Add blog posts with previews  
- Create pages  

---

## Blog Post Preview Snippet

```liquid
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
