?#### HTML5 ���� ����  
```
<!DOCTYPE html>
<html lang="ko">
  ...
</html>
```

#### ����� �켱 Mobile first

* ������ �������� Ȯ��/��Ҹ� ����, ����� `<head>`�� viewport ��Ÿ�±׸� �߰��ϼ���.
```
<meta name="viewport" content="width=device-width, initial-scale=1">
```

* user-scalable=no �� �߰��Ͽ� ����� ��⿡�� Ȯ��/��� ����� �� �� �ֽ��ϴ�.  
Ȯ��/��Ҹ� ���ٴ� ����, ����ڵ��� ���� ��ũ�Ѹ� �� �� ������ �ǹ��մϴ�.
```
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
```

#### Ÿ�����׷��ǿ� ��ũ

* `body` ���� `background-color: #fff;` �� �����մϴ�.  
* �⺻ Ÿ�����׷��Ƿ� �Ӽ� `@font-family-base`, `@font-size-base`, `@line-height-base` �� ����մϴ�.  
* ���� ��ũ�� ���� `@link-color` �� �����ϰ� ����ȿ���� `:hover` ���� ����Ǿ� �ֽ��ϴ�.  
* �� ��Ÿ�ϵ��� `scaffolding.less` ������ ã�� �� �ֽ��ϴ�.

#### CSS �ʱ�ȭ

���� ũ�ν� ����¡�� ���� Normalize.css �� ����մϴ�.
[Normalize.css](http://necolas.github.io/normalize.css/)


## Containers

  * ��Ʈ��Ʈ���� ����Ʈ �������� ���ΰ� �׸��� �ý����� ���� �����̳� ��Ұ� �ʿ��մϴ�. 
  * ���̾ƿ��� ����� ���� ���� ��ҿ� `.container` �Ǵ� `.container-fluid`�� �߰��մϴ�.
  * 2���� �����̳� �� �ϳ��� ������ �� �ֽ��ϴ�.

  **container�� �⺻������ ��ø �� ������ ���� �����Ͻʽÿ�.**


### .container�� �Ӽ�(������ �����̳�)

```
      .container {
      padding-right: 15px;
      padding-left: 15px;
      margin-right: auto;
      margin-left: auto;
    }

    @media (min-width: 768px) {
      .container {
        width: 750px;
      }
    }  
    @media (min-width: 992px) {
      .container {
        width: 970px;
      }
    }  
    @media (min-width: 1200px) {
      .container {
        width: 1170px;
      }
    }
```

���� �ػ� - 767px ���Ͽ����� 100%,   
            - 768px �̻󿡼��� 750px,   
            - 992px �̻󿡼��� 970px,   
            - 1200px �̻󿡼��� 1170px  


### .container-fluid �Ӽ�(��ü������ �þ�� �ִ��� �����̳�)

```
  .container-fluid {
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}
```

**���� �ػ󵵿� ������� 100%�� �������� �����ϴ�.**

### ����
<div>
<p data-height="268" data-theme-id="0" data-slug-hash="PPxrbB" data-default-tab="result" data-user="hklim82" class='codepen'>See the Pen <a href='http://codepen.io/hklim82/pen/PPxrbB/'>bootstrap container</a> by kero (<a href='http://codepen.io/hklim82'>@hklim82</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>
 </div>

[����������- ��Ʈ��Ʈ�� �����ϱ�](bootstrap-start.md)  
[����������- ��Ʈ��Ʈ��CSS_�׸���](css-grid.md)
