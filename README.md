# MongoDB Installation and Setup Guide

Follow the steps below to download, install, and set up MongoDB on your system.

## 1. Download MongoDB Community Server

Visit [MongoDB Community Server](https://www.mongodb.com/try/download/community) and download the application.

## 2. Install MongoDB Community Server

Execute the downloaded installer and follow the installation instructions.

## 3. Download MongoDB Shell

Visit [Download MongoDB Shell](https://www.mongodb.com/try/download/shell) and download the MongoDB Shell.

## 4. Environment Variable Setup

Add the following path to your system's environment variables:

```plaintext
C:\Program Files\MongoDB\Server\7.0\bin
```

## 5. Command Prompt Version Check

Open a command prompt and run the following command to check the MongoDB version:

```bash
"C:\Program Files\MongoDB\Server\7.0\bin\mongod.exe" --version
```

## 6. Git Bash Version Check

Open Git Bash and run one of the following commands to check the MongoDB version:

```bash
"C:\Program Files\MongoDB\Server\7.0\bin\mongod.exe" --version
```
or
```bash
mongod --version
```

Make sure that the version displayed matches the MongoDB version you installed.

## 7. Check MongoDB Services

Search for "services" in the Windows search bar, and ensure that the MongoDB service is running. If not, start the service.

## 8. Open MongoDB Shell

Open a command prompt and type the following command to run MongoDB Shell:

```bash
mongosh
```

Now you are ready to work with MongoDB using the installed MongoDB Shell. Enjoy working with MongoDB!
