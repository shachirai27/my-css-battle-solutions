<div class=cnt>
<div class=wv1></div>
<div class=wv2></div>
<div class=wv3></div>
</div>

<style>
  body {
    background: #62306D;
  }
  .cnt {
    display:flex;
    justify-content:center;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    width: 100%;
    height: 200px;
  }
  div[class^=wv] {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    border-radius:50% 50% 0 0;
  }
  .wv1,.wv3{align-self:flex-end;transform:rotate(180deg);}
</style>
