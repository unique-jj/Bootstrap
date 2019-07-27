


# ����Ŭ����

��Ÿ�ϸ��� ���� ���ϰ� �����ִ� Ŭ������.

---

## �ƶ����� �ǹ̰� �ִ� ����

- Ŭ������ �̿��Ͽ� ������ ���� ������ �� �� ����.
- ��ũ���� ����Ǹ�, ���콺 �����ÿ��� ��Ÿ���� �����Ǿ� �ִ�.

![�ƶ����� �ǹ̰� �ִ� �����](../images/css-helper-class-01.png)
```html
<p class="text-muted">...</p>
<p class="text-primary">...</p>
<p class="text-success">...</p>
<p class="text-info">...</p>
<p class="text-warning">...</p>
<p class="text-danger">...</p>
```

#### Ư���� �ذ�
```
���� �ؽ�Ʈ ���� Ŭ������ �� �ٸ� ��Ŀ �������� Ư�������� ���� ������� ���� �� ����.
�ذ�å�� �ؽ�Ʈ�� Ŭ������ �Բ� <span> ���� ���θ� �ȴ�.
```

#### �ǹ̸� �����ϱ�
```
Ŭ������ ������ �ؽ�Ʈ���� �ð����� ������ ����� �� ��, ������ �ǹ̸� �������� ����.
������ ��ü�� ���� ���� �����Ϸ��� �ǵ��� ��Ȯ�� ǥ���ϴ� ���� ����.
������ �ʱ⸦ ���ϸ� .sr-only Ŭ������ ������ �� ����.
```




## �ƶ����� �ǹ̰� �ִ� ����

- �ؽ�Ʈ�� ����������, �ƶ����� �ǹ̰� �ִ� �������� ��� ������ ���� �� ����.
- �ؽ�Ʈ�� ����������, ��ũ���� ����Ǹ� ���콺 �����ÿ��� ��Ÿ���� ��������.

![�ƶ����� �ǹ̰� �ִ� ��� �����](../images/css-helper-class-02.png)
```html
<p class="bg-primary">...</p>
<p class="bg-success">...</p>
<p class="bg-info">...</p>
<p class="bg-warning">...</p>
<p class="bg-danger">...</p>
```

#### Ư���� �ذ�
```
���� ��� Ŭ������ �� �ٸ� ��Ŀ �������� Ư�������� ���� ������� ���� �� ����.
�ذ�å�� �ؽ�Ʈ�� Ŭ������ �Բ� <div> ���� ���θ� �ȴ�.
```

#### �ǹ̸� �����ϱ�
```
'�ƶ����� �ǹ̰� �ִ� ����' �� ����������, ���� �ǹ̸� �������� ���� Ȯ���� ������ ���� ����.
```



## �ݱ� ������
����̳� ����� �������� ���ֱ� ���� ������ �ݱ� �������� ���(`<button>` �±׸� �̿�)

![�ݱ� ������](../images/css-helper-class-03.png)
```html
<button type="button" class="close" aria-label="Close"><span aria-hidden="true">&times;</span></button>
```


## ĳ�� (Carets)
- ��Ӵٿ��� ��ɰ� ������ �˷���
- ��Ӿ� �޴������� ȭ��ǥ ������ �ݴ�

![ĳ�� ������](../images/css-helper-class-04.png)
```html
<span class="caret"></span>
```

## ������ float
- Ŭ������ �̿��� �¿�� float
- `!important`�� Ư�� �̽����� ���ϱ� ���� �����.
- �ͽ������� ��� ����

```html
<div class="pull-left">...</div>
<div class="pull-right">...</div>
```

```css
// Classes
.pull-left {
  float: left !important;
}
.pull-right {
  float: right !important;
}

// Usage as mixins
.element {
  .pull-left();
}
.another-element {
  .pull-right();
}
```

#### �׺���̼� �ٿ��� ������� ������.
```
�׺���̼� �ٿ��� ������Ʈ�� �����Ϸ��� .navbar-left �� .navbar-right �� ���
�ڼ��� ������ [�׺���̼ǹ�](http://bootstrapk.com/components/#navbar-component-alignment) ���� ����.
```


## ������ ��� �߾� ����
- `display: block` �� `margin` �� ��Ҹ� �����ϼ���
- �ͽ������� ��� ����

```html
<div class="center-block">...</div>
```

```css
// Class
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}

// Usage as a mixin
.element {
  .center-block();
}
```


## Clearfix
- `.clearfix`�� ����Ͽ� `float`�� ���� Ŭ����
- Nicolas Gallagher �� ������ [the micro clearfix](http://nicolasgallagher.com/micro-clearfix-hack/) ���
- �ͽ������� ��� ����

```html
<!-- Usage as a class -->
<div class="clearfix">...</div>
```

```css
// Mixin itself
.clearfix() {
  &:before,
  &:after {
    content: " ";
    display: table;
  }
  &:after {
    clear: both;
  }
}

// Usage as a mixin
.element {
  .clearfix();
}
```



## ������ ���̰� �����
- `.show`, `.hide`�� �̿��Ͽ� �������� ���̰ų� ���� �� ����.
- Ư�� �̽����� ���ϱ� ���� `!important` ���
- ���� `block` ���������� ����

* `.hide`�� ���������� ��ũ�� �������� �׻� ȿ���� �ִ°��� �ƴ�.(v3.0.1 ���� ������ ����.)
* `.hide` ��� `.sr-only`, `.hidden` ���
* `.invisible` �� ������ �帧(����)�� ����������, ������ �ʴ� ��Ҹ� ���� ���.

```html
<div class="show">...</div>
<div class="hidden">...</div>
```

```css
// Classes
.show {
  display: block !important;
}
.hidden {
  display: none !important;
  visibility: hidden !important;
}
.invisible {
  visibility: hidden;
}

// Usage as mixins
.element {
  .show();
}
.another-element {
  .hidden();
}
```



## ��ũ�� ������ Ű���� �׺���̼��� ������
- **��ũ�� ������ ������** ��� ��⿡�� �������� ����� ���� Ŭ���� : `.sr-only`
- �װ��� ��Ŀ�� �Ǿ��� �� ���̰� �ϱ� ���� Ŭ���� : `.sr-only-focusable`
  - ������ ���ټ��� ���� ����.(�� - Ű���常 ������ �ִ� ����ڵ��� ����)
- �ͽ������� ��� ����

```html
<a class="sr-only sr-only-focusable" href="#content">Skip to main content</a>
```

```css
// Usage as a mixin
.skip-navigation {
  .sr-only();
  .sr-only-focusable();
}
```




## �̹��� ��ü
`.text-hide` Ŭ������ �ͽ����� �ؽ�Ʈ �������� ��� �̹����� ��ü�ϴ� �� Ȱ��.

```html
<h1 class="text-hide">Custom heading</h1>
```

```css
// �ͽ������� ���
.heading {
  .text-hide();
}
```