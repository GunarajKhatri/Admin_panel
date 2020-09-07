<template>
	<div>
	<div class="login-box">
  <div class="login-logo">
    <a href="#"><b>Admin</b>Login</a>
  </div>
  <div class="login-box-body">
    <p class="login-box-msg">Sign in to start your session</p>
      <div class="form-group">
        <input type="email" class="form-control" placeholder="Email">
      </div>
      <div class="form-group">
        <input type="password" class="form-control" placeholder="Password">
      </div>
      <div class="row">
        <div class="col-xs-8">
          <div class="checkbox icheck form-group">
            <label>
              <input type="checkbox"> Remember Me
            </label>
          </div>
        </div>
        <!-- /.col -->
        <div class="col-xs-4">
          <button type="submit" class="btn btn-primary btn-block btn-flat">Sign In</button>
        </div>
      </div>

    <a href="#" class="fpass">I forgot my password</a>

  </div>
</div>
</div>
</template>
<script>
	
export default {
  name: 'login'
}

</script>

<style scoped>
.login-logo{
  font-size: 35px;
  text-align: center;
  margin-bottom: 25px;
  font-weight: 300;
}
.login-logo a{
  color:#444;
}
.login-box{
  width: 360px;
  margin: 7% auto;
}
@media (max-width: 768px) {
  .login-box{
    width: 90%;
    margin-top: 20px;
  }
}
.login-box-body {
  background: #fff;
  padding: 20px;
  border-top: 0;
  color: #666;
}
.login-box-msg{
  margin: 0;
  text-align: center;
  padding: 0 20px 20px 20px;
}
.icheck > label {
  padding-left: 0;
  margin-left:14px;

}
.btn.btn-flat {
  border-radius: 0;
  -webkit-box-shadow: none;
  -moz-box-shadow: none;
  box-shadow: none;
  border-width: 1px;
  margin-left:63px;

}
.fpass{
	text-decoration:none;
	font-size:15px;
}

</style>
