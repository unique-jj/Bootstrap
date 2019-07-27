## �׺���̼� �� (Navbar)

###[�⺻ �׺���̼� �� (Default navbar)](http://getbootstrap.com/components/#navbar)
�׺���̼� �ٴ� ����� ���ø����̼��̳� ����Ʈ�� ���� ��� �׺���̼����� ������ ������ ��Ÿ ������Ʈ�Դϴ�. �װ͵��� ����� �信�� ������ ����(����� �� ����)�� �����ϸ� ������ ����Ʈ �ʺ� �Ǿ��� �� ���������� �������ϴ�.
�������ĵ� �׺���̼� �� ��ũ�� ���� �������� �ʽ��ϴ�.

* ������ �����÷ο� �ϴ°�
>�̰��� �ذ��Ϸ���, ����� ������ ���� �� �� �ֽ��ϴ�. Since Bootstrap doesn't know how much space the content in your navbar needs, you might run into issues with content wrapping into a second row. To resolve this, you can:    
	a.navbar �׸���� ���̳� �ʺ� ���Դϴ�.    
	b.[������ ��ƿ��Ƽ Ŭ����](http://bootstrapk.com/components/#navbar) �� ����Ͽ� ��� ȭ�� ũ�⿡�� ��� navbar �׸��� ����ϴ�.    
	c.navbar �� �������� �������� ������ �ٲߴϴ�. @grid-float-breakpoint ������ �����ϰų� ����� �̵�� ������ �߰��ϼ���.    

* �÷����� ������
>���� �ڹٽ�ũ��Ʈ�� ��Ȱ��ȭ�� ����Ʈ�� ������, �װ��� navbar �� �������� `.navbar-collapse` �� ������ �������� ���� �Ұ��� �� ���Դϴ�.
������ navbar �� ��Ʈ��Ʈ���� ���Ե� �÷��� �÷����� �� �ʿ��մϴ�.

* ������ ����� navbar �б����� �����ϱ�
>`navbar` �� ����� ���κ信�� `@grid-float-breakpoint `���� ������ ������,` @grid-float-breakpoint` ���� ũ�� �������ϴ�. navbar ����/��ħ�� ���� �����Ϸ��� Less ���� �� ������ �����ϼ���. �⺻���� `768px` �Դϴ�. ("�º�" ���� ȭ��)

* navbars �� ���ټ��ְ� ���弼��
>���� ������ ����ڵ鿡�� Ȯ���ϰ� �˸��� ���� `<nav>` �� ����ϴ� ���� Ȯ���� �ϰų�, �� �� �Ϲ����� `<div>` ���� ��ҿ�, `role="navigation"` �� �߰��ϵ��� �ϼ���.


![component_navbar_01](../images/component_navbar_01.jpg)

```html

<nav class="navbar navbar-default">
  <div class="container-fluid">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#">Brand</a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Link <span class="sr-only">(current)</span></a></li>
        <li><a href="#">Link</a></li>
        <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-expanded="false">Dropdown <span class="caret"></span></a>
          <ul class="dropdown-menu" role="menu">
            <li><a href="#">Action</a></li>
            <li><a href="#">Another action</a></li>
            <li><a href="#">Something else here</a></li>
            <li class="divider"></li>
            <li><a href="#">Separated link</a></li>
            <li class="divider"></li>
            <li><a href="#">One more separated link</a></li>
          </ul>
        </li>
      </ul>
      <form class="navbar-form navbar-left" role="search">
        <div class="form-group">
          <input type="text" class="form-control" placeholder="Search">
        </div>
        <button type="submit" class="btn btn-default">Submit</button>
      </form>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#">Link</a></li>
        <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-expanded="false">Dropdown <span class="caret"></span></a>
          <ul class="dropdown-menu" role="menu">
            <li><a href="#">Action</a></li>
            <li><a href="#">Another action</a></li>
            <li><a href="#">Something else here</a></li>
            <li class="divider"></li>
            <li><a href="#">Separated link</a></li>
          </ul>
        </li>
      </ul>
    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav>

```
----

###[�귣�� �̹���](http://getbootstrap.com/components/#navbar-brand-image)
`<img>` �� ���� �ؽ�Ʈ�� ��ü�ϴ� ������ navbar �귣�带 ����� �̹����� ��ü�ϼ���. `.navbar-brand` �� �ڽ��� �е��� ���̸� �����⶧����, ����� ����� �̹����� �°� �ణ�� CSS �� �������̵��ؾ��� �� �ֽ��ϴ�.

![component_navbar_02](../images/component_navbar_02.jpg)

```html

<nav class="navbar navbar-default">
  <div class="container-fluid">
    <div class="navbar-header">
      <a class="navbar-brand" href="#">
        <img alt="Brand" src="...">
      </a>
    </div>
  </div>
</nav>

```
----

###[��](http://getbootstrap.com/components/#navbar-forms)
���� ����Ʈ���� ������ ���� ���İ� ������ ������ ���ؼ� `.navbar-form `�ȿ� ���������� ��������. �װ��� navbar ������ ��� ��ġ���� �����ϱ� ���� ���� �ɼ��� ����ϼ���.
������ ���� `.navbar-form` �� �ͽ����� ���� `.form-inline` �� ���� �ڵ带 �����մϴ�. **navbar ���� �����ϰ� �������� �ϱ� ���� �Է� �׷찰�� ��� �� ��Ʈ���� ������ �ʺ� �ʿ��� �� �ֽ��ϴ�.**

![component_navbar_03](../images/component_navbar_03.jpg)

```html

<form class="navbar-form navbar-left" role="search">
  <div class="form-group">
    <input type="text" class="form-control" placeholder="Search">
  </div>
  <button type="submit" class="btn btn-default">Submit</button>
</form>

```
* ����� ��� ���
> ����ϱ�⿡�� ������ ��Ҿȿ� �� ��Ʈ���� ����ϴµ� ��� ��Ģ�� �ֽ��ϴ�. �ڼ��� ���� �츮�� ������ ���� ������ ������

* �׻� ���� �߰��ϼ���
> ��ũ�� ������ ���� ��� �Է¿� ���� �������� �ʴ´ٸ� ����� ���� �־� ������ ����ų ���Դϴ�. �̷� �ζ��� ���� ����, ����� .sr-only Ŭ������ ���� ����� �ֽ��ϴ�. ���⿡�� ���������� ���� ���� �����ϴ� `aria-label, aria-labelledby, title` �� ���� �Ǵٸ� ��ü ����� �ֽ��ϴ�. ���� �̰͵��� �������� �ʴ´ٸ�, ��ũ�� ������ `placeholder` �Ӽ��� ����� ���� �ֽ��ϴ�. ������ �̰��� �������� �ʽ��ϴ�.

----

###[��ư](http://getbootstrap.com/components/#navbar-buttons)
`<button>` ��ҿ� `.navbar-btn`�� �߰��ϸ� navbar ���� `<form>`������ ������ `vertically : center`�� ����� �ֽ��ϴ�.

![component_navbar_04](../images/component_navbar_04.jpg)

```html

<button type="button" class="btn btn-default navbar-btn">Sign in</button>

```
* ��Ȳ�� ���� ���.
> ǥ�� ��ư Ŭ����ó��, `.navbar-btn`�� `<a>`�� `<input>`���� ����� �� �ֽ��ϴ�. �׷��� `.navbar-btn`�� `<a>`�� `<input>`���� ����Ҷ��� `.navbar-nav`Ŭ���� �������� ����ؾ��մϴ�.

----

###[�ؽ�Ʈ](http://getbootstrap.com/components/#navbar-buttons)
������ �ణ�� ���� ���� ���ڿ��� .navbar-text �� ����� �±�(������ `<p>`)�� ���μ���.

![component_navbar_05](../images/component_navbar_05.jpg)

```html

<p class="navbar-text">Signed in as Mark Otto</p>

```
   

###[�Ϲ� ��ũ](http://getbootstrap.com/components/#navbar-text)
.nav ���ο� ���� ���� ��ũ�� ����Ϸ���, �⺻�� ���� �׺���̼� �ٿ� ������ ���� ���߱� ���� `.navbar-link` �� ����ϼ���.

![component_navbar_06](../images/component_navbar_06.jpg)

```html

<p class="navbar-text navbar-right">Signed in as <a href="#" class="navbar-link">Mark Otto</a></p>

```
----   


###[������Ʈ ���� (Component alignment)](http://getbootstrap.com/components/#navbar-component-alignment)
���� Ŭ���� `.navbar-left` �� `.navbar-right` �� ����Ͽ�, �׺���̼� ��ũ, ��, ��ư, �ؽ�Ʈ�� �����ϼ���. �� Ŭ�������� Ư���� �������� CSS float �� �����մϴ�. ���� ���, �׺���̼� ��ũ�� �����Ϸ���, �װ͵��� ������ ���� Ŭ������ ������ `<ul>` �� �и��Ͽ� �Ӵϴ�.
�� Ŭ�������� `.pull-left` �� `.pull-right` �� ���� �����Դϴٸ�, �װ͵��� �پ��� ��⿡�� �׺���̼� �ٸ� �� ���� �ٷ�� ���� �̵�� �����鿡 ������ �ֽ��ϴ�.

![component_navbar_06](../images/component_navbar_06.jpg)

```html
<p class="navbar-text navbar-right">Signed in as <a href="#" class="navbar-link">Mark Otto</a></p>

```

* ������ ������ ���� ������Ʈ

>navbar���� �Ϲ������� `.navbar-right` Ŭ������ �Բ� ����ϱ⿡�� �Ѱ谡 �ֽ��ϴ�. ���� ������ ������ �ֱ����� '.navbar-right'����� �������� margin�� ����մϴ�. ���� ��ҿ� �� Ŭ������ �Բ� ����ϰ��� �Ҷ� �ǵ��Ѵ�� margin�� �������� �ʽ��ϴ�.
�츮�� V4���� �ش� ���� ��Ҹ� �ٽ� �� ������ �� ��湮 �� ���Դϴ�.


----   

###[��� ���� (Fixed to top)](http://getbootstrap.com/components/#navbar-fixed-top)
`.navbar-fixed-top`�� �߰��ϰ� �� �ȿ� `.container`�� ` .container-fluid`���� navbar �������� ������ Ŭ������ �����մϴ�.

![component_navbar_07](../images/component_navbar_07.jpg)

```html

<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container">
    ...
  </div>
</nav>

```

** Body �� �е��� �ʿ��մϴ�.**    
` <body> `�� ��ܿ� padding �� ���� ������, �׺���̼� �ٴ� �ٸ� �������� ��������ϴ�. ��Ÿ��� ���� �õ��� ���ų� �ϴ��� ���� �̿��ϼ���.     
  ��: �⺻������, �׺���̼� �ٴ� 50px ���� Ů�ϴ�.  
```css

body { padding-top: 70px; }

```
�ݵ�� ��Ʈ��Ʈ�� CSS ���� **����**�� �־�� �մϴ�.

---    

###[�ϴ� ���� (Fixed to bottom)](http://getbootstrap.com/components/#navbar-fixed-bottom)
`..navbar-fixed-bottom`�� �߰��ϰ� �� �ȿ� `.container`�� ` .container-fluid`���� navbar �������� ������ Ŭ������ �����մϴ�.

![component_navbar_08](../images/component_navbar_08.jpg)

```html
<nav class="navbar navbar-default navbar-fixed-bottom">
  <div class="container">
    ...
  </div>
</nav>

```

** Body �� �е��� �ʿ��մϴ�.**    
` <body> `�� �ϼ���ܿ� padding �� ���� ������, �׺���̼� �ٴ� �ٸ� �������� ��������ϴ�. ��Ÿ��� ���� �õ��� ���ų� �ϴ��� ���� �̿��ϼ���.     
  ��: �⺻������, �׺���̼� �ٴ� 50px ���� Ů�ϴ�.  
```css

body { padding-bottom: 70px; }

```
�ݵ�� ��Ʈ��Ʈ�� CSS ���� **����**�� �־�� �մϴ�.


###[���� ���](http://getbootstrap.com/components/#navbar-static-top)
`.navbar-static-top` �� �߰��Ͽ� �������� ��ũ�� ���� �����ʺ��� navbar �� �����, `.container` �� `.container-fluid` �� �����ϼ���.
`.navbar-fixed-*` Ŭ�����ʹ� �ٸ���, ����� `body` �� �е��� �ٲ� �ʿ䰡 �����ϴ�.

![component_navbar_09](../images/component_navbar_09.jpg)

```html
<nav class="navbar navbar-default navbar-static-top">
  <div class="container">
    ...
  </div>
</nav>

```

###[������ �׺���̼� ��](http://getbootstrap.com/components/#navbar-inverted)
`.navbar-inverse `�� �߰��Ͽ� �׺���̼� ���� ����� �ٲ㺸����.

![component_navbar_10](../images/component_navbar_10.jpg)

```html
<nav class="navbar navbar-inverse">
  ...
</nav>

```

<br >
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#navbar)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - �׺���̼� [Navs](component_06_navs.md)
* ���������� - ����Ʈ �̵���� [Breadcrumbs](component_08_breadcrumbs.md)