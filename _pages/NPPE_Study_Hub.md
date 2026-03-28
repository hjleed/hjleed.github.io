---
layout: archive
permalink: /NPPE_Study_Hub/
title: "NPPE Study Hub"
author_profile: true
redirect_from:
  - /nppe/
  - /nppe-exam/
  - /nppe-study-hub/
---

{% include base_path %}

<style>
  :root {
    --primary: #005b96;
    --accent: #0078c2;
    --light: #f4f7fa;
  }
  .nppe-container {
    max-width: 1100px;
    margin: 40px auto;
    background: white;
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    overflow: hidden;
  }
  .nppe-header {
    background: linear-gradient(135deg, var(--primary), var(--accent));
    color: white;
    padding: 2rem;
    text-align: center;
  }
  .nppe-header h1 {
    margin: 0;
    font-size: 2.4rem;
  }
  nav {
    background: #fff;
    border-bottom: 1px solid #ddd;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  }
  nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  nav a {
    display: block;
    padding: 1rem 1.5rem;
    color: var(--primary);
    text-decoration: none;
    font-weight: 600;
  }
  nav a:hover {
    background: var(--light);
    color: var(--accent);
  }
  section {
    padding: 2.5rem;
    border-bottom: 1px solid #eee;
  }
  h2 {
    color: var(--primary);
    border-bottom: 3px solid var(--accent);
    padding-bottom: 10px;
    margin-bottom: 1.5rem;
  }
  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
    margin-top: 20px;
  }
  .card {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 20px;
    text-align: center;
    transition: transform 0.3s, box-shadow 0.3s;
  }
  .card:hover {
    transform: translateY(-8px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.12);
  }
  .card img {
    max-height: 160px;
    width: auto;
    border-radius: 6px;
    margin-bottom: 15px;
  }
  .btn {
    display: inline-block;
    background: var(--accent);
    color: white;
    padding: 12px 24px;
    border-radius: 6px;
    font-weight: 600;
    margin-top: 10px;
    text-decoration: none;
  }
  .btn:hover {
    background: #005b96;
  }
  .quick-links {
    background: #f8fbff;
    padding: 1.5rem;
    border-radius: 8px;
    margin: 20px 0;
  }
  details {
    margin-bottom: 15px;
  }
  summary {
    cursor: pointer;
    font-weight: 600;
    padding: 12px;
    background: #f0f4f8;
    border-radius: 6px;
  }
  @media (max-width: 768px) {
    nav ul { flex-direction: column; }
    section { padding: 1.8rem; }
  }
</style>

<div class="nppe-container">

  <div class="nppe-header">
    <h1>NPPE Study Hub</h1>
    <p>National Professional Practice Examination – Ethics, Law & Professional Practice for Engineers & Geoscientists in Canada</p>
  </div>

  <nav>
    <ul>
      <li><a href="#overview">Overview</a></li>
      <li><a href="#blueprint">Blueprint & Syllabus</a></li>
      <li><a href="#registration">Registration & Exam</a></li>
      <li><a href="#resources">Study Resources</a></li>
      <li><a href="#textbooks">Recommended Textbooks</a></li>
      <li><a href="#free">Free Materials</a></li>
    </ul>
  </nav>

  <section id="overview">
    <h2>Exam Overview</h2>
    <p>The NPPE tests your knowledge of <strong>Ethics, Law, Liability</strong>, and <strong>Professional Practice</strong> relevant to engineering and geoscience professions across Canada.</p>
    <p>The exam consists of <strong>110 multiple-choice questions</strong> (100 scored + 10 experimental). Duration: <strong>2.5 hours</strong>. It is fully remote-proctored (Meazure Learning).</p>
    
    <div class="quick-links">
      <strong>Question Distribution (approximate):</strong><br>
      • Professionalism: 7–10<br>
      • Ethics: 17–21<br>
      • Professional Practice: 27–32<br>
      • Law for Professional Practice: 23–28<br>
      • Professional Law: 7–10<br>
      • Regulation & Discipline: 7–10
    </div>
  </section>

  <section id="blueprint">
    <h2>NPPE Blueprint / Syllabus</h2>
    <p>
      <a href="https://www.nppexam.ca/en/preparation/blueprint/" target="_blank" class="btn">Official Blueprint Page</a> 
      <a href="https://www.peo.on.ca/sites/default/files/2023-05/NPPE-Syllabus.pdf" target="_blank" class="btn">Download PDF Syllabus</a>
    </p>

    <details open>
      <summary>Topic 1 – Professionalism (7–10 questions)</summary>
      <ul>
        <li>Definition and interpretation of professionalism</li>
        <li>Role and responsibilities of professionals in society</li>
        <li>Engineering & geoscience professions in Canada (definitions, scopes, regulators, seals, iron/earth rings)</li>
        <li>Value of the professions to society</li>
      </ul>
    </details>

    <details>
      <summary>Topic 2 – Ethics (17–21 questions)</summary>
      <ul>
        <li>Role of ethics in society & cultures</li>
        <li>Ethical theories and principles</li>
        <li>Codes of Ethics (core tenets across Canada)</li>
        <li>Common ethical dilemmas and decision-making</li>
      </ul>
    </details>

    <details open>
      <summary>Topic 3 – Professional Practice (27–32 questions)</summary>
      <ul>
        <li>Accountability, workplace issues & standards</li>
        <li>Responsibilities to employers and clients</li>
        <li>Risk management, insurance, quality management & due diligence</li>
        <li>Environmental responsibilities & sustainable development</li>
        <li>Software use, document control, communication, whistleblowing</li>
      </ul>
    </details>

    <details>
      <summary>Topic 4 – Law for Professional Practice (23–28 questions)</summary>
      <ul>
        <li>Canadian legal system</li>
        <li>Contract law & tort law (including Quebec civil law)</li>
        <li>Intellectual property, employment/labour law</li>
        <li>Dispute resolution, expert witnesses, bonds & liens</li>
      </ul>
    </details>

    <details>
      <summary>Topic 5 – Professional Law (7–10 questions)</summary>
      <ul><li>Professional liability, negligence, and related legal concepts</li></ul>
    </details>

    <details>
      <summary>Topic 6 – Regulation of Members & Discipline Processes (7–10 questions)</summary>
      <ul><li>Regulatory framework, discipline processes, and member obligations</li></ul>
    </details>
  </section>

  <section id="registration">
    <h2>Registration & Exam Details</h2>
    <ul>
      <li>Register through your <strong>provincial/territorial regulator</strong> (PEO, APEGA, EGBC, etc.).</li>
      <li>Exam offered <strong>5 times per year</strong>.</li>
      <li>Fully remote proctored since 2020 (test centres only in exceptional cases).</li>
      <li>Meazure Learning will email you to schedule your session.</li>
    </ul>
    <p><strong>Tip:</strong> Check your regulator’s website for exact deadlines and contact info.</p>
  </section>

  <section id="resources">
    <h2>Medium Article Summaries (Highly Recommended)</h2>
    <div class="grid">
      <div class="card">
        <p><strong>Topic 1 – Professionalism</strong></p>
        <a href="https://medium.com/write-a-catalyst/nppe-exam-blueprint-topic-1-professionalism-in-engineering-geoscience-27139da72a41" target="_blank" class="btn">Read</a>
      </div>
      <div class="card">
        <p><strong>Topic 2 – Ethics</strong></p>
        <a href="https://medium.com/write-a-catalyst/nppe-exam-blueprint-topic-2-ethics-in-engineering-geoscience-fd602f3d7695" target="_blank" class="btn">Read</a>
      </div>
      <div class="card">
        <p><strong>Topic 3 – Professional Practice</strong></p>
        <a href="https://medium.com/write-a-catalyst/nppe-exam-blueprint-topic-3-professional-practice-part-1-eaeaf33819e1" target="_blank" class="btn">Read 1</a> • 
        <a href="https://medium.com/write-a-catalyst/nppe-exam-blueprint-topic-3-professional-practice-part-2-db464dc9f38d" target="_blank" class="btn">Read 2</a>
      </div>
      <div class="card">
        <p><strong>Topic 4 – Law for Professional Practice</strong></p>
        <a href="https://medium.com/write-a-catalyst/nppe-exam-blueprint-topic-4-law-for-professional-practice-part-1-826e5689a0f4" target="_blank" class="btn">Read 1</a> • 
        <a href="https://medium.com/write-a-catalyst/nppe-exam-blueprint-topic-4-law-for-professional-practice-part-2-1df13179d94a" target="_blank" class="btn">Read 2</a> • 
        <a href="https://medium.com/write-a-catalyst/nppe-exam-blueprint-topic-4-law-for-professional-practice-part-3-d4019ba2fa6f" target="_blank" class="btn">Read 3</a>
      </div>
      <div class="card">
        <p><strong>Topic 5 – Professional Law</strong></p>
        <a href="https://medium.com/write-a-catalyst/nppe-exam-blueprint-topic-5-professional-law-3829db86687d" target="_blank" class="btn">Read Article</a>
      </div>
      <div class="card">
        <p><strong>Topic 6 – Regulation & Discipline</strong></p>
        <a href="https://medium.com/write-a-catalyst/nppe-exam-blueprint-topic-6-regulation-of-members-and-discipline-processes-934b22cc9532" target="_blank" class="btn">Read Article</a>
      </div>
    </div>

    <h3 style="margin-top:40px;">Quick Video Summaries</h3>
    <p>
      <a href="https://www.youtube.com/live/PglwCz8_WQU?si=WwA_WqGjMPcZerAZ" target="_blank" class="btn">NPPE ‘Law and Ethics Walkthrough’</a><br><br>
      <a href="https://www.youtube.com/watch?v=qxy_g897M7E" target="_blank" class="btn">NEDAC Seminar - NPPE Preparation Webinar</a>
    </p>
  </section>

  <section id="textbooks">
    <h2>Recommended Textbooks</h2>

    <h3>Law for Professional Practice</h3>
    <div class="grid">
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/719ZiaL0mQL._SY385_.jpg" alt="Law for Professional Engineers">
        <p><strong>Law for Professional Engineers</strong><br>5th ed. (2019) – Donald L. Marston</p>
        <a href="https://mississauga.bibliocommons.com/v2/record/S220C529337" target="_blank" class="btn">Access Link</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/4112lXvtNFL._SY385_.jpg" alt="Practical Law of Architecture">
        <p><strong>Practical Law of Architecture, Engineering, and Geoscience</strong><br>3rd ed. – Brian M. Samuels & Doug R. Sanders</p>
        <a href="https://github.com/Ottawa23/notes/blob/main/Brian-M.-Samuels-Doug-R.-Sanders-Practical-Law_2ed.pdf" target="_blank" class="btn">PDF Link</a>
      </div>
    </div>

    <h3>Principles of Professional Practice and Ethics</h3>
    <div class="grid">
      <div class="card">
        <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1678273221i/83439629.jpg" alt="Practical Guide to Ethics">
        <p><strong>A Practical Guide to Ethics and Professional Practice</strong><br>1st ed. (2022) – Samuels & Sanders</p>
        <a href="https://www.goodreads.com/en/book/show/83439629-practical-guide-to-ethics-and-professional-practice-for-engineers-and-ge" target="_blank" class="btn">Link</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81BYQKoEkyL._SY466_.jpg" alt="Canadian Professional Engineering and Geoscience">
        <p><strong>Canadian Professional Engineering and Geoscience: Practice & Ethics</strong><br>5th/6th ed. – Andrews, Shaw & McPhee</p>
        <a href="https://bookstore.uoguelph.ca/p-13195-canadian-professional-engineering-and-geoscience.aspx" target="_blank" class="btn">Link</a>
      </div>
    </div>
  </section>

  <section id="free">
    <h2>Free Study Materials & Additional Resources</h2>
    <ul>
      <li><a href="https://www.ic.gc.ca/eic/site/cipointernet-internetopic.nsf/eng/h_wr00003.html" target="_blank">Guide to Copyright</a></li>
      <li><a href="https://www.ic.gc.ca/eic/site/cipointernet-internetopic.nsf/eng/h_wr02360.html" target="_blank">Guide to Industrial Designs</a></li>
      <li><a href="https://www.ic.gc.ca/eic/site/cipointernet-internetopic.nsf/eng/h_wr03652.html" target="_blank">Guide to Patents</a></li>
      <li><a href="https://www.ic.gc.ca/eic/site/cipointernet-internetopic.nsf/eng/h_wr00002.html" target="_blank">Guide to Trademarks</a></li>
      <li><a href="https://www.egbc.ca/getmedia/0d9d0940-5a15-4d06-8a98-35d381600295/EGBC-Use-of-Professional-Practice-Guidelines-V1-1.pdf" target="_blank">Concepts of Professionalism (EGBC)</a></li>
      <li><a href="https://engineerscanada.ca/sites/default/files/2024-07/Guideline_on_the_code_of_ethics-2024.pdf" target="_blank">Guideline for Ethical Practice</a></li>
      <li>Your jurisdiction’s <em>Engineering and Geoscience Professions Act</em> and <em>Occupational Health and Safety Act</em></li>
      <li><a href="https://www.rbc.com/en/about-us/history/letter/vol-71-no-6-november-december-1990-the-soul-of-professionalism/" target="_blank">RBC – “The Soul of Professionalism”</a></li>
    </ul>

    <h3>Other Useful PDFs</h3>
    <div class="grid">
      <div class="card">
        <p><strong>Smart NPPE Preparation Guide</strong></p>
        <a href="https://github.com/Ottawa23/notes/blob/main/NPPE%20Study%20Guide%20-%20Updated%20New%20Syllabus.pdf" target="_blank" class="btn">Download PDF</a>
      </div>
      <div class="card">
        <p><strong>10-Hour Study Guide</strong></p>
        <a href="https://github.com/Ottawa23/notes/blob/main/Study10Hours.pdf" target="_blank" class="btn">Download PDF</a>
      </div>
      <div class="card">
        <p><strong>Engineering and Geoscience Professions Act (Alberta example)</strong></p>
        <a href="https://github.com/Ottawa23/notes/blob/main/ENGINEERING_AND_GEOSCIENCE.pdf" target="_blank" class="btn">Download PDF</a>
      </div>
    </div>
  </section>
  
  <section>
<div>

  ## 📝 Interactive Practice Quiz
Test your knowledge with my collection of 55 NPPE practice questions.

[Take the Practice Quiz](./nppe-quiz.html){: .btn .btn--primary}

</div>
  </section>

  <footer style="text-align:center; padding:2rem; background:#f4f7fa; color:#666; font-size:0.9rem;">
    <p>NPPE Study Hub – Copyright &copy; <script>document.write(new Date().getFullYear());</script> All rights reserved<br>
    "The best person is the one who benefits all human beings" — 
    <a href="https://en.wikipedia.org/wiki/Muhammad_in_Islam" target="_blank">Prophet Muhammad</a></p>
  </footer>

</div>
