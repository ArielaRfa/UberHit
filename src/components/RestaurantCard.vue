<template>
  <div class="restaurant--card">
      <div class="restaurant--image"></div>
      <div class="restaurant--description">
        <div class="top">
          <p class="name">SubWay</p>
          <p class="note">
            <span>4.5</span>
          </p>
        </div>
        <P class="time">20-30min</P>
      </div>
  </div>
</template>

<script>
export default {
  name:"RestaurantCard",
}
</script>

<style lang="scss">
  .restaurant--card{
    width: 32%;
    height: 30vh;

    .restaurant--image{
      background-image: url("https://cn-geo1.uber.com/image-proc/resize/eats/format=webp/width=550/height=440/quality=70/srcb64=aHR0cHM6Ly9kMXJhbHNvZ25qbmczNy5jbG91ZGZyb250Lm5ldC8zNzg4MDJiMC1jNTI4LTQ4MjktYjBiNS0wY2M2NDBkZjYzY2QuanBlZw==");
      height: 70%;
      background-size: cover;
      background-position: center;
    }
    .restaurant--description{
      .top{
        margin: 10px 0;
        display:flex;
        align-items: center;
        justify-content: space-between;

        .note{
          background-color: #eeeeee;
          height: 30px;
          width: 30px;
          display: flex;
          align-items: center;
          justify-content: center;
          font-size: 0.9rem;
          border-radius: 50%;
        }
      }
      .time{
        font-size: 0.9rem;
      }
    }
    p{
      margin: 0px;
    }
  }
</style>