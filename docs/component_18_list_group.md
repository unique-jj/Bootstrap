## List �׷�(List Group)

������ list �Ӹ� �ƴ϶� ������ ���뵵 ����ȭ �Ͽ� ������ �� �ִ� ������ ������Ʈ

----

### [�⺻����](http://getbootstrap.com/components/#list-group-basic)

![��ũ����](../images/bootstrap-cp-list-01.png)

```html
<ul class="list-group">
  <li class="list-group-item">Cras justo odio</li>
  <li class="list-group-item">Dapibus ac facilisis in</li>
  <li class="list-group-item">Morbi leo risus</li>
  <li class="list-group-item">Porta ac consectetur ac</li>
  <li class="list-group-item">Vestibulum at eros</li>
</ul>
```

---

### [����](http://getbootstrap.com/components/#list-group-badges)

list �׸�(item)�� ������ �߰��ϸ� �����ʿ� �ڵ� ��ġ

![��ũ����](../images/bootstrap-cp-list-02.png)

```html
<ul class="list-group">
  <li class="list-group-item">
    <span class="badge">14</span>
    Cras justo odio
  </li>
</ul>
```

---

### [��ũ�׸�](http://getbootstrap.com/components/#list-group-linked)

��ũ�׸��� `<ul>` ��� `<div>` �� `<a>`�� ���. (class�� �⺻������ ����)

1. �������� ��ũ�׸� : `.list-group-item.active`
2. ��Ȱ�� ��ũ�׸� : `.list-group-item.disabled`


* �������� ��ũ�׸� ǥ��

![��ũ����](../images/bootstrap-cp-list-03.png)

* ��Ȱ�� ��ũ�׸�

![��ũ����](../images/bootstrap-cp-list-04.png)


```html
<div class="list-group">
  <a href="#" class="list-group-item active">
    Cras justo odio
  </a>
  <a href="#" class="list-group-item disable">
  	Dapibus ac facilisis in
  </a>
  <a href="#" class="list-group-item">Morbi leo risus</a>
  <a href="#" class="list-group-item">Porta ac consectetur ac</a>
  <a href="#" class="list-group-item">Vestibulum at eros</a>
</div>
```

---

### [��ư Ŭ����](http://getbootstrap.com/components/#list-group-buttons)

- ������ ��ư�� ����Ʈ �׷�ó�� ǥ��ȴ�. 
- ǥ�� .btn Ŭ������ ������� ����. 


![��ũ����](../images/bootstrap-cp-list-01.png)
```html
<div class="list-group">
  <button type="button" class="list-group-item">Cras justo odio</button>
  <button type="button" class="list-group-item">Dapibus ac facilisis in</button>
  <button type="button" class="list-group-item">Morbi leo risus</button>
  <button type="button" class="list-group-item">Porta ac consectetur ac</button>
  <button type="button" class="list-group-item">Vestibulum at eros</button>
</div>
```

---

### [�ƶ����� Ŭ����(����/��Ÿ��)](http://getbootstrap.com/components/#list-group-contextual-classes)

- �� �׸� �ǹ̿� ���� �⺻ ������ �����Ǿ� �ִ�.
- `list-group-item`�� Ŭ������ �߰��Ͽ� ���
- ��ũ �׸񿡵� �����ϰ� ����


1. �ʷ� : `.list-group-item-success`
2. �Ķ� : `.list-group-item-info`
3. ��� : `.list-group-item-warning`
4. ���� : `.list-group-item-danger`

![��ũ����](../images/bootstrap-cp-list-05.png)

```html
<ul class="list-group">
  <li class="list-group-item list-group-item-success">Dapibus ac facilisis in</li>
  <li class="list-group-item list-group-item-info">Cras sit amet nibh libero</li>
  <li class="list-group-item list-group-item-warning">Porta ac consectetur ac</li>
  <li class="list-group-item list-group-item-danger">Vestibulum at eros</li>
</ul>
<div class="list-group">
  <a href="#" class="list-group-item list-group-item-success">Dapibus ac facilisis in</a>
  <a href="#" class="list-group-item list-group-item-info">Cras sit amet nibh libero</a>
  <a href="#" class="list-group-item list-group-item-warning">Porta ac consectetur ac</a>
  <a href="#" class="list-group-item list-group-item-danger">Vestibulum at eros</a>
</div>
```

---

### [�������� �ִ� �׸�](http://getbootstrap.com/components/#list-group-custom-content)
- �׸� �������� �߰��ϴ� ���� ������.

![��ũ����](../images/bootstrap-cp-list-06.png)

```html
<div class="list-group">
  <a href="#" class="list-group-item active">
    <h4 class="list-group-item-heading">List group item heading</h4>
    <p class="list-group-item-text">...</p>
  </a>
</div>
```

---

<br >
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#list-group)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - �̵�� ��ü [Media object](component_17_media_object.md)
* ���������� - �г� [Panels](component_19_panelmark.md) 

