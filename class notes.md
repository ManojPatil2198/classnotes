# File and Directory Management**
    
    - `ls`  
     List files and directories in the current location.  
        Example: `ls -l` (detailed view), `ls -a` (show hidden files)
        
    - `cd`  
        Change directory.  
        Example: `cd /path/to/directory`
        
    - `pwd`  
        Print the current working directory.
        
    - `mkdir`  
        Create a new directory.  
        Example: `mkdir new_folder`
        
    - `rmdir`  
        Remove an empty directory.
        
    - `rm`  
        Remove files or directories.  
        Example: `rm file.txt`, `rm -r folder` (recursively delete)
        
    - `cp`  
        Copy files or directories.  
        Example: `cp source.txt destination.txt`
        
    - `mv`  
        Move or rename files or directories.  
        Example: `mv old_name.txt new_name.txt`
        
    
    ---
    
# .File Viewing and Editing
    
    - `cat`  
        Display the content of a file.  
        Example: `cat file.txt`
        
    - `less`  
        View file content one page at a time.  
        Example: `less file.txt`
        
    - `nano`  
        Edit a file in the Nano text editor.  
        Example: `nano file.txt`
        
    - `vim`  
        Open a file in the Vim editor.  
        Example: `vim file.txt`
        
    - `head` / `tail`  
        Display the first/last lines of a file.  
        Example: `head -n 10 file.txt`, `tail -n 10 file.txt`
        
    
    ---
    
# File Permissions
    
    - `chmod`  
        Change file permissions.  
        Example: `chmod 755 file.txt`
        
    - `chown`  
        Change file ownership.  
        Example: `chown user:group file.txt`
        
    
    ---
    
# Disk Usage**
    
    - `df`  
        Show disk space usage.  
        Example: `df -h` (human-readable format)
        
    - `du`  
        Estimate file or directory size.  
        Example: `du -sh folder/`
        
    
    ---
    
# Process Management**
    
    - `ps`  
        View running processes.  
        Example: `ps aux`
        
    - `top` / `htop`  
        Monitor system performance and running processes.
        
    - `kill`  
        Terminate a process by PID.  
        Example: `kill 1234`
        
    - `killall`  
        Kill all processes by name.  
        Example: `killall firefox`
        
    
    ---
    
# . Networking**
    
    - `ping`  
        Check network connectivity.  
        Example: `ping google.com`
        
    - `ifconfig` / `ip`  
        View or configure network interfaces.  
        Example: `ip a`
        
    - `curl`  
        Transfer data from or to a server.  
        Example: `curl http://example.com`
        
    - `wget`  
        Download files from the web.  
        Example: `wget http://example.com/file.zip`
        
    
    ---
    
# System Information**
    
    - `uname`  
        Display system information.  
        Example: `uname -a`
        
    - `uptime`  
        Show how long the system has been running.
        
    - `who`  
        See who is logged in.
        
    - `hostname`  
        Display or set the system hostname.
        
    
    ---
    
# Searching**
    
    - `find`  
        Search for files or directories.  
        Example: `find /path -name file.txt`
        
    - `grep`  
        Search text in files.  
        Example: `grep "search_term" file.txt`
        
    
    ---
    
# Package Management**
    
    - **For Debian/Ubuntu**:  
        `apt update`, `apt install`, `apt remove`  
        Example: `sudo apt install package_name`
        
    - **For Red Hat/CentOS**:  
        `yum install`, `yum remove`  
        Example: `sudo yum install package_name`
        
    - **For Arch Linux**:  
        `pacman -S package_name`
        
    
    ---
# Archive and Compression**
    
    - `tar`  
        Create or extract tar archives.  
        Example: `tar -czvf archive.tar.gz folder/`
        
    - `zip` / `unzip`  
        Compress or extract ZIP files.  
        Example: `zip archive.zip file.txt`, `unzip archive.zip`
        
    ****
___
16-1-2025 
stpes for azure devops sign up-
first up on go to ...dev.azure.com/manojpatil2198
start  free with **github**
sign up with github

***two piplines in azure devops 
***1-build 
2-Deployment

# Checkout the video below for Day1

[![Course Introduction](https://img.youtube.com/vi/ME06qJ2VeXA/sddefault.jpg)](https://youtu.be/ME06qJ2VeXA "https://youtu.be/ME06qJ2VeXA")

## What is Cloud Computing?

To run an application, you must purchase computing, storage, and hardware. Cloud computing minimizes these upfront expenses, and you can rent or lease hardware from cloud providers such as AWS/Azure/GCP.

![image](https://github.com/piyushsachdeva/AzureDevOps-Zero-to-Hero/assets/40286378/d3e3c678-760f-4b3f-bc31-2817634d1de6)

**Cloud Computing aims at**

![image](https://github.com/piyushsachdeva/AzureDevOps-Zero-to-Hero/assets/40286378/05b2bcf2-d8af-4814-a8e0-e2383548a0b0)

## IaaS VS PaaS VS SaaS

![image](https://github.com/piyushsachdeva/AzureDevOps-Zero-to-Hero/assets/40286378/19b803a8-45be-4f30-b32f-aa5be6c601d3)

## Shared Responsibility Model in Azure

![image](https://github.com/piyushsachdeva/AzureDevOps-Zero-to-Hero/assets/40286378/fd327641-f690-4d98-963c-8afa823d869a)

## Traditional Build and Deployment workflow

![image](https://github.com/piyushsachdeva/AzureDevOps-Zero-to-Hero/assets/40286378/51690599-927b-437e-b525-61e3fe4b03f1)

## What is the Waterfall model?

![image](https://github.com/piyushsachdeva/AzureDevOps-Zero-to-Hero/assets/40286378/6a6bd063-8586-4911-a9a2-76be3435a659)

## What were the challenges with the waterfall model?

![image](https://github.com/piyushsachdeva/AzureDevOps-Zero-to-Hero/assets/40286378/24157bd9-191a-409a-80fb-7b0474531500)

## What is Agile

![image](https://github.com/piyushsachdeva/AzureDevOps-Zero-to-Hero/assets/40286378/45cbf236-2254-4332-b1a7-3370e5177a77)

## What is DevOps, and why does it matter?

![image](https://github.com/piyushsachdeva/AzureDevOps-Zero-to-Hero/assets/40286378/5e199e8e-15c1-4ba6-8d75-dcf8dd4ce706)

## What is Azure DevOps 🤷‍♂️

Azure DevOps is a suite of services that allows you to implement end-to-end DevOps in your organization. 
It includes services such as Azure Repos, Boards, Wikis, Build and Release pipelines, Test plans, and Artifacts.



### **Relative Path**

- **Definition**: A relative path specifies the location of a resource relative to the current file or directory.
- **Usage**: Often used when linking files within the same project or directory structure.
- **Format**:
    - Starts with `./`, `../`, or directly with the file/directory name.
    - Examples:
        - `./styles.css` – refers to a file in the same directory.
        - `../images/logo.png` – goes up one directory level and then into the `images` directory.
        - `scripts/main.js` – refers to a file in the `scripts` folder, assuming the folder is in the same directory as the current file.
- **Pros**:
    - Portable within the project structure.
    - Easier to maintain when moving a project to a different location.

---

### **Absolute Path**

- **Definition**: An absolute path specifies the complete location of a resource from the root of the file system or website.
- **Usage**: Used when the resource location is fixed or needs to be accessed from anywhere.
- **Format**:
    - Starts with a `/` (for website root) or a protocol like `http://` or `https://`.
    - Examples:
        - `/assets/images/logo.png` – refers to the `logo.png` file located in the `assets/images` directory from the root of the website.
        - `https://example.com/scripts/main.js` – specifies the full URL of the resource.
- **Pros**:
    - Always points to the same location, regardless of the file's location.
    - Useful for external resources or when the resource location doesn't change.

---

### **Key Differences**

| Feature            | Relative Path                              | Absolute Path                                 |
| ------------------ | ------------------------------------------ | --------------------------------------------- |
| **Starting Point** | Relative to the current file's location    | Starts from the root or includes the full URL |
| **Portability**    | Changes if the file is moved               | Always points to the same location            |
| **Use Case**       | Internal resources within the same project | External or fixed resources                   |
|                    |                                            |                                               |

---
### **what is page object model (POM)
   
**The Page Object Model (POM) is a design pattern widely used for creating automated test frameworks. 
It helps create an abstraction between the web application's UI and the test scripts, promoting maintainability and scalability.

**In JavaScript, POM is typically implemented using tools like WebDriverIO, Protractor, Playwright, or Puppeteer.
Below is an example of how to implement a simple Page Object Model in JavaScript using WebDriverIO.
### **what is selectors
In JavaScript, **selectors** are used to target and manipulate elements in the Document Object Model (DOM). 
They allow developers to select elements on a web page based on attributes like their ID, class, tag name, or other characteristics.
These are commonly used with methods provided by the DOM API, such as those in `document` or through libraries like jQuery.


### What is helper ts
In software development, particularly in **TypeScript (TS)**, a "helper" is generally a file, function, or module 
that provides reusable utility logic to make code cleaner and more maintainable.
A **`helper.ts`** file typically contains utility functions, constants, or other shared logic used across multiple parts of an application.

### Common Usage of `helper.ts`

1. **Utility Functions**  
    Functions that perform common operations like formatting dates, numbers, strings, or other reusable tasks.
    
    typescript
    
    CopyEdit
    
    `// helper.ts export const formatDate = (date: Date): string => {     return date.toISOString().split('T')[0]; };  export const capitalize = (text: string): string => {     return text.charAt(0).toUpperCase() + text.slice(1).toLowerCase(); };`
    
2. **Constants**  
    A place to define reusable constants like default configurations or environment settings.
    
    typescript
    
    CopyEdit
    
    `// helper.ts export const API_URL = "https://api.example.com"; export const DEFAULT_TIMEOUT = 5000; // in milliseconds`
    
3. **Shared Logic**  
    Abstracted pieces of code that might not fit well into a specific feature module.
    
    typescript
    
    CopyEdit
    
    `// helper.ts export const calculatePercentage = (value: number, total: number): number => {     return (value / total) * 100; };`
    

### Why Use a `helper.ts` File?

- **Avoid Duplication:** Keeps logic reusable instead of duplicating it in different parts of the code.
- **Improved Readability:** Keeps core code clean and easier to understand by abstracting repetitive logic.
- **Organization:** Groups similar utility functions or constants in one place.

### Best Practices

1. **Keep It Small:** Avoid letting the `helper.ts` file become too large or overgeneralized. If it grows too much, consider splitting it into smaller, feature-specific files.
    - E.g., `dateHelpers.ts`, `stringHelpers.ts`, `mathHelpers.ts`.
2. **Naming Conventions:** Use descriptive names for the file and the exported functions.
3. **Type Safety:** Use TypeScript features like interfaces and type annotations to ensure the helpers are type-safe.
___
### **1. Enum (Enumerations)**
    
    **Enums** are used to define a set of named constants, often for representing a collection of related values. Enums make your code more readable and maintainable.
    
    #### Example in TypeScript:
    
    typescript
    
    CopyEdit
    
    `enum Direction {   Up = 1,   Down,   Left,   Right }  let move: Direction = Direction.Up; // Assign a specific enum value console.log(move); // Output: 1 console.log(Direction[1]); // Output: "Up"`
    
    - **Use Case**: Useful for defining a finite set of possible values (e.g., days of the week, directions, statuses).
    - **Auto-increment**: By default, enums start from `0` and increment for subsequent members unless explicitly set.
    
    In plain JavaScript, you can achieve similar functionality using **objects**:
    
    javascript
    
    CopyEdit
    
    `const Direction = {   Up: 1,   Down: 2,   Left: 3,   Right: 4 };  let move = Direction.Up; console.log(move); // Output: 1`
    
    ---
### Interface**
    
    An **interface** in TypeScript is used to define the structure of an object, specifying what properties and methods an object should have. It doesn't exist in pure JavaScript but is invaluable for type-checking in TypeScript.
    
    #### Example in TypeScript:
    
    typescript
    
    CopyEdit
    
    `interface Person {   name: string;   age: number;   greet(): void; }  const user: Person = {   name: "Alice",   age: 25,   greet() {     console.log("Hello!");   } };  user.greet(); // Output: "Hello!"`
    
    - **Use Case**: Interfaces are used to define contracts for objects or classes, ensuring consistency in code.
    
    ---
    
### . Type**
    
    A **type** in TypeScript is a way to define custom types. It can represent a union, intersection, or a more complex combination of types. `type` is more versatile than `interface` and can be used for things beyond object structures.
    
    #### Example in TypeScript:
    
    typescript
    
    CopyEdit
    
    `// Defining a type for a union type Status = "success" | "failure" | "pending";  let currentStatus: Status = "success"; // Valid // currentStatus = "error"; // Error: not assignable to type 'Status'  // Defining a type for an object type Point = {   x: number;   y: number; };  const point: Point = { x: 10, y: 20 };`
    
    #### Differences Between `type` and `interface`:
    
    1. **Extensibility**: Interfaces can be extended (merged) using `interface`, but `type` cannot.
        
        typescript
        
        CopyEdit
        
        `interface A { prop: string; } interface A { anotherProp: number; } // Merges properties  type B = { prop: string; }; // type B = { anotherProp: number; }; // Error: Cannot redeclare`
        
    2. **Complex Combinations**: `type` allows unions, intersections, and mapped types.
        
        typescript
        
        CopyEdit
        
        `type Result = { success: true } | { success: false; error: string };`
___
 

# **`for...of`**

- **Purpose**: Iterates over the **values** of iterable objects such as arrays, strings, Maps, Sets, etc.
- **Use Case**: Use it when you want to work with the actual **values** in an iterable.

#### Example with an Array:

javascript

CopyEdit

`const fruits = ["apple", "banana", "cherry"];  for (const fruit of fruits) {   console.log(fruit); // Output: "apple", "banana", "cherry" }`

#### Example with a String:

javascript

CopyEdit

`const name = "Alice";  for (const char of name) {   console.log(char); // Output: "A", "l", "i", "c", "e" }`

---

# **`for...in`**

- **Purpose**: Iterates over the **keys (property names)** of an object or array.
- **Use Case**: Use it when you want to work with the **keys** of an object or array. It's generally used with objects, but it can be used with arrays (though it's not recommended).

#### Example with an Object:

javascript

CopyEdit

`const person = { name: "Alice", age: 25 };  for (const key in person) {   console.log(key);          // Output: "name", "age"   console.log(person[key]);  // Output: "Alice", 25 }`

#### Example with an Array (Not Recommended):

javascript

CopyEdit

`const fruits = ["apple", "banana", "cherry"];  for (const index in fruits) {   console.log(index);        // Output: "0", "1", "2" (indexes as strings)   console.log(fruits[index]); // Output: "apple", "banana", "cherry" }`

Using `for...in` with arrays is discouraged because it also iterates over **inherited properties** if they exist, which might lead to unexpected behavior.

---

### Key Differences

|Feature|`for...of`|`for...in`|
|---|---|---|
|**Purpose**|Iterates over values in an iterable.|Iterates over keys (property names).|
|**Works With**|Arrays, strings, Maps, Sets, and other iterables.|Objects (and arrays, but not recommended).|
|**Output**|Value of each element.|Key or index of each element.|
|**Best Use Case**|When working with iterables.|When working with object properties.|
|**Inherited Props**|Does not iterate over inherited properties.|Iterates over inherited properties.|
# What is json?

**JSON** stands for **JavaScript Object Notation**. It is a lightweight data-interchange format that is easy for humans to read and write and easy for machines to parse and generate. 
it is based on JavaScript syntax, JSON is a language-independent format and is widely used across programming languages.

### Key Features of JSON:

1. **Human-readable**: The syntax is simple and clean, making it easy to understand.
2. **Lightweight**: JSON uses a minimal amount of text.
3. **Structured**: It organizes data in a logical, hierarchical way.
4. **Language-independent**: JSON is supported by almost every major programming language.
5. **Data Exchange**: Frequently used for transferring data between a client (like a web browser) and a server.

---

### JSON Syntax:

JSON represents data as key-value pairs and supports the following data types:

1. **String**: Enclosed in double quotes (`" "`)
2. **Number**: Integer or floating-point numbers
3. **Boolean**: `true` or `false`
4. **Array**: Ordered list of values enclosed in square brackets (`[ ]`)
5. **Object**: Unordered collection of key-value pairs enclosed in curly braces (`{ }`)
6. **Null**: Represents an empty value (`null`)

---

### Example of JSON:

json

CopyEdit

`{   "name": "Alice",   "age": 25,   "isStudent": false,   "courses": ["Math", "Science", "History"],   "address": {     "street": "123 Main St",     "city": "New York",     "zip": "10001"   } }`

- **Object**: The whole JSON data is an object.
- **Key-Value Pair**: `"name": "Alice"` is a key-value pair.
- **Array**: `"courses": ["Math", "Science", "History"]` is an array of strings.
- **Nested Object**: `"address": { ... }` is a nested object.

---

### Applications of JSON:

1. **Web APIs**: JSON is commonly used to send and receive data between clients and servers in REST APIs.
2. **Configuration Files**: JSON is often used for application configuration files.
3. **Data Storage**: Some databases like MongoDB use JSON-like formats to store data.
4. **Serialization**: Convert data structures into JSON format to transmit or save them.
_______________________________________________________________________
**Object destructuring** in JavaScript is a concise way to extract properties from objects and assign them to variables.
It allows you to unpack values from objects into individual variables using a simple and readable syntax.

---

### **Basic Syntax**

javascript

CopyEdit

`const { key1, key2 } = object;`

- `key1` and `key2` are the property names of the object.
- The variables `key1` and `key2` will contain the corresponding values of those properties.

---

### **Examples**

#### 1. **Basic Destructuring**

javascript

CopyEdit

`const person = {   name: "Alice",   age: 30 };  const { name, age } = person; console.log(name); // Output: "Alice" console.log(age);  // Output: 30`

---

#### 2. **Renaming Variables**

You can assign a property to a variable with a different name.

javascript

CopyEdit

`const person = {   name: "Alice",   age: 30 };  const { name: fullName, age: years } = person; console.log(fullName); // Output: "Alice" console.log(years);    // Output: 30`

---

#### 3. **Default Values**

You can assign default values to variables if the property doesn't exist in the object.

javascript

CopyEdit

`const person = {   name: "Alice" };  const { name, age = 25 } = person; console.log(name); // Output: "Alice" console.log(age);  // Output: 25 (default value)`

---

#### 4. **Nested Destructuring**

You can destructure properties from nested objects.

javascript

CopyEdit

`const person = {   name: "Alice",   address: {     city: "New York",     zip: "10001"   } };  const { name, address: { city, zip } } = person; console.log(city); // Output: "New York" console.log(zip);  // Output: "10001"`

---

#### 5. **Rest Properties**

You can collect remaining properties into a separate object using the **rest operator** (`...`).

javascript

CopyEdit

`const person = {   name: "Alice",   age: 30,   profession: "Developer" };  const { name, ...rest } = person; console.log(name); // Output: "Alice" console.log(rest); // Output: { age: 30, profession: "Developer" }`

---

### **Use Cases of Object Destructuring**

1. **Function Parameters**: Destructure object properties directly in function parameters.
    
    javascript
    
    CopyEdit
    
    ``function greet({ name, age }) {   console.log(`Hello, ${name}. You are ${age} years old.`); }  const person = { name: "Alice", age: 30 }; greet(person); // Output: "Hello, Alice. You are 30 years old."``
    
2. **Accessing API Responses**: Extract specific data from a response object.
    
    javascript
    
    CopyEdit
    
    `const response = {   status: 200,   data: { user: "Alice", age: 30 } };  const { status, data: { user } } = response; console.log(status); // Output: 200 console.log(user);   // Output: "Alice"`
    
3. **React Props**: Commonly used to destructure props in React components.
    
    javascript
    
    CopyEdit
    
    `function Component({ title, description }) {   return <h1>{title}: {description}</h1>; }`
    

---

### **Summary**

- **Object destructuring** is a powerful and concise way to work with objects.
- It can simplify code when extracting multiple properties.
- It works well with default values, renaming variables, nested structures, and the rest operator.
____
# what is swagger file in API

- A **Swagger file**, also known as an **OpenAPI Specification (OAS)** file, is a standardized format for describing RESTful APIs. It serves as a blueprint that defines how an API works, including its endpoints, request/response structures, parameters, and authentication methods.
    
    Swagger files are typically written in either **JSON** or **YAML** and are used to provide a clear, machine-readable description of an API. This enables both humans and machines to understand and interact with the API effectively.
    
    ### Key Components of a Swagger File:
    
    1. **OpenAPI Version**: Specifies the version of the OpenAPI Specification being used.
        
        yaml
        
        CopyEdit
        
        `openapi: 3.0.0`
        
    2. **Info**: Contains metadata about the API, such as the title, version, and description.
        
        yaml
        
        CopyEdit
        
        `info:   title: Sample API   description: A sample API to demonstrate Swagger   version: 1.0.0`
        
    3. **Servers**: Defines the base URL(s) for the API.
        
        yaml
        
        CopyEdit
        
        `servers:   - url: https://api.example.com/v1`
        
    4. **Paths**: Lists the available API endpoints and their methods (e.g., GET, POST, PUT, DELETE).
        
        yaml
        
        CopyEdit
        
        `paths:   /users:     get:       summary: Get all users       responses:         200:           description: Successful response`
        
    5. **Components**: Reusable objects such as schemas, parameters, and security schemes.
        
        yaml
        
        CopyEdit
        
        `components:   schemas:     User:       type: object       properties:         id:           type: integer         name:           type: string`
        
    6. **Security**: Details about authentication methods (e.g., API keys, OAuth2).
        
        yaml
        
        CopyEdit
        
        `security:   - apiKeyAuth: []`
        
    
    ### Benefits of a Swagger File:
    
    - **Documentation**: Provides automatically generated, user-friendly API documentation.
    - **Testing**: Tools like Swagger UI or Postman can use the Swagger file to test endpoints without manual configuration.
    - **Code Generation**: Developers can generate server stubs or client SDKs in various programming languages.
    - **Standardization**: Ensures consistency across API design and communication.
    
    Swagger is part of the **OpenAPI Initiative**, and although "Swagger" refers to tools provided by SmartBear (e.g., Swagger Editor, Swagger UI), the underlying specification itself is now called OpenAPI Specification.
    
    4o