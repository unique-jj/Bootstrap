## �Է� �׷� (Input Groups)

���� ����� `<input>` �� ��,�� Ȥ�� ���ʿ� ���ڳ� ��ư�� �߰��Ͽ� ����Ʈ���� Ȯ���ϼ���. `.form-control` �� ���̳� �ڿ� ÷�ε� `.input-group-addon` �� �Բ� `.input-group` �� ����մϴ�.

* ���� ����� `<input>` ��
> ���⿡ `<select>` ��Ҹ� ����ϴ� ���� ���ϼ���. �ֳ��ϸ� ��Ŷ ���������� ������ �������� �ʱ� �����Դϴ�.
���⿡ `<textarea>` ��Ҹ� ����ϴ� ���� ���ϼ���. �ֳ��ϸ� �׵��� rows �Ӽ��� ��� ��쿡 ������� �ʱ� �����Դϴ�.

* �Է� �׷���� ���� & �˿����� Ư���� ������ �ʿ��մϴ�
> `.input-group` ��ҿ� �����̳� �˿����� ����� ��, ����� ��ġ�ʴ� ���ۿ�(��Ұ� �о����ٰų� �𼭸��� �������ٰų�)�� ���ϱ� ���� �ɼ� `container: 'body'` �� ����ؾ� �� ���Դϴ�.

* �ٸ� ������Ʈ�� ���� ������
> �� �׷��̳� �׸��� �� Ŭ������ ���� ���� ������. ���, �� �׷��̳� �׸��� ���� ��� �ȿ� ��ø�ϼ���.

* �׻� ���� �߰��ϼ���
> ��ũ�� ������ ���� ��� �Է¿� ���� �������� �ʴ´ٸ� ����� ���� �־� ������ ����ų ���Դϴ�. �̷� �Է� �׷��� ����, ���� ���п��� �߰����� ���̳� ��ɼ��� �����ϴ� ���� Ȯ���� �ϵ��� �ϼ���.
���Ǿ��� �� �ִ� ��Ȯ�� ���(`.sr-only` Ŭ������ ����Ͽ� ������ `<label>` ��ҳ�, `aria-label`, `aria-labelledby`, `aria-describedby`, `title`, `placeholder` ��Ҹ� ���)�� �����ϴ� �ʿ��ϰ� �� �߰����� �������� ����� ����ϴ� �������̽� ������ ��Ȯ�� ������ ���� �޶��� ���Դϴ�. �� ������ ������ �� ���� ������ ������ �����մϴ�.
---

###[�⺻ ����](http://getbootstrap.com/components/#input-groups-basic)

�Է���Ʈ���� ���ʿ� �ֵ���̳� ��ư�� ��������. ����� ���� �ƴϸ� ���� �� ���� �� �ֽ��ϴ�.    

- **�츮�� ���ʸ鿡 �ټ��� �ֵ���� �������� �ʽ��ϴ�.**    
- **�츮�� �ϳ��� �Է� �׷쳻�� �ټ��� �� ��Ʈ���� �������� �ʽ��ϴ�.**    

![component_input_01](../images/component_input_01.jpg)

```html

<div class="input-group">
  <span class="input-group-addon" id="basic-addon1">@</span>
  <input type="text" class="form-control" placeholder="Username" aria-describedby="basic-addon1">
</div>

<div class="input-group">
  <input type="text" class="form-control" placeholder="Recipient's username" aria-describedby="basic-addon2">
  <span class="input-group-addon" id="basic-addon2">@example.com</span>
</div>

<div class="input-group">
  <span class="input-group-addon">$</span>
  <input type="text" class="form-control" aria-label="Amount (to the nearest dollar)">
  <span class="input-group-addon">.00</span>
</div>

```

--- 

###[ũ�� ����](http://getbootstrap.com/components/#input-groups-sizing)
`.input-group` �� ũ������ Ŭ������ �߰��ϼ���. ������ ��ҵ��� �ڵ����� ũ�������� �˴ϴ�.     
������ �±׿� ����Ʈ�� ũ�� Ŭ�������� �ݺ��� �ʿ䰡 �����ϴ�.

![component_input_02](../images/component_input_02.jpg)

```html
<div class="input-group input-group-lg">
  <span class="input-group-addon" id="sizing-addon1">@</span>
  <input type="text" class="form-control" placeholder="Username" aria-describedby="sizing-addon1">
</div>

<div class="input-group">
  <span class="input-group-addon" id="sizing-addon2">@</span>
  <input type="text" class="form-control" placeholder="Username" aria-describedby="sizing-addon2">
</div>

<div class="input-group input-group-sm">
  <span class="input-group-addon" id="sizing-addon3">@</span>
  <input type="text" class="form-control" placeholder="Username" aria-describedby="sizing-addon3">
</div>
```
--- 

###[üũ�ڽ��� ���� �����](http://getbootstrap.com/components/#input-groups-checkboxes-radios)
�Է±׷� �� ����¿� ���� ��� üũ�ڽ��� ������ �μ���.

![component_input_03](../images/component_input_03.jpg)

```html
<div class="row">
  <div class="col-lg-6">
    <div class="input-group">
      <span class="input-group-addon">
        <input type="checkbox" aria-label="...">
      </span>
      <input type="text" class="form-control" aria-label="...">
    </div><!-- /input-group -->
  </div><!-- /.col-lg-6 -->
  <div class="col-lg-6">
    <div class="input-group">
      <span class="input-group-addon">
        <input type="radio" aria-label="...">
      </span>
      <input type="text" class="form-control" aria-label="...">
    </div><!-- /input-group -->
  </div><!-- /.col-lg-6 -->
</div><!-- /.row -->
```

--- 

###[��ư �����](http://getbootstrap.com/components/#input-groups-buttons)
�Է±׷� �� ��ư�� ������ �ణ �ٸ� ��ø �±׸� �ʿ�� �մϴ�. `.input-group-addon` ��� `.input-group-btn` ���� ��ư�� ���Դϴ�. �̰��� �������̵� �� �� ���� �⺻ ������ ��Ÿ�ϵ�� ���� �ʿ��մϴ�.

![component_input_04](../images/component_input_04.jpg)

```html
<div class="row">
  <div class="col-lg-6">
    <div class="input-group">
      <span class="input-group-btn">
        <button class="btn btn-default" type="button">Go!</button>
      </span>
      <input type="text" class="form-control" placeholder="Search for...">
    </div><!-- /input-group -->
  </div><!-- /.col-lg-6 -->
  <div class="col-lg-6">
    <div class="input-group">
      <input type="text" class="form-control" placeholder="Search for...">
      <span class="input-group-btn">
        <button class="btn btn-default" type="button">Go!</button>
      </span>
    </div><!-- /input-group -->
  </div><!-- /.col-lg-6 -->
</div><!-- /.row -->
```
--- 

###[��Ӵٿ� ��ư](http://getbootstrap.com/components/#input-groups-buttons-dropdowns)

![component_input_05](../images/component_input_05.jpg)

```html
<div class="row">
  <div class="col-lg-6">
    <div class="input-group">
      <div class="input-group-btn">
        <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-expanded="false">Action <span class="caret"></span></button>
        <ul class="dropdown-menu" role="menu">
          <li><a href="#">Action</a></li>
          <li><a href="#">Another action</a></li>
          <li><a href="#">Something else here</a></li>
          <li class="divider"></li>
          <li><a href="#">Separated link</a></li>
        </ul>
      </div><!-- /btn-group -->
      <input type="text" class="form-control" aria-label="...">
    </div><!-- /input-group -->
  </div><!-- /.col-lg-6 -->
  <div class="col-lg-6">
    <div class="input-group">
      <input type="text" class="form-control" aria-label="...">
      <div class="input-group-btn">
        <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-expanded="false">Action <span class="caret"></span></button>
        <ul class="dropdown-menu dropdown-menu-right" role="menu">
          <li><a href="#">Action</a></li>
          <li><a href="#">Another action</a></li>
          <li><a href="#">Something else here</a></li>
          <li class="divider"></li>
          <li><a href="#">Separated link</a></li>
        </ul>
      </div><!-- /btn-group -->
    </div><!-- /input-group -->
  </div><!-- /.col-lg-6 -->
</div><!-- /.row -->
```

---

###[���ҵ� ��ư](http://getbootstrap.com/components/#input-groups-buttons-segmented)

![component_input_06](../images/component_input_06.jpg)

```html
<div class="input-group">
  <div class="input-group-btn">
    <!-- Button and dropdown menu -->
  </div>
  <input type="text" class="form-control" aria-label="...">
</div>

<div class="input-group">
  <input type="text" class="form-control" aria-label="...">
  <div class="input-group-btn">
    <!-- Button and dropdown menu -->
  </div>
</div>
```

---

###[�������� ��ư](http://getbootstrap.com/components/#input-groups-buttons-multiple)

![component_input_07](../images/component_input_07.jpg)

```html
<div class="input-group">
  <div class="input-group-btn">
    <!-- Buttons -->
  </div>
  <input type="text" class="form-control" aria-label="...">
</div>

<div class="input-group">
  <input type="text" class="form-control" aria-label="...">
  <div class="input-group-btn">
    <!-- Buttons -->
  </div>
</div>
```

<br />
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#input-groups)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - ��ư ��Ӵٿ� [Button dropdowns](component_04_button_dropdown.md) 
* ���������� - �׺���̼� [Navs](component_06_navs.md)