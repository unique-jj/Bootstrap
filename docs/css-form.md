# Form



### �⺻ ����

������ �� ��Ʈ���� �ڵ������� �ణ�� ���� ��Ÿ���� �ް� �ް� �˴ϴ�. `.form-control`�� �ִ� ��� �ؽ�Ʈ ������ `<input>`, `<textarea>`, `<select>`�� �⺻���� width�� 100%�� �������ϴ�. ������ ������ ���� �󺧵�� ��Ʈ�ѵ��� `.form-group`���� ����� �մϴ�.

![�⺻ ���� ���̺�](../images/css-table-basic.png)

[����](http://codepen.io/luensys/pen/GoZwYj?editors=100)
```html
<form>
  <div class="form-group">
    <label for="exampleInputEmail1">�̸��� �ּ�</label>
    <input type="email" class="form-control" id="exampleInputEmail1" placeholder="�̸����� �Է��ϼ���">
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">��ȣ</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="��ȣ">
  </div>
  <div class="form-group">
    <label for="exampleInputFile">���� ���ε�</label>
    <input type="file" id="exampleInputFile">
    <p class="help-block">���⿡ ��Ϸ��� ���� ����</p>
  </div>
  <div class="checkbox">
    <label>
      <input type="checkbox"> �Է��� ����մϴ�
    </label>
  </div>
  <button type="submit" class="btn btn-default">����</button>
</form>
```
```
form-group�� input-group�� ���� ���� ������.
form-group�� input-group�� ���� ���� ���� ������. ��� input-group�� form-group �ȿ� ������.
```

### �ζ��� ��

�������� �����ϱ� ���ؼ��� `form-inline`�� �߰��ϼ���. ��, �̰��� �ּ� 768px�� ����Ʈ ���� ������ ����˴ϴ�.

���� �ʺ� �ʿ��� �� �̽��ϴ�.  
�Է� ��Ʈ���̳� ����Ʈ ��Ʈ���� ��Ʈ��Ʈ������ �⺻������ `width:100%`�� ����Ǿ� �ֽ��ϴ�.  
�ζ��� �� �������� �� ���� `width: auto;`�� �ʱ�ȭ �Ͽ� �� ���� ��Ʈ�ѵ��� ���� �ٿ� �ֵ��� �� �� �ֽ��ϴ�.  
���̾ƿ��� ���� �߰����� ���� �ʺ� �ʿ��� �� �ֽ��ϴ�.  


������ ���� �߰��ϼ���.  
��ũ�� ������ input ���� �������� ���� ��� ������ ���� �� �ֽ��ϴ�.  
�ζ��� ���� ���ؼ� `.sr-only`�� ����Ͽ� ���� ���� �� �ֽ��ϴ�.  
�������� ������� `area-label`, `aria-labelledby`, `title`�� �ֽ��ϴ�.  
�̷� �͵��� �������� �ʴ´ٸ� ��ũ�� ������ `placeholder` �Ӽ��� ������ �� �ۿ� ������,  
`placeholder`�� �ٸ� �󺧸��� ��ü�ϴ� ���� �������� �ʽ��ϴ�.  

![�ζ��� ���� ���̺�](../images/css-table-inline.png)

[����](http://codepen.io/luensys/pen/JGEZwK?editors=100)

```html
<form class="form-inline">
  <div class="form-group">
    <label for="exampleInputName2">Name</label>
    <input type="text" class="form-control" id="exampleInputName2" placeholder="Jane Doe">
  </div>
  <div class="form-group">
    <label for="exampleInputEmail2">Email</label>
    <input type="email" class="form-control" id="exampleInputEmail2" placeholder="jane.doe@example.com">
  </div>
  <button type="submit" class="btn btn-default">Send invitation</button>
</form>
```

### ���� ��
���� `.form-horizontal`�� �߰��Ͽ� �󺧵�� �� ��Ʈ���� �̸� ���ǵ� �׸��� Ŭ������ ������ �����մϴ�.  
�׸����� ������ `.form-group`�� �ϱ� ������ `.row`�� �ʿ䰡 �����ϴ�.

![���� �� ���� ���̺�](../images/css-table-horizontal.png)

[����](http://codepen.io/luensys/pen/BjpPLv?editors=100)
```html
<form class="form-horizontal">
  <div class="form-group">
    <label for="inputEmail3" class="col-sm-2 control-label">Email</label>
    <div class="col-sm-10">
      <input type="email" class="form-control" id="inputEmail3" placeholder="Email">
    </div>
  </div>
  <div class="form-group">
    <label for="inputPassword3" class="col-sm-2 control-label">Password</label>
    <div class="col-sm-10">
      <input type="password" class="form-control" id="inputPassword3" placeholder="Password">
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-2 col-sm-10">
      <div class="checkbox">
        <label>
          <input type="checkbox"> Remember me
        </label>
      </div>
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-2 col-sm-10">
      <button type="submit" class="btn btn-default">Sign in</button>
    </div>
  </div>
</form>
```

### �����Ǵ� ��Ʈ�� ��

#####�Էµ�

�Ʒ��� Ÿ�Ե��� ��� �����մϴ�.(HTML5)

`text`, `password`, `datetime`, `datetime-local`, `date`, `month`, `time`, `week`, `number`, `email`, `url`, `search`, `tel`, `color`

```
�Է��� type�� ����� ����� ��쿡�� ��Ÿ�� �˴ϴ�.
```

[����](http://codepen.io/luensys/pen/EPZpdv?editors=100)
�Ʒ��� ������ type�� �ٲ㺸�� ���� �����ϰ� �ۼ��Ͽ����ϴ�.

```html
<input type="month" class="form-control" placeholder="Text input">
```

#####TextArea

�������� �Է��� �����ϴ� ��  
`row`�� �̿��ؼ� ���� �ٲ� �� �ֽ��ϴ�.

[����](http://codepen.io/luensys/pen/eJWMwJ?editors=100)
```html
<textarea class="form-control" rows="3"></textarea>
```

##### üũ�ڽ�, ����

`disabled` �Ӽ��� ���� ��쿡�� �����ϰ� ��Ÿ�� �� ���Դϴ�.

###### �⺻

[����](http://codepen.io/luensys/pen/jWmzjg?editors=100)
```html
<div class="checkbox">
  <label>
    <input type="checkbox" value="">
    Option one is this and that&mdash;be sure to include why it's great
  </label>
</div>
<div class="checkbox disabled">
  <label>
    <input type="checkbox" value="" disabled>
    Option two is disabled
  </label>
</div>

<div class="radio">
  <label>
    <input type="radio" name="optionsRadios" id="optionsRadios1" value="option1" checked>
    Option one is this and that&mdash;be sure to include why it's great
  </label>
</div>
<div class="radio">
  <label>
    <input type="radio" name="optionsRadios" id="optionsRadios2" value="option2">
    Option two can be something else and selecting it will deselect option one
  </label>
</div>
<div class="radio disabled">
  <label>
    <input type="radio" name="optionsRadios" id="optionsRadios3" value="option3" disabled>
    Option three is disabled
  </label>
</div>
```

###### �ζ��� üüũ�ڽ��� ����

üũ�ڽ��� ���� ��Ʈ�ѵ��� ���� �ٿ� ���̰� �Ϸ��� `.checkbox-inline` �̳� `radio-inline` Ŭ������ ����ϼ���.

[����](http://codepen.io/luensys/pen/bEWvXJ?editors=100)
```html
<label class="checkbox-inline">
  <input type="checkbox" id="inlineCheckbox1" value="option1"> 1
</label>
<label class="checkbox-inline">
  <input type="checkbox" id="inlineCheckbox2" value="option2"> 2
</label>
<label class="checkbox-inline">
  <input type="checkbox" id="inlineCheckbox3" value="option3"> 3
</label>
<br>
<label class="radio-inline">
  <input type="radio" name="inlineRadioOptions" id="inlineRadio1" value="option1"> 1
</label>
<label class="radio-inline">
  <input type="radio" name="inlineRadioOptions" id="inlineRadio2" value="option2"> 2
</label>
<label class="radio-inline">
  <input type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option3"> 3
</label>
```

###### �� �ؽ�Ʈ ���� üũ�ڽ��� ����

�Է� ��Ʈ���� ��������� ��ġ�Ѵٸ� `<label>`�� �ؽ�Ʈ�� �ʿ����� ���� �� �ֽ��ϴ�.`���� �ζ����� �ƴ� üũ�ڽ��� ���������� ����`  
������ �������� ���������� �����Ǿ�� ���� ����ϼ���.(�� `aria-label`)

[����](http://codepen.io/luensys/pen/gPWzYB?editors=100)

```html
<div class="checkbox">
  <label>
    <input type="checkbox" id="blankCheckbox" value="option1" aria-label="...">
  </label>
</div>
<div class="radio">
  <label>
    <input type="radio" name="blankRadio" id="blankRadio1" value="option1" aria-label="...">
  </label>
</div>
```

###### ����Ʈ

���ĸ��� ũ���� ����Ʈ�� `border-radius` �Ӽ����� �������� �ʴ� �ձ� �ڳʸ� ���� �� �ְ� �մϴ�.

[����](http://codepen.io/luensys/pen/jWmxON?editors=100)

```html
<select class="form-control">
  <option>1</option>
  <option>2</option>
  <option>3</option>
  <option>4</option>
  <option>5</option>
</select>

```

�⺻������ ���� �ɼ��� �����ֱ� ���ؼ��� ����Ʈ ��Ʈ���� `multiple` �Ӽ��� �ִ�.

[����](http://codepen.io/luensys/pen/EPmLxZ?editors=100)

```html
<select multiple class="form-control">
  <option>1</option>
  <option>2</option>
  <option>3</option>
  <option>4</option>
  <option>5</option>
</select>
```

### ���� ��Ʈ��

������ �ؽ�Ʈ�� �ְ� ���� ���� `<p>`�� `.form-control-static` Ŭ������ ����մϴ�.

[����]http://codepen.io/luensys/pen/LGymYz?editors=100)

```html
<form class="form-horizontal">
  <div class="form-group">
    <label class="col-sm-2 control-label">Email</label>
    <div class="col-sm-10">
      <p class="form-control-static">email@example.com</p>
    </div>
  </div>
  <div class="form-group">
    <label for="inputPassword" class="col-sm-2 control-label">Password</label>
    <div class="col-sm-10">
      <input type="password" class="form-control" id="inputPassword" placeholder="Password">
    </div>
  </div>
</form>
```

```html
<form class="form-inline">
  <div class="form-group">
    <label class="sr-only">Email</label>
    <p class="form-control-static">email@example.com</p>
  </div>
  <div class="form-group">
    <label for="inputPassword2" class="sr-only">Password</label>
    <input type="password" class="form-control" id="inputPassword2" placeholder="Password">
  </div>
  <button type="submit" class="btn btn-default">Confirm identity</button>
</form>
```

### ��Ŀ�� ����

`:focus`�� ���� �� �� ����Ʈ�ѵ鿡 `box-shadow`�� �����߽��ϴ�.

![�� ��Ŀ��](../images/css-form-focus.png)
```
���� �󿡼� �ٷ� ��Ŀ���� ǥ���� �� ���� ĸ�ĵ� �̹����� ��ü�մϴ�.
```

### ��Ȱ��ȭ ����

input���� ��ȣ�ۿ��� �������� `disabled` �Ӽ��� �߰��ϼ���.  
��Ȱ��ȭ�� �Է¾���� �� �� ��� �������� `not-allowed` Ŀ���� �߰��˴ϴ�.

[����](http://codepen.io/luensys/pen/WrjJvV?editors=100)

```html
<input class="form-control" id="disabledInput" type="text" placeholder="Disabled input here..." disabled>
```

##### ��Ȱ��ȭ �� �ʵ��

�� ���� `<fieldset>` �� ��� ��Ʈ���� ��Ȱ��ȭ �Ϸ��� `<fieldset>`�� `disabled`�Ӽ��� �߰��ϼ���.

```
<a> ��ũ ��ɼ��� ���� ���
�⺻������ ��Ȱ��ȭ�� �ʵ�¿����� ��� �� ��Ʈ�ѵ��� �� ����� ���� ��Ȱ��ȭ �ǰ�����,
���� ���� <a ... class="btn btn-*">�� �����ϸ�,
�� ���� ���� �ƴϹǷ� ����� �������� ���� �� �ֽ��ϴ�.
�̷��� ��ũ�� ���� ���� �ڹٽ�ũ��Ʈ�� ����ϼ���.
```
```
ũ�ν� ������ ȣȯ��
��Ʈ��Ʈ���� �� ��Ÿ�ϵ��� ��� �������� ����������,
���ͳ� �ͽ��÷η� 11�� �� ���Ͽ����� �������� �ʽ��ϴ�.
�� ���������� �ʵ���� ��Ȱ��ȭ �Ϸ��� ���� �ڹٽ�ũ��Ʈ�� ����ϼ���.
```

[����](http://codepen.io/luensys/pen/WrjJQV?editors=100)

```html
<form>
  <fieldset disabled>
    <div class="form-group">
      <label for="disabledTextInput">Disabled input</label>
      <input type="text" id="disabledTextInput" class="form-control" placeholder="Disabled input">
    </div>
    <div class="form-group">
      <label for="disabledSelect">Disabled select menu</label>
      <select id="disabledSelect" class="form-control">
        <option>Disabled select</option>
      </select>
    </div>
    <div class="checkbox">
      <label>
        <input type="checkbox"> Can't check this
      </label>
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </fieldset>
</form>
```

### �б� ���� ����

�Է� ���� ������ �������� �Է���Ʈ�ѿ� `readonly` �Ӽ��� �߰��մϴ�.  
�б����� �Է���Ʈ���� �� �� ��� ��������, Ŀ���� �⺻Ŀ���� �����ֽ��ϴ�.

[����](http://codepen.io/luensys/pen/EPmLPm?editors=100)

```html
<input class="form-control" type="text" placeholder="Readonly input here��" readonly>
```

##### ��ȿ ����
��Ʈ��Ʈ���� �� �ܷ� ���� ����, ���, ���� ���¸� ���� ��ȿ���� ��Ÿ���� �����ϰ� �ֽ��ϴ�.  
����Ϸ���, �θ� ��ҿ� `has-warning`, `has-error`, `has-success` �� �߰��ϼ���.  
�� ��Ҿ��� ��� `control-label`, `.form-control`, `.help-block`�� ��ȿ�� ��Ÿ���� ���� �޽��ϴ�.

```
������������ ��ȿ ���¸� �����ϱ�
�� ��Ʈ���� ���¸� �˸��� ���� ���� �ð����� ǥ���� ���Դϴ�.  
���� �� ����� ������δ� <label> �ؽ�Ʈ ��ü�� ��Ʈ�� ������ �� �ֽ��ϴ�.
�ƴϸ� aria-dscribedby�� ����ϴ� ����Ʈ�� ��ȿ���¿� ���� �ؽ�Ʈ ������ �߰����� �Ӽ����� ����� �� �ֽ��ϴ�.
������ ���, ����� ����Ʈ�ѿ� area-invalid="true"�� ����� �� �ֽ��ϴ�.
```

[����](http://codepen.io/luensys/pen/yebjOe?editors=100)

```html
<div class="form-group has-success">
  <label class="control-label" for="inputSuccess1">Input with success</label>
  <input type="text" class="form-control" id="inputSuccess1">
</div>
<div class="form-group has-warning">
  <label class="control-label" for="inputWarning1">Input with warning</label>
  <input type="text" class="form-control" id="inputWarning1">
</div>
<div class="form-group has-error">
  <label class="control-label" for="inputError1">Input with error</label>
  <input type="text" class="form-control" id="inputError1">
</div>
<div class="has-success">
  <div class="checkbox">
    <label>
      <input type="checkbox" id="checkboxSuccess" value="option1">
      Checkbox with success
    </label>
  </div>
</div>
<div class="has-warning">
  <div class="checkbox">
    <label>
      <input type="checkbox" id="checkboxWarning" value="option1">
      Checkbox with warning
    </label>
  </div>
</div>
<div class="has-error">
  <div class="checkbox">
    <label>
      <input type="checkbox" id="checkboxError" value="option1">
      Checkbox with error
    </label>
  </div>
</div>
```

##### �������� ������

����� ���� `.has-feedback`�� ���� �������� �߰��� �������� �ǵ�� �������� �߰��� �� �ֽ��ϴ�.  
��, �ǵ�� �������� ���� �ؽ�Ʈ�� ����ϴ� `<input class="form-control"> ��ҿ����� �۵��մϴ�.

```
������, ��, �Է� �׷�
�ǵ�� �������� ���� ��ġ�� �� ���� �Է���Ʈ�Ѱ� �ֵ���� �����ʿ� �ִ� input groups�� ���� �ʿ��մϴ�.
����� ���ټ� ������ ���� ��� �Է� ��Ʈ���� ���� ���� �����ϴ� ���� �����ϰ� ����ؾ� �մϴ�.
���� ����� �� ���� �Ѵٸ�, �ǵ��������� top���� �����մϴ�.
�Է� �׷��� ����, ����� �ֵ���� �ʺ� ����Ͽ� ������ �ȼ������� right���� �����ϼ���.
```
```
�������п� �������� �ǹ̸� �����ϴ� ��
��ũ�� �������� ���� ���п��� �������� �ǹ̸� Ȯ���ϰ� �����Ϸ���, .sr-only Ŭ������ �߰����� ������ �ؽ�Ʈ�� �����ϰų�, aria-describedby�� ����Ͽ� �� ��Ʈ�Ѱ� �����Ǿ� �־�� �մϴ�.
�׷��� ������ ����Ʈ�ѿ� ����� <label>�� �ؽ�Ʈ�� �ٲٴ� ��ó�� �ٸ� ����� ����ؾ� �մϴ�.
�Ʒ��� �������� Ȯ���� �� �ֽ��ϴ�.
```

[����](http://codepen.io/luensys/pen/EPmLym?editors=100)

```html
<div class="form-group has-success has-feedback">
  <label class="control-label" for="inputSuccess2">Input with success</label>
  <input type="text" class="form-control" id="inputSuccess2" aria-describedby="inputSuccess2Status">
  <span class="glyphicon glyphicon-ok form-control-feedback" aria-hidden="true"></span>
  <span id="inputSuccess2Status" class="sr-only">(success)</span>
</div>
<div class="form-group has-warning has-feedback">
  <label class="control-label" for="inputWarning2">Input with warning</label>
  <input type="text" class="form-control" id="inputWarning2" aria-describedby="inputWarning2Status">
  <span class="glyphicon glyphicon-warning-sign form-control-feedback" aria-hidden="true"></span>
  <span id="inputWarning2Status" class="sr-only">(warning)</span>
</div>
<div class="form-group has-error has-feedback">
  <label class="control-label" for="inputError2">Input with error</label>
  <input type="text" class="form-control" id="inputError2" aria-describedby="inputError2Status">
  <span class="glyphicon glyphicon-remove form-control-feedback" aria-hidden="true"></span>
  <span id="inputError2Status" class="sr-only">(error)</span>
</div>
<div class="form-group has-success has-feedback">
  <label class="control-label" for="inputGroupSuccess1">Input group with success</label>
  <div class="input-group">
    <span class="input-group-addon">@</span>
    <input type="text" class="form-control" id="inputGroupSuccess1" aria-describedby="inputGroupSuccess1Status">
  </div>
  <span class="glyphicon glyphicon-ok form-control-feedback" aria-hidden="true"></span>
  <span id="inputGroupSuccess1Status" class="sr-only">(success)</span>
</div>
```

###### �������� �ζ��������� ���� ������

�Ʒ��� ������ ������������ �ζ��������� ������������ ��� ǥ�õǴ����� �����ִ� �����Դϴ�.

[����](http://codepen.io/luensys/pen/BjRxzE?editors=100)

```html
<form class="form-horizontal">
  <div class="form-group has-success has-feedback">
    <label class="control-label col-sm-3" for="inputSuccess3">Input with success</label>
    <div class="col-sm-9">
      <input type="text" class="form-control" id="inputSuccess3" aria-describedby="inputSuccess3Status">
      <span class="glyphicon glyphicon-ok form-control-feedback" aria-hidden="true"></span>
      <span id="inputSuccess3Status" class="sr-only">(success)</span>
    </div>
  </div>
  <div class="form-group has-success has-feedback">
    <label class="control-label col-sm-3" for="inputGroupSuccess2">Input group with success</label>
    <div class="col-sm-9">
      <div class="input-group">
        <span class="input-group-addon">@</span>
        <input type="text" class="form-control" id="inputGroupSuccess2" aria-describedby="inputGroupSuccess2Status">
      </div>
      <span class="glyphicon glyphicon-ok form-control-feedback" aria-hidden="true"></span>
      <span id="inputGroupSuccess2Status" class="sr-only">(success)</span>
    </div>
  </div>
</form>
```
```html
<form class="form-inline">
  <div class="form-group has-success has-feedback">
    <label class="control-label" for="inputSuccess4">Input with success</label>
    <input type="text" class="form-control" id="inputSuccess4" aria-describedby="inputSuccess4Status">
    <span class="glyphicon glyphicon-ok form-control-feedback" aria-hidden="true"></span>
    <span id="inputSuccess4Status" class="sr-only">(success)</span>
  </div>
</form>
<form class="form-inline">
  <div class="form-group has-success has-feedback">
    <label class="control-label" for="inputGroupSuccess3">Input group with success</label>
    <div class="input-group">
      <span class="input-group-addon">@</span>
      <input type="text" class="form-control" id="inputGroupSuccess3" aria-describedby="inputGroupSuccess3Status">
    </div>
    <span class="glyphicon glyphicon-ok form-control-feedback" aria-hidden="true"></span>
    <span id="inputGroupSuccess3Status" class="sr-only">(success)</span>
  </div>
</form>
```

###### ������ `.sr-only` �󺧰� ���� ������
���� ����Ʈ���� `<lable>`�� ��������� `.sr-only` Ŭ������ ����Ѵٸ�, ��Ʈ��Ʈ���� �ڵ����� �������� ��ġ�� �����մϴ�.  
(aria-label �Ӽ����� �ٸ� �󺧸� ����� ������� �ʰ�)

[����](http://codepen.io/luensys/pen/adWGmy?editors=100)

```html
<div class="form-group has-success has-feedback">
  <label class="control-label sr-only" for="inputSuccess5">Hidden label</label>
  <input type="text" class="form-control" id="inputSuccess5" aria-describedby="inputSuccess5Status">
  <span class="glyphicon glyphicon-ok form-control-feedback" aria-hidden="true"></span>
  <span id="inputSuccess5Status" class="sr-only">(success)</span>
</div>
<div class="form-group has-success has-feedback">
  <label class="control-label sr-only" for="inputGroupSuccess4">Input group with success</label>
  <div class="input-group">
    <span class="input-group-addon">@</span>
    <input type="text" class="form-control" id="inputGroupSuccess4" aria-describedby="inputGroupSuccess4Status">
  </div>
  <span class="glyphicon glyphicon-ok form-control-feedback" aria-hidden="true"></span>
  <span id="inputGroupSuccess4Status" class="sr-only">(success)</span>
</div>
```

### �� ��Ʈ�� ũ�� ����

`.input-lg` ���� Ŭ������ ����Ͽ� ���̸� �����ϼ���. �׸��� `.col-lg=*` ���� �׸��� �� Ŭ������ ����Ͽ� �ʺ� �����ϼ���.

##### ���� ����

�� ��Ʈ���� ��ư ũ�⿡ ���� ũ�ų� �۰� ���弼��.

[����](http://codepen.io/luensys/pen/jWmxVP?editors=100)

```html
<input class="form-control input-lg" type="text" placeholder=".input-lg">
<input class="form-control" type="text" placeholder="Default input">
<input class="form-control input-sm" type="text" placeholder=".input-sm">

<select class="form-control input-lg">
  <option value="">.input-lg</option>
</select>
<select class="form-control">
  <option value="">Default select</option>
</select>
<select class="form-control input-sm">
  <option value="">.input-sm</option>
</select>
```

##### ������ �׷� ũ�� ����

`.form-horizontal`���� �󺧰� ����Ʈ���� �����ϰ� `.form-group-lg`�� `.form-group-sm`���� ũ������ �ϼ���.

[����](http://codepen.io/luensys/pen/wMdjoL?editors=100)

```html
<form class="form-horizontal">
  <div class="form-group form-group-lg">
    <label class="col-sm-2 control-label" for="formGroupInputLarge">Large label</label>
    <div class="col-sm-10">
      <input class="form-control" type="text" id="formGroupInputLarge" placeholder="Large input">
    </div>
  </div>
  <div class="form-group form-group-sm">
    <label class="col-sm-2 control-label" for="formGroupInputSmall">Small label</label>
    <div class="col-sm-10">
      <input class="form-control" type="text" id="formGroupInputSmall" placeholder="Small input">
    </div>
  </div>
</form>
```

##### �� ũ�� ����

�Է���Ʈ���� �׸��� ���̳� ������ ���ϴ� �ʺ�� �����ִ� ���� �θ� ��ҷ� ���μ���.

[����](http://codepen.io/luensys/pen/XXRqpM?editors=100)

```html
<div class="row">
  <div class="col-xs-2">
    <input type="text" class="form-control" placeholder=".col-xs-2">
  </div>
  <div class="col-xs-3">
    <input type="text" class="form-control" placeholder=".col-xs-3">
  </div>
  <div class="col-xs-4">
    <input type="text" class="form-control" placeholder=".col-xs-4">
  </div>
</div>
```

### ����

�� ��Ʈ���� ���� ��� ���� ����.

```
����Ʈ�Ѱ� ������ �����ϱ�
������ ��Ȯ�ϰ� aria-describedby �� ����Ͽ� ����Ʈ�Ѱ� ����Ǿ�� �մϴ�.  
�̰��� ���� ���� ���� ��Ʈ�ѿ� ��Ŀ�� �ǰų� ������ �� ������ �˷��ݴϴ�.
```

[����](http://codepen.io/luensys/pen/VebxPd?editors=100)

```html
<label class="sr-only" for="inputHelpBlock">Input with help text</label>
<input type="text" id="inputHelpBlock" class="form-control" aria-describedby="helpBlock">
...
<span id="helpBlock" class="help-block">A block of help text that breaks onto a new line and may extend beyond one line.</span>
```