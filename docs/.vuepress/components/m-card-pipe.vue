<template>
  <m-card title="Pipe">
    <table>
      <tr>
        <td>SCH No</td>
        <td>20</td>
        <td>40</td>
        <td>80</td>
      </tr>
      <tr>
        <td>THK</td>
        <td>1.5</td>
        <td>1.6</td>
        <td>1.7</td>
      </tr>
      <tr>
        <td>WT</td>
        <td>5</td>
        <td>6</td>
        <td>7</td>
      </tr>
    </table>
  </m-card>
</template>

<style lang="scss">

table {
  border-collapse: collapse;
  // border: none;
  table-layout: fixed;
  width: 70%;
  padding: 5px 10px;
}
td,
th {
  border: 1px solid var(--c-text);
  text-align: center;
}
</style>
