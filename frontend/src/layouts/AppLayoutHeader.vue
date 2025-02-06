<template>
  <header class="header">
    <div class="header__logo">
      <a href="#" class="logo">
        <img
          src="@/assets/img/logo.svg"
          alt="VueWork logo"
          width="147"
          height="23"
        />
      </a>
    </div>

    <form action="#" class="header__search">
      <input type="search" name="search" required placeholder="Поиск" />
      <button type="submit">Найти</button>
    </form>
    <!-- New task creation button -->
    <a href="#" class="header__create-task">Создать карточку</a>
    <!-- User's avatar -->
    <a href="#" class="header__user">
      <img
        src="@/assets/img/admin.jpg"
        alt="Администратор"
        width="40"
        height="40"
      />
    </a>
    <!-- User's bar -->
    <div class="header__menu">
      <div class="user-menu">
        <img
          src="@/assets/img/admin.jpg"
          alt="Администратор"
          width="56"
          height="56"
        />
        <span>Администратор</span>
        <a href="#" class="user-menu__link">Мой аккаунт</a>
        <a href="#" class="user-menu__link">Выйти</a>
      </div>
    </div>
  </header>
</template>
