<template>
  <div id="app">
    <div class="container">
      <span class="close"></span>
        <div class="content">
          <h1>Unlock everything</h1>
          <div class="button-group">
            <a href="#" class="button">
              <div class="button_container">
                <div class="button_discount">
                  <span class="discount">Save 67%</span>
                  <span class="year_discount">$49.99/year</span>
                </div>
                <div class="button_description">
                  <p>7-day free trial</p>
                </div>
              </div>
            </a>

            <a href="#" class="button">
              <div class="button_container">
                <div class="button_discount">
                  <span class="year_discount">$12.99/month</span>
                </div>
                <div class="button_description">
                  <p>join</p>
                </div>
              </div>
            </a>
          </div>

          <ul class="list">
            <li class="list-item">
              <div class="list-item-icon-wrap">
                <div class="icon">l</div>
              </div>
              <div class="list-item-description">Access to all workout plans</div>
            </li>

            <li class="list-item">
              <div class="list-item-icon-wrap">
                <div class="icon">l</div>
              </div>
              <div class="list-item-description">Access to personal coaches</div>
            </li>

            <li class="list-item">
              <div class="list-item-icon-wrap">
                <div class="icon">l</div>
              </div>
              <div class="list-item-description">Access to yummy meal plans</div>
            </li>

            <li class="list-item">
              <div class="list-item-icon-wrap">
                <div class="icon">l</div>
              </div>
              <div class="list-item-description">Access to 1000+ mixes </div>
            </li>
          </ul>
        </div>
    </div>
    <div class="footer">
      <p>
        Recurring billing. Cancel anytime.</br>
        <a href="#">Terms &amp Conditions</a>&nbsp &nbsp &nbsp<a href="#">Privicy Policy</a></br>
      </p>

      <p>
        The subscription will automatically renew unless 
        auto-renew is turned off at least 24 hours before the end of the current period. You can go to your iTunes Account settings to manage your subscription and turn off 
        auto-renew. Your iTunes Account will be charged when the purchase is confirmed. If you subscribe before your free trial ends, the rest of your free trial will be forfeited as soon as your purchase is confirmed.
      </p>
    </div>
    <div class="opacity-container"></div>
    <div class="substrate"></div>
  </div>
</template>

<script>
import './styles/container.scss';
export default {
  name: 'app',
}
</script>