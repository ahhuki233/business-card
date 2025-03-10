# business-card
business card project from the android developer training
### **How to Run a Kotlin Project**

Follow these steps based on your development environment:

---

## **1. Running a Kotlin Script (Standalone)**
If you have a simple Kotlin script (`.kt` file) and want to run it directly:

### **Using the Command Line**
1. **Install Kotlin Compiler**:  
   - Download and install [Kotlin](https://kotlinlang.org/docs/getting-started.html) if not already installed.
   - Verify the installation:
     ```sh
     kotlin -version
     ```
2. **Run the Kotlin script**:
   ```sh
   kotlinc -script your_script.kt
   ```

---

## **2. Running a Kotlin Project in IntelliJ IDEA (Recommended)**
IntelliJ IDEA is the official IDE for Kotlin.

### **Steps:**
1. **Install IntelliJ IDEA** ([Download Here](https://www.jetbrains.com/idea/download/)).
2. **Create a New Kotlin Project**:
   - Open IntelliJ IDEA.
   - Select **New Project > Kotlin > JVM Application**.
   - Click **Next**, then **Finish**.
3. **Write Kotlin Code** in `Main.kt`:
   ```kotlin
   fun main() {
       println("Hello, Kotlin!")
   }
   ```
4. **Run the Project**:
   - Click the **Run button** (green play icon).
   - Or use the shortcut:
     - **Windows/Linux:** `Shift + F10`
     - **Mac:** `⌘ + R`

---

## **3. Running a Kotlin Project with Gradle (For Larger Projects)**
If your project uses **Gradle**:
1. Open a terminal in your project folder.
2. Run:
   ```sh
   ./gradlew run  # macOS/Linux
   gradlew.bat run  # Windows
   ```

---

## **4. Running Kotlin in VS Code**
If you prefer **VS Code**:
1. Install the **Kotlin Language** extension.
2. Install **Kotlin Compiler** (`kotlinc`).
3. Run your script using:
   ```sh
   kotlinc your_file.kt -include-runtime -d output.jar
   java -jar output.jar
   ```

---

Now you can run your Kotlin project easily based on your setup!

