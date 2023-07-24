<template>

<!-- header -->
<header id="header"><div class="logoArea">
	<div class="logoImg"><span style="font-size: 30px;color: white;" class="glyphicon glyphicon-education"></span></div>
	<h1 class="logoTxt"><span>ビックエンジニアグループ</span>hogehoge</h1>
</div>
</header>
<!-- main -->
<div class="container-fluid login-wrapper">
  <div class="row">
    <div class="col-sm-4 hidden-xs"></div>
    <div class="col-sm-4">
		<div class="panel panel-default login_form_wrap" style="display: block;">
		  <div class="panel-heading"><h4 class="pageTtl"><span class="glyphicon glyphicon glyphicon-user"></span> <span id="login_panel_name">ログイン</span></h4></div>
		  <div class="panel-body">
			<form id="login_form">
		      <div class="row">
				  <div class="form-group errPosRight">
				    <label class="hidden-xs" for="user_id">ログインID</label>
				    <input type="email" class="form-control chkrequired errPosRight after" id="user_id" name="user_id" placeholder="ログインID"><div id="err_user_id" class="formError userformError form_login_form fixed" style="display: none;"><div class="formErrorMsg formErrorContent"></div><div class="formErrorArrow"><div class="line10"></div><div class="line9"></div><div class="line8"></div><div class="line7"></div><div class="line6"></div><div class="line5"></div><div class="line4"></div><div class="line3"></div><div class="line2"></div><div class="line1"></div></div><span class="formErrorClose">×</span></div>
				</div>
				  <div class="form-group errPosRight">
				    <label class="hidden-xs" for="user_pass">パスワード</label>
				    <input type="password" class="form-control chkrequired errPosRight after" id="user_pass" name="user_pass" placeholder="パスワード">
                    <div id="err_user_pass" class="formError userformError form_login_form fixed" style="display: none;">
                        <div class="formErrorMsg formErrorContent"></div><div class="formErrorArrow"><div class="line10">
                        </div>
                        <div class="line9"></div>
                        <div class="line8"></div>
                        <div class="line7"></div>
                        <div class="line6"></div>
                        <div class="line5"></div>
                        <div class="line4"></div>
                        <div class="line3"></div>
                        <div class="line2"></div>
                        <div class="line1"></div>
                    </div><span class="formErrorClose">×</span></div>
				  </div>
				  <div class="checkbox errPosRight">
				    <label>
				      <input id="save_check" name="save_check" type="checkbox" class="errPosRight"><p>ログイン情報を記憶</p>
				    </label>
				  </div>
		          <div class="form-group text-center errPosRight">
					  <button type="button" class="btn btn-primary form-control" id="login_b">ログイン</button>
		          </div>
		      </div>
			</form>
		  </div>
		</div>
  </div>
  <div class="col-sm-4 hidden-xs"></div>
  </div>
</div>
<footer id="footer">kari hogehoge</footer>


</template>