<script lang="ts">
  let emojis = {
    apple: '🍎',
    banana: '🍌',
    carrot: '🥕',
    doughnut: '🍩',
    egg: '🥚',
  }

  export let name
  let emoji = emojis[name]
</script>

<p>
  <span>The emoji for {name} is {emoji}</span>
</p>
