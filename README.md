# BurpSuitePro Loader & Keygen

A simple guide to install and run BurpSuite Professional with a custom Loader on Linux systems.

## Downloads

1. **BurpSuite Professional:**  
   [Download the latest version](https://portswigger.net/burp/releases#professional)

2. **Java JDK (required to run the loader):**  
   [Download OpenJDK](https://www.openlogic.com/openjdk-downloads)

3. **Loader:**  
   `Loader.jar` (you must obtain this file separately)

---

## Installation Guide (Linux)

Follow these steps to install and run BurpSuitePro:

### 1. Install Java and BurpSuitePro

- Download and install both BurpSuitePro and Java JDK from the above links.
- Ensure Java is installed correctly:

  ```bash
  java -version
  ```

### 2. Place the Loader

- Copy `Loader.jar` to the BurpSuitePro installation directory (e.g., `/opt/BurpSuitePro`):

  ```bash
  sudo cp Loader.jar /opt/BurpSuitePro/
  ```

### 3. Run the Loader

Navigate to the installation directory and run:

```bash
cd /opt/BurpSuitePro
java -jar Loader.jar
```

### 4. Launch Burp

- Click the `Launch` button inside the loader UI.
- You should now see BurpSuite Professional running.

---

## That's it!

If everything was followed correctly:

```text
BurpSuitePro is now running with Loader.
```

Enjoy your security testing!

---

## Author

**rizul0x01**  
[https://github.com/rizul0x01](https://github.com/rizul0x01)
