<template>
<div class="container">
  <div class="row mx-auto p-4">
    <div class="col-sm-6">
      <div class="card my-3" style="width: 18rem;">
      <div class="card-header">
      会社情報
      </div>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">
          <a class="nav-link" href="#">会社管理</a>
        </li>
        <li class="list-group-item">
          <a class="nav-link" href="#">ソフト管理</a>
        </li>
        <li class="list-group-item">
          <a class="nav-link" href="#">メンバー管理</a>
        </li>
      </ul>
      </div>
    </div>
    <div class="col-sm-6">
      <div class="card my-3" style="width: 18rem;">
      <div class="card-header">
      アカウント情報
      </div>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">
          <NuxtLink class="nav-link" href="/">ユーザー情報</NuxtLink>
        </li>
        <li class="list-group-item">
          <NuxtLink class="nav-link" href="/">パスワード変更</NuxtLink>
        </li>
        <li class="list-group-item">
          <NuxtLink class="nav-link" href="/">メールアドレス変更</NuxtLink>
        </li>
        <li class="list-group-item">
          <NuxtLink class="nav-link" href="/">アカウント解約</NuxtLink>
        </li>
      </ul>
      </div>
    </div>
    </div>
  </div>
</template>