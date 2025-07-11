## Hey there, I'm Gem Lo 👋

I'm a data-driven individual who is passionate about turning raw data into actionable insights. Trained at Sigma Labs XYZ, I build end-to-end data pipelines and analytical tools using Python, SQL, and AWS. I enjoy working across the data lifecycle, from processing and analysis to visualisation and stakeholder reporting, using tools like Tableau and Streamlit to solve real-world problems and support data-driven decision-making.

## 🎯 Key Projects

### 🏛 Liverpool Museum Visitor Feedback Pipeline
**Goal**: Improve visitor engagement and operational efficiency at a natural history museum by analysing real-time and historical survey data.

**Task**:
- Built two parallel ETL pipelines to process kiosk feedback: one for historical data (Python + PostgreSQL) and one for real-time streams (Kafka + AWS EC2).
- Provisioned cloud infrastructure using Terraform and stored data in AWS RDS.
- Created an interactive Tableau dashboard to provide museum staff with real-time insights and recommendations on exhibit popularity and visitor satisfaction.

**Key Tools**: Python, SQL, Kafka, Tableau, AWS (EC2, RDS), Terraform

[🔗 View Repository](https://github.com/gem09lo/Liverpool-Museum-of-Natural-History-LMNH-Project) 

---

### 🍔 Tasty Truck Treats – Automated Sales Analytics
**Goal**: Help a mobile catering business use data to optimise menus, routes, and marketing strategy.

**Task**:
- Designed a two-layer pipeline: one for processing historical sales data, another for ingesting daily transactions in real time using AWS Lambda and Step Functions.
- Built a Streamlit dashboard to track performance KPIs and configured AWS SES to email daily reports to leadership.
- Cleaned and transformed data using Pandas, and stored insights in Amazon Redshift.

**Key Tools**: Python (Pandas), SQL, AWS (S3, Lambda, Redshift, SES, Step Functions), Terraform, Docker, Streamlit

[🔗 View Repository](https://github.com/gem09lo/T3-Trucks-Project) 

---

### 🛍️ It’s On Sale – Price Tracking & Alert System
**Role**: Project Manager 

**Goal**: Empower users to get notified when products they care about go on sale.

**Task**:
- Built a web scraping tool (Python + BeautifulSoup) to track price changes across multiple e-commerce sites.
- Developed a Streamlit front end for user input and settings.
- Integrated AWS SES for real-time email alerts when tracked products dropped below user-defined thresholds.
- Presented a live demo to non-technical stakeholders and discussed how businesses could use the tool for competitor pricing analysis.

**Key Tools**: Python, Streamlit, BeautifulSoup, Pandas, AWS SES, Terraform

[🔗 View Repository](https://github.com/gem09lo/PriceSlashTrack) 

---

### 🧬 PubMed Articles – Institution Matching & Metadata Extraction (Machine Learning)
**Goal**: Automate the extraction and matching of institutional affiliations from PubMed research articles to support pharmaceutical research.

**Task**:
- Built a multi-step ETL pipeline to extract XML data from S3, transform and clean it using spaCy and RapidFuzz, and match institutions to the GRID dataset.
- Processed over 1 million PubMed articles with author metadata, keywords, and institutional affiliations.
- Integrated NLP (spaCy) for named entity recognition (GPE and ORG) and applied fuzzy matching (RapidFuzz) to identify institutions.
- Dockerised the pipeline and deployed it via AWS ECS Fargate, with automated task triggering using CloudWatch and EventBridge.
- Managed infrastructure using Terraform.

**Key Tools**: Python (Pandas, spaCy, RapidFuzz), XML, AWS (S3, ECS Fargate, EventBridge, SES), Docker, Terraform

[🔗 View Repository](https://github.com/gem09lo/PubMed-Articles) 


--- 
--- 

## 📚 Additional Projects

### Software Development Fundamentals
- **[🃏 Blackjack Game - Procedural](https://github.com/gem09lo/Blackjack-Game)** - CLI game demonstrating clean code principles, TDD with pytest, and Python best practices (9.5/10 Pylint score)
- **[🃏 Blackjack Game - OOP Refactor](https://github.com/gem09lo/Blackjack-Game-OOP-)** - Extension of the procedural Blackjack game, rewritten using object-oriented principles. Focuses on modular class design (Card, Deck, Hand), unit testing, and clean architecture for future gameplay expansion.
- **[🎥 Blockbuster Rental System - OOP](https://github.com/gem09lo/BlockBuster-Rental-System-OOP)** - Simulates a video rental store using object-oriented design (Video, Customer, Rental, VideoStore). Demonstrates clean code, TDD with pytest, and real-world logic (due dates, fines, age validation).
