# ���(Modals)

����� ����ȭ �Ǿ��ְ� �ּ����� ����� ������ ����Ʈ�ϰ� ǥ���� �� �ִ� ��ȭ â �Դϴ�.

## ��� ����

### ���� ����

�Ʒ��� ������ ����ϸ� ��� â�� �⺻���� ����� Ȯ���� �� �ֽ��ϴ�.  
[����](http://codepen.io/luensys/pen/NGoOLv)
```
<div class="modal fade in" style="display: block;">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title">Modal title</h4>
      </div>
      <div class="modal-body">
        <p>One fine body&hellip;</p>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div><!-- /.modal-content -->
  </div><!-- /.modal-dialog -->
</div><!-- /.modal -->
```
�� ������ ������� ���� �� �� �ֵ���
```
      <div class="modal-body">
        <p>One fine body&hellip;</p>
      </div>
```
�ȿ� �ִ� ���� �ֿ� ������ �Դϴ�.

### ��ư ����

�Ʒ��� ������ ����ϸ� ��ư�� ������ �� ���â�� ��Ÿ���� ���� �� �� �ֽ��ϴ�.  
[����](http://codepen.io/luensys/pen/wKNYYe)
```
<!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModal">
  Launch demo modal
</button>

<!-- Modal -->
<div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Modal title</h4>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
```
����� ���â�� �������� �÷����Ϸ��� ��Ʈ��Ʈ�� ��޸����δ� ������ ��ư� Ŀ���͸���¡�� �ؾ��մϴ�.


### ��� ũ�� �ɼ�

����� 2���� ���� ������ �ɼ��� �ֽ��ϴ�. .modal-dialog�� �� Ŭ������ �����ϴ� ���� �����մϴ�.  
[����](http://codepen.io/luensys/pen/RWveqa)
```
<!-- Large modal -->
<button type="button" class="btn btn-primary" data-toggle="modal" data-target=".bs-example-modal-lg">Large modal</button>

<div class="modal fade bs-example-modal-lg" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel">
  <div class="modal-dialog modal-lg">
    <div class="modal-content">
      ...
    </div>
  </div>
</div>

<!-- Small modal -->
<button type="button" class="btn btn-primary" data-toggle="modal" data-target=".bs-example-modal-sm">Small modal</button>

<div class="modal fade bs-example-modal-sm" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel">
  <div class="modal-dialog modal-sm">
    <div class="modal-content">
      ...
    </div>
  </div>
</div>
```
���� �������� modal-sm, modal-lg �� �̿��ϴ� ���� �� �� ������,
�� ���� �ڵ�� ��Ʈ��Ʈ���� �Ʒ� �ڵ� �κ��� ���� ������ �� �ֽ��ϴ�.
```
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, .5);
            box-shadow: 0 5px 15px rgba(0, 0, 0, .5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
```

### �ִϸ��̼� ����

����� ������ ���� �����ϰ� �ϱ� ���� �ִϸ��̼��� �����ϴ� �͵� �����մϴ�.  
[����](http://codepen.io/luensys/pen/epxPQP)
```
<button type="button" class="btn btn-primary" data-toggle="modal" data-target=".modal">Open modal no Animation</button>

<div class="modal" tabindex="-1" role="dialog" aria-labelledby="" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      ...
    </div>
  </div>
</div>
```

### �׸��� �ý����� ����ϴ� ��
��޿����� ��Ʈ��Ʈ�� �׸��� �ý����� ������ ������ؼ��� `.modal-body`�ȿ� `.row`�� ����� �Ϲ����� �׸��� �ý��� Ŭ������ ����� �� �ֽ��ϴ�.  
[����](http://codepen.io/luensys/pen/YyBJdy)
```
<!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#gridSystemModal">
	Launch demo modal
</button>

<div id="gridSystemModal" class="modal fade" tabindex="-1" role="dialog" aria-labelledby="gridModalLabel" style="display: none;">
	<div class="modal-dialog" role="document">
		<div class="modal-content">
			<div class="modal-header">
				<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">��</span></button>
				<h4 class="modal-title" id="gridModalLabel">Modal title</h4>
			</div>
			<div class="modal-body">
				<div class="row">
					<div class="col-md-4">.col-md-4</div>
					<div class="col-md-4 col-md-offset-4">.col-md-4 .col-md-offset-4</div>
				</div>
				<div class="row">
					<div class="col-md-3 col-md-offset-3">.col-md-3 .col-md-offset-3</div>
					<div class="col-md-2 col-md-offset-4">.col-md-2 .col-md-offset-4</div>
				</div>
				<div class="row">
					<div class="col-md-6 col-md-offset-3">.col-md-6 .col-md-offset-3</div>
				</div>
				<div class="row">
					<div class="col-sm-9">
						Level 1: .col-sm-9
						<div class="row">
							<div class="col-xs-8 col-sm-6">
								Level 2: .col-xs-8 .col-sm-6
							</div>
							<div class="col-xs-4 col-sm-6">
							Level 2: .col-xs-4 .col-sm-6
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="modal-footer">
				<button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
				<button type="button" class="btn btn-primary">Save changes</button>
			</div>
		</div><!-- /.modal-content -->
	</div><!-- /.modal-dialog -->
</div><!-- /.modal -->
```

### Ʈ���� ��ư�� ��������� �پ��� ��� ������

�Ʒ��� ������ ��ư�� Ŭ���� �� �ش� ��ư�� ������� ��Ÿ���� ���â�� ���� �ٲپ��ִ� �����Դϴ�.
����� script�� ready�� ���� ���� �ܵ� ������������ �� �Լ��� ��� jQuery�� �����ϱ� �����Դϴ�.  
[����](http://codepen.io/luensys/pen/zvemeb)
```
<script>
	$(document).ready(function(){
		$('#exampleModal').on('show.bs.modal', function (event) {
		  var button = $(event.relatedTarget) // Button that triggered the modal
		  var recipient = button.data('whatever') // Extract info from data-* attributes
		  // If necessary, you could initiate an AJAX request here (and then do the updating in a callback).
		  // Update the modal's content. We'll use jQuery here, but you could use a data binding library or other methods instead.
		  var modal = $(this)
		  modal.find('.modal-title').text('New message to ' + recipient)
		  modal.find('.modal-body input').val(recipient)
		})
	});
</script>
<button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal" data-whatever="@mdo">Open modal for @mdo</button>
<button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal" data-whatever="@fat">Open modal for @fat</button>
<button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal" data-whatever="@getbootstrap">Open modal for @getbootstrap</button>
...more buttons...

<div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="exampleModalLabel">New message</h4>
      </div>
      <div class="modal-body">
        <form>
          <div class="form-group">
            <label for="recipient-name" class="control-label">Recipient:</label>
            <input type="text" class="form-control" id="recipient-name">
          </div>
          <div class="form-group">
            <label for="message-text" class="control-label">Message:</label>
            <textarea class="form-control" id="message-text"></textarea>
          </div>
        </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Send message</button>
      </div>
    </div>
  </div>
</div>

```

###�ڹٽ�ũ��Ʈ�� ����� ���
�ڹٽ�ũ��Ʈ�� ����Ͽ� ����� ���۽�ų �� �ֽ��ϴ�.
```
$("#myModal").modal();
```

�Ʒ��� �� ���� ����� �����Դϴ�.
�ٸ� ��� ������ ������ ����� ����ϴ� ���� �ڹٽ�ũ��Ʈ�� �����Ǿ� �ֽ��ϴ�.  
[����](http://codepen.io/luensys/pen/epxPXQ)
```
<div class="container">
  <h2>Activate Modal with JavaScript</h2>
  <!-- Trigger the modal with a button -->
  <button type="button" class="btn btn-info btn-lg" id="myBtn">Open Modal</button>

  <!-- Modal -->
  <div class="modal fade" id="myModal" role="dialog">
    <div class="modal-dialog">
    
      <!-- Modal content-->
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal">&times;</button>
          <h4 class="modal-title">Modal Header</h4>
        </div>
        <div class="modal-body">
          <p>Some text in the modal.</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
        </div>
      </div>
      
    </div>
  </div>
  
</div>

<script>
$(document).ready(function(){
    $("#myBtn").click(function(){
        $("#myModal").modal();
    });
});
</script>
```

### �̺�Ʈ ����

�Ʒ��� ������ ���� �̺�Ʈ�� �����ϴ� ����� �� �� �ֽ��ϴ�.
[����](http://codepen.io/luensys/pen/NGoOmw)

```
<div class="container">
  <h2>Modal Events - shown.bs.modal</h2>
  <!-- Trigger the modal with a button -->
  <button type="button" class="btn btn-info btn-lg" id="myBtn">Open Modal</button>

  <!-- Modal -->
  <div class="modal fade" id="myModal" role="dialog">
    <div class="modal-dialog">
    
      <!-- Modal content-->
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal">&times;</button>
          <h4 class="modal-title">Modal Header</h4>
        </div>
        <div class="modal-body">
          <p>The <strong>shown.bs.modal</strong> event occurs when the modal is fully shown.</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
        </div>
      </div>
      
    </div>
  </div> 
</div>
 
<script>
$(document).ready(function(){
  $("#myBtn").click(function(){
      $("#myModal").modal("show");
  });
      $("#myModal").on('show.bs.modal', function () {
          alert('The modal is about to be shown.');
  });
      $("#myModal").on('shown.bs.modal', function () {
          alert('The modal is fully shown.');
  });
});
</script>
```
������ ������� ����
show�� ��� ��� â�� ����Ǳ� ���� ��Ÿ���� ���� �� �� �ְ�,
shown�� ��� ��� â�� ����� �Ŀ� ��Ÿ���� ���� �� �� �ֽ��ϴ�.




