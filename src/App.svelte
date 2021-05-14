<script>
  import { RouterView } from '@bjornlu/svelte-router';
  import './nedb.min.js';
  var db = new Nedb({
    filename: 'AppData.db',
    autoload: true
  });
  import './w3.css';
  import './bootstrap.bundle.min.js';
  import './bootstrap.min.css';
  import Top from './components/Top.svelte';
  import Nav from './components/Nav.svelte';
  
</script>
<style>
  .aa{
display: flex;
flex: 1;
flex-direction: column;
height: 100vh;
  }
  .bb{
    flex: 1.25;

  }
  .cc{
   flex: 7;
   background-color: #9a8c98;
   height: 100%;
  }
  .dd{
 flex: 1.75;
  }
</style>
  <div class="aa">
    <div class="bb">
  <Top></Top>
  </div>
  <div class="cc">
  <RouterView />
  </div>
  <div class="dd">
  <Nav></Nav>
  </div>
  </div>