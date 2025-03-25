<template>
    <section class="hero">
      <div class="hero-content">
        <h1>შეცვალე მომავალი, გახდი გმირი დღეს!</h1>
        <p>
            შეუერთდით ცვლილებების საზოგადოებას და მხარი დაუჭირეთ ჩვენს მისიას, მოვიზიდოთ სახსრები მათთვის ვისთვისაც ეს სასიცოცხლოდ მნიშვნელოვანია.
        </p>
        <div class="hero-buttons">
          <button class="primary-btn">დაიწყე ახლა</button>
          <button class="outlined-btn">▶ როგორ მუშაობს?</button>
        </div>
      </div>
    </section>
  </template>
  
  <style scoped lang="scss">
  .hero {
    background: linear-gradient(to bottom, #ffffff, #f9f9ff);
    padding: 4rem 1rem;
    display: flex;

  
    .hero-content {
      max-width: 635px;
  
      h1 {
        text-align: left;
        color: var(--Text-500, #0A0A0A);
        font-family: "Noto Sans Georgian";
        font-size: 54px;
        font-style: normal;
        font-weight: 700;
        line-height: 80px; 
        letter-spacing: -1px;
      }
  
      p {
        font-family: "Noto Sans Georgian";
        font-size: 18px;
        font-style: normal;
        font-weight: 400;
        text-align: left;
        line-height: 28px;
        color: #666;
        font-size: 1rem;
        margin-bottom: 2rem;
        line-height: 1.6;
      }
  
      .hero-buttons {
        display: flex;
        gap: 16px;
        flex-wrap: wrap;
  
        .primary-btn {
          background-color: #6c63ff;
          color: #fff;
          padding: 0.7rem 1.8rem;
          font-size: 1rem;
          border-radius: 25px;
          border: none;
          font-weight: 500;
          cursor: pointer;
        }
  
        .outlined-btn {
          background: white;
          border: 2px solid #1a1a1a;
          color: #1a1a1a;
          padding: 0.7rem 1.6rem;
          font-size: 1rem;
          border-radius: 25px;
          font-weight: 500;
          cursor: pointer;
          display: flex;
          align-items: center;
          gap: 0.5rem;
        }
      }
    }
  }
  </style>
  