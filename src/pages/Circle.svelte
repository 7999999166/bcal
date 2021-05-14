<script></script>
<style>
    .aa{
    display: flex;
    flex: 1;
    flex-direction: column;
    height: 100%;
    }
    .bb{
    flex: 4.5;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    }
    .cc{
    flex: 4.5;
    height: 100%;
    background-color: #c9ada7;
     display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    }
    .dd{
   flex: 1;
   height: 100%;
   display: flex;
   justify-content: space-between;
   align-items: center;
    }
     h2{
        padding-top: 13px;
        padding-bottom: 13px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
    .xx{
        margin-bottom: 30px;
        margin-top: 30px;
        
    }
    input{
        width: 80px;
    }
     label{
        font-size: 1.3rem;
    }
     .yy{
        margin-left: 5px;
    }
    .zz{
        margin-right: 5px;
    }
</style>
<div class="aa">
    <div class="bb">
        <div>
       <h2>Volume (kg/m3) :</h2>
        </div>
        <div>
       <h2>Weight (kg) :</h2>
        </div>
        <div>
       <h2>Volume (ltr) :</h2>
        </div>

    </div>
    
    <div class="cc">
               <div class="row g-3 align-items-center xx">
  <div class="col-auto">
    <label for="inputPassword6" class="col-form-label">Diameter (inch) :</label>
  </div>
  <div class="col-auto">
    <input type="password" id="inputPassword6" class="form-control" aria-describedby="passwordHelpInline">
  </div>  
</div>

<div class="row g-3 align-items-center xx">
  <div class="col-auto">
    <label for="inputPassword6" class="col-form-label">Thickness (mm) :</label>
  </div>
  <div class="col-auto">
    <input type="password" id="inputPassword6" class="form-control" aria-describedby="passwordHelpInline">
  </div>  
</div>

    </div>
    
    <div class="dd">
<button type="button" class="btn btn-primary yy">Clear</button>
<button type="button" class="btn btn-primary zz">Check</button>
    </div>
    
</div>