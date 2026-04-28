### 🔍 Simple Search Engine

A Java-based mini search engine that includes a **Web Crawler** and a **Search Engine** with a JSP/Servlet web interface. The crawler collects data from the web and indexes it, while the search engine provides a UI for users to search through the indexed data.

-----

### 📁 Project Structure

```
SimpleSearchEngine/
├── WebCrawler/    # Java-based web crawler for collecting data
└── SearchEngine/  # JSP-based search UI built with Servlets
```

-----

### 🚀 Features

✅ **Web Crawler (WebCrawler)**

  * Starts crawling from a seed URL (currently roadmap.sh)
  * Fetches and parses HTML content
  * Extracts and stores textual data
  * Can be configured for crawling depth and page limits

✅ **Search Engine (SearchEngine)**

  * Accepts search queries from the user
  * Matches queries with indexed data
  * Displays results in a clean JSP-based interface

-----

### 🛠️ Technologies Used

  * **Java** (Core logic)
  * **JSP / Servlets** (Web interface)
  * **Apache Tomcat** (Web server)
  * **MySQL** (For storing the index)
  * **Maven** (Dependency management)
  * **HTML / CSS** (Frontend)

-----

### ⚙️ Setup Instructions

**🔧 Prerequisites**

Make sure you have the following installed:

  * Java JDK 8 or higher
  * Apache Tomcat 9+
  * Maven
  * MySQL (optional, for storing the index)
  * An IDE like IntelliJ IDEA or Eclipse

-----

### 🗺️ Roadmap

The project is currently in its early stages. Here are the plans for future updates:

  * **Current State:** The web crawler is limited to crawling a single specified site (`roadmap.sh`).
  * **Future Updates:**
      * **Multi-Site Crawling:** The search results will be expanded to include content from multiple websites.
      * **History Feature:** A user search history feature will be added to allow users to view their previous queries.
