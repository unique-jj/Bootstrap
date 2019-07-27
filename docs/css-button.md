# Button



### ��ư �±�
`<a>`, `<button>`, `<input>` ��ҿ� ��ư Ŭ������ ����ϼ���.

[����](http://codepen.io/luensys/pen/JGNvWM?editors=100)

```html
<a class="btn btn-default" href="#" role="button">Link</a>
<button class="btn btn-default" type="submit">Button</button>
<input class="btn btn-default" type="button" value="Input">
<input class="btn btn-default" type="submit" value="Submit">
```

```
���� Ư�� ���
��ư Ŭ������ <a>, <button>�� ���Ǿ�������, ���� <button>���� �׺���̼ǰ� �׺���̼ǹ� ������Ʈ���� �����˴ϴ�.
```
```
��ưó�� �۵��ϴ� ��ũ
���� <a> ��Ұ� ��ưó�� ���ȴٸ�, �׵��� ������ role="button"�� �־����� �մϴ�.
```
```
ũ�ν�����¡ ������
ũ�ν������� �������� ������ Ȯ���� �ϱ����� ������ <button>�� ����ϴ� ���� ������ ��õ�մϴ�.
�� �ܿ� ���̾��������� ���װ� �ֽ��ϴ�.
�װ��� <input>�� line-height�� ������ ���� ������ ���̾������� �ٸ� ��ư�� ���̿� ��Ȯ�ϰ� �������� ���մϴ�.
```

### �ɼ�

�����ϰ� ��Ÿ�� ��ư�� ����� ���� ��밡���� ��ư Ŭ���� �� �ϳ��� ����ϼ���.

[����](http://codepen.io/luensys/pen/yebjbJ?editors=100)

```html
<!-- Standard button -->
<button type="button" class="btn btn-default">Default</button>

<!-- Provides extra visual weight and identifies the primary action in a set of buttons -->
<button type="button" class="btn btn-primary">Primary</button>

<!-- Indicates a successful or positive action -->
<button type="button" class="btn btn-success">Success</button>

<!-- Contextual button for informational alert messages -->
<button type="button" class="btn btn-info">Info</button>

<!-- Indicates caution should be taken with this action -->
<button type="button" class="btn btn-warning">Warning</button>

<!-- Indicates a dangerous or potentially negative action -->
<button type="button" class="btn btn-danger">Danger</button>

<!-- Deemphasize a button by making it look like a link while maintaining button behavior -->
<button type="button" class="btn btn-link">Link</button>
```

```
���� ���п� �ǹ̸� �����ϴ� ��
��ư�� �ǹ̸� �߰��ϱ� ���� ���� ����ϴ� ���� �ð����� ǥ�ÿ��� ������ �˴ϴ�.
�������� ������ ������ ��ü���� ��Ÿ�� �� �ֵ��� �ϼ���.
�׸��� .sr-only�� �ؽ�Ʈ�� ������� �ֽ��ϴ�.
```

### ũ��

��ư�� ũ�ų� �۰� �Ϸ���, `.btn-lg`, `btn-sm`, `.btn-xs`�� �߰��ϼ���.

[����](http://codepen.io/luensys/pen/VebxbB?editors=100)

```html
<p>
  <button type="button" class="btn btn-primary btn-lg">Large button</button>
  <button type="button" class="btn btn-default btn-lg">Large button</button>
</p>
<p>
  <button type="button" class="btn btn-primary">Default button</button>
  <button type="button" class="btn btn-default">Default button</button>
</p>
<p>
  <button type="button" class="btn btn-primary btn-sm">Small button</button>
  <button type="button" class="btn btn-default btn-sm">Small button</button>
</p>
<p>
  <button type="button" class="btn btn-primary btn-xs">Extra small button</button>
  <button type="button" class="btn btn-default btn-xs">Extra small button</button>
</p>
```

`.btn-block`�� ���ϴ� ������ ��Ϸ��� ��ư�� �θ� ��� ��ŭ �� �� �ʺ�� ����ϴ�.

```html
<div class="well center-block" style="max-width: 400px;">
  <button type="button" class="btn btn-primary btn-lg btn-block">Block level button</button>
  <button type="button" class="btn btn-default btn-lg btn-block">Block level button</button>
</div>
```

### Ȱ�� ����

��ư�� Ȱ��ȭ �Ǿ��� �� ������ ��ó�� ������ ���Դϴ�. `<button>` ��Ҹ� ���ؼ� `:active` �� ����� �� �ֽ��ϴ�.  
������ ���α׷������� Ȱ��ȭ�� ���¸� ������ �ʿ䰡 ���� �� `.active`�� ����� �� �ֽ��ϴ�.  
(�׸��� aria-pressed="ture" �Ӽ��� �����մϴ�.)

##### ��ư ���

`:active`�� ���� �ʿ�� �����ϴٸ�, ���� ������ ���� ����� �ʿ��ϴٸ�, `.active`�� �߰��ϼ���.

[����](http://codepen.io/luensys/pen/qbmYjx?editors=100)
(�� ������ �Ʒ��� ��Ŀ ��� �ڵ嵵 �����մϴ�.)

```html
<button type="button" class="btn btn-primary btn-lg active">Primary button</button>
<button type="button" class="btn btn-default btn-lg active">Button</button>
```

##### ��Ŀ ���

`<a>` ��ư�� `.active` Ŭ������ �߰��ϼ���.

```html
<a href="#" class="btn btn-primary btn-lg active" role="button">Primary link</a>
<a href="#" class="btn btn-default btn-lg active" role="button">Link</a>
```

### ��Ȱ��ȭ �� ����

`opacity`�� ������� �Ͽ� ��ư�� Ŭ���� �� ���� ��ó�� �������� ���弼��.  
(�������Ը� �ϴ� ���� �ƴ� ���� Ŭ���� ���� �ʽ��ϴ�.)

##### ��ư���

`<button>` ��ҿ� `disabled` �Ӽ��� �߰��ϼ���.

[����](http://codepen.io/luensys/pen/MKmGvj?editors=100)
(�� ������ �Ʒ��� ��Ŀ ��� �ڵ嵵 �����մϴ�.)

```html
<button type="button" class="btn btn-lg btn-primary" disabled="disabled">Primary button</button>
<button type="button" class="btn btn-default btn-lg" disabled="disabled">Button</button>
```

```
ũ�ν� ������ ȣȯ��
���� <button>�� diabled �Ӽ��� �߰��Ѵٸ�, ���ͳ� �ͽ��÷η� 9 �� �� ���ϴ� �츮�� ��ĥ �� ���� �̻��� �ؽ�Ʈ �׸��� ȸ�� �ؽ�Ʈ�� ������ �� ���Դϴ�.
```

##### ��Ŀ ���

`<a>`��ư�� `.diabled`�� �߰��ϼ���.

```html
<a href="#" class="btn btn-primary btn-lg disabled" role="button">Primary link</a>
<a href="#" class="btn btn-default btn-lg disabled" role="button">Link</a>
```
�츮�� ��ƿ��Ƽ Ŭ������ `.disabled`�� ����մϴ�. `.active`�� �����մϴ�. prefix�� �ʿ����� �ʽ��ϴ�.

```
��ũ ��ɼ� ���
�� Ŭ����(.diabled)�� <a>�� ��ũ ��ɼ��� ��Ȱ��ȭ �ϱ� ���� pointer-events: none�� ����մϴ�.
�׷��� �� CSS �Ӽ��� ���� ǥ���� ���� �ʾ� ����� 18�� ���� �׸��� ���ͳ� �ͽ��÷η� 11���� ȯ���ϰ� �������� �ʽ��ϴ�.
�߰���, pointer-events: none �� �����ϴ� ������ ������ Ű���� �׺���̼ǿ��� ȿ���� �����ϴ�.
�� ���� �������� ����ڵ��� ������ �̷� ��ũ�鿡 ������ �� �ִٴ� ����Դϴ�.
�����ϰ� ����Ϸ���, �׷� ��ũ���� ��Ȱ��ȭ �� �� �ִ� ���� �ڹٽ�ũ��Ʈ�� ����ϼ���.
```