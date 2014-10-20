---
layout: standard
title: Equipo MediaFranca
active: equipo
---
<div class='container'>
	{% include nav-pages.html %}
</div>

# {{ page.title }}


<form role="form" action="http://getsimpleform.com/messages?form_api_token=5d10aa4f599a65850aa0de859b5330f5" method="post">
<!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
<input type='hidden' name='redirect_to' value='http://mediafranca.github.io/pags/gracias' />
<!-- all your input fields here.... -->
<div class="form-group">
	<label for="name1" class="control-label">Nombre</label>
	<input type="text" class="form-control" id='name1' name='name' placeholder="tu nombre y apellido, por favor">

</div>
<div class="form-group">
	<label for="message1" class="control-label">Mensaje</label>
	<textarea id='message1' name='message' class='form-control' placeholder='cuéntanos...'></textarea>
	<input type='submit' id='' class='btn btn-primary' value='Enviar'>
</div>
</form>


<div class='row'>
	<div class='col-md-4'>
		<div class='well'>
			<h3>Herbert Spencer</h3>
			<span class='label label-primary'><a href="http://twitter.com/hspencer"><i class='fa fa-twitter'></i> @hspencer</a></span>
			<p class='air-top'>Diseñador de Interacción y Profesor de Diseño, e[ad] Escuela de Arquitectura y Diseño PUCV</p>
		</div>
	</div>
	<div class='col-md-4'>
		<div class='well'>
			<h3>Francisco Vera</h3>
			<span class='label label-primary'><a href="http://twitter.com/pancho_vm"><i class='fa fa-twitter'></i> @pancho_vm</a></span>
			<p class='air-top'>Diseñador e[ad] Escuela de Arquitectura y Diseño PUCV, Jefe de Diseño en AyerViernes</p>
		</div>
	</div>
	<div class='col-md-4'>
		<div class='well'>
			<h3>Rodrigo Moya</h3>
			<span class='label label-primary'><a href="http://twitter.com/rodrigomoya"><i class='fa fa-twitter'></i> @rodrigomoya</a></span>
			<p class='air-top'>Arquitecto de Software y Desarrollador independiente</p>
		</div>
	</div>
</div>