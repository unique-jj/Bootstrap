## ���������̼�(Pagination)

��Ƽ������ ���������̼� ������Ʈ�� �� �� �ܼ��� ������ ���۳�Ʈ �� ����� ����Ʈ�� ���� ���� ���������̼� ��ũ�� �����մϴ�.

### [�⺻ ���������̼�(Default pagination)](http://getbootstrap.com/components/#pagination-default)
Rdio ���� ������ ���� �ܼ��� ���������̼�, �۰� �˻� ����� �����ϴ�. ū ����� ���� �� ���, ���� ũ�������� �ǰ�, ���� Ŭ�� ������ �����մϴ�.

![component_pagenation_01](../images/component_pagenation_01.jpg)

```html
<nav>
  <ul class="pagination">
    <li>
      <a href="#" aria-label="Previous">
        <span aria-hidden="true">&laquo;</span>
      </a>
    </li>
    <li><a href="#">1</a></li>
    <li><a href="#">2</a></li>
    <li><a href="#">3</a></li>
    <li><a href="#">4</a></li>
    <li><a href="#">5</a></li>
    <li>
      <a href="#" aria-label="Next">
        <span aria-hidden="true">&raquo;</span>
      </a>
    </li>
  </ul>
</nav>

```

#### ��Ȱ��ȭ�� �׸��� Ȱ������
��ũ�� �ٸ� ��Ȳ�� ���� ����ȭ �� �� �ֽ��ϴ�. Ŭ���Ҽ� ���� ��ũ�� ���� `.disabled` �� ����ϰ� ���� �������� ����ų ���� `.active` �� ����ϼ���.

![component_pagenation_02](../images/component_pagenation_02.jpg)

```html
<nav>
  <ul class="pagination">
    <li class="disabled"><a href="#" aria-label="Previous"><span aria-hidden="true">&laquo;</span></a></li>
    <li class="active"><a href="#">1 <span class="sr-only">(current)</span></a></li>
    ...
  </ul>
</nav>

```
����� ���������� �ǵ��� ��Ÿ���� �����ϸ鼭 Ŭ�� ��ɼ��� �����ϱ� ���� Ȱ��ȭ �Ǿ��ų� ��Ȱ��ȭ�� ��Ŀ �±׸� `<span>` �� ��ü�� �� �ֽ��ϴ�.

```html
<nav>
  <ul class="pagination">
    <li class="disabled">
      <span>
        <span aria-hidden="true">&laquo;</span>
      </span>
    </li>
    <li class="active">
      <span>1 <span class="sr-only">(current)</span></span>
    </li>
    ...
  </ul>
</nav>

```

#### ũ�� ����    

�� �� ũ�ų� ���� ���������̼��� ���ϼ���? `.pagination-lg` �� `.pagination-sm` �� �߰��Ͻø� �˴ϴ�.    

![component_pagenation_03](../images/component_pagenation_03.jpg)

```html
<nav><ul class="pagination pagination-lg">...</ul></nav>
<nav><ul class="pagination">...</ul></nav>
<nav><ul class="pagination pagination-sm">...</ul></nav>

```

### [������(Pager)](http://getbootstrap.com/components/#pagination-pager)
�������� ������ ��ũ���� ��Ÿ�Ϸ� �ܼ��� ���������̼� ������ ���� ���� ���� �̵� ��ũ�Դϴ�. ��α׳� �Ű��� ���� ������ ����Ʈ�� �����ϴ�. 

#### �⺻ ����(Default example)
�⺻������, �������� ��ũ�� ��� �����մϴ�.

![component_pagenation_04](../images/component_pagenation_04.jpg)

```html
<nav>
  <ul class="pager">
    <li><a href="#">Previous</a></li>
    <li><a href="#">Next</a></li>
  </ul>
</nav>

```

#### ���ĵ� ��ũ(Aligned links)
�׷��� ������, �� ��ũ�� ���� �𼭸��� ������ �� �ֽ��ϴ�:

![component_pagenation_05](../images/component_pagenation_05.jpg)

```html
<nav>
  <ul class="pager">
    <li class="previous"><a href="#"><span aria-hidden="true">&larr;</span> Older</a></li>
    <li class="next"><a href="#">Newer <span aria-hidden="true">&rarr;</span></a></li>
  </ul>
</nav>

```

#### ��Ȱ��ȭ ����
������ ��ũ�� ���� �Ϲ����� `.disabled` ���� Ŭ������ ����մϴ�.

![component_pagenation_06](../images/component_pagenation_06.jpg)

```html
<nav>
  <ul class="pager">
    <li class="previous disabled"><a href="#"><span aria-hidden="true">&larr;</span> Older</a></li>
    <li class="next"><a href="#">Newer <span aria-hidden="true">&rarr;</span></a></li>
  </ul>
</nav>

```

<br >
---

* [��������Ʈ �ٷΰ���](http://getbootstrap.com/components/#pagination)
* [��Ʈ��Ʈ�� ReadMe](../README.md)

---
* ���������� - ����Ʈ �̵���� [Breadcrumbs](component_08_breadcrumbs.md)
* ���������� - �� [Labels](component_10_labels.md)