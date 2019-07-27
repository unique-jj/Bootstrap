## ��Ӵٿ�

��ũ���� ����� �����ֱ� ���� ����� ������ ���ؽ�Ʈ �޴�. ��Ӵٿ� [�ڹٽ�ũ��Ʈ �÷�����](http://bootstrapk.com/javascript/#dropdowns) ���� ��ȣ�ۿ��ϵ��� ���弼��.

---

###[����](http://getbootstrap.com/components/#dropdowns-example)
��Ӵٿ��� Ʈ���ſ� ��Ӵٿ� �޴��� `.dropdown` ���� �ѷ��μ���, �ƴϸ� �ٸ� �±׿� position: relative; �� �����ϰ�, �޴� HTML �� �߰��ϼ���. ��Ӵٿ� �޴��� �θ� `.dropup` �� �߰��ϴ� ������ �ٲ�� ���� �����մϴ�.    

![component_glyphicons_ex](../images/component_dropdown_01.jpg)

```html

<div class="dropdown">
  <button class="btn btn-default dropdown-toggle" type="button" id="dropdownMenu1" data-toggle="dropdown" aria-expanded="true">
    Dropdown
    <span class="caret"></span>
  </button>
  <ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenu1">
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Action</a></li>
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Another action</a></li>
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Something else here</a></li>
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Separated link</a></li>
  </ul>
</div>
<div class="dropup">
  <button class="btn btn-default dropdown-toggle" type="button" id="dropdownMenu2" data-toggle="dropdown" aria-expanded="true">
    Dropdown
    <span class="caret"></span>
  </button>
  <ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenu2">
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Action</a></li>
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Another action</a></li>
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Something else here</a></li>
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Separated link</a></li>
  </ul>
</div>

```
---

###[����](http://getbootstrap.com/components/#dropdowns-alignment)
�⺻������, ��Ӵٿ� �޴��� �ڵ������� �»�ܿ� ��ġ�մϴ�. ���� �����Ϸ��� .dropdown-menu �� `.dropdown-menu-right` �� �߰��ϼ���.

* �߰������� ��ġ�� ��� ���� �ʿ��� �� �ֽ��ϴ�
> ��Ӵٿ��� �ڵ������� CSS �� ���� ������ �⺻ �帧���� ��ġ�� ����ϴ�. �̰��� ��Ӵٿ��� �θ��� overflow �̳� ����Ʈ�� �ٱ������� ���� ũ��(crop)�� �� ������ �ǹ��մϴ�. �̷� �̽��� �߻��ϸ� ������ �ذ��ؾ��մϴ�

* ���������� .pull-right ����    
>v3.1.0 ���ķ�, �츮�� ��Ӵٿ� �޴��� `.pull-right` �� ������������ �Ͽ����ϴ�. �޴��� ���������Ϸ���, `.dropdown-menu-right` �� ����ϼ���. �׺���̼ǹٿ��� �������ĵ� �׺���̼� ������Ʈ�� �޴��� �ڵ������� �����ϱ� ���� �� Ŭ������ �ͽ��� ������ ����մϴ�. �װ��� �������̵��ϱ� ����, `.dropdown-menu-left` �� ����ϼ���.
```html

<ul class="dropdown-menu dropdown-menu-right" role="menu" aria-labelledby="dLabel">
  ...
</ul>

```
---   

###[����(Headers)](http://getbootstrap.com/components/#dropdowns-headers)
��Ӵٿ� �޴��� �׼� �׷쿡 ���� ���̷��� ����� �߰��ϼ���.

![component_glyphicons_ex](../images/component_dropdown_02.jpg)

```html

<ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenu3">
  ...
  <li role="presentation" class="dropdown-header">Dropdown header</li>
  ...
</ul>

```
---   

###[���м�(Divider)](http://getbootstrap.com/components/#dropdowns-divider)

��Ӵٿ� �޴��� �Ϸ��� ��ũ�� �����ϱ� ���� ���м��� �߰��ϼ���.

![component_glyphicons_ex](../images/component_dropdown_03.jpg)

```html

<ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenuDivider">
  ...
  <li role="presentation" class="divider"></li>
  ...
</ul>
```
---   

###[��Ȱ��ȭ�� �޴� �׸�](http://getbootstrap.com/components/#dropdowns-disabled)
��ũ�� ��Ȱ��ȭ �Ϸ��� ��Ӵٿ��� `<li>` �� `.disabled` �� �߰��ϼ���.

![component_glyphicons_ex](../images/component_dropdown_04.jpg)

```html

<ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenu4">
  <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Regular link</a></li>
  <li role="presentation" class="disabled"><a role="menuitem" tabindex="-1" href="#">Disabled link</a></li>
  <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Another link</a></li>
</ul>
```

<br />
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#dropdowns)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - ������ [Glyphicons](component_01_glyphicons.md)
* ���������� - ��ư �׷� [Button groups](component_03_button.md)