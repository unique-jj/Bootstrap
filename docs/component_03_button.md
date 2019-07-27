## ��ư(Button)

�Ϸ��� ��ư���� ��ư �׷����� ���� ���ٿ� ��������. [��ư �÷�����](http://bootstrapk.com/javascript/#buttons) ���� ������ üũ�ڽ�ó�� ����� ���� �ֽ��ϴ�.

---

###����
��Ӵٿ��� Ʈ���ſ� ��Ӵٿ� �޴��� `.dropdown` ���� �ѷ��μ���, �ƴϸ� �ٸ� �±׿� position: relative; �� �����ϰ�, �޴� HTML �� �߰��ϼ���. ��Ӵٿ� �޴��� �θ� `.dropup` �� �߰��ϴ� ������ �ٲ�� ���� �����մϴ�.    

* ��ư �׷���� ���� & �˿��� Ư���� ������ �ʿ��մϴ�
> `.btn-group` ��ҿ� �����̳� �˿����� ����� ��, ����� ��ġ�ʴ� ���ۿ�(��Ұ� �о����ٰų� �𼭸��� �������ٰų�)�� ���ϱ� ���� �ɼ� `container: 'body'` �� ����ؾ� �� ���Դϴ�.

* ��Ȯ�� `role` �� �ο��ϰ� ���� �����ϼ���
> ���� ������ ���� �׷�ȭ�� �Ϸ��� ��ư���� �����ϱ� ���ؼ�, ������ `role` �Ӽ��� �����Ǿ����� �մϴ�. ��ư �׷��� ����, �̰��� `role="group"` �� �� �� �ֽ��ϴ�. ���ٴ� `role="toolbar"` �� ������ �մϴ�.
�Ѱ��� ���ܴ� �ϳ��� ��Ʈ�� �ۿ� ���� �׷��̳� ��Ӵٿ��Դϴ�. ���� ��� `<button>` ��ҿ� �Բ��ϴ� �������ĵ� ��ư �׷�
�Դ�, ��κ��� ���� ������ �ùٸ� `role` �Ӽ��� �����Կ��� �ұ��ϰ�, �׷�� ���ٴ� ��Ȯ�ϰ� ���� �־����� �մϴ�. ���⿡ ������ ��������, �츮�� `aria-label` �� ����߽��ϴٸ� `aria-labelledby `���� ��ȵ� ���� �� �ֽ��ϴ�.

---

###[�⺻ ����](http://getbootstrap.com/components/#btn-groups-single)
`.btn` �� �� �Ϸ��� ��ư���� `.btn-group` ���� ���μ���.

![component_button_01](../images/component_button_01.jpg)

```html

<div class="btn-group" role="group" aria-label="...">
  <button type="button" class="btn btn-default">Left</button>
  <button type="button" class="btn btn-default">Middle</button>
  <button type="button" class="btn btn-default">Right</button>
</div>

```
---   

###[��ư ����](http://getbootstrap.com/components/#btn-groups-toolbar)
�� �������� ������Ʈ�� ������� `<div class="btn-group">` ��Ʈ�� `<div class="btn-toolbar">` ���� ��ġ����.

![component_button_02](../images/component_button_02.jpg)

```html

<div class="btn-toolbar" role="toolbar" aria-label="...">
  <div class="btn-group" role="group" aria-label="...">...</div>
  <div class="btn-group" role="group" aria-label="...">...</div>
  <div class="btn-group" role="group" aria-label="...">...</div>
</div>
 
```
---   

###[ũ�� ����](http://getbootstrap.com/components/#btn-groups-sizing)
�׷� �� ��� ��ư�� ������ ũ������ Ŭ������ �����ϴ� ���, `.btn-group` �� `.btn-group-*` �� �߰��մϴ�.

![component_button_03](../images/component_button_03.jpg)

```html

<div class="btn-group btn-group-lg" role="group" aria-label="...">...</div>
<div class="btn-group" role="group" aria-label="...">...</div>
<div class="btn-group btn-group-sm" role="group" aria-label="...">...</div>
<div class="btn-group btn-group-xs" role="group" aria-label="...">...</div>
```
---   

###[��ø�ϱ�](http://getbootstrap.com/components/#btn-groups-nested)
�Ϸ��� ��ư�� ���� �ִ� ��Ӵٿ� �޴��� ���� ���� `.btn-group` �ȿ� �ٸ� `.btn-group` �� �����ø� �˴ϴ�.

![component_button_04](../images/component_button_04.jpg)

```html
<div class="btn-group" role="group" aria-label="...">
  <button type="button" class="btn btn-default">1</button>
  <button type="button" class="btn btn-default">2</button>

  <div class="btn-group" role="group">
    <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-expanded="false">
      Dropdown
      <span class="caret"></span>
    </button>
    <ul class="dropdown-menu" role="menu">
      <li><a href="#">Dropdown link</a></li>
      <li><a href="#">Dropdown link</a></li>
    </ul>
  </div>
</div>
```

---

###[������](http://getbootstrap.com/components/#btn-groups-vertical)
��ư �׷��� �������� ���� �������� ���Դϴ�. `�и��� ��ư ��Ӵٿ��� �������� �ʽ��ϴ�.`

![component_button_05](../images/component_button_05.jpg)

```html
<div class="btn-group-vertical" role="group" aria-label="...">
  ...
</div>
```

---

###[�������ĵ� ��ư �׷�](http://getbootstrap.com/components/#btn-groups-justified)
��ư �׷��� �װ��� �θ��� ���� �ʺ� ���� ���� ũ��� �ø��� �մϴ�. ���� ��ư �׷쳻�� ��Ӵٿ�� �۵��մϴ�.

* �𼭸� �ٷ��
> �������ĵ� ��ư�� ���� ���� Ư�� HTML �� CSS �� ���� (�����ڸ�, `display: table-cell`), �׵������ �𼭸��� �ι��Դϴ�. ���� ��ư �׷쿡����, �׵��� ���ֱ� ���� `margin-left: -1px` �� ���˴ϴ�. ������ margin �� `display: table-cell` �� ���� �۵����� �ʽ��ϴ�. ���������, ��Ʈ��Ʈ���� ����ȭ�Ͽ�, �𼭸��� �����ϰų� ���� �����ϴ� ���� ���� �� �ֽ��ϴ�.

* IE8 �� �𼭸�
> ���ͳ� �ͽ��÷η� 8 �� ���� ���ĵ� ��ư �׷��� ��ư�𼭸��� ������ ���� �ʽ��ϴ�. �װ��� `<a>` �̰ų� `<button>` ������ ����� �����ϴ�. �̰��� ��ȸ�Ϸ���, ��ư�� �Ǵٸ� `.btn-group` ���� ���μ���.
�� ���� ������ [#12476](https://github.com/twbs/bootstrap/issues/12476) �� ������.

#####[`<a> `���](http://getbootstrap.com/components/#with-a-elements)
`<a> `��ҿ� �׳� �Ϸ��� `.btn` ���� `.btn-group.btn-group-justified` ���� ���μ���.

![component_button_06](../images/component_button_06.jpg)

```html
<div class="btn-group btn-group-justified" role="group" aria-label="...">
  ...
</div>
```

* ��ư���μ��� ��ũ   
 > ���� `<a>` ��Ұ� ��ư���μ� ���ȴٸ�, �׵��� ������ `role="button"` �� �־����� �մϴ�.


#####[`<button>` ���](http://getbootstrap.com/components/#with-button-elements)

`<button> `��ҿ� �������ĵ� ��ư �׷��� ����ϱ� ����, **����� �� ��ư�� ��ư �׷����� ���ξ� �մϴ�.** ��κ��� ���������� `<button>` ��Ҹ� �����ϱ� ���� �츮�� CSS �� ������ �������� �ʽ��ϴٸ�, �츮�� ��ư ��Ӵٿ��� ������ ���ķ�, �츮�� �װ��� ��ȸ�Ͽ� �۵��� �� �ֽ��ϴ�.

![component_button_07](../images/component_button_07.jpg)

```html
<div class="btn-group btn-group-justified" role="group" aria-label="...">
  <div class="btn-group" role="group">
    <button type="button" class="btn btn-default">Left</button>
  </div>
  <div class="btn-group" role="group">
    <button type="button" class="btn btn-default">Middle</button>
  </div>
  <div class="btn-group" role="group">
    <button type="button" class="btn btn-default">Right</button>
  </div>
</div>
```




<br />
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#btn-groups)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - ��Ӵٿ� [Dropdowns](component_02_dropdowns.md)
* ���������� - ��ư ��Ӵٿ� [Button dropdowns](component_04_button_dropdown.md) 