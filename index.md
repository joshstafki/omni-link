---
layout: default
title: Josh Stafki
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Papyrus&display=swap');

  body {
    background: linear-gradient(to bottom right, #6a11cb, #2575fc);
    font-family: 'Papyrus', 'Comic Sans MS', cursive, sans-serif;
    text-align: center;
    padding-top: 50px;
    color: #ffffff;
    overflow-x: hidden;
  }

  .profile-container {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    animation: moveToTopLeft 2s ease-in-out 2s forwards;
    z-index: 10;
  }

  @keyframes moveToTopLeft {
    to {
      top: 20px;
      left: 20px;
      transform: translate(0, 0);
    }
  }

  img.profile {
    width: 220px;
    height: 220px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
  }

  .link-group {
    font-size: 20px;
    line-height: 3.5;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 300px;
  }

  .link-group a {
    display: flex;
    align-items: center;
    gap: 12px;
    text-decoration: none;
    color: #ffffff;
    opacity: 0;
    transform: translateY(20px);
    animation: fadeInUp 1s forwards;
  }

  .link-group a:nth-child(1) {
    animation-delay: 3s;
    transform: translateX(-100%);
    animation-name: slideInLeft;
  }

  .link-group a:nth-child(2) {
    animation-delay: 3.2s;
    transform: translateY(-100%);
    animation-name: slideInDown;
  }

  .link-group a:nth-child(3) {
    animation-delay: 3.4s;
    transform: translateX(100%);
    animation-name: slideInRight;
  }

  .link-group a:nth-child(4) {
    animation-delay: 3.6s;
    transform: rotate(-360deg) scale(0);
    animation-name: spinIn;
  }

  .link-group a:nth-child(5) {
    animation-delay: 3.8s;
    transform: translateY(100%);
    animation-name: slideInUp;
  }

  .link-group a:nth-child(6) {
    animation-delay: 4s;
    transform: scale(0);
    animation-name: zoomIn;
  }

  @keyframes slideInLeft {
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }

  @keyframes slideInRight {
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }

  @keyframes slideInDown {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes slideInUp {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes spinIn {
    to {
      opacity: 1;
      transform: rotate(0deg) scale(1);
    }
  }

  @keyframes zoomIn {
    to {
      opacity: 1;
      transform: scale(1);
    }
  }

  .link-group img.icon {
    width: 30px;
    height: 30px;
    object-fit: contain;
    border-radius: 6px;
  }
</style>

<div class="profile-container">
  <img src="https://raw.githubusercontent.com/joshstafki/omni-link/refs/heads/main/IMG_9828.jpeg" alt="Josh Stafki Profile" class="profile"/>
</div>

<div class="link-group">

  <a href="https://www.instagram.com/joshstafki?igsh=emQ3YWplM2ZneTFz&utm_source=qr" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/174/174855.png" class="icon" alt="Instagram Logo"/> @joshstafki
  </a>

  <a href="https://x.com/joshstafki?s=21" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/53/X_logo_2023.svg" class="icon" alt="X Logo"/> @joshstafki
  </a>

  <a href="https://open.spotify.com/user/31coy7zzjdxsugr3i3dlcxx4whsu?si=Wz6ICs4bTZm8EGK3yffzEA" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/174/174872.png" class="icon" alt="Spotify Logo"/> Astønautik
  </a>

  <a href="https://www.intrepidflights.com" target="_blank">
    <img src="https://lh3.googleusercontent.com/p/AF1QipPtHd6cUt0YyHZs3-K4_LlGuO-HjPDYltm3ma5P=w170-h213-n-k-no-nu" class="icon" alt="Intrepid Flights Logo"/> Intrepid Flights Photography
  </a>

  <a href="https://notary.sos.mn.gov/Notary/NotaryDetails?notaryMasterId=b1b201ad-7a3b-ee11-9076-00155d01c440" target="_blank">
    <img src="https://www.sos.mn.gov/media/yfyadhpm/seal_1c_blk_outlined-final2024.png" class="icon" alt="Notary Logo"/> MN Notary 
