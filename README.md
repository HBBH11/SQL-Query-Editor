# ✨ SQL Query Editor

A professional web-based SQL editor built with Streamlit and Supabase, designed for interactive SQL learning and practice.

![SQL Query Editor Interface](https://github.com/user-attachments/assets/7471d5cb-28d6-4d70-8b2a-dce775b4603c)

## 🌟 Features

### 🚀 Core Functionality
- 💻 Interactive SQL editor with syntax highlighting
- ⚡ Real-time query validation and execution
- 📝 Immediate feedback on query correctness
- 📚 Question bank with practice problems
- 🛡️ Secure query execution environment
- 🎨 Professional user interface with modern styling

### 🔧 Technical Components

#### 🖥️ User Interface
- 📝 Professional SQL editor with syntax highlighting
- 📊 Question selector dropdown
- ⌨️ Query input text area
- 🎯 Test and Submit buttons
- 📈 Result display area
- 🎨 Custom CSS styling for modern appearance

#### ⚙️ Key Functions

**🔄 Query Processing**
- 🔍 `compare_query_results()`: Compares user's query results with solutions
- 🛡️ `is_safe_query()`: Security validation for potentially harmful queries
- 🎨 `highlight_sql()`: SQL syntax highlighting
- 📋 `normalize_query()`: Query standardization for comparison
- ⚡ `execute_query()`: Secure query execution through Supabase
- ✅ `is_query_correct()`: Solution verification
- 📚 `fetch_questions()`: Question retrieval from database

**🔒 Security Features**
- 🛡️ Comprehensive query validation
- 👤 User-specific view creation
- 🔐 Safe query execution via RPC calls
- ⚔️ Prevention of harmful operations

**📡 Session Management**
- 🔑 Unique user ID generation
- 📝 Query history tracking
- 💾 State persistence during session

## 🛠️ Technology Stack

- 🌐 **Streamlit**: Web interface framework
- 📊 **Supabase**: Database operations
- 🐼 **Pandas**: Data manipulation and comparison
- 🔑 **UUID**: User identification

## 📦 Setup

1. Clone the repository
2. Install dependencies:
```bash
pip install streamlit supabase pandas uuid
```
3. Configure Supabase:
   - Create a Supabase project
   - Replace `url` and `key` with your Supabase credentials
   - Set up your database schema

## 🔄 Usage Flow

1. 📝 Select a practice question from the dropdown
2. ⌨️ Write your SQL query in the editor
3. 🔍 Test the query to see immediate results
4. ✅ Submit your final answer
5. 📊 Review feedback and explanations

## ⚠️ Error Handling

- 🔄 Comprehensive try-catch implementation
- 💬 User-friendly error messages
- 🛟 Graceful failure handling
- ✅ Multi-level data validation

## 🎨 Styling

- 🖌️ Custom CSS for modern interface
- 📱 Responsive design elements
- 🎭 Professional color scheme
- 📝 Enhanced typography
- 🔘 Interactive button states
- 📊 Clean table formatting

## 📚 Educational Benefits

- 🏫 Safe environment for SQL practice
- ⚡ Immediate feedback system
- 💼 Professional development interface
- 📖 Structured learning approach
- 🔄 Interactive query testing

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 Note

Remember to update the Supabase credentials (`url` & `key`) and implement your own database structure before deploying.



## 📊 Performance Metrics

- ⚡ Query execution time < 2s
- 🔄 Real-time syntax highlighting
- 📦 Minimal memory footprint
- 🚀 Fast page load times

## 🔗 Quick Links

- 📚 [Documentation](#)
- 💻 [API Reference](#)
- 🐛 [Issue Tracker](#)
- 💬 [Community Forum](#)
