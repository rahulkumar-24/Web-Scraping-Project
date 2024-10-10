<h1>🎬 JustWatch TV Shows & Movies Data Scraper</h1>

<p>This project is a <strong>web scraping tool</strong> that extracts data from the JustWatch website, specifically for TV shows and movies. It collects information such as titles, release years, genres, IMDB ratings, runtimes, production countries, streaming services, and age ratings.</p>

<h2>📋 Project Overview</h2>

<p>The project consists of two different datasets:</p>
<ul>
  <li><strong>TV Shows:</strong> Extracts information about TV shows available on JustWatch.</li>
  <li><strong>Movies:</strong> Extracts information about movies available on JustWatch.</li>
</ul>

<h3>Sample of the scraped data (TV Shows):</h3>

<table>
  <thead>
    <tr>
      <th>Link</th>
      <th>Title</th>
      <th>Release Year</th>
      <th>Genre</th>
      <th>IMDB Rating</th>
      <th>Runtime</th>
      <th>Production Country</th>
      <th>Streaming Services</th>
      <th>Age Rating</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://www.justwatch.com/in/tv-show/house-of-the-dragon">House of the Dragon</a></td>
      <td>House of the Dragon</td>
      <td>2022</td>
      <td>Drama, Action, Sci-Fi, Fantasy, Romance</td>
      <td>8.4</td>
      <td>1h 3min</td>
      <td>United States</td>
      <td>Jio Cinema</td>
      <td>A</td>
    </tr>
    <tr>
      <td><a href="https://www.justwatch.com/in/tv-show/the-bear">The Bear</a></td>
      <td>The Bear</td>
      <td>2022</td>
      <td>Drama, Comedy</td>
      <td>8.6</td>
      <td>34min</td>
      <td>United States</td>
      <td>Hotstar</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="https://www.justwatch.com/in/tv-show/shogun-2024">Shōgun</a></td>
      <td>Shōgun</td>
      <td>2024</td>
      <td>War, Drama, History</td>
      <td>8.7</td>
      <td>59min</td>
      <td>United States</td>
      <td>Hotstar</td>
      <td></td>
    </tr>
  </tbody>
</table>

<h3>Sample of the scraped data (Movies):</h3>

<table>
  <thead>
    <tr>
      <th>Link</th>
      <th>Title</th>
      <th>Release Year</th>
      <th>Genre</th>
      <th>IMDB Rating</th>
      <th>Runtime</th>
      <th>Age Rating</th>
      <th>Production Country</th>
      <th>Streaming Services</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://www.justwatch.com/in/movie/project-k">Kalki 2898 AD</a></td>
      <td>Kalki 2898 AD</td>
      <td>2024</td>
      <td>Science-Fiction, Fantasy, Mystery, Drama</td>
      <td>7.7</td>
      <td>3h 1min</td>
      <td>UA</td>
      <td>India</td>
      <td>Bookmyshow</td>
    </tr>
    <tr>
      <td><a href="https://www.justwatch.com/in/movie/maharaja-2024">Maharaja</a></td>
      <td>Maharaja</td>
      <td>2024</td>
      <td>Mystery, Action, Drama</td>
      <td>8.7</td>
      <td>2h 30min</td>
      <td></td>
      <td>India</td>
      <td>Netflix, Bookmyshow</td>
    </tr>
    <tr>
      <td><a href="https://www.justwatch.com/in/movie/furiosa">Furiosa: A Mad Max Saga</a></td>
      <td>Furiosa: A Mad Max Saga</td>
      <td>2024</td>
      <td>Science-Fiction, Thriller, Action</td>
      <td>7.7</td>
      <td>2h 28min</td>
      <td>A</td>
      <td>Australia, United States</td>
      <td>Apple TV, Amazon Video</td>
    </tr>
  </tbody>
</table>

<h2>🛠️ Tools and Libraries</h2>

<p>This project utilizes the following tools and libraries:</p>
<ul>
  <li><strong>Python</strong>: Core language for the project</li>
  <li><strong>BeautifulSoup</strong>: To parse HTML and extract data from the JustWatch website</li>
  <li><strong>Requests</strong>: To send HTTP requests to the website</li>
  <li><strong>Pandas</strong>: For data cleaning and manipulation</li>
  <li><strong>Google Colab</strong>: For analysis and testing (no extra extensions required)</li>
</ul>

<h2>🚀 How to Run</h2>

<p>Since this project is hosted on <strong>Google Colab</strong>, you don’t need to install any extra extensions or software. Simply open the provided Colab link below, and you can run the entire project directly in the browser.</p>

<ol>
  <li><strong>Open the Colab Notebook:</strong>
    <ul>
      <li><a href="https://colab.research.google.com/drive/1wL31tKADjwyH1ROOIPWPYI9lNLz0tZzB#scrollTo=tytqsADVR2x6">JustWatch Web Scraper Colab </a></li>
    </ul>
  </li>
  <li><strong>Run the cells:</strong> Each step is laid out in individual cells in the notebook, and you can run them sequentially to see how the data is scraped and processed.</li>
  <li><strong>Save or Download the Data:</strong> After scraping, you can download the generated CSV file containing all the scraped data.</li>
</ol>

<h2>📄 Dataset</h2>

<p>The scraped data includes the following fields for both TV shows and movies:</p>
<ul>
  <li><strong>Link:</strong> URL of the show/movie</li>
  <li><strong>Title:</strong> Name of the show/movie</li>
  <li><strong>Release Year:</strong> The year of release</li>
  <li><strong>Genre:</strong> Genres assigned to the show/movie</li>
  <li><strong>IMDB Rating:</strong> IMDB user rating</li>
  <li><strong>Runtime:</strong> Length of the show/movie</li>
  <li><strong>Age Rating:</strong> Age restriction or rating (if applicable)</li>
  <li><strong>Production Country:</strong> Country of production</li>
  <li><strong>Streaming Services:</strong> Platforms where the show/movie is available</li>
</ul>

<h2>📊 Usage</h2>

<p>This data can be used for:</p>
<ul>
  <li>Building recommendation systems</li>
  <li>Performing statistical analysis on trends in TV shows and movies</li>
  <li>Analyzing content across different streaming platforms</li>
</ul>

<h2>🔗 Links</h2>

<ul>
  <li><a href="https://colab.research.google.com/drive/1wL31tKADjwyH1ROOIPWPYI9lNLz0tZzB#scrollTo=tytqsADVR2x6">Google Colab Notebook (TV Shows)</a></li>
</ul>

<h2>🤝 Contributing</h2>

<p>Feel free to contribute by submitting a pull request or opening an issue. For major changes, please open a discussion first to ensure the changes fit within the project's scope.</p>

<h2>📧 Contact</h2>

<p>If you have any questions or suggestions, feel free to contact me at <a href="mailto:rahulkumar.19k8@gmail.com">rahulkumar.19k8@gmail.com</a>.</p>
