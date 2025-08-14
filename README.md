I selected the “120 Years of Olympic History – Athletes and Results” dataset, originally in CSV format. I converted it to Excel for easier processing and performed data handling tasks such as cleaning, organizing, and preparing the data in Excel. Following this, I created visualizations in Power BI to discover insights and present the findings interactively.Zip file is shared for the dataset.

DATA HANDLING IN EXCEL

Tasks to be done in the cleaning process:
During the data cleaning of the Olympic dataset, duplicates were removed based on six critical columns — ID, Name, Games, Year, Event, and Medal — to eliminate redundant entries and preserve the uniqueness of each athlete-event record. Missing values in the Medal column were replaced with “No Medal” to clearly distinguish between athletes who did not win a medal and those with unrecorded data, ensuring consistency. Entries with all three key physical attributes — Age, Height, and Weight — missing were dropped, as they lacked sufficient information for meaningful analysis. The remaining missing values in the Age column were replaced with the rounded average value of 25, representing a typical Olympic athlete's age and improving completeness without significantly skewing age distribution. Missing values in the Height column were filled with a fixed value of 175 cm, based on a reasonable median approximation across all athletes. For the Weight column, missing values were imputed with a fixed value of 80 kg, which reflects an average estimate for Olympic participants. These imputations were made to standardize the dataset, minimize data loss, and ensure it was ready for reliable analysis and visualization.

DATA VISUALIZATION IN POWER BI

This interactive Power BI dashboard is designed as a comprehensive Olympic data exploration tool, featuring five interconnected pages with user-friendly navigation via blank buttons, enabling seamless movement between sections. Strategic bookmarks are incorporated to enhance interactivity, allowing users to quickly toggle between specific filtered views or focus points within visuals.
1. Home Page
 Serves as the central hub with four navigation buttons linking to key analysis pages: Athlete Performance, Athlete Analysis, Medal Analysis, and Sports & Events Breakdown. Selecting any button directs users instantly to the corresponding section.
2. Athlete Performance Page
 Focuses on showcasing individual athlete achievements. Slicers for Year, Region, Sport, Medal, and Sex allow targeted filtering. Cards display Total Athletes, Total Medals, and Win Percentage, complemented by a KPI for Win Percentage. A clustered column chart highlights the top 5 sports by medal count, while a bar chart showcases the top 20 regions by medal count, with drill-through to detailed athlete information (Athlete_Detail page).
3. Athlete Analysis Page
 Provides in-depth insight into athlete demographics and trends. Includes a table listing athlete names with medal counts, a line chart tracking the number of athletes by year, and a scatter plot illustrating the relationship between age and medal count. Slicers for Sport and Season allow focused exploration.
4. Medal Analysis Page
 Examines medal distribution and trends over time. Features cards showing the total gold, silver, and bronze medal counts, slicers for Region and Sport, a scatter plot tracking medal trends for the top 10 regions by year, and a pie chart displaying total medal count distribution. Provided Map for locating countries with medal they got.
5. Sports & Events Breakdown Page
 Analyzes Olympic performance by sport and event. A bar chart presents the count of events by sport, while a column chart shows the count of sports by event and season. Filters for season, event type, and gender allow additional segmentation.
Navigation Structure
 The Home Page offers quick access to the four main analysis pages. All analysis pages contain five navigation buttons at the bottom, enabling users to move between sections without returning to the Home Page, ensuring smooth and continuous data exploration. In addition, bookmarks allow users to instantly switch between predefined filtered views, enhancing storytelling and analysis efficiency.
