<template>
  <header class="flex flex-col bg-black text-white">
    <div class="flex flex-row justify-between bg-black p-2">
      <ul class="flex">
        <li class="flex items-center mr-2">
          <i class="material-icons mr-2">mail_outline</i>
          <a href="mailto:kontakt@sklepjogina.pl">kontakt@sklepjogina.pl</a>
        </li>
        <li
          class="flex items-center border-l-2 border-solid border-gray-400 pl-2"
        >
          <i class="material-icons mr-2">chat_bubble_outline</i>
          <a href="tel:785036025">+48 789 729 739</a>
        </li>
      </ul>
      <ul class="flex">
        <li class="flex items-center mr-6">
          <a href="/pl/reg" title="Zarejestruj się" class="register">
            <i class="material-icons">lock_outline</i>
            <span>Zarejestruj się</span>
          </a>
        </li>
        <li class="flex items-center">
          <a href="/pl/login" title="Zaloguj się" class="login">
            <i class="material-icons">person_outline</i>
            <span>Zaloguj się</span>
          </a>
        </li>
      </ul>
    </div>
  </header>
</template>
