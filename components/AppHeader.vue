<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
      <div class="container-fluid">
        <img src="/homo.png" style="width: 6rem;">
        <a class="navbar-brand sticky-top p-3 font-weight-bold navbar-brand h1" href="#">財務会計システム</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <NuxtLink class="nav-link active" aria-current="page" href=".">Home</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" to="/">各種メニュー</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" to="mypage">マイページ</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" href="/" tabindex="-1" aria-disabled="true">アカウント情報</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </nav>
</template>