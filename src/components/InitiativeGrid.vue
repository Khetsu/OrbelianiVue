<template>
    <section class="initiative-section">
      <div class="section-header">
        <div class="shine-icon">
          <svg width="104" height="104" viewBox="0 0 104 104" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M52 104C50.1479 97.5039 45.2946 83.8183 32.7386 71.2629C20.1826 58.7027 6.49169 53.8543 0 51.9976C6.34922 50.3973 19.589 46.1473 31.8648 34.4894C45.6935 21.3594 50.3996 6.32994 52 0C52.1995 0.569837 52.4226 1.18241 52.6648 1.82823C55.6709 9.79645 62.1531 23.3728 75.6351 35.3631C86.2393 44.7939 97.0287 49.5663 104 51.9976C96.815 54.5571 83.5609 60.3505 71.2566 73.0104C59.8974 84.7015 54.5074 96.9483 51.9953 104H52Z" fill="#FAA11D"/>
</svg>

        </div>
        <div class="titles">
          <h2>წამოიწყე ინიციატივა</h2>
          <p>გაგვიზიარე შენი იდეა, რომ მეტი სასიკეთო ცვლილება მოვახდინოთ ერთად!</p>
        </div>
      </div>
  
      <div class="card-grid">
        <div class="card" v-for="n in 6" :key="n">
          <div class="icon">
            <!-- Replace with your inline SVG icon -->
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M18.5 11.5V6H20V11.5C20 11.9142 19.6642 12.25 19.25 12.25C18.8358 12.25 18.5 11.9142 18.5 11.5Z" fill="#6C68E1"/>
<path d="M16 10V7H8V10C8 12.2091 9.79086 14 12 14C14.2091 14 16 12.2091 16 10Z" fill="#6C68E1"/>
<path d="M4.02804 5.54334L10.7816 2.54177C11.5573 2.19701 12.4427 2.19701 13.2184 2.54177L19.972 5.54334C20.3679 5.7193 20.3679 6.2812 19.972 6.45716L13.2184 9.45873C12.4427 9.80349 11.5573 9.80349 10.7816 9.45873L4.02804 6.45716C3.63213 6.2812 3.63213 5.7193 4.02804 5.54334Z" fill="#6C68E1"/>
<path d="M14.2996 15.3999L12.711 17.0062C12.3196 17.4019 11.6804 17.4019 11.289 17.0062L9.70045 15.3999C9.45505 15.1517 9.09681 15.046 8.762 15.1444C5.95686 15.9693 4 17.8332 4 20.0003C4 21.1049 4.89543 22.0003 6 22.0003H18C19.1046 22.0003 20 21.1049 20 20.0003C20 17.8332 18.0431 15.9693 15.238 15.1444C14.9032 15.046 14.5449 15.1517 14.2996 15.3999Z" fill="#6C68E1"/>
</svg>
          </div>
          
          
          <div class="text">
            <h3>განათლება {{ n }}</h3>
            <p>ორბელიანი მეტი დაეხმარე გარემოს სახსრების მოზიდვაში</p>
          </div>
          <div class="arrow">↗</div>
        </div>
      </div>
    </section>
  </template>
  
  <style scoped lang="scss">
  .initiative-section {
    background: #1e1e1e;
    border-radius: 16px;
    text-align: center;
    display: flex;
    padding: 24px;
    flex-direction: column;
    align-items: flex-start;
    gap: 18px;
    align-self: stretch;
  
    .section-header {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 1rem;
      flex-wrap: wrap;
      margin-bottom: 2rem;
  
      .shine-icon {
        background: transparent;
      }
  
      .titles {
        h2 {
            color: var(--Text-50, #FFF);
            font-family: "Noto Sans Georgian";
            font-size: 44px;
            font-style: normal;
            font-weight: 700;
            line-height: 56px; 
            text-align: left;
        }
  
        p {
          font-size: 1rem;
          color: #e2e2e2;
          margin-top: 0.3rem;
        }
      }
    }
  
    .card-grid {
      display: grid;
      gap: 1.5rem;
      grid-template-columns: repeat(3, 1fr);
  
      .card {
        background: white;
        color: #1e1e1e;
        border-radius: 16px;
        padding: 1.2rem;
        display: flex;
        flex-direction: column;
        gap: 1rem;
        text-align: left;
        position: relative;
  
        .icon {
          width: 40px;
          height: 40px;
          background: #f2efff;
          border-radius: 12px;
          display: flex;
          align-items: center;
          justify-content: center;
        }
  
        .text {
          h3 {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            flex: 1 0 0;
          }
  
          p {
            color: var(--Text-400, #1D1E1E);
            font-family: "Noto Sans Georgian";
            font-size: 14px;
            font-style: normal;
            font-weight: 400;
            line-height: 20px;
          }
        }
  
        .arrow {
          position: absolute;
          top: 1rem;
          right: 1rem;
          font-size: 1rem;
          color: #333;
        }
      }
    }
  }
  </style>
  