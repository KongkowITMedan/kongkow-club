<template>
  <div class="container">
    <div class="columns is-multiline">
      <div class="column is-3">
        <card icon="fa-telegram" title="Telegram Group" link="https://t.me/kongkowITMedan"/>
      </div>
      <div class="column is-3">
        <card icon="fa-comment" title="LINE Group" link="https://line.me/ti/g2/BBGHHDA7QF"/>
      </div>
      <div class="column is-3">
        <card icon="fa-medium" title="Community Blog" link="https://medium.com/kongkow-it-medan" />
      </div>
      <div class="column is-3">
        <card icon="fa-code-fork" title="Source Code" link="https://github.com/KongkowITMedan" />
      </div>
      <div class="column is-3">
        <card icon="fa-university" title="Kulgram" link="https://github.com/KongkowITMedan?q=kulgram" />
      </div>
      <div class="column is-3">
        <card icon="fa-ticket" title="Event Ticket" link="https://kongkowitmedan.eventbrite.com" />
      </div>
      <div class="column is-3">
        <card icon="fa-archive" title="Event Archive" link="https://kongkowitmedan.github.io/meetup" />
      </div>
      <div class="column is-3">
        <card icon="fa-gift" title="Backer" link="https://kongkowitmedan.github.io/backer" />
      </div>
      <div class="column is-3">
        <card icon="fa-money" title="Cash Flow" link="https://docs.google.com/spreadsheets/d/1HlUw3dlsmYStGIcHKQZcoIw1xyXt2imnq8xHwTt4xzs/edit?usp=sharing" />
      </div>
      <div class="column is-3">
        <card icon="fa-envelope" title="Email" link="mailto:hello@kongkow.club" />
      </div>
    </div>
  </div>
</template>

<script>
import Card from './Card'

export default {
  name: 'home',

  components: {
    Card
  }
}
</script>

