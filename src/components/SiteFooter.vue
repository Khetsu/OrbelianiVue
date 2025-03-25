<template>
    <footer class="site-footer">
      <div class="footer-top">
        
        <div class="footer-block">
          <img src="/src/assets/photos/orbeliani_logo.png" alt="Logo">
          <div class="social-icons">
            
            <a href="#"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
<circle cx="20" cy="20" r="19.5" fill="white" stroke="#ECEFF1"/>
</svg>
</a>
            <a href="#"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
<circle cx="20" cy="20" r="19.5" fill="white" stroke="#ECEFF1"/>
</svg>
</a>
            <a href="#"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
<circle cx="20" cy="20" r="19.5" fill="white" stroke="#ECEFF1"/>
</svg>
</a>
            <a href="#"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
<circle cx="20" cy="20" r="19.5" fill="white" stroke="#ECEFF1"/>
</svg>
</a>
          </div>
          <p class="social-label">გამოიწერე სოციალური ქსელებში</p>
        </div>
  
       
        <div class="footer-block">
          <h4>მეტი ჩვენზე</h4>
          <ul>
            <li><a href="#">ჩვენს შესახებ</a></li>
            <li><a href="#">სასწავლო</a></li>
          </ul>
        </div>
  
        <div class="footer-block">
          <h4>მომხმარებლისთვის</h4>
          <ul>
            <li><a href="#">კითხვა-პასუხი</a></li>
            <li><a href="#">ბლოგი</a></li>
          </ul>
        </div>
  
     
        <div class="footer-block">
          <h4>კონტაქტი</h4>
          <ul>
            <li>
              <span>📧</span> office@orbeliani.net
            </li>
            <li>
              <span>📍</span> ჯავახიშვილის გამზირი N37, თბილისი
            </li>
          </ul>
        </div>
      </div>
  
      <div class="footer-bottom">
        <p>© 2022 Orbelianimeti ყველა უფლება დაცულია</p>
        <div class="links">
          <a href="#">წესები & პირობები</a>
          <a href="#">კონფიდენციალურობა</a>
        </div>
      </div>
    </footer>
  </template>
  
  <style scoped lang="scss">
  .site-footer {
    background: #fff;
    border-top: 1px solid #eee;
    padding: 2rem 2rem 1rem;
    font-size: 15px;
    color: #222;
  
    .footer-top {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 2rem;
      margin-bottom: 2rem;
  
      .footer-block {
        min-width: 180px;
  
        h3 {
          font-size: 1.6rem;
          font-weight: 800;
          margin-bottom: 0.5rem;
        }
  
        h4 {
          font-size: 1rem;
          font-weight: 700;
          margin-bottom: 0.8rem;
        }
  
        ul {
          list-style: none;
          padding: 0;
          margin: 0;
  
          li {
            margin-bottom: 0.5rem;
  
            a {
              text-decoration: none;
              color: #222;
  
              &:hover {
                text-decoration: underline;
              }
            }
          }
        }
  
        .social-icons {
          display: flex;
          gap: 0.5rem;
          margin: 0.5rem 0;
  
          a {
            display: flex;
    
            width: 40px;
            height: 40px;
            
          
          }
        }
  
        .social-label {
          font-size: 0.85rem;
          color: #555;
        }
      }
    }
  
    .footer-bottom {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      border-top: 1px solid #eee;
      padding-top: 1rem;
      font-size: 15px;
      color: #555;
  
      .links {
        display: flex;
        gap: 1rem;
  
        a {
          text-decoration: none;
          color: #555;
  
          &:hover {
            text-decoration: underline;
          }
        }
      }
    }
  }
  </style>
  