---
layout: default
---

# SSL Dataset
This dataset is the result of a collaborative effort between King Fahd University of Petroleum and Minerals (KFUPM) and the National Center for Artificial Intelligence (NCAI). It contains sign language data collected from a diverse group of signers, designed to support research and development in the field of sign language recognition and related AI applications.

## Data Summary

The dataset includes sign language sentences from a variety of signers, capturing different signing styles and contexts. Below is a brief overview of the dataset:

- **Number of Signers**: 18
- **Total Hours of Video**: 35 hours
- **Data Splits**: 
  - **Training Split**:
    - Includes three female signers and eleven male signers.
    - The total duration of the training split is 34 hours.

  - **Test Split**:
    - The test split is 7 hours in total, consisting of:
      - **Test 1**: Unseen signers and unseen sentences.
      - **Test 2**: Seen signers and unseen sentences.
      - **Test 3**: Seen sentences and unseen signers.

The table below summarizes the data for each split based on the sentences, minutes, seen sentences, seen signers, and other parameters.

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Table</title>
  <style>
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
      font-family: Arial, sans-serif;
    }
    th, td {
      border: 1px solid #ddd;
      padding: 8px 12px;
      text-align: center;
    }
    th {
      background-color: #4CAF50;
      color: white;
    }
    tr:nth-child(even) {
      background-color: #f2f2f2;
    }
    tr:hover {
      background-color: #ddd;
    }
    td {
      font-size: 14px;
    }
    th {
      font-size: 16px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <table>
    <thead>
      <tr>
        <th><strong>Split</strong></th>
        <th><strong>Sentences</strong></th>
        <th><strong>Minutes</strong></th>
        <th><strong>Seen Sentences</strong></th>
        <th><strong>Seen Signers</strong></th>
        <th><strong># Samples</strong></th>
        <th><strong># Signers</strong></th>
        <th><strong>Gender</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Train</td>
        <td>24,111</td>
        <td>2,017.82</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>1,900</td>
        <td>16</td>
        <td>4F, 12M</td>
      </tr>
      <tr>
        <td>Test 1</td>
        <td>200</td>
        <td>16.65</td>
        <td>No</td>
        <td>No</td>
        <td>100</td>
        <td>2</td>
        <td>1F, 1M</td>
      </tr>
      <tr>
        <td>Test 2</td>
        <td>1,297</td>
        <td>107.95</td>
        <td>No</td>
        <td>Yes</td>
        <td>100</td>
        <td>11</td>
        <td>3F, 10M</td>
      </tr>
      <tr>
        <td>Test 3</td>
        <td>3,783</td>
        <td>337.33</td>
        <td>Yes</td>
        <td>No</td>
        <td>1,900</td>
        <td>2</td>
        <td>1F, 1M</td>
      </tr>
    </tbody>
  </table>
</body>
</html>


## Data Access
- **Data Acess Requirement**: This dataset can be accessed by clicking <a href="https://www.kaggle.com/t/c36c02c8809d409b9c6971929e575087"> Kaggle dataset</a>

##  Citation
When utilizing this dataset in your research, remember to cite the dataset paper once it is published.

## License
Please follow the licensing terms of Creative Commons Attribution-NonCommercial (CC BY-NC).

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled List</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    .list-container {
      background-color: #f9f9f9;
      border: 1px solid #ddd;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }
    h2 {
      color: #4CAF50;
      font-size: 24px;
      margin-bottom: 10px;
    }
    ul {
      list-style-type: none;
      padding-left: 20px;
    }
    li {
      font-size: 16px;
      line-height: 1.6;
    }
    li::before {
      content: "• ";
      color: #4CAF50;
    }
    .sub-list {
      margin-left: 20px;
      font-size: 14px;
      color: #555;
    }
  </style>
</head>
<body>
