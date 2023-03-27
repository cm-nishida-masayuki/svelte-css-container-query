<div class="container">
  <div class="wrapper">
    <img class="image" src="https://source.unsplash.com/random/640x400"  />
    <div>
      <dl>
        <dt>長いラベル</dt>
        <dd>投稿しました</dd>
      </dl>
      <dl>
        <dt>長いラベル</dt>
        <dd>¥100,000</dd>
      </dl>
    </div>  
  </div>
</div>

<style>
  .container{
    container-type: inline-size;
    margin: 10px;
    border: solid 1px #eee;
    box-shadow: 0 5px 5px 0 rgba(0, 0, 0, .2);
  }
  .wrapper {
    display: flex;
    flex-direction: column;
    padding: 10px;
    gap: 10px;
  }

  .image {
    height: 200px;
    width: 100%;
    border-radius: 10px;
    object-fit: cover;
  }

  dl {
    display: flex;
    flex-direction: column;
  }

  dt {
    font-size: 1.1rem;
    font-weight: 700;
  }
  
  dd {
    font-size: 1.0rem;
    font-weight: 400;
  }

  @container (min-width: 420px) {
    .wrapper {
      flex-direction: row;
    }

    .image {
      max-width: 50%
    }

    dl {
      flex-direction: row;
    }
    dd {
      margin-left: 10px
    }
  }
</style>
