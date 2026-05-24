<h1>Netflix Content Dashboard | Tableau</h1>

<h2>Description</h2>
This project analyzes Netflix movies and TV shows from 1925–2021 using Tableau.  
The dashboard explores content distribution, ratings, genres, release years, and country production trends while also providing business insights and recommendations for the Vietnamese market.
<br />

<h2>Tools and Technologies Used</h2>

- <b>Python (Pandas)</b>
- <b>Tableau</b>
- <b>Jupyter Notebook</b>

<h2>Dataset Overview</h2>

- <b>8,807 rows</b>
- <b>12 columns</b>
- Data types included:
  - Categorical
  - Numerical
  - Date/Time
  <br/>
<img src="https://github.com/hatr201610-cyber/Netflix-Shows-Films-Dashboard-Tableau/blob/e49a0619a2a94714d28e6e9991257f3d6b66ca2d/Null%20Declaration" height="20%" width="20%" alt="Finding null"/>
<br />
<br />


<h2>Data Cleaning Process</h2>

- Missing values in <b>Director</b>, <b>Cast</b>, <b>Country</b>, and <b>Rating</b> were replaced with <b>"Unknown"</b>
- Missing <b>Duration</b> values were filled using average duration by content type
- Rows with missing <b>Date Added</b> were removed
- Converted <b>date_added</b> into <b>datetime64[ns]</b>
- Split and exploded:
  - <b>country</b>
  - <b>listed_in</b> (genres)

<h2>Dashboard Analysis</h2>

<p align="center">

Content Distribution: <br/>
- Movies: 6,131 (70%) <br/>
- TV Shows: 2,676 (30%) <br/>
Netflix content is heavily focused on movies.
<br />
<br />

Release Year Trends: <br/>
- Titles range from 1925–2021 <br/>
- Significant growth after 2000
<br />
<br />

Content Ratings: <br/>
- TV-MA: 36% <br/>
- TV-14: 25% <br/>
- Family/Kids content: ~15% <br/>
Most Netflix content targets mature audiences.
<br />
<br />

Top Production Countries: <br/>
- United States
- India
- United Kingdom
- Canada
- France
<br />
Vietnam only contributed 7 titles (~0.08% of the catalog).
<br />
<br />

Top Genres: <br/>
- International Movies
- Drama
- Comedy
- Documentaries
<br />
Less common genres include teen TV, classic movies, and TV horror.
 <br/>
 <br/>
<img src="https://github.com/hatr201610-cyber/Netflix-Shows-Films-Dashboard-Tableau/blob/e49a0619a2a94714d28e6e9991257f3d6b66ca2d/Final%20Product.png" height="100%" width="100%" alt="Finding null"/>
<br />

</p>

<h2>Key Findings & Business Recommendations</h2>

<h3>1. Limited Vietnamese & Southeast Asian Content</h3>

- Vietnamese titles are significantly underrepresented
- Opportunity to invest in local productions and licensed films
- Suggested KPI:
  - Increase Vietnamese titles from 7 → 50+ within 2 years
  - Produce 3–5 Vietnamese Netflix Originals annually

<h3>2. Popular Genres in Vietnam Are Underserved</h3>

- Anime
- Sports
- Reality Shows
- Stand-up Comedy

Recommendations:
- Acquire anime simulcast licenses
- Partner with Vietnamese entertainment programs
- Expand sports documentaries and regional partnerships

<h3>3. Catalog Freshness</h3>

- Many titles are older and less relevant to younger Vietnamese audiences
- Newer regional content should be prioritized

Suggested KPI:
- Increase recent content ratio from 54% → 65% within 18 months

<!--
 ```diff
- Older catalog dependency
+ More localized and recent content
! Stronger regional engagement
# Improved subscriber retention
@@ Better market adaptation @@
