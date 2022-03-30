---
title: Github Pages Math Equation
---
#### 配置
1. 在MD文件中使用正常语法标记数学公式，例：
```markdown
$$E=mc^2$$
```

2. 配置_config.yml文件，修改markdown参数：
```yaml
# Build settings
markdown: kramdown
```
3. 在模板文件中添加mathjax解析，如在custom-head.html中添加：
```html
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript" ></script>
```

4. inline and outline
+ inline
```markdown
这个是质能方程
$$ E=mc^2 $$
```
这个是质能方程
$$ E=mc^2 $$
+ outline
```markdown
这个是质能方程
CRCF
$$ E=mc^2 $$
```
这个是质能方程
$$ E=mc^2 $$

---
这是个复合函数 
$$f(x)=\frac{P(x)}{Q(x)}$$

求积分运算

$$\int_{a}^{b} {\frac {\sin{x}} {x}} = \frac {\sin{x}} {x} \mid ^{b} _{a}$$
