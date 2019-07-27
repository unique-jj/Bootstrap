## �׺���̼�
��Ʈ��Ʈ�� �� ��밡���� �׺���̼��� �⺻ `.nav` Ŭ������ �����ϴ� ��ũ���� ������ �Ӹ� �ƴ϶� ���� Ŭ������ �����մϴ�. �� ��Ÿ�Ϸ� ��ȯ�Ϸ��� ���� Ŭ������ ��ü�ϼ���.

* �� �г��� ���� �׺���̼��� ����ϴ� ���� �ڹٽ�ũ��Ʈ �� �÷������� �ʿ�� �մϴ�.
> ���Ҽ��ִ� ���������� ���� ����, ����� �� �ڹٽ�ũ��Ʈ �÷����� �� ����ؾ� �մϴ�. ��ũ���� ���� �߰����� `role` �� `ARIA` �Ӽ��� �ʿ��� ���Դϴ�. ���� �ڼ��� ���� �÷������� ��ũ�� ���� �� ������.

* ���ٰ����� �׺���̼����μ� �׺���̼�(navs) �� ����ϼ���
> ���� ����� �׺���̼� �ٸ� �����ϱ� ���� navs �� ����Ѵٸ�, `<ul>` �� �θ� �����̳ʿ� `role="navigation"` �� �߰��ϰų� `<nav> `���� ���ξ� �մϴ�. `<ul>` ��ü�� ����(role)�� �߰����� ������. �ֳ��ϸ� ���� ���п��� ���� ����� �������� ���� ���� �����Դϴ�.


----

###[����](http://getbootstrap.com/components/#nav-tabs)
`.nav-tabs` Ŭ������ `.nav` Ŭ������ �ʿ��� ���� ����ϼ���.

![component_nav_01](../images/component_nav_01.jpg)

```html

<ul class="nav nav-tabs">
  <li role="presentation" class="active"><a href="#">Home</a></li>
  <li role="presentation"><a href="#">Profile</a></li>
  <li role="presentation"><a href="#">Messages</a></li>
</ul>

```

--- 
###[�˾��� (Pills)](http://getbootstrap.com/components/#nav-pills)
���� HTML ������, .nav-pills �� ��� ����ϼ���.

![component_nav_02](../images/component_nav_02.jpg)

```html

<ul class="nav nav-pills">
  <li role="presentation" class="active"><a href="#">Home</a></li>
  <li role="presentation"><a href="#">Profile</a></li>
  <li role="presentation"><a href="#">Messages</a></li>
</ul>

```
�˾����� ���������� ���� ���� �ֽ��ϴ�. .nav-stacked �� �߰��ϼ���.
![component_nav_03](../images/component_nav_03.jpg)

```html

<ul class="nav nav-pills nav-stacked">
  ...
</ul>

```

--- 

###[���������� (Justified)](http://getbootstrap.com/components/#nav-justified)
`.nav-justified` �� �����̳� �˾����� �װ͵��� ���� �±׿� ���� �ʺ�� ���弼��. ���� ȭ�鿡����, �׺���̼� ��ũ�� ���̰� �˴ϴ�.
�������ĵ� `navbar nav` ��ũ�� ���� �������� �ʽ��ϴ�.

* ���ĸ��� ������ �������� navs
> v8.0 ���ķ�, ���ĸ��� �������ĵ� `nav` ���� ����� �������� ���������� ũ�⸦ �����Ҷ� ������ �������ϴ� ���׸� �������ϴ�. �� ���״� [�������ĵ� nav ����](http://bootstrapk.com/examples/justified-nav/) ���� �� �� �ֽ��ϴ�.

![component_nav_04](../images/component_nav_04.jpg)

```html

<ul class="nav nav-tabs">
  <li role="presentation" class="active"><a href="#">Home</a></li>
  <li role="presentation"><a href="#">Profile</a></li>
  <li role="presentation"><a href="#">Messages</a></li>
</ul>

```

--- 

###[��Ȱ��ȭ�� ��ũ](http://getbootstrap.com/components/#nav-disabled-links)
� �׺���̼� ������Ʈ(����, �˾���, �����)����, ȸ�� ��ũ�� ���� ȣ�� ȿ�� �� ���� `.disabled` �� �߰��ϼ���.

* ��ũ ��ɼ��� ������ ���� �ʽ��ϴ�.
> �� Ŭ������ �� ��ɼ��� �ƴ� ������� ��ȭ�ϵ��� �մϴ�. ��ũ�� ��Ȱ��ȭ�Ϸ��� ���� �ڹٽ�ũ��Ʈ�� ����ϼ���.

![component_nav_05](../images/component_nav_05.jpg)

```html

<ul class="nav nav-tabs">
  <li role="presentation" class="active"><a href="#">Home</a></li>
  <li role="presentation"><a href="#">Profile</a></li>
  <li role="presentation"><a href="#">Messages</a></li>
</ul>

```

--- 

###[��Ӵٿ� ����ϱ�](http://getbootstrap.com/components/#nav-dropdowns)
�ణ�� HTML �� [��Ӵٿ� �ڹٽ�ũ��Ʈ �÷�����](http://bootstrapk.com/javascript/#dropdowns) �� ��Ӵٿ� �޴��� �߰��ϼ���.

####���������� ��Ӵٿ�

![component_nav_06](../images/component_nav_06.jpg)

```html

<ul class="nav nav-tabs">
  ...
  <li role="presentation" class="dropdown">
    <a class="dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-expanded="false">
      Dropdown <span class="caret"></span>
    </a>
    <ul class="dropdown-menu" role="menu">
      ...
    </ul>
  </li>
  ...
</ul>

```
####�˾��������� ��Ӵٿ�

![component_nav_07](../images/component_nav_07.jpg)

```html

<ul class="nav nav-pills">
  ...
  <li role="presentation" class="dropdown">
    <a class="dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-expanded="false">
      Dropdown <span class="caret"></span>
    </a>
    <ul class="dropdown-menu" role="menu">
      ...
    </ul>
  </li>
  ...
</ul>

```
--- 



<br />
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#nav)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - �Է� �׷� [Input groups](component_05_input_groups.md)
* ���������� - �׺���̼� �� [Navbar](component_07_navbar.md)