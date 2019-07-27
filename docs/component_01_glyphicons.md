## ������ (Glyphicons)

### [��밡���� ��ȣ](http://getbootstrap.com/components/#glyphicons-glyphs)   
��Ʈ��Ʈ���� ���� ����� �������� �����մϴ�.
[Glyphicons](http://glyphicons.com/)Halflings ��Ʈ�� ��Ʈ ���信 250 ��ȣ �̻��� �����ϰ� �ֽ��ϴ�. 

---
![component_glyphicons](../images/component_glyphicons_01.jpg)
---
### [����](http://getbootstrap.com/components/#glyphicons-how-to-use)    

��� �������� �⺻Ŭ������ ������ Ŭ������ �ʿ�� �մϴ�. ����Ϸ���, ������ �ڵ带 ������ ���������� �˴ϴ�. ������ �е��� ���� �����ܰ� ���� ���̿� ������ ���ܵμ���.

* �ٸ� ������Ʈ�� ���� ������
> ������ Ŭ������ �ٸ� ������Ʈ�� ���� ���ϼ� �����ϴ�. �׵��� ���� ��ҿ� �ٸ� Ŭ������ �Բ� ������ ���� ���Դϴ�. ���, ��ø�� <span> �� �߰��ϰ� <span> �� ������ Ŭ������ �����ϼ���.

* ���ҿ��� ����ϼ���
> ������ Ŭ������ �ؽ�Ʈ�� �ڽ� ��Ұ� ���� ��ҿ��� ���Ǿ�� �մϴ�.

* ������ ��Ʈ ��ġ �����ϱ�
> ��Ʈ��Ʈ���� ������ ��Ʈ ������ �����ϵ� CSS ������ ������� `../fonts/` �� ���� ���̶�� �����մϴ�. �� ��Ʈ ������ �ű�ų� �̸��� �ٲٴ� ����� 3���� ����� �ϳ��� �Ͻø� �˴ϴ�.    
Less ���Ͽ��� `@icon-font-path` �� `@icon-font-name` ������ �����մϴ�.    
Less �����Ϸ����� �����Ǵ� `relative URLs �ɼ�` �� Ȱ���ϼ���.    
�����ϵ� CSS ���� `url() ��θ� ����`�ϼ���.    
����� ���� ������ �ִ��� ���� �ɼ��� ����ϼ���.

* ���ٰ����� ������
> ���� ������ ���� ������ �����ڵ带 �˸����Դϴ�. ��ũ���������� �ǵ�ġ �ʰ� ȥ�������� ����� ���ϱ� ����, �츮�� �׵��� `aria-hidden="true"` �Ӽ����� ����ϴ�.
���� ����� �ǹ̸� �����ϴ� �������� ����Ѵٸ�, `.sr-only` �� ����Ͽ�, �������п��� �ǹ̰� ���޵Ǿ�߸� �մϴ�.
���� ����� �ؽ�Ʈ ���� ��Ʈ��(�����ܸ� �ִ� `button` ó��)�� ����ٸ�, ����� �׻� ��Ʈ���� ������ �ĺ��� �� �ִ� ��ü �������� �����ؾ� �մϴ�. �� ���, ����� ��Ʈ�� ��ü�� aria-label �Ӽ��� �߰��ϼŵ� �˴ϴ�.

```html
<span class="glyphicon glyphicon-search" aria-hidden="true"></span>
```
---


### [����](http://getbootstrap.com/components/#glyphicons-examples)
���ٿ� �׺���̼��� ���� ��ư�� ��ư �׷쿡 �׵��� ����ϰų�, �� �Է¿�� �տ� �������ϴ�.

![component_glyphicons_ex](../images/component_glyphicons_02.jpg)

```html
<button type="button" class="btn btn-default" aria-label="Left Align">
  <span class="glyphicon glyphicon-align-left" aria-hidden="true"></span>
</button>

<button type="button" class="btn btn-default btn-lg">
  <span class="glyphicon glyphicon-star" aria-hidden="true"></span> Star
</button>
```
�������� �溸���� �װ��� �����޽������ ���� �����ϱ� ���� ���˴ϴ�. �׸��� �װ��� ���� ���� ����ڵ鿡�Ե� �˸��� ���� �߰����� `.sr-only `�ؽ�Ʈ�� �ʿ��մϴ�.
![component_glyphicons_ex](../images/component_glyphicons_03.jpg)

```html
<div class="alert alert-danger" role="alert">
  <span class="glyphicon glyphicon-exclamation-sign" aria-hidden="true"></span>
  <span class="sr-only">Error:</span>
  Enter a valid email address
</div>
```

<br />
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#glyphicons)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - ��Ӵٿ� [Dropdowns](component_02_dropdowns.md)