## �����(Progress bars)

�۾��帧�̳� �׼��� ���࿡�� �����ϰ� ������ ����ٷ� �ֽ� �ǵ���� �����մϴ�.

* ũ�ν������� ȣȯ��
> ����ٴ� ��� ȿ���� ���� CSS3 �� Ʈ�����ǰ� �ִϸ��̼��� ����մϴ�. �� ��ɵ��� IE9 ���Ͽ����� ���̾������� ���������� �������� �ʽ��ϴ�. ����� 12 �� �ִϸ��̼��� �������� �ʽ��ϴ�.

### [�⺻ ����](http://getbootstrap.com/components/#progress-basic)
�⺻ �����

![component_progressbar_01](../images/component_progressbar_01.jpg)

```html
<div class="progress">
  <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
    <span class="sr-only">60% Complete</span>
  </div>
</div>
```
---

### [�󺧰� �Բ�](http://getbootstrap.com/components/#progress-label)
�������� �������� ����ٳ��� `.sr-only` Ŭ������ �ִ� `<span>` �� �����ϼ���.

![component_progressbar_02](../images/component_progressbar_02.jpg)

```html
<div class="progress">
  <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
    60%
  </div>
</div>
```

���� ������������ �� �ؽ�Ʈ�� ���� �� �ְ� �ϱ� ����, ����ٿ� min-width �� �߰��ϴ� ���� ����غ�����.

![component_progressbar_03](../images/component_progressbar_03.jpg)

```html
<div class="progress">
  <div class="progress-bar" role="progressbar" aria-valuenow="0" aria-valuemin="0" aria-valuemax="100" style="min-width: 2em;">
    0%
  </div>
</div>
<div class="progress">
  <div class="progress-bar" role="progressbar" aria-valuenow="2" aria-valuemin="0" aria-valuemax="100" style="min-width: 2em; width: 2%;">
    2%
  </div>
</div>
```
---

### [�ƶ����� ���](http://getbootstrap.com/components/#progress-alternatives)
����ٴ� �ϰ��� ��Ÿ���� ���� ��ư�� �溸 Ŭ������ ���� �͵��� ����մϴ�.

![component_progressbar_04](../images/component_progressbar_04.jpg)

```html
<div class="progress">
  <div class="progress-bar progress-bar-success" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%">
    <span class="sr-only">40% Complete (success)</span>
  </div>
</div>
<div class="progress">
  <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="20" aria-valuemin="0" aria-valuemax="100" style="width: 20%">
    <span class="sr-only">20% Complete</span>
  </div>
</div>
<div class="progress">
  <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%">
    <span class="sr-only">60% Complete (warning)</span>
  </div>
</div>
<div class="progress">
  <div class="progress-bar progress-bar-danger" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 80%">
    <span class="sr-only">80% Complete (danger)</span>
  </div>
</div>
```
---

### [�ٹ���(Striped)](http://getbootstrap.com/components/#progress-striped)
�׶���Ʈ�� �̿��� �ٹ��� ȿ���� ����ϴ�. IE8 ������ �۵����� �ʽ��ϴ�.

![component_progressbar_05](../images/component_progressbar_05.jpg)

```html
<div class="progress">
  <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%">
    <span class="sr-only">40% Complete (success)</span>
  </div>
</div>
<div class="progress">
  <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="20" aria-valuemin="0" aria-valuemax="100" style="width: 20%">
    <span class="sr-only">20% Complete</span>
  </div>
</div>
<div class="progress">
  <div class="progress-bar progress-bar-warning progress-bar-striped" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%">
    <span class="sr-only">60% Complete (warning)</span>
  </div>
</div>
<div class="progress">
  <div class="progress-bar progress-bar-danger progress-bar-striped" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 80%">
    <span class="sr-only">80% Complete (danger)</span>
  </div>
</div>
```
---

### [�����̴�(Animated)](http://getbootstrap.com/components/#progress-animated)
����ٸ� �����ʿ��� �������� �����̴� �ٹ��� ȿ���� �ַ��� .active �� .progress-striped �� �߰��ϼ���. IE �� ��� �������� �۵����� �ʽ��ϴ�.

![component_progressbar_06](../images/component_progressbar_06.jpg)

```html
<div class="progress">
  <div class="progress-bar progress-bar-striped active" role="progressbar" aria-valuenow="45" aria-valuemin="0" aria-valuemax="100" style="width: 45%">
    <span class="sr-only">45% Complete</span>
  </div>
</div>
```

---

### [�״�(Stacked)](http://getbootstrap.com/components/#progress-stacked)
���� ����ٸ� �������� ���� .progress �ȿ� ���� ���� ����ٸ� �Ӵϴ�.

![component_progressbar_07](../images/component_progressbar_07.jpg)

```html
<div class="progress">
  <div class="progress-bar progress-bar-success" style="width: 35%">
    <span class="sr-only">35% Complete (success)</span>
  </div>
  <div class="progress-bar progress-bar-warning progress-bar-striped" style="width: 20%">
    <span class="sr-only">20% Complete (warning)</span>
  </div>
  <div class="progress-bar progress-bar-danger" style="width: 10%">
    <span class="sr-only">10% Complete (danger)</span>
  </div>
</div>
```

<br >
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#progress)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - �溸 [Alerts](component_15_alerts.md)
* ���������� - �̵�� ��ü [Media object](component_17_media_object.md)