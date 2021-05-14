<script></script>
<style>
    .aa{
    display: flex;
    flex: 1;
    flex-direction: column;
    height: 100%;
    }
    .bb{
    flex: 2.8;
    height: 100%;
    display: flex;
    flex-direction: column;
    }
    .cc{
    flex: 6;
    height: 100%;
    background-color: #c9ada7;
    }
    .dd{
   flex: 1.2;
   height: 100%;
   display: flex;
   justify-content: space-between;
   align-items: center;
    }
     .yy{
        margin-left: 5px;
    }
    .zz{
        margin-right: 5px;
    }
    h2{
        text-align: center;
    }
    input {
        background-color: transparent;
        width: 120px;
        height: 40px;
        margin-left: 20px;
        margin-right: 20px;
        text-align: center;
    }
    .kk{
        display: flex;
        flex: 1;
        justify-content: start;
        align-items: center;
        margin-bottom: 10px;
    }
    .jj{
        flex: .5;
        padding-top: 7px;
        margin-right: 10px;
    
    }
   
    .gg{
        margin-right: 10px;
    }
    .uu{
        font-weight: bolder;
        font-size: larger;
        margin-left: 5px;
    }
   
    .ii{
        width: 70px;
    }
    .ss{
        font-family: monospace;
        margin-right: 60px;
        margin-bottom: 10px;
        margin-top: 5px;
    }
    .vv{
        margin-bottom: 20px;
        margin-top: 20px;
    }
    .oo{
        margin-bottom: 35px;
    }
   
</style>
<div class="aa">
    <div class="bb">
        <div class="jj">
        <h2 class="ss">Purchase &nbsp; : &nbsp;&nbsp;100000</h2>
        </div>
        <div class="kk w3-row">
        <input class="w3-input gg " type="text">
        <input class="w3-input w3-border w3-light-grey w3-round ii " type="text" placeholder="Qty">
        <span class="uu ">&times;</span>
        <input class="w3-input w3-border w3-light-grey w3-round ii" type="text" placeholder="Price">
        </div>

    </div>
    
    <div class="cc">
  <div class="jj">
        <h2 class="ss vv">Sale &nbsp;&nbsp;&nbsp;&nbsp; : &nbsp;&nbsp;100000</h2>
        </div>
        <div class="kk w3-row oo">
        <input class="w3-input gg " type="text">
        <input class="w3-input w3-border w3-light-grey w3-round ii " type="text" placeholder="Qty">
        <span class="uu ">&times;</span>
        <input class="w3-input w3-border w3-light-grey w3-round ii" type="text" placeholder="Cost">
        </div>

        <div class="kk w3-row oo">
        <input class="w3-input gg " type="text">
        <input class="w3-input w3-border w3-light-grey w3-round ii " type="text" placeholder="Qty">
        <span class="uu ">&times;</span>
        <input class="w3-input w3-border w3-light-grey w3-round ii" type="text" placeholder="Price">
        </div>

        <div class="kk w3-row oo">
        <input class="w3-input gg " type="text">
        <input class="w3-input w3-border w3-light-grey w3-round ii " type="text" placeholder="Qty">
        <span class="uu ">&times;</span>
        <input class="w3-input w3-border w3-light-grey w3-round ii" type="text" placeholder="Price">
        </div>

        <div class="kk w3-row oo">
        <input class="w3-input gg " type="text">
        <input class="w3-input w3-border w3-light-grey w3-round ii " type="text" placeholder="Qty">
        <span class="uu ">&times;</span>
        <input class="w3-input w3-border w3-light-grey w3-round ii" type="text" placeholder="Price">
        </div>
    </div>
    
    <div class="dd">
<button type="button" class="btn btn-primary yy">Clear</button>
<button type="button" class="btn btn-primary zz">Check</button>
    </div>
    
</div>