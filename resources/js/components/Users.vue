<template>
    <div class="container">
        <div class="col-md-12 justify-content-center">
            <div class="card">
                <div class="card-header">
                    <h4 class="card-title">Managment Users</h4>
                    <div class="card-tools">
                        <div class="input-group input-group-sm" >
                            <div class="input-group-append">
                                <button type="submit" class="btn btn-success rounded" data-toggle="modal" data-target="#AddNewUser"> Add User <i class="fas fa-user-plus"></i> </button>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- /.card-header -->
                <div class="card-body table-responsive p-0">
                    <table class="table table-hover">
                        <thead>
                            <tr class="bg-light">
                                <th>ID</th>
                                <th>name</th>
                                <th>email</th>
                                <th>Type</th>
                                <th>Edit</th>
                            </tr>
                        </thead>
                        <tbody>
                             <tr>
                                <th>20161810</th>
                                <th>Hossam </th>
                                <th>hosasmhsb96@gmail.com</th>
                                <th>user</th>
                                <th>
                                    <button class="btn btn-sm text-light btn-outline btn-danger">
                                        <i class="fas fa-eraser"></i>
                                    </button>
                                    <button class="btn btn-outline text-light btn-sm btn-info">
                                        <i class="fas fa-user-edit"></i>
                                    </button>
                                </th>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <!-- /.card-body -->
            </div>
            <!-- /.card -->
        </div>

        <!-- Modal To Add New User -->
        <!-- Modal -->
        <div class="modal fade" id="AddNewUser" tabindex="-1" role="dialog" aria-labelledby="AddNewUser" aria-hidden="true">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title" id="AddNewUser"><i class="fas fa-user-plus text-primary"></i> &nbsp; Add New User</h5>
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">&times;</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        ...
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                        <button type="button" class="btn btn-primary">Add User <i class="fas fa-user-plus text-light"></i>  </button>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
