<template>
  <aside class="list-group">
    <ul>
      <li><router-link to="/vi" class="list-group-item" exact>Lời mở đầu</router-link></li>
      <li><router-link to="/vi/about" class="list-group-item" exact>Giới thiệu</router-link></li>
    </ul>
    <div class="menu">
      <p class="menu-label">RL cơ bản</p>
      <ul class="menu-list">
        <li><router-link to="/vi/theorical/1" exact>DDPG</router-link></li>
        <li><router-link to="/vi/theorical/2" exact>TRPO/PPO</router-link></li>
        <li><router-link to="/vi/theorical/3" exact>SAC</router-link></li>
        <li><router-link to="/vi/theorical/3" exact>Inference</router-link></li>
      </ul>

      <p class="menu-label">RL luyện tập</p>
      <ul class="menu-list">
        <li><router-link to="/en/components/affix" exact>OpenAI Gym</router-link></li>
        <li><router-link to="/en/components/scrollto" exact>Q-learning</router-link></li>
        <li><router-link to="/en/components/breadcrumb" exact>DDPG</router-link></li>
        <li><router-link to="/en/components/breadcrumb" exact>TRPO/PPO</router-link></li>
        <li><router-link to="/en/components/breadcrumb" exact>SAC</router-link></li>
      </ul>

      <p class="menu-label">Thư viện RL</p>
      <ul class="menu-list">
        <li><router-link to="/en/components/alert" exact>OpenAI baselines</router-link></li>
        <li><router-link to="/en/components/aside" exact>Stable baselines</router-link></li>
        <li><router-link to="/en/components/collapse" exact>Ray/RLLib</router-link></li>
        <li><router-link to="/en/components/modal" exact>Unity ML-Agents</router-link></li>
      </ul>

      <p class="menu-label">Ứng dụng</p>
      <ul class="menu-list">
        <li><router-link to="/en/components/form" exact>Frew<i class="fas fa-angle-double-up" ></i>rd Env</router-link></li>
        <li><router-link to="/en/components/form2" exact>Frew<i class="fas fa-angle-double-up" ></i>rd Exp</router-link></li>
      </ul>
    </div>
  </aside>
</template>

<style scoped>
  .menu-list
  {
  font-size: 14px;
  color: black;
  }
</style>
