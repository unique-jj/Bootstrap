# Table


### �⺻ ����

`<table>`�� �ణ�� �е��� ���� ���� ���� �ֱ� ���ؼ� ���� �⺻ ��Ÿ���� `.table`�� ����� �� �ֽ��ϴ�.

[����](http://codepen.io/luensys/pen/NxNLXO)
```html
<table class="table">
  <thead>
    <tr>
      <th>#</th>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Username</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope=row>1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope=row>2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope=row>3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
```

### �ٹ��� ��

�ٺδ̸� �߰��ϱ� ���ؼ���(�� �ະ�� �����ϱ� ����) `<tbody`�� `.table-striped`�� �߰��ϼ���.
```
����! CSS�� :nth-child �Ӽ����� ��������� ������ IE8������ �������� �ʽ��ϴ�.
```

[����](http://codepen.io/luensys/pen/wMGEyx)
```html
<table class="table table-striped">
  <thead>
    <tr>
      <th>#</th>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Username</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope=row>1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope=row>2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope=row>3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
```

### ���� �ִ� ���̺�

���̺��� �׵θ��� ���� ���� �ֱ� ���ؼ� `.table-bordered`�� �߰��ϼ���.

[����](http://codepen.io/luensys/pen/obxPdZ)
```html
<table class="table table-bordered">
  <thead>
    <tr>
      <th>#</th>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Username</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope=row>1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope=row>2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope=row>3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
```

### Hover ��

`<tbody>` ���� ���̺� ����� Hover ���¸� Ȱ��ȭ�Ϸ��� `.table-hover`�� �߰����ּ���.

[����](http://codepen.io/luensys/pen/bEpxMm)
```html
<table class="table table-hover">
  <thead>
    <tr>
      <th>#</th>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Username</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope=row>1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope=row>2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope=row>3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
```

### ���� �� ���̺�

�� �е��� ������ �ٿ��� �� �� ����Ʈ �ϰ� ���̺��� ����� ���ؼ��� `.table-condensed`�� �߰��ϼ���.

[����](http://codepen.io/luensys/pen/vLGzre)
```html
<table class="table table-condensed">
  <thead>
    <tr>
      <th>#</th>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Username</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope=row>1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope=row>2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope=row>3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
```

### �ƶ����� Ŭ������

���̺� '��'�̳� '��'�� ���� �������� �Ʒ��� Ŭ�������� ����ϼ���.

| Ŭ���� | ���� |
|---|---|
|`.active`|Ư���� ���̳� ���� hover ���� ���� ���� ���� �����ϴ�.|
|`.success`|�������̰ų� �������� �׼��� �ǹ��մϴ�.|
|`.info`|�߸����� ������ ��ȭ�� �׼��� �ǹ��մϴ�.|
|`.warning`|���ǰ� �ʿ��� ��� �ǹ��մϴ�.|
|`.danger`|�����ϰų� �������� �� �ִ� �׼��� �ǹ��մϴ�.|

[����](http://codepen.io/luensys/pen/KVzxBL)
```html
<table class="table">
  <thead>
    <tr>
      <th>TD1</th>
      <th>TD2</th>
      <th>TD3</th>
    </tr>
  </thead>
  <tbody>
    <tr class="active">
      <td>active</td>
      <td>class</td>
      <td>row</td>
    </tr>
    <tr class="success">
      <td>success</td>
      <td>class</td>
      <td>row</td>
    </tr>
    <tr class="warning">
      <td>warning</td>
      <td>class</td>
      <td>row</td>
    </tr>
    <tr class="danger">
      <td>danger</td>
      <td>class</td>
      <td>row</td>
    </tr>
    <tr class="info">
      <td>info</td>
      <td>class</td>
      <td>row</td>
    </tr>
  </tbody>
</table>
```

### ������ ���̺�

`.table`�� `.table-responsive`�� ���μ� ������⿡���� ���� ��ũ���� ���⵵�� �ϴ� ���̺��� ����ϴ�.
������� 768px �����Դϴ�.

```
���� �߶󳻱� / ����
������ ���̺��� ���� ����� �ʰ��� �� ������ ��ũ���� �����ִ� overflow-y: hidden�� �̿��մϴ�.
�̰��� ��Ӵٿ� �޴��� �ٸ� ������Ƽ ������ ���ֹ��� �� �ֽ��ϴ�.
```
```
���̾������� �ʵ��
���̾������� ������ ���̺� �����ϴ� width ���� �� ���� �̻��� �ʵ�� ��Ÿ���� ������ �־�,
���̾����� ������ ���̴� ����� ���� �����ϴ�.
```

[����](http://codepen.io/luensys/pen/yeOxGB)
```html
<div class="table-responsive">
  <table class="table">
    <thead>
      <tr>
        <th>#</th>
        <th>Table heading</th>
        <th>Table heading</th>
        <th>Table heading</th>
        <th>Table heading</th>
        <th>Table heading</th>
        <th>Table heading</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope=row>1</th>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
      </tr>
      <tr>
        <th scope=row>2</th>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
      </tr>
      <tr>
        <th scope=row>3</th>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
      </tr>
    </tbody>
  </table>
</div>
<div class="table-responsive">
  <table class="table table-bordered">
    <thead>
      <tr>
        <th>#</th>
        <th>Table heading</th>
        <th>Table heading</th>
        <th>Table heading</th>
        <th>Table heading</th>
        <th>Table heading</th>
        <th>Table heading</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope=row>1</th>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
      </tr>
      <tr>
        <th scope=row>2</th>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
      </tr>
      <tr>
        <th scope=row>3</th>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
        <td>Table cell</td>
      </tr>
    </tbody>
  </table>
</div>
```

