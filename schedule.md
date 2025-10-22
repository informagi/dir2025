<style>
  /* High-specificity + !important to beat frameworks */
  table.force-layout {
    width: 100% !important;
    table-layout: fixed !important;
    border-collapse: collapse;
  }
  table.force-layout th,
  table.force-layout td {
    border: 1px solid #ddd;
    padding: 8px;
    box-sizing: border-box;            /* keeps widths exact */
    overflow: hidden;                  /* prevents column blowout */
    text-overflow: ellipsis;           /* show … when no wrap */
    white-space: nowrap;               /* keep one-line by default */
  }

  /* If you want the middle column to wrap instead of ellipsis: */
  table.force-layout th:nth-child(2),
  table.force-layout td:nth-child(2) {
    white-space: normal;               /* allow wrapping */
    overflow-wrap: anywhere;           /* break very long tokens */
    word-break: break-word;            /* legacy break */
  }
</style>




<div>
<table class="force-layout">
  <colgroup>
    <col style="width:30%">
    <col style="width:60%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Time</th>
      <th>Information</th>
      <th>Where</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>8:30-9:00</td>
      <td>Registration (Maria Montesorigebouw Building)</td>
      <td> MM00.029</td>
    </tr>
    <tr>
      <td>9:00-9:15</td>
      <td>Opening</td>
      <td>MM00.029</td>
    </tr>
    <tr>
      <td>9:15-10:15</td>
      <td>Keynote: Thomas Demeester, Multimodal Health Data: From Representation to Causal Understanding</td>
      <td>MM00.029</td>
    </tr>
    <tr>
      <td>10:15-10:45</td>
      <td>Coffee Break</td>
      <td>Grand Cafe Iris</td>
    </tr>
    <tr>
      <td>10:45-12:00</td>
      <td>Oral Session #1</td>
      <td>MM00.029</td>
    </tr>
    <tr>
      <td>12:00-13:00</td>
      <td>Lunch</td>
      <td>Grand Cafe Iris</td>
    </tr>
    <tr>
      <td>13:00-14:00</td>
      <td>Keynote: Asia Biega, From regulations to implementations: Building information access systems in the public interest</td>
      <td>MM00.029</td>
    </tr>
    <tr>
      <td>14:00-15:00</td>
      <td>Oral Session #2</td>
      <td>MM00.029</td>
    </tr>
    <tr>
      <td>15:00-15:30</td>
      <td>Coffee Break</td>
      <td>Grand Cafe Iris</td>
    </tr>
    <tr>
      <td>15:30-16:00</td>
      <td>Oral Session #3</td>
      <td>MM00.029</td>
    </tr>
    <tr>
      <td>16:00-16:05</td>
      <td>Closing Session</td>
      <td>MM00.029</td>
    </tr>
    <tr>
      <td>16:05-17:00</td>
      <td>Poster Session</td>
      <td>Grand Cafe Iris</td>
    </tr>
    <tr>
      <td>16:30-18:00</td>
      <td>Drinks (Overlap with Poster Session)</td>
      <td>Grand Cafe Iris</td>
    </tr>
  </tbody>
</table>
</div>


