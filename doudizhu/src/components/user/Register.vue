<template>
	<el-row>
			<el-col :span="4">&nbsp;</el-col>
			<el-col :span="16" style='align-content: center;border:1px solid #99a9bf;padding: 21px;'>
				<el-form ref="form">
					<el-form-item style='text-align: center;margin:0px;'>
						注册
					</el-form-item>
				  <el-form-item >
				    <el-input placeholder="请输入email" class='elInputClass'></el-input>
				    <el-input placeholder="请输入密码" type='password' class='elInputClass'></el-input>
				    <el-input placeholder="请再次输入密码" type='password' class='elInputClass'></el-input>
				    <el-input placeholder="请输入昵称" class='elInputClass'></el-input>
				  </el-form-item>
				  <el-form-item style='text-align: center'>
				    <el-button type="primary">注册</el-button>
				    <router-link to="/">
				    	<el-button>返回登陆</el-button>
				    </router-link>
				  </el-form-item>
				</el-form>
			</el-col>
			<el-col :span="4">&nbsp;</el-col>
		</el-row>
</template>
<style>
	.elInputClass{
		margin-bottom:15px;
	}
</style>