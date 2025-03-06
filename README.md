



<div class="content-wrapper">
    <section class="content-header">
        <h1>
            Administrar Usuarios
        </h1>
        <ol class="breadcrumb">
            <li><a href="#"><i class="fa fa-dashboard"></i> inicio</a></li>
            <li class="active">Administrar Usuarios</li>
        </ol>
    </section>

<section class="content">
        <div class="box">
            <div class="box-header with-border">
                <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#modalAgregarUsuario">
                    Agregar Usuario
                </button>
            </div>
            <div class="box-body">
                <table class="table table-bordered table-striped dt-responsive tablas" width="100%">
                    <thead>
                        <tr>
                            <th style="text-align: center; width: 50px;"><i class="fa fa-caret-square-o-right"> #</i></th>
                            <th style="text-align: center;"><i class="fa fa-user"> Nombre</i></th>
                            <th style="text-align: center;"><i class="fa fa-user-secret"> Usuario</i></th>
                            <th style="text-align: center;"><i class="fa fa-users"> Perfil</i></th>
                            <th style="text-align: center;"><i class="fa fa-sticky-note"> Estado</i></th>
                            <th style="text-align: center;"><i class="fa fa-sticky-note"> Grado</i></th>
                            <th style="text-align: center;"><i class="fa fa-gears"> Acciones</i></th>
                        </tr>
                    </thead>
                    <tbody>
                        
</tbody>
                </table>
            </div>
        </div>
    </section>
</div>

<div id="modalAgregarUsuario" class="modal fade" role="dialog">

<div class="modal-dialog">

<div class="modal-content">


<form role="form" method="post" enctype="multipart/form-data">

              
<div class="modal-header" style="background:#3c8dbc; color:white">

<button type="button" class="close" data-dismiss="modal">&times;</button>

<h4 class="modal-title">Agregar Usuario</h4>

</div>


<div class="modal-body">
                        <div class="box-body">


<div class="form-group">

<div class="input-group">

<span class="input-group-addon"><i class="fa fa-user"></i></span>

<input type="text" class="form-control input-lg" name="nuevoNombre"
                                        placeholder="Ingresar Nombre" required>

</div>
</div>


<div class="form-group">

<div class="input-group">

<span class="input-group-addon"><i class="fa  fa-user-secret"></i></span>

<input type="text" class="form-control input-lg" name="nuevoUsuario"
                                        placeholder="Ingresar Usuario" id="nuevoUsuario" required>

</div>

</div>



<div class="form-group">

<div class="input-group">

<span class="input-group-addon"><i class="fa fa-key"></i></span>

<input type="password" class="form-control input-lg" name="nuevoPassword"
                                        placeholder="Ingresar Contraseña" required>

</div>

</div>


<div class="form-group">

<div class="input-group">
                                    <span class="input-group-addon"><i class="fa fa-users"></i></span>
                                    <select class="form-control input-lg" name="nuevoPerfil">
                                       <option value="">Selecionar Perfil</option>

<option value="Administrador">Administrador</option>
                                        <option value="Especial">Especial</option>
                                        <option value="Vendedor">Vendedor</option>
                                    </select>
                                </div>
                            </div>
                    </div>
                    </div>
                   <div class="modal-footer">
                        <button type="button" class="btn btn-default pull-left" data-dismiss="modal">Salir</button>
                        <button type="reset" class="btn btn-default pull-left" data-dismiss="">Limpiar</button>
                        <button type="submit" class="btn btn-primary">Guardar Usuario</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
