## �г�(Panel)

�ڽ� �ȿ� DOM�� �ְ� ���� �� �г��� ����մϴ�.

---

#### [�⺻ �г�](http://getbootstrap.com/components/#panels-basic)

- �⺻������ �е��� �׵θ��� �� ����.
- �⺻Ŭ������ `.panel.panel-default`
- �г� ������ `.panel-body`�� ���μ� ���

![��ũ����](../images/bootstrap-cp-panel-01.png)

```html
<div class="panel panel-default">
  <div class="panel-body">
    Basic panel example
  </div>
</div>
```

---

#### [���/Ÿ��Ʋ�� �ִ� �г�](http://getbootstrap.com/components/#panels-heading)

- �г� ���ο� `.panel-heading` �׸��� �߰��� �� ����.
- `.panel-heading` ���ο� `<h1> ~ <h6>` �±׸� �̿��Ͽ� Ÿ��Ʋ �߰��� ������.
- `<h1> ~ <h6>` �� `.panel-title` Ŭ������ �߰��Ѵ�.

![��ũ����](../images/bootstrap-cp-panel-02.png)

```html
<div class="panel panel-default">
  <div class="panel-heading">Panel heading without title</div>
  <div class="panel-body">
    Panel content
  </div>
</div>

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Panel title</h3>
  </div>
  <div class="panel-body">
    Panel content
  </div>
</div>
```

---

#### [�ϴ�(Ǫ��)�� �ִ� �г�](http://getbootstrap.com/components/#panels-footer)

- �ϴܿ� ��ư�̳� �ΰ����� �ؽ�Ʈ�� �߰��� �� ����.
- �г� ���ο� `.panel-footer` �� �߰�.
- �ƶ����� Ŭ����(����)�� ������ ���� ����.

![��ũ����](../images/bootstrap-cp-panel-03.png)

```html
<div class="panel panel-default">
  <div class="panel-body">
    Panel content
  </div>
  <div class="panel-footer">Panel footer</div>
</div>
```

---

#### [�ƶ����� Ŭ����(����/��Ÿ��)](http://getbootstrap.com/components/#panels-alternatives)

- �� �׸� �ǹ̿� ���� �⺻ ������ �����Ǿ� �ִ�.
- �ټ����� ������ ����.

![��ũ����](../images/bootstrap-cp-panel-04.png)

1. �Ķ� : `.panel-primary`
2. �ʷ� : `.panel-success`
3. �ϴ� : `.panel-info`
4. ��� : `.panel-warning`
5. ���� : `.panel-danger`

```html
<div class="panel panel-primary">...</div>
<div class="panel panel-success">...</div>
<div class="panel panel-info">...</div>
<div class="panel panel-warning">...</div>
<div class="panel panel-danger">...</div>
```

---

#### [���̺�� �Բ� ���](http://getbootstrap.com/components/#panels-tables)

- �г� ���ο� ���̺��� �߰��� �� ����.
- �ΰ��� ���
   - `.panel-body`�� �ִ� ��� : ������ ���̺� ���̿� ���м��� ��
   - `.panel-body`�� ���� ���

* `.panel-body`�� �ִ� ���

![��ũ����](../images/bootstrap-cp-panel-05.png)

```html
<div class="panel panel-default">
  <!-- Default panel contents -->
  <div class="panel-heading">Panel heading</div>
  <div class="panel-body">
    <p>...</p>
  </div>

  <!-- Table -->
  <table class="table">
    ...
  </table>
</div>
```

* `.panel-body`�� ���� ���

![��ũ����](../images/bootstrap-cp-panel-06.png)

```html
<div class="panel panel-default">
  <!-- Default panel contents -->
  <div class="panel-heading">Panel heading</div>
  <div class="panel-body">
    <p>...</p>
  </div>

  <!-- Table -->
  <table class="table">
    ...
  </table>
</div>
```


#### [list �׷�� �Բ� ���](http://getbootstrap.com/components/#panels-list-group)
- �г� ���ο� ���� �ʺ��� [list group](component_18_list_group.md)�� �߰��� �� ����.

![��ũ����](../images/bootstrap-cp-panel-07.png)

```html
<div class="panel panel-default">
  <!-- Default panel contents -->
  <div class="panel-heading">Panel heading</div>
  <div class="panel-body">
    <p>...</p>
  </div>

  <!-- List group -->
  <ul class="list-group">
    <li class="list-group-item">Cras justo odio</li>
    <li class="list-group-item">Dapibus ac facilisis in</li>
    <li class="list-group-item">Morbi leo risus</li>
    <li class="list-group-item">Porta ac consectetur ac</li>
    <li class="list-group-item">Vestibulum at eros</li>
  </ul>
</div>
```


<br >
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#panels)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - ��� �׷� [List group](component_18_list_group.md) 
* ���������� - ������ �Ӻ��� [Responsive embed](component_20_responsive_embed.md)
