# AI-Based-RecommenderApp
This is a simple Java-based recommender system project using Apache Mahout and Maven.

## 📁 Project Structure

recommenderapp/
├── src/
│ └── main/
│ └── java/
│ └── com/
│ └── recommender/
│ └── app/
│ └── RecommenderApp.java
├── pom.xml

## ⚙️ Prerequisites

- Java JDK 17 or higher (e.g. JDK 22)
- Maven 3.8+ (Apache Maven)
- IntelliJ IDEA or VS Code
- Internet connection (for Maven to download dependencies)

## 🚀 How to Run (in IntelliJ)

1. Open IntelliJ IDEA.
2. Click **Open** and select the project folder.
3. IntelliJ will auto-detect the `pom.xml` and import the project as a Maven project.
4. If not imported, right-click `pom.xml` → **Add as Maven Project**.
5. Wait for indexing and Maven dependency resolution to complete.
6. Open `RecommenderApp.java`.
7. Right-click on the file → **Run 'RecommenderApp.main()'**.

## 🐛 Troubleshooting

- ❌ **Maven not found?**
  - Make sure it's added to the `Path` environment variable.
- ❌ **JAVA_HOME not set?**
  - Set `JAVA_HOME` to your JDK installation folder (e.g. `C:\Program Files\Java\jdk-22`)
- ❌ **Dependencies not resolving?**
  - Use: `mvn clean install -U` in terminal.

## 📚 Dependencies

```xml
<dependency>
    <groupId>org.apache.mahout</groupId>
    <artifactId>mahout-core</artifactId>
    <version>0.9</version>
</dependency>
