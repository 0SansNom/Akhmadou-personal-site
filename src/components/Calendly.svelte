<div on:click={initCalendly} class="inline-block"><slot/></div>

<svelte:head>
  <link href="https://assets.calendly.com/assets/external/widget.css" rel="stylesheet">
  <script src="https://assets.calendly.com/assets/external/widget.js" type="text/javascript" async></script>
</svelte:head>

<script>
function initCalendly() {
  Calendly.initPopupWidget({url: 'https://calendly.com/akhmadou/met?hide_event_type_details=1'});return false;
}
</script>

