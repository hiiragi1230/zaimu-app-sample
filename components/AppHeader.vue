<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
      <div class="container-fluid">
        <h1 class="navbar-brand sticky-top p-3 font-weight-bold navbar-brand h1" href="#">財務会計システム</h1>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href=".">Home</a>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" to="#">各種メニュー</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" to="mypage">マイページ</NuxtLink>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#" tabindex="-1" aria-disabled="true">アカウント情報</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
</template>