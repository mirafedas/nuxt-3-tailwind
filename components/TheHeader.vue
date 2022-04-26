<template>
  <header class="flex flex-col text-sm">
    <div
      class="flex flex-row justify-between px-28 py-2 bg-zinc-700 text-slate-300"
    >
      <ul class="flex">
        <li class="flex items-center mr-2">
          <i class="material-icons mr-2 text-sm">mail_outline</i>
          <a href="mailto:kontakt@sklepjogina.pl">kontakt@sklepjogina.pl</a>
        </li>
        <li class="flex items-center border-l-2 border-solid border-black pl-2">
          <i class="material-icons mr-2 text-sm">chat_bubble_outline</i>
          <a href="tel:785036025">+48 789 729 739</a>
        </li>
      </ul>
      <ul class="flex">
        <li class="flex items-center mr-6">
          <i class="material-icons mr-2 text-sm">lock_outline</i>
          <a href="/pl/reg" title="Zarejestruj się" class="register">
            <span>Zarejestruj się</span>
          </a>
        </li>
        <li class="flex items-center">
          <i class="material-icons mr-2 text-sm">person_outline</i>
          <a href="/pl/login" title="Zaloguj się" class="login">
            <span>Zaloguj się</span>
          </a>
        </li>
      </ul>
    </div>
    <div>
      <a href="/">
        <img
          src="https://sklepjogina.pl/skins/store_user/store_51530cb51aa33584410334a776d96a81_3/images/logo.png"
          alt="logo sklepu"
        />
      </a>
    </div>
  </header>
</template>
