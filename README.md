<h1>Cinemate</h1>
    <p>
        Cinemate to aplikacja internetowa zbudowana w <strong>Nuxt.js</strong>, która pozwala użytkownikom przeglądać informacje o filmach i serialach przy wykorzystaniu API The Movie Database (TMDb). 
        Aplikacja jest hostowana na platformie <strong>Netlify</strong> i dostępna pod <a href="https://cinimate.netlify.app" target="_blank">tym linkiem</a>.
    </p>

    <h2>Funkcjonalności aplikacji:</h2>
    <ul>
        <li>
            <strong>Strona główna:</strong>
            <p>Wyświetla najbardziej znane filmy i seriale, zapewniając użytkownikom szybki dostęp do popularnych treści.</p>
        </li>
        <li>
            <strong>Wyszukiwarka (Search):</strong>
            <p>Pozwala na wyszukiwanie filmów i seriali poprzez wpisanie ich tytułów w polu wyszukiwania. Wyniki wyświetlane są w przejrzysty sposób, z informacjami o tytule, dacie premiery, opisie i popularności.</p>
        </li>
        <li>
            <strong>Zakładki tematyczne:</strong>
            <ul>
                <li><strong>Now Playing:</strong> Wyświetla listę filmów aktualnie granych w kinach.</li>
                <li><strong>Upcoming:</strong> Lista filmów, które będą miały premierę w najbliższym czasie.</li>
                <li><strong>Popular:</strong> Najpopularniejsze filmy i seriale, które są obecnie na topie.</li>
                <li><strong>Top Rated:</strong> Zestawienie najlepiej ocenianych filmów i seriali.</li>
            </ul>
        </li>
    </ul>

    <h2>Technologie użyte w aplikacji:</h2>
    <ul>
        <li><strong>Framework Nuxt.js:</strong> Użyty do budowy aplikacji opartych na Vue.js z możliwością renderowania po stronie serwera (SSR).</li>
        <li><strong>API The Movie Database (TMDb):</strong> Źródło danych o filmach i serialach, takich jak tytuły, daty premier, opisy, oceny i zdjęcia.</li>
        <li><strong>Netlify:</strong> Hosting aplikacji, zapewniający łatwy dostęp publiczny.</li>
    </ul>

    <h2>Jak aplikacja działa:</h2>
    <p>
        Aplikacja pobiera dane z API TMDb za pomocą różnych endpointów, takich jak popularne filmy, filmy obecnie grane w kinach, czy filmy nadchodzące. 
        Dane są prezentowane w atrakcyjny wizualnie sposób z użyciem kart zawierających zdjęcia, tytuły, daty premiery i opisy.
    </p>

    <h2>Link do aplikacji:</h2>
    <p>
        Aplikacja jest publicznie dostępna pod adresem: <a href="https://cinimate.netlify.app" target="_blank">Cinemate</a>.
    </p>

    <h2>Sposób użycia:</h2>
    <ol>
        <li>Na stronie głównej możesz przeglądać najbardziej znane filmy i seriale.</li>
        <li>W zakładce <strong>Search</strong> wpisz tytuł filmu, który chcesz znaleźć, aby zobaczyć jego szczegóły.</li>
        <li>Użyj zakładek takich jak <strong>Now Playing</strong>, <strong>Upcoming</strong>, <strong>Popular</strong> czy <strong>Top Rated</strong>, aby odkrywać różne zestawienia filmów.</li>
    </ol>

    <h2>Autor:</h2>
    <p>
        Aplikacja została wykonana w ramach kursu programistycznego. Jej celem było wykorzystanie technologii Nuxt.js i integracji z API, aby stworzyć intuicyjną aplikację do przeglądania filmów.
    </p>

    <h2>Uwagi:</h2>
    <p>
        Dane wyświetlane w aplikacji pochodzą z TMDb i są aktualizowane na podstawie dostępnych endpointów. 
        Do działania aplikacja wymaga klucza API, który został poprawnie zaimplementowany w konfiguracji projektu.
    </p>