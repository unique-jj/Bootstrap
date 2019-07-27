## ��ư ��Ӵٿ�(Button Dropdown)

��Ӵٿ� �޴��� �۵��Ǵ� ��ư�� ����Ϸ��� `.btn-group` �ȿ� �װ͵��� �ΰ� ������ �޴� ��ũ���� ���ݴϴ�.

*�÷����� ������
> ��ư ��Ӵٿ��� ��Ʈ��Ʈ���� ���Ե� ��Ӵٿ� �÷����� �� �ʿ�� �մϴ�.

---

###�ܹ�ư ��Ӵٿ�

��� �⺻ ��ũ���� �����Ͽ� ��ư�� ��Ӵٿ� ��۷� �ٲټ���.

![component_button_dropdown_01](../images/component_button_dropdown_01.jpg)

```html

<!-- Single button -->
<div class="btn-group">
  <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-expanded="false">
    Action <span class="caret"></span>
  </button>
  <ul class="dropdown-menu" role="menu">
    <li><a href="#">Action</a></li>
    <li><a href="#">Another action</a></li>
    <li><a href="#">Something else here</a></li>
    <li class="divider"></li>
    <li><a href="#">Separated link</a></li>
  </ul>
</div>

```

--- 

###[���ҵ� ��ư ��Ӵٿ�](http://getbootstrap.com/components/#dropdowns)
�Ȱ��� ��ũ����, �и��� ��ư�� �߰��Ͽ� ���ҵ� ��ư ��Ӵٿ��� ���弼��.

![component_button_dropdown_02](../images/component_button_dropdown_02.jpg)

```html

<!-- Split button -->
<div class="btn-group">
  <button type="button" class="btn btn-danger">Action</button>
  <button type="button" class="btn btn-danger dropdown-toggle" data-toggle="dropdown" aria-expanded="false">
    <span class="caret"></span>
    <span class="sr-only">Toggle Dropdown</span>
  </button>
  <ul class="dropdown-menu" role="menu">
    <li><a href="#">Action</a></li>
    <li><a href="#">Another action</a></li>
    <li><a href="#">Something else here</a></li>
    <li class="divider"></li>
    <li><a href="#">Separated link</a></li>
  </ul>
</div>

```

--- 

###[ũ������](http://getbootstrap.com/components/#btn-dropdowns-sizing)
��ư ��Ӵٿ��� ��� ũ���� ��ư���� �����մϴ�.

![component_button_dropdown_03](../images/component_button_dropdown_03.jpg)

```html

<!-- Large button group -->
<div class="btn-group">
  <button class="btn btn-default btn-lg dropdown-toggle" type="button" data-toggle="dropdown" aria-expanded="false">
    Large button <span class="caret"></span>
  </button>
  <ul class="dropdown-menu" role="menu">
    ...
  </ul>
</div>

<!-- Small button group -->
<div class="btn-group">
  <button class="btn btn-default btn-sm dropdown-toggle" type="button" data-toggle="dropdown" aria-expanded="false">
    Small button <span class="caret"></span>
  </button>
  <ul class="dropdown-menu" role="menu">
    ...
  </ul>
</div>

<!-- Extra small button group -->
<div class="btn-group">
  <button class="btn btn-default btn-xs dropdown-toggle" type="button" data-toggle="dropdown" aria-expanded="false">
    Extra small button <span class="caret"></span>
  </button>
  <ul class="dropdown-menu" role="menu">
    ...
  </ul>
</div>

```

--- 

###[��Ӿ���](http://getbootstrap.com/components/#btn-dropdowns-dropup)
�����±׿� `.dropup` �� ���Ͽ� ��Ӵٿ� �޴��� ��� ���� �ö󰡵��� �۵���Ű����.

![component_button_dropdown_04](../images/component_button_dropdown_04.jpg)

```html

<div class="btn-group dropup">
  <button type="button" class="btn btn-default">Dropup</button>
  <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-expanded="false">
    <span class="caret"></span>
    <span class="sr-only">Toggle Dropdown</span>
  </button>
  <ul class="dropdown-menu" role="menu">
    <!-- Dropdown menu links -->
  </ul>
</div>

```



<br />
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#btn-dropdowns)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - ��ư �׷� [Button groups](component_03_button.md)
* ���������� - �Է� �׷� [Input groups](component_05_input_groups.md)