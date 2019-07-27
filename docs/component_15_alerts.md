## Alerts (�溸)


**���� ���� ��밡���ϰ� ������ alert �޽����� �������� ����� �׼ǿ� ���� �ƶ����� �ǵ�� �޽����� �����մϴ�.**


### [����](http://getbootstrap.com/components/#alerts-examples)
�⺻ alert �޽����� ���� ���ڿ� �ɼ��� ���ֱ� ��ư�� `.alert` �� 4���� �ƶ����� Ŭ������ �� �ϳ��� ���μ���. (��: .alert-success)


* �⺻(default) Ŭ������ �����ϴ�
> alert�� �⺻ Ŭ������ ������ �ʽ��ϴ�, ���� �⺻�� ����Ŭ������ �����ϴ�. �⺻ ȸ�� alert�� �̻��մϴ�. �׷��� ����� �ƶ����� Ŭ������ �̿��Ͽ� Ÿ���� ����ؾ� �մϴ�. `success, info, warning, danger `�� �ϳ��� �����ϼ���.


![component_alert_01](../images/component_alert_01.jpg)

```html
<div class="alert alert-success" role="alert">...</div>
<div class="alert alert-info" role="alert">...</div>
<div class="alert alert-warning" role="alert">...</div>
<div class="alert alert-danger" role="alert">...</div>

```
----

### [���� �� �ִ� Alert](http://getbootstrap.com/components/#alerts-dismissible)

alert�� �ɼ��� `.alert-dismissible` �� ���ֱ� ��ư�� �߰��Ͽ� ����ϴ�.


* �ڹٽ�ũ��Ʈ alert �÷������� �ʿ��մϴ�

> ������ ���, ������ִ� alert�� ����, ����� [alert �÷�����](http://getbootstrap.com/javascript/#alerts) �� ����ؾ��մϴ�.


![component_thumbnails_02](../images/component_alert_02.jpg)

```html
<div class="alert alert-warning alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Warning!</strong> Better check yourself, you're not looking too good.
</div>

```

* ��� ��⿡�� ����� �۵��ϵ��� �մϴ�

> `<button>` �±׸� �ݵ�� `data-dismiss="alert"` �Ӽ��� �Բ� ����ؾ� �մϴ�.

### [alert �� ��ũ](http://getbootstrap.com/components/#alerts-links)

alert �� ������� ��ũ�� ������ �����ϴ� ����Ŭ���� `.alert-link` �� ����մϴ�.

![component_thumbnails_03](../images/component_alert_03.jpg)

```html
<div class="alert alert-success" role="alert">
  <a href="#" class="alert-link">...</a>
</div>
<div class="alert alert-info" role="alert">
  <a href="#" class="alert-link">...</a>
</div>
<div class="alert alert-warning" role="alert">
  <a href="#" class="alert-link">...</a>
</div>
<div class="alert alert-danger" role="alert">
  <a href="#" class="alert-link">...</a>
</div>
```

<br >
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#alerts)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - ����� [Thumbnails](component_14_thumbnails.md)
* ���������� - ���α׷����� [Progress bars](component_16_progress_bars.md)