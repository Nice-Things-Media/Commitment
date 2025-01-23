---
Title: "Nice Things Commitment"
HeaderTitle: "NT Commitment"
Company: "NT Media"
Author: "Bill Solomon"
Version: "00.01.01"
TotalPages: "2"
Summary: "!!!include(CommitmentSummary_2025-01-23.md)!!!"
Content: "!!!include(CommitmentContent_2025-01-23.md)!!!"
---

<style>
:root {
    --dark_mono: #1a1a1a;
    --mid_mono: #808080;
    --mid_blue: #29478e;
    --light_blue: #d5e5f6;
}

* {
    box-sizing: border-box;
    margin: 0px;
    padding: 0px;
    border: 0px;
    font-family: Calibri;
    font-size: 13pt;
    line-height: 1.2em;
    color: var(--dark_mono);
    background-color: white;
}

.COLS {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.SHORT {
    height: 120px;
}

.TALL {
    height: 200px;
}

.SUMMARY {
    width: 45%;
    padding: 2rem;
    border-radius: 2rem;
    background-color: var(--light_blue);
    display: flex;
    justify-content: center;
    align-items: center;
}

table, th, td {
    border-collapse: collapse;
    border: none;
}

.SUMMARY>* {
    background-color: var(--light_blue);
}

.SUMMARY>*>* {
    background-color: var(--light_blue);

}

h1,
h2,
h3,
h4,
h5 {
    font-family: 'bebas neue';
}

h2, h3, h4, h5, p {
        margin-bottom: 0.7rem;
}

h1 {
    width: 45%;
    border: none;
    font-size: 4rem;
    padding-top: 2rem;
    padding-bottom: 2rem;
    margin-top: 15px;
}

h2 {
    font-size: 2rem;
    padding-top: 0.5rem;
    padding-bottom: 0.3rem;
    padding-left: 1rem;
    color: white;
    background-color: var(--mid_blue);
    font-weight: normal;
}

p {
    text-align: justify;
}

h3 {
    font-size: 1.5rem;
    padding-left: 2rem;
    font-weight: normal;
}

.footer {
    text-align: center;
}

.header {
    display: flex;
    justify-content: space-between;
    margin-bottom: 1rem;
}

</style>

<div class="COLS SHORT">
<img src="../img/logo.svg">
 <table>
   <tr>
    <th>Company</th>
    <td>{{Company}}</td>
  </tr>
  <tr>
    <th>Author:</th>
    <td>{{Author}}</td>
  </tr>
  </tr>
    <tr>
    <th>Pages:</th>
    <td>{{TotalPages}}</td>
  </tr>
</table>
</div>

<div class="COLS TALL">
<h1>{{Title}}</h1>
<div class="SUMMARY">
{{{Summary}}}
</div>
</div>

{{Content}}
