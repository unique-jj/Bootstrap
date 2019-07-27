?
��Ʈ��Ʈ���� �����ϸ鼭 �����ؾ� �ϴ� ���ϵ�� ���� ����, �⺻���� ���� ���� �� ���ҽ��ϴ�.  
�̹� ��Ʈ��Ʈ�� Ȩ�������� ��Ʈ��Ʈ�� �ѱۻ���Ʈ�� ���� �ִ� ���������� �ٽ��ѹ� �ʿ��ϴٰ� �����Ǵ� �κи� �����Ͽ����ϴ�.


## �ٿ�ε�

* �ҽ��ٿ�ε�� ���� �ڼ��� ������ �Ʒ� ����Ʈ�� �����ϼ���(������ ����� ������ �ٲ� �� �����Ƿ� Ȩ�������� ���� ��)

[��Ʈ��Ʈ��/����](http://getbootstrap.com/getting-started/)  
[��Ʈ��Ʈ��/�ѱ�](http://bootstrapk.com/getting-started/)

#### ��Ʈ��Ʈ�� CDN 

  * [MaxCDN ](https://www.maxcdn.com/) ���� ��Ʈ��Ʈ���� CSS �� �ڹٽ�ũ��Ʈ�� CDN ���� �����մϴ�. �̸� ����Ϸ���, �Ʒ��� ��Ʈ��Ʈ�� CDN ��ũ���� ����ϼ���.
  * ������ �������� �ٲ� �� �ֽ��ϴ�.

```
<!-- �������� �ּ�ȭ�� �ֽ� CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css">

<!-- �ΰ����� �׸� -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap-theme.min.css">

<!-- �������� �ּ�ȭ�� �ֽ� �ڹٽ�ũ��Ʈ -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>
```

## ���� ����

#### �ּ�ȭ�� ��Ʈ��Ʈ��

```
bootstrap/
������ css/
��   ������ bootstrap.css
��   ������ bootstrap.css.map
��   ������ bootstrap.min.css
��   ������ bootstrap-theme.css
��   ������ bootstrap-theme.css.map
��   ������ bootstrap-theme.min.css
������ js/
��   ������ bootstrap.js
��   ������ bootstrap.min.js
������ fonts/
    ������ glyphicons-halflings-regular.eot
    ������ glyphicons-halflings-regular.svg
    ������ glyphicons-halflings-regular.ttf
    ������ glyphicons-halflings-regular.woff
    ������ glyphicons-halflings-regular.woff2
```

* ����Ʈ���� �ּҷ� ����Ѵٸ� �� �����߿��� `*.min.css` �� `*.min.js` �� �ε��ϰ� `font`�� �ε��ϸ� �˴ϴ�.

####��ü ��Ʈ ��Ʈ�� �ҽ� 

```
bootstrap/
������ less/
������ js/
������ fonts/
������ dist/
��   ������ css/
��   ������ js/
��   ������ fonts/
������ docs/
    ������ examples/
```

`*docs/`���� �ȿ��� �̸� �����ϵ� �ҽ����� �־� ������ ���鼭 ���� �Ҽ��� �ֽ��ϴ�

> ��Ʈ��Ʈ���� HTML5�� CSS, �ڹٽ�ũ��Ʈ�� ����ϱ� ���Ͽ�  jQuery �� 
> �ʿ��մϴ�.  

##�⺻ ���ø� 

#### �⺻����

```
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- �� 3���� ��Ÿ �±״� *�ݵ��* head �±��� ó���� 
    � �ٸ� ���������� �ݵ�� �� �±׵� *������* �;� �մϴ� -->
    <title>��Ʈ��Ʈ�� 101 ���ø�</title>

    <!-- ��Ʈ��Ʈ�� -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- IE8 ���� HTML5 ��ҿ� �̵�� ������ ���� HTML5 shim �� Respond.js -->
    <!-- WARNING: Respond.js �� ����� file:// �� ���� �������� �� ���� �������� �ʽ��ϴ�. -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- jQuery (��Ʈ��Ʈ���� �ڹٽ�ũ��Ʈ �÷������� ���� �ʿ��մϴ�) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
    <!-- ��� �����ϵ� �÷������� �����մϴ� (�Ʒ�), ������ �ʴ´ٸ� �ʿ��� ������ ������ �����ϼ��� -->
    <script src="js/bootstrap.min.js"></script>
  </body>
</html>
```

> `html5shiv.js` �� �ͽ��÷η��� html5 �� ������ �𸣱⶧���� �˷��ִ� ������
> �մϴ�. �׷��߸� html �� �ε�ɶ� ����� �ν��ϱ� �����Դϴ�.
> `respond.min.js` �� ���ͳ� �ͽ��÷η� 8�� �̵�������� �����ϱ� ���� 
> �ʿ��մϴ�.

[���� ���ø�](http://getbootstrap.com/getting-started/#examples)


#### ������ ���� 

������ ����� ���� ����, ������ ������ �����ϼ���. 

* ������ CSS �� ��õ� ����Ʈ <meta>�� �����մϴ�.
* `.container`�� width: 970px !important; ���� ��ġ���� �־��ݴϴ�.  
  **�̰͵��� �⺻ ��Ʈ��Ʈ�� CSS �ڿ� �;����� ����ϼ���**

* ���� �׺���̼� �ٸ� ����Ϸ���, ��� �׺���̼� ���� ������� ���̱� ������ �������ּ���.
* �׸��� ���̾ƿ��� ����, .col-md-* �� .col-lg-* Ŭ���� ��� `.col-xs-*` Ŭ������ ����ϼ���. ( ��� �ػ󵵿��� �����ϰ� �۵��մϴ�.)

* ������ IE8 �� ���� `respond.js` �� �ʿ��մϴ�(�̵�������� ������ �ʿ��ϱ⶧����).�̰��� ��Ʈ��Ʈ���� "����� ����Ʈ" ������ ������ �մϴ�.


[������� ����](http://bootstrapk.com/examples/non-responsive/)


#### ���ͳ� �ͽ��÷η� 8 �� 9

���ͳ� �ͽ��÷η� 8 �� 9 ���� �����˴ϴٸ�, �� ���������� �����ϰ� �������� �ʴ� ��� CSS �Ӽ��� HTML5 ��ҵ��� �������ּ���. ����, ���ͳ� �ͽ��÷η� 8 �� �̵�������� �����ϱ� ���� `Respond.js` �� ����� �ʿ��մϴ�.

<html>
<head>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap-theme.min.css">
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>
  <title></title>
</head>
<body>
  <div class="">
    <table class="table table-bordered table-striped">
      <thead>
        <tr>
          <th class="col-xs-4">���</th>
          <th class="col-xs-4">���ͳ� �ͽ��÷η� 8</th>
          <th class="col-xs-4">���ͳ� �ͽ��÷η� 9</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row"><code>border-radius</code></th>
          <td class="text-danger"><span class="glyphicon glyphicon-remove" aria-hidden="true"></span> �������� ����</td>
          <td class="text-success"><span class="glyphicon glyphicon-ok" aria-hidden="true"></span> ������</td>
        </tr>
        <tr>
          <th scope="row"><code>box-shadow</code></th>
          <td class="text-danger"><span class="glyphicon glyphicon-remove" aria-hidden="true"></span> �������� ����</td>
          <td class="text-success"><span class="glyphicon glyphicon-ok" aria-hidden="true"></span> ������</td>
        </tr>
        <tr>
          <th scope="row"><code>transform</code></th>
          <td class="text-danger"><span class="glyphicon glyphicon-remove" aria-hidden="true"></span> �������� ����</td>
          <td class="text-success"><span class="glyphicon glyphicon-ok" aria-hidden="true"></span> ������, <code>-ms</code> ���λ� �ʿ�</td>
        </tr>
        <tr>
          <th scope="row"><code>transition</code></th>
          <td colspan="2" class="text-danger"><span class="glyphicon glyphicon-remove" aria-hidden="true"></span> �������� ����</td>
        </tr>
        <tr>
          <th scope="row"><code>placeholder</code></th>
          <td colspan="2" class="text-danger"><span class="glyphicon glyphicon-remove" aria-hidden="true"></span> �������� ����</td>
        </tr>
      </tbody>
    </table>
  </div>
</body>
</html>




[����������- ��Ʈ��Ʈ��CSS_�����̳�](css-container.md)


