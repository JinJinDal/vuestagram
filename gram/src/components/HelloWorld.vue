<template>
  <div class="allpage">
    <div class="content-contenier">
      <div class="img"></div>
      <div class="chat">
        <div>💬</div>
      </div>
      <div class="text">글</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.allpage{
  .content-contenier{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    .img{
      background: rgba(0, 0, 0,1);
      width: 100%;
      height: 250px;
    }
    .chat{
      >div{
        margin-left: 1rem;
      }
    }
    .text{
      margin: 1rem;
    }
  }
  
}
  
</style>
