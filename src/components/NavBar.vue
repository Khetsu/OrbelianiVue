<template>
  <nav class="navbar">
    <div class="navbar-left">
      <div class="logo">
        <img src="/src/assets/photos/orbeliani_logo.png" alt="Logo">
      </div>
      <ul class="menu">
        <li>გაცანი იდეებს <span>▾</span></li>
        <li>მეტი ჩვენზე <span>▾</span></li>
        <li>აქციები <span>▾</span></li>
        <li>განვითარება</li>
      </ul>
    </div>

    <div class="navbar-right">
      <div class="logo-search">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M21 21L17.5001 17.5M20 11.5C20 16.1944 16.1944 20 11.5 20C6.80558 20 3 16.1944 3 11.5C3 6.80558 6.80558 3 11.5 3C16.1944 3 20 6.80558 20 11.5Z" stroke="#1D1E1E" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/>
</svg>

      </div>
      <button class="primary-btn">პროექტის დაწყებაა</button>
      <button class="outlined-btn">შესვლა</button>
      <div class="earth">
        <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
<g clip-path="url(#clip0_5201_5259)">
<path d="M10 1.66675C12.0844 3.94871 13.269 6.91011 13.3334 10.0001C13.269 13.0901 12.0844 16.0515 10 18.3334M10 1.66675C7.91562 3.94871 6.73106 6.91011 6.66669 10.0001C6.73106 13.0901 7.91562 16.0515 10 18.3334M10 1.66675C5.39765 1.66675 1.66669 5.39771 1.66669 10.0001C1.66669 14.6025 5.39765 18.3334 10 18.3334M10 1.66675C14.6024 1.66675 18.3334 5.39771 18.3334 10.0001C18.3334 14.6025 14.6024 18.3334 10 18.3334M2.08337 7.50008H17.9167M2.08335 12.5001H17.9167" stroke="#0A0A0A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
</g>
<defs>
<clipPath id="clip0_5201_5259">
<rect width="20" height="20" fill="white"/>
</clipPath>
</defs>
</svg>
      </div>
      <span class="lang">ქარ</span>
    </div>
  </nav>
</template>

<style scoped lang="scss">
.logo-search{
  margin-left: 50px;
  margin-right: 16px;
}
.navbar {
  display: flex;
  background-color: #fff;
  display: flex;
  justify-content: space-between;


  .navbar-left {
    display: flex;
    align-items: center;
    gap: 56px;


    .menu {
      display: flex;
      list-style: none;
      gap: 32px;

      li {
        font-family: "Noto Sans Georgian";
        font-size: 15px;
        font-style: normal;
        font-weight: 500;
        color: #1a1a1a;
        cursor: pointer;
        display: flex;
        align-items: center;
        gap: 32px;

        span {
          font-size: 0.7rem;
        }
      }
    }
  }

  .navbar-right {
    display: flex;
    align-items: center;
    gap: 0.8rem;

    .icon-btn {
      background: none;
      border: none;
      font-size: 1.1rem;
      cursor: pointer;
      color: #1a1a1a;
    }

    .primary-btn {
      background-color: #6c63ff;
      color: white;
      border: none;
     
      font-size: 0.85rem;
      border-radius: 20px;
      cursor: pointer;
      font-weight: 500;
    }

    .outlined-btn {
      background: white;
      border: 1px solid #6c63ff;
      color: #6c63ff;
      font-size: 0.85rem;
      border-radius: 20px;
      cursor: pointer;
      font-weight: 500;
    }

    .icon {
      color: #1a1a1a;
      cursor: pointer;
    }

    .lang {
      font-size: 0.9rem;
      font-weight: 500;
      color: #1a1a1a;
    }
  }
}
</style>
