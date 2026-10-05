<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00758f,50:0b4f6c,100:20252e&height=240&section=header&text=SQL%20Course%20Materials&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Visual%20examples%20%E2%80%A2%20Exercises%20%E2%80%A2%20Cheat%20Sheet%20%E2%80%94%20learn%20SQL%20by%20seeing%20it&descAlignY=58&descSize=17" alt="SQL Course Materials banner" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=800&color=00C2E0&center=true&vCenter=true&width=700&lines=SELECT+*+FROM+knowledge+WHERE+topic+%3D+'SQL'%3B;JOIN+theory+ON+practice%3B;ORDER+BY+skill+DESC%3B" alt="Typing animation" />
</a>

<br/>

![SQL](https://img.shields.io/badge/Language-SQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)
![Level](https://img.shields.io/badge/Level-Beginner%20→%20Intermediate-orange?style=for-the-badge)
![Visual](https://img.shields.io/badge/Visual%20Examples-16-2ea44f?style=for-the-badge)
![Exercises](https://img.shields.io/badge/Exercises-2-8A2BE2?style=for-the-badge)
![Cheat Sheet](https://img.shields.io/badge/Cheat%20Sheet-PDF-D9272E?style=for-the-badge)

**A complete, beginner-friendly SQL learning kit: examples, exercises, a cheat sheet and visual explanations.**
*Perfect for students, developers, and anyone preparing for interviews.*

<br/>

**[✨ Features](#-features)** &nbsp;•&nbsp;
**[🗺️ Learning Path](#️-learning-path)** &nbsp;•&nbsp;
**[📚 Topics](#-topics-covered)** &nbsp;•&nbsp;
**[🧩 Exercises](#-exercises)** &nbsp;•&nbsp;
**[📘 Cheat Sheet](#-sql-cheat-sheet)** &nbsp;•&nbsp;
**[🚀 Get Started](#-how-to-use)**

</div>

---

## ✨ Features

| | |
|:-:|:--|
| 🖼️ | **Visual examples** for every SQL concept |
| 🌱 | **Beginner to intermediate** coverage |
| 🔗 | Includes **JOINs, WHERE, LIKE, REGEXP, UNION** and more |
| 🧩 | **Exercises** to practice what you learn |
| 📘 | **SQL Cheat Sheet (PDF)** for quick revision |
| 🎓 | Ideal for **self-study** or **teaching material** |

---

## 🗺️ Learning Path

Follow the topics in this order. Each step builds on the one before it.

```mermaid
flowchart LR
    A["🟢 Basics<br/>SELECT · WHERE<br/>DISTINCT · ORDER BY<br/>LIMIT · INSERT"] --> B["🟡 Operators<br/>AND/OR · IN/NOT IN<br/>BETWEEN · LIKE<br/>REGEXP · IS NULL"]
    B --> C["🟠 Joins<br/>INNER JOIN<br/>LEFT / RIGHT JOIN<br/>Across databases"]
    C --> D["🔴 Advanced<br/>UNION"]
    D --> E["🏆 Practice<br/>Exercises"]
```

> 💡 `content.txt` in this repo lays out the same structured path, so you can follow it step by step.

---

## 📚 Topics Covered

Open any topic to see its visual example.

### 🔹 Basic SQL

<details>
<summary><b>SELECT</b> &nbsp;·&nbsp; choose which columns to return</summary>
<br/>
<div align="center">
  <img src="./SELECT%20EXAMPLE.PNG" alt="SELECT example" width="85%" />
</div>
</details>

<details>
<summary><b>WHERE</b> &nbsp;·&nbsp; filter rows by a condition</summary>
<br/>
<div align="center">
  <img src="./WHERE%20EXAMPLE.PNG" alt="WHERE example" width="85%" />
</div>
</details>

<details>
<summary><b>DISTINCT</b> &nbsp;·&nbsp; remove duplicate values from the result</summary>
<br/>
<div align="center">
  <img src="./DISTINCT%20EXAMPLE.PNG" alt="DISTINCT example" width="85%" />
</div>
</details>

<details>
<summary><b>ORDER BY</b> &nbsp;·&nbsp; sort the result ascending or descending</summary>
<br/>
<div align="center">
  <img src="./ORDER%20BY%20EXAMPLE.PNG" alt="ORDER BY example" width="85%" />
</div>
</details>

<details>
<summary><b>LIMIT</b> &nbsp;·&nbsp; restrict how many rows come back</summary>
<br/>
<div align="center">
  <img src="./LIMIT%20EXAMPLE.PNG" alt="LIMIT example" width="85%" />
</div>
</details>

<details>
<summary><b>INSERT</b> &nbsp;·&nbsp; add new rows to a table</summary>
<br/>
<div align="center">
  <img src="./INSERT%20EXAMPLE.PNG" alt="INSERT example" width="85%" />
</div>
</details>

### 🔹 Operators

<details>
<summary><b>AND / OR</b> &nbsp;·&nbsp; combine multiple conditions</summary>
<br/>
<div align="center">
  <img src="./AND%20%26%20OR%20OPERATORS.PNG" alt="AND and OR operators" width="85%" />
</div>
</details>

<details>
<summary><b>NOT / IN</b> &nbsp;·&nbsp; negate a condition, or match against a list</summary>
<br/>
<div align="center">
  <img src="./NOT%20%26%20IN%20OPERATORS.PNG" alt="NOT and IN operators" width="85%" />
</div>
</details>

<details>
<summary><b>BETWEEN</b> &nbsp;·&nbsp; match values within a range</summary>
<br/>
<div align="center">
  <img src="./BETWEEN%20OPERATOR.PNG" alt="BETWEEN operator" width="85%" />
</div>
</details>

<details>
<summary><b>LIKE</b> &nbsp;·&nbsp; simple pattern matching</summary>
<br/>
<div align="center">
  <img src="./LIKE%20OPERATOR.PNG" alt="LIKE operator" width="85%" />
</div>
</details>

<details>
<summary><b>REGEXP</b> &nbsp;·&nbsp; powerful regular-expression matching</summary>
<br/>
<div align="center">
  <img src="./REGEXP%20OPERATOR.PNG" alt="REGEXP operator" width="85%" />
</div>
</details>

<details>
<summary><b>IS NULL</b> &nbsp;·&nbsp; find missing values</summary>
<br/>
<div align="center">
  <img src="./IS%20NULL%20OPERATOR.PNG" alt="IS NULL operator" width="85%" />
</div>
</details>

### 🔹 Joins

<details>
<summary><b>JOIN</b> &nbsp;·&nbsp; combine columns from multiple tables with ON</summary>
<br/>
<div align="center">
  <img src="./JOIN%20EXAMPLE.PNG" alt="JOIN example" width="85%" />
</div>
</details>

<details>
<summary><b>JOIN across databases</b> &nbsp;·&nbsp; use tables from another database</summary>
<br/>
<div align="center">
  <img src="./JOIN%20ACROSS%20DATABASES.PNG" alt="JOIN across databases" width="85%" />
</div>
</details>

<details>
<summary><b>OUTER JOIN</b> &nbsp;·&nbsp; LEFT and RIGHT JOIN keep unmatched rows</summary>
<br/>
<div align="center">
  <img src="./OUTER%20JOIN%20WITH%20LEFT%20OR%20RIGHT%20JOIN%20KEYWORD.PNG" alt="Outer join with LEFT or RIGHT JOIN keyword" width="85%" />
</div>
</details>

### 🔹 Advanced

<details>
<summary><b>UNION</b> &nbsp;·&nbsp; stack the rows of multiple queries</summary>
<br/>
<div align="center">
  <img src="./UNION%20EXAMPLE.PNG" alt="UNION example" width="85%" />
</div>
</details>

---

## 🧩 Exercises

Put your knowledge to work. The exercises cover:

| 🔹 | 🔹 | 🔹 |
|:--|:--|:--|
| ✍️ Query writing | 🎯 Filtering | 🔗 Joins |
| 🔍 Pattern matching | ⚙️ Conditions | 🧠 Logical operators |

<table>
<tr>
<td align="center" width="50%">
  <b>Exercise 1</b><br/><br/>
  <img src="./EXERCISE.PNG" alt="Exercise 1" width="100%" />
</td>
<td align="center" width="50%">
  <b>Exercise 2</b><br/><br/>
  <img src="./EXERCISE%202.PNG" alt="Exercise 2" width="100%" />
</td>
</tr>
</table>

> 💡 Try each one on your own before checking the solution.

---

## 📘 SQL Cheat Sheet

A complete quick-reference sheet is included in the repository.

<div align="center">

### [📥 Open `SQL-Cheat-Sheet.pdf`](./SQL-Cheat-Sheet.pdf)

*Perfect for last-minute revision before an interview or exam.*

</div>

---

## 📂 Repository Structure

```text
SQL-Course-Materials/
│
├── 🔹 Basics
│   ├── SELECT EXAMPLE.PNG
│   ├── WHERE EXAMPLE.PNG
│   ├── DISTINCT EXAMPLE.PNG
│   ├── INSERT EXAMPLE.PNG
│   ├── ORDER BY EXAMPLE.PNG
│   └── LIMIT EXAMPLE.PNG
│
├── 🔹 Operators
│   ├── LIKE OPERATOR.PNG
│   ├── REGEXP OPERATOR.PNG
│   ├── AND & OR OPERATORS.PNG
│   ├── NOT & IN OPERATORS.PNG
│   ├── BETWEEN OPERATOR.PNG
│   └── IS NULL OPERATOR.PNG
│
├── 🔹 Joins
│   ├── JOIN EXAMPLE.PNG
│   ├── JOIN ACROSS DATABASES.PNG
│   └── OUTER JOIN WITH LEFT OR RIGHT JOIN KEYWORD.PNG
│
├── 🔹 Advanced
│   └── UNION EXAMPLE.PNG
│
├── 🧩 Exercises
│   ├── EXERCISE.PNG
│   └── EXERCISE 2.PNG
│
├── 📘 SQL-Cheat-Sheet.pdf
└── 📝 content.txt
```

---

## 🚀 How to Use

```bash
git clone https://github.com/Manu577228/SQL-Course-Materials.git
cd SQL-Course-Materials
```

| Step | What to do |
|:-:|:--|
| **1** | Open the image files to learn each SQL concept visually |
| **2** | Follow `content.txt` for the structured learning path |
| **3** | Revise with the cheat sheet |
| **4** | Test yourself with the exercises |

---

## 🏆 Ideal For

<table>
<tr>
<td align="center" width="20%">🎓<br/><b>Students</b><br/>learning SQL</td>
<td align="center" width="20%">💻<br/><b>Developers</b><br/>refining querying skills</td>
<td align="center" width="20%">📊<br/><b>Data analysts</b><br/>and beginners</td>
<td align="center" width="20%">🎯<br/><b>Interview</b><br/>preparation</td>
<td align="center" width="20%">👨‍🏫<br/><b>Trainers</b><br/>teaching SQL</td>
</tr>
</table>

---

## ⭐ Support

If this repository helped you, please **star the repo**. It helps more learners find it.

<div align="center">

<a href="https://star-history.com/#Manu577228/SQL-Course-Materials&Date">
  <img src="https://api.star-history.com/svg?repos=Manu577228/SQL-Course-Materials&type=Date" alt="Star History Chart" width="600" />
</a>

</div>

---

## 📬 Connect

<div align="center">

<a href="https://github.com/Manu577228">
  <img src="https://img.shields.io/badge/GitHub-Manu577228-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://youtube.com/@code-with-Bharadwaj">
  <img src="https://img.shields.io/badge/YouTube-Code%20with%20Bharadwaj-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
</a>

<br/><br/>

**Happy Querying! 🚀**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:20252e,50:0b4f6c,100:00758f&height=110&section=footer" alt="footer wave" />

</div>
