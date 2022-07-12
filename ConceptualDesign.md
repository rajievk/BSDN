---
layout: default
title: Conceptual Design
nav_order: 3
---

## Business Overview
<hr/>
<table>
  <tr>
    <th align="left">Administration Services</th>
    <th align="center"></th>
    <th align="left">Software and Support Services</th>
  </tr>
  <tr>
    <td>
      <ul>
        <li>Data management and transaction processing</li>
        <li>Valuation, trade, settlement, processing</li>
        <li>Reconciliation</li>
        <li>Reporting and member communication</li>
        <li>Tax receipt issuance and reporting</li>
        <li>Fulfillment services</li>
        <li>Contact centre services</li>
      </ul>
    </td>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/178588071-5589f2aa-ec05-4433-b814-8082a73d320b.png">
    </td>
    <td>
      <ul>
        <li>Record keeping, administration and trading software(FundSERV and CameronFIX)</li>
        <li>Compliance with Canadian laws and regulations</li>
        <li>Upgrades and enhancements</li>
        <li>Operational and infrastructure support</li>
        <li>Training</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Buck integrates with but is not an:</th>
    <th align="center"></th>
    <th align="left">Hosting Services</th>
  </tr>
  <tr>
    <td>
      <ul>
        <li>Investment Manager</li>
        <li>Broker / Dealer</li>
        <li>Trustee / Custodian</li>
        <li>Transfer Agent / Payment Agent</li>
      </ul>
    </td>
    <td>
    </td>
    <td>
      <ul>
        <li>Systems management</li>
        <li>Data backup and recovery</li>
        <li>Disaster recovery services</li>
        <li>Security administration</li>
        <li>CSAE 3416 / SSAE 18 certification</li>
        <li>Hardware evergreen</li>
      </ul>
    </td>
  </tr>
</table>

## Entity Relationships
</hr>
<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/178596588-e7b2d4b1-9d55-4c5c-83d1-cb10a6ea29b0.png">
    </td>
  </tr>
</table>

## Functional Overview
</hr>
<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/178596968-4b892f89-bb88-4f95-9ade-ebef17fe8984.png">
    </td>
     <td>
      <table>
        <tr>
          <th>
            Components
          </th>
        </tr>
        <tr>
          <td>
            <ul>
              <li><b>ISS:</b> Authentication and authorization</li>
              <li><b>Portal:</b> View and transaction layer</li>
              <li><b>DES:</b> Data entry system / transaction repository</li>
              <li><b>BASIS:</b> Valuation system</li>
              <li><b>Scheduler:</b> Batch processing system</li>
              <li><b>FRS:</b> Forms, reports and statements system</li>
            </ul>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>
