<template>
  <div class="authorization-success">
    <h1>这里是任务工单管理系统，欢迎您</h1>
    <p style="font-size: 30px"><span class="emoji">&#x1F389;</span> 感谢您使用我们的服务 <span class="emoji">&#x1F389;</span></p>
  </div>
</template>

<script>
export default {
  name: 'Index'
}
</script>

<style>
.authorization-success {
  font-family: Arial, sans-serif;
  font-size: 16px;
  color: #333;
  /* background-color: #f8f8f8; */
  text-align: center;
  margin-top: 150px;
}

h1 {
  font-size: 36px;
  margin-bottom: 20px;
  color: #007bff;
  text-shadow: 2px 2px #f8f8f8;
}

p {
  margin-bottom: 20px;
  color: #555;
  font-size: 24px;
  letter-spacing: 1px;
}

.emoji {
  display: inline-block;
  animation: emoji 1s infinite;
}

@keyframes emoji {
  0% {
    transform: translateY(0);
  }

  50% {
    transform: translateY(-10px);
  }

  100% {
    transform: translateY(0);
  }
}
</style>