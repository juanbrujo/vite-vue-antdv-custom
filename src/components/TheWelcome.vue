<template>
  <div>
    <a-button type="primary">Primary</a-button>
    <a-button type="primary" disabled>Primary(disabled)</a-button>
    <br />
    <a-button>Default</a-button>
    <a-button disabled>Default(disabled)</a-button>
    <br />
    <a-button type="dashed">Dashed</a-button>
    <a-button type="dashed" disabled>Dashed(disabled)</a-button>
    <br />
    <a-button type="text">Text</a-button>
    <a-button type="text" disabled>Text(disabled)</a-button>
    <br />
    <a-button type="link">Link</a-button>
    <a-button type="link" disabled>Link(disabled)</a-button>
    <br />
    <a-button danger>Danger Default</a-button>
    <a-button danger disabled>Danger Default(disabled)</a-button>
    <br />
    <a-button type="text" danger>Danger Text</a-button>
    <a-button type="text" danger disabled>Danger Text(disabled)</a-button>
    <br />
    <a-button type="link" danger>Danger Link</a-button>
    <a-button type="link" danger disabled>Danger Link(disabled)</a-button>
    <br />
    <div :style="{ padding: '16px', background: 'rgb(190, 200, 200)' }">
      <a-button ghost>Ghost</a-button>
      <a-button ghost disabled>Ghost(disabled)</a-button>
    </div>
  </div>
</template>

<style>
button {
  margin: 8px;
}
</style>
