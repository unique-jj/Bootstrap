# Collapse

���� ��� �ൿ�� �ϱ����� �� ���� Ŭ���� ���� �̿��ϴ� ������ �÷����� �Դϴ�.

## Collapse ����

### ����
.collapse �������� ���� �ݴϴ�.
.collapsing ��ȯ �߿� ����˴ϴ�.
.collapse.in �������� �����ݴϴ�.

�Ʒ��� ��ư�� ������ ��Ÿ���� ������� ���� �Դϴ�.  
jsfiddle [����](http://jsfiddle.net/luensys/2e6jm9hm/)  
codepen.io [����](http://codepen.io/luensys/pen/epxjWw)
```
<a class="btn btn-primary" data-toggle="collapse" href="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
	Link with href
</a>
<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
	Button with data-target
</button>
<div class="collapse" id="collapseExample">
	<div class="well">
		...
	</div>
</div>
```

### Accordion ����
�г� ������Ʈ�� Accodion�� ������� �⺻ �÷��� ������ Ȯ���ϼ���.  
  
jsfiddle [����](http://jsfiddle.net/luensys/2e6jm9hm/1/)  
codepen.io [����](http://codepen.io/luensys/pen/avXjmz)  
```
<div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingOne">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
          Collapsible Group Item #1
        </a>
      </h4>
    </div>
    <div id="collapseOne" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="headingOne">
      <div class="panel-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingTwo">
      <h4 class="panel-title">
        <a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
          Collapsible Group Item #2
        </a>
      </h4>
    </div>
    <div id="collapseTwo" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
      <div class="panel-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingThree">
      <h4 class="panel-title">
        <a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
          Collapsible Group Item #3
        </a>
      </h4>
    </div>
    <div id="collapseThree" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
      <div class="panel-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
</div>
```
�� ������ ��� �� �� �̻��� Ȯ����� �ʴµ���.
�� ������ panel �׷����� ���� �־� �׷����ϴ�.
���� ���� div�� ������ �Ǹ� ������ ���������� �����ϰ� �˴ϴ�.

���� .panel-body ���� .list-group ��� ��ȯ�ϴ� �͵� �����մϴ�.
���� �� �ݴ��� .list-group ���� .panel-body ��� ��ȯ�ϴ� �͵� �����մϴ�.  

jsfiddle [����](http://jsfiddle.net/luensys/2e6jm9hm/2/)  
codepen.io [����](http://codepen.io/luensys/pen/GpzXWP)  
```
<div class="panel-group" role="tablist">
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="collapseListGroupHeading1">
      <h4 class="panel-title">
        <a class="collapsed" data-toggle="collapse" href="#collapseListGroup1" aria-expanded="false" aria-controls="collapseListGroup1">
          Collapsible list group
        </a>
      </h4>
    </div>
    <div id="collapseListGroup1" class="panel-collapse collapse" role="tabpanel" aria-labelledby="collapseListGroupHeading1">
      <ul class="list-group">
        <li class="list-group-item">Bootply</li>
        <li class="list-group-item">One itmus ac facilin</li>
        <li class="list-group-item">Second eros</li>
      </ul>
      <div class="panel-footer">Footer</div>
    </div>
  </div>
</div>
```

### �̺�Ʈ ����

�Ʒ��� Collapse�� �̿��� ����� ���� �� �̺�Ʈ�� ����� ���� �Դϴ�
����� �Ʒ� �ڵ忡�� script�� ready�� ���� ���� �ܵ� ������������ �� �Լ��� ��� jQuery�� �����ϱ� �����Դϴ�.  
[����](http://codepen.io/luensys/pen/QjYZmq)
```
<script>
	$(document).ready(function(){
		$('.panel').on('hidden.bs.collapse', function (e) {
		    alert('Event fired on #' + e.currentTarget.id);
		  })
	});
</script>
<div class="panel-group" id="accordion">
  <div class="panel panel-default" id="panel1">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapseOne">
          Collapsible Group Item #1
        </a>
      </h4>
    </div>
    <div id="collapseOne" class="panel-collapse collapse in">
      <div class="panel-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
  <div class="panel panel-default" id="panel2">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapseTwo">
          Collapsible Group Item #2
        </a>
      </h4>
    </div>
    <div id="collapseTwo" class="panel-collapse collapse">
      <div class="panel-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
  <div class="panel panel-default" id="panel3">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapseThree">
          Collapsible Group Item #3
        </a>
      </h4>
    </div>
    <div id="collapseThree" class="panel-collapse collapse">
      <div class="panel-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
</div>
```

�Ʒ� ������ �̺�Ʈ Ÿ�̹��� �� �� �ִ� �����Դϴ�.  
[����](http://codepen.io/luensys/pen/bVzmMW)
```
<div class="container">
  <h2>Collapsible Methods</h2>
  <p>The toggle method toggles the collapsible content.</p>
  <p>The show method shows the collapsible content.</p>
  <p>The hide method hides the collapsible content.</p>
  <button type="button" class="btn btn-primary">Toggle</button>
  <button type="button" class="btn btn-success">Show</button>
  <button type="button" class="btn btn-warning">Hide</button> 
    
  <div class="collapse">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit,
    sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
  </div>
</div>

<script>
$(document).ready(function(){
  $(".btn-primary").click(function(){
      $(".collapse").collapse('toggle');
  });
  $(".btn-success").click(function(){
      $(".collapse").collapse('show');
  });
  $(".btn-warning").click(function(){
      $(".collapse").collapse('hide');
  });
  $(".collapse").on('show.bs.collapse', function(){
      alert('The collapsible content is about to be shown.');
  });
  $(".collapse").on('shown.bs.collapse', function(){
      alert('The collapsible content is now fully shown.');
  });
  $(".collapse").on('hide.bs.collapse', function(){
      alert('The collapsible content is about to be hidden.');
  });
  $(".collapse").on('hidden.bs.collapse', function(){
      alert('The collapsible content is now hidden.');
  });
});
</script>
```
������ ���� show�� ��� ������ �������� ���� �˸�â�� ���̴� ���� �� �� �ְ�,
shown�� ��� ������ ������ �� �˸�â�� ���̴� ���� �� �� �ֽ��ϴ�.


