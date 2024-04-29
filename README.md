# Edux.Lectures  

  <body class="c22 doc-content">
    <h1 class="c44" id="h.q7geq699fzw">
      <span class="c49 c55">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62108/chapter/25888&amp;sa=D&amp;source=editors&amp;ust=1714064099677980&amp;usg=AOvVaw0tlrRygRi0poLKkT0s7DWX">1 </a>
      </span>
      <span class="c48 c50">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62108/chapter/25888&amp;sa=D&amp;source=editors&amp;ust=1714064099678312&amp;usg=AOvVaw3-g6gxmy2ZiK8iMgYp2lOo">Lesson II – Introduction to the relational databases</a>
      </span>
    </h1>
    <p class="c13">
      <span class="c34 c5">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62108/chapter/25888&amp;sa=D&amp;source=editors&amp;ust=1714064099678667&amp;usg=AOvVaw1IkUlf7Q1KQz-_ErHPhDcp">15.03.2024 11:45 | Number of chapters: 8</a>
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.wi7w8462c4ky">
      <span class="c14 c5">New skills</span>
    </h1>
    <p class="c3">
      <span class="c2">The goal of this lecture is to explain the problem of storing data, especially within relational databases. This issue will be studied in depth in future semesters during lectures like </span>
      <span class="c4">“Relational Databases”</span>
      <span class="c2">&#160;and </span>
      <span class="c4">“Database Systems”</span>
      <span class="c1">. After studying the five following database related lectures student should be able to explain terms like “data”, “information”, “logical database structure”, know the basics of designing the relational database structure and the basics of SQL query syntax.</span>
    </p>
    <p class="c3">
      <span class="c1">The first lecture is dedicated to explaining the need of storing data in today’s world and pointing out the currently used technologies and data models.</span>
    </p>
    <h3 class="c9" id="h.2sk4uzq7jyq4">
      <span class="c17 c5">Learning outcome</span>
    </h3>
    <ul class="c8 lst-kix_lyr3b2ph9j2j-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">Student understands the ubiquity of data stored in various ways depending on the technology used,</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Student understands the need of introducing data structure when storing data,</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Student is able to list the database examples from the everyday life,</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Student understands the existence of various data models and can explain in detail at least two of them.</span>
      </li>
    </ul>
    <h1 class="c36 c22" id="h.bsiuzpgnwh4w">
      <span class="c14 c5">Database – what’s that?</span>
    </h1>
    <p class="c3">
      <span class="c1">The term „database” in the sense of a system for collecting and storing data dates back to the ancient times. People have always strived for recording their knowledge. The main purpose of this activity was the possibility of drawing conclusions on the basis of possessed information. The basic idea of this mechanism hasn’t changed at all.</span>
    </p>
    <h3 class="c9" id="h.sg0m2z985kfj">
      <span class="c51 c5">Do you see this sign:</span>
    </h3>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 145.33px; height: 222.67px;">
        <img alt="" src="images/image18.jpg" style="width: 145.33px; height: 222.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.7rqx6me8codd">
      <span class="c51 c5">Remember where and inform the others.</span>
    </h3>
    <p class="c3">
      <span class="c1">All we need to know is:</span>
    </p>
    <ul class="c8 lst-kix_43hhuxt2rq9t-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">How to store this information?</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">How to make it available?</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">For whom should we make it available?</span>
      </li>
    </ul>
    <p class="c3">
      <span class="c1">While the answer on the third question depends mainly on one’s intentions, the answers to the first and the second questions are strictly dependent on the technology at our disposal. Moreover the technology used can influence the data accessibility and therefore the usability of our solution. Hence our conclusion is: the ability to store information and the extent of its accessibility are determined by the technology we use.</span>
    </p>
    <h3 class="c9" id="h.qa8yboet525t">
      <span class="c17 c5">How was data stored in ancient times?</span>
    </h3>
    <p class="c3">
      <span class="c1">We can say that one of the important aspects of human history was the way of recording and storing data. Only few were known and all of them were determined by the technology available at that stage of human development.</span>
    </p>
    <h3 class="c9" id="h.d09ach9bds7g">
      <span class="c17 c5">Ways of storing data archaic from our perspective</span>
    </h3>
    <p class="c3">
      <span class="c4">Clay tablets, cuneiform writing</span>
      <span class="c1">&#160;– 4 000 BC till 4 century</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 238.00px; height: 158.00px;">
        <img alt="" src="images/image94.png" style="width: 238.00px; height: 158.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c4">Papyrus, handwriting</span>
      <span class="c1">&#160;– 3 000 BC until the first century</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 184.00px; height: 137.00px;">
        <img alt="" src="images/image28.png" style="width: 184.00px; height: 137.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c4">Parchment, handwriting and print</span>
      <span class="c1">&#160;– 3rd century BC till 17th century</span>
    </p>
    <h3 class="c9" id="h.r55av880ue6p">
      <span class="c17 c5">…and a little closer to our times</span>
    </h3>
    <h3 class="c9" id="h.vcv9yripoe73">
      <span class="c17 c5">Finally a few modern technologies</span>
    </h3>
    <p class="c3">
      <span class="c4">Paper</span>
      <span class="c1">&#160;– discovered in China in 8 BC and used until today around the world</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c4">Print</span>
      <span class="c1">&#160;– method of duplication of text with a stamp, known for thousands of years. Modern printing is done using a moveable type invented during the medieval times. The zenith of its development falls on the first half of the 20th century.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 219.00px; height: 288.00px;">
        <img alt="" src="images/image93.png" style="width: 219.00px; height: 288.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">First modern </span>
      <span class="c4">printing machine</span>
      <span class="c1">&#160;was constructed significantly later (in second half of 19th century) as an aid for handwriting.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 220.00px; height: 165.00px;">
        <img alt="" src="images/image20.png" style="width: 220.00px; height: 165.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.l934fgdqcg78">
      <span class="c17 c5">… and what was the result of storing this data?</span>
    </h3>
    <p class="c3">
      <span class="c1">After many years of acquiring and storing data we managed to collect an enormous amount of data.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c4">Library of Congress</span>
      <span class="c1">&#160;– the biggest library in the world. 142 mln of various documents (29 mln of books, 4.8 mln of maps and atlases, 12 mln of photos, 6 mln of microfilms, 3.5 mln of music documents, 0.5 mln of films). Library consists of 856 km of shelfs in three buildings. There are 22 reading rooms, 5 thousands employees (source: Wikipedia).</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">And there are so many other, smaller libraries containing a lot of data.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">What’s our conclusion then? We have enormous collections of data recorded using various old, “classical” technologies. This, however leads to serious problems, such as: how can you find the information you need in this enormous data set using the old technologies? Or how can we make sure that the information coming from two different sources is consistent? And finally, how to decide which information is “true” and which is “false”?</span>
    </p>
    <h3 class="c9" id="h.3j2rpliak31k">
      <span class="c17 c5">Computer – revolution in technology</span>
    </h3>
    <p class="c3">
      <span class="c1">…of course not only in the data storing technology. And it did not happen overnight.</span>
    </p>
    <p class="c3">
      <span class="c4">Atanasoff-Berry Computer, ABC</span>
      <span class="c1">&#160;– machine used for solving linear algebraic equitation. The first machine was built using 270 electron tubes. It used binary numbers and wasn’t programmable. USA 1939.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c4">Z3 – (relay successor of mechanic Z3) – Germany, 1941</span>
      <span class="c1">&#160;– the computer was able to perform four types of operations and extract the roots from binary numbers, the clock frequency was 5 1/3 Hz, the memory capacity up to 64 words (each consisting of 22 bits ), the program memory consisted of an eight channel punched tape. Only one model was built and it was subsequently destroyed by the Allied forces. It was used for the endurance calculations of wings in the aircraft industry.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c4">Colossus</span>
      <span class="c1">&#160;– Great Britain – the first one was built on 14th of April in 1941. Altogether 11 models were built. It was used for breaking the code of German encryption machine called (Lorenz machine).</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c4">ENIAC</span>
      <span class="c1">&#160;– USA 1943 – 1945 (27 tons, 18 000 electron tubes, 140 square meters). It didn’t have operational memory. It was programmed by manipulating switches and cables. Afterwards it also used punched cards.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">As we can see the beginnings weren’t so easy. But what has the computer brought to the technology of storing data? There are two basic technology advancements we should point out:</span>
    </p>
    <ul class="c8 lst-kix_kuovaf6uwbxb-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">The drop in prices of mass storage (tapes, drives, CD) allowed for storing vast amounts of data on very little space and with little cost.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">The ability to search through data in relatively short time.</span>
      </li>
    </ul>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 271.00px; height: 186.00px;">
        <img alt="" src="images/image55.png" style="width: 271.00px; height: 186.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">But along with these possibilities certain challenges appeared. Various data structures were needed for efficient data storage in order to make a full use of the computer. This is the beginning of the databases in the modern meaning.</span>
    </p>
    <h3 class="c9" id="h.20nsknk6wkmv">
      <span class="c17 c5">Control questions</span>
    </h3>
    <p class="c13 c29">
      <span class="c4 c5">Do you think that the computer is necessary for storing data?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Yes</span>
    </p>
    <p class="c31 c29">
      <span class="c1">No</span>
    </p>
    <p class="c13 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c29">
      <span class="c4 c5">Did the concept of data storage appear in the second half of the 20th century?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Yes</span>
    </p>
    <p class="c31 c29">
      <span class="c1">No</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c46 c18" id="h.daj6cb71v9uc">
      <span class="c14 c5">Database – basic information</span>
    </h1>
    <p class="c3 c20">
      <span class="c2">We often use terms </span>
      <span class="c4">“data”</span>
      <span class="c2">&#160;and </span>
      <span class="c4">“information”</span>
      <span class="c1">&#160;interchangeably. But what do they really mean? Are they interchangeable?</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c4">Information</span>
      <span class="c2">&#160;and </span>
      <span class="c4">data</span>
      <span class="c1">&#160;–both terms are used for describing the reality or more precisely a part of it, but they are not synonyms.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c4">Data</span>
      <span class="c1">&#160;– these are values that can be transformed and processed (by computer or by our mind). We can assume that data is something that we can save and record in various ways (numbers, text, image files etc.).</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c4">Information</span>
      <span class="c1">&#160;– this term generally means data along with its semantics which is the key to proper interpretation. Lack of interpretation can render data useless.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">Let’s assume that in front of us we have a page with Japanese symbols. This is our data. But can we read and understand the information contained within each symbol? We probably could if we knew the Japanese language. Otherwise we can’t. Just to be clear I have no idea about Japanese language.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">Data is one of company’s (or institution’s, organization’s) main assets, next to its capital, employees and infrastructure. It allows the company to operate and interact with business environment but, just like other assets, it requires maintenance and management. The data management is realized through </span>
      <span class="c16">the information system</span>
      <span class="c1">&#160;which satisfies the need for information about certain part of our business domain. Database is usually a part of this system which is responsible for storing, security and management of the data and its accessibility.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">We can identify here a conceptual dualism. By “database” we mean:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_bu096cxa7zy2-0 start">
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          Database Management System (DMS) – data structure, security, rules about its accessibility (DBMS)
        </span>
      </li>
    </ul>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">Or</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_3ewi2x1kv5uq-0 start">
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          Data Collection (DC)
        </span>
      </li>
    </ul>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">The database has become a standard way of introducing structure and rules into the process of data management. These structures and rules evolve together with the information technologies. In the next part of this lecture, under the term “database”, we will mean the term ”Database Management System”.</span>
    </p>
    <h3 class="c46 c18" id="h.kvmyyrloe7k1">
      <span class="c17 c5">Control questions</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">Can you tell what number it is? - 1101</span>
    </p>
    <p class="c10">
      <span class="c1">Yes</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">Can a school library be called a "database" according to/as explained in the aforementioned definitions?</span>
    </p>
    <p class="c10">
      <span class="c1">Yes</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">Can student’s notes from lectures be called a “database”?</span>
    </p>
    <p class="c10">
      <span class="c1">Yes</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.jxitvhxl4g9i">
      <span class="c14 c5">More on database</span>
    </h1>
    <h3 class="c9" id="h.wmn13oi5fff7">
      <span class="c17 c5">What do we expect from a DBMS?</span>
    </h3>
    <p class="c3">
      <span class="c1">We generally expect database to securely store our data and allow it to be easily queried by the authorized users. In practice we demand the following:</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_sbnx2aog7wgo-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">Durability</span>
        <span class="c1">&#160;– data should be stored for specific amount of time. Usually we don’t know how long this period will be. Time should not affect the data.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">Data must be accurate</span>
        <span class="c1">&#160;– data must reflect the reality as accurately as possible and the structure must allow for data updates whenever changes occur.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">Replication control</span>
        <span class="c1">&#160;– database must guarantee control over the redundant data in order to avoid ambiguity.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">Structure design</span>
        <span class="c1">&#160;– database should be structured in accordance with specific data model.</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">As it soon turns out the technological progress has rendered the last two demands somewhat outdated and consequently they are often rejected by modern database specialists.</span>
    </p>
    <p class="c3">
      <span class="c1">I would like to turn your attention to the term “redundancy”, which describes superfluous data used to record some kind of information. It can lead to a situation when we obtain different and often contradictory answers when we use different data sets to describe the same thing. Of course this is an unwanted situation, although in practice it is inevitable to some degree. If it happens we would like to know how to control it.</span>
    </p>
    <h3 class="c9" id="h.ettrhqe100lh">
      <span class="c17 c5">What do we require from a modern DBMS?</span>
    </h3>
    <p class="c3">
      <span class="c1">Any modern database must fulfill many different requirements which are necessary for functioning as part of information system, such as:</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_l3f4cvceui9t-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">Concurrent data access</span>
        <span class="c1">&#160;– database must be able to handle many concurrent operations on the same set of data while maintaining data consistency. Can we imagine banking, airport control or ticket booking systems which cannot handle securely hundreds or thousands of concurrent clients trying to access them?</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">Data security</span>
        <span class="c1">&#160;- this is a multi-faceted issue. Security can be considered from many different viewpoints. Data is valuable, its acquisition is usually costly and its loss may be devastating for a company (e.g. banking systems).</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">Independence of the data and the processes using it</span>
        <span class="c1">&#160;– this property has a big impact on the possibility of the future development of an information system and of a widespread use of databases as part of it. One database can be accessed by many processes, run by different applications on various platforms. The DBMS should be able to handle them independently of their platform or technology.</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">We should always remember that the costs of fulfilling of each aforementioned requirements </span>
      <span class="c4">are proportional to the quality of the solutions adopted</span>
      <span class="c2">. On the other hand cheaper solutions may turn out to be </span>
      <span class="c4 c5">much more costly on the long run!</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c46 c18" id="h.5pmg1zdim2gb">
      <span class="c14 c5">Does information always have value?</span>
    </h1>
    <p class="c3 c20">
      <span class="c1">We can conclude that information has value if it is:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_wkdyljpeit7k-0 start">
      <li class="c21 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c16">Correct</span>
        <span class="c1">&#160;– it contains true information about specific subject. It is obvious that keeping the false information does not make sense. Of course it does not mean that all of the information stored in a database are always correct. The reasons behind it may vary – starting from errors in data model structure or errors during writing or reading process, finishing with a deliberate act of data manipulation.</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c16">Accurate</span>
        <span class="c1">&#160;– information should be neither too accurate nor too general. Storing and searching the database is costly. From this we can conclude that storing too detailed data can generate unnecessary cost. On the other hand absence of important data can render information to be inaccurate or false. This is why the phase of designing the correct database structure is so important, especially the decisions we make about the level of detail that we want to store.</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c16">Available</span>
        <span class="c1">&#160;– time required to access the information must be adequate to the importance of data. Of course “time of access” is a relative term. One hour may be the proper time frame for generating a company annual balance sheet but it is surely unacceptable for checking the train timetable. Incorrect database structure and incorrect methods of acquiring data can prevent access to data in a reasonable time. In this kind of situation changing the hardware configuration (e.g. adding more RAM) wouldn’t help in a long run and would generate additional costs.</span>
      </li>
    </ul>
    <h3 class="c46 c18" id="h.wphh6kcmkzgn">
      <span class="c17 c5">Databases are everywhere</span>
    </h3>
    <p class="c3 c20">
      <span class="c1">Considering why databases have become such an important part of information technologies we should point out two main aspects: formalizing of the database concept and emergence of consistent data model, on which a number of applications were developed, allowed to solve a number of problems caused by:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_qxqu9g2j7hjr-0 start">
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          A ubiquity of information,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          Creation of various data sets with increasing level of volume and complexity,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          The widespread need for availability of data with lower access time,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          Easy and widespread possibility of generating new data sets.
        </span>
      </li>
    </ul>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">Of course the Internet and its popularity has had a big influence all over the world as Web 2.0 became more popular – every Internet user is now both the consumer and the producer of data.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">We can assume without hesitation that every IT - related project nowadays uses some kind of database, either internal (integral part of the project) or external (which shares its data through a specific interface). Moreover it is possible that one IT project uses multiple databases or that one database is used by multiple IT projects.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">The field of database systems represents nowadays one of the largest and most active segments of software market (which means good earning possibilities). Creating and management of databases involves almost all branches of the modern IT:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_uy6mucuvaggy-0 start">
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          Operating systems,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          IT theory,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          Artificial Intelligence,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          Logic,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          Programming languages,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          Multimedia,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          Software engineering.
        </span>
      </li>
    </ul>
    <h3 class="c46 c18" id="h.gcg8zxtc2x9w">
      <span class="c17 c5">Control questions</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">What does the term “redundancy” mean?</span>
    </p>
    <p class="c10">
      <span class="c1">Storing data which is contradictory.</span>
    </p>
    <p class="c10">
      <span class="c1">Lack of data, which prevents acquiring the correct information.</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">Unnecessary/redundant data in the database.</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">Does the information access time decide about the quality of IT solution?</span>
    </p>
    <p class="c10">
      <span class="c1">No, time required to access the required information is irrelevant if we are able to acquire it.</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">The information access time is one of the main parameters determining the quality of the DBMS.</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.ujsqfixu6rks">
      <span class="c14 c5">Data models – what is it?</span>
    </h1>
    <p class="c3">
      <span class="c1">Data model is a data storage structure which allows us to anticipate where and in what form data will be stored and how it will be queried and read. In a relatively short span of IT technology evolution a few models have emerged, the most important of which is the relational database model. In fact, the database history can be split into the period before this data model and afterwards.</span>
    </p>
    <h2 class="c9" id="h.ot2mrazto7b">
      <span class="c5 c59">“Classical” data models</span>
    </h2>
    <h3 class="c9" id="h.bnzlqibd2d8g">
      <span class="c17 c5">The card index model</span>
    </h3>
    <p class="c3">
      <span class="c1">Data is stored in records within one or more tables of identical structure. The records can be sorted and filtered. Each table is an independent document without the possibility to cooperate with the others. The phone book in a mobile phone or tables in Excel or Word are good examples of this model.</span>
    </p>
    <h3 class="c9" id="h.utzqb4ebs8rw">
      <span class="c17 c5">The hierarchical model</span>
    </h3>
    <p class="c3">
      <span class="c1">In this model the data is stored in the form of records linked by forming a parent - child relation structure. Each record has one parent. If record has more than one parent it must be copied to keep the aforementioned rule. Removing the records means deleting all off its descendants. This model should be familiar from our file system. In order to operate on data we can use traditional programming languages like C, Pascal or others.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">Searching through data in a hierarchical database requires looking through all of the descendant records. An example of this database model can be found in a family tree. In the world of IT we can find this model in our file systems.</span>
    </p>
    <h3 class="c9" id="h.xj1kyrxv2i1w">
      <span class="c17 c5">The network data model</span>
    </h3>
    <p class="c3">
      <span class="c1">This model is an extension of the hierarchical data model. It allows to add pointers which allow for sharing “branches” of the data tree structure among records. Relations between records are defined by creating the collections of data which thus model an owner - member relationship. Each record can enter multiple relationships.</span>
    </p>
    <h3 class="c9" id="h.te2ghpi8dx64">
      <span class="c17 c5">The relational model</span>
    </h3>
    <p class="c3">
      <span class="c1">The relational data model represents a radical change in comparison to the classical database models whose functioning is based on the concept of file and records (lines) written in it. The relational model turned out to be a great success as it gave a solution to many important problems. It introduced a lot of well thought out solutions which were a turning point in developing highly scalable database solutions (e.g. SQL language, advanced “engines” for processing data). Because of that it has become a reference point for further development of the database solutions.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">On the other hand the relational model is more than 40 years old. This is a long time in the IT industry. Nowadays there are more modern approaches to solve similar problems.</span>
    </p>
    <h3 class="c9" id="h.os4cspc1k2r0">
      <span class="c17 c5">Object databases</span>
    </h3>
    <p class="c3">
      <span class="c1">The concept of object databases emerged when it became necessary to work with non-objective data structure in objective programming languages. The “objects” in object database represent real life entities and they possess certain identity. Object type (class) defines complex data type which can contain other data types or collections of data types. Data structure is characterized by strong encapsulation (inner structure of the object is not visible to the user). Moreover, the knowledge of this structure is not necessary for using the specific object. The object inherits the structure, properties and methods from its class. In spite of the beauty of such solution (in terms of the IT theory) it hasn’t become as popular as the relational data model due to the enormous cost of replacing already working relational solutions with object databases. On the other hand it doesn’t seem to solve one of the most important problems of the modern IT technology which is processing very large volumes of data (the “Big Data” problem).</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">However there are some solutions developed by object databases which have been introduced into the relational databases resulting in structures called object - relational solutions.</span>
    </p>
    <h3 class="c9" id="h.uwnqxdlfpm73">
      <span class="c17 c5">Modern data models</span>
    </h3>
    <p class="c3">
      <span class="c1">Actually this is the end of the history of “well-defined” data models. Modern technologies (Internet, cloud-related technologies) force us to develop other approaches to data processing. Instead of the “data model” we now prefer to talk about the “Database Management System”.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">All of the classical data models assumed the existence of predetermined, rigid structure for storing data. This approach was very convenient especially when it comes to data querying. However it doesn’t work well when faced with challenges of modern world like common Internet access and the Web 2.0 philosophy.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">The main problem is the need for processing very large volumes of unstructured data in small time frame, for example the data generated by social sites like Facebook, Twitter, and internet search engines (Google) or services used for storing data in the cloud. The solutions for this problem are database management systems (or data models) which deliberately abandon various requirements of the traditional data models, like the control of replication or uniform data model (there is a few more but we will leave it for now).</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">The DBMS’s which perform these tasks are called the NoSQL Databases (Not Only SQL).</span>
    </p>
    <h3 class="c9" id="h.b084kg8ictiw">
      <span class="c17 c5">Graph databases</span>
    </h3>
    <p class="c3">
      <span class="c1">A graph database is based on the concept of a graph. Each node represents an object and the data associated with it. Graph’s edges (named and directed) represent relations between objects. Typically this kind of database is used for modelling of social networks.</span>
    </p>
    <h3 class="c9" id="h.wrd1v9za2gn2">
      <span class="c17 c5">Semantic Web</span>
    </h3>
    <p class="c3">
      <span class="c1">This concept (it can hardly be called a data model) assumes the emergence of a technology and standards which allow machines and programs to search and process data based on its semantics. In this case we treat Internet and its resources as “the database”.</span>
    </p>
    <h3 class="c9" id="h.f77ot057a8th">
      <span class="c17 c5">Map Reduce</span>
    </h3>
    <p class="c3">
      <span class="c1">Again it is difficult to call this a data model. Here we deal with the concept of storing and concurrently processing of large volumes of data within big data clusters. It comes down to dividing the problem into various smaller ones which then can be split among different clusters. The results from the clusters are returned and merged together into one global solution. This concept has already a few implementations and is currently in the development stage.</span>
    </p>
    <h1 class="c36 c22" id="h.ea52hcnys12u">
      <span class="c14 c5">A short history of databases</span>
    </h1>
    <ul class="c8 lst-kix_poxumw20mduo-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">1961</span>
        <span class="c4">&#160;– Integrated Data Store IDS</span>
        <span class="c1">&#160;(author: Charles Bachman for General Electric) – first DBMS, first implementation of the network data model</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">Started in </span>
        <span class="c16">1966</span>
        <span class="c2">, first-ever run in </span>
        <span class="c16">1968</span>
        <span class="c4">&#160;– Information Management System IMS –</span>
        <span class="c1">&#160;Created by the IBM consortium along with the Rockwell and Caterpillar for the purpose of managing the technical documentation of Saturn V rocket ship and Apollo capsule. Realized according to the hierarchical data model (is still in use).</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">1970</span>
        <span class="c2">&#160;– dr Edgar Codd (IBM employee at that time), proposed basic principles of relational data model in the article </span>
        <span class="c2 c38 c25">“A Relational Model for Larged Shared Data Banks”</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">1969</span>
        <span class="c2">&#160;– the first specification of the network data model known as </span>
        <span class="c4">CODASYL</span>
        <span class="c1">. There have been many implementations loosely based on this specification. The ISO/ANSI standardization was created in 1968 but it gained no practical significance.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">First half of 1970s</span>
        <span class="c2">&#160;– first prototype of SQL query language called </span>
        <span class="c4">Sequel</span>
        <span class="c2">&#160;(authors: Donald Chamberlain and Robert Boyce) was created in IBM’s laboratory in San Jose. However the name had to be changed to the </span>
        <span class="c4">Structured Query Language (SQL)</span>
        <span class="c2">&#160;due to the naming issues with a British company called </span>
        <span class="c2 c25 c38">Hawker Siddeley.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">1974</span>
        <span class="c2">&#160;– first relational database management system and first implementation of SQL – </span>
        <span class="c4">System R</span>
        <span class="c2">&#160;in </span>
        <span class="c2 c25">IBM</span>
        <span class="c1">. In the beginning it was treated as a research project. Their first commercial client was Pratt &amp; Whitney in 1977.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">1976</span>
        <span class="c1">&#160;– Peter Chen created the concept of the entity data model (ERD, ERM) as the methodology for designing and analyzing database structure. It has become the base of the future CASE solutions and repositories. However it hasn’t been standardized so far.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">1977</span>
        <span class="c2">&#160;– the company called </span>
        <span class="c2 c25">Software Development Laboratories</span>
        <span class="c2">&#160;was crated. In 1979 it was renamed to </span>
        <span class="c2 c25">Relational Software Inc.</span>
        <span class="c2">&#160;and in 1982 it was renamed once more to </span>
        <span class="c2 c25">Oracle Systems Corporation</span>
        <span class="c1">. The company started to work on a database system compatible with Codd’s relational data model. In 1979 they introduced their first commercial database solution called ORACLE 2.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">1983</span>
        <span class="c2">&#160;– IBM introduced system called </span>
        <span class="c4">DB2</span>
        <span class="c2">&#160;which was the successor of </span>
        <span class="c4">System R</span>
        <span class="c2">. It was the first fully commercial relational database. In the beginning it was used only with the mainframe computers produced by the </span>
        <span class="c2 c25">IBM</span>
        <span class="c1">.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">1986</span>
        <span class="c1">&#160;– the first standard of the SQL language (ANSI)</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">1987</span>
        <span class="c1">&#160;– the first standard of the SQL language (ISO)</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Next versions of the ANSI/ISO standard: 1989, 1992 (SQL2), 1999 (object - relational data model), 2003, (SQL:2003, XML databases), 2006 (SQL:2006, usage of SQL with XML), 2008 (SQL:2008).</span>
      </li>
    </ul>
    <h3 class="c9" id="h.57tdhgsq6m6g">
      <span class="c17 c5">Further development of databases</span>
    </h3>
    <p class="c3">
      <span class="c1">1990s – the database theory was expanded to include the following aspects:</span>
    </p>
    <ul class="c8 lst-kix_o316414q4358-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">Multilayer architecture</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Distributed data</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Concurrent access methods</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Internet as a data access technology</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Data warehouses and OLAP (On-Line Analysis Processes)</span>
      </li>
    </ul>
    <p class="c3">
      <span class="c1">Databases are used in new technologies:</span>
    </p>
    <ul class="c8 lst-kix_8nyroabd25ur-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">Storing and sharing multimedia</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Storing documents (including XML data)</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">GIS (Geographical Information Systems)</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Utility systems – ERP (Enterprise Resource Planning) and MRP (Management Resource Planning) – packages like SAP, Baan, Oracle, PeopleSoft, Siebel, CRM (Client Relationship Management)</span>
      </li>
    </ul>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.o6tgyls23huf">
      <span class="c5 c14">Summary</span>
    </h1>
    <p class="c3">
      <span class="c1">In the second lecture we presented the history of databases and their importance in the modern information technologies, and thus in many branches of economy and administration. We introduced different concepts of data models including the relational data model. In the next lectures we will discuss the relational data model in detail.</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c44" id="h.sg12l7vufjzd">
      <span class="c49 c55">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62109/chapter/25896&amp;sa=D&amp;source=editors&amp;ust=1714064099699058&amp;usg=AOvVaw1v4gCqauJJWZiVsZcYgZgD">2 </a>
      </span>
      <span class="c48 c50">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62109/chapter/25896&amp;sa=D&amp;source=editors&amp;ust=1714064099699423&amp;usg=AOvVaw2nCslZ3faL7ehjslDxABXU">Lesson III - Relational database model</a>
      </span>
    </h1>
    <p class="c13">
      <span class="c34 c5">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62109/chapter/25896&amp;sa=D&amp;source=editors&amp;ust=1714064099699733&amp;usg=AOvVaw1C4mw_YVCXXCUB3BGOEmnz">15.03.2024 11:45 | Number of chapters: 9</a>
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.d32pk657wso1">
      <span class="c14 c5">New skills and knowledge</span>
    </h1>
    <p class="c3">
      <span class="c1">In this lecture we will present the idea of a relational database and elementary examples of data structures in the relational model. We will also present so-called Codd’s 12 rules, which constitute the basic assumptions of the relational model. After this lecture student should grasp the general idea of this model. I would like to emphasise that this lecture contains the basic knowledge necessary for understanding the relational model and for further learning of this subject.</span>
    </p>
    <h3 class="c9" id="h.mj42cywc0nj0">
      <span class="c17 c5">Learning outcome</span>
    </h3>
    <ul class="c8 lst-kix_y48cfiwpd1yk-0 start">
      <li class="c27 li-bullet-0">
        <span class="c17">
          <br/>
        </span>
        <span class="c1">Student knows who was the inventor of the relational database model,</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          Student understands the concept of data storage in a logical table structure and the idea of recording the relationship between data written in many different tables,
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          Student can define the concepts of a primary key and a foreign key and understands their function in the relational database model,
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          Student knows and understands the notion of a relation as a mathematical model of a database table,
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          Student understands the notion of the pseudo-value NULL and knows the results of algebraic, text and logical operations using NULL.
        </span>
      </li>
    </ul>
    <h1 class="c36 c22" id="h.ym7kz14xohlc">
      <span class="c14 c5">The origin of the relational database model</span>
    </h1>
    <p class="c3">
      <span class="c1">Edgar Frank Codd was the founder of the relational database model. A short biographical note from Wikipedia is enclosed below</span>
    </p>
    <p class="c3">
      <span class="c4">Edgar Frank “Ted” Codd</span>
      <span class="c1">&#160;(19.08.1923-18.04.2003) was an English computer scientist, famous for introducing the relational database model. He studied maths and chemistry at University of Oxford. During the Second World War he served as RAF pilot. In 1948 he moved to New York to work for IBM as a mathematical programmer. In 1953 (at the time of McCarthy’s commission) he moved to Ottawa, Canada. A decade later he returned to the USA and received his doctorate in computer science from the University of Michigan in Ann Arbor. After that he moved to San Jose, California, to work for the IBM. During 1960’s and 1970’s he worked out his theory of data arrangement, issuing his fundamental paper “A Relational model of Data for Large Shared Data Banks” in 1970. To his disappointment, IBM proved slow to exploit his suggestions until the commercial rivals such as Oracle (formulated by Larry Ellison and based on Codd’s ideas) started implementing them. Codd also coined the term OLAP (Online analytical processing) and wrote “the twelve laws of online analytical processing”. He also had a contribution to the cellular automata theory. Codd received the Turing Award (computer science “Nobel Prize”) in 1981.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 211.00px; height: 291.00px;">
        <img alt="" src="images/image4.png" style="width: 211.00px; height: 291.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">Initially the relational model was sceptically received as other data storage systems had already been in use. The Integrated Data Store developed on the basis of the network data model by General Electric, and IBM-made Information Management System, based on the hierarchical model were already available. Nevertheless, its popularity grew in time and soon the relational database model became the most popular.</span>
    </p>
    <p class="c3">
      <span class="c1">Today, despite the emergence of next generation models (the objective and the semantic ones) applications implementing the relational models still dominate the market. This is due to its simplicity and flexibility, high quality of the relational model-based DBMSs as well as large amounts of data already stored in relational databases. We do observe though a tendency to include some features of the objective models into the relational model, giving rise to the so-called objective-relational database model.</span>
    </p>
    <h1 class="c46 c18" id="h.iofhhbsrv5jj">
      <span class="c14 c5">Relational database model, the first elementary example</span>
    </h1>
    <p class="c3 c20">
      <span class="c1">In the next lectures and during other database related courses the relational database model will be presented in more detail. In this lecture the basic principles of this model will be presented using an elementary (but representative) example.</span>
    </p>
    <p class="c3 c20">
      <span class="c1">The basic principles of relational database model are:</span>
    </p>
    <ul class="c8 lst-kix_sz2een1y35py-0 start">
      <li class="c21 li-bullet-0">
        <span class="c1">All data is written in the form of tables</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c2">A table contains </span>
        <span class="c16">columns </span>
        <span class="c2">which include data of a </span>
        <span class="c4 c5">specific type</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c2">A table cell (on the intersection of row and a column) contains a </span>
        <span class="c16">single, atomic, indivisible value</span>
      </li>
    </ul>
    <p class="c3 c20">
      <span class="c1">These three conditions are enough for now.</span>
    </p>
    <h3 class="c46 c18" id="h.es1fsso9746u">
      <span class="c17 c5">Relational model: the first elementary example</span>
    </h3>
    <h3 class="c46 c18" id="h.77qb23rme63">
      <span class="c17 c5">Assumptions</span>
    </h3>
    <p class="c3 c20">
      <span class="c1">Let us assume that we want to record information about courses and lecturers at our school. We assume that each course has only one lecturer, but every lecturer can be responsible for many courses.</span>
    </p>
    <p class="c3 c20">
      <span class="c1">We need to guarantee unambiguous identification for every lecturer and every course and we also have to attribute every lecturer the courses taught by him or her.</span>
    </p>
    <p class="c3 c20">
      <span class="c2">In accordance with the above formulated postulate that all the data must be written as tables, we will start by creating a table of </span>
      <span class="c33">LECTURERS</span>
      <span class="c1">.</span>
    </p>
    <p class="c3 c20">
      <span class="c1">This table will include each lecturer’s personal and professional data – name, surname and his or her scientific degree. Every row (record) will include the data of one lecturer. In order to be able to distinguish between the data of each lecturer independently from their names and surnames (which can in principle be the same for different people!), each record (and thus also the lecturer) is identified by an additional field (i.e. a column) named Lecturers_Id. It is essential that each lecturer has an unambiguous, unique identifier, because in the relational model a row can only be identified by the values stored in the columns. Since we have assumed that the lecturers’ names and surnames are not unique we need to include a column whose value uniquely identifies a row.</span>
    </p>
    <p class="c6 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 682.00px; height: 163.00px;">
        <img alt="" src="images/image74.png" style="width: 682.00px; height: 163.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c20 c28">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">We now need to prepare the </span>
      <span class="c33">COURSES</span>
      <span class="c1">&#160;table. This table will include the courses data: the name of the course, its code and the Lecturers_ Id. Note that its value doesn’t describe any feature of the course itself, but rather represents the relation between the course and its lecturer, whose data can be accessed in different table using the Lecturers_Id.</span>
    </p>
    <p class="c6 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 557.00px; height: 217.00px;">
        <img alt="" src="images/image34.png" style="width: 557.00px; height: 217.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c20 c28">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">Adding an unambiguous key for each row to the table </span>
      <span class="c33">LECTURERS</span>
      <span class="c2">&#160;allows us to connect rows from the tables </span>
      <span class="c33">LECTURERS</span>
      <span class="c2">&#160;and </span>
      <span class="c33">COURSES</span>
      <span class="c1">. Thus there is no need for each row to include all the data (name, surname, degree) of the course’s lecturer. In fact this would lead to redundancy: one piece of information (the lecturer’s data) would be stored in many places.</span>
    </p>
    <p class="c3 c20">
      <span class="c2">The value of the Lecturers_Id will appear in the </span>
      <span class="c33">COURSES</span>
      <span class="c2">&#160;table as many times as many courses the lecturer is responsible for. On the other hand, each course is connected with at most one lecturer and the “Data warehouses” course is not connected to any elements of </span>
      <span class="c33">LECTURERS</span>
      <span class="c1">, which simply means that the course has no lecturer assigned yet.</span>
    </p>
    <h3 class="c46 c18" id="h.ppimt9knpvy9">
      <span class="c17 c5">Control questions</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">Can we have 9999 in the index for the Lecturers_Id table in the elementary example above?</span>
    </p>
    <p class="c10">
      <span class="c1">Yes, we can</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No, we can't</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">Which option for the row “Data warehouses” would be better: leaving a cell LECTURERS_ID empty, or filling it with a value not appearing in Lecturers_Id column in LECTURERS table?</span>
    </p>
    <p class="c10">
      <span class="c1">It is better to leave the cell empty.</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">It is better to fill in the cell with arbitrary value.</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.e5dd3sshsei6">
      <span class="c14 c5">Primary, alternate and foreign keys</span>
    </h1>
    <p class="c3">
      <span class="c2">Each table must have an unambiguous index which is called the </span>
      <span class="c16 c49">primary key</span>
      <span class="c1">. It represents one or more columns, whose values unambiguously identify the row (record). The primary key value must be specified and unambiguous.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">An </span>
      <span class="c16 c49">alternate key</span>
      <span class="c1">&#160;(called also candidate key or just key) has the same uniqueness property as the primary key, but there is only one primary key and there can be several alternative keys.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">In the </span>
      <span class="c33">COURSES</span>
      <span class="c2">&#160;table </span>
      <span class="c4">Code</span>
      <span class="c2">&#160;is the primary key, while </span>
      <span class="c4">Name</span>
      <span class="c2">&#160;is an alternate key. These keys specify the course uniquely in a natural way if we assume that no 2 courses can have the same name or code. In the </span>
      <span class="c33">LECTURERS</span>
      <span class="c2">&#160;table </span>
      <span class="c4">Lecturers_Id</span>
      <span class="c1">&#160;is the primary key. The family name, the first name or the degree on the other hand cannot be the primary keys, as their values can repeat. It is even possible for all 3 values to repeat. Thus, we have introduced an additional column Lecturers_Id which describes no physical feature of the lecturer, but which is used as a unique identifier of a lecturer.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">A foreign key is one or more column whose value is the primary key identifying a row in another table.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">In the </span>
      <span class="c33">COURSES</span>
      <span class="c2">&#160;table the </span>
      <span class="c4">LECTURERS_ID</span>
      <span class="c2">&#160;is a foreign key whose values come from the primary key column of the </span>
      <span class="c33">LECTURERS</span>
      <span class="c2">&#160;table. For example the value 235 in the “Relational databases” lecture points to the row in the </span>
      <span class="c33">LECTURERS</span>
      <span class="c1">&#160;table which contains the information about a lecturer whose surname is Kowalski, whose name is Jan and who holds a PhD. This information may simply be interpreted as:</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">“The ‘Relational databases’ lecture has been assigned to a lecturer named Dr Jan Kowalski”.</span>
    </p>
    <h3 class="c9" id="h.7z5ayiqoiztf">
      <span class="c17 c5">Control questions</span>
    </h3>
    <p class="c13 c29">
      <span class="c4 c5">How many primary keys can table in relational database have?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Up to 1</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Only 1</span>
    </p>
    <p class="c31 c29">
      <span class="c1">Possibly more than 1</span>
    </p>
    <p class="c13 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c29">
      <span class="c4 c5">Does a relational database need to have a foreign key?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Yes, there must be at least one.</span>
    </p>
    <p class="c31 c29">
      <span class="c1">No, there are tables which do not have any foreign key.</span>
    </p>
    <p class="c13 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c29">
      <span class="c4 c5">Is it possible for the foreign key value to be indefinite?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Yes, if we assume this is allowed.</span>
    </p>
    <p class="c31 c29">
      <span class="c1">No, the foreign key value must be specified for each table row.</span>
    </p>
    <p class="c13 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c29">
      <span class="c4 c5">Can a foreign key have an arbitrary value?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Yes, as long as it is consistent with the data type in the column.</span>
    </p>
    <p class="c31 c29">
      <span class="c1">No, we can only use values which have previously been used as primary keys of the appropriate table.</span>
    </p>
    <p class="c13 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c29">
      <span class="c4 c5">Can the value of the primary key remain indefinite?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Yes, if we assume from the beginning that we allow it.</span>
    </p>
    <p class="c31 c29">
      <span class="c1">No, its value has to be set in every row of the table.</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.dc37t270nlx4">
      <span class="c14 c5">Relational database model: elementary example 2</span>
    </h1>
    <h3 class="c9" id="h.bxqzanvpov88">
      <span class="c17 c5">Assumptions</span>
    </h3>
    <p class="c3">
      <span class="c1">Let us modify our assumptions from the previous elementary example. Let us assume now that we need to record data about the courses and the lecturers. Just like before, one lecturer can teach several courses, but unlike the previous example one course can be taught by more than one lecturer.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">The database needs to be able identify uniquely all lecturers and all courses, find all lecturers responsible for each course and all courses assigned to a given lecturer.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">Let us use the data of two lecturers and their courses for our database example: dr Jan Kowalski teaches PPJ, ASD and SBD, and dr Konrad Piotrowski teaches AUG, ASD and RBD.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">The table below shows how tables </span>
      <span class="c33">LECTURERS</span>
      <span class="c2">&#160;and </span>
      <span class="c33">COURSES</span>
      <span class="c1">&#160;can be linked.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 992.00px; height: 288.00px;">
        <img alt="" src="images/image35.png" style="width: 992.00px; height: 288.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">As we can see, our case is now more sophisticated. In order to link the courses with their lectures we would have to write multiple values into the Lecturers_Id column of the table. If we implemented this solution it would mean that we break the atomic rule, which is one of the most important rules in relational model.</span>
    </p>
    <p class="c3">
      <span class="c1">Let us try to implement another solution for our case. Let us then record pairs of records (a lecturer and a lecture) registering this way links between them. Note that we do not need the full records as each record is identified by its primary key. Thus, writing just pairs of primary keys we store sufficient amount of information to link lecturers and their courses.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 247.00px; height: 197.00px;">
        <img alt="" src="images/image68.png" style="width: 247.00px; height: 197.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">Our current scheme is shown below:</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 945.00px; height: 217.00px;">
        <img alt="" src="images/image87.png" style="width: 945.00px; height: 217.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">In order for the scheme to be clear the linking arrows have been left out. As you can see, we managed to record the full information about the links between the lecturers and the courses they hold in a separate table. In a table storing this data (called the junction table) each lecture primary key appears as many times as many lecturers hold it and, conversely, each lecturers primary key appears as many times as many lectures he is assigned to. And what is the primary key in a junction table? Note that the code and the Lecturers_Id taken together must be unique. Repetition of these values would result in redundancy (repeating the same information). Thus the primary key of the junction table is defined as the sum of the 2 foreign keys.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        One final remark: I would like to point out that that thanks to the junction table we have effectively returned to the situation from our 1st example: now each record in the junction table is linked with one
        <br/>
        <br/>
        table record and one 
      </span>
      <span class="c33">COURSES</span>
      <span class="c1">&#160;table record.</span>
    </p>
    <h3 class="c9" id="h.e8z6kbdwuiyh">
      <span class="c17 c5">Control questions:</span>
    </h3>
    <p class="c13 c29">
      <span class="c4 c5">Can we solve abovementioned case without using associative/junction table?</span>
    </p>
    <p class="c29 c35">
      <span class="c1">No, it is not possible.</span>
    </p>
    <p class="c31 c29">
      <span class="c1">Yes, this is possible by entering more than one value of the foreign key in the appropriate column.</span>
    </p>
    <p class="c13 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c29">
      <span class="c4 c5">Is it possible to omit the value in one of the columns of a junction table?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Yes, you can omit one.</span>
    </p>
    <p class="c31 c29">
      <span class="c1">No, no column can be omitted.</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c46 c18" id="h.vt88lvp4rot2">
      <span class="c14 c5">Database – why have we chosen the relational model?</span>
    </h1>
    <p class="c3 c20">
      <span class="c1">In maths we define a relation as a subset of the Cartesian product of two sets.</span>
    </p>
    <p class="c3 c20">
      <span class="c48 c4">Discrete mathematics – short revision</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        <br/>
        The Cartesian product of two sets A and B is a set of all ordered pairs (x,y) such that x is an element of A and y is an element of B.
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">A × B = {(x,y):x ∈ A and y ∈ B }</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">The Cartesian product is not commutative : A×B ≠ B×A</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">For example:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        A={a,b,c}
        <br/>
        <br/>
        B={1,2,3,4}
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        <br/>
        A×B = {a1, a2, a3, a4, b1, b2, b3, b4, c1, c2, c3, c4}
        <br/>
        <br/>
        B×A = {1a, 1b, 1c, 2a, 2b, 2c, 3a, 3b, 3c, 4a, 4b, 4c}
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">Thus:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">A relation on sets A and B is any subset of the Cartesian product A×B, while a relation on B and A is any subset of B×A.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c48 c4">The end of discrete mathematics revision</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        <br/>
        But how is this connected with the main topic of this lecture, i.e. databases? It’s easy to see that the representation of a relation built on two sets is a 2-dimensional table made of 2 columns and as many rows as many elements of relation we have. Obviously a relation on n sets can be represented by a table with n columns. This concept is the basis of the relational database model: all data are stored in two-dimensional tables.
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">
        <br/>
        The set of 13 rules (numbered from 0 to 12) which need to be fulfilled when designing a relational database management system (DBMS) as well as the database model has been published by Edgar Codd in his article “A Relational Model of Data for Large Shared Data Banks” published in 1985. It is known as the 
      </span>
      <span class="c16">“Codd’s 12 Rules”</span>
      <span class="c1">.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">Before we discuss some of the rules in detail we need to introduce two important notions.</span>
    </p>
    <h3 class="c46 c18" id="h.7qw8r0irn16d">
      <span class="c17 c5">Database levels of abstraction</span>
    </h3>
    <p class="c3 c20">
      <span class="c1">A database can be considered on various levels of abstraction:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <ol class="c8 lst-kix_evax12ghdetq-0 start" start="1">
      <li class="c21 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">The external (view) level:</span>
        <span class="c1">&#160;this is the way ordinary users see the data in a database. What he or she sees is usually very different from the data structure on the logical level (i.e. the table structure). What we mean here is the access to the database via client applications, usually using a GUI, for example via a web browser.</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">The logical (conceptual) level:</span>
        <span class="c1">&#160;this is the collection of tables linked by relations as well as all other objects guaranteeing the integrity of the data and its connection to the physical record on a disk. We focus on this level in this lecture, because it is the level on which the database designers and developers operate.</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">The physical level:</span>
        <span class="c1">&#160;the collection of files in a file system in which the data is physically stored. This level is interesting to a rather limited number of users, consisting of the system administrators.</span>
      </li>
    </ol>
    <h3 class="c46 c18" id="h.2qocr64w5ezr">
      <span class="c17 c5">Constraints</span>
    </h3>
    <p class="c3 c20">
      <span class="c1">The constraints are rules whose functions is to guarantee the logical correctness of the data stored in the database. They are defined already in the database designing phase and they are later enforced by the DBMS. We will discuss this in detail further on.</span>
    </p>
    <h3 class="c46 c18" id="h.ca0z7no5uf4h">
      <span class="c17 c5">Control questions</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">Can the Cartesian product of two sets contain 2 identical elements?</span>
    </p>
    <p class="c10">
      <span class="c1">Yes</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">Do we need to consider the files arrangement on the servers’ disks while designing a database?</span>
    </p>
    <p class="c10">
      <span class="c1">Yes</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c46 c18" id="h.1d087txub6fb">
      <span class="c14 c5">View – a useful tool for working with RM (relational model)</span>
    </h1>
    <p class="c3 c20">
      <span class="c1">In the example above it was possible to store data about courses and their lectures in a simple and clear way. It is however much more difficult to read the data about the relations between the records in the LECTURERS and the COURSES table.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">In example 1 we described the relations between lecturers and their courses where we assumed that one course can be taught by only one lecturer, whereas a lecturer can teach several courses. Accessing information stored in these tables is quite simple. If we want to read data about lecturers and their courses, we need to read data from tables. This can be achieved using the links between the rows (records), the primary key values in LECTURERS table and the foreign key values in the COURSES table.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">The relations between the lecturers and the courses are even more difficult to read in Example 2. Recall that we have assumed that ONE lecturer may hold many courses and at the same time ONE course may be simultaneously held by many lecturers. Our solution was to create an additional table just for the relations between courses and lecturers. In this additional junction table we store pairs of foreign keys linking the lecturer with the appropriate course. But this means that in order to find out which lecturer holds which course we need to read data from three tables: the lecturer’s data from LECTURERS, the course data from COURSE and the data about the relation between them from the junction table. This is somewhat cumbersome.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">As you can see, the RM is not particularly user-friendly when it comes to reading the data. We need to read three separate tables and link the appropriate records with the corresponding primary and foreign keys if we want to find out who teaches which course. This process may be simplified if we use objects called VIEWS created as the result of reading the current state of data.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">We present an example of a view containing courses names and lecturers data.</span>
    </p>
    <p class="c6 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 394.00px; height: 172.00px;">
        <img alt="" src="images/image26.png" style="width: 394.00px; height: 172.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c20 c28">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">A view presents data in a way they are seen by the users (and not the database designers). Views provide data (from one or more tables) which are suitable for presentations. The same data can be presented in different layouts by various perspectives.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        The content of a standard view is calculated by the system from the underlying tables. Usually the result of this operation is not permanently stored in the database. What is recorded is the view’s definition (a ‘recipe’ how to prepare it). Although views do not store data, they are often called ‘’virtual tables” as they ‘’provide data’’ for database objects and processes in the same way as it is done through the tables. Moreover, the result of the data reading is the same for the end user irrespective whether it was read from a view or from the tables themselves.
        <br/>
        The end user doesn’t usually know if the provided data come from the table or from a view.
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">In some cases it is more convenient to store the content of a view in the database and use it instead of performing complicated searches which might overload the server. This kind of view is called the </span>
      <span class="c16">MATERIALIZED VIEW</span>
      <span class="c1">. Not all DBMS’s create and store materialized views. Note that although a materialized view is physically stored the same way as a table, there is a significant difference between them. The data in a database are “alive”: the records may be modified, rows may be added or removed. The data in tables are always up-to-date. The data in a materialized view on the other hand constitute a snapshot of the database from a given moment. If the data in the database changed after the materialized view had been made the view remains unaffected. It’s important to realize that.</span>
    </p>
    <h3 class="c46 c18" id="h.35ac4242qkr7">
      <span class="c17 c5">Control questions</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">Can we use a non-materialised view to store data?</span>
    </p>
    <p class="c10">
      <span class="c1">Yes, we can store data in non-materialised view as well as in tables.</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No, a view cannot store data.</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">On which database abstraction level are views used?</span>
    </p>
    <p class="c10">
      <span class="c1">Logical level</span>
    </p>
    <p class="c10">
      <span class="c1">Physical level</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">External level</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <ul class="c8 lst-kix_4ozj8cu0p377-0 start">
      <li class="c21 li-bullet-0">
        <span class="c1">abase objects.</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c16">DML</span>
        <span class="c1">&#160;(Data Manipulation Language) – set of instructions for writing, modifying and deleting data.</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c16">DQL</span>
        <span class="c1">&#160;(Data Query Language) – set of instructions to read data from databases.</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c16">DCL</span>
        <span class="c1">&#160;(Data Control Language) – set of instructions for authorizing and de-authorizing users to access and manipulate data.</span>
      </li>
    </ul>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">The SQL language structure will be presented in more detail in the next lectures and other database related courses. It is important to remember that SQL in its basic form is not a programming language. It does have extensions allowing to use variables, conditional statements, loops, recursion and exception handling. Note however that while the SQL syntax is almost identical in all of its implementations, the extensions are quite different in many aspects. Another big difference between SQL and other programming languages is its declarative character: in SQL we define what operation we need to be executed, but the way it is done is decided by the DBMS. In other words: we decide what needs to be done, but we leave the decision about the way it is done to the DBMS.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <h2 class="c46 c18" id="h.hjg8x2cjpm1d">
      <span class="c5 c60">Rule 10</span>
    </h2>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <h2 class="c46 c18" id="h.cpgp5gq51m9v">
      <span class="c60 c5">Integrity independence.</span>
    </h2>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c23 c38 c25">Integrity constraints specific to a particular relational data base must be definable in the relational data sublanguage and storable in the catalogue, not in the application programs.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">The DBMS must guarantee the possibility to define the integrity constraints and enforce them. Defining database constraints must be possible on the DBMS level, independently from the applications using it. Their modification must be possible at all times without the need to update the applications. Fulfilling this rule guarantees that the constraints defined once and stored in one place will be obeyed by all processes accessing the database.</span>
    </p>
    <h3 class="c18 c46" id="h.k5et0diquzo5">
      <span class="c17 c5">Control questions</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">Which of these objects constitutes the logical data structure in a relational database?</span>
    </p>
    <p class="c10">
      <span class="c1">A file</span>
    </p>
    <p class="c10">
      <span class="c1">A view</span>
    </p>
    <p class="c10">
      <span class="c1">A table</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">A folder</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">You are looking for one piece of information in a database. Is it enough to know the column’s and table’s name to find it?</span>
    </p>
    <p class="c10">
      <span class="c1">Yes</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No, one more information is needed.</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">You are looking for one data in relational database. Is it necessary to know the name of the file where these data are stored?</span>
    </p>
    <p class="c10">
      <span class="c1">Yes</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">What is the result of this operation: X*3 + 12 for X as NULL (pseudo value)?</span>
    </p>
    <p class="c10">
      <span class="c1">12</span>
    </p>
    <p class="c10">
      <span class="c1">15</span>
    </p>
    <p class="c10">
      <span class="c1">NULL</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">0</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">What is the result of FALSE AND NULL logical operation?</span>
    </p>
    <p class="c10">
      <span class="c1">TRUE</span>
    </p>
    <p class="c10">
      <span class="c1">FALSE</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">NULL</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">What is the result of FALSE OR NULL operation?</span>
    </p>
    <p class="c10">
      <span class="c1">TRUE</span>
    </p>
    <p class="c10">
      <span class="c1">FALSE</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">NULL</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">What is the result of TRUE OR NULL operation?</span>
    </p>
    <p class="c10">
      <span class="c1">TRUE</span>
    </p>
    <p class="c10">
      <span class="c1">FALSE</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">NULL</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.b31iblsl85zb">
      <span class="c14 c5">Final remarks</span>
    </h1>
    <p class="c3">
      <span class="c1">This is probably the most important lecture of the whole WSI course concerning the relational databases. We presented the concept of the relational database model, which is built on the relation algebra, briefly outlined here, and the logical idea of recording data in tables. We have also introduced a new notion: the NULL pseudo value modifying the standard logical operations. We will encounter this notion repeatedly in the field of databases, so it is very important to understand what role NULL plays in the elementary logic. Finally the Codd’s rules (only a few presented here, the full list will be discussed on the RBD course) form the axiomatic basis for the relational data model. We need to understand them in order to understand the field of relational databases.</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c44" id="h.68z8ielinddh">
      <span class="c49 c55">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62110/chapter/25905&amp;sa=D&amp;source=editors&amp;ust=1714064099719621&amp;usg=AOvVaw3ZGziaYetkoApwMlRB96bM">3</a>
      </span>
      <span class="c48 c50">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62110/chapter/25905&amp;sa=D&amp;source=editors&amp;ust=1714064099719928&amp;usg=AOvVaw1ngkhpNS2XCP6JVEQblBLa">Lesson IV - Designing database structure</a>
      </span>
    </h1>
    <p class="c13">
      <span class="c34 c5">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62110/chapter/25905&amp;sa=D&amp;source=editors&amp;ust=1714064099720281&amp;usg=AOvVaw0oyhpC7Csh_BTJ6lCWpkZp">15.03.2024 11:45 | Number of chapters: 5</a>
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.g4frtbdgcy5j">
      <span class="c14 c5">Introduction</span>
    </h1>
    <p class="c3">
      <span class="c1">In the previous lecture we learned about the concept of the relational data model. This model assumes that all the data is stored in the logical structures of tables. Its mathematical description comes from the relational algebra. The outline of this model was presented in the second lecture. In the fourth lecture we will discuss the problem of designing a relational database. In particular, we will answer the questions: why do we need to design database structures? How does the design process look like? What tools and notations do we use in the designing process? And finally - how do we create a database using a given model? During the WSI course we will present an outline of these topics. We will discuss them in depth during database related subjects like RBD, SBD and APBD.</span>
    </p>
    <h3 class="c9" id="h.8h5laapfcoep">
      <span class="c17 c5">Learning outcome</span>
    </h3>
    <ul class="c8 lst-kix_szafnxrkjncx-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">Student knows the stages of the database design process, understands the role of these stages and knows what each of these stages involves.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Students knows what do we use the CASE tools for (especially in the context of databases).</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Student understands the terms: “entity” as a representation of a real object and the model of a table in a relational database.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Student knows and understands the terms: entity, attribute, attribute domain, entity key.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Student understands the meaning of a relation as an ordered list of entities, the “parent” entity and the “child” entity.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Student is able to use the CASE tools to create a simple database diagram model consisting of a few entities.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Student is aware of various database diagram notations and knows the notation used in MS Visio.</span>
      </li>
    </ul>
    <h1 class="c36 c22" id="h.plnxhrizzdc">
      <span class="c14 c5">Draft of the database design process</span>
    </h1>
    <p class="c3">
      <span class="c1">In the database design process we can distinguish three main stages or three perspectives defining this process:</span>
    </p>
    <h3 class="c9" id="h.wycv3x73oko3">
      <span class="c17 c5">The Concept design stage</span>
    </h3>
    <p class="c3">
      <span class="c1">At this stage we must define the demand for the project. We can say that this is the marketing stage in which we should decide what functions our customer needs and what his budget limitations are.</span>
    </p>
    <p class="c3">
      <span class="c1">The drafts appearing at this stage are rather vague – they do not contain any details and do not choose any specific technology, but they need to be understandable for the customer and allow him to make corrections. We can compare it to the process involved in the process of designing and building a car.</span>
    </p>
    <h3 class="c9" id="h.e8fmab32dozn">
      <span class="c17 c5">The Logical design stage</span>
    </h3>
    <p class="c3">
      <span class="c1">At this stage we transform the draft into a logical model. We create the model structure, specific solutions for the problem defined at the concept stage which will fulfil the client’s business needs. We design all the segments of the whole solution and define the connections between them. This time we can compare it to an architectural project with general plans but without the technical plans.</span>
    </p>
    <h3 class="c9" id="h.q4ttk7ynnv13">
      <span class="c17 c5">The Implementation stage</span>
    </h3>
    <p class="c3">
      <span class="c1">At this stage we transform the draft into a technological model. We take into account all the constraints due to the available technology, but we must also fulfil all the conditions outlined in the logical design.</span>
    </p>
    <p class="c3">
      <span class="c1">… and then we create the prototype, debug it, implement the solution and we can work on the next improved version.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">As we mentioned earlier a database is usually a part of the whole information system – an important part but not the only one. Because of that it is important to consider the database design rules in the context of the whole system. On the other hand the process of creating the whole system must be preceded by a precise analysis which will give us answers to the following questions:</span>
    </p>
    <ul class="c8 lst-kix_ewlea9l5v2mb-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">What is the subject of our project?</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">What is the purpose of our project, what kind of problems can be solved or improved by using our system?</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">What functions will need to be carried out within our project?</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Who will be using these functions?</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">What kind of information will be stored in our database so that all the aforementioned conditions will be met?</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">What is the predicted cost of this solution?</span>
      </li>
    </ul>
    <p class="c3">
      <span class="c1">From the database designer’s point of view the next to the last question concerning functionality of the future database is the most important one. However the answer to this question depends on the answers to the other questions.</span>
    </p>
    <p class="c3">
      <span class="c2">The problems discussed above belong to the </span>
      <span class="c33">analysis stage</span>
      <span class="c1">&#160;of the designing process.</span>
    </p>
    <p class="c3">
      <span class="c2">Then comes the </span>
      <span class="c33">project stage</span>
      <span class="c1">, in which the future system documentation is written. We should also make a detailed description of the system’s functions and define its users (“actors”). At the same time we should outline the structure of the database in a way which guarantees the possibility to record all the required data. We should also define all the integrity constraints, guaranteeing the logical consistency of data.</span>
    </p>
    <p class="c3">
      <span class="c2">The documentation of the system functions and the definition of the actors is often presented in the form of a </span>
      <span class="c33">use case diagram</span>
      <span class="c1">.</span>
    </p>
    <p class="c3">
      <span class="c2">On the other hand, the implementation model of a database can be represented by the </span>
      <span class="c33">entity relationship diagram</span>
      <span class="c1">.</span>
    </p>
    <p class="c3">
      <span class="c2">The third and final stage is the </span>
      <span class="c33">implementation</span>
      <span class="c1">.</span>
    </p>
    <p class="c3">
      <span class="c1">This description should be sufficient to explain what the entity diagram is and what role it plays in the design process. This role will be explained further on.</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.jt5z6afco0mw">
      <span class="c14 c5">What is an entity relationship diagram (ERD)?</span>
    </h1>
    <p class="c3">
      <span class="c2">An </span>
      <span class="c33">entity relationship diagram</span>
      <span class="c1">&#160;is a model which can represent a part of reality needed for the system and also the database structure. Just like every model it represents a simplification of the real or database object it describes. At the stage of preliminary analysis the objects needed for our database are identified. The role of the entity diagram is to create models of these objects and relationships between them. The graphic character of the diagram makes it easier to understand the database structure. It is important to understand the relationships between the database objects which can often be quite complicated.</span>
    </p>
    <p class="c3">
      <span class="c1">The use case diagram presented in the previous lecture was basically the input data for graphical user interface (GUI). The entity relationship diagram has a different function as it is a model of the data structure. Thus, it puts aside client’s perspective of our application, or deals with it in a small extent.</span>
    </p>
    <p class="c3">
      <span class="c1">There is a list of requirements for a proper entity relationship diagram. It should</span>
    </p>
    <ul class="c8 lst-kix_ahbvbvxjsk00-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">Unambiguously present users’ requirements for the data stored in it,</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Allow to check if the analyst fully grasped the users’ requirements and the character of the environment in which the system will be utilized,</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Be much simpler from the database itself , as it puts aside the implementation details, which must be later developed by the database designer so that our database can exist and carry out its tasks.</span>
      </li>
    </ul>
    <h3 class="c9" id="h.ng4k599psonj">
      <span class="c17 c5">CASE (Computer Aided Software Engineering) tools</span>
    </h3>
    <p class="c3">
      <span class="c1">CASE tools are specialized programs which aid the designing of the information systems and allow to create various types of diagrams useful in the design process. The CASE tools provide graphic tools to design and draw diagrams on screen. The tools used to create the entity relationship diagrams must take into account the specific details of various database servers, for example the available data types. They should be (and usually are) able to translate the graphical version of the diagram into an SQL script. The script can then be run in the appropriate DBMS environment in order to generate all the database objects and integrity constraints.</span>
    </p>
    <p class="c3">
      <span class="c1">In our lectures diagrams are made in Microsoft Visio for Enterprise Architects 2003.</span>
    </p>
    <h3 class="c9" id="h.b2gm17ee6mfm">
      <span class="c17 c5">Entity</span>
    </h3>
    <p class="c3">
      <span class="c33">Entity</span>
      <span class="c2">&#160;(lat. </span>
      <span class="c33">Entia</span>
      <span class="c1">
        ) – an entity is a singular, independent object which can be described and whose description can be stored in database.
        <br/>
        In the world of databases, the term entity is used to describe (model) things (objects phenomena, relationships etc.) about which we will collect data in our database. Every entity has a name that must be unique for a given database.
      </span>
    </p>
    <p class="c3">
      <span class="c1">The definition of an entity consists of the attributes (characteristics, properties) which are sufficient to unambiguously distinguish an entity from the other ones.</span>
    </p>
    <p class="c3">
      <span class="c1">We must distinguish the notion of entity as a class of objects and as an instance of this class, i.e. a single instance of the object (single copy) of a given type. For example the “PERSON” entity as a type defines attributes necessary to describe a certain group of people. Only after we substitute specific values for its attributes we obtain an instance of this entity which will represent a particular person. It should be emphasized that if the entity is used to describe a selected class of objects (in our example a specific group of people), each single object of this class (in our case each specific person) must be described with the same attributes. Note that it may be hard in practice to describe two different groups of people, e.g. a group of prisoners and a group of preschoolers, with the same attributes.</span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        But the principle:
        <br/>
        <br/>
      </span>
      <span class="c16">Entia non sunt multiplicanda praeter necessitatem</span>
      <span class="c2">&#160;(novacula Occami) - </span>
      <span class="c16">entities must not be multiplied beyond necessity</span>
      <span class="c1">
        &#160;– known as the Occam's razor
        <br/>
        <br/>
        … also relates to the databases!
      </span>
    </p>
    <p class="c3">
      <span class="c1">Entities are usually represented graphically as rectangles. The graphical representations of entities vary (slightly) according to the notation adopted by the specific CASE tool.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 352.00px; height: 170.67px;">
        <img alt="" src="images/image89.png" style="width: 352.00px; height: 170.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.w90sqgi8dba1">
      <span class="c17 c5">Attribute</span>
    </h3>
    <p class="c3">
      <span class="c2">It is crucial to correctly choose the attributes for describing an entity. Note that attributes represent certain abstract features or characteristics, not the specific values. The attribute of the </span>
      <span class="c33">Student</span>
      <span class="c2">&#160;entity is </span>
      <span class="c11">Name</span>
      <span class="c2">, not a specific value (say “Smith”) the attribute can take. The attribute should describe the entity rather than its relations with other entities, for instance in an airline’s database the attribute </span>
      <span class="c11">Seat_number</span>
      <span class="c2">&#160;should be an attribute of the </span>
      <span class="c33">Airliner</span>
      <span class="c2">&#160;entity, not </span>
      <span class="c33">Passenger</span>
      <span class="c2">, despite the fact that the passenger sits on a specific seat during the flight. In the same way the place won by an athlete in a competition is neither an attribute of the entity </span>
      <span class="c33">Athlete</span>
      <span class="c2">&#160;or </span>
      <span class="c33">Competition</span>
      <span class="c2">, but most preferably the </span>
      <span class="c33">Competition_results</span>
      <span class="c1">&#160;entity.</span>
    </p>
    <p class="c3">
      <span class="c2">Consider now the entity as a model for future table in the database. It is clear that the </span>
      <span class="c4">attributes</span>
      <span class="c2">&#160;are nothing else but the models for the future </span>
      <span class="c4">columns</span>
      <span class="c1">, specifying their names. If we also define their domains, i.e. we specify the data types we will use to store the values of the attribute, we will define the domains of the columns table.</span>
    </p>
    <h3 class="c9" id="h.ozvzsk22kks">
      <span class="c17 c5">First Normal Form (1NF)</span>
    </h3>
    <p class="c3">
      <span class="c1">The concept of the “First Normal Form” (1NF) was formulated as one of the Codd’s rules. It is the first condition we must meet when we normalize the database structure. Its purpose is to eliminate any anomalies in the data insertion, modification and deletion as well as any uncontrolled data redundancy. The whole normalization process and the subsequent normal forms will be thoroughly discussed during the relational databases course in the future semesters.</span>
    </p>
    <p class="c3">
      <span class="c1">An entity (and thus also its corresponding table) is in the first normal form if:</span>
    </p>
    <ul class="c8 lst-kix_nhxf08ng0zjh-0 start">
      <li class="c27 li-bullet-0">
        <span class="c2">It describes one type (one class) of objects; e.g. the information about the car owners and their cars </span>
        <span class="c4">IS NOT</span>
        <span class="c1">&#160;stored in a single entity that contains attributes of both the owners as well as the cars,</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">Its attribute values are elementary (atomic , indivisible) - each column represents a scalar (atomic) value rather than an array, list or anything that has its own structure; e.g. the </span>
        <span class="c11">Person</span>
        <span class="c2">&#160;entity </span>
        <span class="c4">DOES NOT</span>
        <span class="c2">&#160;include an attribute called </span>
        <span class="c11">Names</span>
        <span class="c1">&#160;which contains all the person’s names stored in a list.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">It does not contain collections (i.e. repeating groups of information); e.g. in order to store the information about sportsmen we </span>
        <span class="c4">DO NOT ADD</span>
        <span class="c2">&#160;to the </span>
        <span class="c33">Athlete</span>
        <span class="c2">&#160;entity an attribute called </span>
        <span class="c11">Medals</span>
        <span class="c1">&#160;containing all the medals won by him or her.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">It has a key, i.e. a set of attributes whose values distinguish each row from the other ones.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">The order of the attributes should not encode any information, i.e. any change in the order of attributes should have no influence on the information content; e.g. in order to record information about the competition results we </span>
        <span class="c4">DO NOT</span>
        <span class="c2">&#160;create an entity called </span>
        <span class="c33">Result</span>
        <span class="c2">&#160;with attributes </span>
        <span class="c11">Athlete 1, Athlete 2, Athlete 3, ...</span>
      </li>
    </ul>
    <p class="c3">
      <span class="c2">The above definition of the </span>
      <span class="c4">1NF</span>
      <span class="c1">&#160;is a bit of an over-interpretation of the original one. The latter consists only of the first three points, but I allowed myself to extend it slightly for the sake of the further argument. All the information above is true and correct .</span>
    </p>
    <h3 class="c9" id="h.tkbn1smoyd9x">
      <span class="c17 c5">Key</span>
    </h3>
    <p class="c3">
      <span class="c2">The term </span>
      <span class="c4">"entity key"</span>
      <span class="c2">&#160;describes a set of entity's attributes whose values are unique (unambiguous) for its every instance. Similarly, the term </span>
      <span class="c4">"table key"</span>
      <span class="c2">&#160;describes a set of columns whose values will be unique (unambiguous) for every row in the table. Obviously it is possible that these sets contain only one element. Each table (entity) may contain none, one or more sets fulfilling the uniqueness condition, for example the </span>
      <span class="c11">Social security number</span>
      <span class="c2">&#160;or the </span>
      <span class="c11">PESEL</span>
      <span class="c2">&#160;can be the key in the </span>
      <span class="c33">Person</span>
      <span class="c2">&#160;entity or the </span>
      <span class="c11">Registration_number</span>
      <span class="c2">&#160;in the </span>
      <span class="c33">Car</span>
      <span class="c1">&#160;entity. However if there is no attribute with the uniqueness property in the entity we need to add an artificial attribute (column in the table) that meets this requirement. This is usually an attribute of integer type. The table column will then contain integers which uniquely identify the instances. But it can also be an attribute of the text type – e.g. the lecture code in the studies curriculum.</span>
    </p>
    <p class="c3">
      <span class="c2">If the entity has more than one set of attributes whose values meet the requirement of uniqueness for every instance of the entity, then you should arbitrarily choose one of them to act as the primary key. If the entity has only one set, then there is no dilemma involved - it automatically becomes a </span>
      <span class="c4">primary key</span>
      <span class="c1">. Thus, we can identify a few keys in the entity, but only one of them can be used as our primary key.</span>
    </p>
    <p class="c3">
      <span class="c1">Every CASE tool allows us to select the attribute (or multiple attributes) as the primary key during the design phase of our diagram. The illustration below shows this process in MS Visio.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 638.67px; height: 324.00px;">
        <img alt="" src="images/image22.png" style="width: 638.67px; height: 324.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.e2lsdfkedar9">
      <span class="c17 c5">Data types – attributes domains</span>
    </h3>
    <p class="c3">
      <span class="c1">Data types or attribute domains are sets of values which can be stored by variables in the table columns. The principal types of data which we will encounter in every DBMS is the numeric type, the text type and the date type. For each of these types specific implementations provide a number of subtypes. For example: for a numeric type there is the two-byte integer and the four-byte one, the floating point number stored in four or eight bytes etc. Therefore we should find out what types are available before we start working in the specific DBMS environment.</span>
    </p>
    <p class="c3">
      <span class="c1">When we speak about the entity-relationship diagram as a model of the future database we operate on the level of abstract concepts. On the other hand, on the database level we are closer to the concrete implementation. Hence, at the conceptual level (entity-relationship diagram) we are talking about the domain types as a general concept. However when we implement the database in a specific DBMS we use the types of data specific to the database solution.</span>
    </p>
    <p class="c3">
      <span class="c2">CASE tools usually offer a choice of one of these approaches - either operate on universal data types not associated with a particular DBMS or choose data types implemented in the specific DBMS. MS Visio distinguishes between these two specifications of the data types. We can choose platform independent data types (</span>
      <span class="c4">Portable Data Type</span>
      <span class="c2">) or database specific data types (</span>
      <span class="c4">Physical Data Type</span>
      <span class="c1">).</span>
    </p>
    <p class="c3">
      <span class="c1">The following illustration shows the selection process of the attribute’s domain (data type) from the drop-down list representing the physical data types (Oracle Server).</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 652.00px; height: 389.33px;">
        <img alt="" src="images/image19.png" style="width: 652.00px; height: 389.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.lf00jwi88ys">
      <span class="c17 c5">Relationship</span>
    </h3>
    <p class="c3">
      <span class="c2">The relationship is defined as an ordered list of entities in the relational model. Individual entities can appear on the list multiple times. Each relationship defines a certain dependence between the sets of copies (instances) of the entities belonging to it. This correlation is called the instance of the relationship. In other words an instance of the relationship is the relationship between the entities instances. For example, the relationship between the </span>
      <span class="c33">Person</span>
      <span class="c2">&#160;entities and the </span>
      <span class="c33">Car</span>
      <span class="c2">&#160;entities can be described as the </span>
      <span class="c11">OwnerOfTheCar</span>
      <span class="c2">. Every instance of the </span>
      <span class="c33">Person</span>
      <span class="c2">&#160;entity will be able to have a relationship with an instance of the </span>
      <span class="c33">Car</span>
      <span class="c1">&#160;entity thus creating information about the cars and their owners.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        The relationship can be formally represented using the relational notation:
        <br/>
        <br/>
      </span>
      <span class="c4">
        Z(E1 ,...,En)
        <br/>
        <br/>
      </span>
      <span class="c2">which means: entities </span>
      <span class="c4">E1 , ..., En</span>
      <span class="c2">&#160;are included in the </span>
      <span class="c4">Z</span>
      <span class="c1">&#160;relationship</span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        You can also describe the relationship verbally, e.g.:
      </span>
    </p>
    <ul class="c8 lst-kix_3ipl4jxrgfvg-0 start">
      <li class="c27 li-bullet-0">
        <span class="c11">An employee works in a department</span>
        <span class="c1">&#160;(relationship between the Employee and the Department entity)</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c11">An employee has a specific function in the project</span>
        <span class="c1">&#160;(relationship between the Employee and the Project entity)</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c11">The company produces goods</span>
        <span class="c1">&#160;(relationship between the Company and the Goods entity)</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c1">In practice, when designing a database, we define relationships through their verbal description.</span>
    </p>
    <p class="c3">
      <span class="c1">&#160;</span>
    </p>
    <h3 class="c9" id="h.lv0e9wpzk9wi">
      <span class="c17 c5">Binary relationship</span>
    </h3>
    <p class="c3">
      <span class="c33">Binary relationship</span>
      <span class="c2">&#160;is a relationship that exists between two entities. It is represented graphically as a line connecting two frames (entities). </span>
      <span class="c33">An instance of a binary relationship</span>
      <span class="c1">&#160;is a two argument relation in the Cartesian product of the entities instances collections.</span>
    </p>
    <p class="c3">
      <span class="c2">The graph below shows the relationship between the </span>
      <span class="c33">Student</span>
      <span class="c2">&#160;and the </span>
      <span class="c33">City</span>
      <span class="c2">&#160;entities . This relationship can be described as follows: </span>
      <span class="c2 c38 c25">every student was born in a city, each student in ONE city, but… many students could have been born in ONE city.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 408.00px; height: 189.33px;">
        <img alt="" src="images/image49.png" style="width: 408.00px; height: 189.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">After defining the relationship in the CASE tool (in our case MS Visio), the primary key from one entity forming the relationship is transferred to the entity on the other side of the relationship. This way we can create a </span>
      <span class="c33">foreign key</span>
      <span class="c1">.</span>
    </p>
    <p class="c3">
      <span class="c2">In the first lecture we described the example of the </span>
      <span class="c33">Course</span>
      <span class="c2">&#160;and </span>
      <span class="c33">Lecturer</span>
      <span class="c2">&#160;tables and a relationship between them: </span>
      <span class="c11">for each course there is one teacher responsible, but one teacher may be responsible for several courses</span>
      <span class="c2">. In that example, the ID of a lecturer was placed in the Courses table and served as the indicator in order to determine which teacher is responsible for that item. A similar case is shown in the example above. The city ID (i.e. primary key of the </span>
      <span class="c33">City</span>
      <span class="c2">&#160;entity) is placed in the </span>
      <span class="c33">Student</span>
      <span class="c2">&#160;entity in order to indicate his or her place of birth. One instance of the </span>
      <span class="c33">Student</span>
      <span class="c2">&#160;entity is associated with one instance of the </span>
      <span class="c33">City</span>
      <span class="c1">&#160;entity, thus creating a single instance of a relationship.</span>
    </p>
    <p class="c3">
      <span class="c2">Let us go back to the definition of the relationship as an ORDERED list of entities. The relationship in our example can be described as follows: ONE student was born in ONE city, but in ONE city MANY students could have been born. This definition is not symmetric! For each student you can specify one city where he or she was born, but for each city we can potentially find many students who were born in it. A relationship of this kind is called a one-to-many relationship. Here the entity </span>
      <span class="c33">City</span>
      <span class="c2">&#160;is located on the </span>
      <span class="c4">ONE</span>
      <span class="c2">&#160;side of the relationship and entity </span>
      <span class="c33">Student</span>
      <span class="c2">&#160;on the </span>
      <span class="c4">MANY</span>
      <span class="c2">&#160;side. We also use other names: </span>
      <span class="c33">Student</span>
      <span class="c2">&#160;represents the child entity and </span>
      <span class="c33">City</span>
      <span class="c2">&#160;represents the </span>
      <span class="c4">parent entity</span>
      <span class="c1">.</span>
    </p>
    <p class="c3">
      <span class="c2">When we define a relationship in a CASE tool, an attribute is automatically added to the entity on the “many” side, containing the value of the primary key of the other entity. Thus we have added a </span>
      <span class="c33">foreign key</span>
      <span class="c1">&#160;to the entity attributes. It will serve as a pointer linking the rows on the “many” side with one row on the “one” side of the relationship.</span>
    </p>
    <p class="c3">
      <span class="c2">In our example MS Visio has automatically created in the </span>
      <span class="c33">Student</span>
      <span class="c2">&#160;entity the attribute </span>
      <span class="c11">IdMiasto</span>
      <span class="c2">&#160;(labeled FK1 - foreign key), defining the relationship between the instances of the </span>
      <span class="c33">Student</span>
      <span class="c2">&#160;entity with the instances of the </span>
      <span class="c33">City</span>
      <span class="c1">&#160;entity.</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.upbx3qqym8cs">
      <span class="c14 c5">Working with MS Visio</span>
    </h1>
    <p class="c3">
      <span class="c2">In the previous section we discussed the concept of an entity and an entity relationship. I tried to convey the meaning of these terms. However, as mentioned above, the practical process of creating the entity relationship diagrams is made using specialized CASE tools. In this section we present the Microsoft CASE tool called MS Visio. We discuss here a version of the MS Visio for Enterprise Architects included in the MS Office 2003, because it is the last version of this program equipped with full functionality we expect from a CASE program. We will also present the newer version MS Visio 2007, unfortunately already deprived of some of its functionality, but sufficient for the learning purposes within the WSI course. The MS Visio 2010, available for the students under the academic license at </span>
      <span class="c30">
        <a class="c12" href="https://www.google.com/url?q=https://software.pjwstk.edu.pl/&amp;sa=D&amp;source=editors&amp;ust=1714064099735460&amp;usg=AOvVaw3-AYW-o4-iAxLXfCOi3vwh">https://software.pjwstk.edu.pl/</a>
      </span>
      <span class="c1">, is almost identical. The latest version of MS Visio 2013, on the other hand, is not suitable for the tasks we will deal with during this course.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">Below are short videos in the MP4 format presenting the basics of working with the MS Visio. These materials are not intended to teach you every detail of creating the entity relationship diagrams, but rather to demonstrate how to use this tool.</span>
    </p>
    <h3 class="c9" id="h.209we2hu124n">
      <span class="c17 c5">Running MS Visio 2003</span>
    </h3>
    <p class="c3">
      <span class="c1">
        In links below are video files which present MS Visio use, which should be attached to the lectures.
        <br/>
        Z:\PBD_nagrania\Uruchomienie Visio
      </span>
    </p>
    <h3 class="c9" id="h.eyqifikk1ycz">
      <span class="c17 c5">Running MS Visio 2010</span>
    </h3>
    <p class="c3">
      <span class="c1">Z:\PBD_nagrania\Uruchomienie Visio 2010</span>
    </p>
    <h3 class="c9" id="h.4gfqpgn6yv6m">
      <span class="c17 c5">Creating entities with MS Visio</span>
    </h3>
    <p class="c3">
      <span class="c1">Z:\PBD_nagrania\Tworzenie encji w MS Visio</span>
    </p>
    <h3 class="c9" id="h.mplk3z3z24if">
      <span class="c17 c5">Creating relationships with MS Visio</span>
    </h3>
    <p class="c3">
      <span class="c1">Z:\PBD_nagrania\Tworzenie związków w MS Visio</span>
    </p>
    <h3 class="c9" id="h.cuzpoo3u0gei">
      <span class="c17 c5">But what do we need these diagrams for?</span>
    </h3>
    <p class="c3">
      <span class="c1">In this chapter we presented the process of designing a database by creating the entity relationship diagrams. We have already said that the entities and their relationships can be thought of as models of some parts of the real world, but at the same time they represent the structure of the future database. But do we obtain from such diagrams something more than just a convenient image of the database structure? Graphic representation of the tables and relationships makes it easier to work with the future database, but is it everything we get? It turns out that the CASE tools have one more (very important) function. Namely, they can generate a DDL script which creates a database. What is a DDL (“Data Definition Language”) script? This is a set of SQL text commands, and in fact also a subset of commands used for creating the database objects. The database server is able to interpret these commands and create a database whose structure has been designed in the form of the entity-relationship diagram.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">Unfortunately, among the tools implemented by the currently available student version of the Visio 2010 there is no DDL generation tool. It is included in the MS Visio for Enterprise Architects (Visio 2003) and is available on the computers in PJATK laboratory. MP4 video below shows how to generate the DDL script of the entity relationship diagram in the MS Visio 2003.</span>
    </p>
    <h3 class="c9" id="h.b80doc9biamz">
      <span class="c17 c5">Generating DDL script from the MS Visio</span>
    </h3>
    <p class="c3">
      <span class="c1">Z:\PBD_nagrania\Generowanie skryptu DDL z MS Visio</span>
    </p>
    <h3 class="c9" id="h.fo1k5kal1aui">
      <span class="c17 c5">Other notations used for creating entity relationship diagrams</span>
    </h3>
    <p class="c3">
      <span class="c1">As previously mentioned, there is no standard for the notation used in the entity relationship diagrams. You could say that every CASE tool introduces its own notation, although most of them are quite similar. However, the notation used in MS Visio (called relational) is quite distinct and rare. Below we present a few examples of the most commonly used notations. The first diagram was made in a relational notation, while the other ones were created in various notations different from the one used in MS Visio.</span>
    </p>
    <h3 class="c9" id="h.kgvhqcsed1zf">
      <span class="c17 c5">Relational notation</span>
    </h3>
    <p class="c3">
      <span class="c1">We first encountered the relational notation while working with MS Visio - this is the basic notation used in this tool. The designations used are simple, yet the diagram contains little information in the graphic layer.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 614.67px; height: 294.67px;">
        <img alt="" src="images/image53.png" style="width: 614.67px; height: 294.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.swhq29gqq0ty">
      <span class="c17 c5">IDEF1X notation</span>
    </h3>
    <p class="c3">
      <span class="c1">The same diagram made in MS Visio, but with the IDEF1X notation. Try to figure out what the signs mean. They will be thoroughly discussed in a different course called “Relational Databases”.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 577.33px; height: 282.67px;">
        <img alt="" src="images/image2.png" style="width: 577.33px; height: 282.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">Once again, the same diagram made in the IDEF1X notation, but with a different CASE tool called Erwin. Unlike the previous ones it can represent an ambiguous relationship (many - to - many) on a diagram without decomposing it into two unambiguous relationships and an associative entity. Of course this will have to be done later at the implementation stage.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 561.33px; height: 240.00px;">
        <img alt="" src="images/image6.png" style="width: 561.33px; height: 240.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.k2o3xi6af6f8">
      <span class="c17 c5">Crow’s Foot notation</span>
    </h3>
    <p class="c3">
      <span class="c1">The name of this notation comes from the symbol of the "many" side of the relationship - the symbol of three lines which is similar to the imprint of a crow’s foot. This example was done using the IBM's Relational Data Architect.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 540.00px; height: 280.00px;">
        <img alt="" src="images/image64.png" style="width: 540.00px; height: 280.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <h1 class="c36 c22" id="h.dfvtt465890y">
      <span class="c14 c5">Summary</span>
    </h1>
    <p class="c3">
      <span class="c2">This lecture is an introduction to the design process of an information system, with particular emphasis on the design of the database. We emphasized the role of the CASE tools in the design process as well as the role of the entity-relationship diagram as a model of the future database. We presented and discussed the basic ERD elements: the entity, the attribute and the relationship and showed examples of the simple entity relationship diagrams in several different notations. The whole issue of the relational database design will be discussed in detail in a different course called “Relational Databases”.</span>
    </p>
    <h1 class="c44" id="h.aw0vc620vrep">
      <span class="c5 c40">4 Lesson V – SQL - relational database language</span>
    </h1>
    <p class="c13">
      <span class="c0">15.03.2024 11:45 | Number of chapters: 10</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c22 c36" id="h.vx24gfu6xgdn">
      <span class="c14 c5">New skills and knowledge</span>
    </h1>
    <p class="c3">
      <span class="c1">One of the Codd’s rules defining the requirements for the relational database model was introducing a complete language which, independently from other programming languages, would perform all the database operations. The Structured Query Language (SQL) was created in order to meet these requirements. The basics of this language will be presented in this lecture. After this lecture student should be able to: write simple commands for data reading, add a new record to the table, change data of the existing table. The student should also know the basic syntax of the commands which create and alter the table structure.</span>
    </p>
    <p class="c3">
      <span class="c1">In the current lecture we will discuss the following topics:</span>
    </p>
    <ol class="c8 lst-kix_hz7e6qe4lbhh-0 start" start="1">
      <li class="c27 li-bullet-0">
        <span class="c1">The origins of SQL</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">The structure of SQL</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">Data types according to the SQL standard</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">The SELECT commands,</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">The commands from the DDL and DML sublanguages.</span>
      </li>
    </ol>
    <p class="c3">
      <span class="c1">Remember that the aim of this lecture is to give an overview of the topic. The details will be discussed more thoroughly in the courses called: Relational Databases and Database Systems.</span>
    </p>
    <h3 class="c9" id="h.yr47y37aety8">
      <span class="c17 c5">Learning outcome</span>
    </h3>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_k9z0wtrlykrk-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">The student can explain the role of the SQL language as a specialized language for relational databases, which is not a programming language</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">The student can name 4 sublanguages of SQL and can describe their application</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">The student can distinguish the data types provided by the language standard and point out the differences in their implementation in various database servers</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">The student knows how to use the basic version of the SELECT command together with the FROM and WHERE clauses and can write a simple SELECT command in a known and simple data structure made of at most two tables.</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">The student can use the DDL commands (CREATE, ALTER, DROP) and the DML commands (INSERT, UDATE, DELETE) in their basic scope.</span>
      </li>
    </ul>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c46 c18" id="h.l5aay1t3raue">
      <span class="c14 c5">The origins of the SQL language</span>
    </h1>
    <p class="c3 c20">
      <span class="c1">Earlier database models, such as the network or hierarchical models, were based on the notion of a file as a named collection of records. The traditional programming languages, like COBOL, PL/I or C, were sufficient for operating on these data structures. The appearance of the relational data model (Edgar C. Codd “Relational model of data for large shared data banks”, 1970) sparked the interest in specialized, “relational” languages which were supposed to implement the theoretical framework in concrete applications. The most advanced research was conducted in IBM, partially due to the fact that the relational database concept emerged in the IBM labs in San Jose. In 1974 the group led by Donald Chamberlin presented the Structured English Query Language, also known under the acronym SEQUEL. Its first, prototype implementation created by IBM appeared in 1974-1975 and was known as the SEQUEL-XRM. It was followed by another version of the language called SEQUEL/2 and in 1977 the SYSTEM R implementation was launched. The name SEQUEL/2 had to be dropped because of legal issues (the name was a trademark of a British aircraft company De Haviland) and the language was renamed SQL. The name soon lost its original meaning as an abbreviation and became the name of a new language.</span>
    </p>
    <p class="c3 c20">
      <span class="c1">The ANSI (American National Standards Institute) standard for SQL, which appeared in 1986, was based on the IBM dialect. The ANSI standard was adopted later by ISO (International Organization for Standardization) as the world standard in 1987. Since then SQL has been standardized a number of times and implemented in many DBMS with varying degree of ANSI standard conformity. To some extend each of these implementations uses its own dialect which differs in details from all others, although all of them remain similar in basic constructions.</span>
    </p>
    <p class="c3 c20">
      <span class="c1">The most popular DBMS’s implementing the relational database model are ORACLE, DB2, PostgresSQL, MS SQL Server, Sybase, MySQL. Each of them implements its own dialect of SQL, none of them satisfies all of the ISO standard requirements and no 2 are identical.</span>
    </p>
    <p class="c3 c20">
      <span class="c2">In the next part of the lecture and in the examples we will mostly work with the Microsoft implementation from the MS SQL Server 2008 R2 (called simply MS SQL further on). For comparison we will sometimes compare it to the ORACLE 11g implementation (ORACLE in short). If we do not discuss differences between the two, then this means that the differences are either insignificant or non-existent.</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.v6veuc3rqhhx">
      <span class="c14 c5">The SQL language structure</span>
    </h1>
    <p class="c3">
      <span class="c1">Due to its name the SQL language is described as a QUERY database language. It is a simplified description, as this language also contains database COMMANDS. In this lectures QUERIES and COMMANDS will be used as synonyms.</span>
    </p>
    <p class="c3">
      <span class="c1">The SQL is a declaratory language, which means that DBMS decides about the physical details of storing and operating on the data. The SQL is used only for database operations. Strictly speaking it is not a programming language, as it does not include the necessary programming structures (variables, conditional instructions, loop instructions). However the SQL implementations usually contain these structures because of their usefulness. We can thus distinguish the pure SQL and its procedural extensions. We will discuss two of those extensions further on: the PL/SQL (the procedural language of the ORACLE DB) and Transact SQL or T-SQL (the procedural language of MS SQL Server).</span>
    </p>
    <p class="c3">
      <span class="c1">
        The SQL language structure.
        <br/>
        Queries – we distinguish four subsets of commands:
      </span>
    </p>
    <ul class="c8 lst-kix_ib9j2ls61eto-0 start">
      <li class="c27 li-bullet-0">
        <span class="c4">SQL DML</span>
        <span class="c1">&#160;– Data Manipulation Language</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c4">SQL DDL</span>
        <span class="c1">&#160;– Data Definition Language</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c4">SQL DCL</span>
        <span class="c1">&#160;– Data Control Language</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c4">SQL DQL</span>
        <span class="c1">&#160;– Data Query Language</span>
      </li>
    </ul>
    <h3 class="c9" id="h.5v13v9acs5su">
      <span class="c17 c5">DQL – Data Query Language</span>
    </h3>
    <p class="c3">
      <span class="c1">The set of commands for reading the data from the database. All commands begin from the SELECT word and their execution doesn’t influence the state of data.</span>
    </p>
    <h3 class="c9" id="h.cvlc80s5wtra">
      <span class="c17 c5">DML – Data Manipulation Language</span>
    </h3>
    <p class="c3">
      <span class="c1">The set of commands responsible for data operations.</span>
    </p>
    <ul class="c8 lst-kix_pxgusehopho8-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">INSERT </span>
        <span class="c1">– entering new data (records) into the database</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">UPDATE </span>
        <span class="c1">– updating (changing) the existing data</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">DELETE </span>
        <span class="c1">– deleting data (records) from the database</span>
      </li>
    </ul>
    <h3 class="c9" id="h.ebrcj241xo2y">
      <span class="c17">
        DDL – Data Definition Language
        <br/>
      </span>
      <span class="c1">The set of commands responsible for manipulating database objects.</span>
    </h3>
    <ul class="c8 lst-kix_uhcf91an71wf-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">CREATE </span>
        <span class="c1">– creating a new database object</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">ALTER </span>
        <span class="c1">– changing the structure of the existing object</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">DROP </span>
        <span class="c1">– deleting an existing object from the database</span>
      </li>
    </ul>
    <h3 class="c9" id="h.26uy24rfey4t">
      <span class="c17">
        DCL – Data Control Language
        <br/>
      </span>
      <span class="c1">The set of commands responsible for granting access to the database operations.</span>
    </h3>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_2zf3qhky0qd4-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">GRANT</span>
        <span class="c1">- granting access to a given database objects</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">REVOKE </span>
        <span class="c1">– revoking access to a given database objects</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">DENY </span>
        <span class="c1">– denies operations on a database object</span>
      </li>
    </ul>
    <h3 class="c9" id="h.tl57r3pgdj0x">
      <span class="c17 c5">Control questions</span>
    </h3>
    <p class="c13 c29">
      <span class="c4 c5">Is it possible to change the database structure using SELECT instruction?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">No</span>
    </p>
    <p class="c31 c29">
      <span class="c1">Yes</span>
    </p>
    <p class="c13 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c29">
      <span class="c4 c5">Which of the commands can alter data recorded in a database?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">SELECT</span>
    </p>
    <p class="c35 c29">
      <span class="c1">ROLLBACK</span>
    </p>
    <p class="c35 c29">
      <span class="c1">UPDATE</span>
    </p>
    <p class="c35 c29">
      <span class="c1">GRANT</span>
    </p>
    <p class="c31 c29">
      <span class="c1">DELETE</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.qmq1r8idyce5">
      <span class="c14 c5">Data types in SQL</span>
    </h1>
    <p class="c3">
      <span class="c1">As we have mentioned, in the relational data model it is assumed that each column of a data table contains data of a fixed type. The SQL standard defines the basic data types, but the implementations sometimes depart from the standard in details.</span>
    </p>
    <h3 class="c9" id="h.qj64z3f5245f">
      <span class="c17 c5">The SQL general data types</span>
    </h3>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_pf6gjug0y9iv-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">CHARACTER (n)</span>
        <span class="c1">&#160;– fixed length string of characters</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">CHARACTER VARYING</span>
        <span class="c1">&#160;– variable length string of characters</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">INTEGER</span>
        <span class="c1">&#160;– an integer number</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">NUMERIC</span>
        <span class="c1">&#160;- floating point number</span>
      </li>
    </ul>
    <p class="c3">
      <span class="c2">Each implementation follows the general guidelines of the SQL standard, but each of them does it in its own way. We present below the data types for MS SQL Server 2012 and ORACLE 11g. Note that the MS SQL 2012 version contains a number of significant changes (not only concerning data types) in comparison to versions 2000 and 2005. We will not discuss data types which are not contained in the standard and are unimportant for us in this lecture, like BLOB or ROWID and other data types which are not so much used on the elementary level. Students interested in this topic may look it up on the software producers webpages (</span>
      <span class="c30">
        <a class="c12" href="https://www.google.com/url?q=http://technet.microsoft.com/&amp;sa=D&amp;source=editors&amp;ust=1714064099748657&amp;usg=AOvVaw3-td0it3Sb5rINyc_K-Pdi">http://technet.microsoft.com</a>
      </span>
      <span class="c2">, </span>
      <span class="c30">
        <a class="c12" href="https://www.google.com/url?q=http://docs.oracle.com/&amp;sa=D&amp;source=editors&amp;ust=1714064099749084&amp;usg=AOvVaw12DDmA9QTBTyqtLSMwcJ8r">http://docs.oracle.com</a>
      </span>
      <span class="c1">).</span>
    </p>
    <h3 class="c9" id="h.mif902qpd4xf">
      <span class="c17">
        Names of the SQL data types
        <br/>
      </span>
      <span class="c4 c5">Character string data types</span>
    </h3>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_m6xa40k4vexm-0 start">
      <li class="c27 li-bullet-0">
        <span class="c23">CHARACTER(n)</span>
        <span class="c1">&#160;– string of fixed length n</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c23">VARYING CHARACTER(n)</span>
        <span class="c1">&#160;– string of variable length, with maximum length n</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c23">BIT(n)</span>
        <span class="c1">&#160;– string of a fixed bit length n</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c23">VARYING BIT(n)</span>
        <span class="c1">&#160;- string of variable bit length, with maximum length n</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c4 c5">Integer numeric data types</span>
    </p>
    <ul class="c8 lst-kix_67axahw2bw4y-0 start">
      <li class="c27 li-bullet-0">
        <span class="c23">INTEGER </span>
        <span class="c1">– decimal or binary integer, signed</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c23">SMALLINT </span>
        <span class="c1">- decimal or binary integer, signed</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c4 c5">Floating point numeric data types</span>
    </p>
    <ul class="c8 lst-kix_8bw4pomaqyc2-0 start">
      <li class="c27 li-bullet-0">
        <span class="c23">NUMERIC(p,q)</span>
        <span class="c1">&#160;– signed decimal number made of p digits in total, with the decimal point after q digits counting from right</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c23">DECIMAL(p,q)</span>
        <span class="c1">&#160;– signed decimal number made of p digits before and q digits after the decimal point</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c23">FLOAT(p)</span>
        <span class="c1">&#160;– floating point number (written in exponential notation)</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c4 c5">Time and data types</span>
    </p>
    <ul class="c8 lst-kix_xhpr2ex4dnkl-0 start">
      <li class="c27 li-bullet-0">
        <span class="c23 c5">DATE</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c23 c5">TIME</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c23 c5">TIMESTAMP</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c23">INTERVAL </span>
        <span class="c1">– specifies a time interval</span>
      </li>
    </ul>
    <p class="c3">
      <span class="c1">
        <br/>
        The descriptions above have been taken from the standard description. In practice we work with types implemented by each database server. They differ from the standard in details. Therefore before you start working on a database on a given server you should find out what data types it supports. At the end of this lecture we give a detailed description of data types used by ORACLE and MS SQL.
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.stpo54ej5ict">
      <span class="c14 c5">An example of the database – Emp, Dept and Salgrade tables</span>
    </h1>
    <p class="c3">
      <span class="c2">All examples of the </span>
      <span class="c16">SELECT </span>
      <span class="c2">command included in this lecture will be presented using the database consisting of the three tables: </span>
      <span class="c4">EMP</span>
      <span class="c2">, </span>
      <span class="c4">DEPT </span>
      <span class="c2">and </span>
      <span class="c4">SALGRADE</span>
      <span class="c1">, whose structure is presented in the graph below.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 494.00px; height: 350.00px;">
        <img alt="" src="images/image66.jpg" style="width: 494.00px; height: 350.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">This simple graph presents a simplified structure of a company. The </span>
      <span class="c4">EMP </span>
      <span class="c2">table stores the company’s employees data, </span>
      <span class="c4">DEPT </span>
      <span class="c2">table stores the departments’ data and </span>
      <span class="c4">SALGRADE </span>
      <span class="c1">table describes the salary structure of the company.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        The 
      </span>
      <span class="c4">EMP </span>
      <span class="c1">table</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_5m2k735u0wc3-0 start">
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Empno </span>
        <span class="c1">Int Primary Key - &#160;employee’s number</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Ename </span>
        <span class="c1">Varchar - employee’s surname</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Job </span>
        <span class="c1">Varchar - employee’s position</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Mgr </span>
        <span class="c1">Int Foreign Key - the employee supervisor’s number (a recursive relationship)</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Hiredate </span>
        <span class="c1">Date - date of employment</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Sal </span>
        <span class="c1">Int - salary (monthly)</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Comm </span>
        <span class="c1">Int - the provision (annual)</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Deptno </span>
        <span class="c1">Int Foreign Key - employee’s department number</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">&#160;</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 800.00px; height: 449.33px;">
        <img alt="" src="images/image79.jpg" style="width: 800.00px; height: 449.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        The 
      </span>
      <span class="c4">DEPT </span>
      <span class="c1">table</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_2fs6d4epazv0-0 start">
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Deptno </span>
        <span class="c1">Int Primary Key - department number</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Dname </span>
        <span class="c1">Varchar - department name</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Loc </span>
        <span class="c1">Varchar - department location (the city)</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c2">The </span>
      <span class="c4">SALGRADE </span>
      <span class="c1">table</span>
    </p>
    <ul class="c8 lst-kix_v4y75fpnt0mm-0 start">
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Grade </span>
        <span class="c1">Int Primary Key - classification number</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Losal </span>
        <span class="c1">Int - the group’s minimum salary</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c4">Hisal </span>
        <span class="c1">Int - the group’s maximum salary</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">&#160;</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 740.00px; height: 362.67px;">
        <img alt="" src="images/image73.jpg" style="width: 740.00px; height: 362.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">I would like to point out that the </span>
      <span class="c4">SALGRADE </span>
      <span class="c2">table is not connected via a primary-foreign key pair with </span>
      <span class="c4">EMP </span>
      <span class="c2">and the pair </span>
      <span class="c4">Losal</span>
      <span class="c2">-</span>
      <span class="c4">Hisal </span>
      <span class="c2">is just the salary brackets. In order to see in which group somebody’s salary (SAL) lies we need to find out into which </span>
      <span class="c4">Losal</span>
      <span class="c2">-</span>
      <span class="c4">Hisal </span>
      <span class="c1">bin the salary fits.</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c46 c18" id="h.i3f8irzcatc">
      <span class="c14 c5">SELECT instruction</span>
    </h1>
    <p class="c3 c20">
      <span class="c2">The </span>
      <span class="c16">SELECT </span>
      <span class="c1">instruction is used for reading data recorded (or not recorded…) in the database, without changing its structure or content.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">The </span>
      <span class="c16">SELECT </span>
      <span class="c1">instruction consists of a few “clauses” appearing in a strictly specified order and beginning with a keyword. The first clause, beginning with the keyword SELECT, and second clause, beginning with the key word FROM, are obligatory and therefore they must appear in the command syntax at least once (they can appear many times).</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">The </span>
      <span class="c16">SELECT </span>
      <span class="c1">instruction defines:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_cmtzg17lkw6e-0 start">
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          the sources for data reading in the database,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          the conditions the data must satisfy in order to appear in the result,
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c1">
          <br/>
          in what form the result should be returned to the user.
        </span>
      </li>
    </ul>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">Most language standards require SELECT (and every other instruction) to end with a semicolon “;”, although MS SQL treats this requirement as optional.</span>
    </p>
    <p class="c3 c20">
      <span class="c2">
        <br/>
        The 
      </span>
      <span class="c16">SELECT </span>
      <span class="c1">instruction syntax</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">SELECT </span>
      <span class="c2">[</span>
      <span class="c26">DISTINCT</span>
      <span class="c1">] wyrażenie (, ...)</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">FROM </span>
      <span class="c1">nazwa_tabeli (, ...)</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">[</span>
      <span class="c26">WHERE </span>
      <span class="c1">warunek]</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">[</span>
      <span class="c26">GROUP BY </span>
      <span class="c1">wyrażenie (, ...)]</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">[</span>
      <span class="c26">HAVING </span>
      <span class="c1">warunek]</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c1">(...)</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">[</span>
      <span class="c26">ORDER BY </span>
      <span class="c1">wyrażenie (, ...)];</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">&#160;</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">
        <br/>
        Every clause (except 
      </span>
      <span class="c16">ORDER BY</span>
      <span class="c2">) can appear in the instruction syntax more than once. </span>
      <span class="c16">SELECT </span>
      <span class="c2">and </span>
      <span class="c16">FROM </span>
      <span class="c1">clauses must appear at least once.</span>
    </p>
    <h3 class="c46 c18" id="h.rgkpd6vdwrpz">
      <span class="c17 c5">SELECT instruction SELECT clause</span>
    </h3>
    <p class="c3 c20">
      <span class="c17">
        <br/>
      </span>
      <span class="c16">SELECT </span>
      <span class="c2">
        clause structure
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c26">SELECT </span>
      <span class="c2">[</span>
      <span class="c26">DISTINCT</span>
      <span class="c2">
        ] expression (,…)
        <br/>
        <br/>
      </span>
      <span class="c26">FROM </span>
      <span class="c1">
        table_name (,…)
        <br/>
        <br/>
        (…);
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">
        <br/>
        The 
      </span>
      <span class="c16">SELECT </span>
      <span class="c2">
        clause defines the data which are going to be read from the database and the way they will be presented. It can involve the column names, expressions (also referring to the column names) and constants unrelated to the database content. The expressions should be separated by commas. The column names should be prefixed with the table name:
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4">
        Table_name. Column_name
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c2">If the column names are unambiguous then the name of the table preceding column name can be omitted. By unambiguous we mean here that the column name appears only in one table among those from which </span>
      <span class="c16">SELECT </span>
      <span class="c1">is reading the data.</span>
    </p>
    <h3 class="c46 c18" id="h.7w7gvolby2ub">
      <span class="c17 c5">SELECT instruction FROM clause</span>
    </h3>
    <p class="c3 c20">
      <span class="c2">The </span>
      <span class="c16">FROM </span>
      <span class="c2">clause defines the sources from which the data will be read. These can involve tables, views and other </span>
      <span class="c16">SELECT </span>
      <span class="c2">instructions. The names of tables, views and </span>
      <span class="c16">SELECT </span>
      <span class="c1">instructions (written in bracket) are separated by commas. In this lecture we will only discuss how to read data from a single table. Reading data from a view is not much different.</span>
    </p>
    <h3 class="c46 c18" id="h.uxlrv8ou8xuf">
      <span class="c17 c5">SELECT instruction – elementary examples</span>
    </h3>
    <p class="c3 c20">
      <span class="c17">
        <br/>
      </span>
      <span class="c2">
        We want to list the names, salaries and positions of the company employees:
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c26">SELECT </span>
      <span class="c2">
        Ename, Sal, Job
        <br/>
        <br/>
      </span>
      <span class="c26">FROM </span>
      <span class="c1">
        Emp;
        <br/>
        <br/>
        <br/>
        <br/>
        The result is shown in the table below:
      </span>
    </p>
    <p class="c6 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 322.67px; height: 350.67px;">
        <img alt="" src="images/image101.jpg" style="width: 322.67px; height: 350.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c20 c28">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">
        <br/>
        If we want to see the whole table we use:
        <br/>
        <br/>
      </span>
      <span class="c26">SELECT </span>
      <span class="c2">
        *
        <br/>
        <br/>
      </span>
      <span class="c26">FROM </span>
      <span class="c2">
        EMP;
        <br/>
        or
        <br/>
      </span>
      <span class="c26">TABLE </span>
      <span class="c1">
        EMP;
        <br/>
        <br/>
        The last instruction is contained in the SQL standard, but not implemented in either ORACLE or MS SQL Server.
      </span>
    </p>
    <h3 class="c46 c18" id="h.1g9jxr7ojesw">
      <span class="c17 c5">SELECT instruction ORDER BY clause</span>
    </h3>
    <p class="c3 c20">
      <span class="c17">
        <br/>
      </span>
      <span class="c2">The query’s results can be sorted either as </span>
      <span class="c16">ASCENDING </span>
      <span class="c2">(the default ordering, also abbreviated as </span>
      <span class="c16">ASC</span>
      <span class="c2">) or </span>
      <span class="c16">DESCENDING </span>
      <span class="c2">(</span>
      <span class="c16">DESC</span>
      <span class="c2">
        ).
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c16">SELECT </span>
      <span class="c2">[</span>
      <span class="c16">DISTINCT</span>
      <span class="c2">] phrase [[</span>
      <span class="c16">AS</span>
      <span class="c2">
        ] alias] (,…)
        <br/>
        <br/>
      </span>
      <span class="c16">FROM </span>
      <span class="c2">
        table_name
        <br/>
        <br/>
        [
      </span>
      <span class="c16">WHERE </span>
      <span class="c2">
        condition]
        <br/>
        <br/>
      </span>
      <span class="c16">ORDER BY </span>
      <span class="c2">phrase1 [</span>
      <span class="c16">ASC </span>
      <span class="c2">| </span>
      <span class="c16">DESC</span>
      <span class="c2">
        ] (,…);
        <br/>
        <br/>
        <br/>
        <br/>
        The 
      </span>
      <span class="c16">ORDER BY </span>
      <span class="c2">clause can occur </span>
      <span class="c2 c49">only once and it should always be placed at the end</span>
      <span class="c2">. The clause’s list can include expressions, also involving table names and their aliases as well as expression numbers in the order of their occurrence in the </span>
      <span class="c16">SELECT </span>
      <span class="c2">
        command.
        <br/>
        <br/>
        Sorting can be done according to more than on expression. The sorting hierarchy results from the order of the expressions on the list.
        <br/>
        <br/>
        The 
      </span>
      <span class="c16">ASC </span>
      <span class="c1">word (pointing the default sorting direction) can be omitted in command’s syntax.</span>
    </p>
    <h3 class="c46 c18" id="h.gu8ghbltjjvm">
      <span class="c17 c5">SELECT instruction WHERE clause</span>
    </h3>
    <p class="c3 c20">
      <span class="c17">
        <br/>
      </span>
      <span class="c2">
        The WHERE clause is the third clause in the SELECT syntax. It is optional - it does not have to appear. It allows to limit the records returned by the SELECT command using a logical condition. Only those records for which the condition is TRUE are returned, those with FALSE or NULL are eliminated from the result.
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4 c49">
        Example.
        <br/>
        <br/>
      </span>
      <span class="c2">
        We want to list the names, positions and salaries of all the employees from department 10.
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c26">SELECT </span>
      <span class="c2">
        Ename, Job, Sal
        <br/>
      </span>
      <span class="c26">FROM </span>
      <span class="c2">
        Emp
        <br/>
      </span>
      <span class="c26">WHERE </span>
      <span class="c1">
        deptno = 10;
        <br/>
        <br/>
        <br/>
        The command’s result is presented below:
      </span>
    </p>
    <p class="c6 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 318.67px; height: 138.67px;">
        <img alt="" src="images/image9.jpg" style="width: 318.67px; height: 138.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c20 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c46 c18" id="h.y58i7zkxad3c">
      <span class="c17 c5">SELECT instruction – reading from multiple data sources</span>
    </h3>
    <p class="c3 c20">
      <span class="c17">
        <br/>
      </span>
      <span class="c2">
        According to the SQL syntax if the data is supposed to be read from multiple tables (sources), the names of the tables, separated by commas, need to appear in the FROM clause.
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        This was a theoretical introduction. Let us now see how it works in the SQL language. We will begin with an experiment. We will read the result below in order to find out the names and locations of departments for every employee.
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c26">SELECT </span>
      <span class="c2">
        Ename, Dname, Loc
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c26">FROM </span>
      <span class="c2">
        EMP, DEPT;
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        The result is a bit surprising. There are 14 records in the 
      </span>
      <span class="c4">EMP </span>
      <span class="c2">table and 4 records in the </span>
      <span class="c4">DEPT </span>
      <span class="c2">table and the query’s result includes 56 records. Let us analyze the result in more detail. According to this result each employee’s name appears 4 times in the table and is linked with the name and the location of every department. Thus, every department is displayed together with all the names of the employees. As a result we got the Cartesian Product of on the sets of rows of </span>
      <span class="c4">EMP </span>
      <span class="c2">and </span>
      <span class="c4">DEPT</span>
      <span class="c2">
        .
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        Is this result correct? No, although it contains true information. The true records are those which line the employee’s name with the name and location of the department where he or she works. Since in our result all employees’ names are linked with all departments and locations we can be sure that the result contains the correct records as well. We just need to find them.
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        Every record in the 
      </span>
      <span class="c4">DEPT </span>
      <span class="c2">table includes the primary key in the form of the number in the </span>
      <span class="c4">Deptno </span>
      <span class="c2">column. If the employee works in a department then the record in the </span>
      <span class="c4">EMP </span>
      <span class="c2">table contains the </span>
      <span class="c4">Deptno </span>
      <span class="c2">value (foreign key) which points to the department in which he or she works. So if we want to read only the correct records we need to include the following condition ensuring that the </span>
      <span class="c4">Deptno </span>
      <span class="c2">
        value is the same in both tables:
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4 c49">
        EMP.DEPTNO = DEPT.Deptno
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c2">This way the SELECT command will omit those records for which </span>
      <span class="c4">EMP.Deptno &lt;&gt; DEPT.Deptno</span>
      <span class="c2">&#160;or </span>
      <span class="c4">EMP.Deptno is NULL</span>
      <span class="c1">.</span>
    </p>
    <h3 class="c46 c18" id="h.pwa4tt7ud57u">
      <span class="c17 c5">Control questions</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">Which clause defines the data sources (tables) which should be read by the SELECT command?</span>
    </p>
    <p class="c10">
      <span class="c1">SELECT</span>
    </p>
    <p class="c10">
      <span class="c1">FROM</span>
    </p>
    <p class="c10">
      <span class="c1">WHERE</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">ORDER BY</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">How many times can the clause ORDER BY appear in the SELECT command?</span>
    </p>
    <p class="c10">
      <span class="c1">It needs to appear exactly once.</span>
    </p>
    <p class="c10">
      <span class="c1">It can appear multiple times.</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">At most once.</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">What will be the number of records for the command SELECT * FROM T1, T2; where T1 and T2 are the tables names including respectively 5 and 3 records?</span>
    </p>
    <p class="c10">
      <span class="c1">0</span>
    </p>
    <p class="c10">
      <span class="c1">3</span>
    </p>
    <p class="c10">
      <span class="c1">5</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">15</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">What will be the result of the command below? SELECT ename FROM emp WHERE 1=1;</span>
    </p>
    <p class="c10">
      <span class="c1">Empty set.</span>
    </p>
    <p class="c20 c29 c31">
      <span class="c1">All names read from the EMP table.</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">What will be the result of the command below? SELECT dname FROM dept WHERE deptno = deptno;</span>
    </p>
    <p class="c10">
      <span class="c1">Names of all departments read from the DEPT table</span>
    </p>
    <p class="c10">
      <span class="c1">The command’s syntax is incorrect</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">The set is empty</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">If the SELECT command contains more than one table in the clause FROM:</span>
    </p>
    <p class="c10">
      <span class="c1">The command’s syntax is incorrect.</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">The user should define a way the tables should be linked</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c46 c18" id="h.4ecbalssfpc8">
      <span class="c14 c5">DDL – Data Definition Language</span>
    </h1>
    <p class="c3 c20">
      <span class="c1">DDL is a subset of the SQL language which is responsible for database object operations such as creating, deleting and changing their structure. The DDL language includes three sets of commands beginning with the key words:</span>
    </p>
    <ul class="c8 lst-kix_uqx5pvtk1sx7-0 start">
      <li class="c21 li-bullet-0">
        <span class="c16">CREATE </span>
        <span class="c1">– create new object</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c16">DROP </span>
        <span class="c1">– delete object</span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c16">ALTER </span>
        <span class="c1">– change the structure of the object</span>
      </li>
    </ul>
    <p class="c3 c20">
      <span class="c2">
        By a database object we mean tables, views, indices, procedures, triggers, databases and other objects. In this lecture we will only discuss operations on tables and integrity constraints. The concept of a view will be presented in the next lecture. The SBD course (another database-related course) will also discuss procedures.
        <br/>
        <br/>
        I would like to point out that the set of objects for which one can use the command 
      </span>
      <span class="c16">CREATE </span>
      <span class="c1">depends on the implementation.</span>
    </p>
    <h3 class="c46 c18" id="h.hkppcy3j2is5">
      <span class="c17 c5">Creating a new table</span>
    </h3>
    <p class="c3 c20">
      <span class="c2">
        Commands for creating a new table:
        <br/>
        <br/>
      </span>
      <span class="c16">CREATE TABLE</span>
      <span class="c1">
        &#160;table_name (
        <br/>
        Column_name_1 Data_type [Integrity_Constraints],
        <br/>
        Column_name_2…
        <br/>
        );
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c2">The </span>
      <span class="c4">table name</span>
      <span class="c2">&#160;cannot exceed 30 signs (</span>
      <span class="c4">ORACLE</span>
      <span class="c2">), 128 signs (</span>
      <span class="c4">MS SQL Server</span>
      <span class="c2">
        ).
        <br/>
        The 
      </span>
      <span class="c4">column number</span>
      <span class="c2">&#160;is also limited – up to 1000 (</span>
      <span class="c4">ORACLE</span>
      <span class="c2">), </span>
      <span class="c4">MS SQL Server</span>
      <span class="c1">
        &#160;assumes that the table row length does not exceed 8060 bytes.
        <br/>
        <br/>
        The names of the tables, columns and other objects can only contain Latin letters, underscores and digits. Some dialects allow also letter with diacritics or spaces, but it is recommended not to use them.
      </span>
    </p>
    <h3 class="c46 c18" id="h.7ri3crqcimy9">
      <span class="c17 c5">Creating a table – the integrity constraints</span>
    </h3>
    <p class="c3 c20">
      <span class="c2">
        One way to introduce the integrity constraints, called the declaration in a single line, has been presented below:
        <br/>
        <br/>
      </span>
      <span class="c16">CREATE TABLE</span>
      <span class="c2">
        &#160;table_name (
        <br/>
        Column_name_1 Data_type Integrity_constraints,
        <br/>
        …);
        <br/>
        <br/>
      </span>
      <span class="c4 c49">
        Example:
        <br/>
        <br/>
      </span>
      <span class="c26">CREATE TABLE</span>
      <span class="c2">
        &#160;Person (
        <br/>
        PersonId 
      </span>
      <span class="c41">INT </span>
      <span class="c26">PRIMARY KEY</span>
      <span class="c2">
        ,
        <br/>
        Name 
      </span>
      <span class="c41">VARCHAR</span>
      <span class="c2">(20) </span>
      <span class="c26">NOT NULL</span>
      <span class="c2">
        ,
        <br/>
        Surname 
      </span>
      <span class="c41">VARCHAR</span>
      <span class="c2">
        (50)
        <br/>
        );
        <br/>
        <br/>
        Constraints are declared in the same line in which their column has been declared. Note however that this is not always possible.
        <br/>
        <br/>
        Another method is to declare constraints “outside the line” using the CONSTRAINT keyword. It allows to name the constraint:
        <br/>
        <br/>
      </span>
      <span class="c4 c49">
        Example:
        <br/>
        <br/>
      </span>
      <span class="c26">CREATE TABLE</span>
      <span class="c2">
        &#160;Person(
        <br/>
        <br/>
        <br/>
        PersonId 
      </span>
      <span class="c41">INT</span>
      <span class="c2">
        ,
        <br/>
        Name 
      </span>
      <span class="c41">VARCHAR </span>
      <span class="c2">
        (20),
        <br/>
        Surname 
      </span>
      <span class="c41">VARCHAR </span>
      <span class="c2">
        (50),
        <br/>
        <br/>
        CONSTRAINT PK_Person 
      </span>
      <span class="c26">PRIMARY KEY</span>
      <span class="c2">
        &#160;(PersonId),
        <br/>
        <br/>
        CONSTRAINT UQ_Person 
      </span>
      <span class="c26">UNIQUE </span>
      <span class="c2">
        (Surname)
        <br/>
        <br/>
        );
        <br/>
        <br/>
        <br/>
        <br/>
        If the constraints are not explicitly named, the DNBS will name them automatically. The examples were presented in the 
      </span>
      <span class="c4">MS SQL Server</span>
      <span class="c2">&#160;dialect. The </span>
      <span class="c4">ORACLE </span>
      <span class="c1">syntax is basically the same, except for the data type names.</span>
    </p>
    <h3 class="c46 c18" id="h.1ffyjvlg51je">
      <span class="c17 c5">Changing the table scheme – the columns</span>
    </h3>
    <p class="c3 c20">
      <span class="c17">
        <br/>
      </span>
      <span class="c2">
        Adding a new column to an existing table, changing the column’s data type, deleting the column
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4">
        MS SQL Server and Standard
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c16">ALTER TABLE</span>
      <span class="c2">&#160;</span>
      <span class="c2 c25">Table_name</span>
      <span class="c2">&#160;</span>
      <span class="c16">ADD </span>
      <span class="c2 c25">
        column_name Data_type;
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c16">ALTER TABLE</span>
      <span class="c2">&#160;</span>
      <span class="c2 c25">Table_name</span>
      <span class="c2">&#160;</span>
      <span class="c16">ALTER COLUMN</span>
      <span class="c2">&#160;</span>
      <span class="c2 c25">
        column_name Data_type;
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c16">ALTER TABLE</span>
      <span class="c2">&#160;</span>
      <span class="c2 c25">Table_nsme</span>
      <span class="c2">&#160;</span>
      <span class="c16">DROP COLUMN</span>
      <span class="c2">&#160;</span>
      <span class="c2 c25">
        column_name;
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4">
        ORACLE
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c16">ALTER TABLE</span>
      <span class="c2">&#160;</span>
      <span class="c2 c25">Table_name</span>
      <span class="c2">&#160;</span>
      <span class="c16">ADD </span>
      <span class="c2 c25">
        (column_name Data_type);
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c16">ALTER TABLE</span>
      <span class="c2">&#160;</span>
      <span class="c2 c25">Table_name</span>
      <span class="c2">&#160;</span>
      <span class="c16">MODIFY </span>
      <span class="c2 c25">
        (column_name Data_type);
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c16">ALTER TABLE</span>
      <span class="c2">&#160;</span>
      <span class="c2 c25">Table_name</span>
      <span class="c2">&#160;</span>
      <span class="c16">DROP COLUMN</span>
      <span class="c2">&#160;</span>
      <span class="c2 c25">
        (column_name);
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c2">The brackets are optional in the </span>
      <span class="c4">ORACLE </span>
      <span class="c1">
        syntax
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <h3 class="c46 c18" id="h.wa3ntfig4q8o">
      <span class="c17 c5">Deleting the table</span>
    </h3>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c16">DROP TABLE</span>
      <span class="c2">&#160;</span>
      <span class="c2 c38 c25">table_name;</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c1">If other tables have foreign keys referring to the table we want to drop and no referential action other than ON DELETE NO ACTION has been declared then the operation will fail.</span>
    </p>
    <p class="c3 c20">
      <span class="c1">&#160;</span>
    </p>
    <h3 class="c46 c18" id="h.2sh2z7t45u29">
      <span class="c17 c5">Control Questions</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">Command ALTER is used for:</span>
    </p>
    <p class="c10">
      <span class="c1">Deleting the table from the database</span>
    </p>
    <p class="c10">
      <span class="c1">Adding a new table to the database</span>
    </p>
    <p class="c10">
      <span class="c1">Changing the data in the existing table</span>
    </p>
    <p class="c10">
      <span class="c1">Changing schema (structure) of an existing table</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">Delete the data from the existing table</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">The word CONSTRAINT for the instruction CREATE TABLE:</span>
    </p>
    <p class="c10">
      <span class="c1">Is optional</span>
    </p>
    <p class="c10">
      <span class="c1">Is used for defining the integrity constraints</span>
    </p>
    <p class="c10">
      <span class="c1">Must appear if we want to name the integrity constraints</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">Should not be used, as DBMS gives names for constraints</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">There are two tables in the database: T1 and T2. T1 includes the column t2 which is a foreign key from table T2. There are records in the T1 table which contain non-null values in t2. What will be the result of the command below? DROP TABLE T2;</span>
    </p>
    <p class="c10">
      <span class="c1">Table T2 will be deleted</span>
    </p>
    <p class="c10">
      <span class="c1">Records in T2 not referred to in T1 will be deleted.</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">The command will return an error.</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c46 c18" id="h.n09trqmxlm60">
      <span class="c14 c5">DML – Data Manipulation Language</span>
    </h1>
    <p class="c3 c20">
      <span class="c14">
        <br/>
      </span>
      <span class="c2">
        The DML is the subset of the SQL language commands responsible for the operations on the database structure. These are: adding new records to the tables, modification of the existing data and deleting the records from the tables. Three kinds of commands are used:
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c16">INSERT </span>
      <span class="c2">
        – add new record to the table
        <br/>
        <br/>
      </span>
      <span class="c16">DELETE </span>
      <span class="c2">
        – delete an existing record
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c16">UPDATE </span>
      <span class="c1">
        – change data in an existing record
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <h3 class="c46 c18" id="h.fi3l8kzcthas">
      <span class="c17 c5">Inserting data into the table</span>
    </h3>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c1">Basic (full) syntax:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c16">INSERT INTO</span>
      <span class="c1">&#160;table_name (list of column names)</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c16">VALUES </span>
      <span class="c1">(values_list);</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c1">Simplified syntax:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c16">INSERT INTO</span>
      <span class="c1">&#160;nazwa_tabeli</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c16">VALUES </span>
      <span class="c1">(values_list);</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">The number, types and order of the columns in the </span>
      <span class="c16">INSERT </span>
      <span class="c2">clause should match the list of values in the </span>
      <span class="c16">VALUES </span>
      <span class="c2">clause. The only columns which may be omitted are those which allow the </span>
      <span class="c4">NULL </span>
      <span class="c2">value, those which have a </span>
      <span class="c16">DEFAULT </span>
      <span class="c1">value defined, those whose value is calculated or realized by the auto-numbering mechanisms.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">If we use the simplified syntax then the list needs to match the order and the types of data from all table columns, just like it was defined in the </span>
      <span class="c16">CREATE TABLE</span>
      <span class="c1">&#160;command.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c48 c4">Example:</span>
    </p>
    <p class="c7">
      <span class="c48 c4"></span>
    </p>
    <p class="c7">
      <span class="c48 c4"></span>
    </p>
    <p class="c7">
      <span class="c48 c4"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">INSERT INTO</span>
      <span class="c1">&#160;Emp (empno, ename, job, sal, deptno, comm)</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">VALUES </span>
      <span class="c2">(1001, ‘</span>
      <span class="c23">WHITE</span>
      <span class="c2">’, ‘</span>
      <span class="c23">SALESMAN</span>
      <span class="c1">’, 2500, 20, NULL);</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c1">MS SQL Server allows inserting more than one record in the INSERT operation:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">INSERT INTO</span>
      <span class="c1">&#160;Emp (empno, ename, job, sal, deptno, comm)</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">VALUES </span>
      <span class="c2">(1002, ‘</span>
      <span class="c23">GREEN</span>
      <span class="c2">’, ‘</span>
      <span class="c23">CLEARK</span>
      <span class="c1">’, 3100, 10, NULL),</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">(1003, ‘</span>
      <span class="c23">YELLOW</span>
      <span class="c2">’, ‘</span>
      <span class="c23">MANAGER</span>
      <span class="c1">’, 2500, 10, 200),</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">(1002, ‘</span>
      <span class="c23">PINK</span>
      <span class="c2">’, ‘</span>
      <span class="c23">SALESMAN</span>
      <span class="c1">’, 2200, 30, NULL);</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">This solution is not implemented by the </span>
      <span class="c4">ORACLE</span>
      <span class="c2">. Values in the </span>
      <span class="c16">VALUES </span>
      <span class="c52">clause</span>
      <span class="c16">&#160;</span>
      <span class="c1">can include: the constants, the functions or the phrases.</span>
    </p>
    <p class="c13 c18">
      <span class="c2">The source for the </span>
      <span class="c16">INSERT </span>
      <span class="c2">instruction can be the </span>
      <span class="c16">SELECT </span>
      <span class="c2">instruction reading the values from the other tables. The </span>
      <span class="c16">SELECT </span>
      <span class="c1">instruction can also include the phrases.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c48 c4"></span>
    </p>
    <p class="c7">
      <span class="c48 c4"></span>
    </p>
    <p class="c13 c18">
      <span class="c48 c4">Example:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">INSERT INTO</span>
      <span class="c1">&#160;Salary_Budget (Year, Month, Sum)</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">SELECT </span>
      <span class="c1">2011, 12, Sum (sal + NVL (comm, 0))</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">FROM </span>
      <span class="c1">EMP</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">In this case we already have the </span>
      <span class="c4">Salary_Budget</span>
      <span class="c2">&#160;table, and its columns’ structure is compatible with the </span>
      <span class="c16">SELECT </span>
      <span class="c2">instruction reading records, which will be written to the </span>
      <span class="c4">Salary_Budget</span>
      <span class="c1">&#160;table.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <h3 class="c46 c18" id="h.e0twprg01d6s">
      <span class="c17 c5">Modifying the data in the existing table</span>
    </h3>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c58">UPDATE &#160; &#160;</span>
      <span class="c2 c38 c25">table_name</span>
    </p>
    <p class="c7">
      <span class="c58 c5"></span>
    </p>
    <p class="c13 c18">
      <span class="c58">SET &#160; &#160;</span>
      <span class="c2 c25">column_name = expression1</span>
      <span class="c1">, ... &#160;</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">[</span>
      <span class="c58">WHERE &#160;</span>
      <span class="c1">condition];</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c1">eg. to increase the salary of all salesmans by 10%:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">UPDATE </span>
      <span class="c1">Emp</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">SET </span>
      <span class="c1">Sal=Sal*1.1, Comm = 1000</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">WHERE </span>
      <span class="c2">Job = ‘</span>
      <span class="c23">SALESMAN</span>
      <span class="c1">’;</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">Omitting the </span>
      <span class="c16">WHERE </span>
      <span class="c1">condition will cause the modification of the data in all table records.</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <h3 class="c46 c18" id="h.d07k2oz8h6ws">
      <span class="c17 c5">Deleting data from the table</span>
    </h3>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c16">DELETE FROM </span>
      <span class="c1">table_name</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">[</span>
      <span class="c16">WHERE </span>
      <span class="c1">condition];</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c1">e.g. in order to delete all employees without the specified position:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">DELETE FROM </span>
      <span class="c1">Emp</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c26">WHERE </span>
      <span class="c1">Job is NULL</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c2">Omitting the </span>
      <span class="c16">WHERE </span>
      <span class="c1">condition will cause deleting all the records from the table.</span>
    </p>
    <p class="c3 c20">
      <span class="c1">&#160;</span>
    </p>
    <h3 class="c46 c18" id="h.swopy3507b3w">
      <span class="c17 c5">Control Questions</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">Will the following command be executed: INSERT INTO emp (ename, sal, job) VALUES (‘PINK’, 1200, ‘ROBBER’);</span>
    </p>
    <p class="c10">
      <span class="c1">No, because the company does not employ criminals.</span>
    </p>
    <p class="c10">
      <span class="c1">No, because not all columns of EMP are filled</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No, because we have not assigned any value to the empno column</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">Will the following command be executed: DELETE FROM dept;</span>
    </p>
    <p class="c10">
      <span class="c1">Yes, all records from the dept table will be deleted.</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">No, because some of the rows of DEPT are referred to by rows of EMP.</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c4 c5">The SALGRADE table contains 5 rows identified by the values 1-5 in the GRADE column. How many rows the will be changed by the command UPDATE salgrade SET Losal = Losal + 50 WHERE grade!=10 ?</span>
    </p>
    <p class="c10">
      <span class="c1">All rows.</span>
    </p>
    <p class="c10">
      <span class="c1">None.</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">One.</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.cf7lztb83pty">
      <span class="c37">Basic data types in the MS SQL Server and in the ORACLE MS SQL Server</span>
      <span class="c14">
        <br/>
      </span>
      <span class="c4 c5">Exact numeric types</span>
    </h1>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_ikb4dfai24wa-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">INTEGER </span>
        <span class="c2">or </span>
        <span class="c16">INT </span>
        <span class="c1">a sign integer type; range from-2^31 to 2^31</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">NUMERIC </span>
        <span class="c2">(p,[s]) or </span>
        <span class="c16">DECIMAL </span>
        <span class="c1">(p,[s]) a floating point number, where p defines signs’ number, s the number of signs after the comma; range from -2^31 to 2^31</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">MONEY </span>
        <span class="c1">a floating point number type representing the currency values; range from -922 337 203 685 477.5808 to 922 337 203 685 477.5807</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c4 c5">Approximate numeric types</span>
    </p>
    <ul class="c8 lst-kix_olrmfo3e8daa-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">FLOAT</span>
        <span class="c1">(n) approximate floating point number, range from -1.79E+308 to -2.23E-308, 0 and from 2.23E-3+8 to 1.79E+308,</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">REAL </span>
        <span class="c1">approximate floating point number, range from -3.40E+38 to -1.18E-38, 0, 1.18E-38 to 3.40E+38.</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c4 c5">Date and time types</span>
    </p>
    <ul class="c8 lst-kix_oqq2ui921j1-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">TIME</span>
        <span class="c1">, format: hh:mm:ss[.nnnn], range 0.00 – 23.59.59.9999</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">DATE</span>
        <span class="c1">, format: YYYY-MM-DD; range: 0001-01-01 to 9999-12-31</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">DATETIME</span>
        <span class="c1">, fornat: YYYY-MM-DD hh:mm:ss; range: 1753-01-01 - 9999-12-31</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c4 c5">Character strings:</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_boxwjc60mpgf-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">CHAR</span>
        <span class="c1">(n): string of constant length, up to n characters; format: 1-8000 ASCII characters</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">VARCHAR</span>
        <span class="c1">(n): string of variable length, up to n characters; format: 1-8000 ASCII characters</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">nCHAR</span>
        <span class="c1">(n): string of constant length, up to n characters; format: 1-4000 UNICODE characters</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">nVARCHAR</span>
        <span class="c1">(n): string of variable length, up to n characters; format: 1-4000 UNICODE characters</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">VARCHAR</span>
        <span class="c1">(max): string of variable length; format: ASCII characters up to 2GB.</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c4 c5">ORACLE</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c4 c5">Exact numerical types</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_m3s6obof6xsw-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">NUMBER</span>
        <span class="c1">(p,s): integer or floating point number, where p – maximal total number of digits (up to 38), s – number of digits after the decimal point</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">INTEGER </span>
        <span class="c2">or </span>
        <span class="c16">INT</span>
        <span class="c1">: integer, same as NUMBER(38)</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c4 c5">Date and time types</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_ihu4chqckap9-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">DATE</span>
        <span class="c1">: stores the year, month, day, minutes and seconds</span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c4 c5">Strings</span>
    </p>
    <ul class="c8 lst-kix_ouu0f4ii1rn1-0 start">
      <li class="c27 li-bullet-0">
        <span class="c16">CHAR</span>
        <span class="c1">(n): string of constant length, up to n characters; format: 1-2000 ASCII characters</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">VARCHAR2</span>
        <span class="c1">(n): string of variable length, up to n characters; format: 1-4000 ASCII characters</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">nCHAR</span>
        <span class="c1">(n): string of constant length, up to n characters; format: 1-2000 UNICODE characters</span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c16">nVARCHAR2</span>
        <span class="c1">(n): string of variable length, up to n characters; format 1-4000 UNICODE characters</span>
      </li>
    </ul>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.pg06f5khtqqf">
      <span class="c14 c5">Summary</span>
    </h1>
    <p class="c3">
      <span class="c1">In this lecture, the last one dedicated to the relational databases, we have discussed the origins of the SQL language and its structure. We have given only an overview of SQL, enough to present what the language can be used for and what its basic instructions are. We have omitted a number of details, so the content of this lecture should be considered an introduction to the topic of SQL, which in turn will be discussed in greater detail in the two next semesters during the RBD and SBD courses.</span>
    </p>
    <h1 class="c44" id="h.k2wnu6fll5vh">
      <span class="c49 c55">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62112/chapter/25920&amp;sa=D&amp;source=editors&amp;ust=1714064099790569&amp;usg=AOvVaw0Ucv6_XbWLfxOobO1zIUG6">5 </a>
      </span>
      <span class="c29 c47">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62112/chapter/25920&amp;sa=D&amp;source=editors&amp;ust=1714064099790957&amp;usg=AOvVaw3YtUTMPJF3m4cgsjEsmjoU">Lesson XI - Structure of a worksheet (spreadsheet), formatting and data entry in Excel</a>
      </span>
    </h1>
    <p class="c13">
      <span class="c34 c29">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62112/chapter/25920&amp;sa=D&amp;source=editors&amp;ust=1714064099791408&amp;usg=AOvVaw2mULnL_-4ncgsCnjVyEnYp">15.03.2024 11:46 | Number of chapters: 6</a>
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.tzipjnpzgao8">
      <span class="c14">
        Introduction
        <br/>
      </span>
      <span class="c1">In this lesson you will learn about the structure of an Excel worksheet and the basics of formatting and data entry. The application is widely used in companies and institutions, as well as by home users. It is mainly used to make calculations (e.g. expenditures) listed in a tabular form. In this use there are applied many logical functions (Lesson 3) mathematical, financial and database functions that are available in the program. Of a great importance is also semi-automatic copying of the created formulas using different variants of addressing (relative addressing, absolute addressing, mixed addressing). Excel is also used to create many types of charts (which we will learn about in lesson 2)which are useful e.g. in physics, mathematics and economics. It also contains a system of reports compilation in which the so-called pivot tables are used, used in the performance of business intelligence (Lesson 4).</span>
    </h1>
    <h3 class="c9" id="h.m7q4882xttai">
      <span class="c17">
        Learning outcome
        <br/>
      </span>
      <span class="c1">On having mastered the material of this lesson, the student should be able to easily enter and format data in Excel worksheets, make calculations (using operators and functions) and use semi-automatic duplication of the created formulas using different variants of addressing (relative addressing, absolute addressing, mixed addressing).</span>
    </h3>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.ebxg9sm7rju4">
      <span class="c14 c5">Structure of an Excel worksheet (spreadsheet) and entering and selecting data</span>
    </h1>
    <h3 class="c9" id="h.qmp61fsqmsw">
      <span class="c17 c5">Structure of a worksheet</span>
    </h3>
    <p class="c3">
      <span class="c17">
        <br/>
      </span>
      <span class="c2">Each document in Excel consists of </span>
      <span class="c4">worksheets</span>
      <span class="c1">.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        An Excel worksheet (spreadsheet), is a two-dimensional grid with 
      </span>
      <span class="c4">columns </span>
      <span class="c2">and </span>
      <span class="c4">rows</span>
      <span class="c1">. The column names are letters of the alphabet (A, B, C, …)and the rows are numbered chronologically (1,2,3 and so on).</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        The worksheet consists of cells i.e. small boxes, into which we can enter data. Each cell has its own address. We create it giving the name of the column and of the row in which the cell is located.
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        In the picture below cell A1 is selected.
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 640.00px; height: 165.00px;">
        <img alt="" src="images/image107.png" style="width: 640.00px; height: 165.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        The address of a cell is always displayed on the left of the Formula Bar
      </span>
    </p>
    <h3 class="c9" id="h.g4h5rlyhjb76">
      <span class="c17 c5">Data entry</span>
    </h3>
    <p class="c3">
      <span class="c17">
        <br/>
      </span>
      <span class="c1">In Excel, we enter data directly into the cells. We click in the selected cell and begin typing. Entered digits will automatically move to the right side of the cell, and the text to the left. If we want to enter a decimal, we separate the integer from tens by a comma (never a dot!). This applies when we use the operating system with the Polish regional settings.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 405.00px; height: 175.00px;">
        <img alt="" src="images/image62.png" style="width: 405.00px; height: 175.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.cbmolt72vtkk">
      <span class="c17 c5">Selecting cells</span>
    </h3>
    <p class="c3">
      <span class="c17">
        <br/>
      </span>
      <span class="c1">
        Before copying or formatting cells we have to select them.
        <br/>
        The cells can be selected as follows:
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_8frcs3cb9mlx-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          to select one cell click in it
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          To select one or more columns of cells, click on the column letter(s).
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          To select one or more rows of cells, click on the row number(s)
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          To select a group of contiguous cells, click in a corner cell and, with the left mouse button depressed, drag the cursor horizontally and/or vertically until all of the cells you want selected are outlined in black.
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          To select multiple cells that are not contiguous, press and hold the Ctrl key while clicking in the desired cells.
        </span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">&#160;</span>
    </p>
    <h3 class="c9" id="h.x4gzr0iuwdpl">
      <span class="c17 c5">CHECKING THE KNOWLEDGE:</span>
    </h3>
    <p class="c13 c29">
      <span class="c4 c5">In the picture below a cell is selected:</span>
    </p>
    <p class="c35 c29">
      <span class="c1">B2</span>
    </p>
    <p class="c31 c29">
      <span class="c1">2B</span>
    </p>
    <p class="c13 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 279.00px; height: 138.00px;">
        <img alt="" src="images/image31.png" style="width: 279.00px; height: 138.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c13 c28">
      <span class="c42 c5"></span>
    </p>
    <h1 class="c36 c22" id="h.xsytzear0pep">
      <span class="c14 c5">Formatting cells</span>
    </h1>
    <p class="c3">
      <span class="c1">In this lesson we will discuss the issue of cell formatting.</span>
    </p>
    <h3 class="c9" id="h.uelg7i4y2365">
      <span class="c17 c5">Basic formatting.</span>
    </h3>
    <p class="c3">
      <span class="c17">
        <br/>
      </span>
      <span class="c1">There are two ways of formatting the contents of the cells. The first is to select the cells and in the formatting window choose the "Main Tools" tab, then we can change the visual and aesthetic part of the worksheet by selecting the appropriate formatting category tab from the existing formatting group ("Font", "Alignment", "Number" etc.)</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 1134.00px; height: 110.00px;">
        <img alt="" src="images/image97.jpg" style="width: 1134.00px; height: 110.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        The second way is to right-click in the selected cells and select Format Cells window. There are different formatting options available on different tab groups.
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        The first tab is Number and contains categories for the type of data that is in the cell. Select one of these to set the appropriate cell format.
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 536.00px; height: 465.00px;">
        <img alt="" src="images/image21.jpg" style="width: 536.00px; height: 465.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        Applying different number formats, you can change the way of displaying numbers without changing them. The format of a number does not affect the actual value of the cell used in Excel to make calculations.
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        This value is displayed in the 
      </span>
      <span class="c23">formula bar</span>
      <span class="c1">.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 233.00px; height: 160.00px;">
        <img alt="" src="images/image17.png" style="width: 233.00px; height: 160.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        The following list contains information about available formats of numbers in the Number tab.
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 861.00px; height: 421.00px;">
        <img alt="" src="images/image10.png" style="width: 861.00px; height: 421.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 857.00px; height: 343.00px;">
        <img alt="" src="images/image51.png" style="width: 857.00px; height: 343.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 861.00px; height: 346.00px;">
        <img alt="" src="images/image36.png" style="width: 861.00px; height: 346.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 860.00px; height: 327.00px;">
        <img alt="" src="images/image54.png" style="width: 860.00px; height: 327.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 855.00px; height: 317.00px;">
        <img alt="" src="images/image78.png" style="width: 855.00px; height: 317.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 853.00px; height: 318.00px;">
        <img alt="" src="images/image57.png" style="width: 853.00px; height: 318.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 855.00px; height: 324.00px;">
        <img alt="" src="images/image12.png" style="width: 855.00px; height: 324.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 856.00px; height: 365.00px;">
        <img alt="" src="images/image13.png" style="width: 856.00px; height: 365.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 853.00px; height: 360.00px;">
        <img alt="" src="images/image108.png" style="width: 853.00px; height: 360.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 852.00px; height: 358.00px;">
        <img alt="" src="images/image27.png" style="width: 852.00px; height: 358.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        On the Alignment tab we set Orientation and Text Alignment
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 542.00px; height: 466.00px;">
        <img alt="" src="images/image25.jpg" style="width: 542.00px; height: 466.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        On the Font tab we set: Font name, Font style, Size, Color and whether you want the text to be underlined.
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 539.00px; height: 467.00px;">
        <img alt="" src="images/image45.jpg" style="width: 539.00px; height: 467.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        The fourth tab is Border. The Border tab provides a variety of border styles, To apply borders select the cells and then right-click and select Format Cells → Border. Select the border style and color first; then select the side or sides of the cell to receive the border.
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 542.00px; height: 469.00px;">
        <img alt="" src="images/image44.jpg" style="width: 542.00px; height: 469.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        To change the background color of a single cell or range of cells, select Format Cells → Fill or Patterns depending on the version of Excel.
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 538.00px; height: 468.00px;">
        <img alt="" src="images/image1.jpg" style="width: 538.00px; height: 468.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.v5726d2og5k9">
      <span class="c17 c5">CHECKING THE KNOWLEDGE:</span>
    </h3>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 350.00px; height: 194.00px;">
        <img alt="" src="images/image104.png" style="width: 350.00px; height: 194.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c13 c29">
      <span class="c4 c5">1. What types of formatting were used in the above picture:</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Numbers -&gt; Percentage, Font -&gt; Arial</span>
    </p>
    <p class="c35 c29">
      <span class="c1">Numbers -&gt; Currency, Border -&gt; outline, Fill</span>
    </p>
    <p class="c31 c29">
      <span class="c1">Numbers -&gt; Fraction, Border -&gt; outline, Fill</span>
    </p>
    <p class="c13 c29">
      <span class="c5 c15">Check the answer</span>
    </p>
    <h3 class="c9" id="h.xu697wicwnaw">
      <span class="c17 c5">Conditional Formatting</span>
    </h3>
    <p class="c3">
      <span class="c17">
        <br/>
      </span>
      <span class="c1">Conditional formatting allows you to automatically format cells, when they fulfill a certain condition. We can e.g. change the font color depending on what grade point average the student has obtained and thus select students with an average of more than 4.75.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        To apply conditional formatting should be:
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_h94ugxasirk3-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          select the cells you want to format
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          select Format → Conditional Formatting
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          determine what condition are to be fulfilled
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          set the appropriate formatting
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          if there are more conditions, click the Add button
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          If all conditions have been added, click the Format button
        </span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">&#160;</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 520.00px; height: 412.00px;">
        <img alt="" src="images/image76.jpg" style="width: 520.00px; height: 412.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.19fy6xt9tg">
      <span class="c17 c5">Example</span>
    </h3>
    <p class="c3">
      <span class="c17">
        <br/>
      </span>
      <span class="c1">There is often a need to highlight in the table some maximum or minimum values. This can be done by sorting the table, however, Microsoft Excel 2013 allows you to award the largest or smallest value without sorting.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">At XYZ company an employee has to highlight the top 10 sales results.</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        First, you select the cells whose fragments you want to highlight. Then you choose 
      </span>
      <span class="c4">Conditional Formatting </span>
      <span class="c2">in the </span>
      <span class="c4">Main Tools</span>
      <span class="c2">. In the menu that appears, you choose the option </span>
      <span class="c4">Top/Bottom Rules</span>
      <span class="c1">.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 1573.00px; height: 686.00px;">
        <img alt="" src="images/image81.jpg" style="width: 1573.00px; height: 686.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        Click the 
      </span>
      <span class="c4">Top 10 elements </span>
      <span class="c1">... and in the window that appears, choose a value of 10 and the kind of distinctions.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 540.00px; height: 313.00px;">
        <img alt="" src="images/image86.jpg" style="width: 540.00px; height: 313.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        At the same spreadsheet denote the color blue 30% of the smallest value. You choose the option 
      </span>
      <span class="c4">Bottom </span>
      <span class="c2">10% ... in the menu </span>
      <span class="c4">Top/Bottom Rules</span>
      <span class="c2">. In the window, enter the value 30, and select the desired way of formatting. Since we do not have to choose blue color fill, select </span>
      <span class="c4">Custom Format</span>
      <span class="c1">&#160;...</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.00px; height: 311.00px;">
        <img alt="" src="images/image37.jpg" style="width: 601.00px; height: 311.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 577.33px; height: 537.33px;">
        <img alt="" src="images/image7.png" style="width: 577.33px; height: 537.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        In the 
      </span>
      <span class="c4">Font </span>
      <span class="c2">tab, </span>
      <span class="c4">Color </span>
      <span class="c2">option select a bright, visible on a dark blue background color. Then go to the </span>
      <span class="c4">Fill </span>
      <span class="c1">tab, where you choose the right color for the background.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 529.00px; height: 498.00px;">
        <img alt="" src="images/image14.jpg" style="width: 529.00px; height: 498.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        After approval of the changes by pressing 
      </span>
      <span class="c4">OK </span>
      <span class="c1">you get a fully formatted spreadsheet.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 427.00px; height: 382.00px;">
        <img alt="" src="images/image24.jpg" style="width: 427.00px; height: 382.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <h1 class="c36 c22" id="h.av2x61ytzbqt">
      <span class="c14 c5">Calculations, operators and functions</span>
    </h1>
    <h3 class="c9" id="h.la00ef5m4xm2">
      <span class="c17 c5">Performing calculations</span>
    </h3>
    <p class="c3">
      <span class="c17">
        <br/>
      </span>
      <span class="c1">Calculations performed using Excel formulas. To enter a formula proceed as follows:</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <ul class="c8 lst-kix_eyq40i4uxhci-0 start">
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          click on the cell in which the formula is to be entered
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          enter the formula (action) starting from the "="
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          type the formula using cell references
        </span>
      </li>
      <li class="c27 li-bullet-0">
        <span class="c1">
          <br/>
          approve the formula of the Enter key
        </span>
      </li>
    </ul>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">&#160;</span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        When you perform all calculations in Excel it is recommended to use cell references. This makes it easier and faster to make adjustments, and speeds up the job when we have a few similar calculations.
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">
        <br/>
        The formula appears in the 
      </span>
      <span class="c16">formula bar</span>
      <span class="c2">, and the result in an</span>
      <span class="c57">&#160;</span>
      <span class="c26">active cell</span>
      <span class="c1">.</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 553.00px; height: 306.00px;">
        <img alt="" src="images/image83.png" style="width: 553.00px; height: 306.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        If you want to make amendments to the previously entered formula, click the cell in which the formula appears and make changes in the formula bar.
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        The formula can be copied between the cells in the example below to get, in rows two and three, the product from columns A and B enough to "catch" the element and stretch it down. More advanced rules to copy formulas will be presented in point 5.
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 598.67px; height: 130.67px;">
        <img alt="" src="images/image48.png" style="width: 598.67px; height: 130.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        The cells can enter a formula using mathematical signs and pointing to the cells to be used in these calculations.
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        It is important to introduce the formulas which begin with the =
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        A collection of the most important operators and functions Excel spreadsheet:
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <a id="t.21156f836e4663dd885632def287abc930489fc6"></a>
    <a id="t.0"></a>
    <table class="c54">
      <tbody><tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c4">Operator</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c4">Explanation</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">+</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Adding</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">-</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Subtraction</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">*</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Multiplication</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">/</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Divide</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">=</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Equal</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">&lt;=</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Less than or equal</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">&gt;=</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Greater than or equal</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">&lt;&gt;</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Different</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">^</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Exponentiation</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">SQRT(x)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Returns the value of a positive square root</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">POWER(number;power)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Raises the number to the power</span>
          </p>
        </td>
      </tr>
      <tr class="c45">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">SUM()</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Returns the sum the from the cells or range in brackets. Example SUM(A1:A10) or SUM(A2;D3;G5)</span>
          </p>
        </td>
      </tr>
      <tr class="c45">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">PRODUCT()</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Returns the product the from the cells or range in brackets. Example PRODUCT(A1:A10) or PRODUCT(A2;D3;G5)</span>
          </p>
        </td>
      </tr>
      <tr class="c53">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">SUMSQ ()</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Displays the sum of the squares of the cells or range in brackets</span>
          </p>
        </td>
      </tr>
      <tr class="c45">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">EXP(x)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Returns e raised to the power of number. The constant e equals 2.71828182845904, the base of the natural logarithm.</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">LN(x)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">The natural logarithm of x. x &gt; 0</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Log10(x)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Displays the logarithm</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Log(number, base)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Returns the logarithm of the specific basis</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">PI()</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Returns the value of π</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">RADIANS(angle)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Converts degrees to radians</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">DEGREES(kąt)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Converts radians to degrees</span>
          </p>
        </td>
      </tr>
      <tr class="c53">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Sin(), Cos(), Tan()</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Sine, Cosine, Tangent (function arguments must be given in radians)</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Ctg = 1/TAN()</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Cotangent</span>
          </p>
        </td>
      </tr>
      <tr class="c43">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">FACT (n)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">n!, n &gt; 0</span>
          </p>
        </td>
      </tr>
      <tr class="c53">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">COMBIN(n;k)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Displays the number of combinations of k - of element of a set of n - element</span>
          </p>
        </td>
      </tr>
      <tr class="c53">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">COUNTIF(range, criteria)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Counts the number of cells within the range that meet the given criteria</span>
          </p>
        </td>
      </tr>
      <tr class="c45">
        <td class="c24" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">SUMIFS(sum_range, criteria_range1, criteria1, [criteria_range2, criteria2], ...)</span>
          </p>
        </td>
        <td class="c32" colspan="1" rowspan="1">
          <p class="c13">
            <span class="c1">Adds all of its arguments that meet multiple criteria</span>
          </p>
        </td>
      </tr>
    </tbody>
</table>
    <h3 class="c9" id="h.b0up70wynski">
      <span class="c17 c5">Examples</span>
    </h3>
    <p class="c3">
      <span class="c17">
        <br/>
      </span>
      <span class="c1">We already know the basic operators and functions of Excel. Now let us discuss a few practical examples:</span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 293.00px; height: 96.00px;">
        <img alt="" src="images/image50.png" style="width: 293.00px; height: 96.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        <br/>
        In Excel to calculate the root of grade 4 of 7 belong to convert it first to another character, because Excel does not provide a feature that allows you to calculate the root level 4 (during practical tasks often is the case, why should then remember the lessons of mathematics in school and properly transform equation).
      </span>
    </p>
    <p class="c3">
      <span class="c2">
        2. Calculate the cos of 27 degrees.
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        As we know the arguments of trigonometric functions in Excel, should be given in radians. In that case, solution to the problem should look like this:
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        a)Transform 27 degrees to radians,
        <br/>
        <br/>
        <br/>
        b)Put the result of the trigonometric function.
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4">Solution</span>
      <span class="c2">
        : Cos (radians(27))
        <br/>
        <br/>
        <br/>
        <br/>
        3. In how many ways can a 16 person group set in a series of pairs?
        <br/>
        <br/>
        To calculate the result of this task should use the so-called permutations of a set: 16!
        <br/>
        <br/>
      </span>
      <span class="c4">Solution</span>
      <span class="c1">
        : FACT(16)
        <br/>
        <br/>
        <br/>
        <br/>
        4. In how many ways can you select a 6 person volleyball team from a 16 people group? It is indeed one of the most difficult tasks, therefore let's we apply the so called Newton's symbol:
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 657.00px; height: 84.00px;">
        <img alt="" src="images/image80.png" style="width: 657.00px; height: 84.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c1">5. How to calculate:</span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 137.00px; height: 62.00px;">
        <img alt="" src="images/image88.png" style="width: 137.00px; height: 62.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c4">Solution</span>
      <span class="c2">
        : sqrt(sin(radians (25))+ 2)/(cos(radians(45)+2)
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        6. XYZ company employee was asked to count the total sales of the three products.
        <br/>
        <br/>
        <br/>
        <br/>
        You enter data to Excel Sheet by selecting the cell and typing data directly
      </span>
      <span class="c26">&#160;in the cell</span>
      <span class="c2">&#160;or in the</span>
      <span class="c26">&#160;formula bar</span>
      <span class="c1">&#160;(indicated by arrows in the figure below).</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 408.00px; height: 262.67px;">
        <img alt="" src="images/image60.png" style="width: 408.00px; height: 262.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c2">&#160;After setting the active cell D8 let's enter in the cell the formula summing sales of these three products. This can be done in many ways, for example by typing in D8 to the formula = SUM (</span>
      <span class="c26">D5: D7</span>
      <span class="c2">), or by entering = SUM (</span>
      <span class="c26">and selecting the interesting range of the mouse</span>
      <span class="c1">
        ), but the best standing on the field select the icon of the sum, which is on the card &#160;'Formulas'. The values you are searching for will be automatically summarized. The spreadsheet should look like as it is shown below.
        <br/>
        <br/>
        <br/>
        <br/>
        In this way we can also introduce other functions - financial, logical and others.
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 608.00px; height: 494.67px;">
        <img alt="" src="images/image91.png" style="width: 608.00px; height: 494.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.iyvn6iptmzf8">
      <span class="c17 c5">Checking knowledge:</span>
    </h3>
    <p class="c13 c29">
      <span class="c4 c5">1. In how many different ways can you select 3 people to go to the cinema out of a 7 person group? What formula will you type in Excel?</span>
    </p>
    <p class="c35 c29">
      <span class="c1">COMBIN(7;3)</span>
    </p>
    <p class="c35 c29">
      <span class="c1">COMBIN(7,3)</span>
    </p>
    <p class="c31 c29">
      <span class="c1">COMBIN(3;7)</span>
    </p>
    <p class="c13 c28">
      <span class="c42 c5"></span>
    </p>
    <h1 class="c36 c22" id="h.tzklfheauih2">
      <span class="c14 c5">The relative and absolute addresses</span>
    </h1>
    <p class="c3">
      <span class="c2">As it has been mentioned earlier </span>
      <span class="c4">cell ADDRESS</span>
      <span class="c2">&#160;is a pair that specifies clearly a cell in the spreadsheet. It arises from the number of column and row sheet. The </span>
      <span class="c4">columns </span>
      <span class="c2">are numbered with successive letters A, B, C, and the </span>
      <span class="c4">rows </span>
      <span class="c2">
        - consecutive numbers 1,2,3; eg. a cell in the upper left corner of the sheet has the address A1.
        <br/>
        <br/>
        <br/>
        <br/>
        Addresses of the cells act as variables in formulas (formulas called) entered into the worksheet cells. As a result, the change in value in 1-wszej cell can be automatically reflected in the other cells.
        <br/>
        <br/>
        <br/>
        <br/>
        you can distinguish three types of addresses spreadsheet cells, typed into formulas - 
      </span>
      <span class="c16 c49">
        their type is indicated by the $ sign:
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4">Absolute </span>
      <span class="c2">- in this addressing the specific cell address is important, not its position relative to other data. Add the cell address $ signs in front of the letter of the column and before the letter indicating the row eg.</span>
      <span class="c16">&#160;$A$1</span>
      <span class="c2">
        . As a result, the cell address will not change. Such addressing is used, for example when the value of a cell refers to a number of data:
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c5 c62">
        Example 1:
        <br/>
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3">
      <span class="c2">
        An employee at XYZ has the task to calculate the price of goods in PLN in terms of Euro.
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4">
        Solution:
        <br/>
        <br/>
      </span>
      <span class="c2">You will get this value by multiplying the price of the goods in Euro (B4:B12) by Euro exchange rate (in cell B1). To all the values in column B multiplied by this one particular cell must address it as an absolute address: formula takes the form: =</span>
      <span class="c26">B4</span>
      <span class="c2">*</span>
      <span class="c16">$B$1</span>
      <span class="c1">
        . You can copy such a form without any changes.
        <br/>
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 306.67px; height: 405.33px;">
        <img alt="" src="images/image40.jpg" style="width: 306.67px; height: 405.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c4">Relative </span>
      <span class="c2">- Addressing is used by the program as default. Addressing utilizes the relative position of the cells relative to each other and not their specific addresses. It is taken into account the position of the cell in which it is entered formula containing the address. Sheet remembers the location of the cells whose addresses appear in the formula, relative to the cell containing the formula. </span>
      <span class="c23">$ Character does not occur</span>
      <span class="c2">
        .
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4">
        Example 2:
        <br/>
        <br/>
      </span>
      <span class="c2">
        In columns A and B are the data series, in column D we obtain the products of the two pairs of the series.
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4">
        Solution:
        <br/>
        <br/>
      </span>
      <span class="c2">To do this, in the cell D1, enter =</span>
      <span class="c26">A1</span>
      <span class="c2">*</span>
      <span class="c16">B1</span>
      <span class="c1">
        , this formula can be copied to other cells in column D. This is possible thanks to this the program at that addressing only checks the relative position of the cell with the formula to each other, so the formula is copied down to the next cell will use a modified version of the formula as =A2*B2 and so on.
        <br/>
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 350.00px; height: 475.00px;">
        <img alt="" src="images/image103.jpg" style="width: 350.00px; height: 475.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <p class="c3">
      <span class="c4">Mixed </span>
      <span class="c2">- Address mixed cell is a combination of an absolute and relative address. It is used when the values have to refer to a particular column or row. If we mean to indicate a specific example of the column address will be the character </span>
      <span class="c16">$A1</span>
      <span class="c2">, and in the case of a particular row becomes A$1. This distinction is important in the transfer (copying) formulas between cells. This part of the address, which is not subject to change should be preceded by a $; eg. the absolute address cell A1 has the form </span>
      <span class="c16">$A$1</span>
      <span class="c2">
        , and copying formulas with the address he remains always the same. In the mixed address only one part is preceded by a $ and does not change when you copy a formula.
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4">
        Example 3
        <br/>
        <br/>
      </span>
      <span class="c2">
        In column A the data to be multiplied by the value of the other two columns.
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c4">
        Solution:
        <br/>
        <br/>
      </span>
      <span class="c2">To make such an operation should be time to enter a formula into cell D1 =</span>
      <span class="c26">$A1</span>
      <span class="c2">*</span>
      <span class="c16">B1 </span>
      <span class="c1">
        and then copy it without modification to the other cells down or right, use addressing mixed in the form of: $=A1*B1
        <br/>
      </span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 349.00px; height: 429.00px;">
        <img alt="" src="images/image59.jpg" style="width: 349.00px; height: 429.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c6 c28">
      <span class="c1"></span>
    </p>
    <h3 class="c9" id="h.3m1r065t6x2s">
      <span class="c17 c5">CHECKING THE KNOWLEDGE:</span>
    </h3>
    <p class="c13 c29">
      <span class="c4 c5">Which of the following formulas satisfies receiving the following multiplication table in two movements, copying the formula - the formula enter into the B2 and then copy to the right and the whole row down.</span>
    </p>
    <p class="c35 c29">
      <span class="c1">A * B $ 2 $ 1</span>
    </p>
    <p class="c35 c29">
      <span class="c1">$ A2 * B $ 1</span>
    </p>
    <p class="c35 c29">
      <span class="c1">A * B $ 2 $ 1</span>
    </p>
    <p class="c35 c29">
      <span class="c1">$ * $ A2 B1</span>
    </p>
    <p class="c35 c29">
      <span class="c1">$ A $ 2 * B $ 1</span>
    </p>
    <p class="c31 c29">
      <span class="c1">$ A2 * $ B $ 1</span>
    </p>
    <p class="c13 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c6">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 736.00px; height: 248.00px;">
        <img alt="" src="images/image96.png" style="width: 736.00px; height: 248.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c13 c28">
      <span class="c42 c5"></span>
    </p>
    <h1 class="c36 c22" id="h.r45r0ownckfx">
      <span class="c14 c5">Summary</span>
    </h1>
    <p class="c3">
      <span class="c1">In the above lesson we presented the basis for the introduction and formatting data in Excel spreadsheets, making calculations (using operators and functions) and the use of semi-automatic copying using different kinds of addressing (relative addressing, absolute addressing, mixed addressing). It should serve as a good kickstart in learning Excel spreadsheet.</span>
    </p>
    <p class="c13 c28">
      <span class="c5 c42"></span>
    </p>
    <p class="c13 c28">
      <span class="c15 c5">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62112/chapter/25920&amp;sa=D&amp;source=editors&amp;ust=1714064099831425&amp;usg=AOvVaw2xEoAxZXPyqlMcJNxIp_ki"></a>
      </span>
    </p>
    <h1 class="c44" id="h.w451kcsggo59">
      <span class="c49 c55">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62113/chapter/25926&amp;sa=D&amp;source=editors&amp;ust=1714064099831931&amp;usg=AOvVaw3zRvWr1OB990xl6Iz4z8vx">6 </a>
      </span>
      <span class="c48 c50">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62113/chapter/25926&amp;sa=D&amp;source=editors&amp;ust=1714064099832313&amp;usg=AOvVaw35bOX1v7tpzNyRxyWiCE1l">Lesson XII - Charts in Excel - Basics</a>
      </span>
    </h1>
    <p class="c13">
      <span class="c34">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62113/chapter/25926&amp;sa=D&amp;source=editors&amp;ust=1714064099832747&amp;usg=AOvVaw28NsW7F4dRIk5E0pu1vLCr">15.03.2024 11:46 | Number of chapters: 5</a>
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h1 class="c36 c22" id="h.pap523bcuqsl">
      <span class="c14 c5">INTRODUCTION</span>
    </h1>
    <p class="c3">
      <span class="c1">Often we need to illustrate our calculations with a chart- particularly when it is about different kinds of analyses and computer simulations. One chart is better than a thousand numbers. This lesson will provide step- by –step directions how to create basic charts in Excel.</span>
    </p>
    <h3 class="c9" id="h.iqbdqjwk6f3l">
      <span class="c17 c5">Learning effects</span>
    </h3>
    <p class="c3">
      <span class="c1">Once the material of this lesson has been mastered, the student should be able to create basic Scatter or Pie Charts in Excel based on entered or acquired data.</span>
    </p>
    <h1 class="c46 c18" id="h.hy4w1rd1q79h">
      <span class="c14 c5">SCATTER CHART</span>
    </h1>
    <p class="c3 c20">
      <span class="c1 c39">[FILM]</span>
    </p>
    <p class="c13 c18">
      <span class="c48 c2">We need to create a table with data</span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        In today's class we will work on a task for mathematical analysis class. The result of our work will be a common, standardized chart of five math functions.
        <br/>
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c2">
        We have a given function formula:
        <br/>
        <br/>
        y = 2x
      </span>
      <span class="c61">2</span>
      <span class="c1">
        &#160;- 3x - 2
        <br/>
        <br/>
        x € &lt;- 20 20&gt;
        <br/>
        <br/>
        <br/>
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        1. The first step is to create a table with data which Excel will use to create a chart.
        <br/>
        <br/>
        2. Fill in the table with a series of number values for x-s - dragging like while copying formulas:
        <br/>
        <br/>
        <br/>
      </span>
    </p>
    <p class="c13 c18">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 125.33px; height: 300.00px;">
        <img alt="" src="images/image72.png" style="width: 125.33px; height: 300.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">up to 20. . .</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c1">3. Fill in the values for y 1:</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 300.00px; height: 146.67px;">
        <img alt="" src="images/image41.png" style="width: 300.00px; height: 146.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">Then we drag the formula to the bottom, so that Excel calculates y for all x-s.</span>
    </p>
    <p class="c13 c18">
      <span class="c48 c2">Creating and editing the chart</span>
    </p>
    <p class="c3 c20">
      <span class="c1">4. Having a ready table select values of all y-s and on the "INSERT" tab choose "SCATTER CHART ":</span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 500.00px; height: 240.00px;">
        <img alt="" src="images/image90.png" style="width: 500.00px; height: 240.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        To draw charts of mathematical functions usually SCATTER CHART is used(position II or III). In this example we will apply position II.
        <br/>
        <br/>
        <br/>
        <br/>
        Click on the second position and the chart will be created.
        <br/>
        <br/>
        <br/>
        <br/>
        5. Unfortunately, the chart we have created is incorrect so we need to change the values of the data series. First, to make our work easier we need to move the chart to another worksheet. To do this, right-click on the chart and from the context menu select "MOVE CHART":
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 363.00px; height: 150.00px;">
        <img alt="" src="images/image56.png" style="width: 363.00px; height: 150.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        Select "Worksheet 1" and click "Ok". Automatically we will get moved to the second spreadsheet.
        <br/>
        <br/>
        <br/>
        <br/>
        6. Now dragging the corners of the chart to the sides we can stretch it to full screen. This way it will be more comfortable. Then right-click on the chart and from the context menu choose "Select data". You will be moved to the first worksheet and the window "Select Data Source” will appear :
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 467.00px; height: 256.00px;">
        <img alt="" src="images/image75.png" style="width: 467.00px; height: 256.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        7. Select the "y 1" s and click the "Edit" button.
        <br/>
        <br/>
        <br/>
        <br/>
        8. "Edit series" window will display.
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 253.00px; height: 148.00px;">
        <img alt="" src="images/image52.png" style="width: 253.00px; height: 148.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        9. First select in the first text box "Name of series." We need to enter the name for the series. To do this, select the cell B1 (there we have entered the name of the series as "Y1"). So click on the graphical icon at the end of the form box and switch to the first worksheet (you can do this by clicking on the appropriate tab in the lower left corner of Excel window).
        <br/>
        <br/>
        <br/>
        <br/>
        10. Now select cell B1 and again click on the icon at the end of the form box.
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 254.00px; height: 57.00px;">
        <img alt="" src="images/image69.png" style="width: 254.00px; height: 57.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        11. The next step is to provide the values of X series. At the beginning we go to the form box and click the icon at the end. Now select all values of X (from -20 to 20). And again, click on the icon at the end of the text box. Then click twice "OK". The chart will display correctly now.
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 500.00px; height: 297.33px;">
        <img alt="" src="images/image32.png" style="width: 500.00px; height: 297.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c13 c18">
      <span class="c48 c2">Add values of another function to the existing chart</span>
    </p>
    <p class="c3 c20">
      <span class="c1">12. At the beginning we have to add one more column to the existing table. We will call it y2:</span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 400.00px; height: 193.33px;">
        <img alt="" src="images/image42.png" style="width: 400.00px; height: 193.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        13 .The next step is to calculate y, according to the function formula.
        <br/>
        <br/>
        <br/>
        <br/>
        Let’s say the formula is this: y2 = (x-1)/(x+2)
        <br/>
        <br/>
        <br/>
        <br/>
        It should be noted that the argument of the function -2, does not belong to the domain. Later you will find out what to do about it.
        <br/>
        <br/>
        <br/>
        <br/>
        14. Enter the appropriate formula in the cell C2 and drag it to the bottom so that Excel calculates the values of y2 for all x-:
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 300.00px; height: 198.67px;">
        <img alt="" src="images/image70.png" style="width: 300.00px; height: 198.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        15. In the cell C20 the message "# DIV / 0!" is displayed which means that you cannot divide by 0. To get the chart drawn correctly, the cell C20 should be left empty, delete its contents by using "Delete" button.
        <br/>
        <br/>
        <br/>
        <br/>
        If while executing the tasks, messages "Number" or "DIV / 0!" are displayed , we delete them leaving a given cell empty.
        <br/>
        <br/>
        <br/>
        <br/>
        16. Having prepared the table, right-click on the graph and select from the context menu the option "SELECT DATA ...".
        <br/>
        <br/>
        <br/>
        <br/>
        17. Then click "Add" button and following the same pattern as for correcting data in the previous exercise, give the name of the series (cell C1), select the value of all x-s (from -20 to 20).
        <br/>
        <br/>
        <br/>
        <br/>
        18. In the box "Values of Y series" delete everything that is typed and select all values of y2. Double click "Ok".
        <br/>
        <br/>
        <br/>
        <br/>
        19. It’s done now! We have added to the chart another data series called "y2".
        <br/>
        <br/>
        <br/>
        <br/>
        20. Now to make the chart look better you move the mouse cursor on the axis and right-click. From the context menu choose "FORMAT AXES".
        <br/>
        <br/>
        <br/>
        <br/>
        21. In the text box "minimum" enter value "-7" and in the text box maximum enter value "7"
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 200.00px; height: 154.67px;">
        <img alt="" src="images/image99.png" style="width: 200.00px; height: 154.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">22. Click "OK". The chart is ready:</span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 500.00px; height: 301.33px;">
        <img alt="" src="images/image95.png" style="width: 500.00px; height: 301.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <h1 class="c46 c18" id="h.jrq3iommto9a">
      <span class="c14 c5">Exercises</span>
    </h1>
    <p class="c3 c20">
      <span class="c1">
        To the created example add data series of function with a formula as below and move to the folder TASKS BY ...:
        <br/>
        <br/>
        <br/>
      </span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c13 c18">
      <span class="c1">Homework</span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <p class="c7">
      <span class="c1"></span>
    </p>
    <ol class="c8 lst-kix_tzx8mz8hspc7-0 start" start="1">
      <li class="c21 li-bullet-0">
        <span class="c2">
          <br/>
        </span>
        <span class="c56 c5">y3 = (sin^2 x)/x </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c56 c5">
          <br/>
          y4 = (tg(x))/(x+1) 
        </span>
      </li>
      <li class="c21 li-bullet-0">
        <span class="c5 c56">
          <br/>
          y5 = ?(x-2)
        </span>
      </li>
    </ol>
    <h3 class="c46 c18" id="h.5wdoie4sdk0p">
      <span class="c17 c5">Checking knowledge:</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">The data for the chart are taken from:</span>
    </p>
    <p class="c10">
      <span class="c1">all selected cells</span>
    </p>
    <p class="c10">
      <span class="c1">Selected cells, but only those in which there is a number</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">From cells with content (to be explained to students)</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h3 class="c46 c18" id="h.i6j9zhnrabxw">
      <span class="c17 c5">Pie chart</span>
    </h3>
    <p class="c3 c20">
      <span class="c1">
        We were asked to prepare a pie chart with information about the most popular browsers in the world according to their percentages expressed in integral numbers - data for 2011. The leading browsers in the world are as follows (December 2011 according to the StatCounter website)
        <br/>
        <br/>
        <br/>
        <br/>
        Internet Explorer - 38,64%.
        <br/>
        <br/>
        Google Chrome - 27,27%.
        <br/>
        <br/>
        Mozilla Firefox - 25.29%.
        <br/>
        <br/>
        Safari - 6.08%.
        <br/>
        <br/>
        Opera - 1.98%
        <br/>
        <br/>
        Others - 0.74%
        <br/>
        <br/>
        <br/>
        <br/>
        Select the table and on the 'Insert' tab select the Pie chart and subtype 'Pie chart 2-D'.
        <br/>
        <br/>
        <br/>
        <br/>
        2-D Pie Charts are clearer, unfortunately due to the attractive form of 3-D Pie charts they have become much more popular and the audiences expect them.
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 500.00px; height: 306.67px;">
        <img alt="" src="images/image38.png" style="width: 500.00px; height: 306.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        Finding products using small squares with their colors in the legend is very tiring, and when there are a lot of elements or if someone finds it hard to differentiate similar colors it becomes almost impossible impossible.
        <br/>
        <br/>
        <br/>
        <br/>
        Click on a '+', uncheck the 'Legend', select the 'Data Labels', then click an arrow at the 'Data labels' first select the 'End of an external' and 'More options ...'.
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 622.67px; height: 300.00px;">
        <img alt="" src="images/image30.jpg" style="width: 622.67px; height: 300.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        In the 'Format Data Labels' mark:
        <br/>
        <br/>
        - 'Category Name' - so that we know which part of the pie applies to a given product.
        <br/>
        <br/>
        - 'Percentage' - here there is calculated and given an approximate percentage of the total figure
        <br/>
        <br/>
        <br/>
        <br/>
        Uncheck:
        <br/>
        <br/>
        - 'Value' - in order to eliminate unnecessary decimals
        <br/>
        <br/>
        <br/>
        <br/>
        There is a default option 'Show lines leading' - useful for large quantities of pie slices, so that the lines leading the clippings labels are connected.
        <br/>
        <br/>
        <br/>
        <br/>
        Both messages displayed on the labels are separated by new line marks, and we can change it in the 'Separator' menu.
        <br/>
        <br/>
        <br/>
        <br/>
        In this window, it is also possible to change the position of labels and change the format of numbers.
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 634.67px; height: 300.00px;">
        <img alt="" src="images/image3.jpg" style="width: 634.67px; height: 300.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">As in all charts we can also use the styles and colour palettes, which are available when you click the Brush icon.</span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 757.33px; height: 400.00px;">
        <img alt="" src="images/image46.jpg" style="width: 757.33px; height: 400.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        A colour slice can be changed by clicking on it twice individually (with a break between clicks) which will result in the selection (small circles), then click it with the right button and choose the colour changes which are visible on the chart when you move the mouse cursor over the colours.
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 500.00px; height: 342.67px;">
        <img alt="" src="images/image71.jpg" style="width: 500.00px; height: 342.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        To eject the selected clipping simply select it and drag it from the centre of the chart. It is used to draw the attention of the recipient precisely on this passage.
        <br/>
        <br/>
        <br/>
        <br/>
        After bolding the data labels and writing the title, the chart will look like in the figure below.
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 500.00px; height: 354.67px;">
        <img alt="" src="images/image61.jpg" style="width: 500.00px; height: 354.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">In order to get rid of the graph frame right click it, and choose the command 'Format chart area ...'</span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 424.00px;">
        <img alt="" src="images/image92.jpg" style="width: 600.00px; height: 424.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">In the 'Format the Chart ' window choose 'No Line'. Close the window.</span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 669.33px; height: 300.00px;">
        <img alt="" src="images/image65.jpg" style="width: 669.33px; height: 300.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">At any time we can change the chart type by right clicking and selecting 'Change the chart type ...'.</span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 380.00px;">
        <img alt="" src="images/image8.jpg" style="width: 600.00px; height: 380.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">Now let’s choose a 3-D pie chart.</span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 500.00px; height: 470.67px;">
        <img alt="" src="images/image33.jpg" style="width: 500.00px; height: 470.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">For 3-D charts, there are many styles, you have to adjust yourself the right one for the job.</span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 749.33px; height: 400.00px;">
        <img alt="" src="images/image5.jpg" style="width: 749.33px; height: 400.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">By right clicking the chart and selecting 'Rotate 3-D' we will be able to choose how to position the chart, which will highlight the fragment we want.</span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 500.00px; height: 329.33px;">
        <img alt="" src="images/image82.jpg" style="width: 500.00px; height: 329.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3 c20">
      <span class="c1">
        WARNING:
        <br/>
        <br/>
        Increasing Prospects makes the graph less clear, and the section which is at the bottom seems larger than it actually is.
      </span>
    </p>
    <p class="c3 c20">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 800.00px; height: 461.33px;">
        <img alt="" src="images/image84.jpg" style="width: 800.00px; height: 461.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <h3 class="c46 c18" id="h.616c0azhi5ow">
      <span class="c17 c5">CHECKING THE KNOWLEDGE:</span>
    </h3>
    <p class="c13 c20 c29">
      <span class="c4 c5">Graphs can be displayed:</span>
    </p>
    <p class="c10">
      <span class="c1">Only in the spreadsheet where the data comes from</span>
    </p>
    <p class="c10">
      <span class="c1">Only in the data spreadsheet and chart spreadsheet</span>
    </p>
    <p class="c31 c20 c29">
      <span class="c1">You can view ae graph in each of the existing spreadsheets and make it a spreadsheet of the chart</span>
    </p>
    <p class="c13 c20 c29">
      <span class="c15 c5">Check the answer</span>
    </p>
    <p class="c13 c28">
      <span class="c15 c5"></span>
    </p>
    <h3 class="c9" id="h.n2qxl4ckdrtn">
      <span class="c17 c5">Summary</span>
    </h3>
    <p class="c3">
      <span class="c1">In the lesson we presented the basics of creating charts in Excel. Once you have mastered the material you should be able to create charts in Excel. This of course does not cover the whole subject of charts therefore we encourage self-experimentation.</span>
    </p>
    <p class="c13 c28">
      <span class="c42 c5">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62113/chapter/25926&amp;sa=D&amp;source=editors&amp;ust=1714064099844559&amp;usg=AOvVaw3G_R3CvDglQebok4kR9CfA"></a>
      </span>
    </p>
    <h1 class="c44" id="h.xemwvl80jxg3">
      <span class="c49 c55">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62114/chapter/25931&amp;sa=D&amp;source=editors&amp;ust=1714064099845003&amp;usg=AOvVaw26J_nOFrOIJ7xjKr76XaU4">7 </a>
      </span>
      <span class="c48 c50 c22">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62114/chapter/25931&amp;sa=D&amp;source=editors&amp;ust=1714064099845320&amp;usg=AOvVaw1Shk9ng67XbmthP5xB3mYw">Lesson XIII - Introduction to Excel logical functions</a>
      </span>
    </h1>
    <p class="c13">
      <span class="c34 c22">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62114/chapter/25931&amp;sa=D&amp;source=editors&amp;ust=1714064099845724&amp;usg=AOvVaw3G40l7tG-rdLYaPNTIXUNW">15.03.2024 11:46 | Number of chapters: 6</a>
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h3 class="c9" id="h.ga9q5e6wy7oj">
      <span class="c17 c5">Introduction</span>
    </h3>
    <p class="c3">
      <span class="c1">The logical functions in Excel are extremely useful, and often indispensable in everyday work. It is hard to imagine a serious spreadsheet e.g. without built-in IF function. The logical functions are primarily used to check whether the values entered in the worksheet’s cells meet the conditions. Only rarely are they used alone, most often they are nested in formulas, being arguments for other functions (often they return a table of numerical values as a parameter for mathematical or statistical functions).</span>
    </p>
    <h3 class="c9" id="h.zfy00g4dyj72">
      <span class="c17 c5">Learning effects</span>
    </h3>
    <p class="c3">
      <span class="c2">
        Once the material of this lesson has been mastered, the student should be able to easily solve the basic problems associated with the use of logical functions in Excel.
        <br/>
        <br/>
        <br/>
        <br/>
        For example :
        <br/>
        <br/>
        "Create a formula that will grant a discount on monthly tickets or not, according to the following principles:
        <br/>
        <br/>
        People who are entitled to discounts need to meet two conditions simultaneously:
        <br/>
        <br/>
        a) be retired
        <br/>
        <br/>
        b) their monthly income per capita cannot exceed 600 zł "
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c1 c39">[FILM]</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h3 class="c9" id="h.3qfuflntfwjh">
      <span class="c17 c5">Basics of logical functions</span>
    </h3>
    <p class="c3">
      <span class="c1">
        TRUE()
        <br/>
        <br/>
        This function has no arguments, it always returns the logical value TRUE. You can also enter this value directly into a cell or formula.
        <br/>
        <br/>
        <br/>
        <br/>
        FALSE()
        <br/>
        <br/>
        This function has no arguments, it always returns the logical value FALSE. You can also enter this value directly into a cell or formula.
        <br/>
        <br/>
        <br/>
        <br/>
        Both of these functions seem to be absolutely unnecessary in Excel and have been introduced in order to comply with other spreadsheets.
        <br/>
        <br/>
        <br/>
        <br/>
        IF()
        <br/>
        <br/>
        This function checks the logical condition specified in the first argument of the function. If the condition is fulfilled (TRUE) then the value of the second argument is returned, and if not (FALSE) - the value of the third argument is returned.
        <br/>
        <br/>
        <br/>
        <br/>
        The syntax of the IF function () is presented below:
        <br/>
        <br/>
        • logical-test - to check the logical condition of a value or expression, the result of which can be calculated as a logical value (TRUE or FALSE). The logical condition often uses logical comparison operators such as =,&gt;, &lt;,&gt; =, &lt;=, &lt;&gt; to show the values of cells. For example, B2 = 9 is a logical expression; if the value entered into cell B2 is actually number 9, this expression will be evaluated to TRUE, in any other case, the expression will have the logical value FALSE
        <br/>
        <br/>
        <br/>
        <br/>
        • value_if_true - the second argument of the function is the value returned when the first argument logical_test is met. If our logical test is the expression B2 = 9 and in the cell B2 there is in fact number 9, then the result of the function - the value of the second argument - may be a text message "in this cell there is number 9". This is an optional argument that can be omitted by placing two semicolons after the first argument. Omitting it indicates that it is a default argument, whose resulting value is TRUE
        <br/>
        <br/>
        <br/>
        <br/>
        • value_if_false - the third argument of the function is the value returned when the first argument logical_test returns the value FALSE. If our logical test is still the expression B2 = 9, and in cell B2 there is a different value (number, text, error, logical value) or the cell is empty, the result of the function (the value of the third argument) can be a text message "the value of this cell is different from number 9". Leaving the argument empty will result in returning the value FALSE. Two optional arguments CANNOT be omitted at the same time, at least one of them should be determined
        <br/>
        <br/>
        <br/>
        <br/>
        The use of IF function is presented below
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 500.00px; height: 141.33px;">
        <img alt="" src="images/image67.jpg" style="width: 500.00px; height: 141.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        =IF(B2 = $ 9; "in this cell is number 9"; "the value of this cell is different from the number 9")
        <br/>
        <br/>
        <br/>
        <br/>
        The result of the function is presented depending on the value of the cell on the left side of the formula. Only in one case, the logical expression is true. Excel does not apply automatic conversion here and properly distinguishes numeric values from the text, that’s why number 9 that is preceded by an apostrophe is treated as text (logical condition returns FALSE, while the formula - the text that is included in the third argument of the function value_if_false).
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h3 class="c9" id="h.elq3f4g7c6yv">
      <span class="c17 c5">Examples of logical function IF ()</span>
    </h3>
    <p class="c3">
      <span class="c1">
        The first example shows the logical condition with statistical function. Apart from the comparison operator that has been mentioned above we use here statistical function AVERAGE ().
        <br/>
        <br/>
        <br/>
        <br/>
        The task is to reward students who have obtained the average grade of at least 4.50 in the given subjects - they are entitled to a scholarship for their academic performance.
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 1033.00px; height: 296.00px;">
        <img alt="" src="images/image85.jpg" style="width: 1033.00px; height: 296.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        The formula in cell F4 checks the average of four subjects and it looks like this:
        <br/>
        <br/>
        =IF(AVERAGE ($B4:$E4)&gt;= 4.5; "yes - "&amp;TEXT(AVERAGE($B4:$E4);"0.00"); "no - "&amp;TEXT(AVERAGE ($ B4: $ E4), "0.00"))
        <br/>
        <br/>
        <br/>
        <br/>
        The most important in this case is the logical condition, that is checking whether the average of the four subjects is higher than or equals 4.50. If this happens, the formula returns the text
        <br/>
        <br/>
        <br/>
        <br/>
        "yes –“ and shows the average grade for the student, otherwise it returns the text "no -" together with the average grade. Another way is to create two separate columns: average grade, and information about the scholarship (in this case, it is possible e.g. to sort by average).
        <br/>
        <br/>
        <br/>
        <br/>
        The second example shows nesting of the function IF (). Some logical problems can be solved only after multiple nesting of this function e.g. when the need to allocate the grade according to the value range in which the score is.
        <br/>
        <br/>
        <br/>
        <br/>
        Below there is a table in which students were assigned grades according to the number of points obtained in the exam.
        <br/>
        <br/>
        <br/>
        <br/>
        The formula for cell C4 is:
        <br/>
        <br/>
        = IF ($ C4&gt; 18; "very good"; IF ($ C4&gt; 14; "good"; IF ($ C4&gt; 10; "satisfactory", "unsatisfactory")))
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 838.00px; height: 334.00px;">
        <img alt="" src="images/image15.jpg" style="width: 838.00px; height: 334.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        It is worth to remember a few important things:
        <br/>
        <br/>
        • The IF () can be nested up to 7 times in a formula in Excel 2003. For Excel 2007 you can nest it up to 64 times, but the formula will not work correctly in the earlier versions of Excel, so it is advisable to use up to 7 nestings in a single formula. In case of our formula the function IF ()has been nested three times.
        <br/>
        <br/>
        <br/>
        <br/>
        • The second instruction of IF function () is simultaneously an argument value_if_false for the first instruction of the function (view 4). Similarly, the third instruction of IF function () is an argument value_if_false for the second instruction and so on.
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 400.00px; height: 198.67px;">
        <img alt="" src="images/image29.jpg" style="width: 400.00px; height: 198.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">• The formula checks the first logical condition and stops when it returns TRUE (as a result it returns the value of the second argument). If the returned value is FALSE - the formula moves to the second condition etc. In our example (score = 11), the first condition $ C5&gt; 18 is false, the second $ C5&gt; 14 also returns FALSE. Only the third $ C5&gt; 10 is met - the result of the formula is thus the word "sufficient".</span>
    </p>
    <p class="c3">
      <span class="c1">• For any number of points lower than 11 each of the three conditions returns FALSE. In such situation (in another case)the formula returns the word "unsatisfactory".</span>
    </p>
    <h3 class="c9" id="h.9jjoari0hxs9">
      <span class="c17 c5">The AND () function - Expansion function IF ()</span>
    </h3>
    <h3 class="c9" id="h.uo8shfr8ae5t">
      <span class="c17 c5">AND()</span>
    </h3>
    <p class="c3">
      <span class="c1">
        The AND () works in conjunction with IF (), extending its operation. IF () in basic form operates only one logical condition, while the AND () allows you to enter up to 30 logical conditions. To perform function as a result of TRUE, it is necessary that each of the conditions, function arguments, he was satisfied. If at least one of the accepted conditions is FALSE, the function returns a result of FALSE.
        <br/>
        <br/>
        <br/>
        <br/>
        AND () it is therefore, in other words, the product of (a conjunction) conditions. Be very careful to keep all function arguments logical values using other types of values, as very simply, you can generate an error. Using arguments and empty text is permitted only in particularly justified cases - only if the second argument is a reference to an empty cell or one that contains text, the formula will work - the data entered in the parameters manually generate this error #VALUE !.
        <br/>
        <br/>
        <br/>
        <br/>
        The following table is presented on the basis of which in a very useful function can be used, AND (). The task concerns the selection of candidates for the position of Analyst in our company. In total, it reported seven people who were tested in various fields. The assumption is that we are interested in people who are very familiar with English, Excel, and have obtained at least 15 points in our test checking the knowledge of controlling. If the candidate meets all these conditions, it is admitted to the second stage of recruitment; otherwise eliminated.
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 642.00px; height: 313.00px;">
        <img alt="" src="images/image77.jpg" style="width: 642.00px; height: 313.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        The formula contained in the H4 as follows:
        <br/>
        <br/>
        = IF(AND($C4&gt;14; $D4="yes";$F4="yes");"Stage II", "Not applicable")
        <br/>
        <br/>
        <br/>
        <br/>
        • For the first person formula returns the text '' Void '' because it was not satisfied with the conditions of the other very good knowledge of English. Although the other two conditions have been satisfied - AND function () returns a result of FALSE, and the function IF () converts a specific text message.
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h3 class="c9" id="h.oyr62bzbxg4b">
      <span class="c17 c5">The OR () function - Expansion function IF ()</span>
    </h3>
    <h3 class="c9" id="h.17heniaq2ljo">
      <span class="c17 c5">OR()</span>
    </h3>
    <p class="c3">
      <span class="c1">
        The OR () - like function AND () - interacts with function IF (), allowing for a more extensive tests. If you want the function to pay as a result of TRUE, it is required that at least one of the conditions, function arguments, he was satisfied. If all of the accepted conditions are FALSE, the function returns a result of FALSE. OR () it is therefore, in other words, the sum of (alternative) conditions. Using arguments and empty text it is handled by a function similarly to the function AND ().
        <br/>
        <br/>
        <br/>
        <br/>
        The following tables present the same as for the AND () but with different results. This time we carry out recruitment for the position of Specialist. Database, because the eligibility criteria for the next stage are different. The candidate this time must meet two conditions: be fluent in Access, and at least one of the two languages.
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 642.00px; height: 313.00px;">
        <img alt="" src="images/image16.jpg" style="width: 642.00px; height: 313.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        The formula contained in the H4 as follows:
        <br/>
        <br/>
        = IF(AND($G4="yes";OR($D4="yes";$E4="yes")); "Stage II";"eliminated")
        <br/>
        <br/>
        <br/>
        <br/>
        • Here we have a combination of conjunctions and alternative conditions. Conjunction is that the candidate must meet two conditions, an alternative that requires a good knowledge of any foreign language.
        <br/>
        <br/>
      </span>
    </p>
    <h3 class="c9" id="h.cxekna3ux7nk">
      <span class="c17 c5">CHECKING THE KNOWLEDGE:</span>
    </h3>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 500.00px; height: 212.00px;">
        <img alt="" src="images/image105.png" style="width: 500.00px; height: 212.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c2">
        a) =IF(AND(G12="yes";E12&lt;=600);"discount";"without discounts")
        <br/>
        <br/>
        b) =IF(AND(G12&lt;600;OR(E12="yes";F12="yes")); "discount", "no discount")
        <br/>
        <br/>
        c) = IF (AND(G12&lt;=600;OR(E12="yes"; F12="yes")),"discount","no discount") - 
      </span>
      <span class="c4 c5">AND at the beginning because we have to choose options A and B and then oR (students or retirement) and G12&lt;=600 (not to exceed 600 zł)</span>
    </p>
    <h3 class="c9" id="h.b57r39k60b5l">
      <span class="c17 c5">Summary</span>
    </h3>
    <p class="c3">
      <span class="c1">In addition to the IF function () all logical functions return as a result of the logical type TRUE / FALSE. The IF () can be used in many different ways: by means of nesting you can check a number of different conditions; treating each cell in the range as a parameter to a function of mathematical, statistical or information, you can make calculations (eg. to count or sum up) only in those cells that meet certain criteria. Functions AND () and OR () operate on individual cells and allow you to develop logical tests, which are very often used in the making of advanced formulas. We encourage you to own adventure with logic functions.</span>
    </p>
    <p class="c3 c28">
      <span class="c1">
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c1 c39">Test In the attached file SXXXXX-WSI-INTERNET-TEST-EXCEL-LOGICAL-FUNCTIONS.xlsx Scoring max 10 0.5 + 1 + 2 + 2 + (9 * 0.5)</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <p class="c13 c28">
      <span class="c0">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62114/chapter/25931&amp;sa=D&amp;source=editors&amp;ust=1714064099852767&amp;usg=AOvVaw1CgLS4F4wjsP7_gMf58xmF"></a>
      </span>
    </p>
    <h1 class="c44" id="h.9n636vh0asko">
      <span class="c49 c55">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62115/chapter/25937&amp;sa=D&amp;source=editors&amp;ust=1714064099853247&amp;usg=AOvVaw0-o_RkUI_9SS7J6x1IrBB9">8 </a>
      </span>
      <span class="c48 c50">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62115/chapter/25937&amp;sa=D&amp;source=editors&amp;ust=1714064099853572&amp;usg=AOvVaw2mDu0QnmAdDQNiYGjNiWFC">Lesson XIV - Pivot tables basics</a>
      </span>
    </h1>
    <p class="c13">
      <span class="c34 c5">
        <a class="c12" href="https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62115/chapter/25937&amp;sa=D&amp;source=editors&amp;ust=1714064099854001&amp;usg=AOvVaw0X6KAIDWgR5xI8bdVkK-yk">15.03.2024 11:46 | Number of chapters: 4</a>
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h3 class="c9" id="h.y3uvbzg1x7x4">
      <span class="c17 c5">Introduction</span>
    </h3>
    <p class="c3">
      <span class="c1">
        Excel pivot table is a powerful analytical tool. The main functionality of pivot tables that is used, is the possibility of a quick, easy and transparent summary and analysis of large data sets. However it is not the only functionality of pivot tables
        <br/>
        <br/>
      </span>
    </p>
    <h3 class="c9" id="h.3djh6dlcwgww">
      <span class="c17 c5">Learning outcomes</span>
    </h3>
    <p class="c3">
      <span class="c1">Once the student has mastered the material of this lesson, they should be able to easily create pivot tables according to the set purpose (e.g. What is the sales figure by certain regions and years?) out of the given data file (e.g. sales volume) and modify the created tables as needed.</span>
    </p>
    <h3 class="c9" id="h.mrbztalrpu4">
      <span class="c17 c5">Pivot Table out of data file</span>
    </h3>
    <p class="c3 c28">
      <span class="c17 c5">
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
    </p>
    <p class="c13 c19">
      <span class="c1"></span>
    </p>
    <p class="c13 c22">
      <span class="c1 c39">2 Source data - Excel i movie</span>
    </p>
    <p class="c3">
      <span class="c1">To create a Pivot Table we will use the file "PivotTable-Data.xlsx" After opening the file the content is displayed as it is shown below.</span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 800.00px; height: 433.33px;">
        <img alt="" src="images/image23.jpg" style="width: 800.00px; height: 433.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        The data have been generated in such a way that each row contains information about the sale, purchase, plan, price, quantity and margin. To these data there are assigned: branch, region, date of sale and the information on the sale (resulting from the date).
        <br/>
        <br/>
        <br/>
        <br/>
        Note that the figures are formatted.
      </span>
    </p>
    <p class="c13 c22">
      <span class="c48 c2">The goal to achieve</span>
    </p>
    <p class="c3">
      <span class="c1">At the beginning we set ourselves an easy goal, in order to make aquiring information about Pivot Tables nice and easy:</span>
    </p>
    <h3 class="c9" id="h.gss0qq80vh3r">
      <span class="c17 c5">What is the value of sales by individual regions and years?</span>
    </h3>
    <p class="c3">
      <span class="c1">The task that we need to do can be easily accomplished using other built-in Excel functions, let’s say SUM.IFS. function. My goal is to show the possibilities of a Pivot Table, not to convince anyone that this is the only appropriate tool for summarizing and analyzing data. Nevertheless this is a great tool.</span>
    </p>
    <p class="c13 c22">
      <span class="c48 c2">Creating a Pivot Table</span>
    </p>
    <p class="c3">
      <span class="c1">
        Set the active cell in the source data. This is select any cell on the data out of which you want to create a Pivot Table.
        <br/>
        <br/>
        <br/>
        <br/>
        Then, on the Insert tab of the Tables group select the command Pivot Table. If you click on the upper part of the Pivot Table icon, then immediately the dialog box Create a Pivot Table will be displayed. If you click on the arrow under the icon, you will have to choose from the available commands the one about creating a Pivot Table.
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 401.00px; height: 188.00px;">
        <img alt="" src="images/image63.jpg" style="width: 401.00px; height: 188.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        In the Create Pivot Table dialog box, in which Excel automatically detected and entered the range of the source data in the field Select a table or range.
        <br/>
        <br/>
        <br/>
        <br/>
        To place the Pivot Table in the new worksheet, leave the default selection in the part of the dialog box referring to the position of the Pivot Table report.
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 401.00px; height: 335.00px;">
        <img alt="" src="images/image100.png" style="width: 401.00px; height: 335.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        After confirmation the Pivot Table is ready to work. The new worksheet with an empty Pivot Table has been inserted. On the right side there appeared the Pivot Table Field List, below which there are areas of the Pivot Table. Additionally, on the ribbon there appeared a group of contextual tabs Pivot Table Tools, which include cards Options and Design.
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 800.00px; height: 434.67px;">
        <img alt="" src="images/image58.jpg" style="width: 800.00px; height: 434.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c13 c22">
      <span class="c48 c2">Pivot Table Areas</span>
    </p>
    <h3 class="c9" id="h.po5bcqdk09pj">
      <span class="c17 c5">Report filter</span>
    </h3>
    <p class="c3">
      <span class="c1">In this area we place fields from the PivotTable Field List, which are used to filter data. The values of the fields located in the filter will not be visible in the PivotTable.</span>
    </p>
    <h3 class="c9" id="h.1eoh6h98s8hi">
      <span class="c17 c5">Row labels</span>
    </h3>
    <p class="c3">
      <span class="c1">Labels placed in rows, like row headers in an ordinary table.</span>
    </p>
    <h3 class="c9" id="h.z47gri9uyg49">
      <span class="c17 c5">Column labels</span>
    </h3>
    <p class="c3">
      <span class="c1">The labels placed in columns, like column headers in an ordinary table.</span>
    </p>
    <h3 class="c9" id="h.s6pgm2jn6r4z">
      <span class="c17 c5">Values</span>
    </h3>
    <p class="c3">
      <span class="c1">
        The values of the fields located in this area will be summed up. Besides summing up, we can perform other activities on them, but you will learn more about them later on.
        <br/>
        <br/>
        <br/>
        <br/>
        To sum up the values of the fields located in the area of value, it is necessary that these values are recognized by Excel as numbers.
      </span>
    </p>
    <p class="c13 c22">
      <span class="c2 c48">Placing fields in PivotTable areas</span>
    </p>
    <p class="c3">
      <span class="c1">
        We can place the fields in the PivotTable areas in several ways.
        <br/>
        <br/>
        <br/>
        <br/>
        One of them is to select the chosen fields in the PivotTable Field List, the fields will be placed in areas selected by Excel.
        <br/>
        <br/>
        <br/>
        <br/>
        Pay attention to the field of Years, which shows the number representing the year in date.
        <br/>
        <br/>
        <br/>
        <br/>
        This field has been placed in the area of values, and the values in column Years have been summed up!
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 800.00px; height: 434.67px;">
        <img alt="" src="images/image43.jpg" style="width: 800.00px; height: 434.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c2">
        After selecting the fields we can change their position and the way of summing up the field, but a faster way is to place the fields in the appropriate areas right away.
        <br/>
        <br/>
        <br/>
        <br/>
        A more convenient and a faster way is to drag fields from the PivotTable Field List to the selected areas. Click any mouse button (it does not matter whether left or right) on the selected area and drag it to the selected area.
        <br/>
        <br/>
        <br/>
        <br/>
        Let’s recall the set purpose: 
      </span>
      <span class="c2 c25">
        What is the value of sales grouped by individual regions and years?
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c2">We are interested in the fields </span>
      <span class="c4">Sales</span>
      <span class="c2">, </span>
      <span class="c4">Region</span>
      <span class="c2">&#160;and </span>
      <span class="c4">Years</span>
      <span class="c2">
        . The order of placing them in the table can be varied.
        <br/>
        <br/>
        <br/>
        <br/>
        To achieve the goal that was set earlier we need to do the following:
        <br/>
        <br/>
        1. Drag the 
      </span>
      <span class="c4">Sales</span>
      <span class="c2">&#160;field to the </span>
      <span class="c4">Values </span>
      <span class="c1">area</span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 800.00px; height: 434.67px;">
        <img alt="" src="images/image47.jpg" style="width: 800.00px; height: 434.67px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c2">2. Drag the field </span>
      <span class="c4">Region </span>
      <span class="c2">to the area </span>
      <span class="c4 c5">Rows</span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 800.00px; height: 433.33px;">
        <img alt="" src="images/image11.jpg" style="width: 800.00px; height: 433.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c2">3. Drag the field </span>
      <span class="c4">Years </span>
      <span class="c2">to the area </span>
      <span class="c4 c5">
        Columns
        <br/>
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 800.00px; height: 433.33px;">
        <img alt="" src="images/image39.jpg" style="width: 800.00px; height: 433.33px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        Finished! Pivot Table has been prepared. The goal has been achieved.
        <br/>
        <br/>
        <br/>
        <br/>
        We value sales broken down by regions and years, however, these data are difficult to read.
      </span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
    <h3 class="c9" id="h.5juikxmhmk4r">
      <span class="c17 c5">Modifying Pivot Table</span>
    </h3>
    <p class="c3">
      <span class="c1">
        We created a PivotTable in Excel that displays a summary of the values in column with the sales data broken down by region (placed in rows) and years (placed in columns).
        <br/>
        <br/>
        <br/>
        <br/>
        The new goal to achieve
        <br/>
        <br/>
        Early formatting of the data source from which you create a PivotTable does not affect the format of the data in the pivot table. The data in the PivotTable is displayed in the general format. How do you change the format of the data for each field to have useful information is displayed in a clear manner?
        <br/>
        <br/>
        <br/>
        <br/>
        How do you change the format of the data for each field?
        <br/>
        <br/>
        Display format can be changed in several ways. In this section we will describe the most commonly used ones.
        <br/>
        <br/>
      </span>
    </p>
    <p class="c13 c22">
      <span class="c48 c2">Calling the Settings dialog box values.</span>
    </p>
    <p class="c3">
      <span class="c1">
        1. Left-click on the box located in the area of values and select Settings in the value field.
        <br/>
        <br/>
        2. Set the active cell in the pivot table in the data for this field. We can also set up a cell in the row or column totals, and in the cell, which displays the name of the function used for the field (in our case this cell is the cell with the entry Sum of Sales.) It is important that on the Options tab in the group Active box was displayed name fields, which change the format of the displayed data is affected. When you select a cell on the Options tab in the group Active box, click on the Value Field Settings.
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 800.00px; height: 436.00px;">
        <img alt="" src="images/image98.jpg" style="width: 800.00px; height: 436.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c13 c22">
      <span class="c48 c2">Change the format of data displayed.</span>
    </p>
    <p class="c3">
      <span class="c1">When you click on the Settings value field will show the Settings dialog box values.</span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 388.00px; height: 324.00px;">
        <img alt="" src="images/image109.png" style="width: 388.00px; height: 324.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">
        We can change the way data summary (e.g. The sum of these values on the counter) but we will not do it this example. Click on the button Number Format. A window appears Format Cells, which will be visible only card numbers. We can now format the data for the selected field according to their own needs. In this case, I am changing the category on the numerical decimal places I set to 0 and turn on the grouping of numbers after 3 digits by checking the Use 1000 Separator (,).
        <br/>
        <br/>
      </span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 535.00px; height: 465.00px;">
        <img alt="" src="images/image102.png" style="width: 535.00px; height: 465.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <p class="c3">
      <span class="c1">Finished! Once approved, the data is formatted pivot table is as follows.</span>
    </p>
    <p class="c3">
      <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 800.00px; height: 436.00px;">
        <img alt="" src="images/image106.jpg" style="width: 800.00px; height: 436.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""/>
      </span>
    </p>
    <h3 class="c9" id="h.ci2w159j2a0r">
      <span class="c17 c5">Summary</span>
    </h3>
    <p class="c3">
      <span class="c2">
        In the lesson it has been presented how to use pivot tables to let you quickly, easily and clearly summarize and analyze large data sets. Modification of displayed results also does not cause problems. Of course, this does not cover the whole subject pivot tables in Excel. We encourage you to exercise your own research as well.
        <br/>
        <br/>
        <br/>
        <br/>
      </span>
      <span class="c1 c39">In the attached files PivotTable-Data.xls – data for lesson TEST: WSI-INTERNET-TEST-EXCEL-PIVOT-TABLES.pdf SXXXXX-WSI-INTERNET-TEST-EXCEL-PIVOT-TABLES.xlsx Scoring max 6 Point for each task</span>
    </p>
    <p class="c13 c28">
      <span class="c0"></span>
    </p>
</body>
</html>
MARKDOWN 
Introduction to information systems (WSI) Lectures  @import url(https://themes.googleusercontent.com/fonts/css?kit=jcFLf8ZX0K0voV0Wtl8DVwWg0g-wft8BWv\_rYzdOKxw);ul.lst-kix\_m6xa40k4vexm-6{list-style-type:none}ul.lst-kix\_m6xa40k4vexm-7{list-style-type:none}ul.lst-kix\_m6xa40k4vexm-8{list-style-type:none}.lst-kix\_kuovaf6uwbxb-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_kuovaf6uwbxb-4&gt;li:before{content:"\\0025cb "}.lst-kix\_kuovaf6uwbxb-1&gt;li:before{content:"\\0025cb "}.lst-kix\_kuovaf6uwbxb-3&gt;li:before{content:"\\0025cf "}.lst-kix\_kuovaf6uwbxb-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_hz7e6qe4lbhh-3&gt;li{counter-increment:lst-ctn-kix\_hz7e6qe4lbhh-3}.lst-kix\_kuovaf6uwbxb-0&gt;li:before{content:"\\0025cf "}.lst-kix\_v4y75fpnt0mm-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_v4y75fpnt0mm-7&gt;li:before{content:"\\0025cb "}.lst-kix\_v4y75fpnt0mm-6&gt;li:before{content:"\\0025cf "}.lst-kix\_v4y75fpnt0mm-4&gt;li:before{content:"\\0025cb "}.lst-kix\_v4y75fpnt0mm-3&gt;li:before{content:"\\0025cf "}.lst-kix\_v4y75fpnt0mm-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_kuovaf6uwbxb-6&gt;li:before{content:"\\0025cf "}.lst-kix\_v4y75fpnt0mm-1&gt;li:before{content:"\\0025cb "}.lst-kix\_kuovaf6uwbxb-7&gt;li:before{content:"\\0025cb "}.lst-kix\_v4y75fpnt0mm-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_kuovaf6uwbxb-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_oqq2ui921j1-0&gt;li:before{content:"\\0025cf "}.lst-kix\_oqq2ui921j1-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_v4y75fpnt0mm-0&gt;li:before{content:"\\0025cf "}.lst-kix\_ouu0f4ii1rn1-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_oqq2ui921j1-1&gt;li:before{content:"\\0025cb "}.lst-kix\_oqq2ui921j1-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_wkdyljpeit7k-4{list-style-type:none}ul.lst-kix\_wkdyljpeit7k-5{list-style-type:none}ul.lst-kix\_wkdyljpeit7k-2{list-style-type:none}ul.lst-kix\_wkdyljpeit7k-3{list-style-type:none}ul.lst-kix\_wkdyljpeit7k-0{list-style-type:none}ul.lst-kix\_wkdyljpeit7k-1{list-style-type:none}ul.lst-kix\_uhcf91an71wf-0{list-style-type:none}ul.lst-kix\_uhcf91an71wf-2{list-style-type:none}ul.lst-kix\_uhcf91an71wf-1{list-style-type:none}ul.lst-kix\_uhcf91an71wf-4{list-style-type:none}ul.lst-kix\_uhcf91an71wf-3{list-style-type:none}ul.lst-kix\_uhcf91an71wf-6{list-style-type:none}.lst-kix\_evax12ghdetq-4&gt;li{counter-increment:lst-ctn-kix\_evax12ghdetq-4}ul.lst-kix\_uhcf91an71wf-5{list-style-type:none}ul.lst-kix\_uhcf91an71wf-8{list-style-type:none}ul.lst-kix\_uhcf91an71wf-7{list-style-type:none}ul.lst-kix\_m6xa40k4vexm-2{list-style-type:none}ul.lst-kix\_m6xa40k4vexm-3{list-style-type:none}ul.lst-kix\_m6xa40k4vexm-4{list-style-type:none}ul.lst-kix\_m6xa40k4vexm-5{list-style-type:none}.lst-kix\_tzx8mz8hspc7-3&gt;li{counter-increment:lst-ctn-kix\_tzx8mz8hspc7-3}ul.lst-kix\_m6xa40k4vexm-0{list-style-type:none}ul.lst-kix\_m6xa40k4vexm-1{list-style-type:none}.lst-kix\_olrmfo3e8daa-4&gt;li:before{content:"\\0025cb "}.lst-kix\_tzx8mz8hspc7-1&gt;li:before{content:"" counter(lst-ctn-kix\_tzx8mz8hspc7-1,lower-latin) ". "}.lst-kix\_olrmfo3e8daa-0&gt;li:before{content:"\\0025cf "}.lst-kix\_olrmfo3e8daa-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_olrmfo3e8daa-6&gt;li:before{content:"\\0025cf "}.lst-kix\_tzx8mz8hspc7-5&gt;li:before{content:"" counter(lst-ctn-kix\_tzx8mz8hspc7-5,lower-roman) ". "}.lst-kix\_tzx8mz8hspc7-3&gt;li:before{content:"" counter(lst-ctn-kix\_tzx8mz8hspc7-3,decimal) ". "}.lst-kix\_sbnx2aog7wgo-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_43hhuxt2rq9t-7{list-style-type:none}.lst-kix\_olrmfo3e8daa-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_43hhuxt2rq9t-8{list-style-type:none}.lst-kix\_sbnx2aog7wgo-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_43hhuxt2rq9t-3{list-style-type:none}ul.lst-kix\_poxumw20mduo-2{list-style-type:none}.lst-kix\_bu096cxa7zy2-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_43hhuxt2rq9t-4{list-style-type:none}ul.lst-kix\_poxumw20mduo-3{list-style-type:none}ul.lst-kix\_43hhuxt2rq9t-5{list-style-type:none}ul.lst-kix\_poxumw20mduo-0{list-style-type:none}ul.lst-kix\_43hhuxt2rq9t-6{list-style-type:none}ul.lst-kix\_poxumw20mduo-1{list-style-type:none}.lst-kix\_bu096cxa7zy2-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_2zf3qhky0qd4-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_43hhuxt2rq9t-0{list-style-type:none}ul.lst-kix\_43hhuxt2rq9t-1{list-style-type:none}ul.lst-kix\_43hhuxt2rq9t-2{list-style-type:none}.lst-kix\_bu096cxa7zy2-7&gt;li:before{content:"\\0025cb "}.lst-kix\_ouu0f4ii1rn1-1&gt;li:before{content:"\\0025cb "}.lst-kix\_2zf3qhky0qd4-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_poxumw20mduo-8{list-style-type:none}ul.lst-kix\_wkdyljpeit7k-8{list-style-type:none}ul.lst-kix\_poxumw20mduo-6{list-style-type:none}ul.lst-kix\_poxumw20mduo-7{list-style-type:none}ul.lst-kix\_wkdyljpeit7k-6{list-style-type:none}ul.lst-kix\_poxumw20mduo-4{list-style-type:none}ul.lst-kix\_wkdyljpeit7k-7{list-style-type:none}ul.lst-kix\_poxumw20mduo-5{list-style-type:none}.lst-kix\_ouu0f4ii1rn1-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_oqq2ui921j1-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_oqq2ui921j1-7&gt;li:before{content:"\\0025cb "}.lst-kix\_ouu0f4ii1rn1-3&gt;li:before{content:"\\0025cf "}.lst-kix\_2zf3qhky0qd4-0&gt;li:before{content:"\\0025cf "}.lst-kix\_ouu0f4ii1rn1-7&gt;li:before{content:"\\0025cb "}ol.lst-kix\_evax12ghdetq-8{list-style-type:none}ol.lst-kix\_evax12ghdetq-7{list-style-type:none}.lst-kix\_a1n97pss2xec-3&gt;li:before{content:"\\0025cf "}ol.lst-kix\_evax12ghdetq-6{list-style-type:none}ol.lst-kix\_evax12ghdetq-5{list-style-type:none}ol.lst-kix\_evax12ghdetq-0.start{counter-reset:lst-ctn-kix\_evax12ghdetq-0 0}ol.lst-kix\_evax12ghdetq-4{list-style-type:none}ol.lst-kix\_evax12ghdetq-3{list-style-type:none}ol.lst-kix\_evax12ghdetq-2{list-style-type:none}ol.lst-kix\_evax12ghdetq-1{list-style-type:none}ol.lst-kix\_evax12ghdetq-0{list-style-type:none}.lst-kix\_a1n97pss2xec-1&gt;li:before{content:"\\0025cb "}ol.lst-kix\_tzx8mz8hspc7-4.start{counter-reset:lst-ctn-kix\_tzx8mz8hspc7-4 0}.lst-kix\_xhpr2ex4dnkl-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_2zf3qhky0qd4-7{list-style-type:none}ul.lst-kix\_2zf3qhky0qd4-6{list-style-type:none}ul.lst-kix\_2zf3qhky0qd4-8{list-style-type:none}.lst-kix\_xhpr2ex4dnkl-7&gt;li:before{content:"\\0025cb "}.lst-kix\_cmtzg17lkw6e-6&gt;li:before{content:"\\0025cf "}.lst-kix\_8bw4pomaqyc2-6&gt;li:before{content:"\\0025cf "}.lst-kix\_cmtzg17lkw6e-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_5m2k735u0wc3-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_8bw4pomaqyc2-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_uy6mucuvaggy-6{list-style-type:none}ul.lst-kix\_uy6mucuvaggy-5{list-style-type:none}.lst-kix\_5m2k735u0wc3-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_uy6mucuvaggy-4{list-style-type:none}ul.lst-kix\_uy6mucuvaggy-3{list-style-type:none}.lst-kix\_evax12ghdetq-5&gt;li{counter-increment:lst-ctn-kix\_evax12ghdetq-5}ul.lst-kix\_uy6mucuvaggy-2{list-style-type:none}ul.lst-kix\_uy6mucuvaggy-1{list-style-type:none}ul.lst-kix\_uy6mucuvaggy-0{list-style-type:none}ul.lst-kix\_2zf3qhky0qd4-1{list-style-type:none}ul.lst-kix\_2zf3qhky0qd4-0{list-style-type:none}ul.lst-kix\_2zf3qhky0qd4-3{list-style-type:none}ul.lst-kix\_2zf3qhky0qd4-2{list-style-type:none}.lst-kix\_5m2k735u0wc3-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_uy6mucuvaggy-8{list-style-type:none}ul.lst-kix\_2zf3qhky0qd4-5{list-style-type:none}ul.lst-kix\_uy6mucuvaggy-7{list-style-type:none}ul.lst-kix\_2zf3qhky0qd4-4{list-style-type:none}ul.lst-kix\_4ozj8cu0p377-8{list-style-type:none}.lst-kix\_pf6gjug0y9iv-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_4ozj8cu0p377-7{list-style-type:none}ul.lst-kix\_d0j69qeqtikc-8{list-style-type:none}ul.lst-kix\_4ozj8cu0p377-6{list-style-type:none}ol.lst-kix\_hz7e6qe4lbhh-4.start{counter-reset:lst-ctn-kix\_hz7e6qe4lbhh-4 0}ul.lst-kix\_4ozj8cu0p377-5{list-style-type:none}.lst-kix\_bu096cxa7zy2-1&gt;li:before{content:"\\0025cb "}.lst-kix\_sbnx2aog7wgo-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_4ozj8cu0p377-0{list-style-type:none}.lst-kix\_pf6gjug0y9iv-1&gt;li:before{content:"\\0025cb "}.lst-kix\_5m2k735u0wc3-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_tzx8mz8hspc7-7&gt;li:before{content:"" counter(lst-ctn-kix\_tzx8mz8hspc7-7,lower-latin) ". "}ul.lst-kix\_4ozj8cu0p377-4{list-style-type:none}.lst-kix\_pf6gjug0y9iv-3&gt;li:before{content:"\\0025cf "}.lst-kix\_5m2k735u0wc3-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_4ozj8cu0p377-3{list-style-type:none}.lst-kix\_sbnx2aog7wgo-1&gt;li:before{content:"\\0025cb "}.lst-kix\_8bw4pomaqyc2-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_4ozj8cu0p377-2{list-style-type:none}ul.lst-kix\_4ozj8cu0p377-1{list-style-type:none}ul.lst-kix\_uqx5pvtk1sx7-5{list-style-type:none}ul.lst-kix\_ahbvbvxjsk00-8{list-style-type:none}ul.lst-kix\_uqx5pvtk1sx7-4{list-style-type:none}ul.lst-kix\_uqx5pvtk1sx7-3{list-style-type:none}ul.lst-kix\_uqx5pvtk1sx7-2{list-style-type:none}ul.lst-kix\_uqx5pvtk1sx7-8{list-style-type:none}.lst-kix\_8bw4pomaqyc2-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_uqx5pvtk1sx7-7{list-style-type:none}ul.lst-kix\_uqx5pvtk1sx7-6{list-style-type:none}ul.lst-kix\_d0j69qeqtikc-2{list-style-type:none}ul.lst-kix\_d0j69qeqtikc-3{list-style-type:none}ul.lst-kix\_d0j69qeqtikc-0{list-style-type:none}ul.lst-kix\_d0j69qeqtikc-1{list-style-type:none}ul.lst-kix\_d0j69qeqtikc-6{list-style-type:none}ul.lst-kix\_uqx5pvtk1sx7-1{list-style-type:none}ul.lst-kix\_d0j69qeqtikc-7{list-style-type:none}ul.lst-kix\_uqx5pvtk1sx7-0{list-style-type:none}.lst-kix\_8bw4pomaqyc2-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_d0j69qeqtikc-4{list-style-type:none}ul.lst-kix\_d0j69qeqtikc-5{list-style-type:none}.lst-kix\_t9f7ru8r1rgs-1&gt;li:before{content:"\\0025cb "}.lst-kix\_t9f7ru8r1rgs-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_kuovaf6uwbxb-4{list-style-type:none}.lst-kix\_t9f7ru8r1rgs-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_t9f7ru8r1rgs-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_kuovaf6uwbxb-3{list-style-type:none}ul.lst-kix\_kuovaf6uwbxb-6{list-style-type:none}ul.lst-kix\_kuovaf6uwbxb-5{list-style-type:none}ul.lst-kix\_kuovaf6uwbxb-0{list-style-type:none}ul.lst-kix\_kuovaf6uwbxb-2{list-style-type:none}ul.lst-kix\_kuovaf6uwbxb-1{list-style-type:none}ol.lst-kix\_evax12ghdetq-4.start{counter-reset:lst-ctn-kix\_evax12ghdetq-4 0}.lst-kix\_tzx8mz8hspc7-4&gt;li{counter-increment:lst-ctn-kix\_tzx8mz8hspc7-4}.lst-kix\_ywahawqva4s1-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_kuovaf6uwbxb-8{list-style-type:none}ul.lst-kix\_kuovaf6uwbxb-7{list-style-type:none}ol.lst-kix\_tzx8mz8hspc7-3.start{counter-reset:lst-ctn-kix\_tzx8mz8hspc7-3 0}.lst-kix\_ywahawqva4s1-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_pf6gjug0y9iv-7&gt;li:before{content:"\\0025cb "}ol.lst-kix\_hz7e6qe4lbhh-8.start{counter-reset:lst-ctn-kix\_hz7e6qe4lbhh-8 0}ul.lst-kix\_k9z0wtrlykrk-5{list-style-type:none}ul.lst-kix\_k9z0wtrlykrk-6{list-style-type:none}ul.lst-kix\_k9z0wtrlykrk-3{list-style-type:none}ul.lst-kix\_k9z0wtrlykrk-4{list-style-type:none}.lst-kix\_pf6gjug0y9iv-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_k9z0wtrlykrk-7{list-style-type:none}ul.lst-kix\_k9z0wtrlykrk-8{list-style-type:none}ul.lst-kix\_k9z0wtrlykrk-1{list-style-type:none}ul.lst-kix\_k9z0wtrlykrk-2{list-style-type:none}ul.lst-kix\_k9z0wtrlykrk-0{list-style-type:none}.lst-kix\_xhpr2ex4dnkl-4&gt;li:before{content:"\\0025cb "}.lst-kix\_cmtzg17lkw6e-4&gt;li:before{content:"\\0025cb "}.lst-kix\_w0yl8nmrwp6o-1&gt;li:before{content:"\\0025cb "}.lst-kix\_cmtzg17lkw6e-3&gt;li:before{content:"\\0025cf "}.lst-kix\_xhpr2ex4dnkl-1&gt;li:before{content:"\\0025cb "}.lst-kix\_cmtzg17lkw6e-0&gt;li:before{content:"\\0025cf "}.lst-kix\_a1n97pss2xec-6&gt;li:before{content:"\\0025cf "}.lst-kix\_3ewi2x1kv5uq-1&gt;li:before{content:"\\0025cb "}.lst-kix\_xhpr2ex4dnkl-0&gt;li:before{content:"\\0025cf "}.lst-kix\_a1n97pss2xec-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_w0yl8nmrwp6o-0&gt;li:before{content:"\\0025cf "}.lst-kix\_w0yl8nmrwp6o-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_4ozj8cu0p377-0&gt;li:before{content:"\\0025cf "}.lst-kix\_4ozj8cu0p377-4&gt;li:before{content:"\\0025cb "}.lst-kix\_3ewi2x1kv5uq-0&gt;li:before{content:"\\0025cf "}.lst-kix\_w0yl8nmrwp6o-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_4ozj8cu0p377-3&gt;li:before{content:"\\0025cf "}.lst-kix\_w0yl8nmrwp6o-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_8z53ty2gz3mr-2{list-style-type:none}ul.lst-kix\_8z53ty2gz3mr-1{list-style-type:none}.lst-kix\_2zf3qhky0qd4-6&gt;li:before{content:"\\0025cf "}.lst-kix\_2zf3qhky0qd4-7&gt;li:before{content:"\\0025cb "}.lst-kix\_ywahawqva4s1-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_8z53ty2gz3mr-4{list-style-type:none}ul.lst-kix\_8z53ty2gz3mr-3{list-style-type:none}.lst-kix\_ywahawqva4s1-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_8z53ty2gz3mr-6{list-style-type:none}ul.lst-kix\_8z53ty2gz3mr-5{list-style-type:none}.lst-kix\_4ozj8cu0p377-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_8z53ty2gz3mr-8{list-style-type:none}ul.lst-kix\_8z53ty2gz3mr-7{list-style-type:none}.lst-kix\_3ewi2x1kv5uq-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_4ozj8cu0p377-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_8z53ty2gz3mr-0{list-style-type:none}.lst-kix\_3ewi2x1kv5uq-5&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_evax12ghdetq-5.start{counter-reset:lst-ctn-kix\_evax12ghdetq-5 0}.lst-kix\_3ewi2x1kv5uq-4&gt;li:before{content:"\\0025cb "}.lst-kix\_olrmfo3e8daa-7&gt;li:before{content:"\\0025cb "}.lst-kix\_anjmmosejwns-1&gt;li:before{content:"\\0025cb "}.lst-kix\_tzx8mz8hspc7-2&gt;li:before{content:"" counter(lst-ctn-kix\_tzx8mz8hspc7-2,lower-roman) ". "}.lst-kix\_tzx8mz8hspc7-6&gt;li:before{content:"" counter(lst-ctn-kix\_tzx8mz8hspc7-6,decimal) ". "}.lst-kix\_sbnx2aog7wgo-4&gt;li:before{content:"\\0025cb "}.lst-kix\_olrmfo3e8daa-3&gt;li:before{content:"\\0025cf "}.lst-kix\_anjmmosejwns-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_wkdyljpeit7k-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_bu096cxa7zy2-4&gt;li:before{content:"\\0025cb "}.lst-kix\_wkdyljpeit7k-1&gt;li:before{content:"\\0025cb "}.lst-kix\_2zf3qhky0qd4-3&gt;li:before{content:"\\0025cf "}.lst-kix\_ouu0f4ii1rn1-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_sbnx2aog7wgo-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_sbnx2aog7wgo-0{list-style-type:none}.lst-kix\_a1n97pss2xec-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_oqq2ui921j1-4&gt;li:before{content:"\\0025cb "}.lst-kix\_oqq2ui921j1-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_ewlea9l5v2mb-6&gt;li:before{content:"\\0025cf "}.lst-kix\_ouu0f4ii1rn1-6&gt;li:before{content:"\\0025cf "}.lst-kix\_bu096cxa7zy2-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_sbnx2aog7wgo-6{list-style-type:none}ul.lst-kix\_sbnx2aog7wgo-5{list-style-type:none}ul.lst-kix\_sbnx2aog7wgo-8{list-style-type:none}ul.lst-kix\_sbnx2aog7wgo-7{list-style-type:none}ul.lst-kix\_sbnx2aog7wgo-2{list-style-type:none}ul.lst-kix\_sbnx2aog7wgo-1{list-style-type:none}ul.lst-kix\_sbnx2aog7wgo-4{list-style-type:none}ul.lst-kix\_sbnx2aog7wgo-3{list-style-type:none}.lst-kix\_l3f4cvceui9t-3&gt;li:before{content:"\\0025cf "}.lst-kix\_ikb4dfai24wa-4&gt;li:before{content:"\\0025cb "}.lst-kix\_tzx8mz8hspc7-2&gt;li{counter-increment:lst-ctn-kix\_tzx8mz8hspc7-2}ul.lst-kix\_ib9j2ls61eto-1{list-style-type:none}ul.lst-kix\_ib9j2ls61eto-2{list-style-type:none}.lst-kix\_cmtzg17lkw6e-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_ib9j2ls61eto-0{list-style-type:none}.lst-kix\_l3f4cvceui9t-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_ib9j2ls61eto-5{list-style-type:none}ul.lst-kix\_ib9j2ls61eto-6{list-style-type:none}ul.lst-kix\_ib9j2ls61eto-3{list-style-type:none}.lst-kix\_ikb4dfai24wa-0&gt;li:before{content:"\\0025cf "}.lst-kix\_ikb4dfai24wa-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_ib9j2ls61eto-4{list-style-type:none}.lst-kix\_67axahw2bw4y-3&gt;li:before{content:"\\0025cf "}.lst-kix\_xhpr2ex4dnkl-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_ib9j2ls61eto-7{list-style-type:none}ul.lst-kix\_ib9j2ls61eto-8{list-style-type:none}.lst-kix\_67axahw2bw4y-7&gt;li:before{content:"\\0025cb "}.lst-kix\_5m2k735u0wc3-3&gt;li:before{content:"\\0025cf "}.lst-kix\_5m2k735u0wc3-7&gt;li:before{content:"\\0025cb "}.lst-kix\_ahbvbvxjsk00-3&gt;li:before{content:"\\0025cf "}ol.lst-kix\_tzx8mz8hspc7-8.start{counter-reset:lst-ctn-kix\_tzx8mz8hspc7-8 0}.lst-kix\_eyq40i4uxhci-7&gt;li:before{content:"\\0025cb "}.lst-kix\_pf6gjug0y9iv-4&gt;li:before{content:"\\0025cb "}.lst-kix\_bu096cxa7zy2-0&gt;li:before{content:"\\0025cf "}.lst-kix\_uy6mucuvaggy-6&gt;li:before{content:"\\0025cf "}.lst-kix\_sbnx2aog7wgo-0&gt;li:before{content:"\\0025cf "}.lst-kix\_8bw4pomaqyc2-1&gt;li:before{content:"\\0025cb "}.lst-kix\_ahbvbvxjsk00-7&gt;li:before{content:"\\0025cb "}.lst-kix\_uy6mucuvaggy-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_pf6gjug0y9iv-0&gt;li:before{content:"\\0025cf "}.lst-kix\_8bw4pomaqyc2-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_pxgusehopho8-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_ikb4dfai24wa-3{list-style-type:none}ul.lst-kix\_ikb4dfai24wa-4{list-style-type:none}.lst-kix\_pxgusehopho8-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_ikb4dfai24wa-5{list-style-type:none}ol.lst-kix\_evax12ghdetq-1.start{counter-reset:lst-ctn-kix\_evax12ghdetq-1 0}ul.lst-kix\_ikb4dfai24wa-6{list-style-type:none}.lst-kix\_tzx8mz8hspc7-5&gt;li{counter-increment:lst-ctn-kix\_tzx8mz8hspc7-5}ul.lst-kix\_ikb4dfai24wa-0{list-style-type:none}ul.lst-kix\_ikb4dfai24wa-1{list-style-type:none}.lst-kix\_u906582iea27-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_ikb4dfai24wa-2{list-style-type:none}ul.lst-kix\_m3s6obof6xsw-3{list-style-type:none}ul.lst-kix\_m3s6obof6xsw-2{list-style-type:none}ol.lst-kix\_hz7e6qe4lbhh-5.start{counter-reset:lst-ctn-kix\_hz7e6qe4lbhh-5 0}.lst-kix\_pxgusehopho8-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_m3s6obof6xsw-1{list-style-type:none}.lst-kix\_u906582iea27-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_m3s6obof6xsw-0{list-style-type:none}ul.lst-kix\_m3s6obof6xsw-7{list-style-type:none}ul.lst-kix\_m3s6obof6xsw-6{list-style-type:none}ul.lst-kix\_m3s6obof6xsw-5{list-style-type:none}ul.lst-kix\_m3s6obof6xsw-4{list-style-type:none}.lst-kix\_pxgusehopho8-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_u906582iea27-3&gt;li:before{content:"\\0025cf "}.lst-kix\_pxgusehopho8-6&gt;li:before{content:"\\0025cf "}.lst-kix\_u906582iea27-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_ikb4dfai24wa-7{list-style-type:none}ul.lst-kix\_ikb4dfai24wa-8{list-style-type:none}.lst-kix\_u906582iea27-2&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_tzx8mz8hspc7-0.start{counter-reset:lst-ctn-kix\_tzx8mz8hspc7-0 0}.lst-kix\_eyq40i4uxhci-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_t9f7ru8r1rgs-7{list-style-type:none}ul.lst-kix\_t9f7ru8r1rgs-8{list-style-type:none}ul.lst-kix\_t9f7ru8r1rgs-5{list-style-type:none}ul.lst-kix\_t9f7ru8r1rgs-6{list-style-type:none}.lst-kix\_eyq40i4uxhci-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_t9f7ru8r1rgs-3{list-style-type:none}ul.lst-kix\_t9f7ru8r1rgs-4{list-style-type:none}ul.lst-kix\_t9f7ru8r1rgs-1{list-style-type:none}ul.lst-kix\_t9f7ru8r1rgs-2{list-style-type:none}.lst-kix\_8frcs3cb9mlx-6&gt;li:before{content:"\\0025cf "}.lst-kix\_eyq40i4uxhci-0&gt;li:before{content:"\\0025cf "}.lst-kix\_hz7e6qe4lbhh-5&gt;li{counter-increment:lst-ctn-kix\_hz7e6qe4lbhh-5}ol.lst-kix\_evax12ghdetq-6.start{counter-reset:lst-ctn-kix\_evax12ghdetq-6 0}.lst-kix\_ewlea9l5v2mb-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_t9f7ru8r1rgs-0{list-style-type:none}ol.lst-kix\_hz7e6qe4lbhh-0.start{counter-reset:lst-ctn-kix\_hz7e6qe4lbhh-0 0}.lst-kix\_ewlea9l5v2mb-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_ewlea9l5v2mb-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_cfvoc5d5ri28-3{list-style-type:none}ul.lst-kix\_lyr3b2ph9j2j-5{list-style-type:none}ul.lst-kix\_cfvoc5d5ri28-4{list-style-type:none}ul.lst-kix\_lyr3b2ph9j2j-4{list-style-type:none}ul.lst-kix\_cfvoc5d5ri28-1{list-style-type:none}ul.lst-kix\_lyr3b2ph9j2j-3{list-style-type:none}ul.lst-kix\_cfvoc5d5ri28-2{list-style-type:none}ul.lst-kix\_lyr3b2ph9j2j-2{list-style-type:none}ul.lst-kix\_cfvoc5d5ri28-0{list-style-type:none}ul.lst-kix\_lyr3b2ph9j2j-8{list-style-type:none}ul.lst-kix\_lyr3b2ph9j2j-7{list-style-type:none}ol.lst-kix\_tzx8mz8hspc7-5.start{counter-reset:lst-ctn-kix\_tzx8mz8hspc7-5 0}ul.lst-kix\_lyr3b2ph9j2j-6{list-style-type:none}.lst-kix\_ihu4chqckap9-0&gt;li:before{content:"\\0025cf "}.lst-kix\_cg2acydq40lf-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_2fs6d4epazv0-8{list-style-type:none}.lst-kix\_anjmmosejwns-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_cg2acydq40lf-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_2fs6d4epazv0-4{list-style-type:none}ul.lst-kix\_2fs6d4epazv0-5{list-style-type:none}ul.lst-kix\_2fs6d4epazv0-6{list-style-type:none}.lst-kix\_ihu4chqckap9-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_2fs6d4epazv0-7{list-style-type:none}ul.lst-kix\_2fs6d4epazv0-0{list-style-type:none}ul.lst-kix\_2fs6d4epazv0-1{list-style-type:none}ul.lst-kix\_2fs6d4epazv0-2{list-style-type:none}ul.lst-kix\_2fs6d4epazv0-3{list-style-type:none}.lst-kix\_uqx5pvtk1sx7-1&gt;li:before{content:"\\0025cb "}.lst-kix\_anjmmosejwns-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_cfvoc5d5ri28-7{list-style-type:none}ul.lst-kix\_cfvoc5d5ri28-8{list-style-type:none}.lst-kix\_ihu4chqckap9-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_cfvoc5d5ri28-5{list-style-type:none}ul.lst-kix\_cfvoc5d5ri28-6{list-style-type:none}.lst-kix\_wkdyljpeit7k-4&gt;li:before{content:"\\0025cb "}.lst-kix\_wkdyljpeit7k-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_y48cfiwpd1yk-3&gt;li:before{content:"\\0025cf "}.lst-kix\_ewlea9l5v2mb-5&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_evax12ghdetq-3.start{counter-reset:lst-ctn-kix\_evax12ghdetq-3 0}.lst-kix\_y48cfiwpd1yk-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_3ewi2x1kv5uq-0{list-style-type:none}ul.lst-kix\_3ewi2x1kv5uq-1{list-style-type:none}ul.lst-kix\_vez8xevq8akx-3{list-style-type:none}ul.lst-kix\_3ewi2x1kv5uq-2{list-style-type:none}.lst-kix\_ikb4dfai24wa-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_vez8xevq8akx-2{list-style-type:none}ul.lst-kix\_bu096cxa7zy2-0{list-style-type:none}ul.lst-kix\_3ewi2x1kv5uq-3{list-style-type:none}.lst-kix\_l3f4cvceui9t-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_vez8xevq8akx-5{list-style-type:none}ul.lst-kix\_bu096cxa7zy2-1{list-style-type:none}ul.lst-kix\_3ewi2x1kv5uq-4{list-style-type:none}ul.lst-kix\_vez8xevq8akx-4{list-style-type:none}ul.lst-kix\_bu096cxa7zy2-2{list-style-type:none}ul.lst-kix\_3ewi2x1kv5uq-5{list-style-type:none}ul.lst-kix\_3ewi2x1kv5uq-6{list-style-type:none}.lst-kix\_ikb4dfai24wa-7&gt;li:before{content:"\\0025cb "}.lst-kix\_ahbvbvxjsk00-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_3ewi2x1kv5uq-7{list-style-type:none}ul.lst-kix\_vez8xevq8akx-1{list-style-type:none}ul.lst-kix\_3ewi2x1kv5uq-8{list-style-type:none}.lst-kix\_67axahw2bw4y-0&gt;li:before{content:"\\0025cf "}.lst-kix\_sz2een1y35py-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_vez8xevq8akx-0{list-style-type:none}ol.lst-kix\_tzx8mz8hspc7-7{list-style-type:none}ol.lst-kix\_tzx8mz8hspc7-8{list-style-type:none}.lst-kix\_l3f4cvceui9t-0&gt;li:before{content:"\\0025cf "}ol.lst-kix\_tzx8mz8hspc7-3{list-style-type:none}.lst-kix\_l3f4cvceui9t-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_8frcs3cb9mlx-3&gt;li:before{content:"\\0025cf "}ol.lst-kix\_tzx8mz8hspc7-4{list-style-type:none}ol.lst-kix\_tzx8mz8hspc7-5{list-style-type:none}.lst-kix\_67axahw2bw4y-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_sz2een1y35py-2&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_tzx8mz8hspc7-6{list-style-type:none}ol.lst-kix\_tzx8mz8hspc7-0{list-style-type:none}ol.lst-kix\_tzx8mz8hspc7-1{list-style-type:none}ol.lst-kix\_tzx8mz8hspc7-2{list-style-type:none}.lst-kix\_67axahw2bw4y-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_bu096cxa7zy2-7{list-style-type:none}.lst-kix\_8frcs3cb9mlx-1&gt;li:before{content:"\\0025cb "}.lst-kix\_ahbvbvxjsk00-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_bu096cxa7zy2-8{list-style-type:none}.lst-kix\_eyq40i4uxhci-8&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_hz7e6qe4lbhh-3.start{counter-reset:lst-ctn-kix\_hz7e6qe4lbhh-3 0}ul.lst-kix\_vez8xevq8akx-7{list-style-type:none}ul.lst-kix\_bu096cxa7zy2-3{list-style-type:none}ul.lst-kix\_vez8xevq8akx-6{list-style-type:none}ul.lst-kix\_bu096cxa7zy2-4{list-style-type:none}ul.lst-kix\_bu096cxa7zy2-5{list-style-type:none}ul.lst-kix\_vez8xevq8akx-8{list-style-type:none}ul.lst-kix\_bu096cxa7zy2-6{list-style-type:none}ul.lst-kix\_xhpr2ex4dnkl-4{list-style-type:none}ul.lst-kix\_xhpr2ex4dnkl-3{list-style-type:none}ul.lst-kix\_xhpr2ex4dnkl-2{list-style-type:none}.lst-kix\_m6xa40k4vexm-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_xhpr2ex4dnkl-1{list-style-type:none}ul.lst-kix\_xhpr2ex4dnkl-0{list-style-type:none}.lst-kix\_uy6mucuvaggy-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_qxqu9g2j7hjr-8{list-style-type:none}ul.lst-kix\_qxqu9g2j7hjr-7{list-style-type:none}.lst-kix\_m6xa40k4vexm-7&gt;li:before{content:"\\0025cb "}.lst-kix\_uqx5pvtk1sx7-7&gt;li:before{content:"\\0025cb "}ol.lst-kix\_tzx8mz8hspc7-2.start{counter-reset:lst-ctn-kix\_tzx8mz8hspc7-2 0}ul.lst-kix\_qxqu9g2j7hjr-0{list-style-type:none}ul.lst-kix\_qxqu9g2j7hjr-2{list-style-type:none}ul.lst-kix\_m3s6obof6xsw-8{list-style-type:none}ul.lst-kix\_qxqu9g2j7hjr-1{list-style-type:none}ul.lst-kix\_qxqu9g2j7hjr-4{list-style-type:none}.lst-kix\_ahbvbvxjsk00-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_qxqu9g2j7hjr-3{list-style-type:none}ul.lst-kix\_qxqu9g2j7hjr-6{list-style-type:none}ul.lst-kix\_qxqu9g2j7hjr-5{list-style-type:none}ul.lst-kix\_xhpr2ex4dnkl-8{list-style-type:none}ul.lst-kix\_xhpr2ex4dnkl-7{list-style-type:none}ul.lst-kix\_xhpr2ex4dnkl-6{list-style-type:none}ul.lst-kix\_xhpr2ex4dnkl-5{list-style-type:none}.lst-kix\_uy6mucuvaggy-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_ewlea9l5v2mb-2{list-style-type:none}ul.lst-kix\_ewlea9l5v2mb-3{list-style-type:none}ul.lst-kix\_ewlea9l5v2mb-0{list-style-type:none}ul.lst-kix\_ewlea9l5v2mb-1{list-style-type:none}.lst-kix\_t9f7ru8r1rgs-4&gt;li:before{content:"\\0025cb "}.lst-kix\_hz7e6qe4lbhh-2&gt;li{counter-increment:lst-ctn-kix\_hz7e6qe4lbhh-2}ul.lst-kix\_boxwjc60mpgf-1{list-style-type:none}.lst-kix\_3ipl4jxrgfvg-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_boxwjc60mpgf-0{list-style-type:none}.lst-kix\_hz7e6qe4lbhh-2&gt;li:before{content:"" counter(lst-ctn-kix\_hz7e6qe4lbhh-2,lower-roman) ". "}ul.lst-kix\_boxwjc60mpgf-3{list-style-type:none}ul.lst-kix\_boxwjc60mpgf-2{list-style-type:none}ul.lst-kix\_boxwjc60mpgf-5{list-style-type:none}ul.lst-kix\_boxwjc60mpgf-4{list-style-type:none}ul.lst-kix\_boxwjc60mpgf-7{list-style-type:none}ul.lst-kix\_boxwjc60mpgf-6{list-style-type:none}.lst-kix\_hz7e6qe4lbhh-7&gt;li:before{content:"" counter(lst-ctn-kix\_hz7e6qe4lbhh-7,lower-latin) ". "}.lst-kix\_3ipl4jxrgfvg-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_boxwjc60mpgf-8{list-style-type:none}.lst-kix\_ywahawqva4s1-4&gt;li:before{content:"\\0025cb "}.lst-kix\_3ipl4jxrgfvg-8&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_hz7e6qe4lbhh-2.start{counter-reset:lst-ctn-kix\_hz7e6qe4lbhh-2 0}.lst-kix\_t9f7ru8r1rgs-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_ewlea9l5v2mb-8{list-style-type:none}ul.lst-kix\_ewlea9l5v2mb-6{list-style-type:none}ul.lst-kix\_ewlea9l5v2mb-7{list-style-type:none}.lst-kix\_cmtzg17lkw6e-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_ewlea9l5v2mb-4{list-style-type:none}ul.lst-kix\_ewlea9l5v2mb-5{list-style-type:none}.lst-kix\_poxumw20mduo-0&gt;li:before{content:"\\0025cf "}.lst-kix\_cmtzg17lkw6e-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_xhpr2ex4dnkl-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_a1n97pss2xec-7&gt;li:before{content:"\\0025cb "}.lst-kix\_w0yl8nmrwp6o-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_w0yl8nmrwp6o-7&gt;li:before{content:"\\0025cb "}.lst-kix\_a1n97pss2xec-4&gt;li:before{content:"\\0025cb "}.lst-kix\_4ozj8cu0p377-1&gt;li:before{content:"\\0025cb "}.lst-kix\_poxumw20mduo-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_poxumw20mduo-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_hz7e6qe4lbhh-6&gt;li{counter-increment:lst-ctn-kix\_hz7e6qe4lbhh-6}.lst-kix\_ywahawqva4s1-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_y48cfiwpd1yk-8{list-style-type:none}.lst-kix\_3q4kfur98hw3-1&gt;li:before{content:"\\0025cb "}.lst-kix\_2zf3qhky0qd4-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_y48cfiwpd1yk-1{list-style-type:none}ul.lst-kix\_y48cfiwpd1yk-0{list-style-type:none}.lst-kix\_4ozj8cu0p377-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_y48cfiwpd1yk-3{list-style-type:none}ul.lst-kix\_y48cfiwpd1yk-2{list-style-type:none}.lst-kix\_h94ugxasirk3-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_y48cfiwpd1yk-5{list-style-type:none}ul.lst-kix\_y48cfiwpd1yk-4{list-style-type:none}ul.lst-kix\_y48cfiwpd1yk-7{list-style-type:none}ul.lst-kix\_y48cfiwpd1yk-6{list-style-type:none}ol.lst-kix\_hz7e6qe4lbhh-1.start{counter-reset:lst-ctn-kix\_hz7e6qe4lbhh-1 0}.lst-kix\_3ewi2x1kv5uq-3&gt;li:before{content:"\\0025cf "}.lst-kix\_h94ugxasirk3-1&gt;li:before{content:"\\0025cb "}.lst-kix\_3q4kfur98hw3-4&gt;li:before{content:"\\0025cb "}.lst-kix\_3ewi2x1kv5uq-6&gt;li:before{content:"\\0025cf "}.lst-kix\_e1ilhl9h2irp-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_olrmfo3e8daa-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_ihu4chqckap9-3&gt;li:before{content:"\\0025cf "}.lst-kix\_cg2acydq40lf-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_pxgusehopho8-0{list-style-type:none}.lst-kix\_lyr3b2ph9j2j-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_m3s6obof6xsw-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_anjmmosejwns-7&gt;li:before{content:"\\0025cb "}.lst-kix\_uqx5pvtk1sx7-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_pxgusehopho8-2{list-style-type:none}ul.lst-kix\_pxgusehopho8-1{list-style-type:none}ul.lst-kix\_pxgusehopho8-4{list-style-type:none}ul.lst-kix\_pxgusehopho8-3{list-style-type:none}ul.lst-kix\_pxgusehopho8-6{list-style-type:none}ul.lst-kix\_lyr3b2ph9j2j-1{list-style-type:none}.lst-kix\_2zf3qhky0qd4-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_pxgusehopho8-5{list-style-type:none}ul.lst-kix\_lyr3b2ph9j2j-0{list-style-type:none}ul.lst-kix\_pxgusehopho8-8{list-style-type:none}.lst-kix\_tzx8mz8hspc7-4&gt;li:before{content:"" counter(lst-ctn-kix\_tzx8mz8hspc7-4,lower-latin) ". "}.lst-kix\_szafnxrkjncx-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_pxgusehopho8-7{list-style-type:none}.lst-kix\_wkdyljpeit7k-7&gt;li:before{content:"\\0025cb "}.lst-kix\_d0j69qeqtikc-0&gt;li:before{content:"\\0025cf "}.lst-kix\_8z53ty2gz3mr-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_ouu0f4ii1rn1-0&gt;li:before{content:"\\0025cf "}.lst-kix\_y48cfiwpd1yk-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_ib9j2ls61eto-0&gt;li:before{content:"\\0025cf "}.lst-kix\_ewlea9l5v2mb-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_o316414q4358-4{list-style-type:none}.lst-kix\_ib9j2ls61eto-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_o316414q4358-5{list-style-type:none}ul.lst-kix\_o316414q4358-6{list-style-type:none}.lst-kix\_qxqu9g2j7hjr-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_o316414q4358-7{list-style-type:none}ul.lst-kix\_o316414q4358-8{list-style-type:none}.lst-kix\_ikb4dfai24wa-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_8bw4pomaqyc2-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_o316414q4358-0{list-style-type:none}.lst-kix\_y48cfiwpd1yk-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_o316414q4358-1{list-style-type:none}.lst-kix\_cfvoc5d5ri28-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_o316414q4358-2{list-style-type:none}ul.lst-kix\_o316414q4358-3{list-style-type:none}.lst-kix\_qxqu9g2j7hjr-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_8nyroabd25ur-6{list-style-type:none}ul.lst-kix\_8nyroabd25ur-7{list-style-type:none}.lst-kix\_ahbvbvxjsk00-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_8nyroabd25ur-8{list-style-type:none}.lst-kix\_tzx8mz8hspc7-1&gt;li{counter-increment:lst-ctn-kix\_tzx8mz8hspc7-1}ul.lst-kix\_8nyroabd25ur-2{list-style-type:none}ul.lst-kix\_8nyroabd25ur-3{list-style-type:none}.lst-kix\_tzx8mz8hspc7-8&gt;li{counter-increment:lst-ctn-kix\_tzx8mz8hspc7-8}ul.lst-kix\_8nyroabd25ur-4{list-style-type:none}.lst-kix\_sz2een1y35py-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_8nyroabd25ur-5{list-style-type:none}.lst-kix\_67axahw2bw4y-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_l3f4cvceui9t-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_uhcf91an71wf-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_8nyroabd25ur-0{list-style-type:none}.lst-kix\_bu096cxa7zy2-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_8nyroabd25ur-1{list-style-type:none}.lst-kix\_sbnx2aog7wgo-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_pf6gjug0y9iv-6&gt;li:before{content:"\\0025cf "}.lst-kix\_uy6mucuvaggy-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_m6xa40k4vexm-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_boxwjc60mpgf-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_5m2k735u0wc3-1&gt;li:before{content:"\\0025cb "}li.li-bullet-0:before{margin-left:-18pt;white-space:nowrap;display:inline-block;min-width:18pt}ul.lst-kix\_pf6gjug0y9iv-5{list-style-type:none}ul.lst-kix\_pf6gjug0y9iv-6{list-style-type:none}.lst-kix\_vez8xevq8akx-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_pf6gjug0y9iv-7{list-style-type:none}ul.lst-kix\_pf6gjug0y9iv-8{list-style-type:none}.lst-kix\_uy6mucuvaggy-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_pf6gjug0y9iv-1{list-style-type:none}ul.lst-kix\_pf6gjug0y9iv-2{list-style-type:none}ul.lst-kix\_pf6gjug0y9iv-3{list-style-type:none}ul.lst-kix\_pf6gjug0y9iv-4{list-style-type:none}.lst-kix\_d0j69qeqtikc-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_pf6gjug0y9iv-0{list-style-type:none}.lst-kix\_o316414q4358-7&gt;li:before{content:"\\0025cb "}ol.lst-kix\_tzx8mz8hspc7-6.start{counter-reset:lst-ctn-kix\_tzx8mz8hspc7-6 0}.lst-kix\_nhxf08ng0zjh-0&gt;li:before{content:"\\0025cf "}.lst-kix\_43hhuxt2rq9t-6&gt;li:before{content:"\\0025cf "}.lst-kix\_43hhuxt2rq9t-7&gt;li:before{content:"\\0025cb "}.lst-kix\_nhxf08ng0zjh-1&gt;li:before{content:"\\0025cb "}.lst-kix\_nhxf08ng0zjh-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_nhxf08ng0zjh-3&gt;li:before{content:"\\0025cf "}.lst-kix\_43hhuxt2rq9t-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_evax12ghdetq-8&gt;li{counter-increment:lst-ctn-kix\_evax12ghdetq-8}ul.lst-kix\_szafnxrkjncx-0{list-style-type:none}.lst-kix\_43hhuxt2rq9t-0&gt;li:before{content:"\\0025cf "}ol.lst-kix\_evax12ghdetq-7.start{counter-reset:lst-ctn-kix\_evax12ghdetq-7 0}ul.lst-kix\_szafnxrkjncx-4{list-style-type:none}ul.lst-kix\_szafnxrkjncx-3{list-style-type:none}ul.lst-kix\_szafnxrkjncx-2{list-style-type:none}ul.lst-kix\_szafnxrkjncx-1{list-style-type:none}ul.lst-kix\_szafnxrkjncx-8{list-style-type:none}ul.lst-kix\_szafnxrkjncx-7{list-style-type:none}ul.lst-kix\_szafnxrkjncx-6{list-style-type:none}ul.lst-kix\_szafnxrkjncx-5{list-style-type:none}.lst-kix\_43hhuxt2rq9t-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_tzx8mz8hspc7-7&gt;li{counter-increment:lst-ctn-kix\_tzx8mz8hspc7-7}.lst-kix\_43hhuxt2rq9t-4&gt;li:before{content:"\\0025cb "}.lst-kix\_43hhuxt2rq9t-3&gt;li:before{content:"\\0025cf "}.lst-kix\_43hhuxt2rq9t-1&gt;li:before{content:"\\0025cb "}.lst-kix\_43hhuxt2rq9t-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_evax12ghdetq-1&gt;li:before{content:"" counter(lst-ctn-kix\_evax12ghdetq-1,lower-latin) ". "}.lst-kix\_2fs6d4epazv0-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_k9z0wtrlykrk-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_k9z0wtrlykrk-7&gt;li:before{content:"\\0025cb "}.lst-kix\_evax12ghdetq-3&gt;li:before{content:"" counter(lst-ctn-kix\_evax12ghdetq-3,decimal) ". "}.lst-kix\_evax12ghdetq-2&gt;li:before{content:"" counter(lst-ctn-kix\_evax12ghdetq-2,lower-roman) ". "}.lst-kix\_2fs6d4epazv0-7&gt;li:before{content:"\\0025cb "}.lst-kix\_k9z0wtrlykrk-6&gt;li:before{content:"\\0025cf "}.lst-kix\_2fs6d4epazv0-4&gt;li:before{content:"\\0025cb "}.lst-kix\_k9z0wtrlykrk-3&gt;li:before{content:"\\0025cf "}.lst-kix\_2fs6d4epazv0-6&gt;li:before{content:"\\0025cf "}.lst-kix\_evax12ghdetq-0&gt;li:before{content:"" counter(lst-ctn-kix\_evax12ghdetq-0,decimal) ". "}.lst-kix\_2fs6d4epazv0-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_k9z0wtrlykrk-4&gt;li:before{content:"\\0025cb "}.lst-kix\_evax12ghdetq-8&gt;li:before{content:"" counter(lst-ctn-kix\_evax12ghdetq-8,lower-roman) ". "}.lst-kix\_2fs6d4epazv0-0&gt;li:before{content:"\\0025cf "}.lst-kix\_8nyroabd25ur-6&gt;li:before{content:"\\0025cf "}.lst-kix\_8nyroabd25ur-4&gt;li:before{content:"\\0025cb "}.lst-kix\_8nyroabd25ur-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_evax12ghdetq-1&gt;li{counter-increment:lst-ctn-kix\_evax12ghdetq-1}.lst-kix\_2fs6d4epazv0-3&gt;li:before{content:"\\0025cf "}.lst-kix\_8nyroabd25ur-3&gt;li:before{content:"\\0025cf "}.lst-kix\_8nyroabd25ur-7&gt;li:before{content:"\\0025cb "}.lst-kix\_k9z0wtrlykrk-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_2fs6d4epazv0-2&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_hz7e6qe4lbhh-8{list-style-type:none}.lst-kix\_k9z0wtrlykrk-1&gt;li:before{content:"\\0025cb "}ol.lst-kix\_hz7e6qe4lbhh-7{list-style-type:none}.lst-kix\_2fs6d4epazv0-1&gt;li:before{content:"\\0025cb "}.lst-kix\_8nyroabd25ur-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_k9z0wtrlykrk-0&gt;li:before{content:"\\0025cf "}ol.lst-kix\_hz7e6qe4lbhh-4{list-style-type:none}ol.lst-kix\_hz7e6qe4lbhh-3{list-style-type:none}.lst-kix\_nhxf08ng0zjh-6&gt;li:before{content:"\\0025cf "}.lst-kix\_nhxf08ng0zjh-7&gt;li:before{content:"\\0025cb "}ol.lst-kix\_hz7e6qe4lbhh-6{list-style-type:none}ol.lst-kix\_hz7e6qe4lbhh-5{list-style-type:none}ol.lst-kix\_hz7e6qe4lbhh-0{list-style-type:none}.lst-kix\_8nyroabd25ur-0&gt;li:before{content:"\\0025cf "}.lst-kix\_nhxf08ng0zjh-4&gt;li:before{content:"\\0025cb "}.lst-kix\_nhxf08ng0zjh-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_nhxf08ng0zjh-8&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_hz7e6qe4lbhh-2{list-style-type:none}ol.lst-kix\_hz7e6qe4lbhh-1{list-style-type:none}.lst-kix\_8nyroabd25ur-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_8nyroabd25ur-1&gt;li:before{content:"\\0025cb "}.lst-kix\_evax12ghdetq-7&gt;li:before{content:"" counter(lst-ctn-kix\_evax12ghdetq-7,lower-latin) ". "}.lst-kix\_evax12ghdetq-6&gt;li:before{content:"" counter(lst-ctn-kix\_evax12ghdetq-6,decimal) ". "}.lst-kix\_evax12ghdetq-5&gt;li:before{content:"" counter(lst-ctn-kix\_evax12ghdetq-5,lower-roman) ". "}.lst-kix\_evax12ghdetq-4&gt;li:before{content:"" counter(lst-ctn-kix\_evax12ghdetq-4,lower-latin) ". "}.lst-kix\_lyr3b2ph9j2j-1&gt;li:before{content:"\\0025cb "}.lst-kix\_e1ilhl9h2irp-3&gt;li:before{content:"\\0025cf "}.lst-kix\_lyr3b2ph9j2j-3&gt;li:before{content:"\\0025cf "}.lst-kix\_e1ilhl9h2irp-1&gt;li:before{content:"\\0025cb "}.lst-kix\_szafnxrkjncx-7&gt;li:before{content:"\\0025cb "}.lst-kix\_e1ilhl9h2irp-7&gt;li:before{content:"\\0025cb "}.lst-kix\_m3s6obof6xsw-3&gt;li:before{content:"\\0025cf "}.lst-kix\_szafnxrkjncx-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_e1ilhl9h2irp-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_m3s6obof6xsw-1&gt;li:before{content:"\\0025cb "}.lst-kix\_8z53ty2gz3mr-6&gt;li:before{content:"\\0025cf "}.lst-kix\_szafnxrkjncx-1&gt;li:before{content:"\\0025cb "}.lst-kix\_8z53ty2gz3mr-4&gt;li:before{content:"\\0025cb "}.lst-kix\_8z53ty2gz3mr-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_szafnxrkjncx-3&gt;li:before{content:"\\0025cf "}.lst-kix\_8z53ty2gz3mr-2&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_hz7e6qe4lbhh-6.start{counter-reset:lst-ctn-kix\_hz7e6qe4lbhh-6 0}.lst-kix\_uhcf91an71wf-1&gt;li:before{content:"\\0025cb "}.lst-kix\_m3s6obof6xsw-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_lyr3b2ph9j2j-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_ib9j2ls61eto-3&gt;li:before{content:"\\0025cf "}.lst-kix\_m3s6obof6xsw-7&gt;li:before{content:"\\0025cb "}.lst-kix\_lyr3b2ph9j2j-7&gt;li:before{content:"\\0025cb "}.lst-kix\_ib9j2ls61eto-1&gt;li:before{content:"\\0025cb "}.lst-kix\_k9z0wtrlykrk-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_cfvoc5d5ri28-6&gt;li:before{content:"\\0025cf "}.lst-kix\_ib9j2ls61eto-7&gt;li:before{content:"\\0025cb "}ol.lst-kix\_tzx8mz8hspc7-1.start{counter-reset:lst-ctn-kix\_tzx8mz8hspc7-1 0}.lst-kix\_o316414q4358-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_o316414q4358-6&gt;li:before{content:"\\0025cf "}.lst-kix\_qxqu9g2j7hjr-1&gt;li:before{content:"\\0025cb "}.lst-kix\_cfvoc5d5ri28-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_cfvoc5d5ri28-0&gt;li:before{content:"\\0025cf "}.lst-kix\_cfvoc5d5ri28-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_ib9j2ls61eto-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_o316414q4358-4&gt;li:before{content:"\\0025cb "}.lst-kix\_qxqu9g2j7hjr-7&gt;li:before{content:"\\0025cb "}.lst-kix\_d0j69qeqtikc-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_8z53ty2gz3mr-0&gt;li:before{content:"\\0025cf "}.lst-kix\_uhcf91an71wf-3&gt;li:before{content:"\\0025cf "}.lst-kix\_uhcf91an71wf-7&gt;li:before{content:"\\0025cb "}.lst-kix\_vez8xevq8akx-3&gt;li:before{content:"\\0025cf "}.lst-kix\_d0j69qeqtikc-1&gt;li:before{content:"\\0025cb "}.lst-kix\_d0j69qeqtikc-3&gt;li:before{content:"\\0025cf "}.lst-kix\_cfvoc5d5ri28-4&gt;li:before{content:"\\0025cb "}.lst-kix\_vez8xevq8akx-1&gt;li:before{content:"\\0025cb "}.lst-kix\_boxwjc60mpgf-7&gt;li:before{content:"\\0025cb "}.lst-kix\_uhcf91an71wf-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_o316414q4358-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_ihu4chqckap9-7{list-style-type:none}ul.lst-kix\_ihu4chqckap9-8{list-style-type:none}.lst-kix\_boxwjc60mpgf-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_ihu4chqckap9-5{list-style-type:none}ul.lst-kix\_ihu4chqckap9-6{list-style-type:none}ul.lst-kix\_ihu4chqckap9-0{list-style-type:none}.lst-kix\_boxwjc60mpgf-5&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_evax12ghdetq-2.start{counter-reset:lst-ctn-kix\_evax12ghdetq-2 0}ul.lst-kix\_ihu4chqckap9-3{list-style-type:none}ul.lst-kix\_ihu4chqckap9-4{list-style-type:none}.lst-kix\_vez8xevq8akx-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_boxwjc60mpgf-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_ihu4chqckap9-1{list-style-type:none}ul.lst-kix\_ihu4chqckap9-2{list-style-type:none}.lst-kix\_hz7e6qe4lbhh-7&gt;li{counter-increment:lst-ctn-kix\_hz7e6qe4lbhh-7}ul.lst-kix\_a1n97pss2xec-0{list-style-type:none}.lst-kix\_vez8xevq8akx-7&gt;li:before{content:"\\0025cb "}.lst-kix\_d0j69qeqtikc-7&gt;li:before{content:"\\0025cb "}.lst-kix\_qxqu9g2j7hjr-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_a1n97pss2xec-8{list-style-type:none}ul.lst-kix\_a1n97pss2xec-7{list-style-type:none}ul.lst-kix\_a1n97pss2xec-6{list-style-type:none}ul.lst-kix\_a1n97pss2xec-5{list-style-type:none}ul.lst-kix\_a1n97pss2xec-4{list-style-type:none}ul.lst-kix\_a1n97pss2xec-3{list-style-type:none}ul.lst-kix\_a1n97pss2xec-2{list-style-type:none}.lst-kix\_o316414q4358-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_a1n97pss2xec-1{list-style-type:none}.lst-kix\_qxqu9g2j7hjr-3&gt;li:before{content:"\\0025cf "}.lst-kix\_hz7e6qe4lbhh-8&gt;li:before{content:"" counter(lst-ctn-kix\_hz7e6qe4lbhh-8,lower-roman) ". "}.lst-kix\_hz7e6qe4lbhh-4&gt;li:before{content:"" counter(lst-ctn-kix\_hz7e6qe4lbhh-4,lower-latin) ". "}.lst-kix\_3ipl4jxrgfvg-1&gt;li:before{content:"\\0025cb "}.lst-kix\_hz7e6qe4lbhh-5&gt;li:before{content:"" counter(lst-ctn-kix\_hz7e6qe4lbhh-5,lower-roman) ". "}.lst-kix\_3ipl4jxrgfvg-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_ywahawqva4s1-4{list-style-type:none}ul.lst-kix\_ywahawqva4s1-5{list-style-type:none}ul.lst-kix\_ywahawqva4s1-6{list-style-type:none}ul.lst-kix\_ywahawqva4s1-7{list-style-type:none}ul.lst-kix\_ywahawqva4s1-0{list-style-type:none}.lst-kix\_3ipl4jxrgfvg-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_ywahawqva4s1-1{list-style-type:none}.lst-kix\_vez8xevq8akx-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_ywahawqva4s1-2{list-style-type:none}ul.lst-kix\_ywahawqva4s1-3{list-style-type:none}ul.lst-kix\_oqq2ui921j1-2{list-style-type:none}ul.lst-kix\_oqq2ui921j1-1{list-style-type:none}.lst-kix\_hz7e6qe4lbhh-0&gt;li{counter-increment:lst-ctn-kix\_hz7e6qe4lbhh-0}ul.lst-kix\_oqq2ui921j1-4{list-style-type:none}.lst-kix\_hz7e6qe4lbhh-0&gt;li:before{content:"" counter(lst-ctn-kix\_hz7e6qe4lbhh-0,decimal) ". "}ul.lst-kix\_oqq2ui921j1-3{list-style-type:none}ul.lst-kix\_oqq2ui921j1-6{list-style-type:none}ul.lst-kix\_ywahawqva4s1-8{list-style-type:none}.lst-kix\_hz7e6qe4lbhh-1&gt;li:before{content:"" counter(lst-ctn-kix\_hz7e6qe4lbhh-1,lower-latin) ". "}ul.lst-kix\_oqq2ui921j1-5{list-style-type:none}ul.lst-kix\_oqq2ui921j1-8{list-style-type:none}.lst-kix\_3ipl4jxrgfvg-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_oqq2ui921j1-7{list-style-type:none}ul.lst-kix\_oqq2ui921j1-0{list-style-type:none}ul.lst-kix\_h94ugxasirk3-0{list-style-type:none}.lst-kix\_evax12ghdetq-0&gt;li{counter-increment:lst-ctn-kix\_evax12ghdetq-0}ul.lst-kix\_h94ugxasirk3-2{list-style-type:none}ul.lst-kix\_h94ugxasirk3-1{list-style-type:none}ul.lst-kix\_h94ugxasirk3-8{list-style-type:none}ul.lst-kix\_h94ugxasirk3-7{list-style-type:none}.lst-kix\_poxumw20mduo-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_h94ugxasirk3-4{list-style-type:none}ul.lst-kix\_h94ugxasirk3-3{list-style-type:none}ul.lst-kix\_h94ugxasirk3-6{list-style-type:none}ul.lst-kix\_h94ugxasirk3-5{list-style-type:none}ul.lst-kix\_w0yl8nmrwp6o-8{list-style-type:none}.lst-kix\_poxumw20mduo-7&gt;li:before{content:"\\0025cb "}.lst-kix\_poxumw20mduo-6&gt;li:before{content:"\\0025cf "}.lst-kix\_poxumw20mduo-3&gt;li:before{content:"\\0025cf "}.lst-kix\_h94ugxasirk3-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_67axahw2bw4y-5{list-style-type:none}ul.lst-kix\_67axahw2bw4y-6{list-style-type:none}.lst-kix\_h94ugxasirk3-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_67axahw2bw4y-7{list-style-type:none}ul.lst-kix\_67axahw2bw4y-8{list-style-type:none}.lst-kix\_3q4kfur98hw3-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_h94ugxasirk3-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_evax12ghdetq-7&gt;li{counter-increment:lst-ctn-kix\_evax12ghdetq-7}.lst-kix\_h94ugxasirk3-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_67axahw2bw4y-0{list-style-type:none}ul.lst-kix\_67axahw2bw4y-1{list-style-type:none}ul.lst-kix\_67axahw2bw4y-2{list-style-type:none}ul.lst-kix\_67axahw2bw4y-3{list-style-type:none}ul.lst-kix\_67axahw2bw4y-4{list-style-type:none}.lst-kix\_3q4kfur98hw3-7&gt;li:before{content:"\\0025cb "}ol.lst-kix\_hz7e6qe4lbhh-7.start{counter-reset:lst-ctn-kix\_hz7e6qe4lbhh-7 0}.lst-kix\_3q4kfur98hw3-6&gt;li:before{content:"\\0025cf "}.lst-kix\_3q4kfur98hw3-3&gt;li:before{content:"\\0025cf "}.lst-kix\_tzx8mz8hspc7-0&gt;li{counter-increment:lst-ctn-kix\_tzx8mz8hspc7-0}.lst-kix\_ihu4chqckap9-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_e1ilhl9h2irp-0&gt;li:before{content:"\\0025cf "}.lst-kix\_e1ilhl9h2irp-4&gt;li:before{content:"\\0025cb "}.lst-kix\_lyr3b2ph9j2j-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_l3f4cvceui9t-8{list-style-type:none}.lst-kix\_cg2acydq40lf-0&gt;li:before{content:"\\0025cf "}.lst-kix\_cg2acydq40lf-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_m3s6obof6xsw-4&gt;li:before{content:"\\0025cb "}.lst-kix\_e1ilhl9h2irp-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_evax12ghdetq-2&gt;li{counter-increment:lst-ctn-kix\_evax12ghdetq-2}.lst-kix\_szafnxrkjncx-6&gt;li:before{content:"\\0025cf "}.lst-kix\_m3s6obof6xsw-0&gt;li:before{content:"\\0025cf "}.lst-kix\_lyr3b2ph9j2j-0&gt;li:before{content:"\\0025cf "}.lst-kix\_uqx5pvtk1sx7-2&gt;li:before{content:"\\0025a0 "}ol.lst-kix\_tzx8mz8hspc7-7.start{counter-reset:lst-ctn-kix\_tzx8mz8hspc7-7 0}.lst-kix\_szafnxrkjncx-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_w0yl8nmrwp6o-0{list-style-type:none}.lst-kix\_uhcf91an71wf-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_w0yl8nmrwp6o-1{list-style-type:none}ul.lst-kix\_w0yl8nmrwp6o-2{list-style-type:none}ul.lst-kix\_w0yl8nmrwp6o-3{list-style-type:none}ul.lst-kix\_w0yl8nmrwp6o-4{list-style-type:none}ul.lst-kix\_w0yl8nmrwp6o-5{list-style-type:none}.lst-kix\_8z53ty2gz3mr-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_w0yl8nmrwp6o-6{list-style-type:none}ul.lst-kix\_w0yl8nmrwp6o-7{list-style-type:none}.lst-kix\_y48cfiwpd1yk-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_ib9j2ls61eto-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_y48cfiwpd1yk-6&gt;li:before{content:"\\0025cf "}.lst-kix\_m3s6obof6xsw-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_lyr3b2ph9j2j-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_8z53ty2gz3mr-7&gt;li:before{content:"\\0025cb "}.lst-kix\_o316414q4358-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_5m2k735u0wc3-0{list-style-type:none}.lst-kix\_sz2een1y35py-1&gt;li:before{content:"\\0025cb "}.lst-kix\_qxqu9g2j7hjr-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_5m2k735u0wc3-2{list-style-type:none}.lst-kix\_ib9j2ls61eto-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_5m2k735u0wc3-1{list-style-type:none}.lst-kix\_cfvoc5d5ri28-3&gt;li:before{content:"\\0025cf "}.lst-kix\_cfvoc5d5ri28-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_5m2k735u0wc3-4{list-style-type:none}ul.lst-kix\_5m2k735u0wc3-3{list-style-type:none}ul.lst-kix\_5m2k735u0wc3-6{list-style-type:none}ul.lst-kix\_5m2k735u0wc3-5{list-style-type:none}ul.lst-kix\_5m2k735u0wc3-8{list-style-type:none}ul.lst-kix\_5m2k735u0wc3-7{list-style-type:none}.lst-kix\_qxqu9g2j7hjr-6&gt;li:before{content:"\\0025cf "}.lst-kix\_8frcs3cb9mlx-4&gt;li:before{content:"\\0025cb "}.lst-kix\_d0j69qeqtikc-6&gt;li:before{content:"\\0025cf "}.lst-kix\_uhcf91an71wf-6&gt;li:before{content:"\\0025cf "}.lst-kix\_boxwjc60mpgf-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_vez8xevq8akx-4&gt;li:before{content:"\\0025cb "}.lst-kix\_o316414q4358-1&gt;li:before{content:"\\0025cb "}.lst-kix\_sz2een1y35py-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_8frcs3cb9mlx-0&gt;li:before{content:"\\0025cf "}.lst-kix\_d0j69qeqtikc-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_m6xa40k4vexm-4&gt;li:before{content:"\\0025cb "}.lst-kix\_boxwjc60mpgf-0&gt;li:before{content:"\\0025cf "}.lst-kix\_m6xa40k4vexm-0&gt;li:before{content:"\\0025cf "}.lst-kix\_m6xa40k4vexm-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_boxwjc60mpgf-4&gt;li:before{content:"\\0025cb "}.lst-kix\_uqx5pvtk1sx7-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_l3f4cvceui9t-5{list-style-type:none}ul.lst-kix\_l3f4cvceui9t-4{list-style-type:none}ul.lst-kix\_l3f4cvceui9t-7{list-style-type:none}ul.lst-kix\_l3f4cvceui9t-6{list-style-type:none}ul.lst-kix\_l3f4cvceui9t-1{list-style-type:none}ul.lst-kix\_l3f4cvceui9t-0{list-style-type:none}.lst-kix\_vez8xevq8akx-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_l3f4cvceui9t-3{list-style-type:none}ul.lst-kix\_l3f4cvceui9t-2{list-style-type:none}ol.lst-kix\_evax12ghdetq-8.start{counter-reset:lst-ctn-kix\_evax12ghdetq-8 0}.lst-kix\_cg2acydq40lf-4&gt;li:before{content:"\\0025cb "}.lst-kix\_pxgusehopho8-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_pxgusehopho8-4&gt;li:before{content:"\\0025cb "}.lst-kix\_pxgusehopho8-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_u906582iea27-7&gt;li:before{content:"\\0025cb "}ul.lst-kix\_8frcs3cb9mlx-2{list-style-type:none}ul.lst-kix\_8frcs3cb9mlx-1{list-style-type:none}ul.lst-kix\_8frcs3cb9mlx-0{list-style-type:none}.lst-kix\_u906582iea27-6&gt;li:before{content:"\\0025cf "}.lst-kix\_pxgusehopho8-7&gt;li:before{content:"\\0025cb "}.lst-kix\_u906582iea27-1&gt;li:before{content:"\\0025cb "}.lst-kix\_u906582iea27-4&gt;li:before{content:"\\0025cb "}.lst-kix\_eyq40i4uxhci-4&gt;li:before{content:"\\0025cb "}.lst-kix\_eyq40i4uxhci-6&gt;li:before{content:"\\0025cf "}.lst-kix\_eyq40i4uxhci-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_8frcs3cb9mlx-6{list-style-type:none}.lst-kix\_8frcs3cb9mlx-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_8frcs3cb9mlx-5{list-style-type:none}ul.lst-kix\_8frcs3cb9mlx-4{list-style-type:none}ul.lst-kix\_8frcs3cb9mlx-3{list-style-type:none}ul.lst-kix\_8frcs3cb9mlx-8{list-style-type:none}.lst-kix\_eyq40i4uxhci-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_8frcs3cb9mlx-7{list-style-type:none}.lst-kix\_8frcs3cb9mlx-7&gt;li:before{content:"\\0025cb "}.lst-kix\_8frcs3cb9mlx-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_ewlea9l5v2mb-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_e1ilhl9h2irp-6{list-style-type:none}ul.lst-kix\_e1ilhl9h2irp-7{list-style-type:none}ul.lst-kix\_e1ilhl9h2irp-8{list-style-type:none}ul.lst-kix\_e1ilhl9h2irp-2{list-style-type:none}ul.lst-kix\_e1ilhl9h2irp-3{list-style-type:none}ul.lst-kix\_e1ilhl9h2irp-4{list-style-type:none}ul.lst-kix\_e1ilhl9h2irp-5{list-style-type:none}ul.lst-kix\_e1ilhl9h2irp-0{list-style-type:none}ul.lst-kix\_e1ilhl9h2irp-1{list-style-type:none}.lst-kix\_ihu4chqckap9-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_eyq40i4uxhci-1{list-style-type:none}ul.lst-kix\_anjmmosejwns-0{list-style-type:none}ul.lst-kix\_eyq40i4uxhci-0{list-style-type:none}ul.lst-kix\_anjmmosejwns-2{list-style-type:none}.lst-kix\_anjmmosejwns-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_anjmmosejwns-1{list-style-type:none}.lst-kix\_cg2acydq40lf-3&gt;li:before{content:"\\0025cf "}.lst-kix\_hz7e6qe4lbhh-8&gt;li{counter-increment:lst-ctn-kix\_hz7e6qe4lbhh-8}.lst-kix\_ihu4chqckap9-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_cg2acydq40lf-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_anjmmosejwns-8{list-style-type:none}ul.lst-kix\_eyq40i4uxhci-8{list-style-type:none}ul.lst-kix\_anjmmosejwns-7{list-style-type:none}ul.lst-kix\_eyq40i4uxhci-7{list-style-type:none}ul.lst-kix\_eyq40i4uxhci-6{list-style-type:none}ul.lst-kix\_cg2acydq40lf-7{list-style-type:none}ul.lst-kix\_eyq40i4uxhci-5{list-style-type:none}ul.lst-kix\_anjmmosejwns-4{list-style-type:none}ul.lst-kix\_cg2acydq40lf-8{list-style-type:none}ul.lst-kix\_eyq40i4uxhci-4{list-style-type:none}ul.lst-kix\_anjmmosejwns-3{list-style-type:none}ul.lst-kix\_cg2acydq40lf-5{list-style-type:none}ul.lst-kix\_eyq40i4uxhci-3{list-style-type:none}ul.lst-kix\_anjmmosejwns-6{list-style-type:none}.lst-kix\_ihu4chqckap9-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_cg2acydq40lf-6{list-style-type:none}ul.lst-kix\_eyq40i4uxhci-2{list-style-type:none}ul.lst-kix\_anjmmosejwns-5{list-style-type:none}ul.lst-kix\_cg2acydq40lf-3{list-style-type:none}ul.lst-kix\_cg2acydq40lf-4{list-style-type:none}ul.lst-kix\_cg2acydq40lf-1{list-style-type:none}.lst-kix\_uqx5pvtk1sx7-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_cg2acydq40lf-2{list-style-type:none}.lst-kix\_anjmmosejwns-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_uqx5pvtk1sx7-5&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_cg2acydq40lf-0{list-style-type:none}.lst-kix\_anjmmosejwns-6&gt;li:before{content:"\\0025cf "}.lst-kix\_wkdyljpeit7k-6&gt;li:before{content:"\\0025cf "}.lst-kix\_y48cfiwpd1yk-7&gt;li:before{content:"\\0025cb "}.lst-kix\_wkdyljpeit7k-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_wkdyljpeit7k-0&gt;li:before{content:"\\0025cf "}.lst-kix\_ewlea9l5v2mb-7&gt;li:before{content:"\\0025cb "}.lst-kix\_l3f4cvceui9t-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_v4y75fpnt0mm-1{list-style-type:none}ul.lst-kix\_v4y75fpnt0mm-0{list-style-type:none}.lst-kix\_ikb4dfai24wa-3&gt;li:before{content:"\\0025cf "}.lst-kix\_evax12ghdetq-6&gt;li{counter-increment:lst-ctn-kix\_evax12ghdetq-6}.lst-kix\_67axahw2bw4y-4&gt;li:before{content:"\\0025cb "}.lst-kix\_sz2een1y35py-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_v4y75fpnt0mm-7{list-style-type:none}.lst-kix\_ikb4dfai24wa-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_v4y75fpnt0mm-6{list-style-type:none}ul.lst-kix\_v4y75fpnt0mm-8{list-style-type:none}ul.lst-kix\_v4y75fpnt0mm-3{list-style-type:none}.lst-kix\_y48cfiwpd1yk-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_v4y75fpnt0mm-2{list-style-type:none}ul.lst-kix\_v4y75fpnt0mm-5{list-style-type:none}ul.lst-kix\_v4y75fpnt0mm-4{list-style-type:none}.lst-kix\_ahbvbvxjsk00-6&gt;li:before{content:"\\0025cf "}.lst-kix\_ahbvbvxjsk00-4&gt;li:before{content:"\\0025cb "}.lst-kix\_sz2een1y35py-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_l3f4cvceui9t-6&gt;li:before{content:"\\0025cf "}.lst-kix\_sz2een1y35py-6&gt;li:before{content:"\\0025cf "}.lst-kix\_67axahw2bw4y-6&gt;li:before{content:"\\0025cf "}.lst-kix\_m6xa40k4vexm-3&gt;li:before{content:"\\0025cf "}.lst-kix\_m6xa40k4vexm-1&gt;li:before{content:"\\0025cb "}.lst-kix\_uy6mucuvaggy-7&gt;li:before{content:"\\0025cb "}.lst-kix\_uy6mucuvaggy-1&gt;li:before{content:"\\0025cb "}.lst-kix\_hz7e6qe4lbhh-1&gt;li{counter-increment:lst-ctn-kix\_hz7e6qe4lbhh-1}ul.lst-kix\_cmtzg17lkw6e-7{list-style-type:none}ul.lst-kix\_cmtzg17lkw6e-8{list-style-type:none}.lst-kix\_t9f7ru8r1rgs-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_ahbvbvxjsk00-1{list-style-type:none}ul.lst-kix\_ahbvbvxjsk00-0{list-style-type:none}ul.lst-kix\_ahbvbvxjsk00-3{list-style-type:none}ul.lst-kix\_ahbvbvxjsk00-2{list-style-type:none}ul.lst-kix\_ahbvbvxjsk00-5{list-style-type:none}ul.lst-kix\_ahbvbvxjsk00-4{list-style-type:none}ul.lst-kix\_ahbvbvxjsk00-7{list-style-type:none}ul.lst-kix\_ahbvbvxjsk00-6{list-style-type:none}.lst-kix\_hz7e6qe4lbhh-3&gt;li:before{content:"" counter(lst-ctn-kix\_hz7e6qe4lbhh-3,decimal) ". "}ul.lst-kix\_ouu0f4ii1rn1-6{list-style-type:none}ul.lst-kix\_ouu0f4ii1rn1-7{list-style-type:none}.lst-kix\_ywahawqva4s1-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_3q4kfur98hw3-0{list-style-type:none}ul.lst-kix\_ouu0f4ii1rn1-8{list-style-type:none}ul.lst-kix\_3q4kfur98hw3-1{list-style-type:none}.lst-kix\_ywahawqva4s1-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_3q4kfur98hw3-6{list-style-type:none}ul.lst-kix\_cmtzg17lkw6e-0{list-style-type:none}ul.lst-kix\_3q4kfur98hw3-7{list-style-type:none}ul.lst-kix\_cmtzg17lkw6e-1{list-style-type:none}.lst-kix\_hz7e6qe4lbhh-6&gt;li:before{content:"" counter(lst-ctn-kix\_hz7e6qe4lbhh-6,decimal) ". "}ul.lst-kix\_3q4kfur98hw3-8{list-style-type:none}ul.lst-kix\_ouu0f4ii1rn1-0{list-style-type:none}ul.lst-kix\_cmtzg17lkw6e-2{list-style-type:none}ul.lst-kix\_ouu0f4ii1rn1-1{list-style-type:none}ul.lst-kix\_cmtzg17lkw6e-3{list-style-type:none}ul.lst-kix\_3q4kfur98hw3-2{list-style-type:none}ul.lst-kix\_ouu0f4ii1rn1-2{list-style-type:none}ul.lst-kix\_cmtzg17lkw6e-4{list-style-type:none}.lst-kix\_t9f7ru8r1rgs-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_3q4kfur98hw3-3{list-style-type:none}ul.lst-kix\_ouu0f4ii1rn1-3{list-style-type:none}ul.lst-kix\_cmtzg17lkw6e-5{list-style-type:none}ul.lst-kix\_3q4kfur98hw3-4{list-style-type:none}ul.lst-kix\_ouu0f4ii1rn1-4{list-style-type:none}ul.lst-kix\_cmtzg17lkw6e-6{list-style-type:none}ul.lst-kix\_3q4kfur98hw3-5{list-style-type:none}ul.lst-kix\_ouu0f4ii1rn1-5{list-style-type:none}.lst-kix\_3ipl4jxrgfvg-7&gt;li:before{content:"\\0025cb "}.lst-kix\_3ipl4jxrgfvg-4&gt;li:before{content:"\\0025cb "}.lst-kix\_t9f7ru8r1rgs-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_w0yl8nmrwp6o-3&gt;li:before{content:"\\0025cf "}.lst-kix\_xhpr2ex4dnkl-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_sz2een1y35py-2{list-style-type:none}ul.lst-kix\_sz2een1y35py-1{list-style-type:none}ul.lst-kix\_sz2een1y35py-0{list-style-type:none}ul.lst-kix\_nhxf08ng0zjh-8{list-style-type:none}ul.lst-kix\_sz2een1y35py-6{list-style-type:none}ul.lst-kix\_nhxf08ng0zjh-6{list-style-type:none}ul.lst-kix\_sz2een1y35py-5{list-style-type:none}ul.lst-kix\_nhxf08ng0zjh-7{list-style-type:none}ul.lst-kix\_sz2een1y35py-4{list-style-type:none}ul.lst-kix\_nhxf08ng0zjh-4{list-style-type:none}ul.lst-kix\_sz2een1y35py-3{list-style-type:none}ul.lst-kix\_nhxf08ng0zjh-5{list-style-type:none}ul.lst-kix\_nhxf08ng0zjh-2{list-style-type:none}.lst-kix\_poxumw20mduo-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_nhxf08ng0zjh-3{list-style-type:none}.lst-kix\_cmtzg17lkw6e-1&gt;li:before{content:"\\0025cb "}.lst-kix\_3q4kfur98hw3-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_sz2een1y35py-8{list-style-type:none}ul.lst-kix\_nhxf08ng0zjh-0{list-style-type:none}ul.lst-kix\_sz2een1y35py-7{list-style-type:none}ul.lst-kix\_nhxf08ng0zjh-1{list-style-type:none}.lst-kix\_3ewi2x1kv5uq-2&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_8bw4pomaqyc2-8{list-style-type:none}.lst-kix\_4ozj8cu0p377-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_w0yl8nmrwp6o-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_8bw4pomaqyc2-1{list-style-type:none}ul.lst-kix\_8bw4pomaqyc2-0{list-style-type:none}ul.lst-kix\_8bw4pomaqyc2-3{list-style-type:none}.lst-kix\_poxumw20mduo-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_8bw4pomaqyc2-2{list-style-type:none}.lst-kix\_h94ugxasirk3-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_8bw4pomaqyc2-5{list-style-type:none}.lst-kix\_a1n97pss2xec-8&gt;li:before{content:"\\0025a0 "}ul.lst-kix\_8bw4pomaqyc2-4{list-style-type:none}ul.lst-kix\_8bw4pomaqyc2-7{list-style-type:none}ul.lst-kix\_8bw4pomaqyc2-6{list-style-type:none}.lst-kix\_h94ugxasirk3-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_ywahawqva4s1-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_tzx8mz8hspc7-6&gt;li{counter-increment:lst-ctn-kix\_tzx8mz8hspc7-6}.lst-kix\_4ozj8cu0p377-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_szafnxrkjncx-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_3q4kfur98hw3-0&gt;li:before{content:"\\0025cf "}.lst-kix\_3q4kfur98hw3-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_3ewi2x1kv5uq-7&gt;li:before{content:"\\0025cb "}.lst-kix\_h94ugxasirk3-0&gt;li:before{content:"\\0025cf "}.lst-kix\_evax12ghdetq-3&gt;li{counter-increment:lst-ctn-kix\_evax12ghdetq-3}.lst-kix\_ihu4chqckap9-7&gt;li:before{content:"\\0025cb "}.lst-kix\_cg2acydq40lf-6&gt;li:before{content:"\\0025cf "}.lst-kix\_anjmmosejwns-3&gt;li:before{content:"\\0025cf "}.lst-kix\_uqx5pvtk1sx7-0&gt;li:before{content:"\\0025cf "}.lst-kix\_tzx8mz8hspc7-0&gt;li:before{content:"" counter(lst-ctn-kix\_tzx8mz8hspc7-0,lower-latin) ". "}ul.lst-kix\_olrmfo3e8daa-1{list-style-type:none}ul.lst-kix\_olrmfo3e8daa-0{list-style-type:none}.lst-kix\_sbnx2aog7wgo-6&gt;li:before{content:"\\0025cf "}.lst-kix\_e1ilhl9h2irp-6&gt;li:before{content:"\\0025cf "}.lst-kix\_olrmfo3e8daa-1&gt;li:before{content:"\\0025cb "}.lst-kix\_wkdyljpeit7k-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_olrmfo3e8daa-5{list-style-type:none}ul.lst-kix\_olrmfo3e8daa-4{list-style-type:none}ul.lst-kix\_olrmfo3e8daa-3{list-style-type:none}ul.lst-kix\_olrmfo3e8daa-2{list-style-type:none}.lst-kix\_m3s6obof6xsw-6&gt;li:before{content:"\\0025cf "}.lst-kix\_uhcf91an71wf-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_olrmfo3e8daa-8{list-style-type:none}.lst-kix\_2zf3qhky0qd4-1&gt;li:before{content:"\\0025cb "}ul.lst-kix\_olrmfo3e8daa-7{list-style-type:none}.lst-kix\_szafnxrkjncx-0&gt;li:before{content:"\\0025cf "}.lst-kix\_bu096cxa7zy2-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_olrmfo3e8daa-6{list-style-type:none}.lst-kix\_oqq2ui921j1-6&gt;li:before{content:"\\0025cf "}ul.lst-kix\_u906582iea27-0{list-style-type:none}.lst-kix\_lyr3b2ph9j2j-6&gt;li:before{content:"\\0025cf "}.lst-kix\_ewlea9l5v2mb-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_u906582iea27-1{list-style-type:none}.lst-kix\_ouu0f4ii1rn1-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_u906582iea27-2{list-style-type:none}ul.lst-kix\_u906582iea27-3{list-style-type:none}ul.lst-kix\_u906582iea27-8{list-style-type:none}.lst-kix\_a1n97pss2xec-0&gt;li:before{content:"\\0025cf "}ul.lst-kix\_u906582iea27-4{list-style-type:none}.lst-kix\_y48cfiwpd1yk-4&gt;li:before{content:"\\0025cb "}ul.lst-kix\_u906582iea27-5{list-style-type:none}ul.lst-kix\_u906582iea27-6{list-style-type:none}ul.lst-kix\_u906582iea27-7{list-style-type:none}.lst-kix\_67axahw2bw4y-1&gt;li:before{content:"\\0025cb "}.lst-kix\_ikb4dfai24wa-6&gt;li:before{content:"\\0025cf "}.lst-kix\_sz2een1y35py-3&gt;li:before{content:"\\0025cf "}.lst-kix\_ahbvbvxjsk00-1&gt;li:before{content:"\\0025cb "}.lst-kix\_xhpr2ex4dnkl-6&gt;li:before{content:"\\0025cf "}.lst-kix\_ib9j2ls61eto-4&gt;li:before{content:"\\0025cb "}.lst-kix\_8frcs3cb9mlx-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_l3f4cvceui9t-1&gt;li:before{content:"\\0025cb "}.lst-kix\_uhcf91an71wf-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_o316414q4358-3&gt;li:before{content:"\\0025cf "}.lst-kix\_5m2k735u0wc3-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_boxwjc60mpgf-6&gt;li:before{content:"\\0025cf "}.lst-kix\_8z53ty2gz3mr-1&gt;li:before{content:"\\0025cb "}.lst-kix\_d0j69qeqtikc-4&gt;li:before{content:"\\0025cb "}.lst-kix\_vez8xevq8akx-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_cfvoc5d5ri28-5&gt;li:before{content:"\\0025a0 "}.lst-kix\_m6xa40k4vexm-6&gt;li:before{content:"\\0025cf "}.lst-kix\_uqx5pvtk1sx7-8&gt;li:before{content:"\\0025a0 "}.lst-kix\_pf6gjug0y9iv-2&gt;li:before{content:"\\0025a0 "}.lst-kix\_tzx8mz8hspc7-8&gt;li:before{content:"" counter(lst-ctn-kix\_tzx8mz8hspc7-8,lower-roman) ". "}.lst-kix\_hz7e6qe4lbhh-4&gt;li{counter-increment:lst-ctn-kix\_hz7e6qe4lbhh-4}ul.lst-kix\_3ipl4jxrgfvg-7{list-style-type:none}ul.lst-kix\_3ipl4jxrgfvg-8{list-style-type:none}ul.lst-kix\_3ipl4jxrgfvg-3{list-style-type:none}ul.lst-kix\_3ipl4jxrgfvg-4{list-style-type:none}ul.lst-kix\_3ipl4jxrgfvg-5{list-style-type:none}ul.lst-kix\_3ipl4jxrgfvg-6{list-style-type:none}.lst-kix\_uy6mucuvaggy-4&gt;li:before{content:"\\0025cb "}.lst-kix\_qxqu9g2j7hjr-4&gt;li:before{content:"\\0025cb "}.lst-kix\_8bw4pomaqyc2-3&gt;li:before{content:"\\0025cf "}ul.lst-kix\_3ipl4jxrgfvg-0{list-style-type:none}ul.lst-kix\_3ipl4jxrgfvg-1{list-style-type:none}ul.lst-kix\_3ipl4jxrgfvg-2{list-style-type:none}ol{margin:0;padding:0}table td,table th{padding:0}.c32{border-right-style:solid;padding:5pt 5pt 5pt 5pt;border-bottom-color:#000000;border-top-width:0pt;border-right-width:0pt;border-left-color:#000000;vertical-align:top;border-right-color:#000000;border-left-width:0pt;border-top-style:solid;border-left-style:solid;border-bottom-width:0pt;width:256pt;border-top-color:#000000;border-bottom-style:solid}.c24{border-right-style:solid;padding:5pt 5pt 5pt 5pt;border-bottom-color:#000000;border-top-width:0pt;border-right-width:0pt;border-left-color:#000000;vertical-align:top;border-right-color:#000000;border-left-width:0pt;border-top-style:solid;border-left-style:solid;border-bottom-width:0pt;width:209.5pt;border-top-color:#000000;border-bottom-style:solid}.c7{background-color:#ffffff;margin-left:-7pt;padding-top:0pt;padding-bottom:0pt;line-height:1.15;orphans:2;widows:2;text-align:left;margin-right:-7pt;height:11pt}.c47{-webkit-text-decoration-skip:none;color:#ed1c24;font-weight:400;text-decoration:underline;vertical-align:baseline;text-decoration-skip-ink:none;font-size:20pt;font-family:"Arial";font-style:normal}.c10{background-color:#f7f8fa;margin-left:-7pt;padding-top:0pt;padding-bottom:8pt;line-height:1.15;orphans:2;widows:2;text-align:left;margin-right:-7pt}.c21{margin-left:29pt;padding-top:0pt;padding-left:0pt;padding-bottom:12pt;line-height:1.15;orphans:2;widows:2;text-align:left;margin-right:-7pt}.c27{margin-left:36pt;padding-top:0pt;padding-left:0pt;padding-bottom:12pt;line-height:1.15;orphans:2;widows:2;text-align:left}.c3{background-color:#ffffff;padding-top:0pt;padding-bottom:12pt;line-height:1.15;orphans:2;widows:2;text-align:left}.c6{background-color:#ffffff;padding-top:0pt;padding-bottom:0pt;line-height:1.15;orphans:2;widows:2;text-align:center}.c44{padding-top:20pt;padding-bottom:6pt;line-height:1.15;page-break-after:avoid;orphans:2;widows:2;text-align:left}.c1{color:#646c9a;font-weight:400;text-decoration:none;vertical-align:baseline;font-size:10pt;font-family:"Poppins";font-style:normal}.c0{color:#000000;font-weight:400;text-decoration:none;vertical-align:baseline;font-size:11pt;font-family:"Arial";font-style:normal}.c9{background-color:#ffffff;padding-top:0pt;padding-bottom:4pt;line-height:1.2;orphans:2;widows:2;text-align:left}.c35{padding-top:0pt;padding-bottom:8pt;line-height:1.15;orphans:2;widows:2;text-align:left}.c36{padding-top:0pt;padding-bottom:6pt;line-height:1.2;orphans:2;widows:2;text-align:left}.c13{padding-top:0pt;padding-bottom:0pt;line-height:1.15;orphans:2;widows:2;text-align:left}.c46{padding-top:0pt;padding-bottom:0pt;line-height:1.2;orphans:2;widows:2;text-align:left}.c31{padding-top:0pt;padding-bottom:4pt;line-height:1.15;orphans:2;widows:2;text-align:left}.c48{-webkit-text-decoration-skip:none;text-decoration:underline;vertical-align:baseline;text-decoration-skip-ink:none;font-style:normal}.c15{background-color:#ed1c24;color:#ffffff;font-weight:400;font-size:10pt;font-family:"Poppins"}.c16{font-size:10pt;font-family:"Poppins";color:#ff0000;font-weight:700}.c58{font-size:10pt;font-family:"Poppins";color:#c00000;font-weight:700}.c34{font-size:10pt;font-family:"Poppins";color:#74788d;font-weight:400}.c11{font-size:10pt;font-family:"Poppins";color:#0000ff;font-weight:400}.c2{font-size:10pt;font-family:"Poppins";color:#646c9a;font-weight:400}.c41{font-size:10pt;font-family:"Poppins";color:#0070c0;font-weight:400}.c57{font-size:10pt;font-family:"Poppins";color:#00b0f0;font-weight:700}.c30{font-size:10pt;font-family:"Poppins";color:#ed1c24;font-weight:400}.c26{font-size:10pt;font-family:"Poppins";color:#0070c0;font-weight:700}.c17{font-size:12pt;font-family:"Poppins";color:#646c9a;font-weight:400}.c62{color:#000000;font-weight:700;font-size:10pt;font-family:"Poppins"}.c59{color:#646c9a;font-weight:400;font-size:16pt;font-family:"Poppins"}.c61{font-size:7.5pt;font-family:"Poppins";color:#646c9a;font-weight:400}.c23{font-size:10pt;font-family:"Poppins";color:#ff0000;font-weight:400}.c40{color:#000000;font-weight:400;font-size:20pt;font-family:"Arial"}.c56{color:#646c9a;font-weight:400;font-size:10pt;font-family:"Verdana"}.c14{color:#646c9a;font-weight:400;font-size:22pt;font-family:"Poppins"}.c50{color:#595d6e;font-weight:400;font-size:20pt;font-family:"Arial"}.c37{font-size:23pt;font-family:"Poppins";color:#646c9a;font-weight:400}.c4{font-size:10pt;font-family:"Poppins";color:#646c9a;font-weight:700}.c54{border-spacing:0;border-collapse:collapse;margin-right:auto}.c42{color:#000000;font-weight:400;font-size:10pt;font-family:"Poppins"}.c33{font-size:10pt;font-family:"Poppins";color:#0000ff;font-weight:700}.c51{color:#ff0000;font-weight:700;font-size:12pt;font-family:"Poppins"}.c60{color:#646c9a;font-weight:700;font-size:16pt;font-family:"Poppins"}.c49{-webkit-text-decoration-skip:none;text-decoration:underline;text-decoration-skip-ink:none}.c5{text-decoration:none;vertical-align:baseline;font-style:normal}.c52{font-size:10pt;font-family:"Poppins";font-weight:400}.c18{background-color:#ffffff;margin-left:-7pt;margin-right:-7pt}.c38{text-decoration:none;vertical-align:baseline}.c55{background-color:#ed1c24;color:#ffffff}.c19{background-color:#ffffff;height:11pt}.c12{color:inherit;text-decoration:inherit}.c8{padding:0;margin:0}.c20{margin-left:-7pt;margin-right:-7pt}.c29{background-color:#f7f8fa}.c45{height:52pt}.c43{height:25pt}.c53{height:38.5pt}.c39{background-color:#ffff00}.c22{background-color:#ffffff}.c25{font-style:italic}.c28{height:11pt}.title{padding-top:0pt;color:#000000;font-size:26pt;padding-bottom:3pt;font-family:"Arial";line-height:1.15;page-break-after:avoid;orphans:2;widows:2;text-align:left}.subtitle{padding-top:0pt;color:#666666;font-size:15pt;padding-bottom:16pt;font-family:"Arial";line-height:1.15;page-break-after:avoid;orphans:2;widows:2;text-align:left}li{color:#000000;font-size:11pt;font-family:"Arial"}p{margin:0;color:#000000;font-size:11pt;font-family:"Arial"}h1{padding-top:20pt;color:#000000;font-size:20pt;padding-bottom:6pt;font-family:"Arial";line-height:1.15;page-break-after:avoid;orphans:2;widows:2;text-align:left}h2{padding-top:18pt;color:#000000;font-size:16pt;padding-bottom:6pt;font-family:"Arial";line-height:1.15;page-break-after:avoid;orphans:2;widows:2;text-align:left}h3{padding-top:16pt;color:#434343;font-size:14pt;padding-bottom:4pt;font-family:"Arial";line-height:1.15;page-break-after:avoid;orphans:2;widows:2;text-align:left}h4{padding-top:14pt;color:#666666;font-size:12pt;padding-bottom:4pt;font-family:"Arial";line-height:1.15;page-break-after:avoid;orphans:2;widows:2;text-align:left}h5{padding-top:12pt;color:#666666;font-size:11pt;padding-bottom:4pt;font-family:"Arial";line-height:1.15;page-break-after:avoid;orphans:2;widows:2;text-align:left}h6{padding-top:12pt;color:#666666;font-size:11pt;padding-bottom:4pt;font-family:"Arial";line-height:1.15;page-break-after:avoid;font-style:italic;orphans:2;widows:2;text-align:left}

# [1](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62108/chapter/25888&sa=D&source=editors&ust=1714064099677980&usg=AOvVaw0tlrRygRi0poLKkT0s7DWX) [Lesson II – Introduction to the relational databases](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62108/chapter/25888&sa=D&source=editors&ust=1714064099678312&usg=AOvVaw3-g6gxmy2ZiK8iMgYp2lOo)

[15.03.2024 11:45 | Number of chapters: 8](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62108/chapter/25888&sa=D&source=editors&ust=1714064099678667&usg=AOvVaw1IkUlf7Q1KQz-_ErHPhDcp)

# New skills

The goal of this lecture is to explain the problem of storing data, especially within relational databases. This issue will be studied in depth in future semesters during lectures like “Relational Databases”  and “Database Systems” . After studying the five following database related lectures student should be able to explain terms like “data”, “information”, “logical database structure”, know the basics of designing the relational database structure and the basics of SQL query syntax.

The first lecture is dedicated to explaining the need of storing data in today’s world and pointing out the currently used technologies and data models.

### Learning outcome

*   Student understands the ubiquity of data stored in various ways depending on the technology used,
*   Student understands the need of introducing data structure when storing data,
*   Student is able to list the database examples from the everyday life,
*   Student understands the existence of various data models and can explain in detail at least two of them.

# Database – what’s that?

The term „database” in the sense of a system for collecting and storing data dates back to the ancient times. People have always strived for recording their knowledge. The main purpose of this activity was the possibility of drawing conclusions on the basis of possessed information. The basic idea of this mechanism hasn’t changed at all.

### Do you see this sign:

![](images/image18.jpg)

### Remember where and inform the others.

All we need to know is:

*   How to store this information?
*   How to make it available?
*   For whom should we make it available?

While the answer on the third question depends mainly on one’s intentions, the answers to the first and the second questions are strictly dependent on the technology at our disposal. Moreover the technology used can influence the data accessibility and therefore the usability of our solution. Hence our conclusion is: the ability to store information and the extent of its accessibility are determined by the technology we use.

### How was data stored in ancient times?

We can say that one of the important aspects of human history was the way of recording and storing data. Only few were known and all of them were determined by the technology available at that stage of human development.

### Ways of storing data archaic from our perspective

Clay tablets, cuneiform writing  – 4 000 BC till 4 century

![](images/image94.png)

Papyrus, handwriting  – 3 000 BC until the first century

![](images/image28.png)

Parchment, handwriting and print  – 3rd century BC till 17th century

### …and a little closer to our times

### Finally a few modern technologies

Paper  – discovered in China in 8 BC and used until today around the world

Print  – method of duplication of text with a stamp, known for thousands of years. Modern printing is done using a moveable type invented during the medieval times. The zenith of its development falls on the first half of the 20th century.

![](images/image93.png)

First modern printing machine  was constructed significantly later (in second half of 19th century) as an aid for handwriting.

![](images/image20.png)

### … and what was the result of storing this data?

After many years of acquiring and storing data we managed to collect an enormous amount of data.

Library of Congress  – the biggest library in the world. 142 mln of various documents (29 mln of books, 4.8 mln of maps and atlases, 12 mln of photos, 6 mln of microfilms, 3.5 mln of music documents, 0.5 mln of films). Library consists of 856 km of shelfs in three buildings. There are 22 reading rooms, 5 thousands employees (source: Wikipedia).

And there are so many other, smaller libraries containing a lot of data.

What’s our conclusion then? We have enormous collections of data recorded using various old, “classical” technologies. This, however leads to serious problems, such as: how can you find the information you need in this enormous data set using the old technologies? Or how can we make sure that the information coming from two different sources is consistent? And finally, how to decide which information is “true” and which is “false”?

### Computer – revolution in technology

…of course not only in the data storing technology. And it did not happen overnight.

Atanasoff-Berry Computer, ABC  – machine used for solving linear algebraic equitation. The first machine was built using 270 electron tubes. It used binary numbers and wasn’t programmable. USA 1939.

Z3 – (relay successor of mechanic Z3) – Germany, 1941  – the computer was able to perform four types of operations and extract the roots from binary numbers, the clock frequency was 5 1/3 Hz, the memory capacity up to 64 words (each consisting of 22 bits ), the program memory consisted of an eight channel punched tape. Only one model was built and it was subsequently destroyed by the Allied forces. It was used for the endurance calculations of wings in the aircraft industry.

Colossus  – Great Britain – the first one was built on 14th of April in 1941. Altogether 11 models were built. It was used for breaking the code of German encryption machine called (Lorenz machine).

ENIAC  – USA 1943 – 1945 (27 tons, 18 000 electron tubes, 140 square meters). It didn’t have operational memory. It was programmed by manipulating switches and cables. Afterwards it also used punched cards.

As we can see the beginnings weren’t so easy. But what has the computer brought to the technology of storing data? There are two basic technology advancements we should point out:

*   The drop in prices of mass storage (tapes, drives, CD) allowed for storing vast amounts of data on very little space and with little cost.
*   The ability to search through data in relatively short time.

![](images/image55.png)

But along with these possibilities certain challenges appeared. Various data structures were needed for efficient data storage in order to make a full use of the computer. This is the beginning of the databases in the modern meaning.

### Control questions

Do you think that the computer is necessary for storing data?

Yes

No

Check the answer

Did the concept of data storage appear in the second half of the 20th century?

Yes

No

# Database – basic information

We often use terms “data”  and “information”  interchangeably. But what do they really mean? Are they interchangeable?

Information  and data  –both terms are used for describing the reality or more precisely a part of it, but they are not synonyms.

Data  – these are values that can be transformed and processed (by computer or by our mind). We can assume that data is something that we can save and record in various ways (numbers, text, image files etc.).

Information  – this term generally means data along with its semantics which is the key to proper interpretation. Lack of interpretation can render data useless.

Let’s assume that in front of us we have a page with Japanese symbols. This is our data. But can we read and understand the information contained within each symbol? We probably could if we knew the Japanese language. Otherwise we can’t. Just to be clear I have no idea about Japanese language.

Data is one of company’s (or institution’s, organization’s) main assets, next to its capital, employees and infrastructure. It allows the company to operate and interact with business environment but, just like other assets, it requires maintenance and management. The data management is realized through the information system  which satisfies the need for information about certain part of our business domain. Database is usually a part of this system which is responsible for storing, security and management of the data and its accessibility.

We can identify here a conceptual dualism. By “database” we mean:

*     
    Database Management System (DMS) – data structure, security, rules about its accessibility (DBMS)

Or

*     
    Data Collection (DC)

The database has become a standard way of introducing structure and rules into the process of data management. These structures and rules evolve together with the information technologies. In the next part of this lecture, under the term “database”, we will mean the term ”Database Management System”.

### Control questions

Can you tell what number it is? - 1101

Yes

No

Check the answer

Can a school library be called a "database" according to/as explained in the aforementioned definitions?

Yes

No

Check the answer

Can student’s notes from lectures be called a “database”?

Yes

No

Check the answer

# More on database

### What do we expect from a DBMS?

We generally expect database to securely store our data and allow it to be easily queried by the authorized users. In practice we demand the following:

*   Durability  – data should be stored for specific amount of time. Usually we don’t know how long this period will be. Time should not affect the data.
*   Data must be accurate  – data must reflect the reality as accurately as possible and the structure must allow for data updates whenever changes occur.
*   Replication control  – database must guarantee control over the redundant data in order to avoid ambiguity.
*   Structure design  – database should be structured in accordance with specific data model.

As it soon turns out the technological progress has rendered the last two demands somewhat outdated and consequently they are often rejected by modern database specialists.

I would like to turn your attention to the term “redundancy”, which describes superfluous data used to record some kind of information. It can lead to a situation when we obtain different and often contradictory answers when we use different data sets to describe the same thing. Of course this is an unwanted situation, although in practice it is inevitable to some degree. If it happens we would like to know how to control it.

### What do we require from a modern DBMS?

Any modern database must fulfill many different requirements which are necessary for functioning as part of information system, such as:

*   Concurrent data access  – database must be able to handle many concurrent operations on the same set of data while maintaining data consistency. Can we imagine banking, airport control or ticket booking systems which cannot handle securely hundreds or thousands of concurrent clients trying to access them?
*   Data security  - this is a multi-faceted issue. Security can be considered from many different viewpoints. Data is valuable, its acquisition is usually costly and its loss may be devastating for a company (e.g. banking systems).
*   Independence of the data and the processes using it  – this property has a big impact on the possibility of the future development of an information system and of a widespread use of databases as part of it. One database can be accessed by many processes, run by different applications on various platforms. The DBMS should be able to handle them independently of their platform or technology.

We should always remember that the costs of fulfilling of each aforementioned requirements are proportional to the quality of the solutions adopted . On the other hand cheaper solutions may turn out to be much more costly on the long run!

# Does information always have value?

We can conclude that information has value if it is:

*     
    Correct  – it contains true information about specific subject. It is obvious that keeping the false information does not make sense. Of course it does not mean that all of the information stored in a database are always correct. The reasons behind it may vary – starting from errors in data model structure or errors during writing or reading process, finishing with a deliberate act of data manipulation.
*     
    Accurate  – information should be neither too accurate nor too general. Storing and searching the database is costly. From this we can conclude that storing too detailed data can generate unnecessary cost. On the other hand absence of important data can render information to be inaccurate or false. This is why the phase of designing the correct database structure is so important, especially the decisions we make about the level of detail that we want to store.
*     
    Available  – time required to access the information must be adequate to the importance of data. Of course “time of access” is a relative term. One hour may be the proper time frame for generating a company annual balance sheet but it is surely unacceptable for checking the train timetable. Incorrect database structure and incorrect methods of acquiring data can prevent access to data in a reasonable time. In this kind of situation changing the hardware configuration (e.g. adding more RAM) wouldn’t help in a long run and would generate additional costs.

### Databases are everywhere

Considering why databases have become such an important part of information technologies we should point out two main aspects: formalizing of the database concept and emergence of consistent data model, on which a number of applications were developed, allowed to solve a number of problems caused by:

*     
    A ubiquity of information,
*     
    Creation of various data sets with increasing level of volume and complexity,
*     
    The widespread need for availability of data with lower access time,
*     
    Easy and widespread possibility of generating new data sets.

Of course the Internet and its popularity has had a big influence all over the world as Web 2.0 became more popular – every Internet user is now both the consumer and the producer of data.

We can assume without hesitation that every IT - related project nowadays uses some kind of database, either internal (integral part of the project) or external (which shares its data through a specific interface). Moreover it is possible that one IT project uses multiple databases or that one database is used by multiple IT projects.

The field of database systems represents nowadays one of the largest and most active segments of software market (which means good earning possibilities). Creating and management of databases involves almost all branches of the modern IT:

*     
    Operating systems,
*     
    IT theory,
*     
    Artificial Intelligence,
*     
    Logic,
*     
    Programming languages,
*     
    Multimedia,
*     
    Software engineering.

### Control questions

What does the term “redundancy” mean?

Storing data which is contradictory.

Lack of data, which prevents acquiring the correct information.

Unnecessary/redundant data in the database.

Check the answer

Does the information access time decide about the quality of IT solution?

No, time required to access the required information is irrelevant if we are able to acquire it.

The information access time is one of the main parameters determining the quality of the DBMS.

Check the answer

# Data models – what is it?

Data model is a data storage structure which allows us to anticipate where and in what form data will be stored and how it will be queried and read. In a relatively short span of IT technology evolution a few models have emerged, the most important of which is the relational database model. In fact, the database history can be split into the period before this data model and afterwards.

## “Classical” data models

### The card index model

Data is stored in records within one or more tables of identical structure. The records can be sorted and filtered. Each table is an independent document without the possibility to cooperate with the others. The phone book in a mobile phone or tables in Excel or Word are good examples of this model.

### The hierarchical model

In this model the data is stored in the form of records linked by forming a parent - child relation structure. Each record has one parent. If record has more than one parent it must be copied to keep the aforementioned rule. Removing the records means deleting all off its descendants. This model should be familiar from our file system. In order to operate on data we can use traditional programming languages like C, Pascal or others.

Searching through data in a hierarchical database requires looking through all of the descendant records. An example of this database model can be found in a family tree. In the world of IT we can find this model in our file systems.

### The network data model

This model is an extension of the hierarchical data model. It allows to add pointers which allow for sharing “branches” of the data tree structure among records. Relations between records are defined by creating the collections of data which thus model an owner - member relationship. Each record can enter multiple relationships.

### The relational model

The relational data model represents a radical change in comparison to the classical database models whose functioning is based on the concept of file and records (lines) written in it. The relational model turned out to be a great success as it gave a solution to many important problems. It introduced a lot of well thought out solutions which were a turning point in developing highly scalable database solutions (e.g. SQL language, advanced “engines” for processing data). Because of that it has become a reference point for further development of the database solutions.

On the other hand the relational model is more than 40 years old. This is a long time in the IT industry. Nowadays there are more modern approaches to solve similar problems.

### Object databases

The concept of object databases emerged when it became necessary to work with non-objective data structure in objective programming languages. The “objects” in object database represent real life entities and they possess certain identity. Object type (class) defines complex data type which can contain other data types or collections of data types. Data structure is characterized by strong encapsulation (inner structure of the object is not visible to the user). Moreover, the knowledge of this structure is not necessary for using the specific object. The object inherits the structure, properties and methods from its class. In spite of the beauty of such solution (in terms of the IT theory) it hasn’t become as popular as the relational data model due to the enormous cost of replacing already working relational solutions with object databases. On the other hand it doesn’t seem to solve one of the most important problems of the modern IT technology which is processing very large volumes of data (the “Big Data” problem).

However there are some solutions developed by object databases which have been introduced into the relational databases resulting in structures called object - relational solutions.

### Modern data models

Actually this is the end of the history of “well-defined” data models. Modern technologies (Internet, cloud-related technologies) force us to develop other approaches to data processing. Instead of the “data model” we now prefer to talk about the “Database Management System”.

All of the classical data models assumed the existence of predetermined, rigid structure for storing data. This approach was very convenient especially when it comes to data querying. However it doesn’t work well when faced with challenges of modern world like common Internet access and the Web 2.0 philosophy.

The main problem is the need for processing very large volumes of unstructured data in small time frame, for example the data generated by social sites like Facebook, Twitter, and internet search engines (Google) or services used for storing data in the cloud. The solutions for this problem are database management systems (or data models) which deliberately abandon various requirements of the traditional data models, like the control of replication or uniform data model (there is a few more but we will leave it for now).

The DBMS’s which perform these tasks are called the NoSQL Databases (Not Only SQL).

### Graph databases

A graph database is based on the concept of a graph. Each node represents an object and the data associated with it. Graph’s edges (named and directed) represent relations between objects. Typically this kind of database is used for modelling of social networks.

### Semantic Web

This concept (it can hardly be called a data model) assumes the emergence of a technology and standards which allow machines and programs to search and process data based on its semantics. In this case we treat Internet and its resources as “the database”.

### Map Reduce

Again it is difficult to call this a data model. Here we deal with the concept of storing and concurrently processing of large volumes of data within big data clusters. It comes down to dividing the problem into various smaller ones which then can be split among different clusters. The results from the clusters are returned and merged together into one global solution. This concept has already a few implementations and is currently in the development stage.

# A short history of databases

*   1961  – Integrated Data Store IDS  (author: Charles Bachman for General Electric) – first DBMS, first implementation of the network data model
*   Started in 1966 , first-ever run in 1968  – Information Management System IMS –  Created by the IBM consortium along with the Rockwell and Caterpillar for the purpose of managing the technical documentation of Saturn V rocket ship and Apollo capsule. Realized according to the hierarchical data model (is still in use).
*   1970  – dr Edgar Codd (IBM employee at that time), proposed basic principles of relational data model in the article “A Relational Model for Larged Shared Data Banks”
*   1969  – the first specification of the network data model known as CODASYL . There have been many implementations loosely based on this specification. The ISO/ANSI standardization was created in 1968 but it gained no practical significance.
*   First half of 1970s  – first prototype of SQL query language called Sequel  (authors: Donald Chamberlain and Robert Boyce) was created in IBM’s laboratory in San Jose. However the name had to be changed to the Structured Query Language (SQL)  due to the naming issues with a British company called Hawker Siddeley.
*   1974  – first relational database management system and first implementation of SQL – System R  in IBM . In the beginning it was treated as a research project. Their first commercial client was Pratt & Whitney in 1977.
*   1976  – Peter Chen created the concept of the entity data model (ERD, ERM) as the methodology for designing and analyzing database structure. It has become the base of the future CASE solutions and repositories. However it hasn’t been standardized so far.
*   1977  – the company called Software Development Laboratories  was crated. In 1979 it was renamed to Relational Software Inc.  and in 1982 it was renamed once more to Oracle Systems Corporation . The company started to work on a database system compatible with Codd’s relational data model. In 1979 they introduced their first commercial database solution called ORACLE 2.
*   1983  – IBM introduced system called DB2  which was the successor of System R . It was the first fully commercial relational database. In the beginning it was used only with the mainframe computers produced by the IBM .
*   1986  – the first standard of the SQL language (ANSI)
*   1987  – the first standard of the SQL language (ISO)
*   Next versions of the ANSI/ISO standard: 1989, 1992 (SQL2), 1999 (object - relational data model), 2003, (SQL:2003, XML databases), 2006 (SQL:2006, usage of SQL with XML), 2008 (SQL:2008).

### Further development of databases

1990s – the database theory was expanded to include the following aspects:

*   Multilayer architecture
*   Distributed data
*   Concurrent access methods
*   Internet as a data access technology
*   Data warehouses and OLAP (On-Line Analysis Processes)

Databases are used in new technologies:

*   Storing and sharing multimedia
*   Storing documents (including XML data)
*   GIS (Geographical Information Systems)
*   Utility systems – ERP (Enterprise Resource Planning) and MRP (Management Resource Planning) – packages like SAP, Baan, Oracle, PeopleSoft, Siebel, CRM (Client Relationship Management)

# Summary

In the second lecture we presented the history of databases and their importance in the modern information technologies, and thus in many branches of economy and administration. We introduced different concepts of data models including the relational data model. In the next lectures we will discuss the relational data model in detail.

# [2](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62109/chapter/25896&sa=D&source=editors&ust=1714064099699058&usg=AOvVaw1v4gCqauJJWZiVsZcYgZgD) [Lesson III - Relational database model](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62109/chapter/25896&sa=D&source=editors&ust=1714064099699423&usg=AOvVaw2nCslZ3faL7ehjslDxABXU)

[15.03.2024 11:45 | Number of chapters: 9](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62109/chapter/25896&sa=D&source=editors&ust=1714064099699733&usg=AOvVaw1C4mw_YVCXXCUB3BGOEmnz)

# New skills and knowledge

In this lecture we will present the idea of a relational database and elementary examples of data structures in the relational model. We will also present so-called Codd’s 12 rules, which constitute the basic assumptions of the relational model. After this lecture student should grasp the general idea of this model. I would like to emphasise that this lecture contains the basic knowledge necessary for understanding the relational model and for further learning of this subject.

### Learning outcome

*     
    Student knows who was the inventor of the relational database model,
*     
    Student understands the concept of data storage in a logical table structure and the idea of recording the relationship between data written in many different tables,
*     
    Student can define the concepts of a primary key and a foreign key and understands their function in the relational database model,
*     
    Student knows and understands the notion of a relation as a mathematical model of a database table,
*     
    Student understands the notion of the pseudo-value NULL and knows the results of algebraic, text and logical operations using NULL.

# The origin of the relational database model

Edgar Frank Codd was the founder of the relational database model. A short biographical note from Wikipedia is enclosed below

Edgar Frank “Ted” Codd  (19.08.1923-18.04.2003) was an English computer scientist, famous for introducing the relational database model. He studied maths and chemistry at University of Oxford. During the Second World War he served as RAF pilot. In 1948 he moved to New York to work for IBM as a mathematical programmer. In 1953 (at the time of McCarthy’s commission) he moved to Ottawa, Canada. A decade later he returned to the USA and received his doctorate in computer science from the University of Michigan in Ann Arbor. After that he moved to San Jose, California, to work for the IBM. During 1960’s and 1970’s he worked out his theory of data arrangement, issuing his fundamental paper “A Relational model of Data for Large Shared Data Banks” in 1970. To his disappointment, IBM proved slow to exploit his suggestions until the commercial rivals such as Oracle (formulated by Larry Ellison and based on Codd’s ideas) started implementing them. Codd also coined the term OLAP (Online analytical processing) and wrote “the twelve laws of online analytical processing”. He also had a contribution to the cellular automata theory. Codd received the Turing Award (computer science “Nobel Prize”) in 1981.

![](images/image4.png)

Initially the relational model was sceptically received as other data storage systems had already been in use. The Integrated Data Store developed on the basis of the network data model by General Electric, and IBM-made Information Management System, based on the hierarchical model were already available. Nevertheless, its popularity grew in time and soon the relational database model became the most popular.

Today, despite the emergence of next generation models (the objective and the semantic ones) applications implementing the relational models still dominate the market. This is due to its simplicity and flexibility, high quality of the relational model-based DBMSs as well as large amounts of data already stored in relational databases. We do observe though a tendency to include some features of the objective models into the relational model, giving rise to the so-called objective-relational database model.

# Relational database model, the first elementary example

In the next lectures and during other database related courses the relational database model will be presented in more detail. In this lecture the basic principles of this model will be presented using an elementary (but representative) example.

The basic principles of relational database model are:

*   All data is written in the form of tables
*   A table contains columns which include data of a specific type
*   A table cell (on the intersection of row and a column) contains a single, atomic, indivisible value

These three conditions are enough for now.

### Relational model: the first elementary example

### Assumptions

Let us assume that we want to record information about courses and lecturers at our school. We assume that each course has only one lecturer, but every lecturer can be responsible for many courses.

We need to guarantee unambiguous identification for every lecturer and every course and we also have to attribute every lecturer the courses taught by him or her.

In accordance with the above formulated postulate that all the data must be written as tables, we will start by creating a table of LECTURERS .

This table will include each lecturer’s personal and professional data – name, surname and his or her scientific degree. Every row (record) will include the data of one lecturer. In order to be able to distinguish between the data of each lecturer independently from their names and surnames (which can in principle be the same for different people!), each record (and thus also the lecturer) is identified by an additional field (i.e. a column) named Lecturers\_Id. It is essential that each lecturer has an unambiguous, unique identifier, because in the relational model a row can only be identified by the values stored in the columns. Since we have assumed that the lecturers’ names and surnames are not unique we need to include a column whose value uniquely identifies a row.

![](images/image74.png)

We now need to prepare the COURSES  table. This table will include the courses data: the name of the course, its code and the Lecturers\_ Id. Note that its value doesn’t describe any feature of the course itself, but rather represents the relation between the course and its lecturer, whose data can be accessed in different table using the Lecturers\_Id.

![](images/image34.png)

Adding an unambiguous key for each row to the table LECTURERS  allows us to connect rows from the tables LECTURERS  and COURSES . Thus there is no need for each row to include all the data (name, surname, degree) of the course’s lecturer. In fact this would lead to redundancy: one piece of information (the lecturer’s data) would be stored in many places.

The value of the Lecturers\_Id will appear in the COURSES  table as many times as many courses the lecturer is responsible for. On the other hand, each course is connected with at most one lecturer and the “Data warehouses” course is not connected to any elements of LECTURERS , which simply means that the course has no lecturer assigned yet.

### Control questions

Can we have 9999 in the index for the Lecturers\_Id table in the elementary example above?

Yes, we can

No, we can't

Check the answer

Which option for the row “Data warehouses” would be better: leaving a cell LECTURERS\_ID empty, or filling it with a value not appearing in Lecturers\_Id column in LECTURERS table?

It is better to leave the cell empty.

It is better to fill in the cell with arbitrary value.

Check the answer

# Primary, alternate and foreign keys

Each table must have an unambiguous index which is called the primary key . It represents one or more columns, whose values unambiguously identify the row (record). The primary key value must be specified and unambiguous.

An alternate key  (called also candidate key or just key) has the same uniqueness property as the primary key, but there is only one primary key and there can be several alternative keys.

In the COURSES  table Code  is the primary key, while Name  is an alternate key. These keys specify the course uniquely in a natural way if we assume that no 2 courses can have the same name or code. In the LECTURERS  table Lecturers\_Id  is the primary key. The family name, the first name or the degree on the other hand cannot be the primary keys, as their values can repeat. It is even possible for all 3 values to repeat. Thus, we have introduced an additional column Lecturers\_Id which describes no physical feature of the lecturer, but which is used as a unique identifier of a lecturer.

A foreign key is one or more column whose value is the primary key identifying a row in another table.

In the COURSES  table the LECTURERS\_ID  is a foreign key whose values come from the primary key column of the LECTURERS  table. For example the value 235 in the “Relational databases” lecture points to the row in the LECTURERS  table which contains the information about a lecturer whose surname is Kowalski, whose name is Jan and who holds a PhD. This information may simply be interpreted as:

“The ‘Relational databases’ lecture has been assigned to a lecturer named Dr Jan Kowalski”.

### Control questions

How many primary keys can table in relational database have?

Up to 1

Only 1

Possibly more than 1

Check the answer

Does a relational database need to have a foreign key?

Yes, there must be at least one.

No, there are tables which do not have any foreign key.

Check the answer

Is it possible for the foreign key value to be indefinite?

Yes, if we assume this is allowed.

No, the foreign key value must be specified for each table row.

Check the answer

Can a foreign key have an arbitrary value?

Yes, as long as it is consistent with the data type in the column.

No, we can only use values which have previously been used as primary keys of the appropriate table.

Check the answer

Can the value of the primary key remain indefinite?

Yes, if we assume from the beginning that we allow it.

No, its value has to be set in every row of the table.

# Relational database model: elementary example 2

### Assumptions

Let us modify our assumptions from the previous elementary example. Let us assume now that we need to record data about the courses and the lecturers. Just like before, one lecturer can teach several courses, but unlike the previous example one course can be taught by more than one lecturer.

The database needs to be able identify uniquely all lecturers and all courses, find all lecturers responsible for each course and all courses assigned to a given lecturer.

Let us use the data of two lecturers and their courses for our database example: dr Jan Kowalski teaches PPJ, ASD and SBD, and dr Konrad Piotrowski teaches AUG, ASD and RBD.

The table below shows how tables LECTURERS  and COURSES  can be linked.

![](images/image35.png)

As we can see, our case is now more sophisticated. In order to link the courses with their lectures we would have to write multiple values into the Lecturers\_Id column of the table. If we implemented this solution it would mean that we break the atomic rule, which is one of the most important rules in relational model.

Let us try to implement another solution for our case. Let us then record pairs of records (a lecturer and a lecture) registering this way links between them. Note that we do not need the full records as each record is identified by its primary key. Thus, writing just pairs of primary keys we store sufficient amount of information to link lecturers and their courses.

![](images/image68.png)

Our current scheme is shown below:

![](images/image87.png)

In order for the scheme to be clear the linking arrows have been left out. As you can see, we managed to record the full information about the links between the lecturers and the courses they hold in a separate table. In a table storing this data (called the junction table) each lecture primary key appears as many times as many lecturers hold it and, conversely, each lecturers primary key appears as many times as many lectures he is assigned to. And what is the primary key in a junction table? Note that the code and the Lecturers\_Id taken together must be unique. Repetition of these values would result in redundancy (repeating the same information). Thus the primary key of the junction table is defined as the sum of the 2 foreign keys.

One final remark: I would like to point out that that thanks to the junction table we have effectively returned to the situation from our 1st example: now each record in the junction table is linked with one  
  
table record and one COURSES  table record.

### Control questions:

Can we solve abovementioned case without using associative/junction table?

No, it is not possible.

Yes, this is possible by entering more than one value of the foreign key in the appropriate column.

Check the answer

Is it possible to omit the value in one of the columns of a junction table?

Yes, you can omit one.

No, no column can be omitted.

# Database – why have we chosen the relational model?

In maths we define a relation as a subset of the Cartesian product of two sets.

Discrete mathematics – short revision

  
The Cartesian product of two sets A and B is a set of all ordered pairs (x,y) such that x is an element of A and y is an element of B.

A × B = {(x,y):x ∈ A and y ∈ B }

The Cartesian product is not commutative : A×B ≠ B×A

For example:

A={a,b,c}  
  
B={1,2,3,4}

  
A×B = {a1, a2, a3, a4, b1, b2, b3, b4, c1, c2, c3, c4}  
  
B×A = {1a, 1b, 1c, 2a, 2b, 2c, 3a, 3b, 3c, 4a, 4b, 4c}

Thus:

A relation on sets A and B is any subset of the Cartesian product A×B, while a relation on B and A is any subset of B×A.

The end of discrete mathematics revision

  
But how is this connected with the main topic of this lecture, i.e. databases? It’s easy to see that the representation of a relation built on two sets is a 2-dimensional table made of 2 columns and as many rows as many elements of relation we have. Obviously a relation on n sets can be represented by a table with n columns. This concept is the basis of the relational database model: all data are stored in two-dimensional tables.

The set of 13 rules (numbered from 0 to 12) which need to be fulfilled when designing a relational database management system (DBMS) as well as the database model has been published by Edgar Codd in his article “A Relational Model of Data for Large Shared Data Banks” published in 1985. It is known as the “Codd’s 12 Rules” .

Before we discuss some of the rules in detail we need to introduce two important notions.

### Database levels of abstraction

A database can be considered on various levels of abstraction:

1.    
    The external (view) level:  this is the way ordinary users see the data in a database. What he or she sees is usually very different from the data structure on the logical level (i.e. the table structure). What we mean here is the access to the database via client applications, usually using a GUI, for example via a web browser.
2.    
    The logical (conceptual) level:  this is the collection of tables linked by relations as well as all other objects guaranteeing the integrity of the data and its connection to the physical record on a disk. We focus on this level in this lecture, because it is the level on which the database designers and developers operate.
3.    
    The physical level:  the collection of files in a file system in which the data is physically stored. This level is interesting to a rather limited number of users, consisting of the system administrators.

### Constraints

The constraints are rules whose functions is to guarantee the logical correctness of the data stored in the database. They are defined already in the database designing phase and they are later enforced by the DBMS. We will discuss this in detail further on.

### Control questions

Can the Cartesian product of two sets contain 2 identical elements?

Yes

No

Check the answer

Do we need to consider the files arrangement on the servers’ disks while designing a database?

Yes

No

Check the answer

# View – a useful tool for working with RM (relational model)

In the example above it was possible to store data about courses and their lectures in a simple and clear way. It is however much more difficult to read the data about the relations between the records in the LECTURERS and the COURSES table.

In example 1 we described the relations between lecturers and their courses where we assumed that one course can be taught by only one lecturer, whereas a lecturer can teach several courses. Accessing information stored in these tables is quite simple. If we want to read data about lecturers and their courses, we need to read data from tables. This can be achieved using the links between the rows (records), the primary key values in LECTURERS table and the foreign key values in the COURSES table.

The relations between the lecturers and the courses are even more difficult to read in Example 2. Recall that we have assumed that ONE lecturer may hold many courses and at the same time ONE course may be simultaneously held by many lecturers. Our solution was to create an additional table just for the relations between courses and lecturers. In this additional junction table we store pairs of foreign keys linking the lecturer with the appropriate course. But this means that in order to find out which lecturer holds which course we need to read data from three tables: the lecturer’s data from LECTURERS, the course data from COURSE and the data about the relation between them from the junction table. This is somewhat cumbersome.

As you can see, the RM is not particularly user-friendly when it comes to reading the data. We need to read three separate tables and link the appropriate records with the corresponding primary and foreign keys if we want to find out who teaches which course. This process may be simplified if we use objects called VIEWS created as the result of reading the current state of data.

We present an example of a view containing courses names and lecturers data.

![](images/image26.png)

A view presents data in a way they are seen by the users (and not the database designers). Views provide data (from one or more tables) which are suitable for presentations. The same data can be presented in different layouts by various perspectives.

The content of a standard view is calculated by the system from the underlying tables. Usually the result of this operation is not permanently stored in the database. What is recorded is the view’s definition (a ‘recipe’ how to prepare it). Although views do not store data, they are often called ‘’virtual tables” as they ‘’provide data’’ for database objects and processes in the same way as it is done through the tables. Moreover, the result of the data reading is the same for the end user irrespective whether it was read from a view or from the tables themselves.  
The end user doesn’t usually know if the provided data come from the table or from a view.

In some cases it is more convenient to store the content of a view in the database and use it instead of performing complicated searches which might overload the server. This kind of view is called the MATERIALIZED VIEW . Not all DBMS’s create and store materialized views. Note that although a materialized view is physically stored the same way as a table, there is a significant difference between them. The data in a database are “alive”: the records may be modified, rows may be added or removed. The data in tables are always up-to-date. The data in a materialized view on the other hand constitute a snapshot of the database from a given moment. If the data in the database changed after the materialized view had been made the view remains unaffected. It’s important to realize that.

### Control questions

Can we use a non-materialised view to store data?

Yes, we can store data in non-materialised view as well as in tables.

No, a view cannot store data.

Check the answer

On which database abstraction level are views used?

Logical level

Physical level

External level

Check the answer

*   abase objects.
*     
    DML  (Data Manipulation Language) – set of instructions for writing, modifying and deleting data.
*     
    DQL  (Data Query Language) – set of instructions to read data from databases.
*     
    DCL  (Data Control Language) – set of instructions for authorizing and de-authorizing users to access and manipulate data.

The SQL language structure will be presented in more detail in the next lectures and other database related courses. It is important to remember that SQL in its basic form is not a programming language. It does have extensions allowing to use variables, conditional statements, loops, recursion and exception handling. Note however that while the SQL syntax is almost identical in all of its implementations, the extensions are quite different in many aspects. Another big difference between SQL and other programming languages is its declarative character: in SQL we define what operation we need to be executed, but the way it is done is decided by the DBMS. In other words: we decide what needs to be done, but we leave the decision about the way it is done to the DBMS.

## Rule 10

## Integrity independence.

Integrity constraints specific to a particular relational data base must be definable in the relational data sublanguage and storable in the catalogue, not in the application programs.

The DBMS must guarantee the possibility to define the integrity constraints and enforce them. Defining database constraints must be possible on the DBMS level, independently from the applications using it. Their modification must be possible at all times without the need to update the applications. Fulfilling this rule guarantees that the constraints defined once and stored in one place will be obeyed by all processes accessing the database.

### Control questions

Which of these objects constitutes the logical data structure in a relational database?

A file

A view

A table

A folder

Check the answer

You are looking for one piece of information in a database. Is it enough to know the column’s and table’s name to find it?

Yes

No, one more information is needed.

Check the answer

You are looking for one data in relational database. Is it necessary to know the name of the file where these data are stored?

Yes

No

Check the answer

What is the result of this operation: X\*3 + 12 for X as NULL (pseudo value)?

12

15

NULL

0

Check the answer

What is the result of FALSE AND NULL logical operation?

TRUE

FALSE

NULL

Check the answer

What is the result of FALSE OR NULL operation?

TRUE

FALSE

NULL

Check the answer

What is the result of TRUE OR NULL operation?

TRUE

FALSE

NULL

Check the answer

# Final remarks

This is probably the most important lecture of the whole WSI course concerning the relational databases. We presented the concept of the relational database model, which is built on the relation algebra, briefly outlined here, and the logical idea of recording data in tables. We have also introduced a new notion: the NULL pseudo value modifying the standard logical operations. We will encounter this notion repeatedly in the field of databases, so it is very important to understand what role NULL plays in the elementary logic. Finally the Codd’s rules (only a few presented here, the full list will be discussed on the RBD course) form the axiomatic basis for the relational data model. We need to understand them in order to understand the field of relational databases.

# [3](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62110/chapter/25905&sa=D&source=editors&ust=1714064099719621&usg=AOvVaw3ZGziaYetkoApwMlRB96bM) [Lesson IV - Designing database structure](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62110/chapter/25905&sa=D&source=editors&ust=1714064099719928&usg=AOvVaw1ngkhpNS2XCP6JVEQblBLa)

[15.03.2024 11:45 | Number of chapters: 5](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62110/chapter/25905&sa=D&source=editors&ust=1714064099720281&usg=AOvVaw0oyhpC7Csh_BTJ6lCWpkZp)

# Introduction

In the previous lecture we learned about the concept of the relational data model. This model assumes that all the data is stored in the logical structures of tables. Its mathematical description comes from the relational algebra. The outline of this model was presented in the second lecture. In the fourth lecture we will discuss the problem of designing a relational database. In particular, we will answer the questions: why do we need to design database structures? How does the design process look like? What tools and notations do we use in the designing process? And finally - how do we create a database using a given model? During the WSI course we will present an outline of these topics. We will discuss them in depth during database related subjects like RBD, SBD and APBD.

### Learning outcome

*   Student knows the stages of the database design process, understands the role of these stages and knows what each of these stages involves.
*   Students knows what do we use the CASE tools for (especially in the context of databases).
*   Student understands the terms: “entity” as a representation of a real object and the model of a table in a relational database.
*   Student knows and understands the terms: entity, attribute, attribute domain, entity key.
*   Student understands the meaning of a relation as an ordered list of entities, the “parent” entity and the “child” entity.
*   Student is able to use the CASE tools to create a simple database diagram model consisting of a few entities.
*   Student is aware of various database diagram notations and knows the notation used in MS Visio.

# Draft of the database design process

In the database design process we can distinguish three main stages or three perspectives defining this process:

### The Concept design stage

At this stage we must define the demand for the project. We can say that this is the marketing stage in which we should decide what functions our customer needs and what his budget limitations are.

The drafts appearing at this stage are rather vague – they do not contain any details and do not choose any specific technology, but they need to be understandable for the customer and allow him to make corrections. We can compare it to the process involved in the process of designing and building a car.

### The Logical design stage

At this stage we transform the draft into a logical model. We create the model structure, specific solutions for the problem defined at the concept stage which will fulfil the client’s business needs. We design all the segments of the whole solution and define the connections between them. This time we can compare it to an architectural project with general plans but without the technical plans.

### The Implementation stage

At this stage we transform the draft into a technological model. We take into account all the constraints due to the available technology, but we must also fulfil all the conditions outlined in the logical design.

… and then we create the prototype, debug it, implement the solution and we can work on the next improved version.

As we mentioned earlier a database is usually a part of the whole information system – an important part but not the only one. Because of that it is important to consider the database design rules in the context of the whole system. On the other hand the process of creating the whole system must be preceded by a precise analysis which will give us answers to the following questions:

*   What is the subject of our project?
*   What is the purpose of our project, what kind of problems can be solved or improved by using our system?
*   What functions will need to be carried out within our project?
*   Who will be using these functions?
*   What kind of information will be stored in our database so that all the aforementioned conditions will be met?
*   What is the predicted cost of this solution?

From the database designer’s point of view the next to the last question concerning functionality of the future database is the most important one. However the answer to this question depends on the answers to the other questions.

The problems discussed above belong to the analysis stage  of the designing process.

Then comes the project stage , in which the future system documentation is written. We should also make a detailed description of the system’s functions and define its users (“actors”). At the same time we should outline the structure of the database in a way which guarantees the possibility to record all the required data. We should also define all the integrity constraints, guaranteeing the logical consistency of data.

The documentation of the system functions and the definition of the actors is often presented in the form of a use case diagram .

On the other hand, the implementation model of a database can be represented by the entity relationship diagram .

The third and final stage is the implementation .

This description should be sufficient to explain what the entity diagram is and what role it plays in the design process. This role will be explained further on.

# What is an entity relationship diagram (ERD)?

An entity relationship diagram  is a model which can represent a part of reality needed for the system and also the database structure. Just like every model it represents a simplification of the real or database object it describes. At the stage of preliminary analysis the objects needed for our database are identified. The role of the entity diagram is to create models of these objects and relationships between them. The graphic character of the diagram makes it easier to understand the database structure. It is important to understand the relationships between the database objects which can often be quite complicated.

The use case diagram presented in the previous lecture was basically the input data for graphical user interface (GUI). The entity relationship diagram has a different function as it is a model of the data structure. Thus, it puts aside client’s perspective of our application, or deals with it in a small extent.

There is a list of requirements for a proper entity relationship diagram. It should

*   Unambiguously present users’ requirements for the data stored in it,
*   Allow to check if the analyst fully grasped the users’ requirements and the character of the environment in which the system will be utilized,
*   Be much simpler from the database itself , as it puts aside the implementation details, which must be later developed by the database designer so that our database can exist and carry out its tasks.

### CASE (Computer Aided Software Engineering) tools

CASE tools are specialized programs which aid the designing of the information systems and allow to create various types of diagrams useful in the design process. The CASE tools provide graphic tools to design and draw diagrams on screen. The tools used to create the entity relationship diagrams must take into account the specific details of various database servers, for example the available data types. They should be (and usually are) able to translate the graphical version of the diagram into an SQL script. The script can then be run in the appropriate DBMS environment in order to generate all the database objects and integrity constraints.

In our lectures diagrams are made in Microsoft Visio for Enterprise Architects 2003.

### Entity

Entity  (lat. Entia ) – an entity is a singular, independent object which can be described and whose description can be stored in database.  
In the world of databases, the term entity is used to describe (model) things (objects phenomena, relationships etc.) about which we will collect data in our database. Every entity has a name that must be unique for a given database.

The definition of an entity consists of the attributes (characteristics, properties) which are sufficient to unambiguously distinguish an entity from the other ones.

We must distinguish the notion of entity as a class of objects and as an instance of this class, i.e. a single instance of the object (single copy) of a given type. For example the “PERSON” entity as a type defines attributes necessary to describe a certain group of people. Only after we substitute specific values for its attributes we obtain an instance of this entity which will represent a particular person. It should be emphasized that if the entity is used to describe a selected class of objects (in our example a specific group of people), each single object of this class (in our case each specific person) must be described with the same attributes. Note that it may be hard in practice to describe two different groups of people, e.g. a group of prisoners and a group of preschoolers, with the same attributes.

  
But the principle:  
  
Entia non sunt multiplicanda praeter necessitatem  (novacula Occami) - entities must not be multiplied beyond necessity  – known as the Occam's razor  
  
… also relates to the databases!

Entities are usually represented graphically as rectangles. The graphical representations of entities vary (slightly) according to the notation adopted by the specific CASE tool.

![](images/image89.png)

### Attribute

It is crucial to correctly choose the attributes for describing an entity. Note that attributes represent certain abstract features or characteristics, not the specific values. The attribute of the Student  entity is Name , not a specific value (say “Smith”) the attribute can take. The attribute should describe the entity rather than its relations with other entities, for instance in an airline’s database the attribute Seat\_number  should be an attribute of the Airliner  entity, not Passenger , despite the fact that the passenger sits on a specific seat during the flight. In the same way the place won by an athlete in a competition is neither an attribute of the entity Athlete  or Competition , but most preferably the Competition\_results  entity.

Consider now the entity as a model for future table in the database. It is clear that the attributes  are nothing else but the models for the future columns , specifying their names. If we also define their domains, i.e. we specify the data types we will use to store the values of the attribute, we will define the domains of the columns table.

### First Normal Form (1NF)

The concept of the “First Normal Form” (1NF) was formulated as one of the Codd’s rules. It is the first condition we must meet when we normalize the database structure. Its purpose is to eliminate any anomalies in the data insertion, modification and deletion as well as any uncontrolled data redundancy. The whole normalization process and the subsequent normal forms will be thoroughly discussed during the relational databases course in the future semesters.

An entity (and thus also its corresponding table) is in the first normal form if:

*   It describes one type (one class) of objects; e.g. the information about the car owners and their cars IS NOT  stored in a single entity that contains attributes of both the owners as well as the cars,
*   Its attribute values are elementary (atomic , indivisible) - each column represents a scalar (atomic) value rather than an array, list or anything that has its own structure; e.g. the Person  entity DOES NOT  include an attribute called Names  which contains all the person’s names stored in a list.
*   It does not contain collections (i.e. repeating groups of information); e.g. in order to store the information about sportsmen we DO NOT ADD  to the Athlete  entity an attribute called Medals  containing all the medals won by him or her.
*   It has a key, i.e. a set of attributes whose values distinguish each row from the other ones.
*   The order of the attributes should not encode any information, i.e. any change in the order of attributes should have no influence on the information content; e.g. in order to record information about the competition results we DO NOT  create an entity called Result  with attributes Athlete 1, Athlete 2, Athlete 3, ...

The above definition of the 1NF  is a bit of an over-interpretation of the original one. The latter consists only of the first three points, but I allowed myself to extend it slightly for the sake of the further argument. All the information above is true and correct .

### Key

The term "entity key"  describes a set of entity's attributes whose values are unique (unambiguous) for its every instance. Similarly, the term "table key"  describes a set of columns whose values will be unique (unambiguous) for every row in the table. Obviously it is possible that these sets contain only one element. Each table (entity) may contain none, one or more sets fulfilling the uniqueness condition, for example the Social security number  or the PESEL  can be the key in the Person  entity or the Registration\_number  in the Car  entity. However if there is no attribute with the uniqueness property in the entity we need to add an artificial attribute (column in the table) that meets this requirement. This is usually an attribute of integer type. The table column will then contain integers which uniquely identify the instances. But it can also be an attribute of the text type – e.g. the lecture code in the studies curriculum.

If the entity has more than one set of attributes whose values meet the requirement of uniqueness for every instance of the entity, then you should arbitrarily choose one of them to act as the primary key. If the entity has only one set, then there is no dilemma involved - it automatically becomes a primary key . Thus, we can identify a few keys in the entity, but only one of them can be used as our primary key.

Every CASE tool allows us to select the attribute (or multiple attributes) as the primary key during the design phase of our diagram. The illustration below shows this process in MS Visio.

![](images/image22.png)

### Data types – attributes domains

Data types or attribute domains are sets of values which can be stored by variables in the table columns. The principal types of data which we will encounter in every DBMS is the numeric type, the text type and the date type. For each of these types specific implementations provide a number of subtypes. For example: for a numeric type there is the two-byte integer and the four-byte one, the floating point number stored in four or eight bytes etc. Therefore we should find out what types are available before we start working in the specific DBMS environment.

When we speak about the entity-relationship diagram as a model of the future database we operate on the level of abstract concepts. On the other hand, on the database level we are closer to the concrete implementation. Hence, at the conceptual level (entity-relationship diagram) we are talking about the domain types as a general concept. However when we implement the database in a specific DBMS we use the types of data specific to the database solution.

CASE tools usually offer a choice of one of these approaches - either operate on universal data types not associated with a particular DBMS or choose data types implemented in the specific DBMS. MS Visio distinguishes between these two specifications of the data types. We can choose platform independent data types ( Portable Data Type ) or database specific data types ( Physical Data Type ).

The following illustration shows the selection process of the attribute’s domain (data type) from the drop-down list representing the physical data types (Oracle Server).

![](images/image19.png)

### Relationship

The relationship is defined as an ordered list of entities in the relational model. Individual entities can appear on the list multiple times. Each relationship defines a certain dependence between the sets of copies (instances) of the entities belonging to it. This correlation is called the instance of the relationship. In other words an instance of the relationship is the relationship between the entities instances. For example, the relationship between the Person  entities and the Car  entities can be described as the OwnerOfTheCar . Every instance of the Person  entity will be able to have a relationship with an instance of the Car  entity thus creating information about the cars and their owners.

The relationship can be formally represented using the relational notation:  
  
Z(E1 ,...,En)  
  
which means: entities E1 , ..., En  are included in the Z  relationship

  
You can also describe the relationship verbally, e.g.:

*   An employee works in a department  (relationship between the Employee and the Department entity)
*   An employee has a specific function in the project  (relationship between the Employee and the Project entity)
*   The company produces goods  (relationship between the Company and the Goods entity)

In practice, when designing a database, we define relationships through their verbal description.

### Binary relationship

Binary relationship  is a relationship that exists between two entities. It is represented graphically as a line connecting two frames (entities). An instance of a binary relationship  is a two argument relation in the Cartesian product of the entities instances collections.

The graph below shows the relationship between the Student  and the City  entities . This relationship can be described as follows: every student was born in a city, each student in ONE city, but… many students could have been born in ONE city.

![](images/image49.png)

After defining the relationship in the CASE tool (in our case MS Visio), the primary key from one entity forming the relationship is transferred to the entity on the other side of the relationship. This way we can create a foreign key .

In the first lecture we described the example of the Course  and Lecturer  tables and a relationship between them: for each course there is one teacher responsible, but one teacher may be responsible for several courses . In that example, the ID of a lecturer was placed in the Courses table and served as the indicator in order to determine which teacher is responsible for that item. A similar case is shown in the example above. The city ID (i.e. primary key of the City  entity) is placed in the Student  entity in order to indicate his or her place of birth. One instance of the Student  entity is associated with one instance of the City  entity, thus creating a single instance of a relationship.

Let us go back to the definition of the relationship as an ORDERED list of entities. The relationship in our example can be described as follows: ONE student was born in ONE city, but in ONE city MANY students could have been born. This definition is not symmetric! For each student you can specify one city where he or she was born, but for each city we can potentially find many students who were born in it. A relationship of this kind is called a one-to-many relationship. Here the entity City  is located on the ONE  side of the relationship and entity Student  on the MANY  side. We also use other names: Student  represents the child entity and City  represents the parent entity .

When we define a relationship in a CASE tool, an attribute is automatically added to the entity on the “many” side, containing the value of the primary key of the other entity. Thus we have added a foreign key  to the entity attributes. It will serve as a pointer linking the rows on the “many” side with one row on the “one” side of the relationship.

In our example MS Visio has automatically created in the Student  entity the attribute IdMiasto  (labeled FK1 - foreign key), defining the relationship between the instances of the Student  entity with the instances of the City  entity.

# Working with MS Visio

In the previous section we discussed the concept of an entity and an entity relationship. I tried to convey the meaning of these terms. However, as mentioned above, the practical process of creating the entity relationship diagrams is made using specialized CASE tools. In this section we present the Microsoft CASE tool called MS Visio. We discuss here a version of the MS Visio for Enterprise Architects included in the MS Office 2003, because it is the last version of this program equipped with full functionality we expect from a CASE program. We will also present the newer version MS Visio 2007, unfortunately already deprived of some of its functionality, but sufficient for the learning purposes within the WSI course. The MS Visio 2010, available for the students under the academic license at [https://software.pjwstk.edu.pl/](https://www.google.com/url?q=https://software.pjwstk.edu.pl/&sa=D&source=editors&ust=1714064099735460&usg=AOvVaw3-AYW-o4-iAxLXfCOi3vwh) , is almost identical. The latest version of MS Visio 2013, on the other hand, is not suitable for the tasks we will deal with during this course.

Below are short videos in the MP4 format presenting the basics of working with the MS Visio. These materials are not intended to teach you every detail of creating the entity relationship diagrams, but rather to demonstrate how to use this tool.

### Running MS Visio 2003

In links below are video files which present MS Visio use, which should be attached to the lectures.  
Z:\\PBD\_nagrania\\Uruchomienie Visio

### Running MS Visio 2010

Z:\\PBD\_nagrania\\Uruchomienie Visio 2010

### Creating entities with MS Visio

Z:\\PBD\_nagrania\\Tworzenie encji w MS Visio

### Creating relationships with MS Visio

Z:\\PBD\_nagrania\\Tworzenie związków w MS Visio

### But what do we need these diagrams for?

In this chapter we presented the process of designing a database by creating the entity relationship diagrams. We have already said that the entities and their relationships can be thought of as models of some parts of the real world, but at the same time they represent the structure of the future database. But do we obtain from such diagrams something more than just a convenient image of the database structure? Graphic representation of the tables and relationships makes it easier to work with the future database, but is it everything we get? It turns out that the CASE tools have one more (very important) function. Namely, they can generate a DDL script which creates a database. What is a DDL (“Data Definition Language”) script? This is a set of SQL text commands, and in fact also a subset of commands used for creating the database objects. The database server is able to interpret these commands and create a database whose structure has been designed in the form of the entity-relationship diagram.

Unfortunately, among the tools implemented by the currently available student version of the Visio 2010 there is no DDL generation tool. It is included in the MS Visio for Enterprise Architects (Visio 2003) and is available on the computers in PJATK laboratory. MP4 video below shows how to generate the DDL script of the entity relationship diagram in the MS Visio 2003.

### Generating DDL script from the MS Visio

Z:\\PBD\_nagrania\\Generowanie skryptu DDL z MS Visio

### Other notations used for creating entity relationship diagrams

As previously mentioned, there is no standard for the notation used in the entity relationship diagrams. You could say that every CASE tool introduces its own notation, although most of them are quite similar. However, the notation used in MS Visio (called relational) is quite distinct and rare. Below we present a few examples of the most commonly used notations. The first diagram was made in a relational notation, while the other ones were created in various notations different from the one used in MS Visio.

### Relational notation

We first encountered the relational notation while working with MS Visio - this is the basic notation used in this tool. The designations used are simple, yet the diagram contains little information in the graphic layer.

![](images/image53.png)

### IDEF1X notation

The same diagram made in MS Visio, but with the IDEF1X notation. Try to figure out what the signs mean. They will be thoroughly discussed in a different course called “Relational Databases”.

![](images/image2.png)

Once again, the same diagram made in the IDEF1X notation, but with a different CASE tool called Erwin. Unlike the previous ones it can represent an ambiguous relationship (many - to - many) on a diagram without decomposing it into two unambiguous relationships and an associative entity. Of course this will have to be done later at the implementation stage.

![](images/image6.png)

### Crow’s Foot notation

The name of this notation comes from the symbol of the "many" side of the relationship - the symbol of three lines which is similar to the imprint of a crow’s foot. This example was done using the IBM's Relational Data Architect.

![](images/image64.png)

# Summary

This lecture is an introduction to the design process of an information system, with particular emphasis on the design of the database. We emphasized the role of the CASE tools in the design process as well as the role of the entity-relationship diagram as a model of the future database. We presented and discussed the basic ERD elements: the entity, the attribute and the relationship and showed examples of the simple entity relationship diagrams in several different notations. The whole issue of the relational database design will be discussed in detail in a different course called “Relational Databases”.

# 4 Lesson V – SQL - relational database language

15.03.2024 11:45 | Number of chapters: 10

# New skills and knowledge

One of the Codd’s rules defining the requirements for the relational database model was introducing a complete language which, independently from other programming languages, would perform all the database operations. The Structured Query Language (SQL) was created in order to meet these requirements. The basics of this language will be presented in this lecture. After this lecture student should be able to: write simple commands for data reading, add a new record to the table, change data of the existing table. The student should also know the basic syntax of the commands which create and alter the table structure.

In the current lecture we will discuss the following topics:

1.  The origins of SQL
2.  The structure of SQL
3.  Data types according to the SQL standard
4.  The SELECT commands,
5.  The commands from the DDL and DML sublanguages.

Remember that the aim of this lecture is to give an overview of the topic. The details will be discussed more thoroughly in the courses called: Relational Databases and Database Systems.

### Learning outcome

*   The student can explain the role of the SQL language as a specialized language for relational databases, which is not a programming language
*   The student can name 4 sublanguages of SQL and can describe their application
*   The student can distinguish the data types provided by the language standard and point out the differences in their implementation in various database servers
*   The student knows how to use the basic version of the SELECT command together with the FROM and WHERE clauses and can write a simple SELECT command in a known and simple data structure made of at most two tables.
*   The student can use the DDL commands (CREATE, ALTER, DROP) and the DML commands (INSERT, UDATE, DELETE) in their basic scope.

# The origins of the SQL language

Earlier database models, such as the network or hierarchical models, were based on the notion of a file as a named collection of records. The traditional programming languages, like COBOL, PL/I or C, were sufficient for operating on these data structures. The appearance of the relational data model (Edgar C. Codd “Relational model of data for large shared data banks”, 1970) sparked the interest in specialized, “relational” languages which were supposed to implement the theoretical framework in concrete applications. The most advanced research was conducted in IBM, partially due to the fact that the relational database concept emerged in the IBM labs in San Jose. In 1974 the group led by Donald Chamberlin presented the Structured English Query Language, also known under the acronym SEQUEL. Its first, prototype implementation created by IBM appeared in 1974-1975 and was known as the SEQUEL-XRM. It was followed by another version of the language called SEQUEL/2 and in 1977 the SYSTEM R implementation was launched. The name SEQUEL/2 had to be dropped because of legal issues (the name was a trademark of a British aircraft company De Haviland) and the language was renamed SQL. The name soon lost its original meaning as an abbreviation and became the name of a new language.

The ANSI (American National Standards Institute) standard for SQL, which appeared in 1986, was based on the IBM dialect. The ANSI standard was adopted later by ISO (International Organization for Standardization) as the world standard in 1987. Since then SQL has been standardized a number of times and implemented in many DBMS with varying degree of ANSI standard conformity. To some extend each of these implementations uses its own dialect which differs in details from all others, although all of them remain similar in basic constructions.

The most popular DBMS’s implementing the relational database model are ORACLE, DB2, PostgresSQL, MS SQL Server, Sybase, MySQL. Each of them implements its own dialect of SQL, none of them satisfies all of the ISO standard requirements and no 2 are identical.

In the next part of the lecture and in the examples we will mostly work with the Microsoft implementation from the MS SQL Server 2008 R2 (called simply MS SQL further on). For comparison we will sometimes compare it to the ORACLE 11g implementation (ORACLE in short). If we do not discuss differences between the two, then this means that the differences are either insignificant or non-existent.

# The SQL language structure

Due to its name the SQL language is described as a QUERY database language. It is a simplified description, as this language also contains database COMMANDS. In this lectures QUERIES and COMMANDS will be used as synonyms.

The SQL is a declaratory language, which means that DBMS decides about the physical details of storing and operating on the data. The SQL is used only for database operations. Strictly speaking it is not a programming language, as it does not include the necessary programming structures (variables, conditional instructions, loop instructions). However the SQL implementations usually contain these structures because of their usefulness. We can thus distinguish the pure SQL and its procedural extensions. We will discuss two of those extensions further on: the PL/SQL (the procedural language of the ORACLE DB) and Transact SQL or T-SQL (the procedural language of MS SQL Server).

The SQL language structure.  
Queries – we distinguish four subsets of commands:

*   SQL DML  – Data Manipulation Language
*   SQL DDL  – Data Definition Language
*   SQL DCL  – Data Control Language
*   SQL DQL  – Data Query Language

### DQL – Data Query Language

The set of commands for reading the data from the database. All commands begin from the SELECT word and their execution doesn’t influence the state of data.

### DML – Data Manipulation Language

The set of commands responsible for data operations.

*   INSERT – entering new data (records) into the database
*   UPDATE – updating (changing) the existing data
*   DELETE – deleting data (records) from the database

### DDL – Data Definition Language  
The set of commands responsible for manipulating database objects.

*   CREATE – creating a new database object
*   ALTER – changing the structure of the existing object
*   DROP – deleting an existing object from the database

### DCL – Data Control Language  
The set of commands responsible for granting access to the database operations.

*   GRANT \- granting access to a given database objects
*   REVOKE – revoking access to a given database objects
*   DENY – denies operations on a database object

### Control questions

Is it possible to change the database structure using SELECT instruction?

No

Yes

Check the answer

Which of the commands can alter data recorded in a database?

SELECT

ROLLBACK

UPDATE

GRANT

DELETE

# Data types in SQL

As we have mentioned, in the relational data model it is assumed that each column of a data table contains data of a fixed type. The SQL standard defines the basic data types, but the implementations sometimes depart from the standard in details.

### The SQL general data types

*   CHARACTER (n)  – fixed length string of characters
*   CHARACTER VARYING  – variable length string of characters
*   INTEGER  – an integer number
*   NUMERIC  - floating point number

Each implementation follows the general guidelines of the SQL standard, but each of them does it in its own way. We present below the data types for MS SQL Server 2012 and ORACLE 11g. Note that the MS SQL 2012 version contains a number of significant changes (not only concerning data types) in comparison to versions 2000 and 2005. We will not discuss data types which are not contained in the standard and are unimportant for us in this lecture, like BLOB or ROWID and other data types which are not so much used on the elementary level. Students interested in this topic may look it up on the software producers webpages ( [http://technet.microsoft.com](https://www.google.com/url?q=http://technet.microsoft.com/&sa=D&source=editors&ust=1714064099748657&usg=AOvVaw3-td0it3Sb5rINyc_K-Pdi) , [http://docs.oracle.com](https://www.google.com/url?q=http://docs.oracle.com/&sa=D&source=editors&ust=1714064099749084&usg=AOvVaw12DDmA9QTBTyqtLSMwcJ8r) ).

### Names of the SQL data types  
Character string data types

*   CHARACTER(n)  – string of fixed length n
*   VARYING CHARACTER(n)  – string of variable length, with maximum length n
*   BIT(n)  – string of a fixed bit length n
*   VARYING BIT(n)  - string of variable bit length, with maximum length n

Integer numeric data types

*   INTEGER – decimal or binary integer, signed
*   SMALLINT \- decimal or binary integer, signed

Floating point numeric data types

*   NUMERIC(p,q)  – signed decimal number made of p digits in total, with the decimal point after q digits counting from right
*   DECIMAL(p,q)  – signed decimal number made of p digits before and q digits after the decimal point
*   FLOAT(p)  – floating point number (written in exponential notation)

Time and data types

*   DATE
*   TIME
*   TIMESTAMP
*   INTERVAL – specifies a time interval

  
The descriptions above have been taken from the standard description. In practice we work with types implemented by each database server. They differ from the standard in details. Therefore before you start working on a database on a given server you should find out what data types it supports. At the end of this lecture we give a detailed description of data types used by ORACLE and MS SQL.

# An example of the database – Emp, Dept and Salgrade tables

All examples of the SELECT command included in this lecture will be presented using the database consisting of the three tables: EMP , DEPT and SALGRADE , whose structure is presented in the graph below.

![](images/image66.jpg)

This simple graph presents a simplified structure of a company. The EMP table stores the company’s employees data, DEPT table stores the departments’ data and SALGRADE table describes the salary structure of the company.

The EMP table

*     
    Empno Int Primary Key -  employee’s number
*     
    Ename Varchar - employee’s surname
*     
    Job Varchar - employee’s position
*     
    Mgr Int Foreign Key - the employee supervisor’s number (a recursive relationship)
*     
    Hiredate Date - date of employment
*     
    Sal Int - salary (monthly)
*     
    Comm Int - the provision (annual)
*     
    Deptno Int Foreign Key - employee’s department number

![](images/image79.jpg)

The DEPT table

*     
    Deptno Int Primary Key - department number
*     
    Dname Varchar - department name
*     
    Loc Varchar - department location (the city)

The SALGRADE table

*     
    Grade Int Primary Key - classification number
*     
    Losal Int - the group’s minimum salary
*     
    Hisal Int - the group’s maximum salary

![](images/image73.jpg)

I would like to point out that the SALGRADE table is not connected via a primary-foreign key pair with EMP and the pair Losal \- Hisal is just the salary brackets. In order to see in which group somebody’s salary (SAL) lies we need to find out into which Losal \- Hisal bin the salary fits.

# SELECT instruction

The SELECT instruction is used for reading data recorded (or not recorded…) in the database, without changing its structure or content.

The SELECT instruction consists of a few “clauses” appearing in a strictly specified order and beginning with a keyword. The first clause, beginning with the keyword SELECT, and second clause, beginning with the key word FROM, are obligatory and therefore they must appear in the command syntax at least once (they can appear many times).

The SELECT instruction defines:

*     
    the sources for data reading in the database,
*     
    the conditions the data must satisfy in order to appear in the result,
*     
    in what form the result should be returned to the user.

Most language standards require SELECT (and every other instruction) to end with a semicolon “;”, although MS SQL treats this requirement as optional.

The SELECT instruction syntax

SELECT \[ DISTINCT \] wyrażenie (, ...)

FROM nazwa\_tabeli (, ...)

\[ WHERE warunek\]

\[ GROUP BY wyrażenie (, ...)\]

\[ HAVING warunek\]

(...)

\[ ORDER BY wyrażenie (, ...)\];

Every clause (except ORDER BY ) can appear in the instruction syntax more than once. SELECT and FROM clauses must appear at least once.

### SELECT instruction SELECT clause

  
SELECT clause structure  
  
  
  
SELECT \[ DISTINCT \] expression (,…)  
  
FROM table\_name (,…)  
  
(…);

The SELECT clause defines the data which are going to be read from the database and the way they will be presented. It can involve the column names, expressions (also referring to the column names) and constants unrelated to the database content. The expressions should be separated by commas. The column names should be prefixed with the table name:  
  
  
  
Table\_name. Column\_name  
  
  
  
If the column names are unambiguous then the name of the table preceding column name can be omitted. By unambiguous we mean here that the column name appears only in one table among those from which SELECT is reading the data.

### SELECT instruction FROM clause

The FROM clause defines the sources from which the data will be read. These can involve tables, views and other SELECT instructions. The names of tables, views and SELECT instructions (written in bracket) are separated by commas. In this lecture we will only discuss how to read data from a single table. Reading data from a view is not much different.

### SELECT instruction – elementary examples

  
We want to list the names, salaries and positions of the company employees:  
  
  
  
SELECT Ename, Sal, Job  
  
FROM Emp;  
  
  
  
The result is shown in the table below:

![](images/image101.jpg)

  
If we want to see the whole table we use:  
  
SELECT \*  
  
FROM EMP;  
or  
TABLE EMP;  
  
The last instruction is contained in the SQL standard, but not implemented in either ORACLE or MS SQL Server.

### SELECT instruction ORDER BY clause

  
The query’s results can be sorted either as ASCENDING (the default ordering, also abbreviated as ASC ) or DESCENDING ( DESC ).  
  
  
SELECT \[ DISTINCT \] phrase \[\[ AS \] alias\] (,…)  
  
FROM table\_name  
  
\[ WHERE condition\]  
  
ORDER BY phrase1 \[ ASC | DESC \] (,…);  
  
  
  
The ORDER BY clause can occur only once and it should always be placed at the end . The clause’s list can include expressions, also involving table names and their aliases as well as expression numbers in the order of their occurrence in the SELECT command.  
  
Sorting can be done according to more than on expression. The sorting hierarchy results from the order of the expressions on the list.  
  
The ASC word (pointing the default sorting direction) can be omitted in command’s syntax.

### SELECT instruction WHERE clause

  
The WHERE clause is the third clause in the SELECT syntax. It is optional - it does not have to appear. It allows to limit the records returned by the SELECT command using a logical condition. Only those records for which the condition is TRUE are returned, those with FALSE or NULL are eliminated from the result.  
  
  
  
  
Example.  
  
We want to list the names, positions and salaries of all the employees from department 10.  
  
  
SELECT Ename, Job, Sal  
FROM Emp  
WHERE deptno = 10;  
  
  
The command’s result is presented below:

![](images/image9.jpg)

### SELECT instruction – reading from multiple data sources

  
According to the SQL syntax if the data is supposed to be read from multiple tables (sources), the names of the tables, separated by commas, need to appear in the FROM clause.  
  
  
  
  
This was a theoretical introduction. Let us now see how it works in the SQL language. We will begin with an experiment. We will read the result below in order to find out the names and locations of departments for every employee.  
  
  
  
  
SELECT Ename, Dname, Loc  
  
  
FROM EMP, DEPT;  
  
  
  
  
The result is a bit surprising. There are 14 records in the EMP table and 4 records in the DEPT table and the query’s result includes 56 records. Let us analyze the result in more detail. According to this result each employee’s name appears 4 times in the table and is linked with the name and the location of every department. Thus, every department is displayed together with all the names of the employees. As a result we got the Cartesian Product of on the sets of rows of EMP and DEPT .  
  
  
  
  
Is this result correct? No, although it contains true information. The true records are those which line the employee’s name with the name and location of the department where he or she works. Since in our result all employees’ names are linked with all departments and locations we can be sure that the result contains the correct records as well. We just need to find them.  
  
  
  
  
Every record in the DEPT table includes the primary key in the form of the number in the Deptno column. If the employee works in a department then the record in the EMP table contains the Deptno value (foreign key) which points to the department in which he or she works. So if we want to read only the correct records we need to include the following condition ensuring that the Deptno value is the same in both tables:  
  
  
  
  
EMP.DEPTNO = DEPT.Deptno  
  
  
  
  
This way the SELECT command will omit those records for which EMP.Deptno <> DEPT.Deptno  or EMP.Deptno is NULL .

### Control questions

Which clause defines the data sources (tables) which should be read by the SELECT command?

SELECT

FROM

WHERE

ORDER BY

Check the answer

How many times can the clause ORDER BY appear in the SELECT command?

It needs to appear exactly once.

It can appear multiple times.

At most once.

Check the answer

What will be the number of records for the command SELECT \* FROM T1, T2; where T1 and T2 are the tables names including respectively 5 and 3 records?

0

3

5

15

Check the answer

What will be the result of the command below? SELECT ename FROM emp WHERE 1=1;

Empty set.

All names read from the EMP table.

Check the answer

What will be the result of the command below? SELECT dname FROM dept WHERE deptno = deptno;

Names of all departments read from the DEPT table

The command’s syntax is incorrect

The set is empty

Check the answer

If the SELECT command contains more than one table in the clause FROM:

The command’s syntax is incorrect.

The user should define a way the tables should be linked

Check the answer

# DDL – Data Definition Language

DDL is a subset of the SQL language which is responsible for database object operations such as creating, deleting and changing their structure. The DDL language includes three sets of commands beginning with the key words:

*   CREATE – create new object
*   DROP – delete object
*   ALTER – change the structure of the object

By a database object we mean tables, views, indices, procedures, triggers, databases and other objects. In this lecture we will only discuss operations on tables and integrity constraints. The concept of a view will be presented in the next lecture. The SBD course (another database-related course) will also discuss procedures.  
  
I would like to point out that the set of objects for which one can use the command CREATE depends on the implementation.

### Creating a new table

Commands for creating a new table:  
  
CREATE TABLE  table\_name (  
Column\_name\_1 Data\_type \[Integrity\_Constraints\],  
Column\_name\_2…  
);

The table name  cannot exceed 30 signs ( ORACLE ), 128 signs ( MS SQL Server ).  
The column number  is also limited – up to 1000 ( ORACLE ), MS SQL Server  assumes that the table row length does not exceed 8060 bytes.  
  
The names of the tables, columns and other objects can only contain Latin letters, underscores and digits. Some dialects allow also letter with diacritics or spaces, but it is recommended not to use them.

### Creating a table – the integrity constraints

One way to introduce the integrity constraints, called the declaration in a single line, has been presented below:  
  
CREATE TABLE  table\_name (  
Column\_name\_1 Data\_type Integrity\_constraints,  
…);Example:  
  
CREATE TABLE  Person (  
PersonId INT PRIMARY KEY ,  
Name VARCHAR (20) NOT NULL ,  
Surname VARCHAR (50)  
);  
  
Constraints are declared in the same line in which their column has been declared. Note however that this is not always possible.  
  
Another method is to declare constraints “outside the line” using the CONSTRAINT keyword. It allows to name the constraint:  
  
Example:  
  
CREATE TABLE  Person(  
  
  
PersonId INT ,  
Name VARCHAR (20),  
Surname VARCHAR (50),  
  
CONSTRAINT PK\_Person PRIMARY KEY  (PersonId),  
  
CONSTRAINT UQ\_Person UNIQUE (Surname)  
  
);  
  
  
  
If the constraints are not explicitly named, the DNBS will name them automatically. The examples were presented in the MS SQL Server  dialect. The ORACLE syntax is basically the same, except for the data type names.

### Changing the table scheme – the columns

  
Adding a new column to an existing table, changing the column’s data type, deleting the column  
  
  
  
  
MS SQL Server and Standard  
  
  
ALTER TABLE   Table\_name   ADD column\_name Data\_type;  
  
  
ALTER TABLE   Table\_name   ALTER COLUMN   column\_name Data\_type;  
  
  
ALTER TABLE   Table\_nsme   DROP COLUMN   column\_name;  
  
  
  
  
ORACLE  
  
  
ALTER TABLE   Table\_name   ADD (column\_name Data\_type);  
  
  
ALTER TABLE   Table\_name   MODIFY (column\_name Data\_type);  
  
  
ALTER TABLE   Table\_name   DROP COLUMN   (column\_name);  
  
  
  
  
The brackets are optional in the ORACLE syntax  
  
  
  

### Deleting the table

DROP TABLE   table\_name;

If other tables have foreign keys referring to the table we want to drop and no referential action other than ON DELETE NO ACTION has been declared then the operation will fail.

### Control Questions

Command ALTER is used for:

Deleting the table from the database

Adding a new table to the database

Changing the data in the existing table

Changing schema (structure) of an existing table

Delete the data from the existing table

Check the answer

The word CONSTRAINT for the instruction CREATE TABLE:

Is optional

Is used for defining the integrity constraints

Must appear if we want to name the integrity constraints

Should not be used, as DBMS gives names for constraints

Check the answer

There are two tables in the database: T1 and T2. T1 includes the column t2 which is a foreign key from table T2. There are records in the T1 table which contain non-null values in t2. What will be the result of the command below? DROP TABLE T2;

Table T2 will be deleted

Records in T2 not referred to in T1 will be deleted.

The command will return an error.

Check the answer

# DML – Data Manipulation Language

  
The DML is the subset of the SQL language commands responsible for the operations on the database structure. These are: adding new records to the tables, modification of the existing data and deleting the records from the tables. Three kinds of commands are used:  
  
  
  
  
INSERT – add new record to the table  
  
DELETE – delete an existing record  
  
  
UPDATE – change data in an existing record  
  
  
  

### Inserting data into the table

Basic (full) syntax:

INSERT INTO  table\_name (list of column names)

VALUES (values\_list);

Simplified syntax:

INSERT INTO  nazwa\_tabeli

VALUES (values\_list);

The number, types and order of the columns in the INSERT clause should match the list of values in the VALUES clause. The only columns which may be omitted are those which allow the NULL value, those which have a DEFAULT value defined, those whose value is calculated or realized by the auto-numbering mechanisms.

If we use the simplified syntax then the list needs to match the order and the types of data from all table columns, just like it was defined in the CREATE TABLE  command.

Example:

INSERT INTO  Emp (empno, ename, job, sal, deptno, comm)

VALUES (1001, ‘ WHITE ’, ‘ SALESMAN ’, 2500, 20, NULL);

MS SQL Server allows inserting more than one record in the INSERT operation:

INSERT INTO  Emp (empno, ename, job, sal, deptno, comm)

VALUES (1002, ‘ GREEN ’, ‘ CLEARK ’, 3100, 10, NULL),

(1003, ‘ YELLOW ’, ‘ MANAGER ’, 2500, 10, 200),

(1002, ‘ PINK ’, ‘ SALESMAN ’, 2200, 30, NULL);

This solution is not implemented by the ORACLE . Values in the VALUES clause   can include: the constants, the functions or the phrases.

The source for the INSERT instruction can be the SELECT instruction reading the values from the other tables. The SELECT instruction can also include the phrases.

Example:

INSERT INTO  Salary\_Budget (Year, Month, Sum)

SELECT 2011, 12, Sum (sal + NVL (comm, 0))

FROM EMP

In this case we already have the Salary\_Budget  table, and its columns’ structure is compatible with the SELECT instruction reading records, which will be written to the Salary\_Budget  table.

### Modifying the data in the existing table

UPDATE     table\_name

SET     column\_name = expression1 , ...  

\[ WHERE   condition\];

eg. to increase the salary of all salesmans by 10%:

UPDATE Emp

SET Sal=Sal\*1.1, Comm = 1000

WHERE Job = ‘ SALESMAN ’;

Omitting the WHERE condition will cause the modification of the data in all table records.

### Deleting data from the table

DELETE FROM table\_name

\[ WHERE condition\];

e.g. in order to delete all employees without the specified position:

DELETE FROM Emp

WHERE Job is NULL

Omitting the WHERE condition will cause deleting all the records from the table.

### Control Questions

Will the following command be executed: INSERT INTO emp (ename, sal, job) VALUES (‘PINK’, 1200, ‘ROBBER’);

No, because the company does not employ criminals.

No, because not all columns of EMP are filled

No, because we have not assigned any value to the empno column

Check the answer

Will the following command be executed: DELETE FROM dept;

Yes, all records from the dept table will be deleted.

No, because some of the rows of DEPT are referred to by rows of EMP.

Check the answer

The SALGRADE table contains 5 rows identified by the values 1-5 in the GRADE column. How many rows the will be changed by the command UPDATE salgrade SET Losal = Losal + 50 WHERE grade!=10 ?

All rows.

None.

One.

Check the answer

# Basic data types in the MS SQL Server and in the ORACLE MS SQL Server  
Exact numeric types

*   INTEGER or INT a sign integer type; range from-2^31 to 2^31
*   NUMERIC (p,\[s\]) or DECIMAL (p,\[s\]) a floating point number, where p defines signs’ number, s the number of signs after the comma; range from -2^31 to 2^31
*   MONEY a floating point number type representing the currency values; range from -922 337 203 685 477.5808 to 922 337 203 685 477.5807

Approximate numeric types

*   FLOAT (n) approximate floating point number, range from -1.79E+308 to -2.23E-308, 0 and from 2.23E-3+8 to 1.79E+308,
*   REAL approximate floating point number, range from -3.40E+38 to -1.18E-38, 0, 1.18E-38 to 3.40E+38.

Date and time types

*   TIME , format: hh:mm:ss\[.nnnn\], range 0.00 – 23.59.59.9999
*   DATE , format: YYYY-MM-DD; range: 0001-01-01 to 9999-12-31
*   DATETIME , fornat: YYYY-MM-DD hh:mm:ss; range: 1753-01-01 - 9999-12-31

Character strings:

*   CHAR (n): string of constant length, up to n characters; format: 1-8000 ASCII characters
*   VARCHAR (n): string of variable length, up to n characters; format: 1-8000 ASCII characters
*   nCHAR (n): string of constant length, up to n characters; format: 1-4000 UNICODE characters
*   nVARCHAR (n): string of variable length, up to n characters; format: 1-4000 UNICODE characters
*   VARCHAR (max): string of variable length; format: ASCII characters up to 2GB.

ORACLE

Exact numerical types

*   NUMBER (p,s): integer or floating point number, where p – maximal total number of digits (up to 38), s – number of digits after the decimal point
*   INTEGER or INT : integer, same as NUMBER(38)

Date and time types

*   DATE : stores the year, month, day, minutes and seconds

Strings

*   CHAR (n): string of constant length, up to n characters; format: 1-2000 ASCII characters
*   VARCHAR2 (n): string of variable length, up to n characters; format: 1-4000 ASCII characters
*   nCHAR (n): string of constant length, up to n characters; format: 1-2000 UNICODE characters
*   nVARCHAR2 (n): string of variable length, up to n characters; format 1-4000 UNICODE characters

# Summary

In this lecture, the last one dedicated to the relational databases, we have discussed the origins of the SQL language and its structure. We have given only an overview of SQL, enough to present what the language can be used for and what its basic instructions are. We have omitted a number of details, so the content of this lecture should be considered an introduction to the topic of SQL, which in turn will be discussed in greater detail in the two next semesters during the RBD and SBD courses.

# [5](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62112/chapter/25920&sa=D&source=editors&ust=1714064099790569&usg=AOvVaw0Ucv6_XbWLfxOobO1zIUG6) [Lesson XI - Structure of a worksheet (spreadsheet), formatting and data entry in Excel](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62112/chapter/25920&sa=D&source=editors&ust=1714064099790957&usg=AOvVaw3YtUTMPJF3m4cgsjEsmjoU)

[15.03.2024 11:46 | Number of chapters: 6](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62112/chapter/25920&sa=D&source=editors&ust=1714064099791408&usg=AOvVaw2mULnL_-4ncgsCnjVyEnYp)

# Introduction  
In this lesson you will learn about the structure of an Excel worksheet and the basics of formatting and data entry. The application is widely used in companies and institutions, as well as by home users. It is mainly used to make calculations (e.g. expenditures) listed in a tabular form. In this use there are applied many logical functions (Lesson 3) mathematical, financial and database functions that are available in the program. Of a great importance is also semi-automatic copying of the created formulas using different variants of addressing (relative addressing, absolute addressing, mixed addressing). Excel is also used to create many types of charts (which we will learn about in lesson 2)which are useful e.g. in physics, mathematics and economics. It also contains a system of reports compilation in which the so-called pivot tables are used, used in the performance of business intelligence (Lesson 4).

### Learning outcome  
On having mastered the material of this lesson, the student should be able to easily enter and format data in Excel worksheets, make calculations (using operators and functions) and use semi-automatic duplication of the created formulas using different variants of addressing (relative addressing, absolute addressing, mixed addressing).

# Structure of an Excel worksheet (spreadsheet) and entering and selecting data

### Structure of a worksheet

  
Each document in Excel consists of worksheets .

An Excel worksheet (spreadsheet), is a two-dimensional grid with columns and rows . The column names are letters of the alphabet (A, B, C, …)and the rows are numbered chronologically (1,2,3 and so on).

  
The worksheet consists of cells i.e. small boxes, into which we can enter data. Each cell has its own address. We create it giving the name of the column and of the row in which the cell is located.

  
In the picture below cell A1 is selected.

![](images/image107.png)

  
The address of a cell is always displayed on the left of the Formula Bar

### Data entry

  
In Excel, we enter data directly into the cells. We click in the selected cell and begin typing. Entered digits will automatically move to the right side of the cell, and the text to the left. If we want to enter a decimal, we separate the integer from tens by a comma (never a dot!). This applies when we use the operating system with the Polish regional settings.

![](images/image62.png)

### Selecting cells

  
Before copying or formatting cells we have to select them.  
The cells can be selected as follows:

*     
    to select one cell click in it
*     
    To select one or more columns of cells, click on the column letter(s).
*     
    To select one or more rows of cells, click on the row number(s)
*     
    To select a group of contiguous cells, click in a corner cell and, with the left mouse button depressed, drag the cursor horizontally and/or vertically until all of the cells you want selected are outlined in black.
*     
    To select multiple cells that are not contiguous, press and hold the Ctrl key while clicking in the desired cells.

### CHECKING THE KNOWLEDGE:

In the picture below a cell is selected:

B2

2B

Check the answer

![](images/image31.png)

# Formatting cells

In this lesson we will discuss the issue of cell formatting.

### Basic formatting.

  
There are two ways of formatting the contents of the cells. The first is to select the cells and in the formatting window choose the "Main Tools" tab, then we can change the visual and aesthetic part of the worksheet by selecting the appropriate formatting category tab from the existing formatting group ("Font", "Alignment", "Number" etc.)

![](images/image97.jpg)

  
The second way is to right-click in the selected cells and select Format Cells window. There are different formatting options available on different tab groups.

  
The first tab is Number and contains categories for the type of data that is in the cell. Select one of these to set the appropriate cell format.

![](images/image21.jpg)

  
Applying different number formats, you can change the way of displaying numbers without changing them. The format of a number does not affect the actual value of the cell used in Excel to make calculations.

This value is displayed in the formula bar .

![](images/image17.png)

  
The following list contains information about available formats of numbers in the Number tab.

![](images/image10.png)

![](images/image51.png)

![](images/image36.png)

![](images/image54.png)

![](images/image78.png)

![](images/image57.png)

![](images/image12.png)

![](images/image13.png)

![](images/image108.png)

![](images/image27.png)

  
On the Alignment tab we set Orientation and Text Alignment

![](images/image25.jpg)

  
On the Font tab we set: Font name, Font style, Size, Color and whether you want the text to be underlined.

![](images/image45.jpg)

  
The fourth tab is Border. The Border tab provides a variety of border styles, To apply borders select the cells and then right-click and select Format Cells → Border. Select the border style and color first; then select the side or sides of the cell to receive the border.

![](images/image44.jpg)

  
To change the background color of a single cell or range of cells, select Format Cells → Fill or Patterns depending on the version of Excel.

![](images/image1.jpg)

### CHECKING THE KNOWLEDGE:

![](images/image104.png)

1\. What types of formatting were used in the above picture:

Numbers -> Percentage, Font -> Arial

Numbers -> Currency, Border -> outline, Fill

Numbers -> Fraction, Border -> outline, Fill

Check the answer

### Conditional Formatting

  
Conditional formatting allows you to automatically format cells, when they fulfill a certain condition. We can e.g. change the font color depending on what grade point average the student has obtained and thus select students with an average of more than 4.75.

  
To apply conditional formatting should be:

*     
    select the cells you want to format
*     
    select Format → Conditional Formatting
*     
    determine what condition are to be fulfilled
*     
    set the appropriate formatting
*     
    if there are more conditions, click the Add button
*     
    If all conditions have been added, click the Format button

![](images/image76.jpg)

### Example

  
There is often a need to highlight in the table some maximum or minimum values. This can be done by sorting the table, however, Microsoft Excel 2013 allows you to award the largest or smallest value without sorting.

At XYZ company an employee has to highlight the top 10 sales results.

First, you select the cells whose fragments you want to highlight. Then you choose Conditional Formatting in the Main Tools . In the menu that appears, you choose the option Top/Bottom Rules .

![](images/image81.jpg)

Click the Top 10 elements ... and in the window that appears, choose a value of 10 and the kind of distinctions.

![](images/image86.jpg)

At the same spreadsheet denote the color blue 30% of the smallest value. You choose the option Bottom 10% ... in the menu Top/Bottom Rules . In the window, enter the value 30, and select the desired way of formatting. Since we do not have to choose blue color fill, select Custom Format  ...

![](images/image37.jpg)

![](images/image7.png)

In the Font tab, Color option select a bright, visible on a dark blue background color. Then go to the Fill tab, where you choose the right color for the background.

![](images/image14.jpg)

After approval of the changes by pressing OK you get a fully formatted spreadsheet.

![](images/image24.jpg)

# Calculations, operators and functions

### Performing calculations

  
Calculations performed using Excel formulas. To enter a formula proceed as follows:

*     
    click on the cell in which the formula is to be entered
*     
    enter the formula (action) starting from the "="
*     
    type the formula using cell references
*     
    approve the formula of the Enter key

  
When you perform all calculations in Excel it is recommended to use cell references. This makes it easier and faster to make adjustments, and speeds up the job when we have a few similar calculations.

The formula appears in the formula bar , and the result in an   active cell .

![](images/image83.png)

  
If you want to make amendments to the previously entered formula, click the cell in which the formula appears and make changes in the formula bar.

  
The formula can be copied between the cells in the example below to get, in rows two and three, the product from columns A and B enough to "catch" the element and stretch it down. More advanced rules to copy formulas will be presented in point 5.

![](images/image48.png)

  
The cells can enter a formula using mathematical signs and pointing to the cells to be used in these calculations.

  
It is important to introduce the formulas which begin with the =

  
A collection of the most important operators and functions Excel spreadsheet:

|     |     |
| --- | --- |
| Operator | Explanation |
| +   | Adding |
| \-  | Subtraction |
| \*  | Multiplication |
| /   | Divide |
| \=  | Equal |
| <=  | Less than or equal |
| \>= | Greater than or equal |
| <>  | Different |
| ^   | Exponentiation |
| SQRT(x) | Returns the value of a positive square root |
| POWER(number;power) | Raises the number to the power |
| SUM() | Returns the sum the from the cells or range in brackets. Example SUM(A1:A10) or SUM(A2;D3;G5) |
| PRODUCT() | Returns the product the from the cells or range in brackets. Example PRODUCT(A1:A10) or PRODUCT(A2;D3;G5) |
| SUMSQ () | Displays the sum of the squares of the cells or range in brackets |
| EXP(x) | Returns e raised to the power of number. The constant e equals 2.71828182845904, the base of the natural logarithm. |
| LN(x) | The natural logarithm of x. x > 0 |
| Log10(x) | Displays the logarithm |
| Log(number, base) | Returns the logarithm of the specific basis |
| PI() | Returns the value of π |
| RADIANS(angle) | Converts degrees to radians |
| DEGREES(kąt) | Converts radians to degrees |
| Sin(), Cos(), Tan() | Sine, Cosine, Tangent (function arguments must be given in radians) |
| Ctg = 1/TAN() | Cotangent |
| FACT (n) | n!, n > 0 |
| COMBIN(n;k) | Displays the number of combinations of k - of element of a set of n - element |
| COUNTIF(range, criteria) | Counts the number of cells within the range that meet the given criteria |
| SUMIFS(sum\_range, criteria\_range1, criteria1, \[criteria\_range2, criteria2\], ...) | Adds all of its arguments that meet multiple criteria |

### Examples

  
We already know the basic operators and functions of Excel. Now let us discuss a few practical examples:

![](images/image50.png)

  
In Excel to calculate the root of grade 4 of 7 belong to convert it first to another character, because Excel does not provide a feature that allows you to calculate the root level 4 (during practical tasks often is the case, why should then remember the lessons of mathematics in school and properly transform equation).

2\. Calculate the cos of 27 degrees.  
  
  
  
  
As we know the arguments of trigonometric functions in Excel, should be given in radians. In that case, solution to the problem should look like this:  
  
  
  
  
a)Transform 27 degrees to radians,  
  
  
b)Put the result of the trigonometric function.  
  
  
  
  
Solution : Cos (radians(27))  
  
  
  
3\. In how many ways can a 16 person group set in a series of pairs?  
  
To calculate the result of this task should use the so-called permutations of a set: 16!  
  
Solution : FACT(16)  
  
  
  
4\. In how many ways can you select a 6 person volleyball team from a 16 people group? It is indeed one of the most difficult tasks, therefore let's we apply the so called Newton's symbol:

![](images/image80.png)

5\. How to calculate:

![](images/image88.png)

Solution : sqrt(sin(radians (25))+ 2)/(cos(radians(45)+2)  
  
  
  
  
  
6\. XYZ company employee was asked to count the total sales of the three products.  
  
  
  
You enter data to Excel Sheet by selecting the cell and typing data directly  in the cell  or in the  formula bar  (indicated by arrows in the figure below).

![](images/image60.png)

 After setting the active cell D8 let's enter in the cell the formula summing sales of these three products. This can be done in many ways, for example by typing in D8 to the formula = SUM ( D5: D7 ), or by entering = SUM ( and selecting the interesting range of the mouse ), but the best standing on the field select the icon of the sum, which is on the card  'Formulas'. The values you are searching for will be automatically summarized. The spreadsheet should look like as it is shown below.  
  
  
  
In this way we can also introduce other functions - financial, logical and others.

![](images/image91.png)

### Checking knowledge:

1\. In how many different ways can you select 3 people to go to the cinema out of a 7 person group? What formula will you type in Excel?

COMBIN(7;3)

COMBIN(7,3)

COMBIN(3;7)

# The relative and absolute addresses

As it has been mentioned earlier cell ADDRESS  is a pair that specifies clearly a cell in the spreadsheet. It arises from the number of column and row sheet. The columns are numbered with successive letters A, B, C, and the rows \- consecutive numbers 1,2,3; eg. a cell in the upper left corner of the sheet has the address A1.  
  
  
  
Addresses of the cells act as variables in formulas (formulas called) entered into the worksheet cells. As a result, the change in value in 1-wszej cell can be automatically reflected in the other cells.  
  
  
  
you can distinguish three types of addresses spreadsheet cells, typed into formulas - their type is indicated by the $ sign:  
  
  
  
Absolute \- in this addressing the specific cell address is important, not its position relative to other data. Add the cell address $ signs in front of the letter of the column and before the letter indicating the row eg.  $A$1 . As a result, the cell address will not change. Such addressing is used, for example when the value of a cell refers to a number of data:  
  
  
  
  
  
Example 1:  
  
  

An employee at XYZ has the task to calculate the price of goods in PLN in terms of Euro.  
  
  
  
Solution:  
  
You will get this value by multiplying the price of the goods in Euro (B4:B12) by Euro exchange rate (in cell B1). To all the values in column B multiplied by this one particular cell must address it as an absolute address: formula takes the form: = B4 \* $B$1 . You can copy such a form without any changes.  

![](images/image40.jpg)

Relative \- Addressing is used by the program as default. Addressing utilizes the relative position of the cells relative to each other and not their specific addresses. It is taken into account the position of the cell in which it is entered formula containing the address. Sheet remembers the location of the cells whose addresses appear in the formula, relative to the cell containing the formula. $ Character does not occur .  
  
  
  
Example 2:  
  
In columns A and B are the data series, in column D we obtain the products of the two pairs of the series.  
  
  
  
Solution:  
  
To do this, in the cell D1, enter = A1 \* B1 , this formula can be copied to other cells in column D. This is possible thanks to this the program at that addressing only checks the relative position of the cell with the formula to each other, so the formula is copied down to the next cell will use a modified version of the formula as =A2\*B2 and so on.  

![](images/image103.jpg)

Mixed \- Address mixed cell is a combination of an absolute and relative address. It is used when the values have to refer to a particular column or row. If we mean to indicate a specific example of the column address will be the character $A1 , and in the case of a particular row becomes A$1. This distinction is important in the transfer (copying) formulas between cells. This part of the address, which is not subject to change should be preceded by a $; eg. the absolute address cell A1 has the form $A$1 , and copying formulas with the address he remains always the same. In the mixed address only one part is preceded by a $ and does not change when you copy a formula.  
  
  
  
Example 3  
  
In column A the data to be multiplied by the value of the other two columns.  
  
  
  
Solution:  
  
To make such an operation should be time to enter a formula into cell D1 = $A1 \* B1 and then copy it without modification to the other cells down or right, use addressing mixed in the form of: $=A1\*B1  

![](images/image59.jpg)

### CHECKING THE KNOWLEDGE:

Which of the following formulas satisfies receiving the following multiplication table in two movements, copying the formula - the formula enter into the B2 and then copy to the right and the whole row down.

A \* B $ 2 $ 1

$ A2 \* B $ 1

A \* B $ 2 $ 1

$ \* $ A2 B1

$ A $ 2 \* B $ 1

$ A2 \* $ B $ 1

Check the answer

![](images/image96.png)

# Summary

In the above lesson we presented the basis for the introduction and formatting data in Excel spreadsheets, making calculations (using operators and functions) and the use of semi-automatic copying using different kinds of addressing (relative addressing, absolute addressing, mixed addressing). It should serve as a good kickstart in learning Excel spreadsheet.

[](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62112/chapter/25920&sa=D&source=editors&ust=1714064099831425&usg=AOvVaw2xEoAxZXPyqlMcJNxIp_ki)

# [6](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62113/chapter/25926&sa=D&source=editors&ust=1714064099831931&usg=AOvVaw3zRvWr1OB990xl6Iz4z8vx) [Lesson XII - Charts in Excel - Basics](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62113/chapter/25926&sa=D&source=editors&ust=1714064099832313&usg=AOvVaw35bOX1v7tpzNyRxyWiCE1l)

[15.03.2024 11:46 | Number of chapters: 5](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62113/chapter/25926&sa=D&source=editors&ust=1714064099832747&usg=AOvVaw28NsW7F4dRIk5E0pu1vLCr)

# INTRODUCTION

Often we need to illustrate our calculations with a chart- particularly when it is about different kinds of analyses and computer simulations. One chart is better than a thousand numbers. This lesson will provide step- by –step directions how to create basic charts in Excel.

### Learning effects

Once the material of this lesson has been mastered, the student should be able to create basic Scatter or Pie Charts in Excel based on entered or acquired data.

# SCATTER CHART

\[FILM\]

We need to create a table with data

In today's class we will work on a task for mathematical analysis class. The result of our work will be a common, standardized chart of five math functions.  
  
  

We have a given function formula:  
  
y = 2x 2  - 3x - 2  
  
x € <- 20 20>

1\. The first step is to create a table with data which Excel will use to create a chart.  
  
2\. Fill in the table with a series of number values for x-s - dragging like while copying formulas:  
  
  

![](images/image72.png)

up to 20. . .

3\. Fill in the values for y 1:

![](images/image41.png)

Then we drag the formula to the bottom, so that Excel calculates y for all x-s.

Creating and editing the chart

4\. Having a ready table select values of all y-s and on the "INSERT" tab choose "SCATTER CHART ":

![](images/image90.png)

To draw charts of mathematical functions usually SCATTER CHART is used(position II or III). In this example we will apply position II.  
  
  
  
Click on the second position and the chart will be created.  
  
  
  
5\. Unfortunately, the chart we have created is incorrect so we need to change the values of the data series. First, to make our work easier we need to move the chart to another worksheet. To do this, right-click on the chart and from the context menu select "MOVE CHART":  
  

![](images/image56.png)

Select "Worksheet 1" and click "Ok". Automatically we will get moved to the second spreadsheet.  
  
  
  
6\. Now dragging the corners of the chart to the sides we can stretch it to full screen. This way it will be more comfortable. Then right-click on the chart and from the context menu choose "Select data". You will be moved to the first worksheet and the window "Select Data Source” will appear :  
  

![](images/image75.png)

7\. Select the "y 1" s and click the "Edit" button.  
  
  
  
8\. "Edit series" window will display.

![](images/image52.png)

9\. First select in the first text box "Name of series." We need to enter the name for the series. To do this, select the cell B1 (there we have entered the name of the series as "Y1"). So click on the graphical icon at the end of the form box and switch to the first worksheet (you can do this by clicking on the appropriate tab in the lower left corner of Excel window).  
  
  
  
10\. Now select cell B1 and again click on the icon at the end of the form box.

![](images/image69.png)

11\. The next step is to provide the values of X series. At the beginning we go to the form box and click the icon at the end. Now select all values of X (from -20 to 20). And again, click on the icon at the end of the text box. Then click twice "OK". The chart will display correctly now.  
  

![](images/image32.png)

Add values of another function to the existing chart

12\. At the beginning we have to add one more column to the existing table. We will call it y2:

![](images/image42.png)

13 .The next step is to calculate y, according to the function formula.  
  
  
  
Let’s say the formula is this: y2 = (x-1)/(x+2)  
  
  
  
It should be noted that the argument of the function -2, does not belong to the domain. Later you will find out what to do about it.  
  
  
  
14\. Enter the appropriate formula in the cell C2 and drag it to the bottom so that Excel calculates the values of y2 for all x-:

![](images/image70.png)

15\. In the cell C20 the message "# DIV / 0!" is displayed which means that you cannot divide by 0. To get the chart drawn correctly, the cell C20 should be left empty, delete its contents by using "Delete" button.  
  
  
  
If while executing the tasks, messages "Number" or "DIV / 0!" are displayed , we delete them leaving a given cell empty.  
  
  
  
16\. Having prepared the table, right-click on the graph and select from the context menu the option "SELECT DATA ...".  
  
  
  
17\. Then click "Add" button and following the same pattern as for correcting data in the previous exercise, give the name of the series (cell C1), select the value of all x-s (from -20 to 20).  
  
  
  
18\. In the box "Values of Y series" delete everything that is typed and select all values of y2. Double click "Ok".  
  
  
  
19\. It’s done now! We have added to the chart another data series called "y2".  
  
  
  
20\. Now to make the chart look better you move the mouse cursor on the axis and right-click. From the context menu choose "FORMAT AXES".  
  
  
  
21\. In the text box "minimum" enter value "-7" and in the text box maximum enter value "7"

![](images/image99.png)

22\. Click "OK". The chart is ready:

![](images/image95.png)

# Exercises

To the created example add data series of function with a formula as below and move to the folder TASKS BY ...:  
  
  

Homework

1.    
    y3 = (sin^2 x)/x
2.    
    y4 = (tg(x))/(x+1)
3.    
    y5 = ?(x-2)

### Checking knowledge:

The data for the chart are taken from:

all selected cells

Selected cells, but only those in which there is a number

From cells with content (to be explained to students)

Check the answer

### Pie chart

We were asked to prepare a pie chart with information about the most popular browsers in the world according to their percentages expressed in integral numbers - data for 2011. The leading browsers in the world are as follows (December 2011 according to the StatCounter website)  
  
  
  
Internet Explorer - 38,64%.  
  
Google Chrome - 27,27%.  
  
Mozilla Firefox - 25.29%.  
  
Safari - 6.08%.  
  
Opera - 1.98%  
  
Others - 0.74%  
  
  
  
Select the table and on the 'Insert' tab select the Pie chart and subtype 'Pie chart 2-D'.  
  
  
  
2-D Pie Charts are clearer, unfortunately due to the attractive form of 3-D Pie charts they have become much more popular and the audiences expect them.

![](images/image38.png)

Finding products using small squares with their colors in the legend is very tiring, and when there are a lot of elements or if someone finds it hard to differentiate similar colors it becomes almost impossible impossible.  
  
  
  
Click on a '+', uncheck the 'Legend', select the 'Data Labels', then click an arrow at the 'Data labels' first select the 'End of an external' and 'More options ...'.  
  

![](images/image30.jpg)

In the 'Format Data Labels' mark:  
  
\- 'Category Name' - so that we know which part of the pie applies to a given product.  
  
\- 'Percentage' - here there is calculated and given an approximate percentage of the total figure  
  
  
  
Uncheck:  
  
\- 'Value' - in order to eliminate unnecessary decimals  
  
  
  
There is a default option 'Show lines leading' - useful for large quantities of pie slices, so that the lines leading the clippings labels are connected.  
  
  
  
Both messages displayed on the labels are separated by new line marks, and we can change it in the 'Separator' menu.  
  
  
  
In this window, it is also possible to change the position of labels and change the format of numbers.

![](images/image3.jpg)

As in all charts we can also use the styles and colour palettes, which are available when you click the Brush icon.

![](images/image46.jpg)

A colour slice can be changed by clicking on it twice individually (with a break between clicks) which will result in the selection (small circles), then click it with the right button and choose the colour changes which are visible on the chart when you move the mouse cursor over the colours.  
  

![](images/image71.jpg)

To eject the selected clipping simply select it and drag it from the centre of the chart. It is used to draw the attention of the recipient precisely on this passage.  
  
  
  
After bolding the data labels and writing the title, the chart will look like in the figure below.

![](images/image61.jpg)

In order to get rid of the graph frame right click it, and choose the command 'Format chart area ...'

![](images/image92.jpg)

In the 'Format the Chart ' window choose 'No Line'. Close the window.

![](images/image65.jpg)

At any time we can change the chart type by right clicking and selecting 'Change the chart type ...'.

![](images/image8.jpg)

Now let’s choose a 3-D pie chart.

![](images/image33.jpg)

For 3-D charts, there are many styles, you have to adjust yourself the right one for the job.

![](images/image5.jpg)

By right clicking the chart and selecting 'Rotate 3-D' we will be able to choose how to position the chart, which will highlight the fragment we want.

![](images/image82.jpg)

WARNING:  
  
Increasing Prospects makes the graph less clear, and the section which is at the bottom seems larger than it actually is.

![](images/image84.jpg)

### CHECKING THE KNOWLEDGE:

Graphs can be displayed:

Only in the spreadsheet where the data comes from

Only in the data spreadsheet and chart spreadsheet

You can view ae graph in each of the existing spreadsheets and make it a spreadsheet of the chart

Check the answer

### Summary

In the lesson we presented the basics of creating charts in Excel. Once you have mastered the material you should be able to create charts in Excel. This of course does not cover the whole subject of charts therefore we encourage self-experimentation.

[](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62113/chapter/25926&sa=D&source=editors&ust=1714064099844559&usg=AOvVaw3G_R3CvDglQebok4kR9CfA)

# [7](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62114/chapter/25931&sa=D&source=editors&ust=1714064099845003&usg=AOvVaw26J_nOFrOIJ7xjKr76XaU4) [Lesson XIII - Introduction to Excel logical functions](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62114/chapter/25931&sa=D&source=editors&ust=1714064099845320&usg=AOvVaw1Shk9ng67XbmthP5xB3mYw)

[15.03.2024 11:46 | Number of chapters: 6](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62114/chapter/25931&sa=D&source=editors&ust=1714064099845724&usg=AOvVaw3G40l7tG-rdLYaPNTIXUNW)

### Introduction

The logical functions in Excel are extremely useful, and often indispensable in everyday work. It is hard to imagine a serious spreadsheet e.g. without built-in IF function. The logical functions are primarily used to check whether the values entered in the worksheet’s cells meet the conditions. Only rarely are they used alone, most often they are nested in formulas, being arguments for other functions (often they return a table of numerical values as a parameter for mathematical or statistical functions).

### Learning effects

Once the material of this lesson has been mastered, the student should be able to easily solve the basic problems associated with the use of logical functions in Excel.  
  
  
  
For example :  
  
"Create a formula that will grant a discount on monthly tickets or not, according to the following principles:  
  
People who are entitled to discounts need to meet two conditions simultaneously:  
  
a) be retired  
  
b) their monthly income per capita cannot exceed 600 zł "  
  
  
  
\[FILM\]

### Basics of logical functions

TRUE()  
  
This function has no arguments, it always returns the logical value TRUE. You can also enter this value directly into a cell or formula.  
  
  
  
FALSE()  
  
This function has no arguments, it always returns the logical value FALSE. You can also enter this value directly into a cell or formula.  
  
  
  
Both of these functions seem to be absolutely unnecessary in Excel and have been introduced in order to comply with other spreadsheets.  
  
  
  
IF()  
  
This function checks the logical condition specified in the first argument of the function. If the condition is fulfilled (TRUE) then the value of the second argument is returned, and if not (FALSE) - the value of the third argument is returned.  
  
  
  
The syntax of the IF function () is presented below:  
  
• logical-test - to check the logical condition of a value or expression, the result of which can be calculated as a logical value (TRUE or FALSE). The logical condition often uses logical comparison operators such as =,>, <,> =, <=, <> to show the values of cells. For example, B2 = 9 is a logical expression; if the value entered into cell B2 is actually number 9, this expression will be evaluated to TRUE, in any other case, the expression will have the logical value FALSE  
  
  
  
• value\_if\_true - the second argument of the function is the value returned when the first argument logical\_test is met. If our logical test is the expression B2 = 9 and in the cell B2 there is in fact number 9, then the result of the function - the value of the second argument - may be a text message "in this cell there is number 9". This is an optional argument that can be omitted by placing two semicolons after the first argument. Omitting it indicates that it is a default argument, whose resulting value is TRUE  
  
  
  
• value\_if\_false - the third argument of the function is the value returned when the first argument logical\_test returns the value FALSE. If our logical test is still the expression B2 = 9, and in cell B2 there is a different value (number, text, error, logical value) or the cell is empty, the result of the function (the value of the third argument) can be a text message "the value of this cell is different from number 9". Leaving the argument empty will result in returning the value FALSE. Two optional arguments CANNOT be omitted at the same time, at least one of them should be determined  
  
  
  
The use of IF function is presented below

![](images/image67.jpg)

\=IF(B2 = $ 9; "in this cell is number 9"; "the value of this cell is different from the number 9")  
  
  
  
The result of the function is presented depending on the value of the cell on the left side of the formula. Only in one case, the logical expression is true. Excel does not apply automatic conversion here and properly distinguishes numeric values from the text, that’s why number 9 that is preceded by an apostrophe is treated as text (logical condition returns FALSE, while the formula - the text that is included in the third argument of the function value\_if\_false).

### Examples of logical function IF ()

The first example shows the logical condition with statistical function. Apart from the comparison operator that has been mentioned above we use here statistical function AVERAGE ().  
  
  
  
The task is to reward students who have obtained the average grade of at least 4.50 in the given subjects - they are entitled to a scholarship for their academic performance.  
  

![](images/image85.jpg)

The formula in cell F4 checks the average of four subjects and it looks like this:  
  
\=IF(AVERAGE ($B4:$E4)>= 4.5; "yes - "&TEXT(AVERAGE($B4:$E4);"0.00"); "no - "&TEXT(AVERAGE ($ B4: $ E4), "0.00"))  
  
  
  
The most important in this case is the logical condition, that is checking whether the average of the four subjects is higher than or equals 4.50. If this happens, the formula returns the text  
  
  
  
"yes –“ and shows the average grade for the student, otherwise it returns the text "no -" together with the average grade. Another way is to create two separate columns: average grade, and information about the scholarship (in this case, it is possible e.g. to sort by average).  
  
  
  
The second example shows nesting of the function IF (). Some logical problems can be solved only after multiple nesting of this function e.g. when the need to allocate the grade according to the value range in which the score is.  
  
  
  
Below there is a table in which students were assigned grades according to the number of points obtained in the exam.  
  
  
  
The formula for cell C4 is:  
  
\= IF ($ C4> 18; "very good"; IF ($ C4> 14; "good"; IF ($ C4> 10; "satisfactory", "unsatisfactory")))

![](images/image15.jpg)

It is worth to remember a few important things:  
  
• The IF () can be nested up to 7 times in a formula in Excel 2003. For Excel 2007 you can nest it up to 64 times, but the formula will not work correctly in the earlier versions of Excel, so it is advisable to use up to 7 nestings in a single formula. In case of our formula the function IF ()has been nested three times.  
  
  
  
• The second instruction of IF function () is simultaneously an argument value\_if\_false for the first instruction of the function (view 4). Similarly, the third instruction of IF function () is an argument value\_if\_false for the second instruction and so on.

![](images/image29.jpg)

• The formula checks the first logical condition and stops when it returns TRUE (as a result it returns the value of the second argument). If the returned value is FALSE - the formula moves to the second condition etc. In our example (score = 11), the first condition $ C5> 18 is false, the second $ C5> 14 also returns FALSE. Only the third $ C5> 10 is met - the result of the formula is thus the word "sufficient".

• For any number of points lower than 11 each of the three conditions returns FALSE. In such situation (in another case)the formula returns the word "unsatisfactory".

### The AND () function - Expansion function IF ()

### AND()

The AND () works in conjunction with IF (), extending its operation. IF () in basic form operates only one logical condition, while the AND () allows you to enter up to 30 logical conditions. To perform function as a result of TRUE, it is necessary that each of the conditions, function arguments, he was satisfied. If at least one of the accepted conditions is FALSE, the function returns a result of FALSE.  
  
  
  
AND () it is therefore, in other words, the product of (a conjunction) conditions. Be very careful to keep all function arguments logical values using other types of values, as very simply, you can generate an error. Using arguments and empty text is permitted only in particularly justified cases - only if the second argument is a reference to an empty cell or one that contains text, the formula will work - the data entered in the parameters manually generate this error #VALUE !.  
  
  
  
The following table is presented on the basis of which in a very useful function can be used, AND (). The task concerns the selection of candidates for the position of Analyst in our company. In total, it reported seven people who were tested in various fields. The assumption is that we are interested in people who are very familiar with English, Excel, and have obtained at least 15 points in our test checking the knowledge of controlling. If the candidate meets all these conditions, it is admitted to the second stage of recruitment; otherwise eliminated.

![](images/image77.jpg)

The formula contained in the H4 as follows:  
  
\= IF(AND($C4>14; $D4="yes";$F4="yes");"Stage II", "Not applicable")  
  
  
  
• For the first person formula returns the text '' Void '' because it was not satisfied with the conditions of the other very good knowledge of English. Although the other two conditions have been satisfied - AND function () returns a result of FALSE, and the function IF () converts a specific text message.

### The OR () function - Expansion function IF ()

### OR()

The OR () - like function AND () - interacts with function IF (), allowing for a more extensive tests. If you want the function to pay as a result of TRUE, it is required that at least one of the conditions, function arguments, he was satisfied. If all of the accepted conditions are FALSE, the function returns a result of FALSE. OR () it is therefore, in other words, the sum of (alternative) conditions. Using arguments and empty text it is handled by a function similarly to the function AND ().  
  
  
  
The following tables present the same as for the AND () but with different results. This time we carry out recruitment for the position of Specialist. Database, because the eligibility criteria for the next stage are different. The candidate this time must meet two conditions: be fluent in Access, and at least one of the two languages.  
  

![](images/image16.jpg)

The formula contained in the H4 as follows:  
  
\= IF(AND($G4="yes";OR($D4="yes";$E4="yes")); "Stage II";"eliminated")  
  
  
  
• Here we have a combination of conjunctions and alternative conditions. Conjunction is that the candidate must meet two conditions, an alternative that requires a good knowledge of any foreign language.  
  

### CHECKING THE KNOWLEDGE:

![](images/image105.png)

a) =IF(AND(G12="yes";E12<=600);"discount";"without discounts")  
  
b) =IF(AND(G12<600;OR(E12="yes";F12="yes")); "discount", "no discount")  
  
c) = IF (AND(G12<=600;OR(E12="yes"; F12="yes")),"discount","no discount") - AND at the beginning because we have to choose options A and B and then oR (students or retirement) and G12<=600 (not to exceed 600 zł)

### Summary

In addition to the IF function () all logical functions return as a result of the logical type TRUE / FALSE. The IF () can be used in many different ways: by means of nesting you can check a number of different conditions; treating each cell in the range as a parameter to a function of mathematical, statistical or information, you can make calculations (eg. to count or sum up) only in those cells that meet certain criteria. Functions AND () and OR () operate on individual cells and allow you to develop logical tests, which are very often used in the making of advanced formulas. We encourage you to own adventure with logic functions.

  
  
  
  
  
  
  
  
  
  

Test In the attached file SXXXXX-WSI-INTERNET-TEST-EXCEL-LOGICAL-FUNCTIONS.xlsx Scoring max 10 0.5 + 1 + 2 + 2 + (9 \* 0.5)

[](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62114/chapter/25931&sa=D&source=editors&ust=1714064099852767&usg=AOvVaw1CgLS4F4wjsP7_gMf58xmF)

# [8](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62115/chapter/25937&sa=D&source=editors&ust=1714064099853247&usg=AOvVaw0-o_RkUI_9SS7J6x1IrBB9) [Lesson XIV - Pivot tables basics](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62115/chapter/25937&sa=D&source=editors&ust=1714064099853572&usg=AOvVaw2mDu0QnmAdDQNiYGjNiWFC)

[15.03.2024 11:46 | Number of chapters: 4](https://www.google.com/url?q=https://gakko.pjwstk.edu.pl/edux/7542/lessons/62115/chapter/25937&sa=D&source=editors&ust=1714064099854001&usg=AOvVaw0X6KAIDWgR5xI8bdVkK-yk)

### Introduction

Excel pivot table is a powerful analytical tool. The main functionality of pivot tables that is used, is the possibility of a quick, easy and transparent summary and analysis of large data sets. However it is not the only functionality of pivot tables  
  

### Learning outcomes

Once the student has mastered the material of this lesson, they should be able to easily create pivot tables according to the set purpose (e.g. What is the sales figure by certain regions and years?) out of the given data file (e.g. sales volume) and modify the created tables as needed.

### Pivot Table out of data file

  
  
  
  
  
  
  
  
  
  
  

2 Source data - Excel i movie

To create a Pivot Table we will use the file "PivotTable-Data.xlsx" After opening the file the content is displayed as it is shown below.

![](images/image23.jpg)

The data have been generated in such a way that each row contains information about the sale, purchase, plan, price, quantity and margin. To these data there are assigned: branch, region, date of sale and the information on the sale (resulting from the date).  
  
  
  
Note that the figures are formatted.

The goal to achieve

At the beginning we set ourselves an easy goal, in order to make aquiring information about Pivot Tables nice and easy:

### What is the value of sales by individual regions and years?

The task that we need to do can be easily accomplished using other built-in Excel functions, let’s say SUM.IFS. function. My goal is to show the possibilities of a Pivot Table, not to convince anyone that this is the only appropriate tool for summarizing and analyzing data. Nevertheless this is a great tool.

Creating a Pivot Table

Set the active cell in the source data. This is select any cell on the data out of which you want to create a Pivot Table.  
  
  
  
Then, on the Insert tab of the Tables group select the command Pivot Table. If you click on the upper part of the Pivot Table icon, then immediately the dialog box Create a Pivot Table will be displayed. If you click on the arrow under the icon, you will have to choose from the available commands the one about creating a Pivot Table.

![](images/image63.jpg)

In the Create Pivot Table dialog box, in which Excel automatically detected and entered the range of the source data in the field Select a table or range.  
  
  
  
To place the Pivot Table in the new worksheet, leave the default selection in the part of the dialog box referring to the position of the Pivot Table report.

![](images/image100.png)

After confirmation the Pivot Table is ready to work. The new worksheet with an empty Pivot Table has been inserted. On the right side there appeared the Pivot Table Field List, below which there are areas of the Pivot Table. Additionally, on the ribbon there appeared a group of contextual tabs Pivot Table Tools, which include cards Options and Design.  
  

![](images/image58.jpg)

Pivot Table Areas

### Report filter

In this area we place fields from the PivotTable Field List, which are used to filter data. The values of the fields located in the filter will not be visible in the PivotTable.

### Row labels

Labels placed in rows, like row headers in an ordinary table.

### Column labels

The labels placed in columns, like column headers in an ordinary table.

### Values

The values of the fields located in this area will be summed up. Besides summing up, we can perform other activities on them, but you will learn more about them later on.  
  
  
  
To sum up the values of the fields located in the area of value, it is necessary that these values are recognized by Excel as numbers.

Placing fields in PivotTable areas

We can place the fields in the PivotTable areas in several ways.  
  
  
  
One of them is to select the chosen fields in the PivotTable Field List, the fields will be placed in areas selected by Excel.  
  
  
  
Pay attention to the field of Years, which shows the number representing the year in date.  
  
  
  
This field has been placed in the area of values, and the values in column Years have been summed up!

![](images/image43.jpg)

After selecting the fields we can change their position and the way of summing up the field, but a faster way is to place the fields in the appropriate areas right away.  
  
  
  
A more convenient and a faster way is to drag fields from the PivotTable Field List to the selected areas. Click any mouse button (it does not matter whether left or right) on the selected area and drag it to the selected area.  
  
  
  
Let’s recall the set purpose: What is the value of sales grouped by individual regions and years?  
  
  
  
We are interested in the fields Sales , Region  and Years . The order of placing them in the table can be varied.  
  
  
  
To achieve the goal that was set earlier we need to do the following:  
  
1\. Drag the Sales  field to the Values area

![](images/image47.jpg)

2\. Drag the field Region to the area Rows

![](images/image11.jpg)

3\. Drag the field Years to the area Columns  

![](images/image39.jpg)

Finished! Pivot Table has been prepared. The goal has been achieved.  
  
  
  
We value sales broken down by regions and years, however, these data are difficult to read.

### Modifying Pivot Table

We created a PivotTable in Excel that displays a summary of the values in column with the sales data broken down by region (placed in rows) and years (placed in columns).  
  
  
  
The new goal to achieve  
  
Early formatting of the data source from which you create a PivotTable does not affect the format of the data in the pivot table. The data in the PivotTable is displayed in the general format. How do you change the format of the data for each field to have useful information is displayed in a clear manner?  
  
  
  
How do you change the format of the data for each field?  
  
Display format can be changed in several ways. In this section we will describe the most commonly used ones.  
  

Calling the Settings dialog box values.

1\. Left-click on the box located in the area of values and select Settings in the value field.  
  
2\. Set the active cell in the pivot table in the data for this field. We can also set up a cell in the row or column totals, and in the cell, which displays the name of the function used for the field (in our case this cell is the cell with the entry Sum of Sales.) It is important that on the Options tab in the group Active box was displayed name fields, which change the format of the displayed data is affected. When you select a cell on the Options tab in the group Active box, click on the Value Field Settings.

![](images/image98.jpg)

Change the format of data displayed.

When you click on the Settings value field will show the Settings dialog box values.

![](images/image109.png)

We can change the way data summary (e.g. The sum of these values on the counter) but we will not do it this example. Click on the button Number Format. A window appears Format Cells, which will be visible only card numbers. We can now format the data for the selected field according to their own needs. In this case, I am changing the category on the numerical decimal places I set to 0 and turn on the grouping of numbers after 3 digits by checking the Use 1000 Separator (,).  
  

![](images/image102.png)

Finished! Once approved, the data is formatted pivot table is as follows.

![](images/image106.jpg)

### Summary

In the lesson it has been presented how to use pivot tables to let you quickly, easily and clearly summarize and analyze large data sets. Modification of displayed results also does not cause problems. Of course, this does not cover the whole subject pivot tables in Excel. We encourage you to exercise your own research as well.  
  
  
  
In the attached files PivotTable-Data.xls – data for lesson TEST: WSI-INTERNET-TEST-EXCEL-PIVOT-TABLES.pdf SXXXXX-WSI-INTERNET-TEST-EXCEL-PIVOT-TABLES.xlsx Scoring max 6 Point for each task
Heading style 
atx
Horizontal rule 
– – –
Bullet 
*
Code block style 
fenced
Fence 
“`
Em delimiter 
_
Strong delimiter 
**
Link style 
inlined
Link reference style 
full
100% Local Processing: Your Data Stays Yours
Rest assured, none of your data is uploaded to the internet. The tool operates entirely within your browser, utilizing secure JavaScript. This means all processing and conversions happen locally on your device, ensuring your information remains private and secure.

Chose your preferred Markdown style
Below the editor you can select your preferred Markdown style. Here is an explanation of the available settings.

Heading Style
Headings in Markdown are created by adding one or more # symbols before your heading text. The number of # symbols you use will determine the level of the heading. For example:

# Heading 1 for the largest heading
## Heading 2 for the second largest
### Heading 3 and so on, up to ###### Heading 6.
Setext style headings in Markdown provide a simple and visually clear way to designate text as either a first-level or second-level header without using the # symbols associated with ATX style headings. To create a Setext style heading, you underline the heading text with equal signs (=) for a first-level heading, which is equivalent to an <h1> tag in HTML, or with dashes (-) for a second-level heading, equivalent to an <h2> tag.

Here are practical examples:

First-level heading:

This is an H1
=============
Second-level heading:

This is an H2
-------------
It’s important to note that Setext style only allows for these two levels of headings. If you need to create headings for levels three through six, you would use the ATX style, which involves placing # symbols before your heading text.

Horizontal Rule
A horizontal rule is a line that separates sections of text. You can create a horizontal rule by placing three or more hyphens ---, asterisks ***, or underscores ___ on a line by themselves. For example:

---
Bullet
Bullets are used to create unordered lists. You can create a bullet by starting a line with a hyphen -, asterisk *, or plus + followed by a space. For example:

- Item 1
* Item 2
+ Item 3
Code Block Style
Code blocks are sections of text that are formatted to display as code. Markdown supports two styles:

Indented: Indenting lines by four spaces.
Fenced: Enclosing text within triple backticks “` or triple tildes ~~~. You can specify a language identifier for syntax highlighting right after the first set of backticks. For example:
```python
print("Hello, world!")
```
Emphasis Delimiter
Emphasis (italic text) in Markdown is created by wrapping text in one asterisk * or one underscore _. For example:

*italic* or _italic_ renders as italic.
Strong Delimiter
Strong emphasis (bold text) is created by wrapping text in two asterisks ** or two underscores __. For example:

**bold** or __bold__ renders as bold.
Link Style
Links in Markdown can be inlined or referenced:

Inlined: The link text is followed by the URL in parentheses. For example: [Google](https://www.google.com)
Referenced: The link text is followed by a reference in square brackets, and the URL is defined elsewhere in the document with the same reference in square brackets. For example:
[Google][1]

[1]: https://www.google.com
Link Reference Style
This is a way to organize links at the bottom of your document to keep the text clean. You give each link a reference label and use that label whenever you need to link to that URL. For example:

This is [an example][example link] reference-style link.

[example link]: http://example.com/
By using these Markdown features, you can effectively format text for readability and emphasis in documents, websites, and other platforms that support Markdown.

Advanced HTML-to-Markdown Converter
This advanced HTML to Markdown parser, supports GitHub Flavoured Markdown and additional formatting options for a comprehensive conversion experience. Specifically, it includes converting of strikethrough elements (<strike>, <s>, and <del>), creating tables, and managing task list items, allowing for a more versatile and complete translation of HTML content into Markdown format.

Convert HTML to Markdown Online

An HTML to Markdown converter is a tool designed to transform HTML (HyperText Markup Language) content into Markdown format. HTML is the standard language used to create and design web pages, featuring various tags to format text, create links, insert images, and more. Markdown, on the other hand, is a lightweight markup language with plain-text formatting syntax that aims to be readable and easily convertible to HTML but is simpler to write and read.

The converter takes the structured content of an HTML document, such as headings, paragraphs, lists, links, and images, and translates it into the corresponding Markdown syntax. For example, an HTML paragraph (<p>) becomes plain text in Markdown, a bold text (<strong> or <b>) is converted to Markdown’s **bold** syntax, and so on.

This process is particularly useful for those who need to migrate content from web pages to platforms that support or require Markdown, or for users who prefer the simplicity and readability of Markdown for documentation, note-taking, or content creation. It simplifies the task of manually converting complex HTML structures into Markdown, saving time and ensuring the consistency of the formatting.

Creating Content with AI and ChatGPT: The Essential Role of HTML to Markdown Conversion
When crafting texts with the help of artificial intelligence, I find the HTML to Markdown converter absolutely essential.

But why, you might wonder?

To guide the AI, including ChatGPT or Bard, I provide two to three sample texts. This approach helps set the direction for the newly generated content. Initially, I extract these template texts, ending up with an overly complex HTML code that tends to confuse the AI.

This is where the magic of the HTML-to-Markdown converter comes in, seamlessly transforming HTML into easily readable Markdown.

Consider the following SuperPrompt example:

<instructions>
Craft an article on "Topic" using Markdown format. Below, I've included <examples> of other articles containing some necessary information. Draw inspiration from these examples for the new article.
</instructions>

<style>
Always use English and address the reader in the second person singular. Maintain a tone that is both friendly and professional.
</style>

<example-1>
# Example text 1
...
</example-1>

<example-2>
# Example text 2
...
</example-2>
Exploring the Versatile Applications of HTML to Markdown Conversion
HTML to Markdown converters can be incredibly useful for a wide range of applications. Here are 10 purposes for which such a converter can be particularly beneficial:

HTML to Markdown converter
HTML to Markdown converter
Content Migration: Facilitates the transfer of content from websites (HTML) to platforms that support Markdown, such as GitHub, Reddit, or Jekyll-based blogs, ensuring that the formatting remains consistent.
Documentation: Helps in remodeling online documentation written in HTML into Markdown format, making it easier to manage and version control documentation, especially on platforms that prefer Markdown.
Educational Material: Enables educators and online course creators to easily convert their HTML-based learning materials into Markdown format, which is simpler to edit and share on various educational platforms.
Blogging: Bloggers who prefer writing in a simple Markdown editor can use the converter to easily transition their work from HTML templates to Markdown, making the editing process more straightforward.
Emails to Documentation: Transforms HTML emails to Markdown format, allowing for easier incorporation of email content into project documentation or reports.
Content Backup: Offers a way to back up web content in Markdown format, which is more compact and readable in plain text form, preserving the structural elements without the complexity of HTML tags.
Web Development: Developers can quickly draft content in Markdown and convert it to HTML for web pages, or vice versa, streamlining content updates and maintenance.
Publishing: Publishers can convert HTML manuscripts to Markdown for easier editing and formatting before publishing them on platforms that support Markdown.
Note-taking and Knowledge Bases: Facilitates the conversion of online research and articles into Markdown format for inclusion in personal or collaborative knowledge bases, making information easier to organize and search.
Technical Writing: Technical writers can translate complex HTML documentation into Markdown to simplify the editing process and improve the readability of technical documents, especially when collaborating with developers who prefer Markdown for README files and documentation.
These uses highlight the versatility of HTML to Markdown converters in streamlining content creation, management, and conversion across various digital platforms and contexts.

➽ To the HTML table to Markdown Converter

➽ To the Markdown to HTML Converter

For this tool, I have used the best Markdown converter: turndown

About
Contact
Imprint
Privacy Policy
© 2024 HTML to Markdown Converter




