?## �׸��� �ý���

��Ʈ��Ʈ���� ��⳪ ����Ʈ ũ�Ⱑ �����Կ� ���� `12��`�� �����ϰ� Ȯ��Ǵ� ������, ����� �켱 ���� �׸��� �ý����Դϴ�.

#### �Ұ� Introduction
  �׸��� �ý����� ����� �������� ������ ��� �� �ø�� ���� ������ ���̾ƿ��� ����µ� ���Ǿ����ϴ�. 

  * `��(row)`�� �ݵ�� ������ ���İ� �е��� ���ؼ� `.container (fixed-width)` �� `.container-fluid (full-width)` �ȿ� ��ġ�ؾ� �մϴ�.
  * ������ ����׷��� ����µ� ��(row)�� �̿��ϼ���.
  * �������� ���ȿ� ��ġ�ؾ� �մϴ�. �׸��� ���鸸�� ���� �ٷ� �Ʒ��� �� �� �ֽ��ϴ�.
  * ���� `padding` ���� ���� ������ ����ϴ�. �е��� �� ������ ù���� ���������� ���� .row ���� ���� �������� offset �Ǿ� �ֽ��ϴ�.
  * ���� ������ �Ʒ��� �������� ����Ⱑ �Ǿ� �ִ� �����Դϴ�. �װ��� �׸��� �� ���� �������� ��׸��� �������� ���ĵǱ� �����Դϴ�.
```
  .row {
  margin-right: -15px;
  margin-left: -15px;
}
```

* `.row ` : `.container` �Ǵ� `.container-fluid` �ȿ� `.row`�� ���� ����ϴ�.  
* `.col-*-*` : `.row` �ȿ� `.col-*-*`�� ���� ����ϴ�


#### �̵�� ���� Media queries

�׸��� �ý��ۿ��� �ֿ� �б����� ����� ���� ������ �̵�� �������� ����մϴ�.

```
/* �ſ� ���� ���� (�������, 768px ���� ����) */
/* ��Ʈ��Ʈ������ �̰��� �⺻�̹Ƿ� �̵�������� �����ϴ�. */
 
/* ���� ���� (�º�, 768px �̻�) */
@media (min-width: @screen-sm-min) { ... }
 
/* �߰� ���� (����ũž, 992px �̻�) */
@media (min-width: @screen-md-min) { ... }
 
/* ū ���� (ū ����ũž, 1200px �̻�) */
@media (min-width: @screen-lg-min) { ... }
```


    
<table class="">
    <thead>
      <tr>
        <th></th>
        <th>
          �ſ� ���� ���
          <small>������� (&lt;768px)</small>
        </th>
        <th>
          ���� ���
          <small>�º� (��768px)</small>
        </th>
        <th>
          �߰� ���
          <small>����ũž (��992px)</small>
        </th>
        <th>
          ū ���
          <small>����ũž (��1200px)</small>
        </th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th class="text-nowrap" scope="row">�׸��� ����</th>
        <td>�׻� <!-- TODO: Horizontal at all times --></td>
        <td colspan="3">�б������� ũ�� ���� <!-- TODO: Collapsed to start, horizontal above breakpoints --></td>
      </tr>
      <tr>
        <th class="text-nowrap" scope="row">�����̳� �ʺ�</th>
        <td>���� (auto)</td>
        <td>750px</td>
        <td>970px</td>
        <td>1170px</td>
      </tr>
      <tr>
        <th class="text-nowrap" scope="row">Ŭ���� ���λ�</th>
        <td><code>.col-xs-</code></td>
        <td><code>.col-sm-</code></td>
        <td><code>.col-md-</code></td>
        <td><code>.col-lg-</code></td>
      </tr>
      <tr>
        <th class="text-nowrap" scope="row">�÷� ��</th>
        <td colspan="4">12</td>
      </tr>
      <tr>
        <th class="text-nowrap" scope="row">�÷� �ʺ�</th>
        <td class="text-muted">Auto</td>
        <td>~62px</td>
        <td>~81px</td>
        <td>~97px</td>
      </tr>
      <tr>
        <th class="text-nowrap" scope="row">���� �ʺ�</th>
        <td colspan="4">30px (�÷��� ���ʿ� 15px ��)</td>
      </tr>
      <tr>
        <th class="text-nowrap" scope="row">��ø</th>
        <td colspan="4">��</td>
      </tr>
      <tr>
        <th class="text-nowrap" scope="row">������</th>
        <td colspan="4">��</td>
      </tr>
      <tr>
        <th class="text-nowrap" scope="row">�÷� �������ϱ�</th>
        <td colspan="4">��</td>
      </tr>
    </tbody>
  </table>

���鿡 CSS �� ���� �����ϱ� ���� �̵�������� max-width �� �����Ͽ� �ο��մϴ�.

```
@media (max-width: @screen-xs-max) { ... }
@media (min-width: @screen-sm-min) and (max-width: @screen-sm-max) { ... }
@media (min-width: @screen-md-min) and (max-width: @screen-md-max) { ... }
@media (min-width: @screen-lg-min) { ... }
```

#### �׸��� �ɼ�

  <div class="table-responsive">
      <table class="table table-bordered table-striped responsive-utilities">
        <thead>
          <tr>
            <th></th>
            <th>
              �ſ� ���� ����
              <small>������� (&lt;768px)</small>
            </th>
            <th>
              ���� ����
              <small>�º� (��768px)</small>
            </th>
            <th>
              �߰� ����
              <small>����ũž (��992px)</small>
            </th>
            <th>
              ū ����
              <small>����ũž (��1200px)</small>
            </th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th><code>.visible-xs</code></th>
            <td class="is-visible">����</td>
            <td class="is-hidden">������</td>
            <td class="is-hidden">������</td>
            <td class="is-hidden">������</td>
          </tr>
          <tr>
            <th><code>.visible-sm</code></th>
            <td class="is-hidden">������</td>
            <td class="is-visible">����</td>
            <td class="is-hidden">������</td>
            <td class="is-hidden">������</td>
          </tr>
          <tr>
            <th><code>.visible-md</code></th>
            <td class="is-hidden">������</td>
            <td class="is-hidden">������</td>
            <td class="is-visible">����</td>
            <td class="is-hidden">������</td>
          </tr>
          <tr>
            <th><code>.visible-lg</code></th>
            <td class="is-hidden">������</td>
            <td class="is-hidden">������</td>
            <td class="is-hidden">������</td>
            <td class="is-visible">����</td>
          </tr>
        </tbody>
        <tbody>
          <tr>
            <th><code>.hidden-xs</code></th>
            <td class="is-hidden">������</td>
            <td class="is-visible">����</td>
            <td class="is-visible">����</td>
            <td class="is-visible">����</td>
          </tr>
          <tr>
            <th><code>.hidden-sm</code></th>
            <td class="is-visible">����</td>
            <td class="is-hidden">������</td>
            <td class="is-visible">����</td>
            <td class="is-visible">����</td>
          </tr>
          <tr>
            <th><code>.hidden-md</code></th>
            <td class="is-visible">����</td>
            <td class="is-visible">����</td>
            <td class="is-hidden">������</td>
            <td class="is-visible">����</td>
          </tr>
          <tr>
            <th><code>.hidden-lg</code></th>
            <td class="is-visible">����</td>
            <td class="is-visible">����</td>
            <td class="is-visible">����</td>
            <td class="is-hidden">������</td>
          </tr>
        </tbody>
      </table>
    </div>
  


#### ���� 1
�׸��� Ŭ������ `.col-md-*` �̱� ��Ʈ�� ����Ͽ�, ����� ����ũž(�߰�) ��⿡�� �������� �Ǳ�������, ����� ���� �º� ���(�ſ� �������� ��������)���� ���̱� �����ϴ� �⺻ �׸��� �ý����� ���� �� �ִ�. `.row` �ȿ� �׸��� �÷��� ��������.

<div>
  <p data-height="268" data-theme-id="0" data-slug-hash="jbQjMo" data-default-tab="result" data-user="hklim82" class='codepen'>See the Pen <a href='http://codepen.io/hklim82/pen/jbQjMo/'>bootstrap grid1</a> by kero (<a href='http://codepen.io/hklim82'>@hklim82</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>
</div>



***



* **������ �÷� �ʱ�ȭ**  
  ��밡���� 4����� �׸����� Ư�� �б�������, �÷����� �ϳ��� �ٸ� �÷����� �� ��� ��Ȯ�ϰ� Ŭ���� ���� ���� �� �ִ�. �װ� ��ġ�� ���ؼ���, `.clearfix `�� �츮�� ������ ��ƿ��Ƽ Ŭ�������� ������ ����ϸ� �˴ϴ�.
*  **`col-* -offset-*`**  
  .col-md-offset-* Ŭ������ ����Ͽ� �÷��� �������� �ű⼼��. �� Ŭ�������� * �÷���ŭ �� �÷��� ���������� �����ϰ� �մϴ�. ���� ���, .col-md-offset-4 �� .col-md-4 �� 4�÷���ŭ �̵���ŵ�ϴ�.
* **�÷� ��ø�ϱ�**  
  �⺻�׸���� �������� ��ø�Ϸ���, �����ϴ� .col-md-* �÷� ���� ���ο� .row �� .col-md-* �÷� ��Ʈ�� �߰��ϼ���. ��ø�� ���� ���ļ� 12 �� �Ǵ� �ϳ��� �÷� ��Ʈ�� �˴ϴ�.  
* **`col-push�� col-pull `**  
  .col-md-push-* ��.col-md-pull-* ����Ŭ������� �׸��� �÷����� ������ ���� �����Ҽ� �ֽ��ϴ�.
#### ���� 2

<div>
  <p data-height="268" data-theme-id="0" data-slug-hash="JYeQKE" data-default-tab="result" data-user="hklim82" class='codepen'>See the Pen <a href='http://codepen.io/hklim82/pen/JYeQKE/'>bootstrap grid2</a> by kero (<a href='http://codepen.io/hklim82'>@hklim82</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>
</div>

***




[����������- ��Ʈ��Ʈ��CSS_�����̳�](css-container.md)  
[����������- component-list-group](component-list-group.md)

