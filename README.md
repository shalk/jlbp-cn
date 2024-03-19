---
page:
  title: Google Java 库最佳实践
permalink: /
---

# Google Java 库最佳实践

Google Java 库的最佳实践是一些规则，旨在减少使用相关的Java库时的问题。
这些实践来自于多年来维护开源Java库的经验，并且受到了从错误中吸取的许多宝贵教训的启发。
我们发现遵循这些规则可以得到质量更高的Java库，减少依赖冲突和其他类型的问题。
这个规则列表是开放的，所以可能会不时地添加新的规则。

## Best practices

{% for p in site.pages %}{% if p.jlbp -%}
- [{{ p.jlbp.id }}]({{ p.url | relative_url }}): {{ p.title }}
{% endif %}{% endfor -%}

## Concepts

{% for p in site.pages %}{% if p.concepts -%}
- [{{ p.title}}]({{ p.url | relative_url }})
{% endif %}{% endfor -%}

## Reference

- [术语表](glossary.md): 最佳实践中的术语以及其他开源云Java仓库中的术语
