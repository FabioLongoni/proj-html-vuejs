<template>
  <div class="events__wrapper flex">
    <div class="events">
      <span class="made font__o text__up">
        made with love
      </span>
      <h2 class="text__up">
        delish pizza deals
      </h2>
      <ul class="event">
        <li v-for="(event,i) in events" :key="i" class="flex ">
          <div class="day__event">
            <div class="day font__o">{{ event.date }}</div>
            <div class="month font__o font__500 text__up">{{ event.month }}</div>
          </div>
          <div class="event__info">
            <a href="event.href">
              <h3 class="text__up">
                {{ event.info }}
              </h3>
              <span class="address">
                <font-awesome-icon icon="fa-solid fa-location-dot" /> {{ event.place }}
              </span>
            </a>
          </div>
        </li>
      </ul>
    </div>
    <div class="event__bg">

    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      events: [
        {
          date: '02',
          month: 'nov',
          href: "#",
          info: 'traditional neapolitan pies in kyoto pizza mercato',
          place: '204 E. Piazzetta Tommaso'
        },
        {
          date: '03',
          month: 'nov',
          href: "#",
          info: 'terrazza patio dining space opening this weekend',
          place: '204 E. Piazzetta Tommaso'
        },
        {
          date: '05',
          month: 'nov',
          href: "#",
          info: 'sienna private dining room with stéphane brunn',
          place: '204 E. Piazzetta Tommaso'
        },
      ]
    }
  }
}
</script>

<style scoped lang="scss">
  .events__wrapper {
    padding-bottom: 0.5rem;
    .events {
      color: white;
      background-image: url(../assets/img/star.jpg);
      padding: 5rem;
      flex-basis: 50%;
      .made {
        font-size: 12px;
        line-height: 1.375em;
        letter-spacing: .2em;
        color: #d2401e;
      }
      li {
        gap: 2rem;
        padding: 2rem 0;
        border-bottom: 1px dashed  #d2401e;
      }
      h2 {
        padding-bottom: 2rem;
      }
    }
    
  }
  .day__event {
    text-align: center;
  }
  .day {
    font-size: 55px;
    line-height: 1em;
    font-weight: 600;
    color: #ab4027;
  }
  .month {
    font-size: 25px;
    letter-spacing: .05em;
  }
  .event__bg {
    flex-basis: 50%;
    background-image: url(../assets/img/h3-img-5a.jpg);
    background-size: cover;
  }
  .event {
    h3 {
      font-size: 25px;
      padding-bottom: 0.75rem;
    }
  }
  .address {
    color: #d2401e;
    font-size: 12px;
  }
</style>