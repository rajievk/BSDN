---
layout: default
title: Design And Functionality
nav_order: 5
---

## Primary Identifiers
<hr class="hr-no-bottom-margin"/>

### Master Client Versus Super Client Versus Direct Client
<ul>
  <li>Master client and super client are associated with white-labelled clients.</li>
  <li>Client is associated with directly managed clients.</li>
  <li>Master client number, super client number and direct client number assigned by the Administrator during the onboarding process.</li>
  <li>Table structure is common regardless of master client, super client or direct client.</li>
</ul>

### Clients
<table>				
<tr>
  <th align="left">White labelled</th>
  <th align="left">Direct</th>
</tr>
<tr>
  <td>Co-operators (1300)</td>
  <td>Bank of Montreal (1205)</td>
</tr>
<tr>
  <td>CUMIS (3100)</td>
  <td>TD Bank (5533)</td>
</tr>
<tr>
  <td>Royal Trust (RBC) (1870, 1880)</td>
  <td>Manulife (1582)</td>
</tr>
<tr>
  <td>Open Access (1800)</td>
  <td>Royal Bank (1227)</td>
</tr>
<tr>
  <td>Desjardins</td>
  <td>WSIB (1279)</td>
</tr>
<tr>
  <td>Blue Pier (2435)</td>
  <td>Bruce Power (1286)</td>
</tr>
<tr>
  <td></td>
  <td>Colgate (2004)</td>
</tr>
<tr>
  <td></td>
  <td>Becton Dickinson (2010)</td>
</tr>
<tr>
  <td></td>
  <td>Pilkington Glass (3304)</td>
</tr>
<tr>
  <td></td>
  <td>Apergy Energy (3305)</td>
</tr>
</table>

### Master Client and Super Client Structure

<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/178753027-822e3813-3104-47b9-8321-339b250d7801.png">
    </td>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/178753101-76806fd5-678e-47f0-b154-59ee49c6c8ca.png">
    </td>
    <td>
        Plans
      <ul>
        <li>Super clients are linked to a master client by
          DCP_CLIENTS_TABLE.EIN and
          DCP_CLIENTS_TABLE.REGION</li>
      <li>Employers are linked together by
          DCP_PLAN_NAME_TABLE.EIN</li>
      </ul>
    </td>
  </tr>
</table>

### Direct Client Structure
<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/178778364-d835c609-4a68-4b83-b525-2399f1ec709c.png">
    </td>
  </tr>
</table>

### Client, Plan, Fund, Account
<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/178778876-d64d8542-415b-4583-ae1f-d3f6b050a430.png">
    </td>
  </tr>
</table>

### Participant Identifiers
<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/178779108-33a7b8fc-c6ec-4a1f-b4cc-39facdcca214.png">
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/178779995-d16b48d7-3b4f-4899-8a12-d6acc6e9793a.png">
    </td>
  </tr>
</table>
